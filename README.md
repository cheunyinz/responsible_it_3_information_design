

# RESPONSIBLE IT - GREEN G  

## Installatie stappen

1. Clone de repo
   ```sh
   git clone https://github.com/cheunyinz/responsible_it_3_information_design.git
   ```
2. Installeer NPM packages
   ```sh
   npm install
   ```
3. Start de server
   ```sh
   npm run dev
   ```
4. Open de link in je browser 
   ```sh
   http://localhost:5173/
   ```


## Introductie 

Aan ons de opdracht om een Interactieve datavisualisatie voor Gmail te maken. De datavisualisatie moet ervoor zorgen dat de gebruiker inzicht krijgt hoeveel mailtjes diegene heeft, voor hoeveel CO2 al deze mailtjes zorgen en hoe wij diegene kunnen motiveren om zo veel mogelijk mailtjes te verwijderen. Om zo op deze manier de CO2 uitstoot van de gebruiker te verminderen. 


## Teams
| Visual team          | Tech team          
| ---------            | ------------------- 
| Bilal Guenaoui       |   Cheun Yin Zhang
| Xavier               |   Whitney Abrah
 

## Packages / libraries  geinstalleerd

Voor de applicatie hebben wij  de volgende technologieën gebruikt:
* D3
* Vite 
* Sass
* Netlify
* Gmail API




## Onderzoek naar libraries. 
We hebben onderzoek gedaan naar libraries voor het maken van mooie data visualisatie. We hebben gekeken naar anychart. js ,chart.js en d3. 

- Anychart.js

AnyChart.js is een JavaScript-bibliotheek voor het maken van interactieve en visueel aantrekkelijke grafieken in webapplicaties, ondersteunt verschillende grafiektypen en bevat ingebouwde data-visualisatie-functies. Wij hebben  geprobeerde een simpel chart met anychart te maken om te kijken of het een beter keuze is, maar we hebben er achtergekomen dat je niet zo veel kan doen met anychart.js vergeleken met d3. De documentatie van AnyChart is niet zo uitgebreid als bij sommige andere bibliotheken, dus het kan moeilijk zijn om antwoorden te vinden op specifieke vragen of problemen op te lossen.

Hier is een voorbeeld van een gemaakt 


<img width="434" alt="image" src="https://user-images.githubusercontent.com/90154152/214587583-7956d9c0-4021-467b-94ff-6988531c3e6e.png">


- Chart.js 

Chart  is ook een Javascript bibliotheek voor het maken van interactieve visualistatie.Een van de nadelen van Chart.js is dat het alleen werkt met de HTML5 canvas element, dus het zal niet werken op oudere browsers die geen ondersteuning bieden voor deze technologie. Daarnaast kan het soms moeilijk zijn om zeer complexe of aangepaste grafieken te maken met Chart.js, omdat de bibliotheek meer gericht is op eenvoudigere gebruiksscenario's.

Een ander nadeel is dat Chart.js niet zo flexibel is als sommige van de andere populaire grafiekbibliotheken op de markt, zoals D3.js, waardoor het moeilijker is om aangepaste of geavanceerde visualisaties te maken.Een ander nadeel is dat het niet altijd eenvoudig is om gegevens te exporteren of te integreren met andere systemen.

- D3 .js - Gekozen library

We hebben uiteindelijk voor d3 gekozen want  het is zeer flexibel en krachtig, waardoor het geschikt is voor het maken van aangepaste grafieken, kaarten en andere visualisaties.D3.js heeft een grote en actieve gemeenschap, waardoor er veel voorbeelden, tutorials en hulpmiddelen beschikbaar zijn.Daarnaast is D3.js is een open-source project, dus het is gratis te gebruiken en kan worden aangepast aan de specifieke behoeften van een project.Daarom hebben wij d3 als onze eerst keuze gekozen 


## Deployen.
 We hebben gebruik gemaakt van Netlify om de appplicatie live te maken. Hier is een link naar de applicatie https://responsible-it-3.netlify.app/
 
## License
Voor dit project  ik hebben wij gebruik gemaakt  van MIT licence .Feel free to peek!!


 
## Resources 

 -  Stack Overflow - Where Developers Learn, Share, & Build Careers. (n.d.).Stack Overflow. https://stackoverflow.com/
 -  GitHub: Where the world builds software. (n.d.). GitHub. https://github.com/
 - https://observablehq.com/@d3/zoomable-sunburst
 - https://stackoverflow.com/questions/68403276/d3-js-v7-equivalent-of-d3-scale-ordinal - Scaleordinal van de kleuren voor de sunburst 
 - https://www.w3schools.com/howto/howto_css_modal_images.asp- W3 school - Pop images 
 - https://openai.com/blog/chatgpt/ - GPTchat - Pop images 
     
