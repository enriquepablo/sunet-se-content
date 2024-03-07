Title: Policy för samtrafik
Date: 2020-09-30T13:50:07
Modified: 2022-11-15T14:23:04
Slug: om-sunet/policy-for-samtrafik
Status: published
Authors: 
Lang: sv
Translation: false

Denna policy för samtrafik med andra internetoperatörer är fastställd av Sunets styrelse den 17 januari 2008.  
I detta sammanhang definieras en internetoperatör som den som driver verksamhet inom internetområdet och har eget AS-nummer, samt ej använder ”defaultrouting”. Denna policy beskriver **inte** Sunets policy för samtrafik gentemot universitet, högskolor et. c.


Samtrafik (peering)
-------------------


* Samtrafiken bedöms av styrelsen för Sunet vara till nytta för Sunets användare.
* Samtrafik (peering) sker via den eller de nationella internetknutpunkter till vilka Sunet har anslutning eller via annan sammankopplingspunkt till vilken Sunet har anslutning.
* Samtrafik och routing skall ske på ett tekniskt sunt sätt enligt de riktlinjer som anges i avsnitt 8.2 nedan och enligt de övriga överenskommelser som kan göras från fall till fall.
* Internetoperatör får på intet sätt störa trafik till eller från Sunet.
* Överenskommelse om samtrafik gäller tills vidare om inte någondera parten säger upp avtalet. Uppsägning skall ske med en (1) månads varsel.
* Sunet har rätt att, utan avgivande av ersättning, omedelbart bryta överenskommelsen om samtrafik om här angivna förutsättningar inte uppfylls.


Förmedling av trafik mellan internetoperatörer
----------------------------------------------


Sunet förmedlar inte trafik (s.k. transit) mellan Internetoperatörer.


Tekniska riktlinjer för routing m. m. vid samtrafik med Sunet
-------------------------------------------------------------


* Routing skall ske med BGP4 (RFC 1171, RFC 2858), och samtrafiken skall ske på ett tekniskt sunt sätt.
* Routing får ej utbytas över knutpunkt eller annan sammankopplingspunkt med routingprotokoll som utnyttjar multicast eller broadcast, t.ex. RIP eller OSPF.
* Vid konfigurering av samtrafiken med annan internetoperatör skall man sträva efter att trafiken styrs och filtreras med hjälp av information i aktuella vägvalsregister. Detta för att få en försäkran att trafik endast går till och från adresser som verkligen tillhör aktuell internetoperatör.
* Sunet kommer att hålla sin information i registren uppdaterad och aktuell.
* Routing grundad på andra principer än ovan, och som inte överenskommits med Sunet får ej användas för att styra trafik till eller från Sunets nät.
* Vid samtrafik via mer än en sammankopplingspunkt sker peering i normalfallet enligt modellen ”short-exit” (hot potato), d. v. s. man lämnar över till den punkt som är närmast i det egna ryggradsnätet. För mer detaljerad beskrivning, se ”AS-1653” i RIPE-databasen.
* Tekniken för eventuell lastdelning över flera parallella förbindelser skall i förekommande fall på förhand överenskommas av bägge parter.
* S.k. privata AS-nummer får endast användas i en knutpunkt eller annan sammankopplingspunkt om de koordinerats med samtliga internetoperatörer som har anslutning till knutpunkt eller annan sammankopplingspunkt.
* Sunet annonserar samma prefix i alla knutpunkter. Denna information innehåller så kallad MED-information, som kan användas av motparten för vägval. För mer detaljerad beskrivning, se ”AS-1653” i RIPE-databasen. Sunet lyssnar också på MED, så motparten kan på det viset även ange preferenser för trafikstyrning.
* AS-PATH får inte förlängas av en knutpunkt i sig, d. v. s. peering skall ske direkt mellan Sunet och den aktuella motparten via direktförbindelse eller gemensamt media.
* Sunet accepterar inkommande trafik till Sunets nät från operatörer/organisationer anslutna bakom en Sunet-ansluten kund, under förutsättning att detta annonseras i publika vägvalsregister (exempelvis hos RIPE) av berörda parter. Notera att detta inte nödvändigtvis innebär att Sunetanvänder den vägen för trafik tillbaka till den aktuella organisationen.


