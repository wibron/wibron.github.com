---
layout: post
title: Enkla tips som snabbar upp din sajt
striphtml: true
description: Ett par enkla tips som gör att din sajt laddar snabbare
---

Ingen vill sitta och vänta länge för att komma åt innehåll på en webbplats, eller hur? Tänkte därför ta och dela med mig av lite tips som jag anser är riktigt simpla och tar inte lång tid att implementera. Dessa tips är ingen direkt nyhet, men alltid kan det vara någon som inte har tänkt på dessa innan.

* Till att börja med, se över antalet assets på sidan och kolla hur stor första requesten är och hur lång tid det tar till att allt är nedladdat. Du kollar det enklast i Chrome eller Firefox's developer tools på Network-fliken. Försök att göra så få HTTP-requests som möjligt.  
* Optimera designen om det går. Används onödigt många bildelement för utfyllnad, eller gör de faktiskt ett syfte? Stora tunga bakgrundsbilder kan påverka prestandan rätt rejält. CSS-sprites kan även vara att rekommendera om det finns många små bilder som används för att rita ut grafik. 
* Tänk mobile first. Får gå in mer detaljerat på ämnet vid ett annat tillfälle, annars rekommenderas [Luke Wroblewski's bok Mobile First](http://www.abookapart.com/products/mobile-first) som är riktigt läsvärd. 
* Kombinera och minifiera Javascript och CSS. Det finns en skyhög med verktyg där ute för att automatisera detta, bland annat [Grunt](http://gruntjs.com/).
* Ta bort onödig CSS och Javascript om den inte används. Inkludera inte t.ex jQuery om du bara ska lägga till en CSS-klass på ett element. 
* Slå på [Gzip](https://developers.google.com/speed/articles/gzip) på din webbserver som gör att HTTP-responsen komprimeras vid överföringen och resurser laddar snabbare. 
* Sätt korrekta headers. Google har en [bra artikel](https://developers.google.com/speed/docs/best-practices/caching) om detta som du bör läsa.
* Optimera bilder för webben genom t.ex [ImageOptim](http://imageoptim.com/) som helt lossless tar bort onödig metadata från bilder. Du kan vinna rätt mycket på detta och det tar ingen tid alls.
* Servera statiska HTML-filer om möjligt för att minimera lasten på databasen.

Om man har Wordpress som plattform på sin webbplats går dessa tips att lösa rätt enkelt med plugins som t.ex. [W3 Total Cache](http://wordpress.org/extend/plugins/w3-total-cache/) och [WP Super Cache](http://wordpress.org/extend/plugins/wp-super-cache/). 

Har du några fler tips om hur man snabbar upp sin webbplats så får du gärna slänga in en kommentar nedan. 