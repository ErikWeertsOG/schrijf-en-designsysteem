# Bouw je eigen schrijf- en designsysteem met Claude

Ik schrijf elke dag met AI. Webteksten, blogs, LinkedIn-posts voor mezelf en voor experts, decks en whitepapers. Een jaar geleden klonk alles wat eruit kwam hetzelfde: glad, netjes en van niemand.

Een betere prompt loste dat niet op. Wat hielp, was een systeem van skills die op elkaar voortbouwen. Elke skill doet één ding en weet van de andere.

Dit repo deelt geen kant-en-klaar systeem. Mijn eigen skills zijn van mijn werkgever en van de mensen voor wie ik schrijf. Je krijgt de bouwtekening: per laag waarom hij er is, een prompt waarmee Claude je erdoorheen interviewt, een leeg template en de fouten die ik al gemaakt heb.

Je hebt geen programmeerkennis nodig. Wel een paar avonden.

## De zes lagen

```
0. Stop AI Slop         harde checks die in elke schrijfskill zitten
1. Merkstem             hoe jouw organisatie klinkt
2. Designsysteem        hoe jouw organisatie eruitziet, per format
3. Expertstemmen        hoe de mensen klinken voor wie je schrijft
4. Doelgroeptoets       persona's die je tekst afkraken voor je publiceert
5. Pipeline             de keten die alles aan elkaar knoopt
```

Bouw ze in deze volgorde. Elke laag leunt op de vorige. Een pipeline zonder goede merkstem levert alleen sneller middelmaat op.

| Laag | Map | Tijd |
|---|---|---|
| 0 | [Stop AI Slop (NL)](https://github.com/ErikWeertsOG/stop-ai-slop-nl) | 10 minuten |
| 1 | [01-merkstem](01-merkstem/GIDS.md) | één avond |
| 2 | [02-designsysteem](02-designsysteem/GIDS.md) | één à twee avonden |
| 3 | [03-expertstemmen](03-expertstemmen/GIDS.md) | een uur per persoon |
| 4 | [04-doelgroeptoets](04-doelgroeptoets/GIDS.md) | één avond |
| 5 | [05-pipeline](05-pipeline/GIDS.md) | een uur |

## Zo werk je elke laag af

1. Lees de `GIDS.md` van de laag.
2. Verzamel het materiaal dat in de gids staat. Dat is het echte werk, de rest gaat snel.
3. Plak de bouwprompt uit de gids in Claude, samen met je materiaal. Claude stelt je vragen en vult daarna het template in.
4. Test de skill op een echte opdracht. Klopt het niet, zeg dan precies wat er mis is en laat Claude de skill aanpassen.
5. Installeer de skill. In Claude upload je hem als zip bij Skills in je instellingen. In Claude Code zet je de map in `~/.claude/skills/`.

## Drie dingen die ik te laat leerde

**De anti-slop-check hoort ín elke skill.** Ik had eerst een losse humanizer die ik er achteraan draaide. Dan schrijft Claude eerst slop en poetst hem daarna op. Als de regels in de schrijfskill zelf staan, loopt Claude zijn eigen tekst na voordat jij hem ziet.

**Train een stem op tekst van vóór de AI.** Mijn eerste expertstemmen bouwde ik op recente posts, maar daar schreef AI al aan mee. De stem werd een kopie van een kopie: gladder, eenvormiger en elke post eindigde met een vraag. Pak teksten van voordat iemand AI gebruikte.

**Laat één stop over voor jezelf.** Ik wilde alles automatisch. De beste versie van mijn pipeline rijdt de mechanische stappen door en stopt één keer, na de doelgroeptoets. Welke kritiek je verwerkt, is een redactionele keuze en die maak jij.

## Zelf aanpassen

Dit is een begin en geen eindpunt. Bouw je een laag die hier ontbreekt, of loop je tegen iets aan dat niet klopt? Open een issue. Ik leer er net zo veel van als jij.

---

Gemaakt door [Erik Weerts](https://github.com/ErikWeertsOG), Lead Content Marketeer. Elke tekst in dit repo heeft de [zes checks](https://github.com/ErikWeertsOG/stop-ai-slop-nl) doorlopen.
