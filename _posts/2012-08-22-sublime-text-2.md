---
layout: post
striphtml: true
title: Kom igång med Sublime Text 2
description: Tips på plugins och funktioner i editorn Sublime Text 2
image: /img/sublime.png
---

Har du inte provat på texteditorn Sublime Text 2 ännu så ska du göra det med en gång. En fulländad cross-platform-editor med alla möjliga features såsom Textmate bundles/teman, multiselection, inbyggd pakethanterare m.m.

## Plugins ##
Nedan finner du plugins jag tycker är användbara i min frontendutveckling (alla plugins hittar du i Package Control): 

### [Package control](http://wbond.net/sublime_packages/package_control) ###
Pakethanterare med bundles, plugins, buildsystem m.m.

### Soda ###
Soda gör Sublime's UI lite behagligare. Finns i mörkt/ljust och olika utseenden på tabbarna.

### <del>ZenCoding</del> Emmet ###
Förenklar prototypande av HTML. Generera t.ex en lista genom att skriva

```
ul>li[class=list-$]*5>a[href=http://url.com]{Linktext}
```

I.o.m Emmet förenklas även skrivandet av CSS. Läs mer på [Github](https://github.com/sergeche/emmet-sublime). 

### SublimeCodeIntel ###
En portning av Komodo's autocomplete till Sublime där du får autocomplete för de flesta språk. 

### Gist ###
Skapa publika och privata gists på github genom några knapptryck. Du kan även uppdatera existerande gists via Sublime.

### SidebarEnhancements ###
Lägger till fler trevliga val i contextmenyn. 

### EncodingHelper ###
Visar aktuella teckenkodningen i statusraden samt möjliggör en konvertering mellan en rad olika uppsättningar.

### JSHint ###
Eventuella fel i JavaScriptkoden visas i consolen vid build (kompletteras gärna med paketet SublimeOnSaveBuild som kör en build på filen när den sparas).

## Andra användbara features ##

* Split-view vertikalt eller horizontellt
* "Goto anything" - sök på metodnamn eller filnamn i projektet med &#x2318; + P
* Kom åt metoder och properties i klasser på den aktuella filen med &#x2318; + R
* Med multiple cursors kan du redigera text på flera ställen samditigt (&#x2318; + klick)
* Sublime har stöd för Textmate-teman out of the box
* Vintage mode - använd dig av [vim](http://www.vim.org/)'s kommandoläge inuti Sublime (är själv ingen vim-fantast, men det finns säkert någon som gillar detta)

NetTuts gjorde en summering med lite tips&trix i Sublime som kan också kan vara värda att spana in: [http://net.tutsplus.com/tutorials/tools-and-tips/sublime-text-2-tips-and-tricks/](http://net.tutsplus.com/tutorials/tools-and-tips/sublime-text-2-tips-and-tricks/)

Du kommer med största sannolikhet hitta andra features som du gillar! 

Sublime Text 2 laddas ner helt gratis på [http://www.sublimetext.com/2](http://www.sublimetext.com/2)