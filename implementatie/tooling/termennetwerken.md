# termennetwerken

Zoals beschreven in de strategie ([link met andere databronnen](../strategie-tot-implementatie.md#3.-link-met-andere-databronnen)) is het belangrijk om bij het registreren voldoende rekening te houden voor het toekennen van URIs die verwijzen naar andere termennetwerken. Zo verrijk je niet enkel de fiches inhoudelijk, maar verzeker je ook dat de gepubliceerde data aansluiting en verbinding vindt met andere datasets.&#x20;

## gebruikte termennetwerken: nationaal/regionaal

### [Inventaris onroerend erfgoed ](https://inventaris.onroerenderfgoed.be)

_Deze inventaris geeft je een overzicht van het waardevolle erfgoed in Vlaanderen. Zowel archeologisch, bouwkundig, landschappelijk als varend erfgoed zijn opgenomen, goed voor meer dan 90.000 erfgoedobjecten in totaal._&#x20;

wordt gebruikt voor het verwijzen naar afgebeelde gebouwen (zowel in het geval van associaties en iconografische beschrijvingen). Daarnaast kan het ook gebruikt worden voor het verwijzen naar een plaats waar het object zich bevindt tijdens een gegeven event (tentoonstelling, productie, vervaardiging, herkomst).

{% hint style="info" %}
**correcte verwijzing:** [ **https://id.erfgoed.net/themas/**](https://id.erfgoed.net/themas/2909)**{id}**\
****voorbeeld: [ https://id.erfgoed.net/themas/2909](https://id.erfgoed.net/themas/2909)\
\
in adlib/axiell via velden; \
bron: [ https://id.erfgoed.net/themas/](https://id.erfgoed.net/themas/2909)\
nummer: {id}
{% endhint %}

{% tabs %}
{% tab title="json-ld (LDES)" %}
```
InformatieObject.gaatOver: [
    {
        @type: "Entiteit",
        Entiteit.type: [
    {
    @id: " https://id.erfgoed.net/themas/2909",
    skos:prefLabel: {
        @value: "Kleine Vismarkt",
        @language: "nl"
        }
    },
    {
        @id: "cest:Naam_geassocieerd_concept",
        label: "associatie.onderwerp"
    }
]
```
{% endtab %}
{% endtabs %}

### [databank kunstenpunt ](https://data.kunsten.be)

####

### fashion thesaurus (MoMU)

### thesaurus van Belgische fotografen (FoMU)

## gebruikte termennetwerken: internationaaal

### AAT (Getty Vocabularies)

### ULAN (Getty Vocabularies)

### TGN (Getty Vocabularies)



&#x20;
