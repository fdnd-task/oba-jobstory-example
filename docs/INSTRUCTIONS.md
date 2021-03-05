# Zoek een boek bij de OBA

Voor de opdracht Zoek-een-boek-bij-de-OBA leer je JSON data laden en tonen op een pagina.

## Context
    Wat schrijven we hier?
    Hoe deze opdracht in de sprint past, welke leertaak het is en welk niveau de leertaak heeft?

Leertaak: Werk voor een opdrachtgever een interactie uit met externe data.
Deze opdracht wordt behandeld in het college van sprint 8 "Keep Users in Control". Dit is een [voorbeeld taak](#niveau-van-een-leertaak), hierna ga je in een workshop de leertaak zelf ontwerpen en maken in de opdracht [OBA - Zoek een spannend boek]().

## Briefing
*In de briefing staat wat de opdracht is en wat de opdrachtgever wil.*

Ontwerp en maak een zoekresultatenpagina voor de Openbare Bibliotheek Amsterdam (OBA).

## Doel van deze opdracht
    Wat schrijven we hier?
    Wat leren de studenten relatie tot de focus van deze sprint?

In deze taak krijg je een voorbeeld te zien hoe je met JS externe data kan laden en gebruiken om zoekresulaten te presenteren.

## Werkwijze
*De werkwijze volgt de fasering van de [Development Life Cycle](#werkwijze-volgens-de-development-life-cycle).*

Aan de hand van deze Job Story gaan we met de OBA-API zoekresultaten tonen.

> "Als ik een boek zoek wil ik een lijst spannende boeken te zien krijgen, die geschikt zijn voor mijn leeftijd."

Deze opdracht gata over de fases [analyseren](#analyseren), [ontwerpen](#ontwerpen) en [bouwen](#bouwen).

### Analyseren
*In de analysefase inventariseer je wat er moet gebeuren om een taak uit te voeren.* .

<details>
<summary>Werkwijze</summary>

1. Uitleggen wat JSON data is.
2. Aan de hand van voorbeelden laten zien wat je met JSON dat kan doen.
3. JSON data van de OBA-API uitpluizen, wat staat er allemaal in de JSON? Hoe kun je hier de spannende boeken voor een bepaalde leeftijd uit halen?

#### Resources analyseren

- [OBA-API documentatie](https://zoeken.oba.nl/api/v1/)
- [JSON data](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)

</details>

### Ontwerpen
*In de ontwerpfase neem je ontwerpbeslissingen en zorg je dat je precies weet wat je moet gaan bouwen.*
<details>
<summary>Beschrijving</summary>

1. Voorbeelden bekijken van zoekformulieren en resultaatpagina's.
2. Wireflow schetsen met een zoekformulier en hoe de resultaten er uit komen te zien. De resultaten zijn spannenden boeken op leeftijd gefilterd. 
3. Annoteren welke techniek nodig is om de data op te halen en te renderen. 
4. Annoteren hoe je spannende boeken voor een bepaalde leeftijd kan opalen. Wat is de request url?

#### Resources ontwerpen

- Break-down schets maken

</details>

### Bouwen
*In de bouwfase realiseer je de beslissingen uit de ontwerpfase.*
<details>
<summary>Details</summary>

0. Er is al een HTML pagina met basis CSS waar de resultaten getoond kunnen worden. 
1. XMLHttpRequest opzetten
2. Data tonen in de console
3. Loop schrijven en html renderen
4. Stylen van de resultaten

#### Resources bouwen

- Met behulp van [XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest) of [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) kan een [JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) file worden geladen. Daarna kun je de HTML elementen aanmaken, de juiste content koppelen en aan de DOM toevoegen.
- Bij het laden van externe data kan de server verschillende [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) doorgeven, die kun je gebruiken om feedback te tonen.

</details>


### Integreren
*In de integratiefase voer je de aanpassingen door zodat iedereen ze kan zien.*

n.v.t.

### Testen
*In de testfase controleer je of jouw aanpassingen werken zoals bedoeld.*

n.v.t.

## Criteria
*Definitions of done*

1. Je hebt gezien hoe de data wordt van een externe bron ingeladen met Javascript.
2. Je hebt gezien hoe de zoekresultaten worden getoond in een webpagina.
3. Je hebt gezien hoe *HTTP response status codes* kunnen worden gebruikt en vormgegeven.

# Niveau van een leertaak

|   | Scaffolding | Description |
| ---: | :----   | :--- |
| a | Example | Uitgewerkt voorbeeld in het college |
| b | Duplicate | Immitatietaak in een workshop |
| c | Experiment | Taak zonder een specifiek doel |
| d | Extension | Aanvultaak |
| e | Autonomous | Taak zonder ondersteuning |

Meer over [Leertaken, complexiteit en begeleiding in Didactiek en toetsing](hhttps://github.com/fdnd/documents/blob/master/Bijlage%2006%20Didactiek%20en%20toetsing.md#leertaken)

# Werkwijze volgens de Development Life Cycle

Bij FDND gebruiken we voor de werkwijze de fasering van de Development Life Cycle. Leertaken kunnen een of meerdere fases doorlopen.

1. Analyse.
2. Design.
3. Bouwen.  
4. Integreren.
5. Testen.

Meer over de [Development Life Cycle in Didactiek en toetsing](hhttps://github.com/fdnd/documents/blob/master/Bijlage%2006%20Didactiek%20en%20toetsing.md#development-life-cycle)
