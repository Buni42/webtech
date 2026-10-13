# Labo 3 - reflecties

Naam: Bunyamin Anil

## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?
  => insprong en bolletjes, in ul.
- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?
  => er verandert niets behalve de hoogte/breedte.

## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?
  text-align: center; en max-width: 40rem; + margin: 0 auto;
- Waarom werkte de padding op de knop pas na `display: inline-block`?
  Een <a> is standaard display: inline. De padding wordt dan wel toegepast, maar de boven- en onderpadding vergroten de regellijn niet. Daardoor kan de knop visueel te krap lijken of overlappen met andere inhoud.
  Met display: inline-block gedraagt de link zich als een blokje binnen de tekststroom

## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border?
  Dat komt doordat reset.css box-sizing: border-box instelt voor alle elementen. Daardoor is de opgegeven width inclusief inhoud, padding en borders.

## 4. Donut

- Waarom werkt `height: 70%` op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?
  Vermits zijn ouder een vh als hoogte heeft.
- Tegen welke maat van de ouder rekende de browser `margin: 15%`: de breedte of de hoogte?
  Beide zijn hetzelfde in dit geval.

## 5. Landingspagina

- Gaf je `main` een `height` of een `min-height`, en waarom?
  Een min-height. Om afgeknipte tekst te voorkomen (F3.10).
- Wat gebeurt er met de twee helften als je een regeleinde zet tussen `</article>` en `<div class="afbeelding">`?
  witruimte in html telt mee, als ze beide 50% passen ze niet naast elkaar.

## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1.
2.
3.
