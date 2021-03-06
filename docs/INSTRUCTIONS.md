# Zoek een boek in de OBA collectie

Voor de opdracht Zoek-een-boek-bij-de-OBA leer je JSON data laden en tonen op een pagina.

## Context
*Bij welke sprint hoort deze leertaak en welk niveau heeft deze leertaak.*

Leertaak: Werk voor een opdrachtgever een interactie uit met externe data.
Deze leertaak hoort bij sprint 8 "Keep Users in Control".
Dit is een voorbeeld taak en wordt behandeld in het college.
Hierna ga je in een workshop de leertaak zelf ontwerpen en maken in [OBA - Zoek een spannend boek]().

## Briefing
*In de briefing staat wat de opdracht is en wat de opdrachtgever wil.*

Ontwerp voor de OBA een zoekresultatenpagina.

## Doel van deze opdracht
*Wat leer je in deze taak.*

Je krijgt een voorbeeld te zien hoe je met JS externe data kan laden en gebruiken om zoekresulaten te presenteren.

## Werkwijze
*De werkwijze volgt de fasering van de Development Life Cycle.*

Aan de hand van deze Job Story gaan we met de OBA-API zoekresultaten tonen.

> "Als ik een boek zoek wil ik een lijst spannende boeken te zien krijgen."

Deze opdracht gaat over de fases [analyseren](#analyseren), [ontwerpen](#ontwerpen) en [bouwen](#bouwen).

### Analyseren
*In de analysefase inventariseer je wat er moet gebeuren om een taak uit te voeren.* .

<details>
<summary>Aanpak</summary>

1. Uitleggen wat JSON data is.
2. Aan de hand van voorbeelden laten zien wat je met JSON dat kan doen.
3. JSON data van de OBA-API uitpluizen, wat staat er allemaal in de JSON? Hoe kun je hier de spannende boeken voor een bepaalde leeftijd uit halen?

#### Materiaal

- [Presentatie Wat is JSON data](Content-Audit.pdf)
- [JSON data](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
- [OBA-API documentatie](https://zoeken.oba.nl/api/v1/)


</details>

### Ontwerpen
*In de ontwerpfase neem je ontwerpbeslissingen en zorg je dat je precies weet wat je moet gaan bouwen.*
<details>
<summary>Aanpak</summary>

1. Voorbeelden bekijken van zoekformulieren en resultaatpagina's.
2. Wireflow schetsen van de Job Story. Hoe moet het zoekformulier en de resultaatpagina er uit komen te zien.
3. Breakdown maken van welke techniek nodig is om de data op te halen en te renderen.

#### Materiaal

- Break-down schets maken

</details>

### Bouwen
*In de bouwfase realiseer je de beslissingen uit de ontwerpfase.*

<details>
<summary>Aanpak</summary>

0. Er is al een HTML pagina met basis CSS waar de resultaten getoond kunnen worden. 
1. XMLHttpRequest opzetten
2. Data tonen in de console
3. Loop schrijven en html renderen
4. Stylen van de resultaten

#### Materiaal

- Met behulp van [XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest) of [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) kan een [JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) file worden geladen. Daarna kun je de HTML elementen aanmaken, de juiste content koppelen en aan de DOM toevoegen.

</details>

### Integreren
*In de integratiefase voer je de aanpassingen door zodat iedereen ze kan zien.*

n.v.t.

### Testen
*In de testfase controleer je of jouw aanpassingen werken zoals bedoeld.*

n.v.t.

## Criteria
*Definitions of done*

1. Je hebt een voorbeeld gezien van hoe data van een externe bron wordt geladen met Javascript.
2. Je hebt een voorbeeld gezien van hoe de zoekresultaten worden getoond in een webpagina.
3. Je hebt een voorbeeld gezien van hoe *HTTP response status codes* kunnen worden gebruikt en vormgegeven.

