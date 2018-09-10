---
layout: LandingPage
description: Perskaitykite teisinę strategiją, aprašančią palaikomus mechanizmus, skirtus „Microsoft Edge“ ir „Internet Explorer“ veikimui ar vartotojo naudojimui išplėsti arba modifikuoti.
title: Plėtiniai – „Microsoft“ naršyklės plėtinių strategija
author: abbycar
ms.author: abigailc
ms.date: 02/08/2017
ms.topic: article
ms.prod: microsoft-edge
keywords: edge, tinklalapio kūrimas, html, css, javascript, kūrėjas
ms.localizationpriority: high
ms.openlocfilehash: 2d524c6f874715f50ed97eb89f6948fa28ae749e
ms.sourcegitcommit: 3c4c3358e8c1f7f367909c54caa3c732873caf04
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 09/04/2018
ms.locfileid: "3250810"
---
# <a name="microsoft-browser-extension-policy"></a>„Microsoft“ naršyklės plėtinių strategija 
 
Šiame dokumente aprašomos palaikomi mechanizmai, skirti „Microsoft Edge“ ir „Internet Explorer“ arba šių naršyklių rodomo turinio veikimui ar vartotojo naudojimui išplėsti arba modifikuoti. Bet kokie metodai, kurie nėra aiškiai nurodyti šiame dokumente, yra **nepalaikomi**.

Palaikomi plėtinių mechanizmai kuriame siekiant užtikrinti, kad vartotojai galėtų tinkinti ir išplėsti savo naršyklę pasitelkę pasirinktą programinę įrangą ir kartu saugiai ir nepertraukiamai naudoti savo naršyklę ir kompiuterį.

Programinė įranga, kuri naudoja nepalaikomus metodus arba būdus, skirtus išplėsti arba pakeisti naršymą „Microsoft Edge“ arba „Internet Explorer“, gali būti užblokuota arba pašalinta naudojant apsaugos nuo kenkėjiškų programų programinę įrangą.

## <a name="supported-mechanisms-for-software-that-extends-or-modifies-microsoft-edge"></a>Programinės įrangos palaikomi mechanizmai, kurie išplečia arba modifikuoja „Microsoft Edge“

### <a name="summary"></a>Suvestinė

 Pagal numatytuosius nustatymus „Microsoft Edge“ yra saugi, patikima, sparti ir reaguojanti naršyklė, kuri užtikrina, kad vartotojas visada kontroliuotų naudojimą.  

„Microsoft Edge“ plėtiniai, išskirtinai pasiekiami tik iš „Microsoft Store“, yra **vieninteliai palaikomi** mechanizmai, skirti „Microsoft Edge“ galutinio vartotojo patirčiai, pvz., naršyklės konfigūracijai ir naršyklėje rodomam turiniui, pakeisti.

Išskyrus atvejus, kai aiškiai nurodyta šiame dokumente, visi kiti mechanizmai, turintys įtakos „Microsoft Edge“ konfigūracijai arba turiniui, yra **nepalaikomi**.  

### <a name="installation-management-and-removal"></a>Diegimas, valdymas ir šalinimas

Visi „Microsoft Edge“ plėtiniai, turi būti įdiegti iš „Microsoft Store“. Vartotojas diegimą turi pradėti ir užbaigti naudodamas tik „Microsoft Edge“ ir „Microsoft Store“ pateiktus veiksmus. Programinė įranga gali būti susijusi su plėtinį, esančiu „Microsoft Store“, bet negali ji pakeisti plėtinio įsigijimo veiksmų arba kitaip taikyti perdėtą įtaką ar klaidinti vartotoją, kad jis įdiegtų plėtinį.  

Programinės įrangos negali trukdyti vartotojui išjungti ar pašalinti plėtinį arba bet kokiu būdu modifikuoti plėtinį „Microsoft Edge“ naudojimo metu.

Visi plėtiniai, turi būti naudojami pagal dabartinę „Microsoft Store“ strategiją, skirtą „Microsoft Edge“ plėtiniams.

### <a name="extension-development"></a>Plėtinių kūrimas

„Microsoft Store“ reikalavimų išimtis taikoma tik kuriamų plėtinių kūrėjams ir testuotojams. Tai galima laikinai įkelti į „Microsoft Edge“ egzempliorių, kai tai žino vartotojas, kuriam pranešama, kad buvimą. Plėtiniai bus išjungti automatiškai, jei vartotojas nesutiks su jų buvimu.

### <a name="modification-of-microsoft-edge-settings"></a>„Microsoft Edge“ parametrų keitimas

„Microsoft Edge“ naudoja registro ir kitų vietos arba debesies saugyklos mechanizmus, kad galėtų išsaugoti būseną ar konfigūraciją daugelio funkcijų, įskaitant (bet neapsiribojant) vartotojo pradžios puslapį ir jame esantį turinį, adreso juostą ieškos modulyje, naujo skirtuko puslapį, parankinius, skaitinių sąrašą ir naršyklės funkcijų būseną arba konfigūraciją.  

