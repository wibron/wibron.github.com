---
layout: post
title: Markdown + Dropbox = Fantasticbookmarks
striphtml: true
description: Fantasticbookmarks är en tjänst som kombinerar Markdown med Dropbox
---

På luciadagen bjöd [Tictail](http://tictail.com/) in till ett riktigt trevligt event som hette [Lucia Hack Night](https://www.facebook.com/events/446701605378273/) där flera utvecklare, designers och andra kreativa människor samlades hos Tictail och skapade olika tjänster eller koncept.

Jag och [Dan](http://dancarlberg.tumblr.com/) från [Bloglovin'](http://bloglovin.com/) teamade ihop oss och kom på idén att kombinera [Markdown](http://daringfireball.net/projects/markdown/) med Dropbox och i användarens mapp skapa en markdown-fil med länkar som man finner är intressanta. Resultatet blev det något oklara namnet **Fantastic bookmarks**.

På sajten presenterar vi enkelt länkarna som användaren har fyllt i inuti sin markdown-fil. 

I och med att syntaxen i Markdown är väldigt enkel att lära sig, och vi skickar med en exempelmall till användaren när denne autentiserar sig på sajten så det blir lätt att komma igång med bokmärkandet.

Tekniken bakom sajten är Ruby (Rails), Sass och Dropbox's API.

Vill du testa tjänsten hittar du den på [fantasticbookmarks.herokuapp.com](http://fantasticbookmarks.herokuapp.com) där den är i otroligt tidigt (men fungerande) beta-stadie.