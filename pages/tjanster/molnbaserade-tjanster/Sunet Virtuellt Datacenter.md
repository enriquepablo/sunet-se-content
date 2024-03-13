---
Title: Sunet Virtuellt Datacenter
Subtitle: IT-infrastruktur i Sunets egna datacenter
Date: 2023-11-27T14:43:41
Modified: 2023-11-30T13:40:15
Slug: services/molnbaserade-tjanster/sunet-virtuellt-datacenter
Status: published
Contact: anders-nilsson-2
Category: Molnbaserade tjänster
Authors: 
Lang: sv
Translation: false
---

Sunet Virtuellt Datacenter (VDC) innehåller alla funktioner som behövs för att bygga infrastruktur för IT-tjänster: virtuella maskiner, lagring och IP-adresser i Sunets nät.


Så fungerar tjänsten
--------------------


Ett VDC innehåller en pool av resurser i form av minne, CPU och disk som kan fördelas mellan olika virtuella maskiner. Tjänsten sköts antingen via API:er eller via en webbaserad “dashboard” där man kan skapa virtuella maskiner, ansluta till konsolen, titta på loggar och göra annan administration. Inloggning till webben sker via SWAMID-ansluten IdP. Vid konfiguration av nya virtuella maskiner kan man välja mellan ett stort antal färdiga varianter med olika mängd minne, CPU, typ av disk och storlek. Stöd för GPU:er är under utveckling. Det går att beställa tilläggsfunktioner kring system- och applikationer – kontakta tjänsteförvaltaren.


Det här krävs för att få tillgång till tjänsten
-----------------------------------------------


Alla som är anslutna till Sunet och har en IdP ansluten till SWAMID kan beställa tjänsten.


Användarstöd och drifthantering
-------------------------------


[Det finns ett forum för konversation kring tjänsten på Sunet Forum](https://forum.sunet.se/s/molntjanster/). Där pratar vi om hur man går tillväga för att administrera tjänsten och best practice för VDC, bland annat. Forumet används även för att annonsera kommande möten om tjänsten.


Support:


* Första linjens support: organisationens egen IT-support används i regel.
* Andra linjens support: organisationens IT-support kontaktar Safespring, Sunets leverantör av managering av tjänsten. Kontaktuppgift finns i Sunet Forum.


Tjänsten är placerad i datorhallar i Sverige som är anslutna till Sunets nät. Datorhallarna, som ligger i Stockholm (STO3, STO4) och i Kalix/Orion (DCO1), är säkrade med skalskydd, reservkraft och hantering av fysisk access för åtkomst. De är uppbyggda med hårdvara som ägs av Sunet och är utformade för att möta krav på GDPR och krav från forskningsprojekt. DC Orion är Sunets eget datacenter. Här finns bara Sunets kunder i infrastruktur som ägs av Sunet (så kallat privat moln).


I Safesprings datorhall i Stockholm finns ytterligare en motsvarande sajt, STO1. Hårdvaran ägs av Safespring och här finns både Sunets kunder och andra kunder i infrastruktur som ägs av leverantören (så kallat publikt moln).


Vad kostar det?
---------------


[Länk till prislista](/wp-content/uploads/2019/09/prislista_2310.pdf).


Vill du veta mer?
-----------------


På [Sunet Forum](https://forum.sunet.se/s/molntjanster/) finns mer information om tjänsten.


Utvecklingsfrågor och tekniska frågor hanteras av teamet för molntjänsterna.


Kontaktperson är tjänsteförvaltare Anders Nilsson [anders@sunet.se](mailto:anders@sunet.se).


*Denna tjänst ersätter de tidigare tjänsterna StAAS (lagring som tjänst) och IAAS (virtuella maskiner som tjänst). Orsaken till att vi har slagit ihop tjänsterna är för att göra det tydligare för dig som kund och för att tjänsterna nu levereras som en resurspool, på det sätt som beskrivs ovan, istället för som separata funktioner.*