Programinė įranga negali būti tiesiogiai ar netiesiogiai keisti šių parametrų dėl kokios nors priežasties. Visus parametrų keitimus turi atlikti vartotojas naudodamas „Microsoft Edge“. Programinė įranga negali paveikti vartotojo pasirinkimų, naudojat persidengimus ar kitas vartotojo patirties modifikacijas arba suteikti alternatyvius veiksmus su turiniu.

„Microsoft“ palaiko grupės strategiją ir MDM strategiją, kad būtų galima tinkinti konkretų „Microsoft Edge“ veikimą įrenginiuose, kuriuos valdo organizacija. Šias strategijas konfigūruoti gali tik organizacijos administratorius. Programinė įranga, kuri naudoja šias strategijas kitais atvejais, gali būti užblokuota arba pašalinta naudojant apsaugos nuo kenkėjiškų programų programinę įrangą.

### <a name="network-traffic-modification"></a>Tinklo srauto keitimas

Tam tikra programinė įranga pakeičia naršyklėse ir kitose programose rodomą turinį, pakeisdama tinklo srautą per įvairius mechanizmus, įskaitant (bet neapsiribojant) tarpinio serverio diegimą arba DNS pakeitimus.

Ši srauto keitimo forma paprastai yra **nepalaikoma**, išskyrus atvejus, kai ji skirta konkrečiai veiklai: nustatant virtualų privatųjį tinklas (VPN) arba filtruojant žiniatinklio turinį (pvz., nepageidaujamus reklamos, nesaugaus arba netinkamo turinio šalinimas).

Programinė įranga, kuri pakeičia turinį, turi veikti pagal standartines „Windows“ programinės įrangos gero veikimo taisykles: aiškus pranešimas apie programinės įrangos diegimo tikslą ir poveikį, aiškios instrukcijos, kaip išjungti arba pašalinti programinę įrangą ir aiškus patekimas į „Windows“ programų sąrašas, kuriame vartotojas gali pašalinti programinę įrangą (šalinimo metu produktas turi būti visiškai pašalintas iš sistemos).  

Programinė įranga, kuri keičia srautą ne anksčiau išvardytais tikslais, arba kuri veikia nesilaikant „Windows“ programinės įrangos gairių, bus **nepalaikoma** ir gali būti užblokuota arba pašalintas naudojant apsaugos nuo kenkėjiškų programų programinę įrangą.  

## <a name="supported-mechanisms-for-software-that-extends-or-modifies-internet-explorer"></a>Programinės įrangos palaikomi mechanizmai, kurie išplečia arba modifikuoja „Internet Explorer“

### <a name="installation-management-and-removal"></a>Diegimas, valdymas ir šalinimas

Visi plėtiniai turi būti įdiegti naudojant metodus, aprašytus „Microsoft“ kūrimo tinkle, skirtame [„Internet Explorer“ plėtiniams](https://msdn.microsoft.com/library/aa753587). Programinė įranga negali apeiti „Internet Explorer“ plėtinių diegimo proceso. Programinė įranga turi leisti vartotojui patvirtinti plėtinių aktyvinimą ir diegimą per „Internet Explorer“ sąsają ir šios sąsajos negalima pakeisti, apeiti, perdengti, taip pat negalima kitais būdais pakeisti patirties.

Programinė įranga turi leisti vartotojui įjungti arba išjungti bet kurį naršyklės plėtinį per „Internet Explorer“ dialogo langą „Plėtinių valdymas“. Šio dialogo lango jokiu būdu negalima keisti.

Įrankių juostose turi būti uždarymo piktograma, leidžianti vartotojams visam laikui išjungti įrankių juostą. Įrankių juostos taip pat turi leisti pateikti į „Windows“ dialogo langą „Pridėti arba šalinti programas“.

**Pastaba:** šio skyriaus reikalavimai netaikomi „Internet Explorer“ pakeitimams, kuriuos patvirtino organizacijos valdomo įrenginio sistemos administratorius.

### <a name="capabilities-and-execution"></a>Galimybes ir vykdymas

Plėtiniai turi naudojami tik palaikomose „Internet Explorer“ ir „Windows“ API.  

Programinė įranga (pvz., plėtiniai) negali programiškai pakeisti arba apriboti prieigą prie naršyklės funkcijų, įskaitant (bet neapsiribojant) adreso juostą, pagrindinį puslapį, ieškos lauką, naujo skirtuko puslapį arba parankinius.

Tinklu pagrįstą (pvz., DNS arba tarpinio serverio) srauto keitimą galima naudoti tik virtualių privačiųjų tinklų tikslais ar filtruojant žiniatinklio turinį (pvz., panaikinant reklamas, nesaugų arba netinkamą turinį).

Pradedant nuo „Internet Explorer 11“, plėtiniai turi būti suderinami su išplėstiniu apsaugotuoju režimu (EPM). Programinė įranga negali taikyti mažiau griežtų „Internet Explorer“ saugos parametrų.

#### <a name="change-log"></a>Pakeitimų žurnalas 
- 2016 m. balandis: paskelbtas dokumentas
- 2016 m. spalis: „Microsoft Edge“ plėtinių publikavimo „Microsoft Store“ atnaujinimas 
- 2017 m. rugpjūtis: valdomų įrenginių paaiškinimas
