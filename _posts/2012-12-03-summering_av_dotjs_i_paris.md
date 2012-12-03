---
layout: post
striphtml: true
title: Summering av dotJS i Paris
description: Sammanfattning av mitt besök på Javascript-konferensen dotJS i Paris
---

![Théâtre des Variétés, Paris. Photo by @mauriz](http://svay.com/photos/2012-11-30_dotjs/conference/2012-11-30_10-17-17.jpg)

[dotJS](http://dotjs.eu/) är en ny konferens om Javascript som anordnas av [Sylvain Zimmer](http://twitter.com/sylvinus) och [Thomas Bassetto](http://twitter.com/tbassetto). Just i år var det första gången som dotJS genomfördes, så jag tänkte ta och beskriva min upplevelse jag fick där tillsammans med min vän & kollega [Robert](http://twitter.com/rhubinette). 

---

Till att börja med annonserades inget riktigt schema till konferensen, utan man lockade besökarna endast genom att visa vilka talare som var inbjudna. Ett par rätt stora namn som bl.a. [Addy Osmani (@addyosmani)](http://twitter.com/addyosmani), [Mathias Bynens (@mathias)](http://twitter.com/mathias), [Mr Doob (Ricardo Cabello / @mrdoob)](http://twitter.com/mrdoob) och [Jacob Thornton (@fat)](http://twitter.com/fat) listades på evenemangssidan. 

Detta gjorde att jag och över 600 nyfikna deltagare drog sig till den vackra teatern Théâtre des Variétés i centrala Paris för att lyssna på lite kodsnack och saker därtill.

Konferensen anordnades som sagt i Paris, så det var riktigt kul att uppleva en ny stad samt träffa på folk som man kanske inte annars skulle träffa. Vi träffade även på ett par svenskar där, riktigt kul! 

## Keynotes

Varje talare på dotJS hade cirka 20 minuter på sig att göra sin röst hörd, och ibland var tiden väldigt knapp vilket var rätt trist då de säkert hade mycket mer spännande att berätta om.  

Mathias Bynens rivstartade med att ge många obskyra exempel på hur unicode kan hanteras i Javascript. Om du följer hans blogg så tror jag du har sett det innan, annars kan du läsa [detta](http://mathiasbynens.be/notes/javascript-properties) och [detta](http://mathiasbynens.be/notes/javascript-identifiers) blogginlägg.

Addy Osmani visade även lite tips & tricks i Chrome Developer Tools som många kanske inte känner till. T.ex live edit som innebär att du kan spara lokala JS/CSS-filer direkt från DevTools utan att byta tillbaka till editorn för att göra om ändringarna. För CSS gäller detta endast om man ändrar standardproperties som outputats av CSS:en, ej inline-styles samt styles tillagda med custom selectors. 

Jag blev riktigt glad när Addy även visade att det kommer komma stöd för att spara direkt till Sass-filers originalfiler. När man jobbar med Sass jobbar man oftast i en mängd filer och kompilerar sedan alla filer till en enda CSS-fil, men vid debugging kan det vara lite klurigt att se var en property har deklarerats någonstans. Det har varit möjligt sedan tidigare i Canary Chrome med Sass Source Maps, men nu har möjligheten utvidgats och nu kan man till och med spara ändringarna till varje individuell .scss-fil. Helt fantastiskt.     

Under varje presentation hade alla besökare möjlighet att ställa frågor via Google Moderator som sedan lästes upp av moderatorn och besvarades av talaren efter presentationen var klar. Det fungerade riktigt bra måste jag säga.

Avslutningsvis skulle [Jacob Thornton](@fat) berätta om Open Source och dess historia, men han fick reda på att sin keynote endast skulle vara 20 min lång några dagar innan konferensen så hans presentation fick helt göras om. Jacob gick helt emot strömmen och gjorde konstigt nog hela sin presentation som ett långt dokument i Photoshop med karikatyrsketcher på bl.a. Linus Torvalds, Richard Stallman m.fl. Fantastiskt roligt var det, men hans positiva slutsats som lovades blev inte så jätte positiv utan istället en del negativa saker.

## Workshops

Under lördagen anordnades workshops för att man skulle få labba lite med olika typer av tekniker istället för att sitta och lyssna en hel dag, så det kändes jättelockande att vara med på. 

Flera företag såsom Google, Microsoft, Enyo m.m. höll i workshops om diverese tekniker, men vi valde att gå på Google's som även majoriteten av alla andra deltagare pga bra handledare och intressanta ämnen.

Väl inne på workshopen kunde man välja olika spår, i vårt fall gick det att välja mellan att göra en app i Dart alt. labba med CSS3 3D-animationer. Jag som älskar grafik kände jag att det var rätt enkelt val med CSS3-spåret.

Jag och min kollega Robert försov oss rätt rejält och med lite smått värdelöst lokalsinne lyckades vi ansluta drygt en timme efter att workshopen hade startat, så vi hade missat en hel del i introduktionen. 

CSS3-sektionen hölls av [Martin Görner](http://twitter.com/martingorner) och gick ut på att skapa en roterande fotokub med 6st sidor som animerades. Det var egentligen ingenting nytt för mig, men CSS i allmänhet är så fantastiskt så det är alltid trevligt att finslipa kunskaperna.

Efter en massiv pizzalunch startade spår #2 igång med en introduktion/labb i [AngularJS](https://github.com/angular/angular.js) med skaparna själva. De gick igenom allt rätt noggrant och såg till att alla fick hjälp vid behov, otroligt bra för nybörjare.

Labben i AngularJS gick ut på att skapa en web-app som listade restauranger beroende på ett par parametrar. Det skulle även gå att filtrera på pris/rating och lite annat smått och gott. Problemet kände jag var att instruktörerna skenade iväg i en rätt hög nivå och ett högt tempo som gjorde att en del inte riktigt hängde med i svängarna och hängde med att snappa upp allt som sades samtidigt som man skulle skriva kod. Allt fanns dock nedskrivet i dokumentationen och i labbunderlaget för att man skulle kunna gå igenom det senare, men det hade varit bra om tempot var lite långsammare och själva labben hade kunnat vara lite mer avskalad och simplifierad. 

## Sammanfattning

Det var riktigt härligt att komma ifrån Sverige ett par dagar och kombinera arbete med nöje. Paris är en fantastisk stad och jag vill absolut åka tillbaka dit. Om jag vill besöka dotJS även nästa år? Kanske. Om de skulle fokusera på att ha lite mer keynotes med kodinnehåll och lite mer djupare tekniska saker skulle det bli intressant, nu blev det tyvärr ett par presentationer som inte hade detta ämne som blev lite tråkiga. 