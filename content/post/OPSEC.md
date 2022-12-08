+++
title = "OPSEC"
date = 2022-11-20T16:02:10+01:00

description = "OPSEC används som ett sätt att skydda sin egen eller sin organisation/enhet mot informationsinhämtning. Detta är DATATERMINALS grundläggande introduktion till OPSEC och PERSEC."
tags = [
    "OPSEC",
    "OSINT",
    "PERSEC",
    "InfoSec",
    "cybersecurity",
    "anonymitet",
]
categories = [
    "Intel",
]
draft = true
+++

`Detta är en ganska kort genomgång och introduktion till OPSEC (Operationssäkerhet) och PERSEC (Personlig Säkerhet). Dataterminal stödjer på inget sätt olagliga förehavanden och aktiviteter, utan denna text är ur rent utbildningssyfte. Devisen "know thy enemy" kan  tillämpas, för om du känner till motståndarens eventuella tillvägagångssätt blir det lättare att skydda sig.`
<!--more-->
# OPSEC

OPSEC - eller Operational Security - kan i allra högsta grad kokas ner till:

**SHUT THE FUCK UP** 

### Vad det är

Beroende på vem eller vad det är du skyddar dig emot kommer detta vara mer eller mindre enkelt. Anledningen till varför OPSEC kan vara viktigt är enkelt att greppa; förhindra eller försvåra för din motståndare att inhämta information om din egen eller ditt företag/organisation/enhets verksamhet.  

Detta handlar alltså om att skydda operationen, inte specifikt dig som person, då hamnar vi inom området **PERSEC - Personal Sercurity**. 

Det finns dock såklart beröringspunkter mellan de två och benämningarna används ibland felaktigt; man kallar PERSEC för OPSEC och vice versa. Detta spelar väl kanske inte jättestor roll alla gånger, men det är värt att känna till skillnaderna. 

---

De flesta känner till uttryck såsom "loose lips sink ships", eller "en svensk tiger". Innebörden är lätt att greppa i och med dess kontext. 

På grund av detta, och uppmaningen "Shut the fuck up" ovan, kommer denna artikel från och med nu fokusera på området PERSEC.

![image]
*NEED TO KNOW BASIS*

### Hur du gör

* **VAR PARANOID**
    - retroaktiv paranoia funkar inte, ett viss mått av nykter paranoia är således sunt. 

* **VAR STÄDAD**
    - lämna inga kontraband liggande. Kryptera och avskilj. Inte jobbdatorn. Minimera saker som ligger och dräller som folk kan sno och kopiera

Kontraband är all materiel som kan knyta dig till operationen, dvs. datorer, USB-stickor, anteckningsböcker etc. 

* **TALA ALDRIG KLARTEXT** 
    - Utgå ifrån att du alltid är övervakad, överallt. Om en hotaktör redan målangett dig är detta ett faktum och eftersom du inte vet om så är fallet; **utgå ifrån det**.  

* **TALA ALDRIG I KOD**
    - *"Kaninen har lämnat boet"* drar onödig uppmärksamhet till dig. Dessutom kommer din - enligt dig - smarta kod att knäckas.
* **ANVÄND KODORD**
    - Det kan däremot vara rimligt att använda kodord, eller s.k. kryptonymer. Det ger ett ytterligare lager och säkerhet och när din kommunikation blir övervakad och loggad kan det ändå ge s.k. plausable deniability.

* **GÖR DET SVÅRARE FÖR MOTSTÅNDAREN ATT KOMMA ÅT DIG** 
    - knarka inte, sup inte, betala dina räkningar. Var en god medborgare. kamouflage är bra. 

### Underarbetet först

Innan du ens kan påbörja någon form av opertion, där OPSEC är av yttersta vikt måste några åtgärder vidtas. Du kan exempelvis inte agera som ditt riktiga jag. 

* **TÄCKMANTEL**
    - skapa täckmantel åt din nya persona. Det innebär fejkad Twitter, mail, Facebook. Bli personen! Se till att det finns historik på sociala medier för relativt lång tid tillbaka, tänk ett halvår. Det ska alltså vara trolig och rimlig onlineaktivitet. Undvik att kontaminera mellan ditt riktiga jag och din nya persona. Det gäller både för hur du loggar in på sociala medier och vilken metadata du lämnar efter dig, samt hur du skriver; använd inte uttryck etc. som du normalt använder. 
* **CV**
    - jobba på *the legend*, dvs., ditt CV; historia, bakgrund, stödjande bevis för din persona etc.
