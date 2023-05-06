# 💻 PROJECT: WD2 - Superhero Website

## 🥅 Overzicht en Leerdoelen

Met dit project leer je wat het verschil is tussen aanduiding en opmaak (*markup* en *style*), wat ruimte, layout, responsiveness en opmaak precies zijn en ga je de website uit WD1 voorzien van ruimte, layout en opmaak. Je gaat aan de slag met de opmaaktaal **CSS** op een gestructureerde manier.

## 🔍 Superhero Website

In het project WD1 koos je een superheld waar je een website voor uitwerkt. Je hebt je HTML voorzien van semantisch juiste elementen, zodat je alle inhoud volledig en correct weergeeft in de browser. 

Met dit project voorzie je je superheldenwebsite van opmaak. Hiervoor werken we aan de hand van de **C.U.B.E.** methode:
 - **C**omposition: alles dat met layout en ruimte te maken heeft op macro-niveau
 - **U**tilities: kleine klassen die een element van één opmaak-regel voorzien
 - **B**locks: opmaak-regels die je nog niet wist op te lossen met composition of utilities, vaak op micro-niveau
 - **E**xceptions: uitzonderingsregels op de blocks

Voordat je je website voorziet van opmaak, ga je een ontwerp zoeken of maken. Zonder ontwerp kan je niet gericht tewerk gaan. Daarna ga je elke stap van de CUBE methode één voor één doorlopen.

## 🛠️ Opdrachten

<details>
<summary>opdracht 1: website ontwerp</summary>

