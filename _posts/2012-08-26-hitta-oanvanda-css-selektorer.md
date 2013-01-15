---
layout: post
striphtml: true
title: Hitta oanvända CSS-selektorer med ucss
description: Hitta oanvänd CSS-kod i ditt projekt med node.js-modulen ucss
---

Jag jobbade på ett rätt stort projekt förut och behövde kika igenom alla css-selektorer för att se hur pass många som verkligen användes, då hittade jag ucss av Opera Software på Github. En enkel node.js-modul som tillåter dig att mappa upp ett par URL:er och en css-fil att göra testet mot. Du får sedan en fullständig rapport på vilka selektorer som ej används.

Värt att notera är att ucss är i skrivande stund i beta-stadiet och man får överseende med att allt inte fungerar helt 100%.

Du hittar [ucss på Github](https://github.com/operasoftware/ucss).