* **SUB-ALIAS**
    - skapa sub-alias, gärna flera stycken. Alltså:

1. Skapa en alias.
2. Använd din nya alias för att skapa ännu en alias.
3. Använd din andra alias, som du skapade med din första alias, för att skapa din slutgiltiga operationsalias. 

Detta kan givetvis utökas hur många gånger du önskar. Var dock beredd på att det *tar tid*! Att skapa en helt ny persona, med trovärdig bakgrund är nånting som tar många månader.

* **KONTAMINERA ALDRIG** 
    - *Undvik som pesten* att kontaminera mellan dina alias och ditt riktiga jag. **Det går inte att understryka detta tillräckligt**. Som vi var inne på ovan; använd inte dina riktiga uttryck och manerismer. Och om det regnar där du befinner dig, nämn inte det! Efterhand du avslöjat vilket väder det faktiskt är där du befinner dig tillräckligt många gånger, går det att knyta dig till ett visst geografiskt område. Om än inte alltför precist, så kan cirkeln kring dig onekligen minskas. Det vill du inte!

När du nu skapat och känner dig säker med att ditt alias är vattentätt kan operationen påbörjas. Det är nu ditt alias och eventuella sub-alias blir måltavla för fientlig underrättelseverksamhet. 

En hängiven aktör kommer med all sannolikhet syna detta och till slut avslöja dig för den du är, men detta kommer onekligen sätta en mindre aktör ur spel, eller få någon att besluta att det inte är värt att sätta extra resurser på just dig. 

---
⚠️ `FÖRHINDRA ALL KONTAMINERING MELLAN DITT RIKTIGA JAG OCH DINA ALIAS.`

---

### TOR OCH VPN

Några ord om anonymitet och onlineaktivitet. Grundregeln är att du inte kan vara anonym online. Om så var fallet skulle vi inte behöva lägga ner det mödosamma arbetet med täckmantel och multipla alias. 

En VPN funkar bara om du tror att VPN-leverantören kommer ta DITT fängelsestraff - **det kommer inte att ske**.

Det bästa sättet att surfa på nätet är troligen via TOR och The Onion Browser. Problemet är att du inte vet vem som äger utgångsnoderna (exit nodes), så även här är du sårbar. Och återigen; **KONTAMINERA INTE**, se till att du inte loggar in på dina privata konton via samma Tor du använder för din operation. 

**Best practices när det gäller Tor är**

1. Först VPN
2. Därefter Tor. 

Ett alternativ att nyttja är också vara att lägga ett dedikerat operativsystem likt TailsOS på en USB-sticka och utföra dina operationella aktiviteter därifrån. 

## LÄNKAR

https://www.youtube.com/watch?v=eQ2OZKitRwc
DEF CON 22 - Adrian Crenshaw- Dropping Docs on Darknets: How People Got Caught

https://www.youtube.com/watch?v=zXmZnU2GdVk
When Cybercriminals with Good OpSec Attack

https://www.youtube.com/watch?v=8u7yyFYvzC4
OpSec for InfoSec - Justin Nordine

https://vato.cc/the-ultimate-opsec-guide-for-hackers/

### AVSLUTANDE ORD

För länge sedan, under internets guldålder, kunde en privatperson till större del än idag undvika spåras online. 

En liten skara individer satt på kunskapen hur man kunde nyttja eller utnyttja den nya digitala motorvägen - internet - till sin fördel - för gott och för ont.

Kunskapen dessa individer, dessa *hackare*, satt på var ofta av betydligt högre beskaffenhet än hos de myndigheter och stater satta att skydda infrastrukturen. 

Idag däremot är det fullkomligt omöjligt att komma i närheten av en statlig aktör vad gäller pengar, utrustning och till viss del kompetens (även om just du är jätteduktig på IT så har den statliga aktören MÅNGA FLER jätteduktiga på IT). 

Det innebär att vad du än gör så kommer troligtvis allting tids nog avslöjas, kartläggas eller utnyttjas. 

Och även om just Du utför alla steg till punkt och pricka och inte lämna några som helst spår efter dig, så kommer dina kontakter tabba sig; råka säga eller skriva något avslöjande eller helt enkelt gola ner dig när skiten väl träffar fläkten. Med andra ord, **de du absolut inte ska lita på är de du tror dig kunna lita på**.

