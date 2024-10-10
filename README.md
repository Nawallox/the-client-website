

## Inhoudsopgave Readme

Dit project is ontstaan naar aanleiding van een jaar verblijf in Indonesië met als doel de gezondheidszorg in het land beter te leren kennen. Tijdens dit verblijf werd duidelijk dat er behoefte is aan meer interactie met de internationale medische gemeenschap. Het doel van dit project is om de communicatie tussen Nederland en Indonesië te verbeteren, specifiek op het gebied van oncologie. Het systeem dat we ontwikkelen moet artsen ondersteunen bij het delen van kennis, het bespreken van patiënten, en het evalueren van medische beelden zoals CT-scans.

Daarnaast moet het platform fungeren als een centrale hub voor webinars, artikelen, en andere educatieve content om de expertise van beide landen samen te brengen.

nawallox.github.io/the-client-website/

  * [Beschrijving](#beschrijving)

  De website is ontworpen om artsen en medisch personeel te ondersteunen bij het delen van kennis en beelden in de context van oncologie. Het biedt een eenvoudige en effectieve manier om met elkaar te communiceren, CT-scans te evalueren, en relevante medische webinars en artikelen te delen. Dit bevordert niet alleen de samenwerking tussen Nederlandse en Indonesische artsen, maar verbetert ook de kwaliteit van de zorg door kennisuitwisseling.

Features
Chatsysteem
Het platform heeft een geïntegreerd chatsysteem dat artsen in staat stelt om direct met elkaar in contact te komen. Dit maakt het eenvoudig om in real-time te discussiëren over patiëntenzorg en medische beelden, zoals het bepalen van bestralingsgebieden op basis van gedeelde CT-scans.

Uploaden van CT-scans en Documenten
Gebruikers kunnen gemakkelijk CT-scans en andere medische documenten uploaden voor feedback van collega's. Dit is vooral handig bij het bespreken van complexe gevallen waar meer expertise vereist is.

Webinars en Artikelen
Alle webinars worden opgeslagen op het platform en zijn eenvoudig toegankelijk voor gebruikers. Elk webinar heeft een bijbehorende transcriptie met vertaalopties en is voorzien van gerelateerde artikelen. Er is een duidelijke navigatiestructuur zodat gebruikers snel de informatie vinden die ze zoeken.

Vertaalfunctie
Omdat de communicatie tussen Nederlandse en Indonesische artsen is, heeft de website een ingebouwde vertaalfunctie om transcripties van webinars en andere gedeelde documenten toegankelijk te maken voor beide talen.

Responsive Design
De website is volledig responsief en werkt op alle apparaten, van desktops tot smartphones. Dit maakt het voor artsen mogelijk om altijd en overal toegang te hebben tot de inhoud, ongeacht hun locatie. educatieve content om de expertise van beide landen samen te brengen.
  * [Kenmerken](#kenmerken)

  1. HTML Structuur
De HTML-structuur van dit project is ontworpen met een focus op semantiek en toegankelijkheid. We hebben gebruik gemaakt van duidelijke en overzichtelijke secties die de content logisch structureren:

Header: Bevat de navigatiebalk en het logo van het project.
Main: Dit gedeelte bevat de kerninhoud van elke pagina, zoals het chatsysteem, webinars, artikelen, en CT-scan upload secties.
Footer: Bevat contactinformatie, links naar sociale media, en aanvullende informatie over het project.
De HTML is geschreven met een modulaire aanpak, waarbij elk onderdeel van de pagina (bijvoorbeeld het uploaden van webinars, chats, of scans) in aparte secties wordt georganiseerd. We hebben ook aandacht besteed aan het gebruik van ARIA-labels voor betere toegankelijkheid.

2. CSS
De CSS is geschreven om ervoor te zorgen dat het platform een strak en professioneel uiterlijk heeft, met de nadruk op leesbaarheid en gebruiksvriendelijkheid.

Flexbox: Dit is toegepast voor de lay-out van de pagina's, waardoor de elementen netjes uitgelijnd zijn, ongeacht de schermgrootte. Dit maakt het platform ook volledig responsief, wat betekent dat het goed werkt op zowel desktop als mobiele apparaten.
Grid Layout: Gebruikt voor het weergeven van de webinars en artikelen in een overzichtelijk raster.
Responsiviteit: We hebben media queries gebruikt om ervoor te zorgen dat de website op alle apparaten goed schaalt en leesbaar blijft. Het design schaalt automatisch naar verschillende schermgroottes, van mobiele telefoons tot tablets en desktops.
Kleurenpalet: Er is een eenvoudig maar strak kleurenpalet gebruikt, met rustige kleuren die de focus leggen op de content. Bijvoorbeeld, blauwe en groene tinten voor call-to-action knoppen en highlights, en neutrale kleuren voor achtergrond en tekst.
Animaties: Kleine CSS-transities zijn toegevoegd aan knoppen en hover-effecten om de gebruikerservaring vloeiender te maken.
3. JavaScript
JavaScript is op verschillende plekken gebruikt om de interactiviteit van de website te verbeteren. De belangrijkste functies zijn:

Chatsysteem: JavaScript is essentieel voor het real-time chatten tussen Nederlandse en Indonesische medische teams. De chatfunctie maakt gebruik van web sockets om berichten instant te verzenden en ontvangen. Dit zorgt ervoor dat artsen live kunnen overleggen over bijvoorbeeld CT-scans en patiëntinformatie.
CT-scan Upload Functionaliteit: JavaScript zorgt voor het uploaden en verwerken van CT-scans. Er is validatie geïmplementeerd om ervoor te zorgen dat de juiste bestandstypes worden geüpload en dat het uploadproces soepel verloopt. Een progress bar geeft aan hoever het uploadproces is.
Webinars en Transcripties: Voor de webinar-sectie is er gebruik gemaakt van JavaScript om video's dynamisch te laden, inclusief transcripties en vertalingen. Gebruikers kunnen eenvoudig tussen verschillende talen schakelen met behulp van een vertaalfunctie.
Navigatie en Filteren: JavaScript wordt ook gebruikt om gebruikers te helpen snel te filteren op relevante webinars en artikelen op basis van zoekwoorden of categorieën. Dit maakt het makkelijker voor artsen om snel de benodigde informatie te vinden.
4. Frameworks en Libraries
Voor dit project zijn verschillende frameworks en libraries gebruikt om de ontwikkeling te versnellen en de prestaties te optimaliseren:

Bootstrap: Dit CSS-framework wordt gebruikt voor het responsive grid-systeem en kant-en-klare componenten zoals knoppen en navigatiebalken. Het zorgt voor een solide basis qua layout, terwijl we via custom CSS de specifieke stijl voor het platform hebben aangepast.
Socket.io: Deze library wordt gebruikt om real-time communicatie mogelijk te maken in het chatsysteem, waardoor berichten direct worden verzonden en ontvangen.
FilePond: Voor het uploaden van de CT-scans en andere documenten wordt FilePond gebruikt. Dit zorgt voor een gebruiksvriendelijke drag-and-drop interface en biedt extra opties zoals bestandsvalidatie en progress bar.
Google Translate API: Deze API wordt gebruikt om de transcripties van webinars automatisch te vertalen tussen het Nederlands en Indonesisch, zodat artsen uit beide landen makkelijk toegang hebben tot elkaars kennis.
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->



## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
