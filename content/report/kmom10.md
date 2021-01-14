---
Title: Kmom10
Description: Part 10
Template: kmom
---

Kursmoment 10
==================
<div class="sidebar">
    <a href="kmom01"><h2>Kmom01</h2></a>
    <a href="kmom02"><h2>Kmom02</h2></a>
    <a href="kmom03"><h2>Kmom03</h2></a>
    <a href="kmom04"><h2>Kmom04</h2></a>
    <a href="kmom05"><h2>Kmom05</h2></a>
    <a href="kmom06"><h2>Kmom06</h2></a>
    <a href="kmom10"><h2>Kmom10</h2></a>
</div>

<div class="report-text">
<h2>Uppdrag 1: Webbplats</h2>
<p>
    Jag har valt att skapa en webbplats för kund 2: artisten Art Ist, som i mitt fall är en up and coming kvinnlig musiker inom elektronisk dansmusik med en edgy, tuff stil.  
    Jag valde att utgå från min me/portfolio för att på ett smidigt sätt behålla alla funktioner och den struktur vi jobbat upp under kursens gång. Däremot blåste jag upp allt innehåll för att inte behöva stöta på gammalt innehåll som kan ligga i vägen och störa designen. Om jag hade fått göra om det hade jag dock funderat på om det inte hade varit bättre att börja om från början med en ny från example/portfolio ändå med tanke på att då kunna skapa en ren och städad struktur från start.  
    <br>
    Alla tre sidor har jag lagt in samt två undersidor till "Highlights"-delen, där jag ville ha en sida för kommande spelningar, där det även går att köpa biljetter, och en sida för en portfolio för att se vilka tidigare spelningar hon har framträtt på.  
    <br>
    Rörande att innehållet ska vara innehållsrikt, bildrikt och lagom så tycker jag att jag uppnått det genom att använda mig av ett genomgående färgtema i bilder designelement och själva känslan på sidan som genomsyras av musikgenren min valda artist är verksam inom. Jag har lagt mycket tid på att tänja mina gränser inom designattribut som animationer, transformationer och effekter.
</p>  
<br>

<h2>Uppdrag 2: Tema</h2>
<p>
    Jag har utgått från mitt tidigare tema då jag ansåg det lättare att arbeta utifrån det. Jag har delat upp koden i flera moduler, för varje undersida jag skapat har jag även en sass-fil med styling för respektive sida. Detta har underlättat arbetet och gjort att jag snabbt och enkelt kan hitta vilket dokument jag ska gå in i för att justera och uppdatera information och style.  
    <br>
    Alla färgval och designelement har jag designat med valda nyckelord i åtanke för min valda artist: feminint, neon, edgy, nattklubb. Dessa ord har styrt valen jag gjort för att varje sida och element på webbplatsen ska andas den image kunden vill kommunicera. Rent konkret så har jag valt en ganska stilren struktur för de element som innehåller text och sedan en färgstark och lite stökigare omgivning med den färggivande bakgrundsbilden, menyn som jag vill ska representera ett utdraget ljussken som fotats under lång exponeringstid som även ändras för varje menyval.  
    <br>
    temats färger styrs helt och hållet av variabler som jag satt i ett enskilt dokument "variabler". Mer om färgpalett finns att läsa på dokumentationssidan som finns under "Om"-sidan i projektet. Dock fick jag inte till det med en dold länk, så dokumentationen hittas via en diskret rapport-symbol lite längre ned på "Om"-sidan.  
    <br>
</p>  
<br>

<h2>Uppdrag 3: Responsivitet</h2>
<p>
    För att uppnå en god responsivitet genom hela webbplasten har jag arbetat i responsivt läge parallellt genom hela processen. Detta för att inte fastna någonstans efter att ha spenderat en stor del tid på att endast designa i desktopläge som eventuellt kan strula till det och göra det svårare att få till snyggt i mobilläge. Det har fungerat mycket bra och kändes som ett väldigt bra sätt att arbeta på för att alltid ha mobilläge i åtanke.  
    <br>
    Till största del har jag använd mig av CSS Grid för att underlätta styling av elementen för desktop- och mobilläge där jag i desktopläge har mellan 2-3 kolumner med innehåll för att sedan gå över till 1 kolumn vid mindre skärmbredder. Jag har använt mig av Cimage för de bilder som finns på hemsidan och jag har sett till att innehållet känns smidigt och bekvämt i mobilläge utan några horisontella scrollbars eller för stor/liten text exempelvis.   
    <br>
    När det kommer till att uppnå en god tillgänglighet har jag dels testat färgerna för färgblindhet via Adobe's tillgänglighetsverktyg samt använt Lighthouse via devtools och följt de råd och anvisningar som rekommenderats.
</p>  
<br>

<h2>Hur gick projektet att genomföra?</h2>
<p>
    Jag tyckte att detta projekt var mycket roligt att arbeta med, jag kunde inte låta bli att djupdyka ner i komplicerade (för mig iallafall) stylingsätt och effekter det första jag gjorde, innan jag ens hade fått till en bra struktur för hela sidan. Vilket jag i efterhand hade gjort annorlunda. Det kändes kul att få lite mer fria tyglar gällande innehåll och övergripande tema och känsla och få skapa något helt fritt utifrån den kanska breda uppgiften.  
    <br>
    Jag hade problem med att få Cimage att fungera från mina markdown-filer, så jag löste det genom att lyfta ut innehållet till twig-filer där jag kunde anpassa Cimage till mina bilder. Jag hade också lite struligt med att en av mina sass-filer med style för en specifik sida inte ville läsas, så jag var tvungen att lägga in stylen från den i en annan sass-fil, vilket stör lite grann i filstrukturen.  
</p>
<br>

<h2>Tankar om kursen</h2>
<p>
    Jag tycker denna kurs har varit toppen. Jag har längtat efter att lära mig mer om designprinciper och mer teori bakom varför vissa sätt är "bättre" att designa på än andra. Jag kommer däremot fortfarande inte riktigt överend med Pico, markdown och alla dessa Twig-filer. Jag har svårt för att göra de enklaste saker som att lägga in bilder och sedan styla dem exempelvis då vi jobbat på detta sätt.  
    <br>
    Materialet och föreläsningarna har varit mycket bra tycker jag med den variationen mellan Emils långa och djuptgående mer teoretiska föreläsningar och Niklas snabbare mer konkreta föreläsningar. Bra mix! Kurslitteraturen gillade jag även skarpt då den kändes lättläst och gav många exempel, samt att den fanns som e-bok, stort plus.  
    <br>
    Jag ger denna kurs 7/10 i betyg då den var mycket bra teoretiskt och för att det rätt och slätt är en kurs i min smak med bra föreläsningar, enkla och kreativa uppgifter med mera. Men tyckte att vi inte gick igenom Pico och Cimage tillräckligt djuptgående för att kunna göra projektet på bästa sätt. En annan sak som gör att denna kurs får ett lägre betyg än vad jag hade velat ge är att deadlines för den här kursen inte var upplagt på samma sätt som i tidigare kurs (htmlphp) då man efter en rekommenderad deadline fick in på nästa vecka på sig att lämna in uppgifter. Att ha sista deadline samma vecka som kursen startat har känts väldigt stressigt och gjort att flertalet av mina uppgifter har lämnats in för sent (Det är ju såklart bara mitt eget fel, men blev lite besviken att det inte var upplagt på samma sätt som tidigare). Men, överlag är jag nöjd och skulle rekommendera den till vänner/kollegor som är intresserade av att lära sig webbdesign. 
</p>

</div>
