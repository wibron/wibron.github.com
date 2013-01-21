---
layout: post
striphtml: true
title: Kom igång med Sublime Text 2
description: Tips på plugins och funktioner i editorn Sublime Text 2
image: /img/sublime.png
---

Har du inte provat på texteditorn Sublime Text 2 ännu så ska du göra det med en gång. En fulländad cross-platform-editor med alla möjliga features såsom stöd för Textmate bundles/teman, multipla markeringar, inbyggd pakethanterare med mera.

## Plugins ##
Nedan finner du plugins jag tycker är användbara i min frontendutveckling (alla plugins hittar du i Package Control): 

### [Package control](http://wbond.net/sublime_packages/package_control) ###
Den i princip obligatoriska pakethanteraren till Sublime med alla möjliga bundles, plugins och buildsystem.

### Soda ###
Soda gör Sublime's UI lite behagligare. Finns i mörkt/ljust och olika utseenden på tabbarna.

### Emmet (f.d. ZenCoding) ###
Förenklar prototypande av HTML. Generera t.ex en lista genom att skriva

```
ul>li[class=list-$]*5>a[href=http://url.com]{Linktext}
```

I och med användandet av Emmet förenklas även skrivandet av CSS. Läs mer på [Github](https://github.com/sergeche/emmet-sublime).

### SublimeCodeIntel ###
En portning av Komodo's autocomplete till Sublime där du får autocomplete för interna metoder i t.ex PHP-klasser. Det tar en stund att indexera vid första inladdningen. 

### Gist ###
Markera till exempel en fin kodsnutt eller en hel fil och gör den till en privat eller en publik Gist genom några knapptryck. Du kan även uppdatera existerande gists direkt via Sublime Text.

### SidebarEnhancements ###
Lägger till fler användbara val i contextmenyn. 

### EncodingHelper ###
Visar aktuella teckenkodningen i statusraden samt möjliggör en konvertering mellan en rad olika uppsättningar.

### JSHint ###
Eventuella fel i JavaScriptkoden visas i consolen vid build (kompletteras gärna med paketet **SublimeOnSaveBuild** som kör en build på filen när den sparas).

### BracketHighlighter ###
Markerar upp brackets i din kod tydligare så att du lättare kan få kontroll över nästlad kod.

### SublimeLinter ###
När du skriver Javascriptkod kan du få felaktiga bitar att bli markerade och ge dig tips på korrigeringar, t.ex avsaknad av semikolon, brackets m.m.

## Andra användbara features ##

* Split-view vertikalt eller horizontellt eller en grid på 4 kolumner
* "Goto anything" - sök på metodnamn eller filnamn i projektet med &#x2318; + P
* Kom åt metoder och properties i klasser på den aktuella filen med &#x2318; + R
* Med multiple cursors kan du redigera text på flera ställen samditigt (&#x2318; + klick)
* Sublime har stöd för Textmate-teman out of the box
* Vintage mode - använd dig av [vim](http://www.vim.org/)'s kommandoläge inuti Sublime (är själv ingen vim-fantast, men det finns säkert någon som gillar detta)
* Ställ markören på ett ord och tryck &#x2318; + D för att markera nästa förekomst av ordet och multipla markörer skapas åt dig

NetTuts gjorde en summering med lite tips&trix i Sublime som kan också kan vara värda att spana in: [http://net.tutsplus.com/tutorials/tools-and-tips/sublime-text-2-tips-and-tricks/](http://net.tutsplus.com/tutorials/tools-and-tips/sublime-text-2-tips-and-tricks/)

Min konfiguration för Sublime Text hittar du på [Github](https://github.com/PatrikWibron/dotfiles/tree/master/Sublime%20Text%202) där jag har min användarkonfiguration, keymap, färgtema med mera.

Du kommer med största sannolikhet hitta andra features som du gillar! 

Sublime Text 2 laddas ner helt gratis på [http://www.sublimetext.com/2](http://www.sublimetext.com/2)
