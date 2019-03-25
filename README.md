# DHA Eindopdracht app - 2019 edition

## Opdrachtsomschrijving
De eindopdracht is een vrije opdracht. Dat wil zeggen: je hebt vrijheid om zelf functionaliteit te verzinnen. Wat wel vaststaat zijn onderstaande technische requirements. Om hieraan te voldoen moet je Hiervoor zul je doorgaanswel zelf wat functionaliteiten verzinnen, zoals bijvoorbeeld welke data je in lokale opslag gaat gebruiken. De app moet uiteraard ook een hybride app zijn, en in principe met Ionic gemaakt. Deze app moet nu ook voldoen aan de Angular Styleguide.

### Doorwerken met app-2 of nieuwe app
Je werkt in hetzelfde duo als voor app-2. Je mag een nieuwe opdracht maken. Maar je kunt voor deze opdracht doorwerken op je app-2 (incl. sensor afhandeling) en deze uitbreiden met wat *originele* functionaliteit.

Als je doorwerkt op app-2:
- Refactor zowel bestaande code als bestands- en foldernamen waar nodig, zodat deze voldoet aan de Angular styleguide (als je een nieuwe app start kun je vanaf het begin af aan hiermee rekening houden).
- Kopieer dan het relevante gedeelte uit die repository naar deze.
- Verwerk dan ook gegeven feedback hierop nog.
- Geef de interface een makeover, maak het intuitiever.
- Wees ook niet bang functionaliteit die minder werkt te schrappen!

>"Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away." - Antoine de Saint-Exupery

NB: Steek geen of weinig tijd in een backend, voor je eindcijfer is alleen je frontend van belang!

## Normering App 3 - Eindopdracht
Onder `1 Basiscijfer` staat een lijst van minimale vereisten voor een voldoende (6). Als je er één mist is het een knock-out. Onder `2` en `3` dan nog een lijst van punten waarmee jullie respectievelijk min- of juist pluspunten kunt halen. Je kunt minpunten compenseren met pluspunten. De docent kan een pluspunt ook deels toekennen. Een enkel missend vereist item kan evt. ook doorschuiven naar app-3, als het klein is en de app overall een voldoende indruk geeft.

### 1. Basiscijfer 6
Als voldaan is aan deze minimale vereisten:

- [ ] 1. Tijdig aanleveren voorstel App-3 (nieuw idee of significante uitbreiding App-2)
- [ ] 2. Kopieer deze README naar `beoordeling.md` en maak een eigen `README.md` met weer een 'how-to-run' en functioneel overzicht.
- [ ] 3. App werkt ook in je browser (afvangen van fouten door missende native functionaliteit en tonen nette melding gebruiker)
- [ ] 4. Ziet er overall goed uit, is responsive en crasht niet (of nauwelijks)
- [ ] 5. Heeft - net als App 2 - *niet* de standaard naam, app icon, splash screen of bundle identifier
- [ ] 6. De app is van jezelf, niet gekopieerd (e.g. app bevat aantal originele elementen in *1)
- [ ] 7. Voor tenminste één platform gebouwd
- [ ] 8. Code, folderstructuur en bestandsnamen voldoen aan *de link:https://angular.io/guide/styleguide[Angular Styleguide]*
- [ ] 9. De app slaat zaken *(lokaal!) op* (zoals settings, laatste level, eerdere gedane input)*
- [ ] 10. App bevat tenminste één (Angular) *custom component* (met attributen/parameters waaronder minstens 1 `@Input` en 1 `@Output`!)*
- [ ] 11. GEEN wachtwoorden opslaan in App (als toch perse nodig is, gebruik link:https://ionicframework.com/docs/native/intel-security/[IntelSecurity] of gelijkwaardig; NIET zelf security implementeren)
- [ ] 12. Gebruik kan op intuitieve manier invoer doen in app (bv. configuratie, sensor sensitiviteit, spelersniveau van game)
- [ ] 13. Schrijf unit tests voor cruciale/complexere functionaliteiten in je app (minsten 4 unit tests)
- [ ] 14. Schrijf in de README ook een reflectie op basis van de demo les (met evt. debat): Evaluatie app + hybrid vs. native*

**Add 14 Evaluatie:**
- Schrijf een korte evaluatie van je app en de nog te verbeteren punten.
- Vermeld feedback van medestudenten uit demo en wat je hier wel of niet mee gedaan hebt (en waarom).
- Een korte beschrijving van en reflectie op een functionaliteit in je app die wezenlijk anders te realiseren was geweest als je je app als native app had gerealiseerd (bv. makkelijker of moeilijker).

Zet dit alles in een kopje `reflectie` in je README.md of in een apart reflectie.md bestand waarnaar je linkt uit je README. Geef ook een eigen voorkeur voor native of hybrid inclusief motivatie. Of - als je geen directe voorkeur hebt - de criteria wanneer je voor het een of ander zou kiezen. Gebruik hierbij je eigen ervaringen tijdens de MAD course.

*1) De functionaliteit mag wel bestaan, maar is geen directe kopie van een bestaande appstore 'kraker', of heeft tenminste een originele twist, nieuwe doelgroep oid.

