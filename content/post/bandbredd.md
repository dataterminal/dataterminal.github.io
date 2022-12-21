+++
title = "Bandbredd"
date = 2022-12-21T22:26:11+01:00

description = "Inom radiokommunikation avser bandbredd det frekvensområde som en signal upptar på radiofrekvensspektrumet. En signals bandbredd bestämmer hur mycket information som kan överföras under en given tid, eftersom en bredare bandbredd möjliggör en högre datahastighet."
tags = [
    "bandbredd",
    "fading",
    "störningar",
    "frekvensspektrum",
]
categories = [
    "Radiolära",
]
draft = false
+++

`Inom radiokommunikation avser bandbredd det frekvensområde som en signal upptar på radiofrekvensspektrumet. En signals bandbredd bestämmer hur mycket information som kan överföras under en given tid, eftersom en bredare bandbredd möjliggör en högre datahastighet.`
<!--more-->
# ALLMÄNT  

I allmänhet bestäms bandbredden för en radiosignal av moduleringsmetoden som används för att överföra data. Till exempel kommer en signal som använder [Amplitude Shift Keying (ASK)](dataterminal.net/post/digital-modulering/) vanligtvis att ha en smalare bandbredd än en signal som använder *Quadrature Amplitude Modulation (QAM)*, eftersom QAM kan sända mer data på samma tid.

Förutom att bestämma datahastigheten påverkar bandbredden för en radiosignal även dess räckvidd och dess känslighet för brus och störningar. En signal med en smal bandbredd kommer vanligtvis att ha en längre räckvidd och vara mindre känslig för brus och störningar, medan en signal med bred bandbredd kommer att ha en kortare räckvidd och vara mer känslig för brus och störningar  

# STÖRNINGAR  

Högre bandbredd är vanligtvis mer känslig för brus och störningar av ett par anledningar.

**För det första** innebär en bredare bandbredd att signalen upptar ett större frekvensområde på radiofrekvensspektrumet. Detta innebär att det finns en högre sannolikhet för störningar från andra signaler eller bruskällor inom det frekvensområdet.

**För det andra** tillåter en bredare bandbredd i allmänhet en högre datahastighet, vilket innebär att signalen innehåller mer information. Detta ökar signalens känslighet för brus och störningar, eftersom varje förvrängning av signalen kan ha en större inverkan på kvaliteten på den överförda datan.

**Slutligen** kan en signal med bredare bandbredd vara mer mottaglig för [fading](dataterminal.net/post/fading/) och andra atmosfäriska effekter, såsom jonosfärförhållanden, som kan orsaka störningar och brus.
