---
Title: Analys av laddningstid och användbarhet
Description: This is my report page.
Template: analysis
---

Rapport om wepplatsers laddningstid och användbarhet
=======================

Denna rapport handlar om en samling av 3 olika webbplatser där författarna kommer redogöra för sidornas optimering vad gäller laddningstider och användbarhet samt göra en grundläggande analys av varför man tror att vissa av sidorna är långsammare och hur de kan förbättras.

Urval
-----------------------

Urvalet av sidor har framförallt fokus på att vilt skilda hemsidor med olika syften för att på så sätt få ganska vilt skilda design tankar och för att kunna jämföra dessa kort med varandra. Jag ville använda samma sidor som jag använt i tidigare analys vad gäller färgval och design, eftersom jag tror att det skulle ge en intressant tankeställare huruvida design val påverkar en hemsidas prestanda och användbarhet.

Metod
-----------------------

Metoden för studien kommer grunda i ett arbetsflöde där författarna använder sig av Google Pagespped samt Inspector/DevTools network för att möta sidan hastighet samt användbarhet. Huvudsakligen kommer dessa mätningar sen analyseras utifrån de riktlinjer och rekomendationer som ges av Google samt en artikel om page speed av Moz.

Datan kommer sparas ner ett excel som referens

https://docs.google.com/spreadsheets/d/1w9pIP9_Xzx-ceyOw_L4ElTcjx15Wlm3TUE0MAWHzjAs/edit?usp=sharing


Resultat
-----------------------

<h1>World of Warcraft Classic</h1>
<div class="gallery-item"><a href="image/wowclassic.jpg"><img src="image/theoden.jpg?w=854&h=480&crop-to-fit"></a></div>

Denna webbplays har endast en sida och däför kommer analysen bara utgöras av sida 1: https://wowclassic.blizzard.com/en-gb/

Sidan för World of Warcraft CLassic skulle kunna förbättra sin tillgänglighet genom att byta typsnitt till sans-serif. Sidan skulle även kunna ta bort grafiska element för att öka prestanda och ha mindre element som tar plats, dock såklart med nackdelen att designen blir mindre speciell.

<h1>World of Warcraft Retail</h1>
<div class="gallery-item"><a href="image/wowretail.jpg"><img src="image/theoden.jpg?w=854&h=480&crop-to-fit"></a></div>

Sida 1: https://worldofwarcraft.com/en-gb/
Sida 2: https://worldofwarcraft.com/en-gb/story
Sida 3: https://worldofwarcraft.com/en-gb/news

Sidan utnyttjar en stor del bilder och skulle kunna sänka lite antalet bilder och resurser som används. På framsidan använder dom sig av ett videoklipp som tar ganska mycket på prestanda, det skulle kunna vara mer lämpligt att använda sig av en rörande grafik så som de gjort på World of Warcraft Classic. PÅ nyhets och story sidorna laddas väldigt mnga resurser in och det skulle vara mer lämpligt att kanske ha en dynamisk inladdning istället som laddar in allt eftersom man skrollar igenom.

<h1>Avanza</h1>
<div class="gallery-item"><a href="image/avanza.jpg"><img src="image/theoden.jpg?w=854&h=480&crop-to-fit"></a></div>

Sida 1: https://www.avanza.se/start
Sida 2: https://www.placera.se/placera/forstasidan.html
Sida 3: https://blogg.avanza.se/

Avanza är väldigt väloptimerad och jag har svårt att hitta saker som är problematiska.


Analys
-----------------------

<div class="container">
<iframe class="responsive-iframe2" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRpikrosG2G5nn75vavU23pWF6ItKJvKaglSbmoKdKSeHAtdQJoyQWAx8gU2xyniDppsw6YxUF4LWPs/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

Överlag verkar det som att de flesta sidorna har behov av att ha ökad prestanda på mobila enheter. Framförallt för sidorna från World of Warcraft är det ett stort behov av att sänka antalet resurser som har requests. Avanza har inte riktigt samma problem, men det har överlag med att göra eftersom Avanza framförallt har landningssidor jämförelsevis med de andra sidorna vars bibliotek och nyhetssidor har ett väldigt stort antal innehåll. World of Warcraft retail skulle som tidigare ponerat, behöva limitera inladddning av resurser tills de behövs, istället för att ladda in alla på en gång. 


Det gränsvärde som jag ser som optimalt för hemsidor är en laddningstid på under 3 sekunder. Samtliga sidor klarar detta mått väl men återigen så är World of Warcraft retail efter vad gäller just deras story sektion. I denna sektion laddas sidan ner på 5 sekunder, och detta är eftersom den laddar ner väldigt mycket data istället för att servera information allt eftersom.

Referenser
-----------------------

Moz - Page Speed: https://moz.com/learn/seo/page-speed

World of Warcraft Classic: https://wowclassic.blizzard.com/en-gb/

World of Warcraft Retail: https://worldofwarcraft.com/en-gb/

Avanza: https://www.avanza.se/start

Övrigt
-----------------------

Axel Lindmark