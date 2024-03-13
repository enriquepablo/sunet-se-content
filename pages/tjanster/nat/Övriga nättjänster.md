---
Title: Övriga nättjänster
Subtitle: Nättjänster som ingår i Sunet-anslutningen
Date: 2019-09-05T16:38:45
Modified: 2023-07-05T14:02:36
Slug: services/nat/ovriga-nattjanster
Status: published
Contact: borje-josefsson
Category: Nät
Authors: 
Lang: sv
Translation: false
---

Sunet har ett antal kostnadsfria bastjänster – som i de flesta fall är tillgängliga för alla, inte bara Sunet-kunder. Inga avtal krävs för att använda dessa tjänster.

## Ping-tjänster

### Ping

[ping.sunet.se](http://ping.sunet.se) är en server som används av väldigt många för att testa sin nätverkskonnektivitet, eller fördröjningen i nätet. Programmet ***ping***, som finns i de flesta datorer kan användas för att göra en sådan test – skriv bara ping [ping.sunet.se](http://ping.sunet.se) på kommandoraden för att testa.

### E-post ping

Om du skickar ett mail till [ping@sunet.se](mailto:ping@sunet.se) så får du (om allt fungerar) ett mail tillbaka som bekräftelse på att din e-post fungerar, samt med lite info om hur brevet såg ut när det kom till oss.

### HTTP(S) ping

Denna tjänst liknar ping, men för att testa http(s) trafik. Om du (eller ett verktyg, som till exempel ***curl***) surfar till </ping> så ska vår webb-ping svara tillbaka med ett “200 OK” meddelande, det vill säga – allt gick bra.

## Bandbreddstest

Denna tjänst är under ständig utveckling. Ett antal operatörer världen runt har satt upp servrar för att göra bandbreddstester mot. Sunet har en server i Luleå, och NORDUnet har en i Stockholm. På det viset så kan vi dels sprida lasten mellan oss och dels också möjliggöra tester på lite längre avstånd. Notera att denna tjänst främst riktar sig till nätverkstekniker och mer avancerade användare. För enklare mätningar, framförallt för anslutningar upp till 100 Mbit/s (till exempel hemanslutningar) rekommenderar vi istället **[bredbandskollen](http://www.bredbandskollen.se/)**.

## Filarkivet

Sunet-arkivet började drivas av Sunet redan 1993 och är en av Sunets äldsta tjänster. Arkivet fungerar också som spegel för några av världens största freewareorganisationer. Idag finns det många terabyte fritt tillgängligt material inom bland annat följande områden:

* Databaser
* Internetresurser
* Kontorsprogramvara
* Linuxdistributioner
* Multimedia
* Nätverksövervakning och nätverkstjänster
* Programspråk
* Standarder
* Vetenskap

Vem som helst kan gå in på arkivets webbplats och hämta det denne önskar. Sunet tar dock inget ansvar för hur programvaran används, ej heller för innehåll eller kvalitet på program som finns på länkar som leder ut från våra sidor. Sunet lämnar heller inget kundstöd på den programvara som hämtas.

Om du har förslag på nytt material till arkivet skickar du ett e-brev till [archive@ftp.sunet.se](mailto:archive@ftp.sunet.se). Vi tar tacksamt emot förslag om kan göra vårt arkiv ännu bättre. Du kan också höra av dig till arkivets referensgrupp, vilken består av anställda och studenter vid landets universitet och högskolor. De har till uppgift att se till att arkivets innehåll motsvarar de behov som högskolesverige har. Arkivet samarbetar med organisationer som arbetar för att applikationer inriktade på verksamheter inom offentlig sektor ska utvecklas som öppen källkod. Ambitionen är att arkivet ska kunna bidra till kunskapsöverföring och samarbete mellan offentlig sektor i stort och högskolesektorn.

## Sekundär DNS

Till skillnad från tjänsterna ovan är denna bara tillgänglig för Sunet-kunder. För dessa så erbjuder vi möjligheten att “slava” zoner från deras primära DNS. Detta har fördelen att man får en DNS utanför sitt eget nät så att DNS-uppslagningar mot den egna domänen fortsätter att fungera även i händelse av lokala driftsproblem. Sunet-kunder som är intresserade av denna tjänst kan kontakta [noc@sunet.se](mailto:noc@sunet.se) för att sätta igång tjänsten.

## Det här krävs för att få tillgång till tjänsterna

Alla tjänsterna (förutom Sekundär DNS) är tillgängliga för alla, inte bara Sunet-anslutna! Inga avtal krävs för användande.

## Användarstöd

Tjänsterna levereras som “best effort”, dvs. de är till exempel inte redundanta, och felavhjälps inte med säkerhet dygnet runt. Sunet kan tyvärr inte stå till tjänst med direkt support (till exempel att analysera testresultaten) för andra än Sunet-kunder, övriga hänvisar vi att vända sig till sin lokala operatör om man har problem.

## Vad kostar det?

Tjänsterna ingår i Sunet-anslutningen

## Vill du veta mer?

Om du har frågor kan du kontakta Börje Josefsson.

