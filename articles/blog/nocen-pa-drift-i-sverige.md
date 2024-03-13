---
Title: NOCen på drift i Sverige
Date: 2022-11-16T13:05:19
Modified: 2023-02-10T12:33:58
Slug: om-sunet/aktuellt/blogg/nocen-pa-drift-i-sverige
Status: published
Category: blogg
Authors: 
Lang: sv
Translation: false
---

Under några intensiva dagar i höst har Elias och Paulo från Sunet NOC åkt på turné genom Sverige med en fullastad bil för att uppdatera och sköta om Sunets nät.

## Målet med resan

Huvudmålet med resan var att åka till Sunets nya datacenter Orion i Kalix, där vi skulle bygga rack och installera de första routrarna. Under resan skulle vi samtidigt passa på att besöka ett antal stationer för att genomföra en del förändring/installationer.

## Förberedelser

Inför resan kollade vi upp alla platser som vi skulle besöka och en noggrann plan togs fram för vad som skulle göras och var vi skulle övernatta. All utrustning, verktyg, nycklar och accesskort packade vi ihop. Det vi skulle ta med var två stycken mx480, en ALM[[1]](#_ftn1) (ALM-enheter går att nå via fjärranslutning och används för att monitorera fiber-kvalitet samt att genomföra OTDR-mätningar). Det är ett viktigt verktyg som hjälper till att identifiera fiber-avbrott) samt en perfsonar[[2]](#_ftn2) (en enhet som används för prestandaövervakning och nätverksmätning). MX480 hade redan förberetts veckan innan av Dennis som har uppgraderad både SW och FW.

## Dag 1 Tulegatan Stockholm – Luleå

[![Bild på lastad bil på väg till serverhallen Orion i Kalix.](/wp-content/uploads/2022/11/Bild1.jpg "Bild på lastad bil på väg till serverhallen Orion i Kalix.")](/wp-content/uploads/2022/11/Bild1.jpg)  

Dagen började med att vi tog ner allt som skulle tas med och packade in det i bilen. Efter att gått ett par vändor så fick vi in allt. Nu var det dags att bege sig iväg på den längsta etappen på resan.

Målet för dag 1 var att åka från Tulegatan i Stockholm till Luleå. En resa som skulle ta lite mer än 10 timmar för att köra ca 900 km. Sent på kvällen kom vi fram till hotellet. Efter att ha checkat in tog vi kontakt med Börje, ansvarig för Orion i Kalix, för att bestämma när vi skulle träffas vid Orion dagen efter. Det var inte så mycket mer vi kunde göra än att äta middag och få lite sömn innan nästa dag.

## Dag 2 Luleå – Orion

[![Bild på Orion i Kalix](/wp-content/uploads/2022/11/Bild2.jpg "Sunets serverhall Orion i Kalix, från utsidan. ")](/wp-content/uploads/2022/11/Bild2.jpg)

[![](/wp-content/uploads/2022/11/Bild3.jpg "Sunets serverhall Orion i Kalix, från insidan.")](/wp-content/uploads/2022/11/Bild3.jpg)

Efter att ha övernattat i Luleå så fortsatte vi resan mot Orion i Kalix. När vi kom fram så träffade vi Börje och fick en kort introduktion om projektet samt fick gå runt och utforska hallen.

Innan vi kunde installera de routrar vi hade med oss behövde vi bygga fem stycken rack. Börje hade förberett en plats i hallen.[![](/wp-content/uploads/2022/11/Bild4.jpg "Personal från Sunet bygger serverrack i Orion, Kalix.")](/wp-content/uploads/2022/11/Bild4.jpg)  

[![Bygger rack på Orion i Kalix](/wp-content/uploads/2022/11/Bild5.jpg "Personal från Sunet bygger serverrack på Orion Kalix, fortsättning.")](/wp-content/uploads/2022/11/Bild5.jpg)  

[![Färdiga rack på Orion i Kalix](/wp-content/uploads/2022/11/Bild6.jpg "Fem serverrack står klara på Orion, Kalix")](/wp-content/uploads/2022/11/Bild6.jpg)

Efter att ha sneglat på instruktionerna tog vi kontakt med IP-gruppen för att få hjälp med att bygga racken. Ett par timmar senare var vi klara och fem rack stod klara.  

[![Bygger rack på Orion i Kalix](/wp-content/uploads/2022/11/Bild7.jpg "Sunets personal installerar servrar på Orion, Kalix")](/wp-content/uploads/2022/11/Bild7.jpg) [![Färdiga rack på Orion i Kalix](/wp-content/uploads/2022/11/Bild8.jpg "Två servrar installerade i serverrack på Orion, Kalix")](/wp-content/uploads/2022/11/Bild8.jpg)  

När så racken till slut stod på sina platser var det dags att installera mx480 routrarna. Nu hade det hunnit bli sent på kvällen och vi avslutade dagen och åkte till hotellet i Kalix för lite mat och sömn.

## Dag 3 Orion – Umeå

Dagen började med att vi åkte tillbaka Orion för att starta mx480-routrarna samt konfigurera fjärranslutning till Sunet.  Det tog nästan hela förmiddagen men till slut kunde Dennis logga in från Stockholm och vi noterade nöjt att allt fungerade som det skulle.  

[![Installerade routrar i rack på Orion i Kalix](/wp-content/uploads/2022/11/Bild9.jpg "Sunets personal konfigurerar servrar på Orion i Kalix")](/wp-content/uploads/2022/11/Bild9.jpg)  

Efter en välbehövlig lunch packade vi ihop verktygen och resterande utrustning innan vi åkte iväg till nästa destination som återigen var Luleå. Där skulle vi byta en gammal hårdvara för en perfsonar server. Håkan håller på att köra en ordentlig lift-off för Sunets prestanda monitorering och Luleå stationen hade ett starkt behov av ny perfsonar instans. Jobbet tog hela eftermiddagen men till slut var även den uppkopplad.  

[![Bild på kablar ](/wp-content/uploads/2022/11/Bild10.jpg "Närbild på extra loops på Sunets servrar i Orion, Kalix.")](/wp-content/uploads/2022/11/Bild10.jpg)  

Samtidigt som vi höjde prestandan satte vi in extra loops i vår optiska utrustning så att Dennis kunde testa Sunets möjligheter för att leverera 400G och mer.

Efter stoppet i Luleå styrde vi bilen söderut mot Umeå som var vår nästa destination.

## Dag 4 Umeå – Tulegatan Stockholm

Väl på plats i Umeå var vårt första uppdrag att åka till siten i Umeå och installera mera loopar i vår optiska utrustning för test. När detta var gjort fortsatte vi vår resa mot Sundsvall. Väl framme, i tillägg till ”Dennis-loops” gjorde vi även felsökning/rättning av perfsonar enheten som var onåbar i en stund. Som tur räckte det med en omstart för att lösa problemet. Vi har också ordnat konsolaccess till den via fjärranslutning.  

[![Bild på kopplingar i router](/wp-content/uploads/2022/11/Bild11.jpg "Bild som visar Sunets utrustning. ")](/wp-content/uploads/2022/11/Bild11.jpg)  

Dennis testade OOB funkade som det skulle innan vi gick iväg.  

[![](/wp-content/uploads/2022/11/Bild12.jpg "Bild som visar test av OOB.")](/wp-content/uploads/2022/11/Bild12.jpg)

Resan fortsatte till nästa destination i Glössbo som ligger närheten av Söderhamn. Där skulle vi först starta och konfigurera innan vi kunde installera en ny ALM. Den tidigare hade tyvärr gått sönder. Efter installationen och vi kontrollerat att allt fungerade så körde vi vidare till nästa destination.  

[![Bild med sladdar till en router](/wp-content/uploads/2022/11/Bild13.jpg "Bild som visar test av installation av ny ALM.")](/wp-content/uploads/2022/11/Bild13.jpg)  

Resan fortsatte sedan till Gävle där vi hade en annan ALM som behövde kontrolleras. Tyvärr visade sig det att den behövde bytas ut så den packade vi ner i bilen. Vi tog möjlighet att även här sätta upp ett par extra ”Dennis-loops”.  

[![](/wp-content/uploads/2022/11/Bild14.jpg "Bild som visar installation av ny \"Dennis loop\".")](/wp-content/uploads/2022/11/Bild14.jpg)  

Nu återstod bara den sista delen av resan, att åka tillbaka till kontoret på Tulegatan. Väl framme var det bara att lämna av verktygen och utrustning, parkera bilen och konstatera att vår NOC roadtrip var avslutad för denna gång och uppdraget väl utfört.

 

[[1]](#_ftnref1) <https://www.adva.com/en/products/network-infrastructure-assurance/alm>

[[2]](#_ftnref2) https://www.perfsonar.net

*Alla bilder foto: Sunet*

