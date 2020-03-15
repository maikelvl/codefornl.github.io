---
title: "De voordelen van Open Source ontwikkelen"
excerpt: "Vertaling van: The benefits of coding in the open oorspronkelijke auteur: Anna Shipman"
lang: nl
date: 2017-10-21
author: Johan Groenen
layout: blog
---

Vertaling van: [The benefits of coding in the open](https://gds.blog.gov.uk/2017/09/04/the-benefits-of-coding-in-the-open/) oorspronkelijke auteur: [Anna Shipman](https://gds.blog.gov.uk/author/anna-shipman/)

Onderstaande tekst is gepubliceerd door Government Digital Services (GDS), de afdeling voor ontwikkeling van digitale diensten van het Verenigd Koninkrijk (VK).

----

Voor een digitale dienst in het VK mag worden gepubliceerd, moet deze voldoen aan de _Digital Service Standard_, een lijst van 18 criteria.

Één van die criteria is dat alle programmacode openbaar en onder een open source licentie is gepubliceerd.

Dit gaat samen met het design principe “maak het open, dat maakt het beter”.

Waarom dat zo is, leest u hieronder.

# Het bevordert een goede manier van werken

Als je weet dat iemand meekijkt, dan let je nét iets beter op je tellen. Je bent net wat meer geneigd om beter te documenteren wat je hebt gedaan. Je zorgt ervoor dat je code veilig is, door geheimen (bijvoorbeeld wachtwoorden) buiten je code te houden. Je bent beleefd en constructief in je reacties op code, en volgt goede architectuurprincipes.

Al met al: als mensen je werk kunnen zien, dan staat er net iets meer op het spel.

# Het maakt samenwerken makkelijker

Als de code open source is, wordt het eenvoudiger om met andere samen te werken. Je hoeft ze geen speciale toegang te verlenen, of moeilijke afspraken te maken. Je hoeft niet eens bij elkaar op dezelfde plek te zitten.

Iemand van 18F bijvoorbeeld, de organisatie die digitale diensten maakt voor de overheid van de Verenigde Staten, [kan eenvoudig een collega van Government Digital Services in het Verenigd Koninkrijk helpen](https://gdstechnology.blog.gov.uk/2017/07/18/coding-in-the-open-makes-better-code/) met het schrijven van een stukje code.

Dat kan, omdat beide partijen open source programmeren. En zo leverde [samenwerking met de Australische overheid](https://governmenttechnology.blog.gov.uk/2016/09/06/celebrating-sharing-and-reusing-the-digital-marketplace/) een eigen Digitale Marktplaats op.

Dichter bij huis zorgt het ervoor dat het eenvoudiger is om samen te werken met andere departementen en (overheids)organisaties.

# Externe gebruikers kunnen helpen

Open source programmacode maakt het mogelijk voor personen die niet voor je werken om verbeteringen aan te brengen (of voor te stellen) in je code.

Zo konden actieve burgers verbeteringen aanbrengen in de [Government Petitions Service](https://petition.parliament.uk/). Iemand voegde bijvoorbeeld [de ingeroosterde datum](https://github.com/alphagov/e-petitions/pull/456) toe voor debatten. Iemand anders maakt een aanpassing die [het aantal handtekeningen in real-time](https://github.com/alphagov/e-petitions/pull/482) liet zien.

Op die manier kunnen mensen hun eigen problemen oplossen. Ze kunnen kleine verbeteringen maken die misschien niet bovenaan de prioriteitenlijst staan van de ontwikkelende organisatie, en op die manier ook helpen om je code robuuster te maken.

# Anderen kunnen van je leren

Als je programmacode open is, kunnen mensen leren van wat jij hebt geleerd tijdens het ontwikkelen.

Zo gebruikte _Skills Funding Agency_ de code van GOV.UK’s _Smart Answers_ [om een toepassing te maken](https://sfadigital.blog.gov.uk/2016/11/17/when-build-a-thing-really-works/) voor hun opleidingsdienst. Dat kostte ze daardoor minder dan een week.

Zonder dit voorbeeld had dit minstens twee maanden in beslag genomen.

# Het maakt standaarden delen makkelijker

Met open source code kun je heel eenvoudig meekijken met andere teams. Dat zorgt voor een gemeenschappelijke manier van werken en een gedeelde manier van oplossen van bepaalde problemen.

Vaak maken teams dan kleine verbeteringen in het werk van andere teams. Zo maakte een teamlid van GOV.UK een [aanpassing aan GOV.UK Verify](https://github.com/alphagov/verify-frontend/pull/255).

GOV.UK publiceert [coding style guides](https://github.com/alphagov/styleguides/). Hierdoor is het voor iedereen eenvoudig om deze te vinden en te gebruiken.

# Het zorgt voor meer transparantie

Als code open source wordt ontwikkeld, dan zie je meteen waar het geld naartoe gaat.

Het bevordert openheid, ook op andere vlakken. Zo is de [GOV.UK roadmap](https://insidegovuk.blog.gov.uk/2017/02/13/the-2017-to-2018-gov-uk-roadmap/) open, en ook gebruikt één van de GOV.UK teams een [publiek Trello bord](https://trello.com/b/7yWk0jhI/govuk-publishing-platform-tap-support-planning).

Als er af en toe wat mis gaat op GOV.UK, dan onderzoeken we dat en [publiceren we een rapport](https://insidegovuk.blog.gov.uk/category/incident-reports/). Het is belangrijk om te laten zien hoe we leren van onze fouten.

# Het maakt duidelijk wie de eigenaar is

We willen een overheid die verantwoordelijkheid neemt en actief zelf zijn diensten doorontwikkelt. Onduidelijkheid over intellectueel eigendom kan leiden tot welles-nietes spelletjes.

Open source code zorgt ervoor dat copyright en intellectueel eigendom vanaf het begin duidelijk zijn. De _Service Standard_ verplicht dat GDS code onder een open source licentie gepubliceerd wordt (bij GDS gebruiken ze MIT). Daarnaast is al het werk dat de medewerkers van GDS doen als ambtenaar beschikbaar onder _Crown copyright_.

Wanneer overheidsdiensten projectcode wilden aanpassen, was er vaak onduidelijkheid over intellectueel eigendom. Dit probleem vooraf ondervangen is erg waardevol. Het betekent dat een afdeling een leverancier kan aannemen om aan een alfa-versie te werken, en later kan overstappen naar een andere club voor een beta-versie, zonder dat werk verloren gaat.

Ze kunnen zelfs teams vormen van meerdere leveranciers die zonder problemen aan dezelfde code kunnen werken.

Dit voorkomt _lock-in_. Zonder deze helderheid kan de software die speciaal voor jou gemaakt is ervoor zorgen dat je nooit kan overstappen naar een andere aanbieder.

Lock-in voorkomen kan de overheid dus veel geld besparen.

# Het zorgt voor samenhang tussen overheidssoftware

Mensen die verhuizen van afdeling kunnen op dezelfde manier blijven werken, met dezelfde digitale middelen. Dat bespaart tijd en geld. Ze kunnen vrijelijk hun kennis delen van projecten waar ze aan werken, omdat alles open is.

Zo heeft iemand van GDS die verhuisde naar een andere afdeling [bijgedragen aan de single sign-on dienst](https://github.com/alphagov/signon/pull/509).

In de toekomst zal dit ervoor zorgen dat er meer uniformiteit is in werkplekken door de overheid heen, omdat mensen overal de beste tools gaan gebruiken.

# Open Source repositories maken het werk simpeler

Als je vanaf het begin op een open source manier code maakt, dan moet je op ieder moment dat je code publiceert het nieuwe stuk code kritisch bekijken.

Als je dat niet vanaf het begin doet, maar een codebase later open wil maken, moet je door de hele code en geschiedenis van die code heen, om te zien dat er niks in zit dat niet publiek mag worden gemaakt. Dat is vaak een zeer veel extra werk.

# Maak je eigen code open!

Veel mensen denken dat hergebruik het grootste voordeel is van open source programmeren. Bovenstaande laat hopelijk zien dat hergebruik eerder mooi meegenomen is, en dat er grotere voordelen zitten aan open source werken.

Bekijk ook de GDS [open code](https://github.com/alphagov/) en [richtlijnen](https://www.gov.uk/service-manual/technology/making-source-code-open-and-reusable).