---
title: markdown demo
tags: []
originContent: ''
categories: []
toc: false
date: 2019-05-01 04:47:12
---

概述
哲學
Markdown的目標是實現「易讀易寫」。

不過最需要強調的便是它的可讀性。一份使用Markdown格式撰寫的文件應該可以直接以純文字發佈，並且看起來不會像是由許多標籤或是格式指令所構成。Markdown語法受到一些既有text-to-HTML格式的影響，包括Setext、atx、Textile、reStructuredText、Grutatext 和 EtText，然而最大靈感來源其實是純文字的電子郵件格式。

因此Markdown的語法全由標點符號所組成，並經過嚴謹慎選，是為了讓它們看起來就像所要表達的意思。像是在文字兩旁加上星號，看起來就像*強調*。Markdown的清單看起來，嗯，就是清單。假如你有使用過電子郵件，區塊引言看起來就真的像是引用一段文字。

行內HTML
Markdown的語法有個主要的目的：用來作為一種網路內容的寫作用語言。

Markdown不是要來取代HTML，甚至也沒有要和它相似，它的語法種類不多，只和HTML的一部分有關係，重點不是要創造一種更容易寫作HTML文件的語法，我認為HTML已經很容易寫了，Markdow的重點在於，它能讓文件更容易閱讀、編寫。HTML 是一種發佈的格式，Markdown是一種編寫的格式，因此，Markdown的格式語法只涵蓋純文字可以涵蓋的範圍。

不在Markdown涵蓋範圍之外的標籤，都可以直接在文件裡面用HTML撰寫。不需要額外標註這是HTML或是Markdown；只要直接加標籤就可以了。

只有區塊元素──比如<div>、<table>、<pre>、<p>等標籤，必需在前後加上空行，以利與內容區隔。而且這些（元素）的開始與結尾標籤，不可以用tab或是空白來縮排。Markdown的產生器有智慧型判斷，可以避免在區塊標籤前後加上沒有必要的<p>標籤。

舉例來說，在Markdown文件裡加上一段HTML表格：