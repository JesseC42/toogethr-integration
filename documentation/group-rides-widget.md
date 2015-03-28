Group rides widget
==================

## Toelichting

Deze widget laat alle recent ritten in een specifieke groep zien. Ritten bevatten details over locatie, tijd en prijs.

![Pinkpop example]
(http://www.toogethr.com/sites/default/files/styles/large/public/1/ride.png?itok=FNhBXU9C)


## JavaScript code

Voeg voordat je een widget gebruikt op je pagina, deze JavaScript code toe aan je site. Het maakt niet uit waar in de HTML `<body>` je het invoegt. Je hebt het maar een keer nodig, ongeacht hoeveel widgets je gebruikt.

```html
<script>"use strict";(function () {
	var t = document.createElement('script');t.async = true;
	t.src = 'https://m.toogethr.com/widget/v2/api.js';
	var s = document.getElementsByTagName('script')[0];
	s.parentNode.insertBefore(t, s);})();
	</script>
```

## HTML code
Om de Group rides widget te tonen moet je deze HTML code in je webpage opnemen. Het HTML element heeft data attributen om de grootte en het gedrag in te stellen. Deze attributen zijn gemakkelijk te begrijpen, maar worden hieronder verder toegelicht.

```html

<div class="too-GroupRidesList"
	data-groupkey="key-name"
	data-width="400"
	data-height="500"
	data-itemcount="20"
	data-header="true">
</div>
```

## Attributen

`data-groupkey="key-name"`

Bevat de key name van de groep. Bijvoorbeeld "pinkpop". Je kunt de key-name vinden op de settings pagina van iedere groep of in de URL van de groep pagina op https://m.toogethr.com .

`data-width="320"`

Definieert de breedte van de widget in pixels op je webpagina. Er geldt een minimum breedte van 320px.

`data-height="400"`

Definieert de hoogte van de widget in pixels op je webpagina.

`data-itemcount="20"`

Definieert het maximum aantal ritten dat in de lijst wordt getoond. Optionele attribuut. Wanneer er meer items beschikbaar zijn dan de hoogte van de widget ondersteunt, zal deze lijst scrollbaar zijn.

`data-header="true"`

Definieert of de header met de naam van de groep wordt getoond. De default waarde is true.
