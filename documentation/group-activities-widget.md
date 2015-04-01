Group Activities widget
=======================

## Explanation

This widget shows all recent activities in a specific group. Activities includes new followers and rides shared.

![group activitieis widget]( /static/img/act.png)

## JavaScript code

Before you use a widget on your page, put this JavaScript code on your site. It does not matter where in the HTML `<body>` you insert it. You need it only once, irrespectable how many widgets you use.

```html
<script>"use strict";(function(){
var t=document.createElement('script');t.async=true; 
t.src='https://m.toogethr.com/widget/v2/api.js'; 
var s=document.getElementsByTagName('script')[0]; 
s.parentNode.insertBefore(t,s);})();</script>
```

## HTML code

To show the Group Activities widget you must put this HTML code in your webpage. The HTML element has data attributes to configure the size and behaviour. The attributes are easy to understand but are further explained below.

```html
<div class="too-GroupActivitiesList"
     data-groupkey="key-name"
     data-width="400"
     data-height="500"
     data-itemcount="10"
     data-header="true">
</div>
```
## Attributes

`data-groupkey="key-name"`

Contains the key name of the group. For instance "pinkpop". You can find the key-name on the settings page of each group or in the url from the group page on https://m.toogethr.com

`data-width="320"`

Defines the width of the widget in pixels in your webpage. There is a minimum width of 320px.

`data-height="400"`

Defines the height of the widget in pixels in your webpage.

`data-itemcount="10"`

Defines the maximum number of rides that are shown in the list. Optional attribute. When more items are available than the heigth of the widget can accomodate, the list will be scrollable.

`data-header="true"`

Defines if the header with the name of the group is shown. Default is true.