>  - [ ] Ga online op zoek naar een ontwerp dat jij best vindt passen bij je superheld. Ik raad je sterk aan om [één van deze templates te kiezen](https://www.w3schools.com/w3css/w3css_templates.asp).  
>       -Je kan ook zelf op zoek gaan online naar een bijpassende template, of er zelf één tekenen. Hou er rekening mee dat je de opdracht dan wel een stuk moeilijker maakt voor jezelf!
>  - [ ] Duidt de layout elementen aan op niveau 1, 2 en 3 waaruit je ontwerp bestaat.
>  - [ ] Schrijf je HTML pagina opnieuw uit. Houdt daarbij rekening met **semantiek, opdelen in grotere en kleinere delen en IDs en klassen**.
>  - [ ] Vraag aan je leerkracht om je HTML code na te kijken wanneer je hiermee klaar bent.

</details>

---

<details>
<summary>opdracht 2: Ruimte tussen macro-elementen</summary>

> **LET OP:** We maken eerst de Mobile versie van je website. Kijk je website dus ook enkel na in de Mobile Viewer van je webbrowser.
> - [ ] Maak een bestand aan genaamd `composition.css`.
> - [ ] Open `index.html` en voeg in het `<head>` element een `<link>` element toe, waarmee je verwijst naar `composition.css`
> - [ ] Gebruik CSS selectors om ruimte toe te voegen tussen en in alle elementen die zich bevinden op layout niveau 1, 2 en 3.\
>       **LET OP:** Zorg ervoor dat je selectors *niet* tè specifiek zijn!
> 
> - [ ] Kijk de waardes na die je gebruikt hebt: Probeer waardes die dicht bij elkaar liggen gelijk te trekken.\
>       *bv.: heb je ergens een waarde van 31px en ergens anders een waarde van 32px, verander dan bijvoorbeeld die van 31px naar 32px.*
> - [ ] Maak voor elke veelgebruikte waarde een CSS variabele aan in het `:root` element. 
> - [ ] Vervang de waardes door het gebruik van de juiste CSS variabelen.

</details>

---

<details>
<summary>opdracht 3: Ruimte en kleur toevoegen</summary>

> **LET OP:** We maken eerst de Mobile versie van je website. Kijk je website dus ook enkel na in de Mobile Viewer van je webbrowser.
> - [ ] Maak een bestand aan genaamd `utilities.css`.
> - [ ] Open `index.html` en voeg in het `<head>` element een `<link>` element toe, waarmee je verwijst naar `utilities.css`
> - [ ] Maak utility-klassen aan om ruimte tussen en in elementen toe te voegen.
>       - **LET OP:** een utility-klasse bestaat meestal uit een klasse-selector, gevolgd door *één enkele stijlregel*!
> - [ ] Voeg de utility-klassen toe in HTML waar nodig.
> - [ ] Zorg ervoor dat je utility-klassen gebruik maken van CSS variabelen.
>
> CSS variabelen maken:
> - [ ] Maak voor elke veelgebruikte kleur een CSS variabele aan in het `:root` element. 
> - [ ] Maak utility-klassen aan om kleur aan elementen toe te voegen.
>       - **LET OP:** een utility-klasse bestaat meestal uit een klasse-selector, gevolgd door *één enkele stijlregel*!
> - [ ] Voeg de utility-klassen toe in HTML waar nodig.

</details>

---

<details>
<summary>opdracht 4: Layout toevoegen</summary>

> **LET OP:** We gaan de Mobile versie van je website nu uitbreiden naar een Desktop versie. Kijk je website vanaf nu na in zowel Desktop modus als in Mobile modus.
> - [ ] Open `composition.css`
> - [ ] Voeg onderaan een media query toe voor je desktop website.
> - [ ] Voeg layout toe met behulp van CSS Grid en CSS Flexbox in de media query waar nodig, zodat je website nu ook werkt volgens je Desktop ontwerp.
> - [ ] Voeg, indien nodig, layout containers toe aan je HTML code.\
>       **LET OP:** kijk na of je Mobile ontwerp nog steeds werkt! Wanneer je layout containers toevoegt, kan het zijn dat je CSS selectors niet meer juist zijn.

</details>

---

<details>
<summary>opdracht 5: Afwerking</summary>

> **LET OP:** We gaan de Mobile versie van je website nu uitbreiden naar een Desktop versie. Kijk je website vanaf nu na in zowel Desktop modus als in Mobile modus.
> - [ ] Maak een bestand aan genaamd `blocks.css`.
> - [ ] Open `index.html` en voeg in het `<head>` element een `<link>` element toe, waarmee je verwijst naar `blocks.css`
> - [ ] Pas je elementen zo aan dat ze zo goed mogelijk overeenkomen met het oorspronkelijke ontwerp.
> 
> De laatste uitzonderingen:
> - [ ] Maak een bestand aan genaamd `exceptions.css`.
> - [ ] Open `index.html` en voeg in het `<head>` element een `<link>` element toe, waarmee je verwijst naar `exceptions.css`

</details>

---

## 💡 Belangrijke Termen

| Term                      | Definitie |
| ------------------------- | --------- |
| CSS                       |  Een taal die gebruikt wordt om de opmaak van een website te bepalen. CSS staat voor Cascading Style Sheets.         |
| selector                  | De selector duidt aan welke HTML elementen opmaak zullen krijgen.         |
| declaratie                |  De declaratie bestaat uit 1 of meerdere opmaakregels die tussen accolades worden geplaatst.         |
| opmaak                    |verwijst naar de vormgeving en presentatie van een webpagina, inclusief kleur, lettertype, lay-out, afbeeldingen en andere visuele elementen.         |
| property                  |  een stijleigenschap die kan worden toegepast op een HTML-element, zoals kleur, lettertype, afmetingen, enz.         |
| property-value (waarde)   | een specifieke waarde die aan een stijleigenschap wordt toegewezen, zoals bijvoorbeeld een kleurwaarde of lettertype.          |
| stylesheet                |een verzameling van stijleigenschappen die worden gebruikt om de opmaak van een webpagina te definiëren.          |
| externe stylesheet        |een stylesheet dat is opgeslagen in een apart CSS-bestand en wordt gelinkt aan de HTML-pagina.         |
| *.css                     |de bestandsextensie voor CSS-bestanden.         |
| selector                  |een CSS-term die verwijst naar een HTML-element waarop de stijlregels worden toegepast. Een selector kan bijvoorbeeld verwijzen naar een specifieke HTML-tag, class of ID.         |
| conflicterende stijlregel |wanneer twee of meer stijlregels worden toegepast op hetzelfde HTML-element en conflicteren met elkaar. In dit geval wordt bepaald welke stijlregel het meest specifiek is of de hoogste prioriteit heeft.      |
| hover                     |een CSS-pseudo-klasse die wordt gebruikt om stijlen toe te passen wanneer de muis over een HTML-element wordt bewogen.         |
| hexadecimale kleurwaarde  |een kleurwaarde die wordt uitgedrukt als een zescijferige combinatie van letters en cijfers, zoals bijvoorbeeld #FF0000 voor rood.        |
| rgb kleurwaarde           |een kleurwaarde die wordt uitgedrukt als een combinatie van drie getallen tussen 0 en 255, die respectievelijk staan voor de rood-, groen- en blauwcomponenten van de kleur.          |
| font                      | een CSS-stijleigenschap die wordt gebruikt om het lettertype van tekst op een webpagina te definiëren.          |
| generic family            | een reeks van lettertypefamilies die worden gebruikt als fallback-opties wanneer het gewenste lettertype niet beschikbaar is. Voorbeelden van generieke families zijn serif, sans-serif en monospace.          |
| font family               |  een specifieke reeks lettertypefamilies die worden gebruikt om tekst op een webpagina weer te geven. Meerdere lettertypefamilies kunnen worden opgegeven, gescheiden door een komma, om fallback-opties te bieden.         |
| serif                     |  een lettertypefamilie die wordt gekenmerkt door de aanwezigheid van kleine extra lijntjes (serifs) aan het einde van elke letter.         |
| sans-serif                |een lettertypefamilie die geen serifs bevat en daarom een strakkere, schone uitstraling heeft.       |
| monospace                 | een lettertypefamilie waarbij elke letter evenveel ruimte inneemt, ongeacht de breedte van de letter zelf.          |
| box model                 |   een concept in CSS dat elk HTML-element beschrijft als een rechthoekige box met inhoud, padding, rand en marge.         |
| padding                   |De ruimte tussen de inhoud van een element en de rand van het element. Het wordt vaak gebruikt om de afstand tussen de inhoud en de randen van een element te vergroten of te verkleinen.
        |
| border                    |De rand van een element. Het wordt gebruikt om een visuele scheiding tussen de inhoud van een element en de rest van de pagina te creëren. De rand bestaat uit drie delen: de breedte, de stijl en de kleur.
           |
| margin                    | De ruimte tussen de rand van een element en de rand van het element ernaast. Het wordt gebruikt om de afstand tussen elementen te vergroten of te verkleinen en om witruimte te creëren.
          |
| width                     | De breedte van een element. Het kan worden ingesteld op een bepaalde waarde in pixels, procenten of een andere eenheid van lengte.
          |
| height                    |  De hoogte van een element. Het kan worden ingesteld op een bepaalde waarde in pixels, procenten of een andere eenheid van lengte.
         |


## 📚 Bronnen

 - https://flukeout.github.io/

---

## 🏆 Evaluatie
 
### Deadlines

 - **Week 2**: opdracht 1&2
 - **Week 4**: opdracht 3&4
 - **Week 5**: opdracht 5

### Opmaak

| A                                                                                                                                                                                     | B                                                                                                                                                                                    | C                                                                                                                                                                                                            | D                                                                                                                                                                                                                           | E                                                                                                                                                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Selectors zijn correct en voldoende specifiek gedefinieerd. Er werd gekozen voor de correcte stijlregels met de juiste waardes en eenheden. Selectors werden samengevoegd waar nodig. | Selectors zijn correct en voldoende specifiek gedefinieerd. Er werd gekozen voor de correcte stijlregels met de juiste waardes en eenheden. Selectors worden te weinig samengevoegd. | Selectors zijn correct en voldoende specifiek gedefinieerd. Selectors worden te weinig samengevoegd. Er werd gekozen voor de correcte stijlregels, maar de waardes en eenheden werden niet correct gebruikt. | Selectors zijn correct gedefinieerd, maar zijn vaak niet specifiek genoeg. Selectors worden te weinig samengevoegd. Er werd gekozen voor de correcte stijlregels, maar de waardes en eenheden werden niet correct gebruikt. | Selectors zijn verkeerd of niet specifiek genoeg gedefinieerd. Selectors worden te weinig samengevoegd. Stijlregels, waardes en eenheden werden niet correct gebruikt. |

### Statische Websites

| A                                                                                                                                                                                                                                                                                     | B                                                                                                                                                                                                                                                     | C                                                                                                                                                                                                                                | D                                                                                                                                                                                | E                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Layout, ruimte en interactie zijn correct geïmplementeerd. De website is responsive en Mobile First ontwikkeld. Stijlregels zijn duidelijk en overzichtelijk verzameld in externe stylesheets. Je gebruikt relatieve eenheden (em, rem) en custom properties (variabelen) waar nodig. | Layout, ruimte en interactie zijn correct geïmplementeerd. De website is responsive en Mobile First ontwikkeld. Stijlregels zijn duidelijk en overzichtelijk verzameld in externe stylesheets. Je gebruikt custom properties (variabelen) waar nodig. | De interactie op jouw website is onvoldoende geïmplementeerd. Layout en ruimte zijn correct. De website is responsive en Mobile First ontwikkeld. Stijlregels zijn duidelijk en overzichtelijk verzameld in externe stylesheets. | Ruimte en interactie zijn onvoldoende geïmplementeerd. De website is onvoldoende responsive. Je layout werkt en je hebt de website ontwikkeld volgens het Mobile First principe. | Layout, ruimte en interactie zijn onvoldoende geïmplementeerd. De website is niet responsive. Er werd niet gewerkt volgens het Mobile First principe. |

### Markup

| A                                                                                                                                                                                                                                                  | B                                                                                                                                                                                                                                                                               | C                                                                                                                                                                                                                               | D                                                                                                                                                                                                                                                                                     | E                                                                                                                                                                                                               |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Elementen worden correct genest. Elk element bestaat uit de juiste openings- en sluitingstag. Elementen zijn voorzien van de vereiste attributen en elk attribute is ingevuld met een correcte waarde. Bronnen zijn lokaal opgeslagen.             | Elementen worden correct genest. Elk element bestaat uit de juiste openings- en sluitingstag. Elementen zijn voorzien van de vereiste attributen. Attributes bevatten een foutieve waarde. Bronnen zijn lokaal opgeslagen.                                                      | Elementen worden correct genest. Elk element bestaat uit de juiste openings- en sluitingstag. Elementen zijn niet voorzien van de vereiste attributen. Attributes bevatten een foutieve waarde. Bronnen zijn lokaal opgeslagen. | Elementen worden niet correct genest. Elk element bestaat uit de juiste openings- en sluitingstag. Elementen zijn niet voorzien van de vereiste attributen. Attributes bevatten een foutieve waarde. Externe bronnen worden gebruikt, waar interne bronnen een betere oplossing zijn. | Elementen worden niet correct genest. Elementen missen de juiste openings- of sluitingstag. Attributen werden niet correct gebruikt. Er zijn te weinig elementen aanwezig om de inhoud correct over te brengen. |
| De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn ingevuld waar nodig en verbeteren de semantiek. Elementen zijn onderverdeeld in grotere en kleinere elementen, en er is gekozen voor een optimale oplossing. | De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn ingevuld waar nodig en verbeteren de semantiek. Elementen zijn onderverdeeld in grotere en kleinere elementen. Er zijn echter betere oplossingen die je had kunnen bedenken en gebruiken. | De semantisch juiste elementen werden niet altijd gebruikt. De id's en classes van elementen zijn ingevuld waar nodig en verbeteren de semantiek. Elementen zijn onderverdeeld in grotere en kleinere elementen.                | De semantisch juiste elementen werden gebruikt. De id's en classes van elementen zijn niet ingevuld waar nodig en verbeteren de semantiek onvoldoende. Elementen zijn onderverdeeld in grotere en kleinere elementen.                                                                 | De semantisch juiste elementen werden niet of verkeerd gebruikt. De id's en classes zijn onvoldoende ingevuld. Elementen zijn onvoldoende onderverdeeld in grotere en kleinere elementen.                       |