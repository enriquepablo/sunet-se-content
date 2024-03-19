---
Title: Information om behandling av dina personuppgifter när du använder eduID
Date: 2022-04-08T13:26:22
Modified: 2023-09-08T15:59:52
Type: page
Slug: om-sunet/behandling-av-personuppgifter-i-eduid
Status: published
Authors: 
Lang: sv
Translation: false
---

## Allmänt om oss

Sunet (Swedish University Computer Network) är en del av Vetenskapsrådet och har som uppgift att tillgodose behovet av datakommunikation hos svenska lärosäten och andra offentliga organisationer med koppling till forskning eller högre utbildning. Sunet levererar även valbara tilläggstjänster till många anslutna organisationer. En del av Sunetss utbud är eduID – en identitetslösning inom vår utbildningssektor.

## Allmänt om personuppgifter

En personuppgift är en datapunkt som identifierar en nu levande person. Sunet behandlar personuppgifter inom tjänsten eduID för att möjliggöra inloggning och överföring av information till de tjänster som en användare väljer att använda.

### När, hur och varför vi behandlar dina personuppgifter

Tjänsten eduID lagrar och behandlar personuppgifter kopplade till alla registrerade användare av tjänsten. Uppgifterna som lagras och behandlas är de uppgifter du själv väljer att lämna till oss. Dessa kan bestå av personnummer, personliga och pseudonyma identifierare, uppnådd säkerhetsnivå, kryptografiska nycklar, lösenord, samt personliga kontaktuppgifter som till exempel adress, e-post och telefonnummer. I vissa fall när en organisation har valt att använda eduID för att erbjuda tilläggstjänster lagrar eduID kopplingar mellan organisationen och de personer som organisationen valt att hantera i eduID.

Hanteringen av personuppgifter hos Sunet i stort och även för eduID följer minimeringsprincipen i Dataskyddsförordningen (“GDPR”, (EU) 2016/679). Det innebär att när du loggar in i en webbtjänst via eduID så överförs bara så mycket information om dig till tjänsten som behövs för att du av tjänsten ska kunna identifieras som en användare och därmed kunna använda tjänstens funktionalitet. Det är olika hur mycket uppgifter om dig som en tjänst behöver, nedan följer några exempel på vilken information om dig den tjänst du väljer att använda får tillgång till.

Tjänster vars primära syfte är att stödja forskning och utbildning får tillgång till namn, e-postadress och användaridentitet. Registrerade tjänster som via systemet “GÉANT Data Protection Code of Conduct” följer GDPR, får tillgång till samma information.

De tjänster vars syfte är att för studenter hantera antagning, kursregistrering, tentamensanmälan, examination, verksamhetsförlagd utbildning, stipendieansökan och självservice för användarkonton får även tillgång till ditt personnummer när du loggar in i dem eftersom det är viktigt att identifiera dig som individ. Även vissa andra tjänster kan få tillgång till ditt personnummer om de kan påvisa en rättslig grund för detta enligt GDPR artikel 6.

De tjänster som inte får ta del av ditt personnummer enligt ovan får endast en för tjänsten pseudoanonymiserad identifierare (en indirekt personuppgift).

I syfte att driva tjänsten på ett säkert sätt lagras även vissa loggar som visar hur systemet används. Exempel på information vi för logg över är vem som har loggat in och vid vilken tidpunkt man gjorde det, om man har bytt eller uppdaterat sitt namn, och så vidare. Dessa loggar delar vi aldrig med oss av till andra utom när vi enligt svensk lag är skyldiga att göra så.

Eftersom vi på Sunet utvecklar med öppen källkod kan du själv läsa i koden vilka uppgifter om våra användare vi hanterar. Vi finns på GitHub under SUNET, projektet heter eduid-backend. Väl där sök på ”class user” eller använd länken nedan.  
<https://github.com/SUNET/eduid-backend/blob/main/src/eduid/userdb/user.py#L69>

### Var dina personuppgifter kommer ifrån och vilka vi delar dem med

De uppgifter vi sparar om dig tillkommer vid två olika situationer.

