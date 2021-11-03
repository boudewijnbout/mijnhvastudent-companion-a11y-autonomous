# Rapportage webtoegankelijkheid-test voor MijnHvA Companion

Datum webtoegankelijkheid-test: 25/10/2021

Webtoegankelijkheid-test uitgevoerd door: Shauri, Jean en Boudewijn

<img width="1437" alt="Schermafbeelding 2021-11-03 om 12 42 37" src="https://user-images.githubusercontent.com/45170095/140054118-18eb1f23-2562-4a72-96fb-b624bb9af801.png">

## 📚 Inhoudsopgave

- [Samenvatting](#samenvatting)
- [Achtergrond bij de evaluatie](#achtergrond-bij-de-evaluatie)
- [Afbakening](#afbakening)
- [Beoordelaars](#beoordelaars)
- [Beoordelingsproces](#beoordelingsproces)
- [Testresultaten en aanbevelingen](#testresultaten-en-aanbevelingen)
- [Referenties](#referenties)
- [Bijlagen](#bijlagen)
- [Licentie](#licentie)

## ✅ Samenvatting

Dit rapport beschrijft in hoeverre de website MijnHvA Compannion overeenstemt met de Web Content Accessibility Guidelines (WCAG) van het W3C. Na de achtergrondinformatie en afbakening van de test worden beoordelaars, beoordelingsproces en testresulltaten beschreven.

Conslusie van deze test luidt dat de MijnHvA Companion App bijna voldoet aan de WCAG 2.1 op niveau AAA, Behalve op de appearance, animation, controls en color contrast. Bij de appearance moet er nog goed gekeken worden naar de proximity bij de FAQ. Hier kan een een gebruiker met een minder visueel zicht de tekst hiervan minder of niet goed lezen. Niet al onze animation hebben de prefers/reduced/motion media query. Bij het tabben van de site kwamen we ook op 1 probleem uit, tijdens het tabben leest de screenreader de mobile nav voor terwijl die niet zichtbaar is. Verder was ons kleur contrast ook niet optimaal, ons witte achtergrond met de grijze tekst geeft geen goede contrast. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs.


## 🖼️ Achtergrond bij de evaluatie

De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op 25/10/2021. De website kan ondertussen aangepast zijn.

## 📦 Afbakening

#### MijnHvA Companion Welkomspagina

De welkomspagina heeft als doel informatie op een overzichtelijke en duidelijke manier te laten zien. Hierbij wordt gebruik gemaakt van verschillende doelgroepen die zijn opgedeeld in een primaire en secundaire doelgroep. namelijk: studenten, docenten en ondersteuners.

#### Base URL van de website

https://mijnhva.student.fdnd.nl

#### Lijst met URLs die in de beoordeling meegenomen zijn

https://mijnhva.student.fdnd.nl
 
#### Datum beoordeling

* Eerste beoordeling: 01-11-2021

* Tweede beoordeling: 04-11-2021

#### Taal(en) van de website

Nederlands

## 📋 Beoordelaars

#### Naam van de beoordelaar(s)

Obe van der Klei

#### Organisatie van de beoordelaar(s)

Ontwikkelteam MijnHvA

#### Contactinformatie van de beoordelaar(s)

o.j.van.der.klei@hva.nl

#### Expertisegebied van de beoordelaar(s)

Product Owner

#### Niveau van natuurlijke talen waarin de beoordelaar(s) communiceert/communiceren

Standaardnederlands

## 💻 Beoordelingsproces

#### WCAG 2.1 Niveau

Het WCAG 2.1 Niveau `AAA` wordt gezien als uitgangspunt voor het toegankelijkheids niveau van de website.

#### Gebruikte beoordeling en evaluatie tools

* Lighthouse `versie: 100.0.0.0`

* NVDA `versie 2021.2`

* Color contrast `versie 3.1.4`  

* HTML Validator (w3) `versie 1.3`

#### Handmatige tests en tools

The straw test

> Test om te kijken of een mens met beperkt zicht de tekst op een website goed kan lezen.


## ⚡ Testresultaten en aanbevelingen

Onze website is dichtbij aan voldoen van het niveau `AAA` van de WCAG 2.1 classificering. Dit komt door een aantal ontoegankelijke punten die opgelost moeten worden, zoals bijvoorbeeld het navigeren over de pagina met een toetsenbord.

## 💪 Sterke punten

* #### 👓 Screenreaders

   Wij hebben de welkomspagina uitvoerig getest met screenreaders. Dit hebben wij gedaan door het apple voiceover programma te gebruiken. Dit programma hebben wij tijdens het testen aangezet en vervolgens onze ogen dicht gedaan. Het was ontzettend raar om zo over een pagina heen te gaan, maar het voiceover programma deed het verassend goed op onze website, hij haperde nergens en liep nergens vast.

* #### 🎨 Kleurcontrast

   Wij hebben bij de welkomspagina geprobeerd om een zo goed mogelijk kleurencontrast te creëren. Zo als in onderstaande foto te zien is is dit goed gelukt. Wij hebben met kleurconstrast de hoogst haalbare score behaald.

   <details>
   <summary>Kleurcontrast test resultaat</summary>
   <img width="482" alt="Schermafbeelding 2021-11-02 om 14 58 28" src="https://user-images.githubusercontent.com/45170095/139861706-5f5b00a5-3320-4675-9987-fef8c9ad621c.png">
   </details>

* #### 🏠 Lighthouse

   Wij hebben bij de welkomspagina twee keer een lighthouse toegankelijkheids test gedaan. Zie onderstaande foto's. Hier kwam de eerste keer een score van 76 uit. Wij hebben aan de hand van de commentaren van lighthouse de website aangepast, een voorbeeld hiervan was het toevoegen van `alt` tags op onze afbeeldingen. Vervolgens hadden wij een score van 100.

* ##### Eerste lighthouse check

   <img width="1440" alt="Schermafbeelding 2021-10-27 om 12 18 08" src="https://user-images.githubusercontent.com/45170095/139865212-2e2e945b-626e-4a04-bf68-96f0182674be.png">

* ##### Tweede lighthouse check

   <img width="1440" alt="Schermafbeelding 2021-10-27 om 15 14 34" src="https://user-images.githubusercontent.com/45170095/139865217-840db226-ec91-4542-8a84-f377c615b59c.png">

## 🚧 Ontoegankelijke punten

De welkomspagina van MijnHvA Companion heeft een aantal ontoegankelijke punten, deze zijn als volgt: 

* Het is niet goed mogelijk om over de pagina heen te navigeren d.m.v de `tab` toets.

* De lengte van de tekst bij de veelgestelde vragen is te lang, hierdoor is het voor mensen met verminderd zicht erg lastig om de tekst goed te kunnen lezen.

* Screenreaders lezen ook het mobiele navigatie menu voor, terwijl deze niet zichtbaar is, hierdoor is het mogelijk dat iemand zijn oriëntatie op de pagina verliest.

## 🙎 Checklist

<!-- #### Content -->

<details>
 <summary>Content</summary>
 <br>
 
* Use plain language and avoid figures of speech, idioms, and complicated metaphors:

> Onze welkomspagina gebruikt tekst op 8 grade reading level. Hierdoor is onze website begrijpelijk voor alle gebruikers en op deze manier word niemand uitgesloten die moeilijke begrippen of woorden niet begrijpt.

* Make sure that button, a, and label element content is unique and descriptive:

> Button, a of label elementen die wij hebben gebruikt voor de MijnHvA Companion welkomspagina hebben allemaal een unieke beschrijving. Hierdoor kan een screenreader duidelijk aan de gebruiker voorlezen wat er gebeurd als er op een link en/of button wordt geklikt.

* Use left-aligned text for left-to-right (LTR) languages, and right-aligned text for right-to-left (RTL) languages:

> Alle gebruikte tekst op de MijnHvA Companion welkomspagina wordt standaard al links uitgelijnd. Hierdoor zijn de teksten gemakkelijk te lezen.
 </details>

<details>
 <summary>Global code</summary>
 <br>
 
* Validate your html:
 
> Wij hebben de HTML van de MijnHvA Companion welkomspagina gevalideerd door gebruik te maken van de w3 HTML validator, hier kwam bijvoorbeeld uit dat wij geen alt tags op afbeeldingen hadden gebruikt en dat onze HTML structuur van de veelgestelde vragen op de pagina niet juist was. Gelukkig waren dit vrij kleinschalige problemen en hebben wij deze direct opgelost.

* Use a lang attribute on the html element:

> Wij hebben de taal van de welkomspagina gezet op Nederlands met de volgende code: `<html lang="nl">`.
 
* Provide a unique title for each page or view: 
 
> Wij hebben de titel van de pagina gezet op: MijnHvA | Companion met de volgende code: `<title>MijnHvA | Companion</title>`.
 
* Ensure that viewport zoom is not disabled:
 
> Wij hebben de instellingen voor inzoomen op de pagina standaard gelaten, zoomen is daarom mogelijk op de welkomspagina. 
 
* Use landmark elements to indicate important content regions:
 
> Wij hebben de welkomspagina op een semantische wijze opgebouwd, wij hebben bijvoorbeeld de navigatie van de website in een `nav` element gezet en een `main` element gebruikt.
 
* Ensure a linear content flow:
 
> Dit is bij ons niet ter sprake gekomen, wij hebben op de hele welkomspagina geen `tabindex` gebruikt.
 
* Avoid using the autofocus attribute: 
 
> Wij hebben op de hele welkomspagina geen `autofocus` gebruikt.
 
* Allow extending session timeouts:
 
> Dit is niet van toepassing op de welkomspagina.

* Remove title attribute tooltips:
 
> Dit is niet van toepassing op de welkomspagina.
</details>

<details>
 <summary>Keyboard</summary>
 <br>
 
* Make sure there is a visible focus style for interactive elements that are navigated to via keyboard input:

> Helaas is het ons binnen het gegeven tijdsbestek niet gelukt om een focus state op de gebruikte interactieve elementen te zetten.
 
* Check to see that keyboard focus order matches the visual layout:
 
> Het is uit onze testen gebleken dat het voor het grootste gedeelte van de website mogelijk is om met de `tab` toets op een toetsenbord te navigeren, alleen het mobiele menu verstoord de tabstructuur van de pagina, waardoor de gebruiker e.v.t zijn oriëntatie op de pagina kan verliezen.  
 
* Remove invisible focusable elements:
 
> Dit is precies het probleem waar wij bij het gebruik van de `tab` toets tegen aanlopen, het mobiele menu moet eigenlijk worden weggehaald, zodat het niet alleen ontzichtbaar is, maar het ook niet meer mogelijk is om met de `tab` toets te selecteren.
 
### ✅ Keyboard oplossingen
 
> Het tab probleem is op te lossen door het mobiele menu op `display: none` te zetten in CSS, maar dit verwijdert de animatie van het mobiele menu ook gelijk.
 
> De focus state toevoegen kan worden toegevoegd door op de desbetreffende elementen de `:focus` selector in CSS te gebruiken.

</details>

<details>
 <summary>Images</summary> 
 <br>
 
* Make sure that all img elements have an alt attribute:
 
> De afbeeldingen die door ons werden gebruikt beschikten eerst niet over de `alt` tag, maar deze tags hebben wij vervolgens meteen geplaatst en laten voorlezen door een screenreader om te kijken hoe dit zou gaan. Dit ging verassend goed, de beschrijving was goed door ons bedacht en de screenreader las de beschrijving goed voor.
 
* Make sure that decorative images use null alt (empty) attribute values:
 
> Dit is niet van toepassing bij de welkomspagina.
 
* Provide a text alternative for complex images such as charts, graphs, and maps:
 
> Dit is niet van toepassing bij de welkomspagina.

* For images containing text, make sure the alt description includes the image's text:
 
> Dit hebben wij toegepast door bij het Hva logo in de navigatie balk een `alt` tag mee te geven met deze invulling: `title="MijnHvA logo"`
</details>
 
##### Images

Tijdens het testen van de afbeeldingen op de website kwamen wij er achter dat onze afbeeldingen geen alt tag hadden, deze hebben wij vervolgens toegevoegd. Hierna hebben wij met een screenreader getest of onze alt-tags goed waren en dit was in onze optiek het geval. Voor de rest waren onze afbeeldingen goed volgens de checklist.

##### Images oplossingen

> `Alt` tags gebruiken op de afbeeldingen. Zodat deze ook worden voorgelezen door screenreaders.

##### Headings

Bij het testen van de website hebben wij uiteraard ook gekeken naar de headings op de website. Onze gebruikte headings voldeden aan bijna alle punten van de checklist. Wij hadden namelijk perongeluk heading niveaus overgeslagen en hier ook geen logische volgorde in de heading niveaus gebruiken, wij gingen bijvoorbeeld van een h2 naar een h4 zonder een h3 te gebruiken.

##### Headings oplossingen

> Gebruik een logische volgorde in de heading levels: `h1, h2, h3`, enzovoort.

##### Lists

Use list elements (ol, ul, and dl elements) for list content:

Op de list categorie hebben wij een probleem gevonden in onze code. Na het runnen van een lighthouse check kwam eruit dat in onze ul een div was gebruikt. Door dit probleem kregen wij eerst een lighthouse score van 76 procent. 

##### List oplossingen

> `:focus` Door alle div te veranderen naar li gaf lighthouse na het checken dit probleem niet meer aan.

##### Controls

Bij het testen van de controls vanaf de checklist ging eigenlijk ook alles goed in de test, alleen hadden de interactieve elementen geen :focus state. Daarnaast heeft de website ook geen skiplink om direct door te kunnen gaan naar belangrijke informatie op de website.

##### Controls oplossingen

> `:focus` state toevoegen op interactieve elementen.

> Skiplink toevoegen, zodat er direct naar belangrijke informatie op de website kan worden gegaan met de tab toets.

##### Tables

Use the table element to describe tabular data.

Task: Use the th element for table headers (with appropriate scope attributes).
Use the th element for table headers (with appropriate scope attributes).

Task: Use the caption element to provide a title for the table.
Use the caption element to provide a title for the table.

Opmerking

> `:focus` We hebbben voor onze website geen tables gebruikt dus dit is niet van toepassing.

##### Forms

##### Media

Bij het testen van de media op de website ging alles eigenlijk zoals gehoopt, alles werkte naar behoren en de media die wij hadden geplaatst kwam goed overeen met de punten  die op de checklist werden genoemd als referentiepunt.

##### Video

Bij het testen van video was het een iets ander verhaal, volgens de checklist is het namelijk gewenst om ondertiteling toe te voegen, maar dit was in ons geval niet nodig, omdat de video die wij gebruikt hebben voor het overgrote gedeelte al bestaat uit tekst op beeld.

##### Audio

Zoals bij video was dit voor ons niet nodig, omdat de video die wij hebben gebruikt al voor het overgrote gedeelte bestaat uit tekst op beeld.

##### Appearance

Volgens de checklist was de appereance van de website ook goed, alleen hadden wij een probleem bij het uitvoeren van de `straw` test. Hier kwamen wij er namelijk achter dat de tekst van de veelgestelde vragen te lang was voor mensen die zoom software gebruiken.

##### Appearance oplossingen

> Veelgestelde vragen korter maken d.m.v `word-wrap` in css. Hierdoor kunnen mensen met zoom software de tekst ook goed kunnen lezen en de vragen op een goede manier kunnen bekijken.

##### Animation

Onze website maakt niet echt gebruik van animaties, los van wat simpele transitions, maar deze zijn afgestemd aan de hand van de checklist.

##### Color contrast

Bij het testen van het kleurencontrast, was het contrast van de kleuren die wij op de website hebben gebruikt goed, alleen de tekst met een 'normale' grootte is één tint te grijs, deze moet iets meer een zwarte tint hebben, dan is het kleuren contrast van de website helemaal perfect op AAA niveau. 


##### Color contrast oplossingen

> De tekst met een 'normale' grootte, van kleur veranderen met de volgende css property: `color: #363636`. Hiermee wordt de color contrast score van AAA behaald. 

##### Mobile and touch

Bij het testen op een mobiel apparaat, was het even spannend om te kijken of de website het ook goed deed op een andere scherm oriëntatie, maar dit ging eigenlijk super goed. Voor de rest was onze website goed op mobiel volgens de checklist. Alleen werd door de checklist wel aangegeven dat op mobiel horizontaal scrollen niet gewenst is. 

##### Mobile and touch oplossingen

> E.v.t horizontaal scrollen weghalen van de instructies `section`. Dit kan door de `display: grid` weg te halen en de width van de `article` breder te maken.

{Neem links op naar de WCAG 2.1 succescriteria en technieken voor de ontoegankelijke punten}

{Voeg per check specifieke rapportage(s), of links naar rapportage(s) toe in de Wiki, bv. screenshots van tests}

{Schrijf per check aanbevelingen voor het verbeteren van ontoegankelijke punten}

{Beschrijf of verwijs per check naar een programma voor het monitoren van webstite toegankelijkheid, her-beoordeling aan de hand van beoordelingsinstrumenten etc.}

### Resultaten Usability test

Tot onze grote spijt was het bezoek aan het usability lab voor ons geen toegevoegde waarde. Dit komt doordat het usability lab draait op verouderde browsers. Onze website is met bepaalde 'nieuwe' css properties gemaakt, zoals `grid`, hierdoor was het niet mogelijk om onze website in het usability lab te testen, omdat onze website door de gebruikte browser dan volledig uitelkaar werd getrokken.

## Referenties

Referenties welke gebruikt zijn bij de webtoegankelijkheid-test. Deze referenties zijn allen in het Engels:

- [Overzicht en introductie van de Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/intro/wcag)
- [De complete Web Content Accessibility Guidelines 2.1 (WCAG)](https://www.w3.org/TR/WCAG21/)
- [Technieken voor WCAG 2.1](https://www.w3.org/WAI/WCAG21/Techniques/)
- [Bronnen voor beoordeling van webtoegankelijkheidsevaluatie ](http://www.w3.org/WAI/eval/)
- [Tools lijst voor semi-geautomatiseerde beoordeling van webtoegankelijkheid](https://www.w3.org/WAI/ER/tools/)
- [Informatie over het gebruik van gecombineerde expertise voor het evalueren van webtoegankelijkheid](https://www.w3.org/WAI/eval/reviewteams)
- [A11Y Project Checklist](https://www.a11yproject.com/checklist/)

{Vul aan waar nodig, haal weg wat niet relevant is}

## Bijlagen

{Geef een opsomming van de bijlagen, zoals links naar rapportages, screenshots en uitleg in de Wiki}

[Einde van het template]

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
