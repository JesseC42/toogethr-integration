Group counter widget
====================

## Toelichting

Deze widget laat een teller zien van de beschikbare ritten binnen een specifieke groep.

![Group counter widget](http://www.toogethr.com/sites/default/files/styles/large/public/1/counter.png?itok=SxYEgFCt)

## JavaScript code

Voeg, voordat je een widget gebruikt op je pagina, deze JavaScript code toe aan je site. Het maakt niet uit waar in de HTML `<body>` je het invoegt. Je hebt het maar een keer nodig, ongeacht hoeveel widgets je gebruikt.

```
<script>"use strict";(function(){
	var t=document.createElement('script');t.async=true; 
	t.src='https://m.toogethr.com/widget/v2/api.js'; 
	var s=document.getElementsByTagName('script')[0]; 
	s.parentNode.insertBefore(t,s);})();</script>
	```

	## HTML code

	Om de Group rides widget te tonen moet je deze HTML code in je webpage opnemen. Het HTML element heeft data attributen om de grootte en het gedrag in te stellen. Deze attributen zijn gemakkelijk te begrijpen, maar worden hieronder verder toegelicht.

	```
	<div class="too-Counter"
	data-groupkey="key-name"
	data-width="320">
</div>
``` 

## Attributes

`data-groupkey="key-name"`

Bevat de key name van de groep. Bijvoorbeeld "pinkpop". Je kunt de key-name vinden op de settings pagina van iedere groep of in de URL van de groep pagina op https://m.toogethr.com

`data-width="250"`

Definieert de breedte van de widget in pixels op je webpagina. Er geldt een minimum breedte van of 250px.