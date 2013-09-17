---
layout: post
striphtml: true
title: Få grepp om Angular $resource
description: Angular's service $resource
---

Om du har jobbat med Angular förut och t.ex kommunicerat mot en WebService/API av något slag har du förmodligen stött på den inbyggda servicen [$http](http://docs.angularjs.org/api/ng.$http). Den gör att du enkelt kan göra GET och POST-requests som oftast behövs vid kommunikationen och är snarlikt jQuery's [$.ajax](http://api.jquery.com/jQuery.ajax/) i utförandet. 

När du har kommunicerat har du antingen lagt dina $http-anrop direkt i controllern eller i en factory/service (för att återanvända koden så mycket som möjligt). Koden kan ha sett ut som följande: 

<script src="https://gist.github.com/wibron/5380d441b6df89282ec0.js">// </script>

Det är egentligen inget fel med detta, men låt säga att du ska kommunicera med ett [RESTful](http://en.wikipedia.org/wiki/Representational_state_transfer) API istället. Då behöver du manuellt ta och specifiera upp t.ex parametrar, GET/PUT/POST/DELETE etc. som behövs för att göra alla olika anrop. 

Istället kan man göra det smidigare för sig och använda Angular's externa service [$resource](http://docs.angularjs.org/api/ngResource.$resource) som inte följer med som standard (nämns knappt i deras egen dokumentation), och för att göra detta behöver du inkludera en till script-tag samt ange ngResource som dependency vid initieringen av din Angular-applikation. 

Personligen tycker jag dokumentationen av $resource var lite klurig att förstå sig på, men provar man på att använda modulen själv så är det egentligen inte så svårt.

Din factory kan du nu istället skriva om till följande: 

<script src="https://gist.github.com/wibron/8cc58b9bdcb7a101d923.js">// </script>

Nu kommer @id att motsvara id't som en URL-parameter, och både GET/POST/PUT m.m kommer automatiskt att vara tillgängliga. För att i detta exemplet anropa API:et från en controller och hämta antingen alla kort eller ett enskilt kort fungerar det på följande sätt: 

<script src="https://gist.github.com/wibron/610921bd270649003920.js">// </script>

Metoden .query() motsvarar en request till /cards utan några parametrar, och .get() skickar med id't (/cards/1). Vill man istället köra en POST får man skapa en ny instans av $resource på följande vis: 

<script src="https://gist.github.com/wibron/0cc58f03fb65b5e0dfd0.js">// </script>

Metoden $save i detta fall motsvarar en POST-request, och cardData är payloaden som skickas med i requesten. Det går även att utöka $resource med egna metoder som motsvarar GET/POST/PUT/DELETE, till exempel vill du kanske ha en .fetch() istället för .query(), då kan du bara mappa om så att .fetch() motsvarar en GET och att den skall returnera en array istället för ett objekt. 

Hoppas att detta inlägg har gjort det lite enklare för någon. 