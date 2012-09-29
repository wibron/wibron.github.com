---
layout: post
title: Remote-debugging med iOS6 och Safari
striphtml: true
description: Hur du får igång remote-debugging med Safari i iOS6 samt Safari 6 i OS X
---

För ett tag sedan släppte Adobe sitt verktyg <del><a href="http://labs.adobe.com/downloads/shadow.html">Shadow</a> </del> <a href="http://html.adobe.com/edge/inspect/">Edge Inspect</a> som hjälpte oss utvecklare att debugga webbplatser enklare på många mobila enheter. Det fungerade rätt okej till och från, men jag har själv haft problem med att få inspectorn att hänga med stundtals. 

I och med iOS6 har vi fått en ny möjlighet att debugga webbplatser på våra iPhone's och iPad's. För att enkelt komma igång gör man på följande sätt: 

Slå på Web Inspector på din enhet genom att gå till Settings -> Safari -> Advanced. Koppla sedan in enheten till din Mac med USB och den kommer dyka upp under &quot;Develop&quot; i Safari. Nu kan du logga meddelanden, skicka alerts, byta CSS-properties på element m.m på sajten du besöker på din enhet. Superenkelt.

__Uppdatering: __
Adobe släppte Shadow från beta-stadiet och bytte namn på produkten till Adobe Edge Inspect. Tjänsten är inte längre gratis utan kräver numer en prenumerering på Creative Cloud. 