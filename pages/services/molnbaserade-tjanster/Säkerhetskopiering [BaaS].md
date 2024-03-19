---
Title: Säkerhetskopiering [BaaS]
Subtitle: Skräddarsydd säkerhetskopiering ger kontroll över innehåll och kostnader
Date: 2019-09-05T20:36:58
Modified: 2020-12-14T11:59:34
Type: service
Slug: services/molnbaserade-tjanster/backup
Status: published
Contact: anders-nilsson-2
Category: Molnbaserade tjänster
Authors: 
Lang: sv
Translation: false
---

Med Sunets molnbaserade backuptjänst får din organisation en skräddarsydd säkerhetskopiering. Tjänsten är flexibel. Varje organisation bestämmer själv vilken data som ska säkerhetskopieras, hur materialet ska krypteras och hur länge det ska sparas. Fokus ligger på att organisationen ska ha kontroll över sitt innehåll och kostnaderna för detta.

## Så fungerar tjänsten

Sunets backuptjänst har hög säkerhet. Det beror på att den har rollbaserad åtkomstkontroll knuten till SWAMIDs inloggningstjänst, att den har hög tillgänglighet och parallella anslutningar till Sunet och på att säkerhetskopior krypteras både under transporten och vid den helt diskbaserade lagringen.

Backuptjänstens fysiska datacenter ligger i Sverige och är direkt anslutna till Sunets nät, så datan överförs snabbt och säkert och behöver aldrig lämna landet. Det gör det lättare att följa rättsliga ramverk som GDPR etc.

Sunets backuptjänst är baserad på IBM Spectrum Protect (tidigare känt som Tivoli Storage Manager TSM) och Cristie’s Bare Machine Recovery för TSM (TBMR). Med 100 procent diskbaserad lagring går återställningen av säkerhetskopior snabbt. Det finns också omfattande stöd för databaser och applikationer, såsom MS SQL, MySQL, DB2 och MS Exchange.

Spectrum Protect-tekniken, som tjänsten är baserad på, har flera datareducerande funktioner. Den säkerhetskopierar enbart filer som har ändrats, varje fil lagras endast en gång oavsett hur många gånger filen förekommer och den minskar storleken på de flesta filer. På så vis blir de faktiska lagringskraven i allmänhet betydligt lägre för säkerhetskopiorna än för den data som lagras i de säkerhetskopierade systemen. Det kan handla om en reduktion på 40-70 procent i volym.

Varje organisation som använder backuptjänsten har tillgång till minst 5 Gbit/s aggregerad krypterad genomströmning Eftersom tjänsten är diskbaserad har den också mycket god parallellitet .

## Detta krävs för att få tillgång till tjänsten

Alla organisationer som är anslutna till Sunet och medlemmar i identitetsfederationen SWAMID kan beställa Sunet Backup.

## Användarstöd

Varje organisation som beställer tjänsten är själv ansvarig för att erbjuda support i form av teknikstöd och problemklassificering till sina egna användare. Sunet ger support till de kontaktpersoner för tjänsten som finns på organisationerna.

## Vad kostar det?

Varje organisation betalar enbart för den mängd data som säkerhetskopieras och lagras. Tack vare datareduktionsteknikerna blir datavolymen för säkerhetskopiorna i normalfallet betydligt lägre än den ursprungliga datavolymen, trots att säkerhetskopior skapas varje dag och sparas flera månader.

Det finns två olika nivåer på tjänsten: “*Small*” för organisationer som har en låg datavolym att ta säkerhetskopior av, och “*Normal*” för organisationer som har mycket data. Avgiften består dels av en fast avgift, som är densamma oavsett volym eller antal servrar, dels av en rörlig avgift som är baserad på volym:

**Small**: Fast avgift på 5 500 kronor per månad. I den fasta avgiften ingår 1 TB data per månad lagrad i tjänsten.

Rörlig avgift 1,75 kr per GB  och månad på datavolym som överstiger 1 TB.

**Normal**: Fast avgift på 10 450 kronor per månad.

Rörlig avgift på datavolym 0,824 kr per GB  och månad.

## Vill du veta mer?

[Länk till dokumentation om säkerhetsarbete som utförs i tjänsterna.](https://www.safespring.com/dokument/sunet/)

Kontakta [Anders Nilsson](mailto:anders@sunet.se) för mer information

