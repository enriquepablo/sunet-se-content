---
Title: IT-säkerhetspolicy
Date: 2020-05-13T19:26:11
Modified: 2023-10-02T10:24:45
Slug: om-sunet/it-sakerhets-policy
Status: published
Authors: 
Lang: sv
Translation: false
---

Denna IT-säkerhetspolicy är fastställd av Sunets styrelse den 17 januari 2008 och gäller fortfarande.

SUNET har som syfte att tillhandahålla snabb och tillförlitlig datakommunikation och näraliggande tjänster åt svenska universitet, högskolor och andra organisationer i samma intressesfär. SUNET driver därför ett nät som knyter samman de anslutna organisationerna och ser dessutom till att de har god nationell och internationell nätkonnektivitet.

Denna IT-säkerhetspolicy har till syfte att tydliggöra mål och ansvarsfördelning för IT-säkerhetsarbetet inom SUNET.

Ansvarsfördelning
-----------------

### Vetenskapsrådet

Vetenskapsrådet är huvudman för SUNET. Ansvaret för IT-säkerhetsarbetet delegeras enligt nedan.

### SUNET:s styrelse

SUNET leds av en styrelse utsedd av Vetenskapsrådet. Styrelsen är ansvarig för IT-säkerheten i SUNET.

### Samordningsansvarig

SUNET:s styrelse utser en samordningsansvarig för SUNET som har det operativa ansvaret för verksamheten.  

I detta ingår ansvar för IT-säkerheten inom SUNET. Den samordningsansvarige ansvarar för att viktigare IT-säkerhetsfrågor bereds och föreläggs SUNET:s styrelse.

### NOC (Network Operations Centre)

SUNET har en funktion, benämnd NOC, som ansvarar för det dagliga arbetet med drift, övervakning och ändringshantering av nätet.  

Inom NOC skall det finnas en utsedd IT-säkerhetsansvarig. Denne ansvarar inför SUNET:s styrelse för IT-säkerheten i den utrustning och de tjänster som NOC sköter.

### SUNET CERT

SUNET CERT är en funktion inrättad av SUNET:s styrelse för att bistå universitet, högskolor och andra organisationer anslutna till SUNET med samordning av incidenthantering och informationsspridning om aktuella IT-säkerhetsfrågor. I uppdraget ingår också att upprätta och underhålla kontaktnät med andra Internet-operatörer i Sverige och utomlands samt deltaga i nationella och internationella organisationer för CERT-samarbete.  

SUNET CERT har ett övergripande ansvar att bevaka hur anslutna organisationer följer denna policy i tillämpliga delar.  

SUNET CERT,  NOC och den samordningsansvarige ska ha rutiner för samverkan i IT-säkerhetsfrågor. Den samordningsansvarige ansvarar för detta.

### Leverantörer

Med leverantör avses en part som levererar varor eller tjänster till SUNET baserat på avtal.  

SUNET:s styrelse ansvarar för att IT-säkerhetsfrågor beaktas i samband med tecknande av avtal med leverantör med syfte att leverantören skall uppfylla de krav som framgår av denna policy.

### Anslutna organisationer

Med ansluten organisation avses varje organisation som SUNET levererar nätanslutning till, såväl universitet och högskolor som andra. Den anslutna organisationen:

* skall följa de regler som SUNET utfärdar för nätanvändningen.
* ansvarar för sin egen IT-säkerhet.
* ansvarar för att skyndsamt åtgärda situationer som orsakar IT-säkerhetsrelaterade problem för annan.
* skall utse en eller flera kontaktpersoner gentemot SUNET CERT och NOC för samordning vid IT-säkerhetsincidenter.
* skall ha fungerande e-postadress för IT-säkerhetskontakter enligt mönstret abuse@domännamn.

### Tillgänglighet

De nättjänster som SUNET levererar skall ha hög tillgänglighet. Målsättningen är att tjänsterna ska vara tillgängliga dygnet runt alla årets dagar.  

Redundanta och diversifierade förbindelser och redundant utrustning skall användas där det krävs för att erhålla acceptabel tillgänglighet. Detta gäller både internt inom nätet och vid inkoppling av anslutna organisationer.

NOC skall vara nåbar dygnet runt för att ta emot larm och felrapporter från anslutna organisationer.

### Planerade avbrott

Planerade avbrott som bara påverkar redundansen för en ansluten organisation skall meddelas minst 2 arbetsdagar (helgfria måndagar-fredagar) i förväg.  

Planerade avbrott som orsakar trafikbortfall för en ansluten organisation skall i möjligaste mån undvikas. Om ett sådant avbrott är nödvändigt ska det meddelas minst 9 kalenderdagar i förväg.

Den samordningsansvarige kan besluta om kortare förvarningstid om det planerade avbrottet är nödvändigt för att kunna upprätthålla säkerhet (inklusive tillgänglighet) i nätet som helhet. Den samordningsansvarige kan, om särskilda skäl föreligger, delegera rätten att fatta beslut om kortare förvarningstid.

### Kontinuitetsplanering

Den samordningsanvarige skall upprätta en kontinuitetsplan som fastslås av SUNET:s styrelse. Kontinuitetsplanen skall omfatta lösningar för att upprätta provisoriska nättjänster vid olika former av avbrott och katastrofsituationer.Användare som utnyttjar SUNET för tillämpningar där längre avbrott kan orsaka störningar eller ekonomiska förluster, måste själva planera för reservalternativ vid längre avbrott på SUNET:s nättjänster.

### Begränsning av åtkomst till vissa nätresurser

SUNET begränsar normalt inte trafiken som transporteras i nätet. Se dock avsnittet om skyddsåtgärder nedan. Utöver detta kan SUNET:s styrelse i särskilda fall besluta om begränsningar av trafiken. Anslutna organisationer skall informeras om detta.

KONFIDENTIALITET OCH INTEGRITET
-------------------------------

SUNET garanterar inte konfidentialitet eller integritet för data som överförs över nätet. Därför måste den som har krav på konfidentialitet elller integritet själv vidta de skyddsåtgärder som erfordras.

Den samordningsansvarige eller personer som denne delegerat rätten till har rätt att avlyssna trafiken vid teknisk felsökning samt vid hantering av incidenter.  

SUNET har rätt att insamla trafikstatistik som dock inte får vara spårbar till mindre adressenhet än ansluten organisation.

Den som genom anställning eller uppdrag ges tillgång till information avseende nättrafik eller information i datasystem inom SUNET skall iaktta tystnadsplikt utanför tjänsten avseende denna information. Denna tystnadsplikt inskränker inte dennes rättigheter i enlighet med lag och förordning.

Skyddsåtgärder
--------------

Vid incidenter/trafikstörningar (till exempel “denial-of-service-attacker”) kan tillfälliga åtgärder för filtering av trafiken vidtas av NOC för att begränsa skadan. Den anslutna organisationen kan själv begära att NOC inför sådan filtrering. I övrigt kan NOC eller SUNET CERT begära filtrering. I detta fall skall den anslutna organisationen först kontaktas för att lösa problemet eller acceptera att filtrering införs. Går den anslutna organisationen inte att nå eller problemet kvarstår kan samordningsansvarige besluta om filtrering. Går inte den samordningsansvarige att nå kan tillfälligt beslut fattas av NOC eller SUNET CERT. Då ska den samordningsansvarige meddelas så fort det är möjligt. Åtgärden skall vara så specifik som möjligt för att undvika sidoeffekter.

 

