Title: Om SWAMID
Date: 2019-10-11T13:03:33
Modified: 2020-09-30T11:00:13
Slug: om-sunet/om-swamid
Status: published
Authors: 
Lang: sv
Translation: false

En identitetsfederations vara eller icke vara beror på alla parters tillit till federationen. Därför finns en federationspolicy som reglerar organisation och arbetssätt samt ett regelverk för identitetsutgivare och tjänsteleverantörer.


Policyn för SWAMID består av tre delar:


* [SWAMID Federation Policy – styrning och organisation](/wp-content/uploads/2016/02/SWAMID-Federation-Policy-v2.1-FINAL.pdf)
* [Teknologiprofil SAML WebSSO – vad innebär en lärosätesinloggning via SWAMID](http://web-wp.sunet.se/swamid-saml-websso-technology-profile/)
* [Teknologiprofil eduroam – tekniska gränssnitt för SAML WebSSO och eduroam](http://web-wp.sunet.se/swamid-eduroam-technology-profile/)


Vid sidan av tillits- och teknologiprofilerna finns även entitetskategorier för att förenkla kommunikation mellan identitetsutgivare och tjänsteleverantörer.


Identitetsutgivare (IDP)
------------------------



```
/* code example */
const output = data => {
  if (data) {
    return data.filter(item => item.condition);
  }
  return null; 
}
```

Underteckna medlemsansökan  och skicka till SWAMID via post och e-post. Bifoga även en tillitsdeklaration, SWAMID AL1 eller SWAMID AL2, men bara med e-post.



> Citat formateras med grå bakgrund nu.
> 
> 


* [SWAMID Federation Membership Agreement](/wp-content/uploads/2015/12/swamid-membership-agreement2.1.pdf)
* [Tillitsprofil SWAMID AL1](http://web-wp.sunet.se/swamid-identity-assurance-level-1-profile/)
* [Tillitsprofil SWAMID AL2](http://web-wp.sunet.se/om-sunet/om-swamid/tillitsprofil-swamid-al2/)
* Tillitsprofil för personverifierad multifaktorinloggning


Tjänsteleverantör (SP)
----------------------


SWAMID:s nyttjanderegler syftar till att underlätta tillgång till SWAMID:s metadata för externa tjänsteleverantörer. Nyttjandereglerna beskriver syfte, tillgång och till vad man får nyttja SWAMID:s metadata. Genom att acceptera SWAMID:s nyttjanderegler ersätts behovet av ett kontrakt mellan SWAMID och externa tjänsteleverantörer. För att ytterligare underlätta för tjänsteleverantörer att få rätt information om användare som loggar in använder SWAMID entitetskategorier.


* Nyttjanderegler av SWAMID:s Metadata (en. SWAMID Metadata Terms of Access and Use)
* Entitetskategorier inom SWAMID


Säkerhetsprofilen REFEDS SIRTFI


The Security Incident Response Trust Framework for Federated Identity från REFEDS, förkortat SIRTFI, är en internationell Best Current Practice.


SWAMID Board of Trustees rekommenderar starkt att både identitetsutgivare och tjänsteleverantörer i SWAMID använder säkerhetsprofilen REFEDS SIRTFI för att öka tilltron för att medlemmar och tjänster i SWAMID sköts på ett säkerhetsmässigt bra sätt.


REFEDS SIRTFI ersätter den tidigare IdM-checklistan som SWAMID tog fram tillsammans med SUSEC i samband med SWAMID 2.0. En av skillnaderna mellan IdM-checklistan och REFEDS SIRTFI är att REFEDS SIRTFI gäller både identitetsutgivare (IdP) och tjänsteleverantörer (SP). Medlemsorganisationer som uppfyller SWAMID AL1 eller SWAMID AL2 för sin identitetsutgivare uppfyller automatiskt flera av kraven i REFEDS SIRTFI. Främst behöver de även säkerställa att de uppfyller de operativa kraven i profilen samt att de har rutiner på plats för incidenthantering innan de meddelar SWAMID Operations att de uppfyller säkerhetsprofilen REFEDS SIRTFI.


* REFEDS SIRTFI


Interfederation


SWAMID är medlem av interfederationen eduGAIN. På samma sätt som varje medlem i SWAMID måste skriva en tillitsdeklaration genom Identity Management Practice Statement måste varje medlem i interfederationen skriva och publicera en Metadata Registration Practice Statement.


* SWAMID Metadata Registration Practice Statement


SWAMIDs policy omfattas formellt av opensource-licensen, CC BY-SA 3.0.


