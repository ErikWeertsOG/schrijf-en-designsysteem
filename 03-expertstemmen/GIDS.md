# Laag 3: Expertstemmen

## Waarom

Schrijf je voor anderen, zoals een directeur, een specialist of een collega met een LinkedIn-profiel, dan moet de tekst als die persoon klinken. Niet als je merk en niet als jij. Een merkstem is één stem. Een expert heeft er een eigen.

## De belangrijkste regel: elke post heeft een anker

Een anker is iets wat alleen deze persoon kan zeggen. Een scène uit een gesprek van vorige week, een eigen test, een cijfer uit de praktijk, een naam of een event. Zonder anker krijg je een mening die iedereen had kunnen hebben. Zet in de skill dat Claude zonder anker niet begint, maar eerst vraagt.

## Wat je verzamelt

- **Vijftien tot vijfentwintig posts of teksten van de persoon zelf.** Liefst van voordat er AI aan meeschreef. Dat is de belangrijkste les van deze laag, zie hieronder.
- **Een kwartier gesprek.** Neem het op en laat het uitschrijven. Zo hoor je hoe iemand praat in plaats van hoe hij schrijft.
- **Wie zijn publiek is** en wat hij nooit zou zeggen.

## Bouwprompt

```
Ik wil een Claude-skill bouwen die schrijft in de stem van [naam], [rol].
Hieronder staan [aantal] teksten die hij zelf schreef, plus een transcript.

Werk zo:
1. Analyseer de teksten: zinslengte, woordkeus, hoe posts beginnen,
   hoe ze eindigen, wat er tussen haakjes staat, waar hij hard is en waar mild.
   Tel echt: hoeveel posts eindigen met een vraag?
2. Laat me je analyse zien en vraag wat niet klopt.
3. Vul het template in. Gebruik alleen zinnen die hij echt schreef als voorbeeld.
4. Zet erin dat elke post een anker nodig heeft en dat je zonder anker eerst vraagt.
```

## Testen met een blindtest

Pak een post die de persoon zelf schreef. Laat de skill met dezelfde feiten een eigen versie maken. Leg beide aan twee mensen voor zonder te zeggen welke welke is. Vraag welke menselijker klinkt en op welke ze zouden reageren.

Kiezen ze de skillversie als AI, vraag dan waarom. Hun antwoord is je volgende aanpassing.

## Valkuilen

- **Trainen op AI-teksten.** Wie al met AI schrijft, schrijft eenvormiger. Bouw je daar een stem op, dan versterk je dat. Kijk of de posts in de AI-periode op elkaar gaan lijken. Eindigen ze allemaal met een vraag? Verdwijnen de grapjes en zijpaden? Dan gebruik je oudere teksten.
- **Te formeel.** Mensen klinken in een beschrijving altijd netter dan ze zijn. Het transcript corrigeert dat.
- **Geen herijking.** Stemmen veranderen. Kijk elk halfjaar of de skill nog klopt.
