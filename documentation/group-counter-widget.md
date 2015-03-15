Group counter widget
====================

##Explanation

This widget shows a counter of available rides within a specific group.

![Group counter widget](http://www.toogethr.com/sites/default/files/styles/large/public/1/counter.png?itok=SxYEgFCt)

## JavaScript code

Before you use a widget on your page, put this JavaScript code on your site. It does not matter where in the HTML <body> you insert it. You need it only once, irrespectable how many widgets you use.

```
<script>"use strict";(function(){
var t=document.createElement('script');t.async=true; 
t.src='https://m.toogethr.com/widget/v2/api.js'; 
var s=document.getElementsByTagName('script')[0]; 
s.parentNode.insertBefore(t,s);})();</script>
```

## HTML code

To show the Group Counter widget you must put this HTML code in your webpage. The HTML element has data attributes to configure the size and behaviour. The attributes are easy to understand but are further explained below.

```
<div class="too-Counter"
     data-groupkey="key-name"
     data-width="320">
</div>
``` 

## Attributes

`data-groupkey="key-name"`

Contains the key name of the group. For instance "pinkpop". You can find the key-name on the settings page of each group or in the url from the group page on https://m.toogethr.com

`data-width="250"`

Defines the width of the widget in pixels in your webpage. There is a minimum width of 200px.
