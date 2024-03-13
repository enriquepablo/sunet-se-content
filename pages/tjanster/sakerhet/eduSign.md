---
Title: eduSign
Subtitle: Säker digital underskrift och validering
Date: 2020-12-14T12:09:21
Modified: 2023-10-12T11:51:24
Slug: services/sakerhet/edusign
Status: published
Contact: stefan-listrom
Category: Säkerhet
Authors: 
Lang: sv
Translation: false
---

eduSign är säkra och enkla e-signaturer för Sunet kunder. Till eduSign finns även en valideringstjänst för att validera och säkert arkivera de digitala signaturerna. Legitimering sker med e-identitet ansluten till SWAMID och för processer som kräver externa parters signatur kan eduID användas. Tjänsten kan även integreras med egna system via ett API.


Så fungerar tjänsten
--------------------


Du laddar upp PDF- eller XML-dokument som skall skrivas under, signerar dokumentet med din SWAMID e-identitet och laddar sedan ner det signerade dokumentet.


Signerade dokument innehåller både en digital signatur och en sista sida där informationen om den som signerat dokumentet visas upp. I den digitala signaturen finns information om den digitala identitet som användes vid signeringen.


Tjänsten består av två delar:


* en e-signeringstjänst (edusign.sunet.se) där användaren kan logga in, ladda upp ett dokument, få det signerat och ladda ner det signerade dokumentet.
* en valideringstjänst (validator.edusign.sunet.se) där den digitala signaturen kan valideras. I denna funktion utfärdas också så kallade valideringsintyg som gör att de signerade dokumenten går att spara i digitala arkiv.


Hur säker är signaturen?
------------------------


Vi använder nycklar med hög säkerhet och återanvänder aldrig en nyckel för mer än en signatur. Säkerheten i signaturen beror i stor utsträckning på hur mycket man litar på säkerheten i inloggningen. För närvarande finns inga hårda krav på högre förtroendenivå i tjänsten, men information om vilken förtroendenivå som används (se till exempel [SWAMID Assurance Profiles](https://wiki.sunet.se/display/SWAMID/SWAMIDs+Assurance+Profiles)) kommer att lagras i signaturen.


Det här krävs för att få tillgång till tjänsten
-----------------------------------------------


* En IdP ansluten till SWAMID som dessutom följer SWAMID rekommendationer för attribut-överföring.
* För integration via tjänstens API eller etablering av en egen ingång till eduSign krävs tekniska förberedelser och anpassning. Kontakta oss för mer information.


Vad kostar det?
---------------


Priset är satt i relation till organisationens storlek enligt tabellen nedan.




|             |                                     |                        |
| ----------- |:-----------------------------------:|:----------------------:|
| **Storlek** | **Antal heltidsekvivalenter (FTE)** | **Månadsavgift (SEK)** |
| X-Small     |                < 100                |          840           |
| Small       |              100 – 499              |         1 680          |
| Medium      |             500 – 1999              |         3 360          |
| Large       |             2000 – 3999             |         5 600          |
| X-Large     |               4000 –                |         8 400          |


Ni tecknar avtal med Sunet om användandet av tjänsten. Kontakta Stefan Liström, [steli@sunet.se](mailto:steli@sunet.se), om ni är intresserade.


Vill du veta mer?
-----------------


Kontakta Stefan Liström, [steli@sunet.se](mailto:steli@sunet.se).


Läs även vår [FAQ om eduSign](https://wiki.sunet.se/display/EDUSIGN/FAQ).


