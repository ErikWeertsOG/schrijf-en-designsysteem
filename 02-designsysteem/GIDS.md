# Laag 2: Designsysteem

## Waarom

Een tekst in je merkstem op een generieke slide is nog steeds een generieke slide. Je designsysteem zorgt dat Claude een deck, een pdf of een social visual maakt die meteen op je huisstijl lijkt.

De belangrijkste les: een designskill is vooral een **routekaart**. Een deck bouw je anders dan een whitepaper en een drukwerkflyer weer anders dan een webpagina. Laat de skill eerst de route kiezen, dan pas de kleuren.

## Wat je verzamelt

- **Je live website.** Daar haal je de echte tokens vandaan: kleuren, lettertypes, spacing, knoppen.
- **Logo's** in svg en png, in licht en donker.
- **Lettertypes** als bestand, of de naam van de Google Font.
- **Officiële templates** die er al zijn: een PowerPoint-template, een Word-template, Canva-sjablonen.
- **Drie voorbeelden die goed zijn** en drie die van de huisstijl afwijken.

## Stap 1: maak een DESIGN.md van je site

DESIGN.md is een open conventie om een designsysteem vast te leggen in één bestand: tokens bovenin, uitleg eronder. Zie [google-labs-code/design.md](https://github.com/google-labs-code/design.md). Het [template](DESIGN-template.md) in deze map volgt die opzet.

Heb je Claude in Chrome, laat Claude dan je homepage openen:

```
Open [url] in de browser. Maak één screenshot van de viewport
en lees de tekst en de CSS-variabelen van de pagina.
Vul daarmee het DESIGN-template in dat ik meestuur.
Verzin geen tokens: wat je niet ziet, laat je leeg.
```

Zonder browser maak je zelf een screenshot en plak je die in de chat.

## Stap 2: bouw de skill

```
Ik wil een Claude-skill bouwen voor de visuele huisstijl van [organisatie].
Ik stuur mijn DESIGN.md, mijn logo's en een lijst van templates die er al zijn.

Werk zo:
1. Vraag welke formats ik maak: deck, pdf-rapport, one-pager,
   social visual, webpagina, drukwerk. Eén vraag tegelijk.
2. Bepaal per format de route: welk template, welke tool, welk bestandstype.
3. Vul het SKILL-template in. Zet de route bovenaan, de tokens daaronder.
4. Voeg per route een QA-check toe die je doet voordat je oplevert.
```

## Testen

Vraag een one-pager, een slide en een LinkedIn-visual over hetzelfde onderwerp. Leg ze naast iets wat je ontwerper maakte. Kijk naar kleur, maar vooral naar witruimte en hiërarchie. Daar zie je AI-design meestal aan.

## Valkuilen

- **Alleen kleuren en fonts.** Dan krijg je de juiste kleuren in de verkeerde opbouw. Beschrijf ook de visuele taal: hoeveel witruimte, welke vormen, wat je nooit doet.
- **Officiële templates negeren.** Bestaat er een PowerPoint-template, laat de skill dan daarop bouwen en niet zelf iets namaken.
- **Geen "bekende gaten".** Schrijf op wat de skill nog niet goed kan. Dan weet je waar je zelf moet opletten.