### 2. Minpunten (of knockouts)
- [ ] M1. Te laat ingeleverd (uiterlijk) **-1**
    - Op tijd **-0**
    - Halve week te laat **-0.5**
    - Week te laat **-1.0**
    - Meer dan week te laat: **knock-out**, volgende blok inleveren
- [ ] M2. Smelly code _max **-1_**
    - Geen onlogische variabele namen, alles netjes in services, SOLID **-0**
    - Veel gebruik global scope, te grote methodes, weinig SOLID **-0.5**
    - Onlogische code, geen services, of hele grote methodes, niet SOLID **-1.0**
    - Onbegrijpelijke of zonder begrip gecopy-paste code: **knock-out**
- [ ] M3. Buggy max **-1**
    - App crasht in zeldzaam geval, oorzaak is beschreven in README met link naar oorzaak/issue en niet op te lossen **-0**
    - App crasht in zeldzaam geval, oorzaak is niet beschreven maar goede mondelinge toelichting **-0.5**
    - App crasht af en toe om voorkombare reden of reden is niet beschreven of onderzocht **-1**
    - App crasht structureel: **knock-out**
- [ ] M4. Crappy layout **max -1**
    - Een of twee onvolkomenheden **-0.25**
    - Meer onvolkomenheden **-0.5**
    - Geen zorg aan layout besteed **-1.0** 
    - App is alleen usable voor developer: **knock-out**
- [ ] M5. Onduidelijke of ontbrekende evaluatie en/of reflectie in README **max -2**
    - Leesbare en begrijpelijke evaluatie en reflectie **-0**
    - Geen aanpassingen gedaan zonder motivatie **-0.5**
    - Geen of een onduidelijke of onleesbare evaluatie of reflectie geschreven **-1**
    - Geen evaluatie en geen reflectie opgenomen **-2**

### 3. Pluspunten
Uiteraard kun je maximaal maar 4 van de 5 mogelijke bonuspunten halen voor een 6+4=10.

- [ ] P1. App werkt op 2 of meer platformen via platformspecifieke code **max +0.5**
    - Ionic doet al het werk voor je (geen platformspecifieke code) **+0**
    - Minor tweaks mits ook enigszins functioneel toepasselijk (`platform.is`) **+0.25**
    - Complexere en toepasselijk **+0.5**
- [ ] P2. Multi 'form factor'/responsive design **max +0.5**
    - Alleen meeschalen/aanpassen door gebruik Ionic componenten **+0**
    - Serieus gebruik Ionic grid of simpele media query/JS (buiten Ionic) **+0.25**
    - Toepasselijk tonen/verbergen elementen in landscape/portrait of tablet, retina e.d. **+0.5**
- [ ] P3. Meerdere integraties **max +0.5**
    - Geen extra integraties t.o.v. App-2 **+0**
    - Simpel uitlezen, bv. simpele rest API/.json bestand **+0.25**
    - Toepasselijk gebruik van externe API (via http) en/of wrappen van externe library in eigen service (NB code werk in eigen (backend) API's wordt NIET beloond) **+0.5**
- [ ] P4. PWA met tenminste één PWA specifieke implementatie **max +1**
    - Basis PWA van Ionic met triviale service worker **+0**
    - Werkende en non standaard service worker (met bv. Google `workbox`) + 0.25
    - Lighthouse richting 100% score en ook functioneel toepasselijke gebruik bv. push notifications +0.5 tot max **+1**
- [ ] P5. Gebruikt meerdere sensoren op toepasselijke manier **max +0.5**
    - Geen andere sensors dan 1e 2 in App-2 **+0**
    - Niet zo toepasselijk gebruik van extra sensor **+0.25**
    - Toepasselijk gebruik van sensor met custom visualisatie van opgehaalde data in app **+0.5**
- [ ] P6. Goed en toepasselijk gebruik RxJS operators _max +0.5_
    - Geen extra RxJS t.o.v. app-2 of enkel gebruik van `.subscribe`  of `Observable.` of niet functioneel gebruik +0
    - Triviaal maar wel functioneel gebruik van een of meer RxJS operators +0.25
    - Verwerkt merendeel van logica binnen RxJS +0.5
- [ ] P7. Verspreid in een AppStore / Play Store o.i.d. **max +0.5**
    - Basic/niet te vinden **+0**
    - Energie in promotie gestoken zoals mooie custom icon, aantrekkelijke beschrijving **+0.25**
    - Veel energie in gestoken, promotie truc o.i.d. **+0.5**
- [ ] P8. Vrije toevoeging (ter beoordeling docent, oftewel subjectief) **max. +1**
    - Tsja **+0**
    - Phat **+0.25**
    - Phatter **+0.5**
    - Phatst **+1.0**
