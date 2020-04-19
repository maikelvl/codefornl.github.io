---
title: "Samenwerken doorbreekt vendor lock-in!"
excerpt: "Het gebruik van open source software levert kansen om leveranciersafhankelijkheid te verkleinen en tegelijkertijd de kwaliteit van dienstverlening te verhogen"
lang: nl
date: 2018-01-11
author: Edo Plantinga
cover: cogs.jpg
layout: blog
---


Het gebruik van open source software levert kansen om leveranciersafhankelijkheid te verkleinen en tegelijkertijd de kwaliteit van dienstverlening te verhogen. Zo lezen we in het actieplan van Nederland Open in Verbinding uit 2007. NOiV zou het gebruik van open source software en open standaarden binnen de overheid stimuleren. Fast forward naar 2017 en we zien dat er nog te weinig is veranderd.

Waar bij techreuzen Google, Facebook en zelfs Microsoft open source inmiddels business as usual is, kampen we bij de overheid nog altijd met een [vendor lock–in](https://nl.wikipedia.org/wiki/Vendor_lock-in) van gesloten (proprietary) software waar je u tegen zegt. Wat betekent dat voor gemeenten?

De vendor lock-in levert verschillende problemen op. Ten eerste zijn er de voorspelbare eenzijdige [prijsverhogingen](https://www.nrc.nl/nieuws/2015/10/17/gegijzeld-door-de-softwareboer-1545991-a1196802), gevolgd door [nog meer](http://www.binnenlandsbestuur.nl/digitaal/nieuws/prijsverhogingen-vicrea-40-tot-1150-procent.9550958.lynkx) prijsverhogingen.

Ten tweede levert het gesloten model een versnippering op. Ondanks dat de processen bij gemeenten meer overeenkomsten dan verschillen bevatten, is de gemeentelijke ICT nog altijd ingericht volgens de legacy van waar vijftig jaar geleden toevallig de kaartenbak stond. Niks centrale doorontwikkeling. Een beetje alsof elk filiaal van de Albert Heijn niet alleen verantwoordelijk voor zijn eigen assortiment is (dat is logisch), maar ook ieder filiaal zelf zijn ICT-leverancier mag kiezen en de bijbehorende processen mag inrichten (dat is nergens voor nodig). Als je alleen al kijkt naar de diensten die achter DigiD hangen, dan zie je hoeveel geld er wordt uitgegeven aan DigiD-koppelingen en bijbehorende security assessments voor varianten van oplossingen die functioneel praktisch hetzelfde zijn. Simpeler gezegd: we vinden het wiel te vaak opnieuw uit. Dat deze situatie onnodig veel geld kost behoeft geen betoog.

Een gevolg van het versnipperde ICT landschap is bovendien dat er een grote barrière is om gezamenlijke online dienstverlening te ontwikkelen, zoals onder de vlag van [Samen Organiseren](https://ibestuur.nl/tags/samen+organiseren/) de bedoeling is. Als je deze gezamenlijke dienstverlening landelijk wilt uitrollen, zul je die vaak moeten integreren aan de voorkant (de website) én aan de achterkant (de backoffice). En dat keer 388 gemeenten, voor alle online diensten. Wederom een dure grap.

Ten derde loopt de kwaliteit van de dienstverlening bij veel gemeenten achter. De meeste gemeenten hebben onvoldoende budget, kennis en volwassen opdrachtgeverschap om de digitale dienstverlening ingrijpend te verbeteren. Reden te meer om de krachten te bundelen.

Het gevolg van dit alles? De overheid loopt achter de feiten aan. Waar veel bedrijven al bezig zijn met innovaties zoals dienstverlening over kanalen heen, chatbots en spraakinterfaces, staat het thema digitale dienstverlening bij veel gemeenten nog in de kinderschoenen. Bij een recente presentatie van [Gebruiker Centraal](http://www.gebruikercentraal.nl/) bij [Cascadis](https://www.cascadis.nl/community/), de vereniging waar veel gemeentelijke webprofessionals lid van zijn, bleek dat nog geen kwart van de mensen in de zaal ook maar basale usability onderzoeken hadden gedaan (zoals simpelweg eens naast een gebruiker gaan zitten die een digitale dienst probeert af te nemen). Ondertussen verwachten burgers en ondernemers van de overheid dat de kwaliteit van dienstverlening op een vergelijkbaar niveau ligt als bij het bedrijfsleven. Deze kloof zal, als we zo doorgaan, er niet kleiner op worden.

# Landelijk ontwikkelde dienstverlening: waarom lukt het niet?

Het verder landelijk ontwikkelen van de online dienstverlening voor gemeenten is niet meer dan logisch. Maar laten we wel wezen: dat was het tien jaar geleden ook. Dus laten we eerst eens kijken waarom we nog te weinig stappen gemaakt hebben.

Allereerst is de autonomie van gemeenten als te belangrijk beschouwd, ook op het gebied van de inrichting van processen. Combineer dat met een een sausje van not invented here en het gevolg is dat we het wiel vaak opnieuw uitvinden. De centrale coördinatie en belangenbehartiging ontbreekt.

In de tweede plaats is er ook een praktische reden: gemeentelijke processen zijn ingewikkeld en bevatten veel koppelingen naar diverse systemen. Om een gezamenlijk gebruikt proces in te richten, heb je al snel veel afhankelijkheden. Dit maakt de uitrol van centraal ontwikkelde diensten complex: zo heeft de uitrol van de [centrale voorziening](http://koop.overheid.nl/producten/drop) voor decentrale regelgeving jaren geduurd.

De wil om de situatie van versnippering en leveranciersafhankelijkheid te doorbreken is er gelukkig met initiatieven als de [Plus 1-gemeente](https://ibestuur.nl/weblog/radicaal) en Samen Organiseren. Het versnipperde landschap aan ICT-leveranciers, die veelal met een businessmodel op basis van closed source software werken, is daarbij een risico.

Welke stappen kunnen we nemen om deze situatie te veranderen?

# Begin met de website

Aan de kant van de backoffice is het lastig om de situatie te doorbreken, omdat het zo dicht op het primaire proces zit met de bijbehorende afhankelijkheden. Zelfs een not-for-profit ICT-coöperatie als Wigo4it weet nog maar weinig voet aan de grond te krijgen buiten de vier oprichtende gemeenten.

Gelukkig ligt dat anders aan de voorkant: bij de websites van gemeenten. De website vormt immers het startpunt van de meeste online transacties. Het zou een hoop schelen als de integraties van centrale online dienstverlening aan de voorkant sneller zouden verlopen, doordat gemeenten gebruik zouden maken van dezelfde open source basis. Dit heeft veel voordelen:

* Het wordt makkelijker om centrale voorzieningen te ontwikkelen. De integratie met de voorkant is er immers al, zodat alleen de backoffice integratie nodig is. Ook geen sinecure, maar het scheelt een hoop werk. Vanuit een open source basis aan de kant van de website, wordt het steeds makkelijker om delen van de backoffice ook stukje bij beetje meer open source te maken. Dit lijkt een haalbaarder strategie dan bij de backoffice te beginnen.

* Geen vendor lock-in, maar samenwerkende leveranciers. In dit model werken leveranciers samen, in plaats van elkaar te beconcurreren met software met vergelijkbare functionaliteiten. Is dat naïef gedacht? Zeker niet, want het gebeurt al. De code van ‘Drupal voor Gemeenten’ is bijvoorbeeld al vrij te downloaden, ook voor concurrerende leveranciers. Het bedrijfsmodel van open source leveranciers is simpelweg anders: ze hanteren geen abonnementsvorm (met bijbehorende lock-in), maar werken uurtje factuurtje. Dat is een prima duurzaam bedrijfsmodel, getuige het bloeiende ecosysteem.

* Vrijheid om zelf de ontwikkeling in-house te doen. Wil je als gemeente nog minder afhankelijkheid van externe leveranciers? Dan staat bij dit model niets je in de weg om zelf ontwikkelaars aan te nemen en zelf de diensten door te ontwikkelen.

* Innovatie stimuleren. Als je op een open manier ontwikkelt met losgekoppelde API’s, stel je andere partijen in staat binnen een ecosysteem te innoveren. Een soort app-store voor de overheid.

* Meeliften met innovaties. Je lift mee op de grotere golf innovaties van de achterliggende internationale open source communities, waaraan duizenden ontwikkelaars werken. Internationale standaarden (zoals WCAG2 voor toegankelijkheid en OWASP voor security) krijg je daarbij vaak al cadeau, evenals duizenden modules met extra functionaliteit, die je kunt hergebruiken en naar eigen inzicht kunt aanpassen.

* Et cetera. Hiernaast zijn er diverse andere [voordelen van open source ontwikkelen](../de-voordelen-van-open-source-ontwikkelen) in de overheid.

Wil dit model haalbaar en toekomstvast zijn, dan moet de basis van deze (bestaande) open source software aan een aantal kenmerken voldoen.

Ten eerste moet er een levendige community van bedrijven en ontwikkelaars zijn rondom de software, zowel internationaal als nationaal. Zo heb je een volwassen basis, lift je mee op de grote golf van internationale doorontwikkelingen en heb je op nationaal niveau een ruime keuze aan leveranciers.

Ten tweede moet je zorgen dat je content en interacties met gebruikers [niet volledig vervlochten](https://css-tricks.com/what-is-a-headless-cms/) zijn met je front end software. Momenteel vindt dienstverlening voornamelijk plaats via je website, maar dit zal [niet lang meer duren](https://dri.es/the-big-reverse-of-the-web). Technologieën als chatbots, voice control en Internet of Things zijn snel in opkomst. Bedrijven als [Albert Heijn](https://tweakers.net/nieuws/130113/albert-heijn-gaat-app-uitbrengen-om-boodschappen-te-bestellen-via-google-home.html) en [KLM](https://tweakers.net/nieuws/130061/klm-laat-passagiers-tickets-kopen-via-messenger-chatbot.html) zijn hier al druk mee bezig en het zal niet lang duren voordat de overheid hier ook in mee moet. Bovendien: ook nu al zie je dat veel content te vinden is buiten je eigen website: denk aan Facebook, apps of content op sites van derden. Je architectuur moet deze ontwikkelingen niet in de weg staan.

Tot slot moet je de online diensten volgens het Software-As-A-Service (SAAS) model kunnen aanbieden, zoals het [Platform Rijksoverheid Online](https://www.communicatierijk.nl/vakkennis/r/rijkswebsites-aanbevolen-dienstverlening/platform-rijksoverheid-online) dit ook doet. Grotere gemeenten zullen immers graag de vrijheid hebben om hun software naar eigen inzicht aan te passen, maar kleinere gemeenten zullen wellicht liever gebruik maken van standaard functionaliteit die laagdrempelig beschikbaar is.

# We zijn er bijna

Tijd voor het goede nieuws. Er is al veel volwassen open source front end software beschikbaar, onder meer op het gebied Content Management Systemen (CMS-en). Proprietary software verliest daardoor steeds meer terrein, ook [binnen gemeenten](https://www.200ok.nl/cms-gemeenten/). We hoeven dus niet vanaf nul te beginnen. Specifiek voor gemeenten zijn er al drie smaken CMS-en met een grote adoptie: [Typo3Gem](https://www.typo3gem.nl/), [‘Drupal voor Gemeenten’](http://drupalvoorgemeenten.nl/) en [WIM](https://www.wimgemeenten.nl/algemene-informatie-wim)(Website en Intranet Model). Als we de adoptie van dit soort initiatieven verder stimuleren en de klantinteracties die integreren met deze CMS-en steeds verder uitbouwen en ontwikkelen, dan ligt daar een sleutel om de leveranciersafhankelijkheid van gemeenten te doorbreken. Het voordeel van deze strategie is dat het geen big bang hoeft te zijn.

Door stapsgewijs nieuwe functionaliteiten toe te voegen, wordt het steeds aantrekkelijker voor gemeenten om aan te haken en zo ontstaat er een sneeuwbaleffect. De adoptie wordt nog eens vergroot door steeds meer functionaliteit als SAAS aan te bieden. Vanuit een stevige open source basis aan de front end, kun je steeds meer richting de back end bewegen. Die basis impliceert overigens niet dat er ook een centraal beheer moet zijn: de kracht van open source communities ligt er juist in dat iedereen decentraal kan blijven innoveren en deze innovaties weer kan teruggeven aan de community.

# Van vendor lock-in naar samen organiseren

Nu heb ik geen illusies. Samenwerken is niet makkelijk. We bevinden ons nog steeds in een situatie waarin bestuur en management het belang en de mogelijkheden van ICT & online onvoldoende erkennen. Een situatie waarin elke aanbesteding op zich staat en er bijna nooit budget is voor het terugleveren van functionaliteit aan de community. Laat staan dat de budgetten toereikend zijn om voldoende webprofessionals aan te nemen. Maar we móeten wel samenwerken. Het is de enige manier om vendor lock-in te doorbreken en de kwaliteit van de online dienstverlening te vergroten.

Om de situatie te doorbreken hebben we een krachtig samenwerkingsverband nodig voor alle gemeenten die dit stimuleert. Het wordt de hoogste tijd om dit ook [samen te organiseren](https://vng.nl/samen-organiseren). En daarbij niet te lullen, maar te poetsen en te focussen op het eindresultaat: werkende software en diensten die daadwerkelijk door burgers gebruikt worden. Zo blijft die ideale burgergerichte open ontwikkelde +1-gemeente geen [droom](https://platformoverheid.nl/artikel/de-droom-van-de-1-gemeente), maar wordt hij werkelijkheid.


[Edo Plantinga](https://www.linkedin.com/in/edoplantinga/) is projectleider & productowner in de online overheid en mede-initiatiefnemer van de overheidsbrede kenniscommunity Gebruiker Centraal.

Dit artikel werd eerder gepubliceerd op [iBestuur](https://ibestuur.nl/weblog/samenwerken-doorbreekt-de-vendor-lock-in).
