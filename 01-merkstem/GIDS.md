# Laag 1: Merkstem

## Waarom

Zonder merkstem schrijft Claude zoals Claude. Met een merkstem schrijft hij zoals jouw organisatie op haar beste dag. Dat verschil zie je pas als je de skill hebt: opeens hoef je de helft van je correcties niet meer te doen.

## Wat je verzamelt

- **Vijf tot tien teksten die goed klinken.** Pagina's van je eigen site, een sterke klantcase of een mail waar je trots op bent. Ze moeten van mensen zijn, niet van AI.
- **Drie teksten die níet klinken.** Ook van je eigen site. Benoem per tekst wat er mis is. Deze zijn net zo waardevol als de goede.
- **Je merkbegrippen.** De woorden en namen die je organisatie precies zo schrijft, met hoofdletters en al. Zet erbij wanneer je ze gebruikt en wanneer niet.
- **Je aanspreekvorm.** Je of u, wij of de organisatie, en de uitzonderingen.
- **Bestaande richtlijnen**, als die er zijn. Vaak liggen ze in een pdf die niemand meer opent.

## Bouwprompt

Plak dit in Claude, samen met je materiaal:

```
Ik wil een Claude-skill bouwen voor de merkstem van [organisatie].
Hieronder staan goede voorbeelden, slechte voorbeelden met wat er mis is,
onze merkbegrippen en onze aanspreekvorm.

Werk zo:
1. Lees alles en vat de stem samen in één alinea. Vraag of dat klopt.
2. Stel me daarna maximaal acht vragen over wat je nog niet weet:
   toon per teksttype, vaktermen, koppen en knoppen, wat we nooit doen.
   Eén vraag tegelijk.
3. Vul daarna het template in dat ik meestuur.
   Gebruik citaten uit mijn voorbeelden, verzin er geen.
4. Zet de zes Stop AI Slop-checks in de skill, als zelfcontrole voor oplevering.
```

## Testen

Geef de skill drie opdrachten: een korte webtekst, een mail en het herschrijven van een van je slechte voorbeelden. Leg de uitkomst naast een tekst die een collega schreef. Als je niet meer ziet welke van AI is, zit je goed.

## Valkuilen

- **Te veel regels.** Na veertig regels gaat Claude ze afvinken in plaats van schrijven. Begin met tien kernregels en zet de rest in de uitleg.
- **Alleen goede voorbeelden.** Juist "waar we zelf uitglijden" leert Claude waar de grens ligt.
- **Merkbegrippen overal.** Zet erbij dat ze spaarzaam gebruikt worden. Anders staat je propositie in elke alinea.