När du själv registrerar någon uppgift hos oss, eller initierar en verifiering för ditt konto så att uppgifter från en annan källa (exempelvis för att koppla din identitet till ditt eduID) inhämtas och sparas i din profil.

I registervårdande syfte uppdaterar vi regelbundet information som lagras i tjänsten med data från externa betrodda källor som till exempel SPAR-registret i Sverige. eduID delar endast data med betrodda tjänster inom forsknings- och utbildningssektorn i Sverige och då endast på ett sätt som är förenligt med GDPR.

All persondata i eduID lagras säkert och skyddas av stark kryptografi och världens bästa nätverk: Sunet.

## Rättslig grund

Sunet uppdrag regleras genom regleringsbrev från regeringen till Vetenskapsrådet. Ett av Sunets uppdrag är att för utbildningssektorn i Sverige skapa säkra IT-tjänster över ett stabilt nät. Som en del i detta erbjuder Sunet en identitetslösning som används inom sektorn. Det behövs då del av användning i dessa tjänster kräver autentisering av en verifierad användare. För att kunna erbjuda dessa identitetslösningar så behöver Sunet hantera vissa uppgifter om dig som användare. Den rättsliga grunden enligt GDPR för vår behandling av dessa personuppgifter är för att vi i enlighet med vårt uppdrag utför en uppgift av allmänt intresse där det är nödvändigt att behandla dina personuppgifter enligt denna beskrivning.

## Så här länge sparas dina personuppgifter

En identitet i eduID är personlig och den enskilde kan välja att ta bort identiteten när som helst varvid all information om individen samt alla kopplingar mellan individen och eventuella organisationer också tas bort. Detta görs direkt i tjänsten.

Dina personuppgifter sparas så länge som du har ett aktivt konto hos eduID. Med aktivt konto menar vi att du har loggat in på ditt konto på eduid.se eller använt ditt konto för att logga in med ditt eduID i en annan tjänst.

### Personuppgifter och koppling till ORCID och Ladok – sparas i 1 år

Om du inte loggat in på ditt konto på ett (1) år så tas din identifiering bort samt så tas din koppling till ORCID och Ladok bort. För att på nytt kunna verifiera dig som en person behöver du efter detta verifiera din identitet på nytt samt skapa upp din koppling mot ditt ORCID och Ladok på nytt.

### Ditt konto – sparas i 2 år

Om du inte loggat in på ditt konto de senaste två (2) åren så tas ditt konto bort. Innan ditt konto tas bort så kommer en påminnelse om att ditt konto är på väg att tas bort skickas ut till den primära e-postadressen du har registrerad i ditt eduID, med hänvisning att logga in ifall du vill ha kvar ditt konto. Efter att kontot har tagits bort kommer din unika identifierare spärras från att användas igen av dig själv eller någon annan.

### Loggfiler om ditt konto – sparas i 6 månader

Exempel på information vi för logg över är vem som har loggat in och vid vilken tidpunkt man gjorde det, om man har bytt eller uppdaterat sitt namn, och så vidare.

## Dina rättigheter

Var och en har rätt att få felaktiga personuppgifter rättade samt rätt att komplettera ofullständiga personuppgifter. Det finns också en rätt att under vissa förutsättningar få uppgifter raderade eller invända mot en behandling av dina personuppgifter.

## Kontakta vårt dataskyddsombud

Vetenskapsrådets har ett dataskyddsombud som arbetar med frågor som gäller myndighetens egen efterlevnad av dataskyddsförordningen.

Om du har frågor eller synpunkter kring vår hantering av personuppgifter kan du vända dig till dataskyddsombudet på e-postadressen [dataskyddsombudet@vr.se](mailto:dataskyddsombudet@vr.se) eller till Vetenskapsrådet på telefon 08-54644000.

## Kontakta Integritetsskyddsmyndigheten

Om du har klagomål på vår hantering av personuppgifter kan du vända dig till Integritetsskyddsmyndigheten, IMY, som är tillståndsmyndigheten för behandling av personuppgifter. E-postadress till IMY är [imy@imy.se](http://imy@imy.se)

