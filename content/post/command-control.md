+++
title = "Command & Control"
date = 2022-11-17T08:54:12+01:00

description = "Ledningsstöd, situationsmedvetenhet och ATAK. Vad är det och hur används det? Lär dig mer om Command & Control hos DATATERMINAL."
tags = [
    "C2",
    "command & control",
    "ledningsstöd",
    "situationsmedvetenhet",
    "samband",
]
categories = [
    "Samband",
]
draft = false
+++

`Denna artikel tittar på Command & Control, C2.`
<!--more-->
## INLEDNING

Burna C2-system har varit i ropet ett tag (se ATAK) och 2022-10-11 släppte [FOI en rapport om försök med Systematic SitaWare Edge](https://foi.se/rapportsammanfattning?reportNo=FOI-R--5344--SE).

![Atak Chest Rig](/images/atak-chest-rig.webp)
*Klart #tacticool med en smartphone på sin chest rig.*

Ett buret C2-system är inte be-all end-all när det gäller taktisk kommunikation, utan ett komplement till befintliga och kommande system.

---
ℹ️ `LEDNINGSSTÖDSYSTEM ÄR BRA KOMPLEMENT TILL BEFINTLIGA SYSTEM`

---

## VAD ÄR C2?

C2 - Command & Control - är ett ledningsstödsystem, ett geospatialt navigeringssystem och kommunikationsverktyg med applicerbara funktioner och stödfunktioner för alla nivåer inom FM; bat, komp, plut och grupp.
 
---
ℹ️ `ETT C2-SYSTEMS KANSKE FRÄMSTA STYRKA ÄR UTMARKERING AV EGEN TRUPP, S.K. BLUE FORCE TRACKING.`

---                                                         
Systemet gör det möjligt att snabbt markera fientlig trupp, trupprörelser, skapa rutter etc. och (automatiskt) synka detta med alla anslutna enheter.                                                           
Ett C2-system kopplas till ett radiosystem, och beroende på val av radiosystem uppnås olika grader av räckvidd och säkerhet.

---
ℹ️ `KOMMUNIKATION KRYPTERAD MED AES256 FÅR SES SOM FULLGOD I NULÄGET.`

---  

Som alltid är det ur säkerhetssynpunkt bättre att skicka en dataskur istället för tal över radio, då tiden den elektromagnetiska strålningen befinner sig i luften minskas, varpå det blir *svårare* för motståndaren att fånga signalerna.

---
⚠️ `ETT 100% SKYDD MOT FIENTLIG EW-VERKSAMHET ÄR OMÖJLIGT.`

---

C2-system likt SitaWare har chattfunktion.  


## VAD ÄR DET *INTE?*

Ett C2-system fungerar INTE som kommersiellt internet. Bandbredd, hastighet och pålitlighet ligger inte på samma nivå, så det gäller att ha rätt förväntningar. Att livestreama 4K-video från RPAS eller spaningsgrupp är inte helt och hållet realistiskt. 

Redundans är viktigt, varför ett C2-system bör ses som ett **komplement**, inte en komplett lösning.

## CIVIL MARKNAD

Den på marknaden kanske mest kända applikationen för *situationsmedvetenhet* är en derivat av ATAK - ATAK CIV. Appen finns att ladda ner till Android (A:et i ATAK står för Android) samt några relevanta plug-ins, om än att de mest intressant tilläggen endast är tillgängliga för myndighetsutövare.

---
ℹ️ `I DET CIVILA KAN MAN TÄNKA SIG ANVÄNDNINGSOMRÅDEN INOM RÄDDNING/KRISHANTERING OCH SAMORDNING.`

---

För en privatperson kan ATAK användas för exempelvis planering av vandringsrutter, men de förladdade kartorna lämnar en hel del att önska när det kommer till Sverige och jag har svårt att se hur ATAK CIV på ett vettigt och smidigt sätt kommer den stora allmänheten till nytta i nuläget, när det finns mer strömlinjeformade färdiga lösningar på marknaden. 

## VILL DU VETA MER?

För den som önskar fördjupa sig i ämnet finns det resurser att inhämta via valfri sökmotor. En början kan vara att lära sig en molntjänst, antingen jättarna AWS, Azure, Google eller mindre alternativ likt Kamatera, Liquid Web etc. Amazon Lightsail kanske är en bra kompromiss mellan användarvänlighet och kostnad. 

Kolla in Free Tak Server och utforska Youtube. En bra idé kan vara att skaffa sig [grundläggande kunskaper inom Git](https://www.youtube.com/watch?v=HVsySz-h9r4) då det på Github kan finnas relevanta repos ĺikt denna, [för kartor](https://github.com/joshuafuller/ATAK-Maps).

