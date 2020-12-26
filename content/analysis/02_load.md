Analys av webbsidors laddningstider
=======================

__Denna analys syftar till att dokumentera olika webbplatsers laddningstid och vilka förbättringsaspekter de skulle kunna implementera för att förbättra laddningstid och användbarhet.__  
<br>

Urval
-----------------------

Jag har valt att undersöka webbplatserna [Gucci](https://www.gucci.com/), [Ströms](https://www.stroms.com/) och [Tradera](https://www.tradera.com/). Jag valde dessa webbplatser utifrån perspektivet att se hur olika klädföretags hemsidor presterar och då i tre olika prisklasser med ett high-end företag, en nystartad e-handel för konfektionsvaror samt en webbsida för begagnade varor.  
<br>

Metod
-----------------------

För att undersöka de olika webbplatsernas laddningstid använder jag mig av Devtools flik "networks" för att nå nödvändig information om laddningstid, storlek på filer och antalet requests med mera. Jag använder även Googles verktyg  PageSpeed Insight för att se ett övergripande betyg på webbplatsen samt vilka förbättringsmöjligheter som finns.  
<br>

[Länk till Google kalkylark med all data](https://docs.google.com/spreadsheets/d/1wCS2rTKxNly5llByGmVRCmGYox6_pgRzbVF4mjqGK2c/edit?usp=sharing)  
<br>

Resultat
-----------------------
<br>
##Gucci.com

![Screenshot av gucci.com](../assets/img/load/gucci-1.png "Guccis startsida")

Guccis startsida har en medelladdningstid på 5,77 sekunder och laddar 177 resurser. Undersidorna har laddningstid på 3,6 respektive 3,2 sekunder.   
<br>


###Förbättringsmöjligheter
Ta bort javascript som inte används, -0,52s.  <br>

<br>

##Stroms.com  

![Screenshot av stroms.com](../assets/img/load/stroms-1.png "Ströms startsida")

Ströms startida har en medelladdningstid på 2,29 sekunder och laddar in undersidorna har en laddningstid på 4,61 respektive 2,43 sekunder.  
<br>

###Förbättringsmöjligheter
Ta bort resurser som blockerar renderingen, -0,5s.  
Läs in viktiga resurser i förväg, -0,46s.  
Ta bort JavaScript som inte används, -0,28s.  

<br>

##Tradera.com

![Screenshot av tradera.se](../assets/img/load/tradera-1.png "Traderas startsida")

Traderas startsida laddar på 2,60 sekunder och undersidorna på 1,94 respektive 2,23 sekunder.   

<br>
###Förbättringsmöjligheter
Ta bort Javascript som inte används, -0,79s.  
Ta bort resurser som blockerar renderingen, -0,42s.  
Ta bort oanvänd CSS, -0,25s.  

<br>

Analys och sammanfattning
-----------------------
De vanligaste förbättringsåtgärderna för mina valda webbsidor verkar vara att ta bort oanvänd JavaScipt, där alla tre sidor fick det förslaget.


Om jag ska rangordna webbplatserna baserat på de resultat jag fått fram skulle jag placera den nystartade e-handeln stroms.com på första plats, då den fick bäst betyg i alla tester. På andra plats placerar jag tradera.com och på sista plats gucci.com. Gucci tar tredje plats eftersom den både har fått riktigt dåliga betyg från PageSpeed Insights, men också för att min laptop knappt pallar med att ha sidan öppen utan att fläktarna ska gå i full gång och försöka kyla ner datorn det märks tydligt då att sidan innehåller mycket som ska laddas in.  
<br>

Jag upplever att runt 3 sekunder är en rimlig laddningstid för webbplatser. Guccis sidor tog uppåt 5 sekunder att ladda och man får vänta på att se produktbilderna vilket jag upplever som störigt. Gucci klarar därmed inte min gräns för laddningstid och jag upplever sidan rent generelt som mycket påfrestande för datorn då den som tidigare nämnt gör att fläktarna går i full gång för att inte överhetta datorn. De andra webbplatserna, stroms.com och tradera.com laddar sidorna inom min gräns så de får ett godkänt resultat med ett undantag för Ströms undersida stroms.com/julklappstips, som laddar på ca 5 sekunder och klarar därför inte min gräns.  
<br>

Slutsats
-----------------------
Ett stort och välkänt märke såsom Gucci har alltså inte lagt tid och resurser på att effektivisera sin webbsidas laddningstid och storlek, har fel format på bilder vilket förlänger laddningstiden och har rent generellt en mycket belastad sida. Den nystartade webbsidan stroms.com är som förväntat bäst i test och har rätt format på bilder och kortast laddningstid, men som däremot ändå laddar in oanvänd javascript och CSS.  
<br>


Övrigt
-----------------------

Skrivet av: Klara Nordström <br>
