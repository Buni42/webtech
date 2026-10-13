# Labo 2 - reflecties

Naam: Bunyamin Anil

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: Alle links in de list elementen in da nav onder de header.
- b. `article > p`: Alleen de buitenste paragraaf in de article.
- c. `.uren li:nth-child(3)`: Derde element van de uren lijst.
- d. `h2 ~ p`: Elke paragraaf na een header 2.
- e. `.rassen li:first-child`: Eerste element van de lijst onder de klasse rassen.

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
| ----- | ------------------------- | ----------------- | ---------------------- | ------ |
| 1     | groen                     | herkomst          | groen                  | j      |
| 2     | blauw                     | volgorde          | blauw                  | j      |
| 3     | rood                      | specificiteit     | rood                   | j      |
| 4     | rood                      | volgorde          | rood                   | j      |
| 5     | blauw                     | specificiteit     | blauw                  | j      |
| 6     | blauw                     | volgorde          | blauw                  | j      |
| 7     | rood                      | herkomst          | rood                   | j      |
| 8     | rood                      | volgorde          | blauw                  | n      |
| 9     | rood                      | ?                 | rood                   | j      |
| 10    | groen                     | error             | groen                  | j      |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)
Bij vraag 8. Ik dacht door volgorde van bewerking dat we rood gingen krijgen als kleur. Vermits rood de kleur is in style.css.

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
  nav a, omdat er geen klass is in de nav links in de html.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
  footer{text-align: center;}
  Ik dacht dat ik align-items moest gebruiken en dat het helemaal rechts moest alignen. (had de foto half open)

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
  Kleuren, lineheight en font. Om het makkelijker te maken bij een verandering, zeker bij kleuren is dit nuttig.
- Wat verandert er in je site als je één token wijzigt?
  Op dit moment alleen de tekstkleuren en font.

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. Main ol li, main moet er niet staan: F2.7
2. 40 rem komt meerdere keren voor: F2.10
3. font family toegevoegd aan elementen, kon het doen aan de token zelf: inline styles en verweesde waarden
4. /
5. /

Voor de rest ziet het echt nog goed uit.
