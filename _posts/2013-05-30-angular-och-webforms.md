---
layout: post
title: AngularJS och .NET WebForms
striphtml: true
description: Hur du får AngularJS att fungera med .NET WebForms
---

Igår stötte jag på ett problem med .NET WebForms som irriterade mig väldigt mycket. När man bygger webbplatser med den gamla tekniken WebForms innebär det att hela sidan har ett form-element runt content på sidan och åtgärder gör en POST till sig själv och sedan hanteras logik på serversidan. Du kan helt enkelt inte ha fler än ett formulär-element på din sida. 

Problemet uppstod när jag hade implementerat en klientapplikation skriven med Javascript-ramverket [AngularJS](http://angularjs.org/) och upptäckte att inga "[postbacks](http://www.evagoras.com/2011/02/10/how-postback-works-in-asp-net/)" fungerade på webbplatsen. 

Jag hittade dock att Angular [har en check](https://github.com/angular/angular.js/blob/master/src/ng/directive/form.js#L269) i sitt form-directive som kollar på action-attributet om det inte är satt, isåfall körs **event.preventDefault** som förhindrar .NET att göra någon form av logik med formuläret. 

Genom att sätta "?" som action på .NET's omslutande form-element blir vi av med detta problem.