Som allting inleddes med så är detta enbart ur rent utbildningssyfte och texten skall på inget sätt ses som stöd för, eller uppmuntran till, olagliga och  olovliga förehavanden. Ska du utföra en operation så ska det ske med målets vilja och kännedom, där du agerar Red Team för att påvisa eventuella sårbarheter inom en organisation eller dylikt. 

Ett viktigt tillägg är att mycket av detta även kan tillämpas av dig som befinner dig i en organisation e.d. som möjligen skulle kunna utsättas för underrättelseinhämtning från främmande makt.

Din arbetsgivare ska i dessa fall ge dig den kunskap och de verktyg du behöver för att upprätthålla ett fullgott skydd, men även om du på din arbetsplats agerar efter OPSEC och PERSEC så kan arbetsgivaren inte kontrollera det du gör privat - **gör det svårare för motståndaren att komma åt dig!** 

1. Lägg inte upp exakta datum för övningar, insatser eller andra operationer. 
2. Avslöja inte platser eller närliggande platser till där ni befinner er.
3. Diskutera inte säkerhetsrutiner, taktik eller svarstider; hur snabbt kunde ni ta er från A till B, eller X antal soldater kunde infinna sig efter Y tid till [eftersök] eller [stöd till samhället].
4. Diskutera inte färdvägar eller typ av väg; landsväg, motortrafikled. Diskutera inte var ni åt. 
5. Se till att foton inte visar byggnader eller platser och landmärken som är identifierbara.
6. OM publicering av bilder med identifierbar data ändå sker, se till att mörklägga eller pixelera delar enligt (men ej begränsat till) punkt 3; namn, registreringsnummer är information som inte ska spridas. 
7. OM du lägger upp bilder, se till att de inte kan misstolkas eller användas i propagandasyfte. Kan din bild, utan bildtext ändå förstås i dess kontext? 
8. Se till att dina foton inte innhåller metadata.
9. Lägg inte upp foton på dina relationer; barn, partner, släktingar och vänner. 
10. Att "publicera" bilder innefattar även forum som ligger bakom autentiseringskrav; privata chattar, discord, ditt privata Instagram-konto eller direktmeddelande. Du kanske kan kontrollera din egen enhet till en någorlunda god nivå, men kan du lite på mottagaren? Om du anser dig göra det, kan du lita på att dennes enhet omöjligen kan komma att komprometteras?  
11. Sprid inte rykten, varken egna spekulationer eller sådana du hör.
12. Dela inte fitness tracker-data publikt. Dina och ditt förbands motionsrundor är inte för allmän beskådan.   

Mycket av detta kan te sig överdrivet eller att det uppvisar paranoida tendenser, men ett visst mått av proaktiv paranoia är sunt.

Vi kan också använda oss av en liknelse mellan detta och hanteringen av skarpladdade vapen vid övning och insats.

Du säkrar alltid vapnet vid förflyttning; det ska inte vara avhängt din dagsform eller aktuella situation om du säkrar eller ej, du SKA inte kunna orsaka vådaskott. **Har du tid till förflyttning har du tid att säkra.** 

Det är lätt att tänka sig in i en situation där du *tror* att din förflyttning bara kommer ske en kort sträcka, du behöver således inte säkra. Vad händer om något oförutsett sker? Den korta förflyttningen blir längre och krigsdimman gör att du glömmer att vapnet är osäkrat. Vid en hastig uppsittning i fordon råkar antingen fingret eller ett föremål applicera kraft på avtryckaren...

---
ℹ️ `THE MORE YOU SWEAT IN PEACE, THE LESS YOU BLEED IN WAR. `

---

På samma sätt, om vi ALLTID agerar med OPSEC och PERSEC i åtanke minimerar vi riskerna för avsiktligt eller oavsiktligt informationsläckage, vi kommer helt enkelt inte behöva tänka på vårt digitala fotspår utan det sker automatiskt - ett mentalt muskelminne om man så vill. 

**Yttrandefriheten och våra demokratiska rättigheter** är något vi kämpar för att skydda och ingenting som är listat här ska ses som en inskränkning av detta. Dessa riktlinjer är enkom till för säkerställandet av vår egen, vår familjs och våra kamraters säkerhet. 

--- 

Med sunt förnuft kommer vi väldigt långt, och är det något ämne som du känner osäkerhet att diskutera öppet kanske det kan vara bäst att låta bli, eller prata med en kollega, chef eller någon du kan lita på och känner tilltro till.

Oavsett status, rang, ålder eller tjänst - civil eller militär - så är Du en del av ditt lands defensiva infrastruktur. Agera därefter.