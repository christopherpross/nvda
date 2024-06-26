# NVDA NVDA_VERSION felhasználói útmutató
## A felhasználói útmutató elkészítésében részt vettek: Dr. Simon Gergely, Németh Dávid, Ócsvári Áron, Osztolykán Róbert, Papp László
### Ez az útmutató az angol felhasználói dokumentációt figyelembe véve készült, így tartalma azzal nem megegyező.

[TOC]

<!-- KC:title: NVDA NVDA_VERSION parancsok listája -->



## A kézikönyv használata {#toc2}

Tisztelt Felhasználó!

Ön most a Non Visual Desktop Access (azaz NVDA) képernyőolvasó program felhasználói kézikönyvét olvassa.

ez egy html dokumentum, amelyet webböngésző programja (Internet explorer, Firefox, stb.) nyitott meg.

Ezt a kézikönyvet háromféleképpen érheti el:

* az interneten 
* az NVDA menüjében, 
* a fájlrendszerben az NVDA dokumentációs mappájában.

NVDA képernyőolvasó használata esetén nyomja meg az insert-N billentyűparancsot, a menüből válassza a súgó almenüt, abban a felhasználói útmutató parancsot.

Ha ezt a kézikönyvet más képernyőolvasó programmal olvassa, kérjük, forduljon segítségért az adott képernyőolvasó súgójához, dokumentációjához vagy technikai támogató szolgálatához. Az NVDA honosító csapatnak nem áll módjában más képernyőolvasók használatához segítséget nyújtani.

Ha az NVDA képernyőolvasó programot futtatja, az NVDA billentyűparancsai nagy segítségére lesznek a dokumentumban való tájékozódáskor.

Néhány billentyűparancs a teljesség igénye nélkül:

* A tartalomjegyzékben válasszon egy hivatkozást és nyomja meg az entert, a program a kívánt dokumentumrészhez (fejezethez, alfejezethez) ugrik.
* A hivatkozások listáját az NVDA+f7 billentyűvel (insert + f7, vagy capslock+f7) kérheti le 
* a tab billentyűvel hivatkozásról hivatkozásra léphet.
* A H és shift+H billentyűkkel címsorról címsorra ugrálhat előre vagy hátra 
* Az L billentyűvel listát, 
* az I billentyűvel listaelemet kereshet, így könnyedén megtalálja az Önt érdeklő felsorolásokat. 
* Az NVDA billentyű valamelyik Insert vagy a capslock lehet, ld. később részletesen. 
* Az NVDA-gomb+controll+F billentyűparanccsal tetszőleges kifejezésre kereshet 
* A folyamatos felolvasást az NVDA+lenyíllal indíthatja el, a felolvasást bármikor megállíthatja a controll billentyűvel. 
* Az alt-f4 a böngészőprogramot, a controll-f4 (vagy control-w) a megnyitott böngészőlapot zárja be anélkül, hogy a többi megnyitott oldal bezáródna. 

## Bevezetés {#toc3}
### Általános Jellemzők {#toc4}

Az NVDA vakok és gyengénlátók számára hozzáférést biztosít a Windows operációs rendszerhez, valamint számos egyéb alkalmazáshoz egy beszédszintetizátor, vagy braille kijelző segítségével.
Az NVDA programot az [NV Access](https://www.nvacces.org) fejleszti. A program honosítását a [Net-média Alapítvány](https://www.netalap.hu) támogatja, a honosító csapat weboldala az [nvda.hu](https://www.nvda.hu) címen érhető el.

Főbb jellemzői:

* Népszerű alkalmazások támogatása (ide tartoznak a webböngészők, az e-mail kliensek, különböző internetes chat programok, és az irodai szoftverek)
* Beépített beszédszintetizátor, ami több mint 80 nyelvet támogat
* A szöveg formázásának - például szöveg mérete és betűtípusa, stílus és helyesírási hibák - bemondása ahol elérhető,
* Az egérmutatónál lévő szöveg automatikus bemondása és választható hangjelzés az egér pozíciójának megállapításához
* A frissíthető braille kijelzők támogatása, a számítógépes braille bevitellel együtt
* Telepítés nélküli futtatás egy USB hordozható eszköz használatával
* Könnyen használható, beszédtámogatást nyújtó telepítő
* A felület többnyelvű  támogatása
* A Windows 32 és 64 bites verzióinak támogatása
* A Windows bejelentkező és biztonsági képernyőinek támogatása
* Általános kisegítő lehetőséget biztosító felületek támogatása, mint például Microsoft Active Accessibility, Java Access Bridge, IAccessible2 és UI Automation
* A Windows Parancssor és konzolos alkalmazások támogatása

### Honosítás {#toc5}

Fontos, hogy az emberek a világ bármely részén, nyelvi korlátok nélkül, egyenlően hozzáférhessenek a különböző, a technológia nyújtotta lehetőségekhez. Az NVDA már 52 nyelvre lett lefordítva, ezek: Afrikaans, Amhara, Aragóniai, Albán, Arab, Bolgár, Burmai, Cseh, Dán, Farsi, Finn, Francia, Gallego, Görög, Grúz, Héber, Hindi, Holland, Horvát, Indonéz, Izlandi, Ír, Japán, Kannada, Katalán, Kirgiz, Kínai (hagyományos és egyszerűsített), Koreai, Lengyel, Litván, Macedón, Magyar, Német (németországi és svájci), Nepáli, Norvég (bokmal és nynorsk), Olasz, Orosz, Pandzsábi, Portugál (portugáliai és brazíliai), Román, Spanyol (kasztíliai és kolumbiai), Svéd, Szerb (latin betűs), Szlovák, Szlovén, Tamil, Thai, Török, Ukrán, Urdu és Vietnami nyelvre, sőt még eszperantóra is.

### Beszédszintetizátor Támogatás {#toc6}

Az üzenetek és a felhasználói felület többnyelvűsége mellett az NVDA lehetőséget biztosít a tartalom megfelelő nyelvű felolvasásához, amennyiben a használni kívánt beszédszintetizátor képes az adott nyelven megszólalni.

Az NVDA tartalmazza az [eSpeak NG](https://github.com/espeak-ng/espeak-ng) beszédszintetizátor programot, amely ingyenes, nyílt forráskódú és többnyelvű. Az NVDA által támogatott többi beszédszintetizátorról a [Támogatott beszédszintetizátorok](#SupportedSpeechSynths) fejezetben olvashat.

### Braille támogatás {#toc7}

A Braille kijelzővel rendelkező felhasználók számára az NVDA lehetőséget biztosít az információ megjelenítésére a kijelzőn. Az NVDA által támogatott braille kijelzőkről a [Támogatott braille kijelzők](#SupportedBrailleDisplays) fejezetében olvashat.
Az NVDA számos nyelv braille tábláját támogatja. A legtöbb esetben az 1-es és 2-es rövidítési fokozat is rendelkezésre áll. Az angol felhasználók részére az egységes és az US braille kódok is elérhetőek.

### Licensz és Copyright {#toc8}

Copyright (C) 2006-2014 [NVDA Közreműködők](https://www.nvda-project.org/)

Copyright (C) 2008-2014 [NVDA honosítási project](https://www.nvda.hu)

Az NVDA a GNU Általános Nyilvános Licensz (2-es verzió) rendelkezéseinek elfogadásával használható. A szoftver szabadon közzétehető vagy módosítható a licensz és a forráskód bárki számára elérhetővé tételével. Ez az eredeti és módosított szoftverre, valamint bármilyen a szoftver forráskódjából származó kódrészletre vonatkozik.

Ha erről többet szeretne megtudni, látogassa meg a következő (angol nyelvű) [honlapot](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
vagy nézze meg a szoftverhez mellékelt Copying.txt fájlt.

## Rendszerkövetelmények {#toc9}

* Operációs rendszerek: 32 és 64 bites Windows 7,  Windows 8, Windows 8.1, Windows 10, illetve bármely szerver operációs rendszer a Windows Server 2008 R2 verziótól kezdve
* Windows 7 esetén NVDA igényli a szerviz csomag 2 meglétét
* Windows Server 2008 R2 esetén az NVDA igényli a Szerviz csomag 1 vagy újabb meglétét.
* Memória: 256 mb vagy több
* Processzor sebesség: 1.0 ghz vagy gyorsabb
* Kb. 90 mb szabad hely a merevlemezen.

## Az NVDA letöltése és telepítése {#toc10}

Ha még  nincs NVDA képernyőolvasója, az [NVDA hivatalos oldaláról (angol)](https://www.nvda-project.org), vagy a [honosítócsapat weboldaláról](https://www.nvda.hu) letöltheti azt a letöltés oldalon az NVDA legfrissebb verziójára mutató hivatkozásra kattintva.

A letöltött fájl elindításakor az NVDA egy átmeneti példánya töltődik be. Ekkor a program rákérdez a következő lépésre. Lehetősége van a program feltelepítésére a számítógépre, a hordozható verzió elkészítésére, vagy az átmeneti példány futtatására.

Ha fel szeretné telepíteni az NVDA programot, a "telepítés" gombot kell megnyomnia.
Az NVDA telepítésével elérhetővé válik néhány extra funkció, úgy mint a program automatiku s elindulása a rendszer betöltésekor, vagy a Windows bejelentkező és biztonsági képernyők olvasása. Ezen felül a telepített verzió képes elkészíteni sajátmaga hordozható verzióját is.

Ha magával szeretnévinni egy hordozható eszközön az NVDA programot, válassza a "Hordozható verzió készítése" lehetőséget. A hordozható verzió fel tudja telepíteni saját magát az éppen futó számítógépre. Ha egy csak olvasható adathordozóról szeretné futtatni a programot (pl. cd/dvd), akkor a letöltött telepítőfájlt másolja fel rá, ugyanis az NVDA hordozható változata nem támogatja a csak olvasható eszközöket.

Az NVDA átmeneti példányának használata főképp demonstrációs célokat szolgál, a gép újraindulásakor ez és az ekkor megadott összes beállítás elveszik.

### A hordozható és az ideiglenes példány korlátozásai {#toc11}

Azon túl, hogy az NVDA hordozható változatban és ideiglenes példányban nem képes automatikusan elindulni sem a bejelentkezés előtt, sem azt követően, az NVDA hordozható és ideiglenes példányát csak az alábbi korlátozásokkal lehet használni:

* Az NVDA ilyenkor nem képes kommunikálni a rendszergazdai jogokkal futó alkalmazásokkal, kivéve, ha maga az NVDA is rendszergazdai jogokkal fut (nem ajánlott).
* Az NVDA nem képes felolvasni a felhasználói fiók felügyeleti (UAC) képernyőket, ha egy alkalmazást rendszergazdai jogokal próbálunk meg elindítani.
* Windows 8-ban az NVDA ilyenkor nem képes támogatni az érintőképernyőről történő bevitelt.
* Windows 8-ban ilyenkor az NVDA nem képes a Windows Store alkalmazásokban visszaolvasni a begépelt karaktereket, és böngésző módban felolvasni a tartalmakat.
* A hangerő-igazítás a hordozható verzióban nem támogatott.

### Az NVDA telepítése {#toc12}

AzNVDA telepítésének megkezdéséhez nyomja meg az "NVDA telepítése" gombot. Ha bezárta ezt az ablakot, vagy az NVDA hordozható verzióját használja, ugyanezt megteheti az NVDA menü -eszközök almenüjéből is.

A választható beállításokat alább részletezzük. Miután mindent beállított, a "Folytatás" gomb lenyomásával elindíthatja a program telepítését, vagy egy régebbi verzió frissítését.
A telepítés sikeres befejezéséről egy párbeszédablakban ad a program tájékoztatást, ekkor egy entert nyomva a feltelepített NVDA el is indul.

#### Beszédtámogatás nyújtása a Windows bejelentkező képernyők használatakor {#toc13}

A beállítás bekapcsolásával az NVDA képes lesz beszédtámogatást nyújtani a Windows bejelentkező képernyő használatakor (pl. jelszó bekérése). Ennek a funkciónak a segítségével olvastathatja fel a Windowsbiztonsági képernyőjét (UAC) is.

#### Parancsikon elhelyezése az asztalon és a ctrl+alt+n billentyűparancs hozzárendelése {#toc14}

A jelölőnégyzet bejelölése után a program elhelyezi parancsikonját az asztalon, amit a ctrl+alt+n (vagy az altgr + n, azaz a jobb alt + n) billentyűparanccsal is aktiválhat.
Figyelem! Néhány programozási nyelvben sokat használják a } (végkapcsos) jelet, mely a magyar billentyűzeten az NVDA  billentyűparancsának felel meg.

#### a hordozható változat beálításainak átmásolása az aktív felhasználói fiókba {#toc15}

Ez a parancs lehetővé teszi, hogy az NVDA bemásolja az éppen futó hordozható változat beállításait az aktív felhasználó felhasználói fiókjába, ha az NVDA-t a hordozható változatból telepíti. Ez a parancs nem írja felül sem a többi felhasználó, sem a windows biztonsági és bejelentkező képernyők NVDA-beálításait. Ez a parancs csak az NVDA hordozható változatából való telepítéskor érhető el, a normál telepítőcsomagban viszont nem.

### Hordozható verzió készítése {#toc16}

Ha hordozható verziót szeretne létrehozni, válassza a "Hordozható verzió készítése" menüpontot az NVDA telepítő elindításakor. Ha már bezárta ezt az ablakot, vagy az NVDA telepített verzióját használja, ezt megteheti az NVDA menü -eszközök almenüjében is.

A hordozható verzió jelenleg nem futtatható írásvédett eszközökön (pl. cd-n), ilyen esetekben az NVDA telepítőcsomag használatát ajánljuk.

A felbukkanó párbeszédablakban kiválaszthatja az NVDA hordozható verziójának pontos helyét. Ez lehet egy hordozható eszköz főkönyvtára, de megadható egy könyvtár az ön gépének merevlemezén is.

Lehetősége van a felhasználói beállítások átmásolására, ekkor az összes beállítás (beleértve a használt bővítményekkel együtt) másolásra kerül. Ez csak abban az esetben érhető el, ha a hordozható verziót egy már feltelepített verzióból készíti el.

A hordozható verzió elkészítéséhez nyomja meg a "folytatás" gombot. A telepítő egy párbeszédablakban fogja tájékoztatni a telepítés sikerességéről, amit az OK gomb megnyomásával zárhat be.

## Az Első Lépések Az NVDA-val {#toc17}
### Az NVDA Elindítása {#toc18}

Ha ön az NVDA telepítős változatát használja,  az NVDA a control+alt+n billentyűparanccsal (ha ezt engedélyezte a telepítéskor), vagy az enter billentyű megnyomásával a start menü NVDA almenüjéből elindítható. A futtatás menüből is elindíthatja a programot (start gomb +r), írja be a megjelenő mezőbe, hogy NVDA, majd nyomja meg az enter billentyűt.
Megadhat  néhány [parancssori beállítást](#CommandLineOptions) is, mely lehetővé teszi többek közt az NVDA újraindítását (-r), bezárását (-q), vagy a bővítmények letiltását (--disable-addons), stb.

Az NVDA telepített verziói alapértelmezés szerint a Roaming mappába mentik a konfigurációs fájlokat. Ez Windows 10 alatt "C:\Users\<felhasználó>\AppData\Roaming"
 Lehetőség van ezt megváltoztatni, hogy az NVDA a helyi Application Data mappába mentse a konfigurációs fájlokat.
További részletekért keresse fel a [Rendszerparaméterek](#SystemWideParameters) című fejezetet.

Ha a hordozható exe fájl verziót szeretné elindítani, nyissa meg a kicsomagolt fájlok mappáját, jelölje ki az nvda.exe fájlt, nyomja meg az enter billentyűt, vagy kattintson kétszer az nvda.exe fájlra.

Az NVDA elindulását egy emelkedő hang jelzi. A program betöltődése a számítógép, vagy egy lassabb hordozható eszköz sebességétől függően akár pár percig is eltarthat. Ha ez eltér a megszokottól , az NVDA az "Az NVDA betöltése folyamatban, kérem várjon..." üzenettel tájékoztat.

Ha a program betöltődése nem így történik, hanem a Windows hibahang, vagy csökkenő hangjelzés hallható, akkor hiba történt. Ekkor kérjük, jelezze a problémát az NVDA fejlesztőknek. Az NVDA hivatalos weboldalán erről részletes információ olvasható.

Az NVDA első indításakor egy üdvözlőképernyő tájékoztat az NVDA módosítóbillentyűről (a továbbiakban: NVDA vagy NVDA billentyű), valamint az NVDA menüjéről. (A későbbiekben ezekről még lesz szó). A párbeszédpanel tartalmaz egy kombinált listamezőt és három jelölőnégyzetet. A kombinált listamezőben kiválaszthatja a billentyűzet-kiosztást.
Az első jelölőnégyzet bejelölésével meghatározhatja, hogy az NVDA a CapsLock billentyűt használja módosítóbillentyűként. A capslock billentyű egyrészt a notebook-használóknak lehet hasznos, másrészt a jobbkézzel leüthető billentyűk esetén kényelmesebb használni, mint valamelyik insertet. Ha a capslockot eredeti funkciójában szeretné használni, nyomja meg gyorsan kétszer, ezzel lehet bekapcsolni, és ugyanígy kell kikapcsolni is.
A második jelölőnégyzet pedig a párbeszédablak megjelenítése az NVDA minden elindulásakor szabályozható.

### Az NVDA Billentyűparancsai {#toc19}
#### Az NVDA gombról {#toc20}

A legtöbb NVDA specifikus billentyűparancshoz szükség van az NVDA billentyűre, és egy vagy több billentyű megnyomására. Ezek közül kivételt képeznek a szövegáttekintő billentyűparancsok, melyek a numerikus billentyűzet segítségével érhetőek el, valamint a navigációs gyorsbillentyűk, melyek a virtuális kijelzőkben használhatóak.

Alapértelmezettként mind a numerikus Insert, mind pedig a normál Insert billentyű használható NVDA billentyűként. Van lehetőség azonban a capslock billentyű beállítására is NVDA billentyűként (LD feljebb).

#### Billentyűzet kiosztás beállítása {#toc21}

Az NVDA jelenleg az asztali, és a laptop billentyűzet kiosztást támogatja. Alapértelmezetten az NVDA az asztali kiosztást használja, de ezt átállíthatja a beállítások menüben található billentyűzet menüpontot megnyitva.

Az asztali kiosztás használatakor számos NVDA specifikus billentyű a numerikus billentyűzeten érhető el (ha a numlock ki van kapcsolva). Ezzel szemben a laptopok többségén nem található meg külön a numerikus billentyűzet, -bár néhányon az fm billentyű és a betük/számok lenyomásával emulálni lehet (7 8 9 u i o j k l , stb).
Ha ezt a funkciót az ön laptopja nem támogatja, akkor át kell állítania a billentyűzet kiosztást a laptop kiosztásra.

### NVDA Érintési Parancsok {#toc22}

Ha az NVDA egy érintőképernyővel rendelkező számítógépen fut, Windows 8 (vagy újabb) operációs rendszer esetén lehetősége van az NVDA programot az érintőképernyő segítségével használni.

Az NVDA futása közben az összes érintőképernyő parancsot az NVDA értelmezi.

Ez azt jelenti, hogy a megszokott módon kiadott parancsok az NVDA futása közben nem működnek.

#### A képernyő tartalmának felfedezése {#toc23}

A legalapvetőbb parancs, amit használhat a képernyő egy adott pontján található vezérlőelem vagy szöveg felolvastatása.

Ehhez érintse meg a képernyőt.

Az ujját a képernyőn tarthatja, s bármilyen irányba elmozdíthatja, az NVDA bemondja az ujja alatt lévő szöveget.

#### Érintési Parancsok {#toc24}

A felhasználói útmutató későbbi szakaszaiban leírt parancsok némelyike rendelkezik egy érintési paranccsal, mely az érintőképernyőn elvégezhető a művelet végrehajtásához.

Az alábbiakban ezen érintési parancsok elvégzéséről olvashat.

##### Érintések {#toc25}

Egy vagy több ujjal érintse meg a képernyőt.

Az egy ujjas, egyszeri érintést általában érintésnek nevezzük.

A két ujjas érintés két ujjal elvégzett egyszeri érintést jelent.

Ha ugyanannyi ujjal, gyors egymásutánban többször érintjük meg a képernyőt, akkor ezt az NVDA többszörös érintésként kezeli.

A dupla érintés kétszeres, egy ujjas érintést jelent.

A tripla érintés egy ujjas, háromszori érintést jelent.

Természetesen az ujjak és az érintések száma kombinálható pl. két ujjas tripla érintés, négy ujjas érintés, stb.

##### Pöccintés {#toc26}

Gyorsan húzza végig az ujját a képernyőn, mintha csak egy morzsát szeretne lesöpörni.

Négy különböző pöccintés létezik, az iránytól függően: balra pöccintés, jobbra pöccintés, fel pöccintés és le pöccintés.

Ugyanúgy, mint az érintéseknél, a parancs itt is elvégezhető több ujjal.

Így tehát két ujjas fel pöccintés, vagy négy ujjas balra pöccintés is elfogadott.

#### Érintési Módok {#toc27}

Mivel az NVDA jóval több paranccsal rendelkezik mint amit egy érintőképernyőn el lehetne végezni, az NVDA több érintési móddal rendelkezik, melyek különböző rendeltetésű parancsokat tesznek elérhetővé.

A két jelenleg használt mód az elem és szöveges mód.

A parancsok mellett előfordulhat zárójelben egy érintési mód is.

Például a fel pöccintés (szöveges mód) azt jelenti, hogy a parancs csak a szöveges módban hajtódik végre.

Ha a parancs mellett nem található mód, akkor az mindegyik módban működik.

<!-- KC:beginInclude -->
Az érintési módok váltogatásához használja a három ujjas érintést.
<!-- KC:endInclude -->

### A bevitel súgó {#toc28}

Rengeteg beviteli parancsról említést teszünk ebben a felhasználói útmutatóban, de a parancsok legegyszerűbb megismerése a bevitel súgó bekapcsolásával érhető el.

A bevitel súgót az NVDA+1 billentyűparancs lenyomásával kapcsolhatja ki-be. Bekapcsolás után  ha funkcióval van ellátva bármely billentyű vagy érintési parancs, annak kiadásakor arról rövid tájékoztatást kaphat. A billentyűk és parancsok nem fognak a megszokott módon működni, lehetővé téve azok minél jobb megismerését.

### Az NVDA Menüje {#toc29}

A Windows bármely területén, az NVDA futása közben az NVDA menü az NVDA+n billentyűparanccsal, vagy két ujjas dupla érintéssel aktiválható.

A menü aktiválása után billentyűzet esetén használja a nyíl billentyűket a navigáláshoz, és az enter billentyűt egy menüelem aktiválásához.

Az NVDA menü a rendszertálcáról is elérhető. Kattintson a jobb egérgombbal az NVDA rendszertálcaikonjára, vagy a windowsgomb+b billentyűparanccsal ugorjon a rendszertálcára, majd a nyíl billentyűkkel keresse meg az NVDA ikonját és nyomja meg az alkalmazás billentyűt.

A beállítások almenü az NVDA beállításainak megváltoztatását teszi lehetővé. Az eszközök almenü néhány olyan hasznos alkalmazást tartalmaz, mint pl. az NVDA naplónézőjét, a bővítménykezelőt és az NVDA Python konzolt fejlesztők részére. A súgó almenüben többek között megtekintheti a felhasználói útmutatót és a billentyűparancsok listáját. Szintén az NVDA menüből mentheti el, illetve töltheti be a beállításokat. Ugyancsak ebben a menüben léphet ki az NVDA programból.

### Néhány alapvető NVDA parancs {#toc30}

<!-- KC:beginInclude -->

| Funkció |Asztali billentyűparancs |Laptop billentyűparancs |Érintési parancs |Leírás|
|---|---|---|---|---|
|Beszéd leállítása |Control |Control |2 ujjas érintés |A beszéd azonnali leállítása|
|A beszéd megállítása |Shift |Shift |nincs |Az első lenyomáskor a beszéd abbamarad, de a gomb újbóli lenyomása után a beszéd a megállítás helyétől folytatódik. Ez csak azokkal a beszédszintetizátorokkal működik, amelyek támogatják ezt a funkciót.|
|NVDA Menü |NVDA+n |NVDA+n |2 ujjas dupla érintés |Felugrik az NVDA menüje, ahonnan elérheti a beállításokat, a súgót, stb.|
|Váltás a beszédmódok között |NVDA+s |NVDA+s |nincs |Vált a beszédmódok (beszéd, hangjelzés, néma) között.|
|A beviteli súgó be-ki kapcsolása |NVDA+1 |NVDA+1 |nincs |Ha a bevitel súgó be van kapcsolva, és ha funkcióval van ellátva bármely parancs, akkor annak kiadása esetén arról rövid tájékoztatást kaphat.|
|Az NVDA bezárása |NVDA+q |NVDA+q |nincs |Bezárja a programot|
|Billentyűparancs átadása |NVDA+f2 |NVDA+f2 |nincs |Az ezutáni billentyűparancsot az NVDA figyelmen kívül hagyja, és átadja az aktív alkalmazásnak.|
|Az alvómód be- és kikapcsolása |NVDA+shift+s |NVDA+shift+z |nincs |Az alvómód kikapcsolja az NVDA összes billentyűparancsát és beszéd/braille kimenetét egy adott alkalmazásban. A billentyűparancs újbóli lenyomására visszaállítja azt. Ez azokban az alkalmazásokban előnyös, amelyek rendelkeznek saját beszéddel, vagy képernyőolvasó tulajdonságokkal.|

<!-- KC:endInclude -->

### Rendszerinformációk bemondása {#toc31}

<!-- KC:beginInclude -->

| Funkció |billentyűparancs |leírás|
|---|---|---|
|A jelenlegi idő |NVDA+f12 |Egyszeri megnyomásra a jelenlegi időt, kétszeri (gyors) megnyomásra az aktuális dátumot mondja be.|
|Telep állapotának bemondása |NVDA+shift+b |Bemondja a telep állapotát és a hátralévő időt, ha töltés alatt van, akkor a töltöttségi szintet.|
|Vágólap szövegének bemondása |NVDA+c |Bemondja a vágólapon található szöveget, ha van.|

<!-- KC:endInclude -->

## Navigáció az NVDA-val {#toc32}

Az NVDA-val lehetősége van feltérképezni az operációs rendszert, mind az alapértelmezett (rendszerkurzor) módon, mind pedig az NVDA nyújtotta módszerekkel (navigátor kurzor, áttekintő kurzor, síkáttekintés).

### Az objektumokról {#Objects}

Minden alkalmazás, de maga az operációs rendszer is objektumokat tartalmaz.
Az objektum egy különálló elem, ami lehet  összefüggő szöveg, gomb, jelölőnégyzet, csúszka, lista vagy egy szerkesztőmező.

### Navigáció a fókusszal {#SystemFocus}

A rendszerfókusz, vagy fókusz egy [objektum](#Objects) ami fogadja a billentyűzeten leütött billentyűket. Így pl. amikor egy szerkeszthető szöveges mezőbe gépel, a fókusz az adott  mezőben van.

Az NVDA-val való leggyakoribb navigációs mód a Windows fókuszának változtatásával történik. Ez esetben a Windows szabványos billentyűparancsok használhatóak:

* A tabbal és shift-tabbal lépkedhet előre-hátra a vezérlőelemek között
* Az alttal hívhatja elő a menüsort és a menükben a nyilakkal közlekedhet
* A futó alkalmazások között az alt-tabbal válthat

Ha ezek valamelyikét lenyomja, az NVDA elmond néhány információt az adott objektumról, pl. annak  nevét, típusát és állapotát, értékét, leírását, billentyűparancsát és az esetleg még rendelkezésre álló további információkat.

Néhány hasznos billentyűparancs a fókusszal történő mozgás esetén:
<!-- KC:beginInclude -->

| Funkció |Asztali billentyűparancs |Laptop billentyűparancs |Leírás|
|---|---|---|---|
|aktuális objektum felolvasása |NVDA+tab |NVDA+tab |Bemondja az aktuális fókuszban lévő vezérlőelemet, vagy objektumot, kétszeri lenyomásra betűzi.|
|Az ablak címének bemondása |NVDA+T |NVDA+T |Felolvassa az aktív ablak címét|
|Az aktív ablak felolvasása |NVDA+B |NVDA+B |Felolvassa az előtérben lévő ablak tartalmát (hasznos lehet párbeszédpanelek felolvastatásakor)|
|Állapotsor bemondása |NVDA+end |NVDA+shift+end |Bemondja az aktív alkalmazás állapotsorát (ha az NVDA megtalálja), és a navigátor kurzort oda  helyezi. Kétszeri megnyomásra betűzi az információt.|

<!-- KC:endInclude -->

### Navigáció a rendszerkurzorral {#SystemCaret}

ha egy [objektumon](#Objects) amely szövegben történő navigálást és/vagy szerkesztést tesz lehetővé van a [fókusz](#SystemFocus), a rendszerkurzor - másnéven szerkesztő kurzor - használatával mozoghat a szövegben.

Ha a fókusz olyan objektumon áll, amely (rendszerkurzort) tartalmaz, abban a nyilakkal közlekedhet és úgy végezhet benne szerkesztési műveleteket, mint az NVDA nélkül is tenné. Az NVDA felolvassa a karakterek, szavak, sorok közti mozgást, sőt azt is, ha egy szöveg ki van jelölve, vagy a kijelölése megszűnik.

Ha a rendszerkurzorral navigál, az áttekintő kurzor követni fogja azt.

Az NVDA a következő billentyűparancsokat biztosítja a rendszerkurzor mozgatásához:
<!-- KC:beginInclude -->

| Funkció |Asztali billentyűparancs |Laptop billentyűparancs |Leírás|
|---|---|---|---|
|folyamatos felolvasás |NVDA+lenyíl |NVDA+a |A rendszerkurzor aktuális pozíciójától a szöveg végéig olvas.|
|Aktuális sor felolvasása |NVDA+felnyíl |NVDA+l |Felolvassa a kurzornál lévő sort, kétszer megnyomva betűzi azt.|
|Következő mondat |alt+lenyíl |alt+lenyíl |A kurzort a következő mondatra helyezi, és felolvassa azt (jelenleg ez csak a Microsoft Word és Outlook programban érhető el).|
|Előző mondat |alt+felnyíl |alt+felnyíl |A kurzort az előző mondatra helyezi, és felolvassa azt (jelenleg ez csak a Microsoft Word és Outlook programban érhető el).|
|A kijelölt szöveg felolvasása |NVDA+Shift+felnyíl |NVDA+shift+s |Felolvassa a kijelölt szöveget.|
|A karakter formázásának bemondása |NVDA+f |NVDA+f |Bemondja a formázási beállítását annak a karakternek, melyen a rendszerkurzor éppen áll. Kétszeri gyors megnyomásra az információkat megjeleníti böngészőmódban, mely az escape megnyomásával zárható be.|

Ha egy táblázatban áll, a következő billentyűparancsok érhetők el:

| Funkció |Billentyűparancs |Leírás|
|---|---|---|
|ugrás az előző oszlophoz |control+alt+balranyíl |A rendszerkurzort az azonos sorban lévő előző oszlophoz helyezi.|
|Ugrás a következő oszlophoz |control+alt+jobbranyíl |A rendszerkurzort a következő, ugyanabban a sorban lévő| oszlophoz helyezi.|
|Ugrás az előző sorhoz |control+alt+felnyíl |A kurzort ugyanabban az oszlopban az előző sorhoz helyezi.|
|Ugrás a következő sorhoz |control+alt+lenyíl |A kurzort ugyanabban az oszlopban a következő sorra helyezi.|

<!-- KC:endInclude -->

### Közlekedés az elemek között {#ObjectNavigation}

Előfordulhat, hogy akár egy alkalmazást, akár az operációs rendszert a [fókusz](#SystemFocus) elmozdítása nélkül szeretné bejárni.
Szintén ebbe a kategóriába tartoznak azok az [elemek](#Objects) melyek a billentyűzet segítségével nem érhetőek el a megszokott módon.
Ezekben az esetekben használható a navigátor kurzor.

A navigátorkurzor segítségével lépkedhet az egyes elemek (objektumok) között, elolvashatja szövegüket és egyéb információkat kérdezhet le.
Egy elemre lépéskor az NVDA a rendszerkurzornál megszokott módon mondja be az elemek nevét, típusát (ha ismert).
A képernyőn található teljes szöveg áttekintésére használhatja a [síkáttekintő](#FlatReview) módot.

Az egymás melletti elrendezés helyett (főként az oda-vissza mozgás elkerüléseként), az objektumok hierarchikus csoportba vannak rendezve.
Ez azt eredményezi, hogy ha egy adott objektum több objektumot tartalmaz, először az első gyermekobjektumra kell lépni, ekkor a tartalma is hozzáférhetővé válik.
pl. ha a képernyőn egy lista szerepel, a listaelemek megtekintéséhez először a lista első gyermekelemére (azaz a lista első elemére) kell lépnie. Ekkor a lépés az előző/következő objektumra billentyűparancsok a listaelem objektumai (elemei) között fognak lépkedni.
A listaobjektumhoz visszatérve ezek a billentyűparancsok ismét a listával egy szinten lévő objektumokon lépkednek.
Hasonlóképpen, egy eszköztár vezérlőelemeinek megtekintéséhez az eszköztár első gyermekobjektumára (vezérlőelemére) kell lépnie.

Az elemek közötti közlekedéshez használja a következő parancsokat:
<!-- KC:beginInclude -->

| Funkció |asztali billentyűparancs |Laptop billentyűparancs |Érintési parancs |Leírás|
|---|---|---|---|---|
|az aktuális objektum bemondása |NVDA+5 a numerikus billentyűzeten |NVDA+shift+o |Nincs |Felolvassa az aktuális objektumot, kétszeri megnyomásra betűzi azt, háromszori lenyomásra pedig az objektum nevét és értékét a vágólapra másolja.|
|Az objektum szülőelemére lépés |NVDA+8 a numerikus billentyűzeten |NVDA+shift+felnyíl |felfelé pöccintés (elem mód) |A szülő elemre lép (egy szinttel visszalép a fanézet gyökere felé).|
|az előző elemre lépés |NVDA+4 a numerikus billentyűzeten |NVDA+shift+balranyíl |balra pöccintés (elem mód) |Az előző, a jelenlegivel azonos szinten lévő elemre lép.|
|A következő elemre lépés |NVDA+6 a numerikus billentyűzeten |NVDA+shift+jobbranyíl |jobbra pöccintés (elem mód) |A következő, a jelenlegivel azonos szinten lévő elemre lép|
|Az első gyermekelemre lépés |NVDA+2 a numerikus billentyűzeten |NVDA+shift+lefelenyíl |lefelé pöccintés (elem mód) |Az aktuális objektum első gyermekelemére lép.|
|A navigátor kurzor és az áttekintő kurzor áthelyezése |NVDA+minusz a numerikus billentyűzeten |NVDA+backspace |nincs |A navigátor kurzort az aktuális fókuszhoz, az áttekintő kurzort ha lehetséges, a kurzor aktuális pozíciójához helyezi.|
|Az aktuális objektum aktiválása |NVDA+enter a numerikus billentyűzeten |NVDA+enter |dupla érintés |Aktiválja az aktuális elemet (pl. enter, szimpla vagy dupla kattintás).|
|A kurzor áthelyezése a navigátor kurzorhoz |NVDA+shift+Minusz a numerikus billentyűzeten |NVDA+shift+backspace |nincs |A kurzort egyszeri lenyomásra a navigátor kurzorhoz, háromszori lenyomásra pedig az áttekintő kurzorhoz helyezi|
|Elem pozíciójának bemondása |NVDA+delete a numerikus billentyűzeten |NVDA+delete |nincs |Bemondja az áttekintő kurzor alatt található szöveg vagy objektum elhelyeszkedését. Ez tartalmazhatja a szöveg százalékos elhelyezkedését az aktuális dokumentumban, a lapszéltől vett távolságot, vagy a pontos képernyő pozíciót. Kétszeri gyors megnyomásra további információ hangzik el.|

<!-- KC:endInclude -->

Megjegyzés: A funkciók megfelelő működéséhez A numlock billentyűnek kikapcsolt állapotban kell lennie.

Ha a fókusszal navigál, a navigátor kurzor alatt lévő elem a fókusszal együtt változik. Ha azt szeretné, hogy a navigátor kurzor egy adott helyen maradjon, kapcsolja ki a fókusz követését a navigátor kurzorral lehetőséget az NVDA+7 billentyűparanccsal.

### Az aktuális elem szövegének áttekintése {#ReviewingText}

Az NVDA lehetővé teszi, hogy a [navigátor kurzornál](#ObjectNavigation) lévő elem tartalmát (ide tartozik a [sík áttekintés](#FlatReview) is) betűről betűre, szóról szóra, sorrol sorra átolvassa. Ez hasznos pl. parancssorablakban, vagy olyan helyen, ahol csak korlátozott rendszerkurzor aktív, esetleg ha ilyen nem található.

Ha mozgatja az áttekintő kurzort, a rendszer kurzor nem követi azt. Ezzel szemben az áttekintő kurzor követi a rendszer kurzor mozgását, amit természetesen kikapcsolhat.

Az áttekintő kurzor parancsai:
<!-- KC:beginInclude -->

| Funkció |Asztali billentyűparancs |Laptop billentyűparancs |Érintésiparancs |Leírás|
|---|---|---|---|---|
|ugrás a szöveg első sorára |Shift+7 a numerikus billentyűzeten |NVDA+control+home |nincs |Az áttekintő kurzort a szöveg első sorára viszi.|
|Ugrás az előző sorra |7 a numerikus billentyűzeten |NVDA+felnyíl |felfelé pöccintés (szöveges mód) |Az áttekintő kurzort az előző sorra viszi.|
|Az aktuális sor felolvasása |8 a numerikus billentyűzeten |NVDA+shift+. (pont) |nincs |Felolvassa az áttekintő kurzornál lévő sort, háromszor megnyomva betűzi azt|
|Ugrás a következő sorra |9 a numerikus billentyűzeten |NVDA+lefelenyíl |lefelé pöccintés (szöveges mód) |Az áttekintő kurzort a szöveg következő sorára helyezi.|
|alsó sor felolvasása |Shift+9 a numerikus billentyűzeten |NVDA+control+end |nincs |Az áttekintő kurzort a szöveg alsó sorához helyezi|
|Ugrás az előző szóhoz |4 a numerikus billentyűzeten |NVDA+control+balranyíl |két ujjas pöccintés balra (szöveges mód) |Az áttekintő kurzort a szöveg előző szavához helyezi.|
|jelenlegi szó felolvasása |5 a numerikus billentyűzeten |NVDA+control+. (pont) |nincs |Bemondja az áttekintő kurzornál lévő szót. Kétszeri lenyomásra betűzi, háromszori lenyomásra a karakter leírással betűzi azt.|
|Ugrás a következő szóhoz |6 a numerikus billentyűzeten |NVDA+control+jobbranyíl |két ujjas jobbra pöccintés (szöveges mód) |Az áttekintő kurzort a következő szóhoz helyezi.|
|Ugrás a sor elejére |Shift+1 a numerikus billentyűzeten |NVDA+home |nincs |Az áttekintő kurzort az aktuális sor elejére helyezi.|
|Ugrás az előző karakterre |1 a numerikus billentyűzeten |NVDA+balranyíl |pöccintés balra (szöveges mód) |Az áttekintő kurzort az előző karakterhez helyezi.|
|Jelenlegi karakter felolvasása |2 a numerikus billentyűzeten |NVDA+. (pont) |nincs |Bemondja azt a karaktert, ahol az áttekintő kurzor található. Kétszeri lenyomásra a karakterhez tartozó szót, háromszori lenyomásra a decimális és a hexadecimális kódját mondja be.|
|Ugrás a következő karakterre |3 a numerikus billentyűzeten |NVDA+jobbranyíl |jobbra pöccintés (szöveges mód) |Az áttekintő kurzort a következő, az aktuális sorban lévő  karakterre helyezi.|
|áttekintő kurzor a sor végéhez |Shift+3 a numerikus billentyűzeten |NVDA+end |nincs |Az áttekintő kurzort a sor végéhez helyezi.|
|Folyamatos felolvasás az áttekintő kurzorral |+ (plusz) a numerikus billentyűzeten |NVDA+shift+a |három ujjas lefelé pöccintés |Folyamatos olvasás az aktuális pozíciótól az elem tartalmának végéig.|
|Szöveg másolásának megkezdése az áttekintő kurzorral |NVDA+f9 |NVDA+f9 |nincs |Megjelöli az áttekintő kurzor aktuális pozícióját.|
|A kijelölt szöveg vágólapra másolása |NVDA+f10 |NVDA+f10 |nincs |A megadott kezdőponttól az áttekintő kurzor jelenlegi pozíciójáig lévő szöveget a vágólapra másolja.|
|Szöveg formázásának bemondása |NVDA+f |NVDA+f |nincs |Bemondja az áttekintő kurzornál található formázási információkat|

<!-- KC:endInclude -->

Megjegyzés: a numerikus billentyűzet billentyűi akkor működnek megfelelően, ha a numlock ki van kapcsolva.

A könnyű megjegyezhetőség érdekében igyekeztünk logikus struktúrát kialakítani. Az asztali billentyűzetkiosztás használatakor a gombok elhelyezkedése egyfajta táblázatként is felfogható. Így a soronkénti felosztás a következő:

|sor |szó |karakter|

Az oszloponkénti felosztás pedig a következő:

|előző |jelenlegi |következő|

Ha a fókusz szerkesztőmezőn áll és a rendszerkurzor mozog, az áttekintő kurzor követi azt. Ha azt szeretné, hogy az áttekintő kurzor egy adott helyen maradjon és ne kövesse a rendszerkurzort, kapcsolja ki az NVDA+6 billentyűparanccsal az áttekintő kurzor követi a rendszerkurzort opciót.

Előfordulhat, hogy egy szöveg bizonyos részeit szeretné kimásolni, amelyet az áttekintő kurzorral épp tanulmányoz. Pl. egy internetcímet, amit mások egy üzenetküldő programmal küldtek. A művelet megkezdéséhez helyezze az áttekintő kurzort a másolandó szöveg első karakteréhez, majd nyomja meg az NVDA+f9 billentyűkombinációt. Menjen el a másolandó szöveg végére, itt nyomja meg az NVDA+f10 billentyűkombinációt. (Ezzel megadta a kezdő és zárójelölőt úgy, ahogyan a régi típusú, pl. Ms-dos alatt futó szövegszerkesztőkben (Pl. Norton Editor) jelölt ki szöveget). A szöveget az NVDA automatikusan a vágólapra másolja, ahonnan azt szabványos vindows művelettel beillesztheti (control-v) bármelyik programba. Tartsa azonban szem előtt, hogy ha a program normál rendszerkurzort használ és lehetővé teszi a szabványos kijelölési és másolási parancsokat (controll+C), akkor használja inkább a szabványos parancsokat, mert azokkal esetenként jobb eredményt érhet el (pl. formázás megtartása, stb).

### Áttekintő Módok {#ReviewModes}

Az NVDA [Szöveg áttekintő parancsai](#ReviewingText) segítségével áttekinthető a navigátor kurzornál található elem, az aktuális dokumentum, vagy a képernyő, a kiválasztott áttekintési módtól függően.
Az áttekintő módok az NVDA régebbi verzióiban található sík áttekintést helyettesítik.

Az alábbi parancsokkal válthat az áttekintő módok között:
<!-- KC:beginInclude -->

| Név |Asztali Billentyűparancs |Laptop Billentyűparancs |Érintési parancs |Leírás|
|---|---|---|---|---|
|Váltás a következő áttekintő módra |NVDA+numpad7 |NVDA+pageUp |Két ujjas felfelé pöccintés |Átvált a következő elérhető áttekintő módra|
|Váltás az előző áttekintő módra |NVDA+numpad1 |NVDA+pageDown |2 ujjas lefelé pöccintés |Átvált az előző elérhető áttekintő módra|

<!-- KC:endInclude -->

#### Elem Áttekintés {#ObjectReview}

Elem áttekintő módban kizárólag a navigátor kurzornál található [elem](#ObjectNavigation) tartalma érhető el.
Szerkesztőmezők, vagy egyéb szövegmezők esetén ez általában a vezérlőelemekben található szöveg.
Egyéb elemek esetén a tartalom lehet a vezérlőelemek neve és/vagy értéke is.

#### Dokumentum Áttekintés {#DocumentReview}

Ha az aktuális [elem](#ObjectNavigation) egy böngészőmóddal rendelkező dokumentum (pl. egy weboldal) vagy egyéb összetett dokumentum (pl. egy Lotus Symphony dokumentum), a dokumentum áttekintés mód elérhető.
A dokumentum áttekintés mód segítségével egy dokumentum teljes egészében elolvasható, áttekinthető.

Elem áttekintésről dokumentum áttekintésre váltáskor az áttekintő kurzor a navigátor kurzor jelenlegi pozíciójához kerül.
Az áttekintési parancsok használatakor a navigátor kurzor az áttekintő kurzornál található elemhez kerül.

Az NVDA elem áttekintés mód használatakor automatikusan Dokumentum Áttekintés módra vált, ha egy böngészőmóddal rendelkező dokumentumra lépünk.

#### Képernyő Áttekintés {#ScreenReview}

A Képernyő Áttekintés mód segítségével áttekintheti a képernyő teljes tartalmát úgy, ahogyan az egy adott alkalmazás esetén a képernyőn is megjelenik.
Ez a funkció hasonlóan működik más, Windows képernyőolvasókban megszokott funkciókhoz (pl. egér kurzor).

Képernyő Áttekintés módra váltáskor az áttekintő kurzor a navigátor kurzor pozíciójánál található [elemhez](#ObjectNavigation) kerül.
Az áttekintési parancsok használatakor a navigátor kurzor az áttekintő kurzornál található elemhez kerül.

Néhány újabb alkalmazás használatakor az NVDA esetenként nem képes felismerni a képernyőn található szöveg részét, vagy egészét. Ez az újabb képernyő kirajzoló technológiáknak köszönhető, melyek támogatása jelenleg nem lehetséges.

### Navigáció az egérrel {#toc42}

Ha az egeret mozgatja, az NVDA automatikusan felolvassa az egérmutató alatt lévő szöveget, ahogy elhalad fölötte.

Ha ez támogatva van, az NVDA képes egész bekezdéseket is felolvasni annak ellenére, hogy más elemek szövegét sorról sorra olvassa.

Az NVDA beálítható úgy is, hogy felolvassa annak a vezérlőelemnek a típusát, amelyen az egérmutató áthalad. Ez hasznos lehet a teljesen vak felhasználók számára, akiknek a vezérlőelemek szövegének felolvasása nem elég.

Az NVDA képes hanggal is tájékoztatni a felhasználót az egér pozíciójáról. Minél magasabb a hang, az egérmutató annál közelebb van a képernyő felső, minél mélyebb, az alsó széléhez. A képernyő bal és jobb széléhez való közelítést a hang irányából lehet megállapítani, ha sztereó fejhallgatót használ.

Kiegészítő megjegyzés: A képernyő sötétebb vagy világosabb részeiről az NVDA a hangjelzés hangerejével tájékoztat. Minél hangosabb a hangjelzés, annál világosabb az adott képernyőterület.

Ezek a funkciók alapértelmezés szerint ki vannak kapcsolva, de ha ki szeretné használni ezek előnyeit, az egér beállításai párbeszédpanelen ezek bekapcsolhatóak. A párbeszédpanelt az NVDA menü beállítások almenüjében érheti el.
Bár az egér használatához egy fizikai egér (vagy más mutatóeszköz, pl. Trackball) szükséges, az NVDA rendelkezik néhány billentyűparanccsal a könnyebb használat érdekében.
<!-- KC:beginInclude -->

| Funkció |Asztali billentyűparancs |Laptop billentyűparancs |Leírás|
|---|---|---|---|
|bal egérgomb kattintás |Numerikus / |NVDA+ő |Egyszeri kattintást végez a bal egérgombbal. Dupla kattintáshoz nyomja le kétszer egymás után gyorsan.|
|bal egérgomb zárolása és feloldása |Shift+numerikus / |NVDA+control+ő |Zárolja a bal egérgombot, következő lenyomásra feloldja. Ez ugyanazt a funkciót látja el, mintha kézzel nyomva tartaná a bal egérgombot.|
|jobb egérgomb kattintás |Numerikus * |NVDA+ú |Egyszeri kattintást végez a jobb egérgombbal.|
|Jobb egérgomb zárolása és feloldása |Shift +numerikus * |NVDA+control+ú |Zárolja a jobb egérgombot, a következő lenyomásra feloldja azt. Ez ugyanazt a funkciót látja el, mintha kézzel nyomva tartaná a jobb egérgombot.|
|Az egérmutató áthelyezése a navigátor kurzorhoz |NVDA+numerikus per |NVDA+shift+m |Az egérmutatót a navigátor kurzornál található elemhez helyezi.|
|A navigátor kurzor áthelyezése az egérmutatóhoz |NVDA+numerikus csillag |NVDA+shift+n |A navigátor kurzort az egérmutatónál lévő elemhez helyezi.|

<!-- KC:endInclude -->

## A böngészőmód {#BrowseMode}

Az összetett csak olvasható dokumentumok, pl. a weblapok, az NVDA-ban a virtuális kijelzőben jelennek meg.

A virtuális kijelző egy egyszerűsített nézetét tartalmazza pl. egy weboldalnak, amelyben a nyilakkal mozoghat. A különböző információkat, pl.  ha az adott szövegrész egy hivatkozás, a címsorokat, és egyéb információkat az NVDA a szöveggel együtt olvassa.

A virtuális kijelzőben az NVDA kétféleképpen használható. Böngészőmódban egy virtuális kurzor segítségével mozoghat a szövegben, fókuszmódban viszont közvetlenül vihet információkat a böngészőbe, pl. írhat a szerkesztőmezőkbe, választhat a kombinált listákon, bejelölheti az egyik választógombot, tehát ugyanazokat a billentyűket használhatja, amelyeket egyébként is használna. Az NVDA böngészőmódból automatikusan fókuszmódba kapcsol, ha olyan vezérlőelemre lép, amelynek használatához erre van szükség. Kézzel is átválthat fókuszmódra az NVDA+szóköz billentyűparanccsal. Ha az NVDA automatikusan fókuszmódra váltott egy tab vagy egy kattintás miatt, automatikusan visszavált böngészőmódba, ha olyan elemre lép, amely csak így tekinthető meg. Ha viszont kézzel kapcsolta be az NVDA+szóközzel a fókuszmódot, az NVDA mind addig fókuszmódban marad, amíg az escape-pel vagy az NVDA+szóköz billentyűparanccsal vissza nem vált böngészőmódba. A böngészőmód párbeszédpanelen (NVDA menü beállítások almenüjében) tiltani lehet a fókuszmód és böngészőmód automatikus váltását.
<!-- KC:beginInclude -->

| Funkció |billentyűparancs |leírás|
|---|---|---|
|Váltás a virtuális kijelző módjai közt |NVDA+szóköz |Vált a fókuszmód és a  böngészőmód közt|
|Kilépés a fókuszmódból |escape |Visszavált a fókuszmódból böngészőmódra.|
|A virtuális kijelző frissítése |NVDA+f5 |Frissíti a virtuális kijelző tartalmát. Ez akkor lehet hasznos, ha egy oldal hiányosan töltődött be. (a funkció nem érhető el Microsoft Word és Outlook programok használata esetén).|
|Keresés |NVDA+control+f |A felbukkanó ablak segítségével egy szövegrészletre kereshet rá az adott oldalon.|
|Ugrás a következő találatra |NVDA+f3 |Az ön által keresett kifejezés következő előfordulására ugrik.|
|Ugrás az előző találatra |NVDA+shift+f3 |Az ön által keresett kifejezés előző előfordulására ugrik.|

<!-- KC:endInclude -->

Az NVDA jelenleg a Mozilla Firefoxban, a Microsoft Internet Explorerben, a Mozilla Thunderbirdben, a Microsoft Outlook html üzeneteiben, a Google chromeban, az Adobe Readerben, és az Adobe flashben használ virtuális kijelzőt a dokumentumok olvasásához. A Microsoft Word összetett dokumentumaiban is elérhető a böngészőmód, mely megkönnyíti az abban történő navigációt.

### Navigációs gyorsbillentyűk {#toc44}

Böngészőmódban az NVDA a gyorsabb navigáció érdekében egykarakteres navigációs gyorsbillentyűket tartalmaz a virtuális kijelző meghatározott területére történő ugráshoz.
Megjegyzés: Nem minden gyorsbillentyűhasználható a böngészőmódot támogató dokumentumokban.

<!-- KC:beginInclude -->
Egymagukban a következő, a shifttel együtt használva az előző területre ugranak:

* H: címsor
* L: lista
* i: listaelem
* T: táblázat
* K: hivatkozás
* F: űrlapmező
* U: meg nem látogatott hivatkozás
* V: meglátogatott hivatkozás
* E: szerkesztőmező
* B: gomb
* X: jelölőnégyzet
* C: kombinált listamező
* R: választógomb
* Q: idézetblokk
* S: elválasztó
* M: keret
* G: ábra
* D: Jelzőpont
* N: hivatkozás nélküli szöveg
* O: beágyazott objektum (audio és videolejátszó, webes alkallmazások, felugró ablakok, stb)
* a: Mellékszöveg (megjegyzés, korrektúra szöveg, stb)
* 1-től 6-ig: elsőtől hatodikig terjedő szintű címsorokra történő ugrás
* w: Helyesírási hiba

Első vagy utolsó elemre ugrás (listák vagy táblázatok esetében):

| Funkció |billentyűparancs |leírás|
|---|---|---|
|Egy elemblokk első elemére ugrás |shift+vessző |Egy elemblokk (pl. lista vagy táblázat) elejére lép|
|Egy elemblokk utolsó elemére ugrás |vessző |Egy elemblokk (pl. lista vagy táblázat) végéhez lép|

<!-- KC:endInclude -->

Kiegészítő megjegyzés: a navigációs gyorsbillentyűket könnyebb megjegyezni, ha megjegyezzük azoknak a fogalmaknak az angol megfelelőjét, amire utalnak. Pl.: edit box: szerkesztőmező, radio button: választógomb.

Megjegyzés: Bizonyos alkalmazásokban (Facebook, Gmail, stb) elérhetőek a böngészést segítő billentyűparancsok. Ezek használatához ki kell kapcsolnia az egykarakteres navigációt.
<!-- KC:beginInclude -->
Az egykarakteres navigáció ki/bekapcsolásához a jelenlegi dokumentumban nyomja meg az  NVDA+shift+szóköz billentyűparancsot.
 <!-- KC:endInclude -->

### Az elemek listája {#toc45}

Az aktuális virtuális kijelzőben az elemek listájának megjelenítéséhez nyomja meg az NVDA+f7 billentyűparancsot. Ez a hivatkozások,  címsorok, űrlap mezők, gombok, és a jelzőpontok listáját tartalmazza. Egy választógombbal lehet kiválasztani, hogy melyik típusú elemek listáját szeretné megjeleníteni. A "szűrés" mezőbe beírhatja a keresett elem első pár karakterét, így a shift+tabbal visszalépve csak a feltételnek megfelelő elemek listája jelenik meg. Egy elemet az enterrel, vagy az "aktiválás" gombbal aktiválhat. Az "Ugrás gomb" lenyomásakor a kurzor arra az elemre ugrik, de nem aktiválja azt.
<!-- KC:beginInclude -->

| Funkció |billentyűparancs |leírás|
|---|---|---|
|A virtuális kijelző elemeinek listája |NVDA+f7 |A billentyűparancs lenyomására egy ablak bukkan fel, amely tartalmazza a virtuális kijelző címsorainak, hivatkozásainak, és jelzőpontjainak listáját.|

<!-- KC:endInclude -->

### A beágyazott objektumokról {#toc46}

Azokon a weblapokon, amelyeken szórakoztató tartalmak találhatóak (Pl Youtube videók), és az Adobe Flash vagy a Sun Java technológiát használják, az NVDA a "beágyazott objektum" kifejezés bemondásával jelez. Ha ekkor entert nyom, és ez az objektum akadálymentes, a tab vagy a nyíl billentyűk használatával lépkedhet az elemeken (legtöbbször gombokon), amit az enter, vagy a szóköz billentyűvel aktiválhat.
A következő billentyűparanccsal visszaléphet a beágyazott objektumot tartalmazó dokumentumra:
<!-- KC:beginInclude -->

| Funkció |Billentyűparancs |leírás|
|---|---|---|
|Visszalépés a virtuális kijelzőbe |NVDA+control+szóköz |A fókuszt a beágyazott objektumról az azt tartalmazó dokumentumra helyezi.|

<!-- KC:endInclude -->

## Matematikai tartalom olvasása {#toc47}

A Design Science által fejlesztett MathPlayer szoftverrel az NVDA képes a matematikai tartalmak kezelésére, az azokban történő navigációra.
Ehhez az szükséges, hogy a MathPlayer legalább 4-es verziója a számítógépre fel legyen telepítve, ami ingyenesen letölthető a következő címről: https://www.dessci.com/en/products/mathplayer/

Az NVDA a következő matematikai tartalmakat támogatja:

* MathML a Mozilla Firefox, Microsoft Internet Explorer és Google Chrome böngészőkben.
* A Design Science által forgalmazott MathType a Microsoft Word és PowerPoint programokban.
* MathML az Adobe Reader programban. Megjegyzendő, hogy ez nem egy hivatalos szabvány jelenleg, így nincs nyilvánosan elérhető szoftver, amely képes a tartalom teljeskörű kezelésére.

Dokumentum olvasásakor az NVDA bejelenti ha egy matematikai tartalomhoz ér, braille kijelző használata esetén a matematikai tartalom a braille szabványnak megfelelően megjelenik a kijelzőn.

### Interaktív navigáció {#toc48}

Ha ön elsősorban a beszédkimenettel dolgozik, akkor szüksége lehet a kifejezés kissebb részekben történő meghallgatására.

Böngészőmód használata esetén ezt megteheti, csak keresse meg a matematikai tartalmat és nyomja meg az enter billentyűt.

Ha nem böngészőmódban van:

1. Keresse meg az áttekintő kurzorral a matematikai tartalmat.
Alapértelmezetten az áttekintő kurzor követi a rendszerfókuszt, így ezt megteheti a nyíl billentyűk használatával is.
1. Nyomja le a következő billentyűparancsot:

<!-- KC:beginInclude -->

| Megnevezés |Billentyűparancs |Leírás|
|---|---|---|
|Matematikai tartalom aktiválása |NVDA+alt+m |Belép a matematikai áttekintőbe.|

<!-- KC:endInclude -->

Ettől a ponttól kezdve használhatja a MathPlayer billentyűparancsait (pl. a nyíl billentyűket) a tartalom áttekintésére.
Így például bejárhatja a teljes kifejezést a jobbra és balra nyíl használatával, de megtekintheti annak csak egy részletét is (pl. egy zárójel tartalmát) a lefele nyíl megnyomásával.

Bővebb információkért olvassa el a MathPlayer súgóját: https://www.dessci.com/en/products/mathplayer/navigation_commands.htm

Amennyiben szeretne visszatérni a fődokumentumba, nyomja meg az escape billentyűt.

## Braille {#toc49}

Ha rendelkezik braille kijelzővel, az NVDA képes információkat megjeleníteni rajta.
Amennyiben a kijelzője rendelkezik Perkins-féle billentyűzettel, lehetőség van braille bevitelére rövidírással és teljes írással egyaránt.

A támogatott braille kijelzőkkel kapcsolatos információkért nézze meg a [Támogatott Braille kijelzők](#SupportedBrailleDisplays) fejezetet.
A [braille beállítások párbeszédablakon](#BrailleSettings) találja a braille-lal kapcsolatos beállításokat.

### Braille vezérlőtípus-, állapot- és jelzőpontrövidítések {#toc50}

Ahhoz, hogy a braille kijelzőn minél több információ elférjen, a következő rövidítéseket alkalmazzuk a vezérlőelemek típusának, állapotának, ill. a jelzőpontok feltüntetésére.

| Rövidítés |Vezérlőtípus|
|---|---|
|app |alkalmazás|
|idéz |idézetblokk|
|gb |gomb|
|lngb |lenyílógomb|
|lgb |léptetőgomb|
|ogb |osztott gomb|
|tgb |többállapotú gomb|
|klm |kombinált listamező|
|jn |jelölőnégyzet|
|pbp |párbeszédpanel|
|dok |dokumentum|
|szm |szerkesztőmező|
|jlsz |jelszó szerkesztőmező|
|beobj |beágyazott objektum|
|végj |végjegyzet|
|lábj |lábjegyzet|
|ábra |ábra|
|csop |elemcsoport|
|cN |címsor n. szintű, pl. c1, c2.|
|súgó |súgóbuborék|
|jp |jelzőpont|
|hv |hivatkozás|
|mhv |meglátogatott hivatkozás|
|lm |lista|
|mnü |menü|
|mnüs |menüsor|
|mnügb |menügomb|
|mnüe |menüelem|
|tlt |panel|
|foly |folyamatjelző|
|rgb |választógomb|
|gs |gördítősáv|
|szksz |szakasz|
|ás |állapotsor|
|fül |fül|
|tbl |táblázat|
|oN |N. számú táblázatoszlop, pl. o1, o2.|
|sN |N. számú táblázatsor, pl. s1, s2.|
|psor |parancssor|
|et |eszköztár|
|etip |eszköztipp|
|fn |fanézet|
|fngb |körvonalgomb|
|fne |fanézetelem|
|lv N |N. szintű fanézetelem|
|ablk |ablak|
|????? |elválasztó|

Az állapotjelzők rövidítései:

| Rövidítés |Vezérlő állapot|
|---|---|
|... |automatikus kiegészítést támogató elem|
|??? |az elem (pl. többállapotú gomb) lenyomva|
|??? |az elem (pl. többállapotú gomb) nincs lenyomva|
|??? |az elem (pl. jelölőnégyzet) be van jelölve|
|??? |az elem (pl. jelölőnégyzet) félig be van jelölve|
|??? |az elem (pl. jelölőnégyzet) nincs bejelölve|
|- |az elem (pl. fanézetelem) nyitva|
|+ |az elem (pl. fanézetelem) zárva|
|*** |védett elem vagy dokumentum|
|kat |kattintható elem|
|megj |megjegyzést tartalmazó táblázatcella, vagy szövegrész|
|képl |képletet tartalmazó táblázatcella|
|érvn |érvénytelen bejegyzés|
|hleir |egy elem (általában ábra) hosszú leírással rendelkezik|
|tbsor |többsoros szerkesztőmező, pl. kommentek szerkesztőmezője a weboldalakon|
|köt |kötelezően kitöltendő űrlapmező|
|ol |csak olvasható elem (pl. szerkesztőmező)|
|kv |kijelölt elem|
|nkij |nem kijelölt elem|
|rendn |növekvő rendezés|
|rendcs |csökkenő rendezés|
|amnü |az elem felugró almenüt tartalmaz|

Végül a jelzőpontok különböző típusainak rövidítései:

| Rövidítés |Jelzőpont|
|---|---|
|főcím |főcím|
|tart |tartalom lábléc|
|kieg |kiegészítő|
|űrlap |űrlap|
|fő |fő|
|nav |navigáció|
|kers |keresés|
|tlt |terület|

### Braille bevitel {#toc51}

Rövidírással és teljes írással is bevihet szöveget a braille billentyűzet segítségével, az NVDA mindkét változatot támogatja.
A megfelelő braille fordítótábla kiválasztásához használja a [Beviteli tábla](#BrailleInputTable) kombinált listamezőt a Braille beállítások párbeszédablakon.

Ha teljes írással visz be szöveget, az már a bevitellel párhuzamosan beillesztésre kerül. A bevitt braille karaktereket az NVDA a beállított fordítótábla segítségével azonnal átalakítja szöveggé.
Rövidírásos bevitel esetén a szöveg csak akkor kerül beillesztésre, ha szóközt vagy entert üt a szó végén.
Vegye figyelembe, hogy a fordítás csak az éppen bevitt braille szóval foglalkozik, a billentyűzeten korábban bevitt karakterek nem használhatók fel újra.
Pl. ha egymás után két ugyanazzal a braille-karakterrel kezdődő szót akar bevinni, akkor hiába lép vissza a backspace-szel az első karakterhez, mindenképpen be kell vinnie az új szót az elejétől.

<!-- KC:beginInclude -->
7. pont: törli az utoljára bevitt braille cellát vagy karaktert.
8. pont: lefordítja a braille bevitelt és lenyomja az entert.
7. + 8. pont: lefordítja a braille bevitelt a szóköz vagy az enter leütése nélkül.
<!-- KC:endInclude -->

## Tartalom felismerése {#toc52}

Ha a fejlesztők nem adnak elegendő információt a képernyőolvasók felhasználóinak ahhoz, hogy értelmezni tudjanak egy adott tartalmat, különböző eszközök állnak rendelkezésre egy kép tartalmának felismerésére.
Az NVDA támogatja a Windows 10 beépített optikai karakterfelismerés (OCR) funkcióját, használatával képes felismerni a képek szöveges tartalmát.
További tartalom-felismerők találhatók az NVDA kiegészítői közt.

Amennyiben tartalom-felismerő parancsot használ az NVDA megkísérli felismerni a navigátor kurzornál található tartalmat #ObjectNavigation].
Alapértelmezés szerint a navigátor kurzor a rendszerkurzort vagy a böngészőmód kurzorát követi, így a megszokott navigációs parancsokkal léphet a felismerni kívánt tartalomra.
Pl. ha a böngészőmódban egy ábrára navigál, a felismerési parancs az ábra tartalmát kísérli meg értelmezni.
Az elemnavigációt is használhatja, pl. ha egy alkalmazás ablakában akar tartalmat felismertetni.

Ha a felismerés elkészült, akkor a böngészőmódban megszokott navigációs parancsokkal megtekintheti az eredményt.
Enter vagy szóköz: Aktiválja a kurzornál lévő szöveget, ha lehetséges.
Esc: Bezárja a felismerés eredményét.

### Windows 10 OCR {#Win10Ocr}

A Windows 10 tartalmaz OCR-t számtalan nyelvhez.
Az NVDA ezt tudja használni képek és nem akadálymentes alkalmazások szöveges tartalmának felismerésére.

A felismeréshez használt nyelvet beállíthatja a [Windows 10 OCR](#Win10OcrSettings) beállítások párbeszédablakon.
További nyelveket adhat hozzá, ha a gépházban kiválasztja az idő és nyelv menüben a régió és nyelv opciót, és ott megnyomja az Új nyelv hozzáadása gombot.

<!-- KC:beginInclude -->
A navigátor kurzornál található elem tartalmának felismeréséhez Windows 10 OCR segítségével használja az NVDA+r billentyűparancsot.
<!-- KC:endInclude -->

## Alkalmazásfüggő NVDA billentyűparancsok {#toc54}

Az NVDA néhány alkalmazásban saját billentyűparanccsal rendelkezik, melyek megkönnyítik a szoftverek akadálymentes használatát.

### Microsoft Word {#toc55}
#### Automatikus sor- és oszlopfejléc bemondás {#toc56}

Az NVDA képes automatikusan bemondani a megfelelő sor- és oszlopfejléceket miközben a táblázatokban navigál a Microsoft Wordben.
Ehhez először is A táblázat fejléceinek bemondása opciónak bekapcsolt állapotban kell lennie az NVDA Dokumentumformázás párbeszédablakán.
Másodszor az NVDA-nak tudnia kell, hogy az adott táblázatban mely sorok és oszlopok tartalmazzák a fejléceket.
A fejléceket tartalmazó sor vagy oszlop első celláján állva alkalmazhatók az alábbi parancsok:
<!-- KC:beginInclude -->

| Funkció |Billentyűparancs |Leírás|
|---|---|---|
|Oszlopfejlécek beállítása |NVDA+shift+c |Egyszeri lenyomás után az NVDA ezt a cellát tekinti az oszlopfejléceket tartalmazó sor első cellájának. Ezeket az oszlopfejléceket fogja automatikusan bemondani e sor alatt az oszlopok közti navigáció során. Kétszeri lenyomása törli a beállítást.|
|Sorfejlécek beállítása |NVDA+shift+r |Egyszeri lenyomás után az NVDA ezt a cellát tekinti a sorfejléceket tartalmazó oszlop első cellájának. Ezeket a sorfejléceket fogja automatikusan bemondani ezen oszloptól jobbra található  sorok közti navigáció során. Kétszeri lenyomása törli a beállítást.|

<!-- KC:endInclude -->
Ezek a beállítások könyvjelzőként mentésre kerülnek a dokumentumban, és kompatibilisek a többi képernyőolvasóval, így a Jaws-zal is.
Ez azt jelenti, hogy az így beállított sor- és oszlopfejlécek más képernyőolvasók felhasználói számára is használhatók lesznek, bármikor, amikor a későbbiekben megnyitják a dokumentumot.

#### Böngészőmód a Microsoft Wordben {#toc57}

A Microsoft Word is használható böngészőmódban, így elérhetővé válnak az olyan funkciók, mint a gyorsnavigáció, vagy az Elemlista.
<!-- KC:beginInclude -->
A böngészőmód be- és kikapcsolásához használja az NVDA+szóköz billentyűparancsot.
<!-- KC:endInclude -->
A böngészőmódról és a gyorsnavigációról bővebb információkat talál a [Böngészőmódról szóló fejezetben](#BrowseMode).

##### Az Elemlista {#toc58}

<!-- KC:beginInclude -->
Böngészőmódban  a Microsoft Wordben elérhető az Elemlista  az NVDA+f7 billentyűparancs használatával.
<!-- KC:endInclude -->
Az Elemlistában listázva vannak a címsorok, hivatkozások, hibák (jelenleg csak a helyesírási hibák), és a mellékszövegek (megjegyzések és szerkesztői változások).

#### Megjegyzések bemondása {#toc59}

<!-- KC:beginInclude -->
A kurzor aktuális pozíciójában elérhető megjegyzések bemondásához használja az NVDA+alt+c billentyűparancsot.
<!-- KC:endInclude -->
A dokumentumban található összes megjegyzés és szerkesztői változás elérhető az Elemlistából, amennyiben a mellékszövegeket választja a típusok közül.

### Microsoft Excel {#toc60}
#### Automatikus sor- és oszlopfejléc bemondás {#toc61}

Az NVDA képes automatikusan bemondani a megfelelő sor- és oszlopfejléceket miközben munkalapokon navigál a Microsoft Excelben.
Ehhez először is A táblázat fejléceinek bemondása opciónak bekapcsolt állapotban kell lennie az NVDA Dokumentumformázás párbeszédablakán.
Másodszor az NVDA-nak tudnia kell, hogy az adott táblázatban mely sorok és oszlopok tartalmazzák a fejléceket.
A fejléceket tartalmazó sor vagy oszlop első celláján állva alkalmazhatók az alábbi parancsok:
<!-- KC:beginInclude -->

| Funkció |Billentyűparancs |Leírás|
|---|---|---|
|Oszlopfejlécek beállítása |NVDA+shift+c |Egyszeri lenyomás után az NVDA ezt a cellát tekinti az oszlopfejléceket tartalmazó sor első cellájának. Ezeket az oszlopfejléceket fogja automatikusan bemondani e sor alatt az oszlopok közti navigáció során. Kétszeri lenyomása törli a beállítást.|
|Sorfejlécek beállítása |NVDA+shift+r |Egyszeri lenyomás után az NVDA ezt a cellát tekinti a sorfejléceket tartalmazó oszlop első cellájának. Ezeket a sorfejléceket fogja automatikusan bemondani ezen oszloptól jobbra található  sorok közti navigáció során. Kétszeri lenyomása törli a beállítást.|

<!-- KC:endInclude -->
Ezek a beállítások definiált névtartományokként mentésre kerülnek a munkafüzetben, és kompatibilisek a többi képernyőolvasóval, így a Jaws-zal is.
Ez azt jelenti, hogy az így beállított sor- és oszlopfejlécek más képernyőolvasók felhasználói számára is használhatók lesznek, bármikor, amikor a későbbiekben megnyitják a munkafüzetet.

#### Az Elemlista {#toc62}

Böngészőmódban a Microsoft Excelben is elérhetővé válik egy elemlista, ahol különböző típusú információk listázhatók és kezelhetők.
<!-- KC:beginInclude -->
Az elemlista megnyitásához használja az NVDA+f7 billentyűparancsot.
<!-- KC:endInclude -->
Az alábbi típusú elemek érhetőek el az elemlistából:

* Diagram: Kilistázza az aktív munkalap összes diagramját.
A kiválasztott diagram elemei közt az enter billentyű lenyomása, vagy az Ugrás gomb aktiválása után lehet navigálni a nyílbillentyűk segítségével.
* Megjegyzés: Kilistázza a munkalap összes megjegyzéssel ellátott celláját.
A cellák címe a megjegyzéssel együtt szerepel a listában.
Az Enter billentyű lenyomásával, vagy az Ugrás gomb aktiválásával lehet a kiválasztott cellára navigálni.
* Képlet: Kilistázza a munkalap összes képletet tartalmazó celláját.
A cellák címe a képlettel együtt szerepel a listában.
Az enter billentyű lenyomásával, vagy az Ugrás gomb aktiválásával lehet a kiválasztott cellára navigálni.
* Munkalap: Kilistázza a munkafüzet összes munkalapját.
Egy kiválasztott munkalapot az F2 billentyű lenyomása után át lehet nevezni.
Az enter billentyű lenyomásával, vagy az Ugrás gomb aktiválásával lehet a kiválasztott munkalapra navigálni.
* Űrlapmezők: Kilistázza az összes űrlapmezőt az aktív munkalapon.
Az elemlistában elérhető az űrlapmezőkhöz tartozó alternatív szöveg, ill. azon cellák koordinátái, melyek az adott űrlapmezőt tartalmazzák.
A kijelölt űrlapmezőre navigáláshoz nyomja meg az entert, vagy az ugrás gombot.

#### Megjegyzések bemondása {#toc63}

<!-- KC:beginInclude -->
A fókuszban lévő cellához tartozó megjegyzések meghallgatásához használja a az NVDA+alt+c billentyűparancsot.
<!-- KC:endInclude -->
A munkafüzethez tartozó összes megjegyzés elérhető az elemlistából.

#### Zárolt cellák olvasása {#toc64}

Ha egy munkafüzet védett, akkor nem lehet a zárolt, tehát nem szerkeszthető celláira navigálni.
<!-- KC:beginInclude -->
A zárolt cellák eléréséhez böngészőmódra kell váltani az NVDA+szóköz billentyűparanccsal, akkor már az Excel szokásos navigációs parancsaival is felolvastathatók.
<!-- KC:endInclude -->

#### Űrlapmezők {#toc65}

Az Excel munkalapok tartalmazhatnak űrlapmezőket.
Egy űrlapmezőre navigálni böngészőmódban az Elemlista (NVDA+F7), vagy az egykarakteres gyorsnavigáció (F, és Shift+F) segítségével lehet. Az űrlapmező kezeléséhez, a vezérlőelem típusától függően, használja az enter vagy a szóköz billentyűt, vagy váltson fókuszmódra (NVDA+szóköz).
A böngészőmódról, és az egykarakteres gyorsnavigációról további részleteket talál a [Böngészőmód](#BrowseMode) című fejezetben.

### Microsoft PowerPoint {#toc66}

<!-- KC:beginInclude -->

| Funkció |Billentyűparancs |Leírás|
|---|---|---|
|Az előadó jegyzeteire váltás |control+shift+s |Diavetítés közben ez a parancs vált egy adott diához tartozó előadói jegyzetek bemondása, és a dia tartalmának bemondása közt. Ez a parancs csak az NVDA által bemondott információkra van hatással, nem befolyásolja a képernyőn megjelenő tartalmat.|

<!-- KC:endInclude -->

### Skype {#toc67}

<!-- KC:beginInclude -->
Egy beszélgetés ablakában:

| Funkció |Billentyűparancs |Leírás|
|---|---|---|
|Üzenetek áttekintése |NVDA+kontrol+1-0 |Bemondja az utolsó 10 üzenetet annak megfelelően hogy mely szám került lenyomásra. Így pl. ha az NVDA+kontrol+2 billentyűparancsot nyomta le, az NVDA felolvassa az utolsó előtti üzenetet és az áttekintő kurzort oda helyezi.|

<!-- KC:endInclude -->

### Foobar2000 {#toc68}

<!-- KC:beginInclude -->

| Funkció |Billentyűparancs |Leírás|
|---|---|---|
|A hátralévő idő bemondása |control+shift+r |Bemondja a hátralévő időt az éppen lejátszandó fájlból.|

<!-- KC:endInclude -->
Megjegyzés: A hátralévő idő bemondása csak akkor lehetséges, ha a Foobar alapértelmezett állapotsor formázási beállítása van használatban.

### Miranda IM {#toc69}

<!-- KC:beginInclude -->

| Funkció |Billentyűparancs |Leírás|
|---|---|---|
|Aktuális üzenet bemondása |NVDA+control+1-3 |Bemondja a számmal meghatározott üzenetet, így pl. az NVDA+control+2 billentyűparancs megnyomására az utolsó előtti üzenet hangzik el.|

<!-- KC:endInclude -->

### Poedit {#toc70}

<!-- KC:beginInclude -->

| Funkció |Billentyűparancs |Leírás|
|---|---|---|
|A megjegyzés ablak felolvasása |control+shift+c |Felolvassa a megjegyzés ablak tartalmát.|
|A megjegyzések fordítóknak felolvasása |control+shift+a |Felolvassa a fordítóknak szánt megjegyzéseket.|

<!-- KC:endInclude -->

### Kindle for PC {#toc71}

Az NVDA támogatja a navigációt és az olvasást az Amazon Kindle for PC e-book kezelő szoftverében.
Ez kizárólag a képernyőolvasókra optimalizált Kindle könyvek esetében működik. Ezt az információt a könyvek részletes adatai közt lehet megtalálni.

A könyvek olvasása böngészőmódban történik.
Az NVDA automatikusan átvált, amikor megnyit egy könyvet, vagy ránavigál a könyv területre.
A lapozás automatikusan történik amikor szükséges. Akkor is, ha olvasás közben navigál, és akkor is, amikor a folyamatos felolvasás használatával olvas.
<!-- KC:beginInclude -->
A pageDown billentyűvel a következő oldalra léphet, míg a pageUp billentyűvel vissza az előzőre.
<!-- KC:endInclude -->

Az egykarakteres navigáció támogatott a hivatkozások és ábrák esetében, de kizárólag az aktuális oldalon működik.
A hivatkozások közti navigációs parancsok segítségével lehet a lábjegyzeteket elérni.

#### Szöveg kijelölése {#toc72}

A Kindle használata közben bizonyos műveleteket végezhet a kijelölt szövegeken, ilyen pl. szótári definíciók lekérdezése, jegyzet hozzáadása, kiemelés, szöveg másolása a vágólapra, vagy keresés a weben.
Ehhez először a megszokott kijelölési parancsokkal, (pl. shift+nyílbillentyűk) jelölje ki a kívánt szöveget.
<!-- KC:beginInclude -->
A kijelölt szövegen hívja elő a helyi menüt a lehetőségek megjelenítéséhez. Ehhez használja a Helyi menü gombot a billentyűzeten, vagy a shift+F10 billentyűparancsot.
<!-- KC:endInclude -->
Ha nincs szöveg kijelölve, akkor a kurzornál lévő szóhoz kapcsolódó lehetőségek jelennek meg.

#### Személyes jegyzetek {#toc73}

Egy szóhoz, vagy szövegrészlethez jegyzeteket adhat.
Ehhez először jelölje ki a kívánt szövegrészt, és hívja elő a helyi menüt a fent leírrt módon.
Majd válassza az Add Note parancsot a lehetőségek közül.

Böngészőmódú olvasás közben az NVDA ezeket a jegyzeteket megjegyzésként jelzi és kezeli.

Jegyzet megtekintése vagy törlése:

1. Mozgassa a kurzort a jegyzetet tartalmazó szövegrészhez.
1. Hívja elő a helyi menüt.
1. Válassza az Edit Note parancsot a lehetőségek közül.

## Az NVDA beállításai {#ConfiguringNVDA}

A legtöbb beállítás az NVDA beállítások többlapos párbeszédpanelén található meg.
[NVDA beállítások párbeszédpanel](#NVDASettings).

Minden párbeszédpanelen az ok gomb megnyomásával menthetők el az elvégzett beállítások.
 Bármely változtatás visszavonásához nyomjuk meg a mégsem gombot vagy az escape billentyűt.
Bizonyos párbeszédpaneleken az alkalmaz gomb megnyomásával azonnal érvényesíthetők a beállítások anélkül, hogy a párbeszédpanelt bezárnánk.
Egyes beállítások gyorsgombokkal is megváltoztathatók, ezeket a program az érintett beállítási területeken (párbeszédpaneleken) feltünteti, ha ezek alkalmazhatók, lásd alább.

### NVDA beállítások {#NVDASettings}

<!-- KC:settingsSection: || Funkció | Asztali billentyűparancs | Laptop billentyűparancs | Leírás | -->
Az NVDA-beállítások párbeszédpanel számos megváltoztatható opciót tartalmaz.
Ez a párbeszédpanel megjelenít egy listát, melyből többféle beállítási kategória közül választhatunk.
Ha kiválasztunk egy kategóriát, ezen a párbeszédpanelen a kategóriának megfelelő beállítások jelennek meg.
Ezek a beállítások az alkalmaz gombbal fogadhatók el úgy, hogy a párbeszédpanel nyitva marad.
Ha szeretnénka  beállításokat elmenteni és bezárni az NVDA beállításainak párbeszédpanelét, nyomjuk meg az oké gombot.
Több beállítási kategóriának saját gyorsgombja van.
Ha megnyomjuk, a gyorsgomb az NVDA beálításai párbeszédpanelt az adott beállítási kategóriával nyitja meg.
Alapértelmezésben nem minden kategória érhető el gyorsgombbal.
Ha olyan beállítási kategóriát szeretnénk elérni, amelyhez nincs rendelve gyorsgomb, használjuk a [beviteli parancsok párbeszédpanelt](#InputGestures) egy egyéni billentyű- vagy érintőparancs hozzáadásához az adott kategória eléréséhez.
Az NVDA beállításai párbeszédpanelen a beállítási kategóriák vastagon vannak jelölve.

#### Általános (NVDA+control+g) {#GeneralSettings}

Az általános beállításokat az NVDA beállítások/Általános alkategóriában érheti el.
A kategória a következő beállításokat tartalmazza:

##### Nyelv {#GeneralSettingsLanguage}

Ebben a kombinált listamezőben kiválaszthatja az NVDA felhasználói felület és az üzenetek nyelvét. A lista sok nyelvet tartalmaz, ám az alap beállítás az "Alapértelmezett nyelv". E beállítás esetén az NVDA a windows területi és nyelvi beállításaihoz igazítja saját beállításait (Ld. vezérlőpult, területi és nyelvi beállítások).

Fontos: a nyelv megváltoztatása csak az NVDA újbóli elindításával következik be.
 AzNVDA rákérdez, hogy szeretné-e ezt a műveletet. Nyomja meg az igen gombot, és az NVDA újraindul.

##### A beállítások automatikus elmentése kilépéskor {#GeneralSettingsSaveConfig}

Ez egy jelölőnégyzet, amivel vezérelheti az NVDA-t, hogy elmentse-e a beállításokat kilépéskor. Alapértelmezetten ez be van kapcsolva.

##### Lehetőségek mutatása kilépéskor {#GeneralSettingsShowExitOptions}

Ez a beállítás egy jelölőnégyzet, mely lehetővé teszi, hogy az NVDA-ból való kilépéskor megjelenjen-e egy párbeszédpanel az NVDA-ból való kilépéskori lehetőségek felkínálásával.
Ha be van jelölve, egy párbeszédpanel jelenik meg, ahol eldönthető, hogy kilépünk-e az NVDA-ból, teljes újraindítást szeretnénk, bővítmények nélkül indítjuk újra, vagy telepítjük a függőben lévő frissítéseket újranindítás előtt.
Ha nincs bejelölve, az NVDA azonnal kilép.

##### Hangjelzés lejátszása az NVDA indításakor és kilépéskor {#GeneralSettingsPlaySounds}

A jelölőnégyzet bejelölésekor az NVDA egy hangjelzést játszik le a program elindításakor és bezárulásakor (ez az alapértelmezett).

##### Naplózási szint {#GeneralSettingsLogLevel}

Ez egy kombinált listamező, ahol kiválaszthatja, hogy milyen szinten engedélyezze a futás közbeni naplózást. Általában a felhasználóknak nem szükséges ezt beállítani, de ha egy hibáról szóló állapotjelentést szeretne elküldeni a fejlesztőknek, netán az NVDA fejlesztője vagy tesztelője, akkor ezzel nagy mértékben segítheti a fejlesztési, tesztelési munkát.
  Az elérhető naplózási szintek a következők:

* Tiltva: Egy rövid kezdőüzenet kivételével az NVDA nem naplóz semmit, amíg fut.
* Info: Az NVDA alapüzeneteket naplóz, mint például: az indítási üzeneteit, továbbá olyanokat, amelyek a fejlesztők számára hasznosak.
* Figyelmeztetés: olyan figyelmeztető üzenetek, melyeket csak komolyabb hiba esetén naplóz a program.
* Be- és kimenet: a bilentyűzetről és a braille kijelzőkről érkező bemenetet, továbbá a braille kijelzőkre és a beszédszintetizátorra érkező kimenetet naplózza. Ha aggódik a magánszférája megsértése miatt, ne állítsa be ezt a naplózási szintet.
* Hibakeresés: Az info, figyelmeztetés és be- és kimenet naplózási szinteken túl további hibakeresési üzeneteket is naplóz a program. Mint a be- és kimeneti szintnél írtuk, ha meg kívánja védeni magánszféráját, ne állítsa be a naplózást erre a szintre.
 -

==== Az NVDA automatikus elindítása a Windows bejelentkezése után ====[GeneralSettingsStartAfterLogOn]

Ez a beállítás csak az NVDA telepített verziójában érhető el. Ha bejelöli ezt a jelölőnégyzetet, az NVDA a Windows betöltése után magától elindul.

==== Az NVDA elindítása a Windows bejelentkező képernyő használatakor (rendszergazdai jog szükséges)====[GeneralSettingsStartOnLogOnScreen]

A jelölőnégyzet bejelölése után az NVDA minden rendszer indításkor a bejelentkező ablakban beszédtámogatást nyújt (a beállításhoz rendszergazdai jog szükséges)

==== Az aktuális beállítások használata a bejelentkező és egyéb biztonsági képernyőkön (rendszergazdaijog szükséges)====[GeneralSettingsCopySettings]

A gomb megnyomásának hatására az aktuális beállításokat fogja használni az NVDA a bejelentkező és egyéb biztonsági képernyőkön (hangkarakter, beszédtempó, stb.). Győződjön meg arról, hogy elmentette-e az aktuális beállításokat (control+NVDA+c, vagy a beállítások elmentése az NVDA menüjében megtörtént-e), ugyanis a legutolsó mentett beállítások másolódnak át.
Ez a beállítás csak a telepített verzióban érhető el.

==== Az NVDA  frissítéseinek automatikus keresése ====[GeneralSettingsCheckForUpdates]
Ha bekapcsoljuk, az NVDA automatikusan keres frissítést, és ha van, figyelmeztet. Igény szerint kereshetünk frissítést az NVDA menü súgó almenüjének frissítések keresése menüparancsával.
Akár automatikusan, akár kézzel kerestetünk frissítést a képernyőolvasóhoz, az NVDA-nak bizonyos információkat el kell küldenie a frissítési szervernek, hogy a szerver a megfelelő frissítést küldje meg a rendszerünkhöz.
A következő információkat a szoftver mindig elküldi:
* A jelenlegi NVDA verziószámát
* Az operációs rendszer verzióját
* azt, hogy az operációs rendszer 64 vagy 32 bites-e

##### Engedély statisztikai adatok küldésére az NVDA projekt számára {#GeneralSettingsGatherUsageStats}

Ha engedélyezzük, az NV Access a frissítések ellenőrzésekor felhasználja ezeket az információkat, hogy számon tartsa az NVDA felhasználóinak bizonyos adatait: beleértve a felhasználók bizonyos demográfiai adatait, mint az ország, ahol a szoftvert használják, a használt operációs rendszer verzióját.
Vegyük figyelembe, hogy bár az IP címünket használja a szoftver az ország azonosítására a frissítési eljárás során, az IP címeket a rendszer soha nem tárolja.
Bár az előbb felsorolt  információk feltétlenül szükségesek a frissítések kereséséhez, a rendszer a következő információkat is begyűjti:

* az NVDA felhasználói felületének nyelve
* annak meghatározása, hogy a használt NVDA-példány hordozható vagy telepítve van-e
* A használt beszédszintetizátor neve (beleértve azt a bővítményt is, amelyből a driver származik)
* a használatban lévő braille kijelző nevét (beleérttve azt a bővítményt is, amelyből az eszközillesztő-program származik)
* az aktuálisan használt braille kimeneti táblát, ha braille kijelző van használatban

Ez az információ nagy mértékben segíti az NV Accesst, hogy az NVDA jövőbeni fejlesztésekor meghatározza, milyen fejlesztési feladatok a fontosak.

##### Figyelmeztetés indításkor a függő frissítésekre {#GeneralSettingsNotifyPendingUpdates}

Ha be van kapcsolva, az NVDA az indításakor figyelmeztet, hogy frissítés van függőben, lehetővé téve, hogy telepítsük.
A függőben lévő frissítést az NVDA kilépési párbeszédpanelén is telepíthetjük (ha a kilépési párbeszédpanel megjelenítését bekapcsoljuk), elvégezhetjük az NVDA menüjéből, valamint a súgó menüből is, ha ott új frissítés keresést kezdeményezünk.

#### Beszédbeállítások (NVDA+control+v) {#SpeechSettings}

Az NVDA beállításai párbeszédpanel beszéd kategóriája olyan beállítási lehetőségeket tartalmaz, mint például a beszédszintetizátor vagy a beszédszintetizátor hangja jellegzetességeinek megváltoztatása.
A beszédparaméterek egy gyorsabb és bárhonnan történő beállításához lásd a beszédbeállítási kör [Szintetizátorbeállítási kör](#SynthSettingsRing) fejezetet.
A beszédbeállítások kategória a következő lehetőségeket tartalmazza:

##### Beszédszintetizátor megváltoztatása {#SpeechSettingsChange}

Az első opció a beszédbeállítások kategóriában a módosítás... gomb. Ez a gomb a [Beszédszintetizátor kiválasztása](#SelectSynthesizer) párbeszédpanelt aktiválja, melyen kiválaszthatjuk a használni kívánt beszédszintetizátort és kimeneti eszközt.
Ez a párbeszédpanel az NVDA beállításai párbeszédpanel felett nyílik meg.
A beszédszintetizátor-beállítások párbeszédpanelen lévő beállítások elmentését vagy elvetését követően az NVDA beállításai párbeszédpanelhez térünk vissza.

##### Hangkarakter {#SpeechSettingsVoice}

A párbeszédpanel következő eleme egy kombinált listamező, mely felsorolja az aktuálisan telepített beszédszintetizátor hangkaraktereit. A nyílbillentyűkkel meghallgathatja az egyes lehetőségeket. A fel és bal nyíl billentyűkkel felfelé, a jobbra és le nyilakkal lefelé mozoghat a listában.

##### Változat {#SpeechSettingsVariant}

Ha az ESpeak NG beszédszintetizátort használja, mely alapértelmezésként megtalálható az NVDA-ban, ebben a kombinált listamezőben lehetősége van kiválasztani, milyen változatot kíván használni. Az egyes variációk eltérő beszédparamétereket jelentenek, pl férfi vagy női hang.

##### Tempó {#SpeechSettingsRate}

A felolvasás sebességének beállítását lehet itt elvégezni. A csúszka értéke 0-tól 100-ig állítható, 0 a leglassabb, 100 a leggyorsabb.

##### Sebességfokozás {#toc89}

Ha bejelöli ezt a jelölőnégyzetet, az ESpeak NG a megszokottnál gyorsabb beszédre képes.

##### Magasság {#SpeechSettingsPitch}

Ez a beállítás lehetővé teszi a beszédhang hangmagasságának állítását. A csúszkát 0-tól 100-ig lehet állítani, 0 a legmélyebb, 100 a legmagasabb hang.

##### Hangerő {#SpeechSettingsVolume}

A csúszkával a hangerő állítható 0 és 100 között. 0 a leghalkabb, 100 a leghangosabb hangerőt jelenti.

##### Intonáció {#SpeechSettingsInflection}

Ezzel a csúszkával beállítható a beszédszintetizátor hangsúlyozása (a hangmagasság növelése és csökkentése). (Az egyetlen beszédszintetizátor amely használja ezt a beállítást jelenleg az ESpeak NG). 0 esetén teljesen monoton, 100 esetén a legnagyobb mértékben hangsúlyoz.

##### Automatikus nyelvváltás {#SpeechSettingsLanguageSwitching}

Ezzel a jelölőnégyzettel szabályozzuk, hogy az NVDA a beszédszintetizátor nyelvét automatikusan átállítsa-e az olvasandó szöveg nyelvére. Ez a jelölőnégyzet alapértelmezetten be van jelölve. Jelenleg csak az Espeak beszédszintetizátor képes az automatikus nyelvváltásra.

##### Automatikus dialektusváltás {#SpeechSettingsDialectSwitching}

Ezzel a jelölőnégyzettel szabályozzuk, hogy az NVDA automatikusan állítsa-e be a nyelvváltozatot, akárcsak a nyelvet. Például, ha az NVDA amerikai egyesültállamokbeli angol nyelvváltozatban olvas, ám a dokumentum a szöveg nyelvét egyesült királyságbeli angolként határozza meg, a beszédszintetizátor átállítja a nyelvváltozatot. Ez a jelölőnégyzet alapértelmezésben nincs bejelölve.

<!-- KC:setting -->

##### Írásjelszint {#SpeechSettingsSymbolLevel}

Billentyűparancs: NVDA+p

Az NVDA minden írásjelszintnek megfelelően képes az írásjeleket különálló szavanként kezelni. A szintek között a billentyűparancs többszöri lenyomásával tud váltani.

##### Karakterek és írásjelek feldolgozása az aktív hangkarakter nyelvén {#SpeechSettingsTrust}

Alapértelmezésben ez a jelölőnégyzet az NVDA-t arra utasítja, hogy a megadott hangkarakter szabályai szerint dolgozza fel az írásjeleket és a karaktereket. Ha azt észleljük, hogy az NVDA egy beszédszintetizátor vagy hangkarakter kiválasztásakor rosszul olvassa a központozást, a jelölőnégyzet kikapcsolásával az NVDA-t arra kényszeríthetjük, hogy használja az általános nyelvi beállításait.

##### Unicode CLDR használata karakterek és szimbólumok feldolgozásakor {#SpeechSettingsCLDR}

Ha ez a jelölőnégyzet be van jelölve, az NVDA a karakterek és szimbólumok kimondásakor felhasználja a további kiejtési szótárakat.
Ezek a szótárak tartalmazzák a karakterek és szimbólumok kiejtését, különösen a hangulatjeleket (emodzsi), melyeket a [Unicode Konzorcium](https://www.unicode.org/consortium/) tesz közzé az [általános helyi adatkönyvtáruk](http://cldr.unicode.org/) részeként .
Ha azt szeretné, hogy az NVDA ezeknek az adatoknak a felhasználásával mondja ki az emodzsi karakterek (hangulatjelek) leírásait, engedélyezze ezt a beállítást.
Ha azonban olyan beszédszintetizátort használ, mely a hangulatjelek kiejtését beépítve támogatja, inkább kapcsolja ki ezt a beállítást.
Figyelem: a sajátkezűleg hozzáadott vagy átszerkesztett karakterleírások a felhasználói beállítások közé lesznek elmentve.
Így ha egy hangulatjel leírását megváltoztatja, ennek a hangulatjelnek az egyéni leírása fog elhangozni függetlenül attól, hogy ezt az opciót bekapcsolta-e vagy sem.
Ezeket a hangulatjel-leírásokat az NVDA [ írásjelkiejtés párbeszédpanelén](#SymbolPronunciation) adhatja hozzá, szerkesztheti, törölheti.
Ha bárhonnan szeretné engedélyezni az Unicode Konzorcium adatok felhasználását, kérjük, rendeljen hozzá egyéni billentyűparancsot a [beviteli parancsok párbeszédpanelen](#InputGestures).

##### Hangmagasság változtatása nagybetűknél százalékban {#toc98}

Ha ez a jelölőnégyzet be van jelölve, az NVDA megemeli a hangmagasságot a nagybetűknél.

##### Nagybetűk szóbeli jelzése {#SpeechSettingsSayCapBefore}

Ha a jelölőnégyzet be van jelölve, az NVDA a "nagy" szót kimondja minden nagybetű előtt, nyilakkal történő kiválasztás, kimondás vagy begépelés esetén. Általában az NVDA megemeli a hangmagasságot nagybetűhöz érve, de néhány beszédszintetizátor nem támogatja ezt a funkciót, ebben az esetben hasznos lehet ez a beállítás.

##### Nagybetűk jelzése hangjelzéssel {#SpeechSettingsBeepForCaps}

Ha a jelölőnégyzet be van jelölve, egy rövid csipogó hang hallható a nagybetűk előtt. A "Nagybetűk szóbeli jelzése" jelölőnégyzethez hasonlóan ez a beállítás hasznos olyan beszédszintetizátorok használata esetén, melyek nem képesek a hangmagasságot megemelni a nagybetűknél.

##### Betűzés használata, ha támogatott {#toc101}

Az egykarakteres szavakat másképpen kell ejteni hangzó szóként és másképpen karakterként. (Pl. betűzéskor) vagy külön szóként. Például az angolban az "a"-t másképpen kell mondani, ha szó és másképpen, ha betű. Ezzel a jelölőnégyzettel szabályozható, hogy a beszédszintetizátor tegyen-e különbséget e két eset között, ha a beszédszintetizátor támogatja ezt a funkciót. A legtöbb szintetizátor támogatja ezt az opciót. Ez a jelölőnégyzet általában be van jelölve, azonban egyes Microsoft Speech API beszédszintetizátorok nem tartalmazzák megfelelően ezt a funkciót, és ha be van kapcsolva, furcsán viselkednek. Ha problémákat tapasztalunk egyes különálló karakterek kiejtésével, kapcsoljuk ki ezt a jelölőnégyzetet!

#### Beszédszintetizátor kiválasztása (NVDA+control+s) {#SelectSynthesizer}

A beszédszintetizátor választása párbeszédpanel, melyet a módosítás... gombot megnyomva érhetünk el az NVDA beállítások beszéd kategóriájában, lehetővé teszi, hogy kiválasszuk azt a beszédszintetizátort, amelyet az NVDA használjon a megszólaláshoz.
Amint kiválasztotta a kívánt beszédszintetizátort, nyomja meg az oké gombot, hogy az NVDA betöltse azt.
Ha a szintetizátor betöltésekor valamilyen hiba történik, az NVDA egy üzenettel figyelmeztet, és visszatér a korábban használt beszédszintetizátorhoz.

##### Beszédszintetizátor {#SelectSynthesizerSynthesizer}

Ez a beállítás lehetővé teszi, hogy meghatározzuk, hogy az NVDA melyik beszédszintetizátort  használja beszédkimenetként.

Az NVDA által támogatott beszédszintetizátorok listájához olvassa el a [Támogatott beszédszintetizátorok](#SupportedSpeechSynths) című fejezetet.
Egy speciális beállítás, a „nincs” minden esetben megjelenik. Ez lehetővé teszi, hogy az NVDA-t bármilyen beszédszintetizátor nélkül használjuk.
Ez a beállítás azoknak lehet megfelelő, akik az NVDA-t csak braille kijelzővel szeretnék használni, vagy látóknak, akik csak a beszédnézőt használják.

##### Kimeneti eszköz / beszédkimenet {#SelectSynthesizerOutputDevice}

Ezzel a beállítással választható ki, hogy az NVDA által használt beszédszintetizátor melyik hangeszközön szólaljon meg.

<!-- KC:setting -->

##### Hangerő-igazítás {#SelectSynthesizerDuckingMode}

Gyorsbillentyű: NVDA+shift+d

A Windows 8 és újabb Windows verziók alatt ezzel a beállítással szabályozható, hogy az NVDA lehalkítsa-e a többi alkalmazás hangerejét, míg az NVDA beszél vagy mindig, amikor az NVDA fut.

* Soha: Az NVDA sosem halkítja le más  alkalmazás hangját.
* Csak, amikor az NVDA használja a hangkimenetet: Az NVDA csak akkor halkítja le a többi alkalmazást, ha beszél vagy hangot játszik le. Ez a beálllítás nem minden beszédszintetizátorral használható.
* Mindig: Az NVDA mind addig lehalkítja a többi alkalmazást, amíg fut.

Ez a funkció csak akkor érhető el, ha az NVDA telepítve van, nem használható a hordozható, illetve az ideiglenes másolati példányokban (pl. telepítőből indítva).

#### Szintetizátor beállítási kör {#SynthSettingsRing}

Lehetősége van a beszéd párbeszédablak megnyitása nélkül is megváltoztatni a beszéd különböző paramétereit. Ehhez a következő billentyűparancsok állnak rendelkezésére:
<!-- KC:beginInclude -->

| Funkció |Asztali billentyűparancs |Laptop billentyűparancs |Leírás|
|---|---|---|---|
|Ugrás a következő szintetizátor beállításra |NVDA+control+jobbnyíl |NVDA+shift+control+jobbra nyíl |A következő beszéd beállításra ugrik. Ha elérte az utolsót, akkor az elsőre lép.|
|Ugrás az előző szintetizátor beállításra |NVDA+control+balnyíl |NVDA+shift+control+balra nyíl |Az előző beszéd beállításra ugrik. Ha elérte az utolsót, akkor az elsőre lép.|
|Az aktuális beállítás értékének növelése |NVDA+control+fel nyíl |NVDA+shift+control+felnyíl |A gomb megnyomására nő az aktuális beszéd beállítás (hangkarakter, intonáció, beszéd tempó, stb.) értéke.|
|Az aktuális beállítás értékének csökkentése |NVDA+control+le nyíl |NVDA+shift+control+lenyíl |A gomb megnyomására csökken az aktuális beszéd beállítás (hangkarakter, intonáció, beszéd tempó, stb.) értéke.|

<!-- KC:endInclude -->

#### Braille beállításai {#BrailleSettings}

Az NVDA beállítások párbeszédpanel braille kategóriája olyan beállításokat tartalmaz, amelyekkel a braille be- és kimenet jó néhány beállítása változtatható meg.
Ez a kategória a következő beállítási lehetőségeket tartalmazza:

##### Braille kijelző kiválasztása {#BrailleSettingsChange}

Az NVDA beállítások párbeszédpanel braille kategóriájában a módosítás... gomb megnyitja a [ braille kijelző kiválasztása](#SelectBrailleDisplay) párbeszédpanelt, melynek segítségével kiválaszthatjuk a használni kívánt (aktív) braille kijelzőt.
Ez a párbeszédpanel az NVDA beállításai ablak felett nyílik meg.
Akár elfogadjuk, akár elvetjük a braille kijelző kiválasztásának beálításait, az NVDA beállításai párbeszédpanelre térünk vissza.

##### Kimeneti tábla {#BrailleSettingsOutputTable}

A következő beálítás ezen a párbeszédpanelen a braille kimeneti tábla kombinált listamező.
Ebben a kombinált listamezőben a különböző nyelvek braile kimeneti tábláit találhatjuk meg, beleértve a normál és a különböző rövidítési szinteket.
A program a kiválasztott kimeneti táblát használja arra, hogy a szövegeket átalakítsa és braille-ban a braille kijelzőn megjelenítse.
A listában a nyíl billentyűk segítségével lehet kimeneti braile tábláról kimeneti braille táblára lépni.

##### Beviteli Tábla {#BrailleSettingsInputTable}

Az előző parancshoz hasonlóan, a következő parancs a braile beviteli tábla kombinált listamező.
A program a kiválasztott táblát használja arra, hogy a braille kijelző Perkins-stílusú billentyűzetén braille-ban bevitt információt szöveggé alakítsa át.
Az NVDA egyelőre csak a számítógépes braille beviteli módot támogatja, így a listában csak a nyolcpontos braile beviteli táblák jelennek meg.
a listában a nyíl billentyűkkel léphetünk bemeneti braille tábláról bemeneti braille táblára.

Vegyük figyelembe, hogy ez a beállítás csak akkor használható, ha a braille kijelzőnek van Perkins-stílusú braile billentyűzete, és a braille kijelző eszközillesztő programja támogatja ezt a funkciót.
Ha a braille kijelzőnek van bilentyűzete, de ez a  funkció nem érhető el, ezt a [támogatott Braille kijelzők](#SupportedBrailleDisplays) című szakaszban jelezzük.

##### A kurzornál lévő szó átalakítása számítógépes braille kóddá {#BrailleSettingsExpandToComputerBraille}

Ez a beállítás azt jelenti, hogy a kurzor alatt lévő karaktert mindenképp megjeleníti a kijelzőn, még akkoris, ha nincs a táblában hozzárendelve a braille kódja. (ilyenkor az ascii kódot írja ki).

##### Kurzor mutatása {#BrailleSettingsShowCursor}

Ezzel az opcióval a braille kurzort lehet ki- és bekapcsolni.
A rendszerkurzor és az áttekintő kurzor esetében működik, a kijelölésjelzővel viszont nem.

##### Villogó kurzor {#BrailleSettingsBlinkCursor}

Ez az opció lehetővé teszi a kurzor villogásának imitálását a braille kurzorral. Ez egy braille kijelzőn úgy néz ki, hogy a kurzor alakjának megfelelő pontkombináció kiemelkedik kitapintható állapotba, majd visszasűllyed a villogási sebességként beállított értéknek megfelelő ritmusban.
Ha a villogás ki van kapcsolva, akkor a braille kurzor folyamatosan a kitapintható pozícióban van.
A kijelölések jelzésére nincs kihatással ez az opció, az mindig a 7. és 8. pont villogás nélkül.

##### A kurzor villogási sebessége {#BrailleSettingsBlinkRate}

Ebben a mezőben megadhatja, hogy a kurzor hány ezred másodpercenként villogjon

##### A kurzor alakja {#BrailleSettingsCursorShapeForFocus}

Ebben a legördülő mezőben kiválaszthatja    a kurzor pont alakú jelzését a braille kijelzőn.
A  beállításnak nincs ráhatása a kijelölés jelzésére.

##### Az áttekintő kurzor alakja {#BrailleSettingsCursorShapeForReview}

Ezzel az opcióval beállíthatja a braille kurzor alakját olyankor,amikor a braille kurzor az áttekintő kurzort követi.
A kijelölések jelzésére nincs kihatással ez az opció, az mindig a 7. és 8. pont villogás nélkül.

##### Üzenet megjelenésének időtartama(másodperc) {#BrailleSettingsMessageTimeout}

Itt beállíthatja, hogy a felugró üzenetek hány másodpercig jelenjenek meg a kijelzőn.

##### Üzenetek megjelenítése időkorlát nélkül {#BrailleSettingsNoMessageTimeout}

Ez az opció lehetővé teszi, hogy az NVDA üzenetek ne tűnjenek el automatikusan a braille kijelzőről bizonyos idő után.

<!-- KC:setting -->

##### A kurzor követése {#BrailleTether}

Billentyűparancs: NVDA+control+t

Itt  beállítható, mi jelenjen meg a braille kijelzőn. A két beállítási lehetőség: KURZOR, és az áttekintő kurzor követése. A kurzor megjeleníti a kurzornál lévő elemeket, míg az áttekintő kurzor megjeleníti a képernyő tartalmát. A különböző beállítások között a Control+NVDA+T billentyűparancsal váltogathat.

##### Bekezdésenkénti olvasás {#BrailleSettingsReadByParagraph}

Ha ez az opció be van kapcsolva, akkor a braille megjelenítés bekezdésenként és nem soronként történik.
Ezzel egyetemben az előző/következő sorra ugrás navigációs parancsa is bekezdésenként fog lépkedni.
Ez azt jelenti, hogy nem kell minden sor végén görgetni a kijelzőt,, amennyiben egy sornál hosszabb szöveget is meg tud jeleníteni.
Gördülékenyebben olvashatók így nagy mennyiségű szövegek.
Ez az opció alapértelmezés szerint ki van kapcsolva.

##### Ne válassza el a szavakat, ha lehet {#BrailleSettingsWordWrap}

Ha ez a jelölőnégyzet be van jelölve, akkor az utolsó szó ha nem fér ki a kijelzőre, nem kerül megjelenítésre. A beállítás azt okozhatja hogy a kijelzőn sok cella üresen marad, így többet kell görgetni a megjelenítendő szöveg áttekintéséhez. Más programokban ez a beállítás sortörés néven érhető el.

Amennyiben a jelölőnégyzet nincs bejelölve, a lehető legtöbb cella kitöltésre kerül. Ha az utolsó szó nem fér ki, ennek vége levágásra kerül, a maradék csak a görgetés után jelenik meg.

##### Információk az aktív elemről {#BrailleSettingsFocusContextPresentation}

Ezzel az opcióval beállíthatja, hogy az NVDA mennyire részletes információkat jelenítsen meg a braille kijelzőn az aktív elemről.
Ezek az információk az egyes elemek hierarchiáját tükrözik.
Pl. ha az aktív elem egy listaelem, akkor ez az elem egy lista része.
A lista pedig egy párbeszédpanelen található, stb.

Az elemek hierarchiájáról a Közlekedés az elemek között című fejezetben talál részletesebb információkat.

Csak a változások:
Az NVDA megpróbál annyi információt megjeleníteni,amennyit a braille kijelzőn csak tud, de kizárólag olyan információkat jelenít meg, melyek az aktív elem változásakor megváltoztak.
A fenti példa alapján, ha egy elemre navigál, az NVDA megjeleníti azt az elemet a braille kijelzőn.
Amennyiben van elég üres cella a kijelzőn, az NVDA megjeleníti azt is, hogy adott elem típusa listaelem.
Ezután, ha lefelé navigál, tudhatja, hogy a lista elemein lépked.
Viszont a lista további elemeinél az NVDA csak magát az elemet jeleníti meg, azt az információt már nem, hogy adott elem típusa listaelem.
Ha ismét tudni akarja az adott elem hierarchikus elhelyezkedését, visszafelé kell görgetnie a braille kijelzőn.

A lehető legtöbb információ:
Az NVDA mindig megpróbálja a lehető legtöbb információt megjeleníteni a braille kijelzőn, akkor is, ha az aktív elem változásakor nem változik meg semmi.
Azzal együtt, hogy az NVDA a lehető legtöbb információt rendelkezésre bocsájtja, komoly hátrány, hogy az egyes elemek nem ugyanabban a cellában kezdődnek, így elég nehézkes hosszabb listákon navigálni, mert mindig keresni kell az aktív elem elejét.
Ez volt az alapértelmezett viselkedés az NVDA 2017.2 és korábbi verzióinál.

Csak visszagörgetéssel:
Ebben az esetben az NVDA nem ad semmiféle információt az aktív elem hierarchikus elhelyezkedéséről.
Csak magát az elemet jeleníti meg.
Amennyiben mégis kíváncsi az elem hierarchikus elhelyezkedésére, visszafelé kell görgetnie a braille kijelzőn.

Ha használat közben szeretné változtatni az aktív elemről kapott információk mennyiségét, rendeljen hozzá beviteli parancsot.

#### Braille kijelző kiválasztása (NVDA+control+a) {#SelectBrailleDisplay}

A braille kijelző kiválasztása párbeszédpanel, melyet a módosítás... gombbal nyithatunk meg az NVDA beállítások Braille kategóriájában, lehetővé teszi, hogy kiválasszuk, hogy az NVDA melyik braille kijelzőt használja braille kimenetként.
Ha kiválasztottuk a megfelelő braille kijelzőt, nyomjuk meg az ok gombot, és az NVDA betölti az adott braille kijelző  illesztőprogramját.
Ha a kijelző eszközillesztő-programjának betöltése közben hiba történik, az NVDA egy figyelmeztető üzenetet ír ki, és a korábbi braille kijelzőt használja, ha volt ilyen.

##### Braille kijelző {#SelectBrailleDisplayDisplay}

Ez a kombinált listamező attól függően tüntet fel különböző beállításokat, hogy milyen braille kijelző illesztőprogramok vannak telepítve a rendszerre.
Használjuk a nyíl billentyűket a beállítások váltogatásához.
Az automatikus beállítás lehetővé teszi az NVDA számára, hogy a háttérben automatikusan támogatott braille kijelzőt keressen.
Ha ez a beállítás az aktív, és akár usb-n, akár bluetooth-on keresztül csatlakoztatunk egy támogatott braille kijelzőt, az NVDA automatikusan kapcsolódik ehhez a kijelzőhöz.
A „nincs” azt jelenti, hogy nem használunk braille kijelzőt.
A támogatott braille kijelzőkkel kapcsolatban, és hogy ezek közül melyek támogatják a háttérben történő automatikus felismerést, kérjük, tekintse át a [Támogatott Braille kijelzők](#SupportedBrailleDisplays) című fejezetet további információkért

##### Port {#SelectBrailleDisplayPort}

Ha ez a beállítás elérhető, kiválaszthatjuk, hogy az NVDA és a támogatott braille kijelző mely porton, illetve milyen típusú kapcsolaton keresztül kommunikáljon.
Ez egy kombinált listamező, mely tartalmazza a választható beállításokat a kiválasztott braille kijelzőhöz.
Alapértelmezés szerint az NVDA automatikus portfelismerést végez, ami azt jelenti, hogy az NVDA automatikusan határozza meg, hogy a braille kijelzővel a kapcsolatot a rendszeren elérhető usb és bluetooth kapcsolatok felhasználásával automatikusan hozza létre.
Azonban bizonyos braille kijelzőknél kifejezetten meghatározhatjuk, milyen portot használjon az NVDA.
Az általános beállítás az „automatikus”, (melynek során  az NVDA az alapértelmezés szerinti automatikus portkiválasztási eljárást végzi el), további opció a „bluetooth” és az „usb”, valamint a hagyományos soros (legacy serial) kommunikációs port kiválasztása, ha a braille kijelző támogatja az ilyen típusú kommunikációt.
Ez a beállítás nem érhető el, ha a braille kijelző csak az automatikus portkiválasztást támogatja.
Előfordulhat, hogy át kell olvasnia az Ön braille kijelzőjére vonatkozó dokumentációt a [Támogatott Braille kijelzők](#SupportedBrailleDisplays) című fejezetben az adott braille kijelző által támogatott kommunikációvalés az elérhető portokkal kapcsolatban.

#### Vizuális {#VisionSettings}

Az NVDA beállításai párbeszédpanel vizuális kategóriája lehetővé teszi, hogy be- vagy kikapcsoljuk, illetve beállítsuk a [látást segítő beállításokat](#Vision).
Vegyük figyelembe, hogy az ebben a kategóriában szereplő beállításokat bővíthetjük az [NVDA bővítménykezelőjével](#AddonsManager).
Alapértelmezés szerint ez a beállítási kategória a következő opciókat tartalmazza:

##### Fókuszkiemelés {#VisionSettingsFocusHighlight}

A fókuszkiemelés elemcsoportban lévő jelölőnégyzetek az NVDA beépített  [Fókuszkiemelés](#VisionFocusHighlight) funkcióját szabályozzák.

* Fókuszkiemelés engedélyezése: ki- és bekapcsolja a fókuszkiemelést.
* Rendszerfókusz kiemelése: Azt szabályozza, hogy a [rendszerfókusz](#SystemFocus) ki legyen-e emelve.
* Navigációs elemek kiemelése: Szabályozza, hogy a  [navigációs elemek](#ObjectNavigation) ki legyenek-e emelve.
* A böngészőmód kurzorának kiemelése: Szabályozza, hogy a [böngészőmód kurzora](#BrowseMode) ki legyen-e emelve.

Vegyük figyelembe, hogy a fókuszkiemelés ki- és bekapcsolása a másik három jelölőnégyzetet is a fókuszkiemelés jelölőnégyzet állapota szerint állítja át.
ÍGy ha a „fókuszkiemelés” jelölőnégyzet nincs bejelölve, majd bejelöljük, az NVDA automatikusan bejelöli a másik három jelölőnégyzetet is.
Ha csak a fókuszkiemelést szeretnénk bekapcsolni, de a navigátor és a böngészőmód-kurzor fókuszkiemelését nem, akkor a „fókuszkiemelés” jelölőnégyzet félig bejelölve állapotba kerül.

##### Képernyőfüggöny {#VisionSettingsScreenCurtain}

Bekapcsolhatjuk a [képernyőfüggönyt](#VisionScreenCurtain) a „képernyő elfeketítése” jelölőnégyzettel (azonnal aktiválódik).
Az NVDA egy figyelmeztetést ír ki, hogy a bekapcsolást követően a képernyő elfeketedik. Mielőtt folytatnánk és az igen gombot megnyomnánk, győződjünk meg róla, hogy engedélyeztük a beszéd- vagy a braille kimenetet, hogy a gépet a képernyő nélkül is használhassuk.
A képernyőfüggöny kikapcsolásához válasszuk a „nem” lehetőséget.
Ha biztosak vagyunk a dolgunkban, válasszuk az „igen” gombot a képernyőfüggöny bekapcsolásához.
Ha nem szeretnénk, hogy az NVDA ezt a figyelmeztető üzenetet megjelenítse, a figyelmeztető üzenetet tartalmazó párbeszédpanelen kikapcsolhatjuk a figyelmeztetés megjelenítését.
Ha szeretnénk visszaállítani a figyelmeztető üzenetet, jelöljük be a „mindig mutassa a figyelmeztetést a képernyőfüggöny bekapcsolásakor” jelölőnégyzetet, mely a „képernyő elfeketítése” jelölőnégyzet mellett található.
Ha a képernyőfüggönyt akárhonnan szeretnénk bekapcsolni, rendeljünk hozzá egyéni parancsot a [beviteli parancsok párbeszédpanelen](#InputGestures).
Alapértelmezés szerint az NVDA lejátszik egy hangot a képernyőfüggöny bekapcsolásakor. Ha szeretnénk ezt a működést megváltoztatni, vegyük ki a jelölést a „hang lejátszása a képernyőfüggöny bekapcsolásakor” jelölőnégyzetből.

##### Külső felektől származó látást segítő bővítményekkel kapcsolatos beállítások {#VisionSettingsThirdPartyVisualAids}

A további látást segítő bővítményt előállítók a bővítményeiket az
[NVDA bővítmények](#AddonsManager) segítségével illeszthetik a szoftverbe.
Ha a bővítményeikhez beállításokat adnak, azok ebbe a beállítási kategóriába kerülnek elkülönített elemcsoportokba.
A támogatott beállításokhoz és bővítményekhez tekintsük át az adott bővítmény dokumentációját.

#### Billentyűzet  (NVDA+control+k) {#KeyboardSettings}

Az NVDA beállítások párbeszédpanel billentyűzet kategóriája olyan beállításokat tartalmaz, melyek meghatározzák az NVDA működését a billentyűzet használata és a gépelés közben.
Ez a beállítási kategória a következő opciókat tartalmazza:

##### Billentyűzetkiosztás {#KeyboardSettingsLayout}

Ez a kombinált listamező lehetővé teszi, hogy kiválasszuk, az NVDA milyen billentyűzetkiosztást használjon. Jelenleg két kiosztás: az asztali számítógép és a laptop közül lehet választani.

##### NVDA módosítóbillentyű kiválasztása {#KeyboardSettingsModifiers}

Az ebben a listában található jelölőnégyzetekkel szabályozható, milyen billentyűket használhatunk NVDA módosító billentyűként (a továbbiakban: [NVDA gomb](#TheNVDAModifierKey)). A következő billentyűket lehet választani:

* A nagybetűzár (Caps lock)
* Insert a számbillentyűzeten
* Normál insert (mely általában a nyilak, home és end billentyű közelében található)

Ha nem választunk NVDA gombot, előfordulhat, hogy bizonyos NVDA-parancsokat lehetetlen végrehajtani. Ezért az NVDA hibaüzenettel figyelmeztet, ha nem választunk ki egyetlen billentyűt sem, és megnyomjuk az oké vagy az alkalmaz gombot. A hibaüzenetet követően legalább egy billentyűt ki kell választanunk, hogy a párbeszédpanelt az oké gombbal hibaüzenet nélkül be lehessen zárni.

<!-- KC:setting -->

##### Karakterek bemondása íráskor {#KeyboardSettingsSpeakTypedCharacters}

Billentyűparancs: NVDA+2

E jelölőnégyzet bejelölése esetén az NVDA minden beírt karaktert visszamond.

<!-- KC:setting -->

##### Szavak bemondása íráskor {#KeyboardSettingsSpeakTypedWords}

Billentyűparancs: NVDA+3

E jelölőnégyzet bejelölése esetén az Nvda elmondja a beírt szavakat. A szavakat értelemszerűen a szóközök és az írásjelek határolják el egymástól.

==== Beszéd megszakítása íráskor ===[KeyboardSettingsSpeechInteruptForCharacters]
Ha be van kapcsolva, ez a parancs azt idézi elő, hogy a beszéd minden egyes karakter beírásakor megszakad. Ez az alapértelmezett beállítás.

##### Beszéd megszakítása az enterrel {#KeyboardSettingsSpeechInteruptForEnter}

Ha be van kapcsolva, ez a parancs azt idézi elő, hogy a beszéd minden alkalommal megszakad, ha az entert megnyomjuk. Ez az alapértelmezett beállítás.

##### Átfutás engedélyezése folyamatos felolvasáskor {#KeyboardSettingsSkimReading}

Ha ez a funkció be van kapcsolva, bizonyos navigációs parancsok (pl. böngészőmódban a gyors navigációs billentyűk, vagy a sorról sorra, bekezdésről bekezdésre lépés) nem állítja meg a folyamatos felolvasást, hanem a folyamatos felolvasáskor a program az új pozícióra ugrik, és a felolvasást onnan folytatja.

##### Hangjelzés kisbetű beírásakor, ha a capslock be van kapcsolva {#KeyboardSettingsBeepLowercase}

A jelölőnégyzet bejelölése után ha a Capslock be van kapcsolva, és a betű gépelésekor lenyomja a shift billentyűt, a program egy éles csippanással figyelmeztet. Egyes helyzetekben a felhasználók nem veszik észre, hogy a caps lock bekapcsolva maradt, ezért került bele a programba ez a funkció.

<!-- KC:setting -->

##### Parancsbillentyűk bemondása {#KeyboardSettingsSpeakCommandKeys}

Billentyűparancs: NVDA+4

E jelölőnégyzet bejelölése esetén az NVDA bemond minden olyan billentyűt, amely nem valamilyen karakter, hanem egy gyors billentyű. Pl. controll+valamilyen betű.

##### Hangjelzés gépelési hibánál {#KeyboardSettingsAlertForSpellingErrors}

Ha be van kapcsolva, az NVDA egy rövid zümmögő hanggal jelzi, ha gépelés közben hibát vét.
Ez az opció csak akkor elérhető, ha a Helyesírási hibák jelzése opció be van kapcsolva az NVDA [Dokumentum formázás](#DocumentFormattingSettings) párbeszédpanelén.
Megjegyzés: Hogy egy szó hibás-e, vagy sem, azt nem az NVDA dönti el, a program csak a felhasználói alkalmazások jelzéseit alakítja át hangzó információvá, tehát az opció helyes működése nagyban függ az alkalmazások beállításaitól, és az azok által használt helyesírási szótáraktól. Ezen felül hatással lehet rá a rendszer átmeneti túlterheltsége is.

##### Alkalmazások billentyűleütéseinek kezelése {#KeyboardSettingsHandleKeys}

Ennek az opciónak a segítségével szabályozható, hogy az NVDA kezelje-e le a például virtuális billentyűzet vagy szövegfelismerő alkalmazások billentyűleütéseit.
Az opció alapértelmezés szerint engedélyezve van, azonban egyesek valószínűleg letiltják azt, például akik a Vietnami Unikey beviteli módot használják, mivel így az hibás karakterbevitelt eredményezne.

#### Egér (NVDA+control+m) {#MouseSettings}

Az egér beállításait az NVDA beállítások párbeszédpanel  "Egér..." alkategóriában érheti el, és a következő beállítási lehetőségeket tartalmazza:

##### Tájékoztasson az egérmutató alakjának megváltozásáról {#MouseSettingsShape}

E jelölőnégyzet bejelölése esetén az NVDA mindig bemondja, ha az egérmutató alakja megváltozik. A Windowsban az egérmutató alakjának változása bizonyos információkat közöl a felhasználókkal. Ilyen pl. szerkeszthető szöveg, vagy az éppen betöltődő alkalmazás (homokóra), stb. jelzése.

<!-- KC:setting -->

##### Az egér követése {#MouseSettingsTracking}

Billentyűparancs: NVDA+m

E jelölőnégyzet bejelölése esetén az NVDA bemondja azt a szöveget, amely az egérmutató alatt van, annak mozgásakor a képernyőn. Ez lehetővé teszi, hogy az egér valódi mozgatásával térképezze fel a képernyőt, ne pedig az elemek közötti navigációval.

##### Szövegfeldolgozási egység {#MouseSettingsTextUnit}

Ha az NVDA-t úgy állítottuk be, hogy olvassa fel az egérmutató mozgatásakor azt a szöveget, amin áthalad, ezzel a beállítással szabályozhatjuk, hogy az NVDA pontosan mekkora szövegegységet olvasson fel.
A választási lehetőségek: karakter, szó, sor és bekezdés.
Ha bárhol szeretnénk szabályozni a szövegfeldolgozási egység mértékét, kérjük, hozzon létre egyéni parancsot a [beviteli parancsok párbeszédpanelen](#InputGestures).

##### A vezérlőelem típusának bemondása az egérmutató mozgásakor {#MouseSettingsRole}

Ha ez a jelölőnégyzet be van jelölve, az NVDA bemondja az egérmutató alatt lévő vezérlőelem típusát.

##### Az egérmutató mozgásának jelzése hanggal {#toc146}

E jelölőnégyzet bejelölése azt eredményezi, hogy az NVDA kis hangjelzéseket ad, ahogy az egérmutató mozog. Ezzel a felhasználó figyelemmel kísérheti, hogy az egérmutató a képernyő mely részén van.

##### A képernyőn lévő elemek fényerejének jelzése az egér mozgatása közben {#MouseSettingsBrightness}

Ha "Az egérmutató mozgásának jelzése hanggall" jelölőnégyzet be van jelölve, e jelölőnégyzet bejelölése esetén az NVDA hangjelzése attól függően hangosabb vagy halkabb, hogy az egérmutató alatt a képernyő világosabb vagy sötétebb. Mivel ez a funkció Windows Vista alatt teljesítménycsökkenést okozhat, alapértelmezés szerint nincs bejelölve.

##### Más alkalmazásokból érkező egérbemenet figyelmen kívül hagyása {#MouseSettingsHandleMouseControl}

Ezzel a beállítással az NVDA figyelmen kívül hagyja az egérkezelési eseményeket, mint például a mozgatás, kattintás, ha azokata TeamViewerből vagy más hasonló távvezérlő alkalmazásokból végzik.
Ez a beállítás alapértelmezés szerint nincs bekapcsolva.
Ha bejelöljük ezt a beállítást, és egyúttal bekapcsoljuk az * egérkövetése opciót, az NVDA nem fogja felolvasni, ami az egérmutató alatt van, ha az egérmutatót egy másik alkalmazásban mozgatják.

#### Érintőparancsok {#TouchInteraction}

Ez a beállítási kategória csak olyan, windows 8-at vagy újabb verziót futtató gépeken áll rendelkezésre, amelyek képesek az érintőképernyős működési módra. Ez a beállítási kategória szabályozza, hogy az NVDA-val hogyan lehessen kezelni az érintőképernyőket.
Ez a kategória a következő beállításokat tartalmazza:

##### Érintéses bevitel {#TouchTypingMode}

Ezzel a jelölőnégyzettel szabályozhatjuk, hogy milyen módszerrel gépelhetünk az érintőképernyőn megjelenő képernyő-billentyűzeten.
Ha ez a jelölőnégyzet be van jelölve, a következőképpen írhatunk. Keressük meg az ujjunkkal a kívánt betűt, majd emeljük fel. A program az ujjunk felengedésekor írja be a karaktert.
Ha nincs bejelölve, a karakter beviteléhez duplán kell koppintanunk.

#### Áttekintő kurzor {#ReviewCursorSettings}

A beállítás az NVDA beállítások áttekintő kurzor alkategóriában érhető el.
Ez a kategória az alábbi beállításokat tartalmazza:

<!-- KC:setting -->

##### Az aktív elem követése {#ReviewCursorFollowFocus}

Billentyűparancs: NVDA+7

A beállítás engedélyezésével az áttekintő kurzor mindig az aktív elem szövegét mutatja, vagyis azt, ahol a rendszerkurzor található.

<!-- KC:setting -->

##### A kurzor követése {#ReviewCursorFollowCaret}

Billentyűparancs: NVDA+6

A beállítás engedélyezésével az áttekintőkurzor a rendszerkurzor pozíciójához kerül, és követi azt.

##### Az egérmutató követése {#ReviewCursorFollowMouse}

A beállítás engedélyezésével az áttekintő kurzor mindig az egér alatt lévő szöveghez kerül.

##### Egyszerű áttekintőmód {#ReviewCursorSimple}

A beállítás engedélyezésével az NVDA kiszűri a közvetlenül nem hozzáférhető és használható objektumokat, egyszerűbbé téve ezzel a navigálást a navigátor kurzorral.

Az egyszerű áttekintőmód bekapcsolásához rendeljen hozzá billentyűparancsot a [Beviteli parancsok](#InputGestures) párbeszédablakon.

#### Objektumok megjelenítése (NVDA+control+o) {#ObjectPresentationSettings}

Ez a párbeszédpanel az NVDA beállítások Objektumok megjelenítése alkategóriában érhető el, és a következő beállítási lehetőségeket tartalmazza:

##### Eszköztippek bemondása {#ObjectPresentationReportToolTips}

Ha ez a jelölőnégyzet be van jelölve, az NVDA bemondja az eszköztippeket, amint azok megjelennek. Egyes ablakok és vezérlőelemek rövid üzeneteket vagy eszköztippeket jelenítenek meg, ha az egérmutató föléjük kerül, vagy ha a fókuszt rájuk helyezi.

##### Értesítések bemondása {#ObjectPresentationReportNotifications}

Ha ez a jelölőnégyzet be van jelölve, az NVDA felolvassa a súgóbuborékokat és a „toast” értesítéseket, amint azok megjelennek.

* A súgóboburékok olyanok, mint a tippek, de általában nagyobb méretben jelennek meg, és általában olyan rendszereseményekhez kötődnek, mint egy hálózati kábel kihúzása, vagy akár a Windows biztonsági riasztásai.
* A „toast” értesítéseket a Windows 10-ben vezették be, és a rendszertálca értesítési központjában jelennek meg, és számos eseményről tudósítanak (pl. új frissítés, új e-mail, stb.).

##### Az elemhez tartozó gyorsbillentyűk bemondása {#ObjectPresentationShortcutKeys}

Ha e jelölőnégyzet be van jelölve, az NVDA felolvassa az elemhez vagy vezérlőelemhez társított billentyűparancsot. pl. egy program menüsorában a fájl menü az alt+F billentyűparanccsal is előhívható.

##### Az elemen belüli pozíció bemondása {#ObjectPresentationPositionInfo}

Ezzel a beállítással kiválasztható, hogy az objektum pozíciója elhangozzon-e (pl. 1 per 4), amikor a fókusz vagy a navigátor kurzor az objektumhoz kerül.

##### A pozíció meghatározása akkor is, ha nem támogatott {#ObjectPresentationGuessPositionInfo}

A jelölőnégyzet bejelölésekor az NVDA megpróbálja kitalálni azoknak az elemeknek a pozícióját, amik alapértelmezettként nem hozzáférhetőek. Ez a funkció olykor pontatlanul működik.

##### Az elem leírásának bemondása {#ObjectPresentationReportDescriptions}

Kapcsolja ki ezt a jelölőnégyzetet, ha nem kívánja, hogy az NVDA felolvassa az elemhez tartozó leírást.

<!-- KC:setting -->

##### A folyamatjelző változásának jelzése {#ObjectPresentationProgressBarOutput}

Billentyűparancs: NVDA+u

A folyamatjelző egy olyan vezérlőelem, amely egy vonalzóra hasonlít. Egy lassú folyamat esetén a folyamatjelző a feladat előrehaladtával folyamatosan kivilágosodik, továbbá százalékban mutatja, hogy a munka hol tart. Folyamatjelzők pl. weboldal betölltődésekor, e-mailek lehívásakor vagy hangfájlok feldolgozásakor jelennek meg. Az NVDA képes hanggal jelezni, hogy hol tart a folyamat, a hang egyre emelkedik. Ez néha jobb, mintha számokat hallanánk. Egy kombinált listamezőben választhatja ki, hogy az NVDA milyen tájékoztatást adjon a folyamatjelzőkről.

Folyamatjelző állapotának jelzési módjai:

* Nem jelzi a folyamatjelzők változását: Nem tájékoztat a folyamatjelzők állapotáról.
* A folyamatjelzők változásának jelzése beszéddel: A folyamatjelzőket beszéddel (százalékokban) jelzi.
* A folyamatjelzők változásának jelzése hangjelzéssel: A már feljebb írt hangjelzéssel jelzi a folyamatjelzők változását.
* A folyamatjelzők változásának jelzése hangjelzéssel és beszéddel: Százalékokban bemondja, de hangjelzéssel is jelzi a folyamatjelzők állapotát.

##### A háttérben lévő folyamatjelzők változásának jelzése {#ObjectPresentationReportBackgroundProgressBars}

Ha ezt a jelölőnégyzetet bejelöli, és lerakja kis méretre az ablakot, az NVDA akkoris jelezni fogja a változást, így több folyamat előrehaladását is figyelemmel kísérheti.

<!-- KC:setting -->

##### Frissülő tartalom felolvasása {#ObjectPresentationReportDynamicContent}

Billentyűparancs: NVDA+5

Ki és bekapcsolhatja a frissülő tartalom felolvasását bizonyos objektumokban, pl. parancssor ablakok, vagy chat programok előzmény ablakai.

##### Hangjelzés automatikus javaslatok megjelenésekor {#ObjectPresentationSuggestionSounds}

Ez az opció az automatikusan megjelenő javaslatok bejelentését szabályozza. Ha be van jelölve ez a jelölőnégyzet, az NVDA hangjelzést ad minden olyan esetben,amikor automatikus javaslatok jelennek meg. Az automatikus javaslatok egy listán jelennek meg bizonyos szerkesztőmezőkbe, vagy dokumentumokba történő íráskor. A javaslatokat az adott szoftver generálja a beírt karakterek függvényében. Pl. ha elkezd gépelni a Windows vista és újabb verziói esetén a Start menü keresőmezőjébe, a Windows a beírt karakterek alapján megpróbálja kitalálni, hogy mit keres. Ha a javaslatok listáján már szerepel a keresett kifejezés, akkor nem kell tovább gépelni, elég a listáról kiválasztani a megfelelő elemet. A Windows 10 alkalmazások keresőmezőinél az NVDA jelzi a gépeléskor megjelenő javaslatok listáját. A javaslatok listája eltűnik, ha kilép a szerkesztőmezőből. Bizonyos esetekben az NVDA képes jelezni ezt.

#### Beviteli mód {#InputCompositionSettings}

A Beviteli mód párbeszédablakot az NVDA Beállítások Beviteli mód kategóriában találja.
Ebben a párbeszédablakban beállíthatja, hogy az NVDA hogyan kezelje az ázsiai írásjegyek bevitelére szolgáló különböző beviteli módokat.
Ahhoz, hogy igazán gyorsan tudjon gépelni, valószínűleg minden egyes használt beviteli módnál egyedileg kell megadnia ezeket a beállításokat, mivel az egyes beviteli módok nagyon különböző szolgáltatásokat nyújtanak, és más-más módon kommunikálnak a felhasználóval.

##### Az összes javaslat automatikus bemondása {#InputCompositionReportAllCandidates}

Ezzel a beállítással (ami alapértelmezésben be van kapcsolva) megadhatja, hogy az NVDA felolvassa-e automatikusan az összes megjelenő javaslatot javaslati lista megjelenésekor, vagy amikor lapoz a javaslati listában.
Hasznos lehet, ha az írásjegyek alakjára épülő beviteli módoknál (mint amilyen például a kínai New ChangJie, vagy a Boshiami) bekapcsolja ezt a beállítást, hiszen akkor azonnal hallhatja a javasolt írásjegyeket, és hogy egy-egy jel milyen sorszámot visel a listán, és már rögtön választhat is.
Azonban a kiejtésre épülő beviteli módoknál (amilyen például a kínai New Phonetic), célszerű inkább kikapcsolni ezt a beállítást, mert a megjelenő írásjegyek azonosan hangzanak, és csak akkor tud választani a javaslatok közül, ha a nyílbillentyűkkel lépkedve a listán egyenként meghallgatja az írásjegyekhez tartozó magyarázatot.

##### A kijelölt javaslat bemondása {#InputCompositionAnnounceSelectedCandidate}

Ezzel a beállítással (ami alapértelmezésben be van kapcsolva) eldöntheti, hogy az NVDA felolvassa-e a kiválasztott javaslatot javaslati lista megjelenésekor, vagy akkor ha másik javaslatot választ ki a listában.
Azoknál a beviteli módoknál, ahol a nyílbillentyűkkel választhat a javaslatok közül (ilyen például a kínai New Phonetic), be kell kapcsolnia ezt a beállítást, más beviteli módoknál azonban célszerűbb lehet kikapcsolni.
Megjegyzés: az áttekintő kurzor akkor is a kiválasztott elemre kerül, ha ez a beállítás ki van kapcsolva, így az NVDA erre szolgáló parancsaival mindig átnézheti a javaslatokat (nemcsak a kiválasztott javaslatot).

##### Mindig mondja be a rövid karakterleírást javaslatok felolvasásakor {#InputCompositionCandidateIncludesShortCharacterDescription}

Ezzel a beállítással (ami alapértelmezésben be van kapcsolva) megadhatja, hogy az NVDA fűzzön-e rövid magyarázatot a javasolt írásjegyhez (akár kiválasztáskor, akár az összes megjelenő javaslat felolvasásakor).
Megjegyzés: egyes nyelveknél (például a kínainál) a kiválasztott javaslathoz tartozó magyarázat elhangzása nem függ ettől a beállítástól.
Ez a beállítás a koreai, vagy a japán nyelvhez készített beviteli módoknál lehet hasznos.

##### Az olvasási szöveg változásainak bemondása {#InputCompositionReadingStringChanges}

Egyes beviteli módok (például a kínai New Phonetic és a New ChangJie) ún. olvasási szöveget is használnak (ezt néha bevitel előtti szövegnek is nevezik).
Ezzel a beállítással eldöntheti, hogy az NVDA felolvassa-e az olvasási szövegbe beírt írásjegyeket.
Ez a beállítás alapértelmezésben be van kapcsolva.
Megjegyzés: egyes régebbi beviteli módok (például a kínai ChangJie) bevitel előtt nem az olvasási szövegben, hanem közvetlenül a beviteli szövegben tárolják a bevitt írásjegyeket. A beviteli szöveg felolvasását a következő beállítással szabályozhatja.

##### A beviteli szöveg változásainak bemondása {#InputCompositionCompositionStringChanges}

A legtöbb beviteli mód, miután előállította a kívánt írásjegyet, azt átmenetileg egy ún. beviteli szövegben tárolja a korábban beírt írásjegyekkel együtt mindaddig, amíg be nem illeszti ezt a szöveget a dokumentumba.
Ezzel a beállítással megadhatja, hogy az NVDA bemondja-e a beviteli szövegbe kerülő új írásjegyeket.
Ez a beállítás alapértelmezésben be van kapcsolva.

#### Böngészőmód (NVDA+Control+b) {#BrowseModeSettings}

A Böngészőmód beállításait az NVDA beállítások  Böngészőmód... alkategóriában érheti el.
A párbeszédpanel a következő beállítási lehetőségeket tartalmazza:

##### Az egy sorban lévő karakterek maximális száma {#BrowseModeSettingsMaxLength}

E mezőben beállítható, hogy a virtuális kijelző egy-egy sorában maximum hány karakter legyen. Nem biztos, hogy minden sor belefér, de a legtöbb igen.

##### Az egy oldalon lévő sorok száma {#BrowseModeSettingsPageLines}

Annak ellenére, hogy a virtuális kijelzőben valójában nincsenek lapok, ebben a mezőben lehet megadni, hogy a page up és page down billentyűk megnyomásakor hány sort lépjen az NVDA a virtuális kijelzőn.

<!-- KC:setting -->

##### Képernyő-elrendezés használata (ha támogatott) {#BrowseModeSettingsScreenLayout}

Billentyűparancs: NVDA+v

Ezzel a beállítással megadható, hogy a virtuális kijelzőben az elemek és a mezők külön sorban legyenek, vagy tartsák meg a képernyőn lévő helyüket. Ha ez a beállítás engedéllyezve van, akkor minden a képernyőn látható módon jelenik meg, de ha le van tiltva, akkor az elemek külön sorban fognak megjelenni.

##### rétegződő táblázatok jelzése {#BrowseModeSettingsIncludeLayoutTables}

Amikor ez a lehetőség le van tiltva, akkor az NVDA csak táblázatos adatokat jelez, (ahol szükséges a táblázatos elrendezés). Ha a lehetőség engedéllyezve van, az NVDA ezek mellett azokat a táblázatokat is jelzi, amellyek csak a látvány célját szolgálják, (Pl egy weboldal navigációs menüje egy táblázatban).

##### Böngészőmód engedélyezése az oldal betöltésekor {#BrowseModeSettingsEnableOnPageLoad}

Ez a jelölőnégyzet szabályozza, hogy az NVDA automatikusan böngészőmódba kapcsoljon-e egy oldal betöltésekor.
Ha ki van kapcsolva, a böngészőmódot még mindig lehet kézzel aktiválni minden olyan lapon vagy dokumentumban, melyben a böngészőmód támogatva van.
 Tekintse át a [böngészőmód című fejezetet](#BrowseMode) azoknak az alkalmazásoknak a listájáért, amelyekben támogatott a böngészőmód.
Vegyük figyelembe, hogy ez a beállítás nincs hatással azokra az alkalmazásokra, melyben a böngészőmód csupán járulékosan választható, mint pl. a Microsoft Word.
Ez a beállítás alapértelmezés szerint be van kapcsolva.

##### Automatikus fókuszmód az aktív vezérlőelem megváltozásakor {#BrowseModeSettingsAutoPassThroughOnFocusChange}

Ez az opció lehetővé teszi, hogy a fókusz változásakor az NVDA automatikusan fókuszmódba lépjen. pl., ha egy weboldalon egy űrlapmezőre lép a tab billentyűvel, az NVDA automatikusan fókuszmódba lép, ha ez a jelölőnégyzet be van jelölve.

##### Automatikus fókuszmód a kurzor mozgásakor {#BrowseModeSettingsAutoPassThroughOnCaretMove}

Ha ez a jelölőnégyzet be van jelölve, az NVDA a nyílbillentyűk mozgatásakor automatikusan vált a fókuszmód és a böngészőmód közt. Ha pl. egy weboldalon lefelé halad a le nyíl segítségével és az NVDA talál egy szerkesztőmezőt, automatikusan fókuszmódba lép. Ha azonban a szerkesztőmezőt elhagyja, visszavált böngészőmódba.

##### A fókuszmód és a böngészőmód jelzése hangjelzéssel {#BrowseModeSettingsPassThroughAudioIndication}

Ha bekapcsolja ezt a beállítást, akkor a fókuszmód és a böngészőmód közti váltást hangjelzéssel jelzi a program.

##### Automatikus folyamatos felolvasás az oldal betöltésekor {#BrowseModeSettingsAutoSayAll}

Ezzel a jelölőnégyzettel adható meg, hogy az NVDA automatikusan felolvassa-e az oldalt a betöltése után böngészőmódban.
Ez a beállítás gyárilag be van kapcsolva.

##### Rétegződő táblázatok elrendezésének megőrzése {#BrowseModeSettingsIncludeLayoutTables}

Ez a beállítás határozza meg, hogy az NVDA hogyan kezelje a kizárólag elrendezési szempontból létesített táblázatokat.
Ha be van kapcsolva, az NVDA úgy kezeli ezeket, mint a normál táblázatokat, és úgy jelenti be őket, ahogyan a [DokumentumFormázási beállításokban](#DocumentFormattingSettings) megadtuk, és ennek megfelelően kell az egygombos navigációs parancsokkal kezelni őket.
Ha ki van kapcsolva, az NVDA nem jelenti be őket, és nem használhatjuk elérésükre az egygombos navigációs parancsokat sem, ugyanakkor a táblázatok tartalmát a képernyőolvasó rendes szövegként kezeli.
Ez a beállítás alapból ki van kapcsolva.
Ha a rétegződő táblázatok elrendezésének megőrzését máshol is szeretnénk átállítani, kérjük, rendeljen hozzá egyéni parancsot a [beviteli parancsok párbeszédpanelen](#InputGestures).

##### Mezők, pl. linkek, címsorok bejelentésének beálítása böngészőmódban {#BrowseModeLinksAndHeadings}

Kérjük, tekintse át a beállításokat a [DokumentumFormázási kategoriában](#DocumentFormattingSettings) az [NVDA beállításai](#NVDASettings) párbeszédpanelen a navigáció során felolvasandó mezők, pl. hivatkozások, címsorok és táblázatok,  bejelentésének beállításához.

##### A nem NVDA-parancsnak minősülő egyéb parancsok blokkolása {#BrowseModeSettingsTrapNonCommandGestures}

Ez a gyárilag bekapcsolt beállítás lehetővé teszi, hogy ha egy billentyűparancs (pl. billentyűkombináció) nem NVDA-parancs és nem általános billentyűparancs, vissza legyen tartva attól, hogy átmenjen a fókuszban lévő dokumentumon.
Például, ha be lenne kapcsolva és a „j” betűt megnyomnánk, azt az NVDA elfogná és nem engedné át a dokumentumnak annak ellenére sem, hogy az sem gyorsnavigációs parancsnak nem minősül, sem a program nem alkalmazza saját billentyűparancsként.
Ebben az esetben az NVDA a Windowst egy hang lejátszására kéri, ha egy elfogott billentyűt nyomunk meg.

#### Dokumentumformázás (NVDA+control+d) {#DocumentFormattingSettings}

E párbeszédpanel a beállítások menü Dokumentumformázás... parancsával nyitható meg. Az itt található jelölőnégyzetekkel lehet beállítani, hogy az NVDA milyen formázási információkat olvasson fel, ha egy Word vagy Wordpad dokumentumban mozog a nyíl billentyűkkel. pl.: ha bejelöli a betűtípus bemondása jelölőnégyzetet, az NVDA bemondja a betűtípus nevét, ha a kurzorral új betűtípusú szövegrészre lép.

A dokumentumformázási opciók csoportokba vannak sorolva.

* Betűtípus
 * Betűtípus neve
 * Betűméret
 * Betűtípus paraméterek (dőlt, áthúzott, felső index stb.)
 * Kiemelés
 * Stílus (Címsor 1, Címsor 2 stb.)
 * Színek
* Dokumentum
 * Megjegyzések
 * Szerkesztői változások
 * Helyesírási hibák
* Oldalak és sorköz
 * Oldalszámok
 * Sorszámok
 * Sorok behúzásának jelzése [(Kikapcsolva, Beszéd, Hangjelzés, Beszéd és hangjelzés)](#lineIndentationOptions)
 * Bekezdés-behúzás (függő behúzás, első sor behúzás stb.)
 * Sorköz (szimpla, dupla stb.)
 * Bekezdés-igazítás (balra zárt, jobbra zárt stb.)
* Táblázat
 * Táblázatok
 * Sor/oszlop fejlécek
 * Cellakoordináták
 * Cellaszegélyek (Kikapcsolva, stílus, szín és stílus)
* Elemek
 * Címsorok
 * Hivatkozások
 * Listák
 * Idézetblokkok
 * Jelzőpontok
 * Keretek
 * Kattintható

Mindegyik elemhez egyedi billentyűparancsot  rendelhet a [Beviteli parancsok](#InputGestures) párbeszédablakon.

==== A kurzor pozíciójánál lévő formázások változásának jelzése (a beszéd késését okozhatja) ====[DocumentFormattingDetectFormatAfterCursor]
E jelölőnégyzet bejelölésével az NVDA a sorok felolvasásakor bemondja a formázási változásokat (pl. eltérő betűméret, betűtípus, stb). Ez az NVDA lassabb működését eredményezheti.

Alapértelmezettként az NVDA az aktuális karakter formázásait észleli (rendszer vagy áttekintő kurzor használatakor), esetenként az egész sorra kiterjedő formázást is, ha az nem vezet az NVDA működésének lelassulásához.
Engedélyezze ezt a lehetőséget pl. Wordpad esetén, ahol fontos a formázás.

==== Sorok behúzásának jelzése ====[DocumentFormattingSettingsLineIndentation]
Ezzel az opcióval beállíthatja, hogyan jelezze az NVDA a sorok behúzását.
A kombinált listamezőben négy lehetőség közül választhat:

* Kikapcsolva: Az NVDA nem jelzi a sorok behúzását.
* Beszéd: Az NVDA bemondja a sorok elején található szóközök és tabok számát, pl.: "12 szóköz" vagy "4 tab" akkor is, ha vegyesen állnak "tab 2 szóköz 3 tab"
* Hangjelzés: Az NVDA hangjelzéssel jelzi a sorok behúzását. A behúzás mértékére a hangjelzés magasságából lehet következtetni.
Minden szóköz egy egységgel magasítja a hangot, egy tab 4 egységgel. Tehát ha van a sor elején 2 szóköz és egy tab, a hang 6 egységnyi magasan szólal meg.
* Beszéd és hangjelzés: Az NVDA mindkét fenti módszerrel jelzi a sorok elején található tabokat és szóközöket.

#### Windows 10 OCR beállítások {#Win10OcrSettings}

Ezt a párbeszédablakot az NVDA beállítások menüjéből érheti el, itt konfigurálhatja a Windows 10 OCR funkciót. [Windows 10 OCR](#Win10Ocr).

##### Felismerési nyelv {#Win10OcrSettingsRecognitionLanguage}

E kombinált listamezőben kiválaszthatja a szöveg felismeréséhez használt nyelvet.

#### Haladó beállítások {#AdvancedSettings}

Figyelem! Az e kategóriában lévő beállításokat tapasztalt felhasználók vegyék igénybe! Helytelen beállításuk esetén az NVDA nem működik megfelelően!
Csak akkor változtassa meg ezeket a beállításokat, ha biztos abban, amit tesz, vagy ha Önt erre egy NVDA-fejlesztő kifejezetten utasítja.

##### A haladó beállítások engedélyezése {#AdvancedSettingsMakingChanges}

A haladó beállítások engedélyezéséhez jelölje be a jelölőnégyzetet, hogy tisztában van ezen beállítások megváltoztatásának kockázatával.

##### A gyári beállítások visszaállítása {#AdvancedSettingsRestoringDefaults}

A gomb visszaállítja a gyári beállításokat akkor is, ha a speciális beállítások engedélyezésére vonatkozó jelölőnégyzet nincs bejelölve.
Előfordulhat, hogy a beállítások megváltoztatását követően vissza szeretne térnia  program eredeti beállításaihoz.
Ilyen eset például, ha Ön nem biztos abban, hogy egy beállítás megváltozott-e.

##### Saját testreszabott kód betöltésének engedélyezése a fejlesztési könyvtárból {#AdvancedSettingsEnableScratchpad}

Hasznos, ha egy NVDA bővítmény fejlesztésekor tesztelhetjük az általunk megírt kódot. Ennek a beállításnak az aktiválásakor lehetővé válik, hogy az NVDA egyéni alkalmazásmodulokat, általános célú bővítményeket, braille kijelzőkhöz vagy beszédszintetizátorokhoz való illesztőprogramokat töltsön be egy egyéni fejlesztői könyvtárból, mely az NVDA felhasználói beállításai között jön létre.
Korábban az NVDA az egyéni kódokat közvetlenül a felhasználó NVDA-beállításokat tartalmazó könyvtárából töltötte be, így ezeket nem lehetett kiiktatni. Ez a beállítás gyárilag ki van kapcsolva, hogy a felhasználó a kifejezett beleegyezése nélkül ne futtathasson nem tesztelt kódokat.
Ha szeretne másokkal egyéni kódokat megosztani, csomagolja be NVDA-bővítményként.

##### Fejlesztési könyvtár megnyitása {#AdvancedSettingsOpenScratchpadDir}

Ezzel a gombbal lehet megnyitni a fejlesztői könyvtárat, ahová a fejlesztés alatt lévő kódot lehet tenni.
Ez a gomb csak  akkor használható, ha az NVDA úgy van beállítva, hogy be van kapcsolva az Egyéni kódok  betöltésének engedélyezése a Developer Scratchpad könyvtárból opció.

##### UI Automation használata a Microsoft Word dokumentumvezérlőihez, ha lehetséges {#AdvancedSettingsUseUiaForWord}

Ha ez a beállítás engedélyezve van, az NVDA megpróbálja használni a Microsoft UI Automation accessibility API-t az információk kinyeréséhez a Microsoft Word dokumentum vezérlőkből. Ez a Microsoft Wordre, a Microsoft Outlook üzenetnézőjére és üzenetkészítőjére is vonatkozik.
A leggyakoribb, azaz a Windows 10-en futó Microsoft Office 2016/365 esetén az UI Automation támogatás teljesen elegendő, hogy hozzáférést biztosítson a Microsoft Word dokumentumokhoz, majdnem olyan mértékűt, mint amilyen az NVDA meglévő Microsoft Word támogatása, azzal a további előnnyel, hogy a szoftver reakciókészsége nagy mértékben növekedett. Azonban van jó néhány olyan információ, mely nem megfelelően vagy rosszul jelenik meg a Microsoft Office bizonyos verzióiban, ami azt jelenti, hogy az UI Automation támogatásra nem mindig lehet hagyatkozni. A felhasználók többségének még mindig nem ajánljuk, hogy ezt a funkciót alapértelmezés szerint bekapcsolják, noha az Office 2016/365-ben már tesztelik ezt a funkciót, és várnak a visszajelzésekre.

##### Az UI Automation használata a Windows parancssorhoz, ha lehetséges {#AdvancedSettingsConsoleUIA}

Ha ez a beállítás engedélyezve van, az NVDA egy új, röptében elérhető új támogatást nyújt a Windows konzolhoz, mellyel kihasználhatók a [Microsoft akadálymentesítési fejlesztései](https://devblogs.microsoft.com/commandline/whats-new-in-windows-console-in-windows-10-fall-creators-update/). Ez a funkció még nagyon kísérleti jellegű, és még mindig nincsen teljesen készen így használata nem ajánlott. Ha azonban elkészül, előrelátható, hogy ez lesz az alapértelmezett, mely növeli az NVDA teljesítményét és megbízhatóságát a Windows parancssorok használata során.

##### Jelszavak bemondása az UIA konzolokban {#AdvancedSettingsWinConsoleSpeakPasswords}

Ez a beállítás szabályozza, hogy a karakterek bemondása elhangozzon-e a [beírt karakterek bemondása gépeléskor](#KeyboardSettingsSpeakTypedCharacters) vagy a [szavak bemondása gépeléskor](#KeyboardSettingsSpeakTypedWords) olyan esetekben, amikor a képernyő nem frissül, például jelszavak beírásakor parancssorban, ha az UI Automation engedélyezve van. Biztonsági okokból ezt a beállítást célszerű tiltani, de engedélyezhetjük, ha teljesítménybeli problémákat vagy instabilitást tapasztalunk a beírt karakterek vagy szavak gépeléskori felolvasásakor, ha az NVDA kísérleti új konzoltámogatási funkcióját használjuk.

##### Használja az új beírt karakterek bemondását a Windows konzolban, ha elérhető {#AdvancedSettingsKeyboardSupportInLegacy}

Ez a beállítás egy alternatív módszert használ a parancssorba írt karakterek felismeréséhez.
Bár javítja a teljesítményt, és elhárítja azt a hibát, hogy az NVDA lebetűzze a parancskimenetet, több terminálos programmal inkompatibilis.
Ez a beállítás elérhető és alapból be van kapcsolva a Windows 10 1607 és újabb verzióiban, ha az UI Automationt nem használjuk vagy nem érhető el.
Figyelem! Ha ez a beállítás engedélyezve van, az olyan karaktereket, melyek nem jelennek meg a képernyőn, pl. a beírandó jelszavak, a rendszer nem tudja feldolgozni.
Bizonytalan környezetben fontoljuk meg a [karakterek bemondása gépeléskor](#KeyboardSettingsSpeakTypedCharacters) és [szavak bemondása gépeléskor](#KeyboardSettingsSpeakTypedWords) ideiglenes kikapcsolását jelszavak bevitelekor.

##### Beszéd megszakítása az időközben lejárt fókuszeseményeknél {#CancelExpiredFocusSpeech}

Ez a beállítás úgy változtatja meg az NVDA működését, hogy elnémuljon a beszéd az elavult fókuszeseményeknél. Különösképpen az üzeneteken történő gyors lépkedéskor a Gmailben Chrome böngésző használata során előfordu, hogy az NVDA elavult információkat olvas fel.
Ezt a kísérleti funkciót az NVDA 2020.2 verziójában vezették be.

##### Kurzor mozgásának időtúllépése (ezredmásodperc) {#AdvancedSettingsCaretMoveTimeout}

Ezzel a beállítással szabályozható, hogy az NVDA hány ezredmásodpercet várjon a kurzor (beszúrási pont) mozgására a szerkesztőmezőkben.
Ha úgy tűnik, hogy az NVDA rosszul kezeli a kurzort, nem lép egy karakteről a következőre vagy egyik sorról a másikra, próbáljuk megnövelni ezt az értéket.

##### Hibakeresési naplózási kategóriák {#AdvancedSettingsDebugLoggingCategories}

Az ebben a listában található jelölőnégyzetek segítségével engedélyezhetők a hibaüzenetek bizonyos kategóriái az NVDA naplójában.
Ezeknek az üzeneteknek a naplóban történő rögzítése ronthatja a teljesítményt és növelheti a naplófájl méretét.
Csa kakkor kapcsoljuk be ezeket az üzeneteket, ha erre egy NVDA-fejlesztő kifejezetten utasít minket például azért, hogy kiderítsük, miért nem működik megfelelően egy braille kijelző illesztőprogramja.

### Egyéb / vegyes beállítások {#MiscSettings}

Az [NVDA beállításai](#NVDASettings) párbeszédpanel mellett az NVDA menüjének beállítások almenüje további olyan konfigurálási lehetőségeket tartalmaz, melyeket az alábbiakban emelnénk ki.

#### Kivételszótárak {#SpeechDictionaries}

A beállítások menüben található kivételszótárak menü olyan lehetőségeket tartalmaz, melyekkel megadható, hogy az NVDA miként ejtsen ki egyes szavakat, kifejezéseket. Jelenleg háromféle szótártípus létezik:

* Alapértelmezett kivételszótár: az itt megadott szabályok az NVDA minden hangkarakterére érvényesek.
* Hangkarakter kivételszótár: az itt megadott szabályok csak az éppen használt hangkarakterre érvényesek.
* Ideiglenes kivételszótár: az itt megadott szabályok az NVDA minden hangkarakterére érvényesek, de csak a jelenlegi munkameneten belül. A szabályok csak átmeneti jellegűek, melyek az NVDA újraindításakor érvényüket vesztik.

Minden párbeszédablak tartalmaz egy szabálylistát, mely a szöveg feldolgozása közben hajtódik végre. Itt szintén elérhető a hozzáadás, szerkesztés és az eltávolítás gomb is. A párbeszédablakokhoz egyedi billentyűparancsot rendelhet a [Beviteli parancsok](#InputGestures) ablakban.

Új szabály hozzáadásához használja a hozzáadás gombot. Töltse ki a mezőket a felbukkanó párbeszédablakban, majd nyomja meg az OK gombot. A szabály megjelenik a szabályok listájában. A szótár mentéséhez nyomja meg az OK gombot, ha végzett a szabályok hozzáadásával/szerkesztésével.

A szabályok az NVDA kivételszótáraiban lehetővé teszik, hogy egy szövegrészt behelyettesítsen egy másik szövegrésszel. Egy egyszerű példa erre, ha az NVDA a madár szó helyett béka szót mond. A szabály hozzáadása párbeszédablakban a tényleges kifejezés mezőbe írja be: madár. A behelyettesített kifejezés mezőbe pedig a béka szó kerüljön. Megadhatja a szabály leírását a megjegyzés mezőben (pl.: a madár helyett békát mond).

Az NVDA kivételszótárai azonban ennél jóval többre képesek. A párbeszédablak tartalmaz egy kis- és nagybetűk megkülönböztetése jelölőnégyzetet, mely bejelölése esetén az NVDA különbséget tesz a kis- és nagybetűk között. Alapértelmezettként az NVDA figyelmen kívül hagyja a kis- és nagybetűket. Egy másik jelölőnégyzettel beállítható, hogy a kifejezés egy "szabályozott kifejezés" legyen-e. Egy szabályozott kifejezés egy speciális karaktereket tartalmazó kifejezés, mellyel egyszerre töb karakterre, számra, vagy csak betűkre is rákereshet. A szabályozott kifejezések nem képezik az útmutató részét, de rengeteg leírás létezik, melyekkel bővebben megismerheti a használatukat.

#### Írásjelkiejtés {#SymbolPronunciation}

Ezen a párbeszédpanelen állítható be a központozás módja, valamint az, hogy az NVDA hogyan ejtse ki az egyes szimbólumokat / írásjeleket. Így itt állítható be a központozás szintje is, hogy az NVDA mely írásjeleket olvassa fel és melyeket ne.
A párbeszédpanel címsorában látható, milyen nyelv írásjelkiejtési beállításait szerkesztjük. Vegyük figyelembe, hogy ez a párbeszédpanel a „beszédszintetizátor alapján (trust voice)” meghatározott nyelvet veszi figyelembe a karakterek és szimbólumok feldolgozásakor, melyet az [NVDA beállításai](#NVDASettings) párbeszédpanel beszéd kategóriájában található [beszédbeállítások](#SpeechSettings) között találunk, így például ennek a beállításnak az alkalmazásakor a beszédszintetizátor nyelvét veszi alapul ez a párbeszédpanel, nem pedig az NVDA nyelvi beállításait.
Egy írásjel megváltoztatásához először válasszuk ki azt a írásjelek listájából.

* Szűrhetünk írásjelek szerint, ha beírjuk a szimbólumot, vagy az annak helyettesítésére szolgáló kifejezés egy részét a szűrés szerkesztőmezőbe.
* A Behelyettesített kifejezés szerkesztőmezőben megváltoztathatjuk azt a szöveget, mely elhangzik a szimbólum  felolvasásakor.
* A szint legördülő mező segítségével határozhatjuk meg, melyik legyen az a legalacsonyab szint, amelyen a szimbólum elhangzik.
* Az aktuális szimbólum beszédszintetizátorra küldése beállítómező azt szabályozza, hogy az NVDA a szimbólumot magában, ne pedig a helyettesítő kifejezését küldje ki a beszédszintetizátorra.
Ez akkor hasznos, ha a szimbólum a beszédszintetizátort arra utasítja, hogy tartson szünetet, vagy változtasson a hanglejtésén. Például: vessző esetén a beszédszintetizátor szünetet tart.
Három beállítási lehetőség érhető el:
* Soha: soha nem küldi át az aktuális szimbólumot a beszédszintetizátornak.
 * Mindig: Mindig átküldi az aktuális szimbólumot a beszédszintetizátornak.
* Csak akkor, ha a szimbólumhoz meghatározott írásjelszint van beállítva: csak akkor küldi át az aktuális szimbólumot, ha az általánosan beállított írásjelszint alacsonyabb, mint az adott szimbólumhoz megadott írásjelszint.  Például beállíthatjuk egy szimbólumhoz magasabb szintre annak helyettesítő kifejezését szünet nélkül, míg alacsonyabb szinten a beszédszintetizátor szünetet tart.
  -

Új szimbólum hozzáadásához nyomjuk meg a „hozzáadás” gombot. A megjelenő párbeszédpanelen vigyük be a szimbólumot, és nyomjuk meg az oké gombot. Ezt követően úgy változtassuk meg a mezőket, ahogy a többi szimbólumnál is tennénk.
Egy korábban hozzáadott szimbólum eltávolításához nyomjuk meg a törlés / eltávolítás gombot. Ha befejeztük, a beállítások eltárolásához nyomjuk meg az oké, elvetéséhez a mégsem gombot.

#### Beviteli parancsok {#InputGestures}

Ezen a párbeszédpanelen testre szabhatók az NVDA beviteli parancsai (a billentyűparancsok a billentyűzeten, a gombokhoz kötött funkciók a braille kijelzőn, stb.) az NVDA parancsainak használatához. A program csak azokat a parancsokat mutatja, amelyek azonnal alkalmazhatók, mielőtt a párbeszédpanelt megnyitjuk. Például, ha a böngészőmódhoz kapcsolódó parancsokat szeretnénk megváltoztatni, a párbeszédpanelt úgy kell megnyitnunk, hogy már böngészőmódban vagyunk.

a párbeszédablakban lévő fanézet kategóriák szerint csoportosítva listázza az összes alkalmazható NVDA-parancsot. Minden beviteli parancs egy vezérlőparancshoz van társítva. Ahhoz, hogy egy vezérlőparancshoz egy beviteli parancsot hozzáadjunk, válasszuk ki a vezérlőparancsot, nyomjuk meg a hozzáadás gombot, majd adjuk meg azt a beviteli parancsot, amelyet a vezérlőparancshoz kívánunk társítani, például nyomjunk meg egy billentyűt a billentyűzeten, egy gombot a braille kijelzőn. Gyakran előfordul, hogy egy vezérlőparancshoz több beviteli parancsot kell társítanunk. Például: ha ilyenkor leütünk egy billentyűt a billentyűzeten, meghatározhatjuk, hogy az a használt billentyűzet-kiosztásban (asztali vagy laptop), netán az összes kiosztásban alkalmazandó legyen. Ebben az esetben egy menü jelenik meg, melyen kiválaszthatjuk a kívánt működési módot.

Lehetőségünk van a beviteli parancsok szűrésére is. Gépeljünk be egy vagy több kifejezést a szűrés szerkesztőmezőbe, ekkor a tab billentyű megnyomása esetén a feltételnek megfelelő elemek jelennek csak meg a fanézetben.

Egy beviteli parancsot úgy választhatunk le a vezérlőparancsról, ha kiválasztjuk és az eltávolítás gombot megnyomjuk.

Ha befejeztük a változtatásokat, az igen gombbal mentsük el azokat, ha szeretnénk őket elvetni, használjuk a mégsem gombot.

### A Beállítások Elmentése És Betöltése {#SavingAndReloading}

Az NVDA elmenti automatikusan a módosításokat, amit a beállítások menüben kikapcsolhat.  Ha az NVDA csak olvasható fájlrendszerből - pl. CD-ről -  fut, a beállításokat nem lehet elmenteni.

Ha a beállítások megváltoztatása után vissza szeretne térni az elmentett beállításokhoz, aktiválhatja az "Az elmentett beállítások visszaállítása" menüelemet az NVDA menüjében. Ha az eredeti beállításokat szeretné életbe léptetni, az NVDA menüjében erre is van lehetősége.

Néhány billentyűparancs a segítségére lehet:
<!-- KC:beginInclude -->

| Funkció |Asztali billentyűparancs |Laptop billentyűparancs |Leírás|
|---|---|---|---|
|A beállítások elmentése |NVDA+control+c |NVDA+control+c |Elmenti az aktuális beállításokat, így azok nem vesznek el az NVDA bezárásakor.|
|Az elmentett beállítások visszaállítása |NVDA+control+r |NVDA+control+r |Egyszeri megnyomásra visszaállítja az utoljára elmentett beállításokat, háromszori lenyomásra az alapértelmezett  beállításokat tölti be.|

<!-- KC:endInclude -->

### Beállítási profilok {#ConfigurationProfiles}

Néha a különböző helyzetekben különböző beállításokra van szükség. Például szükségünk van arra, hogy a program felolvassa az igazításokat és betűtípusokat szövegszerkesztéskor vagy a szöveg formázásának vagy helyesírásának ellenőrzésekor. Az NVDA lehetővé teszi ezt a beállítás-profilok (a továbbiakban: profil) használatával.

Egy profil csak azokat a beállításokat tartalmazza, amelyek a profil szerkesztésekor megváltoztak. A profilokban szinte minden beállítás megváltoztatható, kivéve az általános beállításokat, mert azok az NVDA egészére hatással vannak.

a profilokat kézzel lehet aktiválni. A profilok automatikusan is aktiválhatók, ha megadjuk a profil alkalmazási feltételeit (a továbbiakban: feltétel), például ilyen feltétel, hogy a profil csak az adott alkalmazásra lépéskor vagy az alkalmazás indításakor lépjen működésbe.

#### Alapvető beállítások {#ProfilesBasicManagement}

A profilokat az NVDA menü profilok testreszabása párbeszédpanelén lehet létrehozni, szerkeszteni, törölni stb. A párbeszédpanelt a következő billentyűparanccsal is megnyithatjuk:
<!-- KC:beginInclude -->

* NVDA+kontrol+p: Megjeleníti a Profilok testreszabása párbeszédpanelt

<!-- KC:endInclude -->

az első vezérlőelem ezen a párbeszédpanelen a profilok listája, melyből kiválaszthatjuk a rendelkezésre álló profilt. A párbeszédpanel megnyitásakor az aktuálisan szerkesztett profilt jelöli ki a program. A profilokhoz további információkat is megjeleníthet a képernyőolvasó. Például, hogy kézzel kell bekapcsolni, feltételtől függően kapcsol be, vagy éppen szerkesztés alatt van.

A profil törléséhez vagy átnevezéséhez értelemszerűen nyomjuk meg a törlés vagy az átnevezés gombot. A párbeszédpanel bezárásához nyomjuk meg a bezárás gombot.

#### Profil készítése {#ProfilesCreating}

Profil készítéséhez nyomjuk meg az új gombot.
az új profil párbeszédpanelen  adjuk meg a profil nevét. Kiválasztható, hogy a profilt hogyan használjuk. Ha a profilt kézi használatúra szeretnénk állítani (a továbbiakban: kézi profil), a "használja ezt a profilt a következőhöz" kombinált listamezőben válasszuk ki a "kézi aktiválás" lehetőséget, ez az alapértelmezett beállítás. Egyéb esetben válasszunk egy feltételt, amely automatikusan alkalmazza a profilt (a továbbiakban: automatikus profil). Ha nem töltjük ki a profil nevét, de választunk egy feltételt, a program - kényelmi okokból - a profilt a feltételnek megfelelően nevezi el. További információkért tanulmányozza a feltételekről szóló fejezetet.

Az ok gomb megnyomásával a profil létrejön és a párbeszédpanel bezáródik. Ettől kezdve a profil szerkeszthető.

#### A profil kézi bekapcsolása {#ConfigProfileManual}

A profilt úgy lehet kézzel bekapcsolni, hogy a profilok testreszabása párbeszédpanelen kiválasztjuk, és megnyomjuk a kézi aktiválás gombot. Ha a profil aktív, további profilokat is bekapcsolhat a program, ha fennállnak annak feltételei, azonban a kézzel aktivált profil beállításai élveznek előnyt. Így pl. ha van nekünk egy az aktuális alkalmazáshoz rendelt profilunk amiben a hivatkozások jelzése be van kapcsolva, de a kézzel aktivált profilban ez ki van kapcsolva, akkor  a linkek nem kerülnek bemondásra.
Ha megváltoztatta a beszéd paramétereit a feltételhez kötött profilban, de a kézzel aktiváltban ezen nem módosított, akkor a feltétel kiváltásakor a feltételhez kötött profil beszédparaméterei lépnek életbe.
Minden beállítás módosítás a kézzel aktivált profilba kerül elmentésre.

A kézi profil kikapcsolásához a profilok testreszabása párbeszédpanelen válasszuk ki azt, majd nyomjuk meg a kézi kikapcsolás gombot.

#### Feltételek {#ConfigProfileTriggers}

A profilok testreszabása párbeszédpanelen a feltételek gomb megnyomását követően megváltoztathatók az automatikus profilok.

A feltételek listája tartalmazza az elérhető feltételeket, melyek a következők:

* aktuális alkalmazás: akkor aktiválja a megadott profilt, ha az aktuális alkalmazásra kapcsolunk.
* Folyamatos felolvasás: akkor kapcsolja be a profilt, ha a folyamatos felolvasás parancsot alkalmazzuk.

Ha szeretnénk megváltoztatni egy automatikus profilt, válasszuk ki a feltételt, majd a feltételhez tartozó profilok listájából azt a profilt, amelyet meg szeretnénk változtatni.

Ha azt szeretnénk, hogy az adott feltétel ne kapcsoljon be egy profilt sem, válasszuk ki a feltételt a feltételek listájából, majd az alapértelmezett beállítás lehetőséget a profil kombinált listamezőből. Ezt követően a bezárás gombbal térhetünk vissza a profilok testreszabása párbeszédpanelhez.

#### Profil szerkesztése {#ConfigProfileEditing}

Ha kézzel aktiváltunk egy profilt, a program minden változtatást ebbe a profilba ment el. Egyéb esetben a program a leggyakrabban használt automatikus profilokba menti a változtatásokat.

Ha például a jegyzettömbhöz készítettünk egy profilt és átkapcsolunk a jegyzettömbre, a program minden változtatást a jegyzettömb profiljába ment el. Végül, ha sem kézi, sem automatikus profilt nem készítettünk, a program a változtatásokat az alapértelmezett profilba menti el.

ahhoz, hogy a folyamatos felolvasás profilját szerkesszük meg, kézzel be kell kapcsolnunk azt.

#### a feltételek ideiglenes felfüggesztése {#ConfigProfileDisablingTriggers}

Néha szükség lehet arra, hogy minden feltételt felfüggesszünk. Ilyen eset, ha például szerkeszteni szeretnénk egy kézi profilt, vagy az alapértelmezett konfiguráció beállítását szeretnénk megváltoztatni anélkül, hogy ütközne bármely automatikus profillal. Ezt úgy érhetjük el, ha a profilok testreszabása párbeszédpanelen bejelöljük az összes feltétel ideiglenes kikapcsolása jelölőnégyzetet.

#### Profil aktiválása a beviteli parancsok használatával {#ConfigProfileGestures}

Minden profilhoz, amit hozzáadtunk, egy vagy több egyéni parancsot rendelhetünk hozzá, hogy aktiválhassuk. Gyárilag a beállítási profilokhoz nincs hozzárendelve beviteli parancs.

Profil aktiválására szolgáló parancs hozzáadásához a [beviteli parancsok párbeszédpanel](#InputGestures) használható. Minden parancsnak saját bejegyzése van a beállítási profilok kategóriában.

Profil átnevezése esetén minden korábban hozzáadott beviteli parancs elérhető marad.

Profil törlésekor automatikusan törlődnek azok a parancsok, melyek hozzá voltak társítva.

### A konfigurációs fájlok helye {#LocationOfConfigurationFiles}

A hordozható verziókban az összes beállítás, driver és script egy userconfig könyvtárban kapott helyet, ami az NVDA könyvtárában található.

Ezzel szemben a telepítős változat fájljai a felhasználó profiljának könyvtárában találhatóak. Ez azt jelenti, hogy ha ugyanazon a gépen több felhasználó is telepítette az NVDA programot, a beállításaikat az NVDA külön kezeli. Ezt a mappát elérheti a start menü-programok-NVDA-A felhasználói beállítások tallózása menüpontot megnyitva.

Az NVDA beállításai a bejelentkező képernyők használatához a program könyvtárában található.
A konfiguráció módosítása kívülről nem ajánllott.
A megváltoztatáshoz állítsa be a kívánt beállítást az NVDA programban, mentse el a módosításokat, majd nyomja meg az "Az aktuális beállítások használata a bejelentkező és egyéb biztonsági képernyőkön" gombot az általános beállítások menüben.

## Extra Eszközök {#ExtraTools}
### Naplónéző {#LogViewer}

A naplónéző segítségével az NVDA elindításakor létrejött napló tartalmát tekintheti meg. Ez főleg a hibák feltérképezésekor lehet hasznos, ugyanis innen megtudható, hogy mikor milyen hibaüzenetet írt ki a program.

A napló megtekintésén kívül annak tartalma másolható, vagy elmenthető. A naplónéző az eszközök  menüben található meg.

### Beszédnéző {#SpeechViewer}

Látó fejlesztők vagy az NVDA bemutatásának megkönnyítésére látó emberek számára elérhető egy úgynevezett beszédnéző, mely egy lebegő ablakban folyamatosan megjeleníti az éppen elhangzó szöveget.

E funkció engedélyezéséhez jelölje be a beszédnéző lehetőséget az eszközök menüben. Letiltásához törölje a jelölést a menüelemről.

A beszédnéző használatakor a lebegő ablak tartalma folyamatosan frissül, attól függően, mit mond épp a beszédszintetizátor. Ha azonban az ablakon belülre kattint, az ablak tartalma nem frissül, lehetővé téve annak tartalmát áttekinteni vagy másolni.

A Beszédnéző ablaka tartalmaz egy "A beszédnéző megnyitása az NVDA indulásakor" címkéjű jelölőnégyzetet.
Ha be van jelölve, akkor a Beszédnéző az NVDA indulásakor automatikusan megnyílik.
A beszédnéző ablaka mindig megőrzi a legutolsó bezáráskor érvényes méretét és pozícióját a képernyőn. Mindig ott és úgy nyílik meg, ahol, és ahogy a legutolsó bezáráskor hagyta.

### Braillenéző {#BrailleViewer}

Látó fejlesztők vagy olyanok számára, akik az NVDA-t látó közönségnek mutatják be, elérhető egy lebegő ablak, mely lehetővé teszi a braille kimenet megjelenítéséta braille karakterek szöveges megfelelőjével együtt. A braillenéző egy fizikai braille kijelzővel egyidejűleg is használható, ilyenkor a braillenéző cellaszáma igazodni fog a braille kijelzőhöz. Amíg a braillenéző aktív, folyamatosan frissül, hogy megjelenítse a braille tartalmat, mintha azt egy fizikai braille kijelzőn jelenítenénk meg.

A braillenéző bekapcsolásához jelöljük be a braillenéző bejelölhető menüelemet az NVDA menü eszközök almenüjében.

Kikapcsolásához vegyük ki a menüelemből a jelölést.

A fizikai braille kijelzőknek általában vannak előre- és visszagörgető gombjai. A braillenézőben való előre- és hátragörgetéshez rendeljünk hozzá egyéni parancsot a [beviteli parancsok párbeszédpanel](#InputGestures) használatával.

A braillenézőben van egy „Indítsa a braillenézőt az NVDA indításakor” jelölőnégyzet. Ha be van jelölve, a braillenéző az NVDA-val együtt indul.

A braillenéző mindig ugyanazokkal az ablakméretezésekkel és azon a helyen próbál megnyílni, ahol bezártuk.

### Python Konzol {#PythonConsole}

Az NVDA Python konzol, mely az NVDA eszközök menüjében található, egy fejlesztői eszköz mely hasznos az NVDA összetevőinek futás közbeni megvizsgálásakor, esetenként egy alkalmazás hozzáférhetőségi hierarchiájának megállapításakor.
Részletes információért tekintse meg az angol nyelvű [NVDA fejlesztői dokumentációt](https://www.nvaccess.org/files/nvda/documentation/developerGuide.html).

### Bővítmények kezelése {#AddonsManager}

A bővítménykezelőben (amelyet az NVDA menü -eszközök almenüjében érhet el) megnézheti a feltelepített bővítmények listáját, hozzáathat egy újat, letilthatja/engedélyezheti, vagy eltávolíthatja őket a programból.
Ezeket az NVDA közössége készíti, amivel a program funkcióit igyekeznek kibővíteni. Lehet ez egy egyszerűbb script (időjárás jelentés lekérdező program), vagy egy új beszédszintetizátor támogatása is.Ezeket a bővítményeket az NVDA közösség készíti, és olyan egyéni kódokat tartalmaznak, amelyek akár ki is egészíthetik vagy megváltoztathatják az NVDA egyes funkcióit, vagy akár további braille kijelzőt vagy beszédszintetizátort támogathatnak.
A bővítménykezelő egy listában jeleníti meg a már feltelepített bővítményeket. A csomag nevét, státuszát, verzióját, és készítőjét már a listából is megtudhatja, a kiegészítő hosszabb leírását és internetes hivatkozását (url) a "bővítmény névjegye" gomb aktiválásával érheti el.
Ha tartozik a kiegészítőhöz súgó, azt a "bővítmény súgója" gomb aktiválásával érheti el.

Az elérhető bővítmények internetről történő beszerzéséhez és böngészéséhez nyomja meg a „bővítmények beszerzése” gombot.
Ez a gomb az [NVDA-bővítmények](https://addons.nvda-project.org/) honlapot nyitja meg.
Ha az NVDA telepítve van és fut, közvetlenül a böngészőből is megnyithatja a bővítményt.
Másik lehetőség: mentsük el a bővítményt, és kövessük az alábbi utasításokat.

A korábban beszerzett bővítmény telepítéséhez nyomja meg a Hozzáadás gombot.
Ennek hatására megnyílik egy fájlböngésző párbeszédpanel, melynek segítségével NVDA-bővítményeket (.nvda-addon kiterjesztésű fájlokat) kereshet bárhol a számítógépen vagy egy hálózaton.
A megnyitás gomb megnyomásával megkezdődik a telepítés.
Az NVDA a telepítés indításakor megkérdezi, hogy biztosan telepíteni szeretné-e a bővítményt.

Ha a bővítmény funkcionalitása nincs korlátozva az NVDA-ban, elméletileg lehetséges, hogy a bővítmény hozzáférjen a személyes adataihoz, telepített NVDA-példány esetén akár az egész rendszerhez, ezért nagyon fontos, hogy csak olyan NVDA-bővítményt telepítsen, mely olyan forrásból származik, amelyben megbízik.
A bővítmény telepítése után az NVDA-t újra kell indítani. Amíg ezt nem teszi meg, a bővítmény státusza a bővítménykezelőben „telepítés alatt” lesz.

Egy bővítmény eltávolításához válassza ki azt a kurzor mozgató billentyűk segítségével, majd aktiválja az "eltávolítás" gombot. Ekkor az NVDA rákérdez még egyszer a bővítmény eltávolítása előtt. A művelet befejezéséhez a program újraindításaszükséges, addig a listában az "eltávolítás" jelenik meg a kiegészítő  státuszaként.

Egy bővítmény letiltásához nyomja meg a Bővítmény letiltása gombot.
Egy korábban letiltott bővítmény engedélyezéséhez nyomja meg a bővítmény engedélyezése gombot.
Akkor tilthat le egy bővítményt, ha annak állapota fut vagy engedélyezett. Akkor engedélyezhet egy bővítményt, ha annak állapota felfüggesztett vagy letiltott.
A Bővítmény letiltása/engedélyezése gomb minden egyes lenyomásakor a kijelölt bővítmény állapota is megváltozik. Ez az állapot jelzi, hogy mi fog történni a bővítménnyel az NVDA újraindítása után.
A bővítmények letiltása és engedélyezése, a telepítéshez és az eltávolításhoz hasonlóan, csak az NVDA újraindítása után lép életbe.
A bővítménykezelő „bezárás” gombja használható a párbeszédpanel bezárására.
Ha telepített, törölt egyet, vagy megváltoztatta egy bővítmény státuszát, az NVDA először rákérdez, hogy a változások életbe lépéséhez újraindítja-e a képernyőolvasót.

Ha máshonnan is szeretne hozzáférni a bővítménykezelőhöz, kérjük, adjon hozzá egyéni parancsot a [beviteli parancsok párbeszédpanel](#InputGestures) használatával.

Több régi bővítmény már nem kompatibilis az NVDA aktuális verziójával. Úgyszintén, ha az NVDA régebbi verzióját használjuk, az újabb bővítmények nem lesznek kompatibilisek az új verzióval.
Ha nem kompatibilis bővítményt kíván telepíteni, az hibát eredményezhet.
Az inkompatibilis bővítmények ellenőrzéséhez nyomja meg az „inkompatibilis bővítmények ellenőrzése” gombot, melynek hatására elindul az inkompatibilis bővítmények kezelője.

#### Inkompatibilis bővítmények kezelése {#incompatibleAddonsManager}

Az inkompatibilis bővítmények kezelője, melyet a bővítménykezelő „inkompatibilis bővítmények megtekintése” gombjának megnyomásával érhetünk el, lehetővé teszi, hogy ellenőrizzük az összeférhetetlen bővítményeket, és kideríthessük, miért lehetnek inkompatibilisek.
A bővítmények összeférhetetlenek lehetnek, ha nem igazítják őket az NVDA jelentős változásaihoz, vagy olyan funkción alapulnak, amely nincs benne az NVDA aktuális verziójában.
Az NVDA rövid üzenettel figyelmeztet a szükséges NVDA verzióra.
Az összeférhetetlen bővítmények kezelője listájában a következő oszlopok találhatók:

1. csomag: a bővítmény neve.
1. verzió: a bővítmény verziója.
1. összeférhetetlenségi ok: rövid leírás, miért tűnik a bővítmény összeférhetetlennek.

Az inkompatibilis bővítmények kezelője tartalmaz továbbá egy „A bővítmény névjegye” gombot.
A megjelenő párbeszédpanelen a bővítménnyel kapcsolatos minden információ elérhető, hogy fel lehessen venni a kapcsolatot a bővítmény fejlesztőjével.

### Hordozható másolat elkészítése {#CreatePortableCopy}

A menüelem kiválasztását követően megnyílik egy párbeszédpanel, melynek segítségével hordozható változat készíthető a telepített példányból.
Ha hordozható példányt futtat, az extra eszközök almenüben e menüpont helyett „Az NVDA telepítése erre a számítógépre” látható.
Mind a két párbeszédpanelen kéri a program, hogy válassza ki a hordozható változat elkészítésére vagy az NVDA telepítésére szolgáló könyvtárat.
Ezeken a párbeszédpaneleken tetszés szerint a következő lehetőségek álíthatók be.

* A bejelentkezett felhasználó beállításainak átmásolása: (magában foglalja a %appdata%\roaming\NVDA könyvtárat, vagy a hordozható példány felhasználói beállításait, beleértve a bővítményeket és modulokat is.)
* Az új hordozható példány elindítása annak elkészítése után, vagy az NVDA indítása a telepítése után: (automatikusan elindítja az NVDA-t a hordozható változat elkészítése vagy a telepítés után.)

### Rendszerkonfiguráció-helyreállító eszköz futtatása {#RunCOMRegistrationFixingTool}

Programok telepítésekor és törlésekor bizonyos esetekben előfordulhat, hogy a COM dll fájlok regisztrációja (beállítása) nem történik meg.
Az olyan COM csatolófelületek (interfészek) működése, mint az IAccessible, a többi COM dll összetevő helyes beállításán múlik. Ha ezek nem helyesen történnek meg, hibák léphetnek fel.

Ilyen hibák történhetnek például az Adobe Reader, a Math Player vagy más programok telepítése vagy törlése után.
Az ilyen beállítási problémák hibákat okozhatnak a böngészők, asztali alkalmazások, a tálca vagy más összetevők használata során.

Ennek az eszköznek a futtatásával különösképpen a következő problémák javíthatók:

* Ha az NVDA azt jelenti be, hogy „ismeretlen” a Firefoxban vagy más böngészőben, illetve a Thunderbirdben történő navigáció során stb.
* Ha az NVDA hibázik a fókuszmód és a böngészőmód közötti átkapcsoláskor.
* Ha az NVDA túl lassan reagál böngészőmódban böngészőben történő navigáció során.
* Más egyéb hibák esetén.

### A bővitmények újratöltése {#ReloadPlugins}

A menüelem aktiválásával az NVDA az összes bővítményt újratölti, anélkül hogy a program újraindulna. Ez főként a fejlesztőknek hasznos.

## Támogatott beszédszintetizátorok {#SupportedSpeechSynths}

Ez a fejezet az NVDA által támogatott beszédszintetizátorokról nyújt bővebb tájékoztatást. Friss információkért látogassa meg az NVDA [Ezzel foglalkozó weboldalát.](https://www.nvda-project.org/wiki/ExtraVoices)

### eSpeak NG {#eSpeakNG}

Az [eSpeak NG](https://github.com/espeak-ng/espeak-ng) egy ingyenes beszédszintetizátor, ami bele van építve az NVDA programba. Ennek egyik nagy előnye az, hogy az NVDA egy USB eszközön is kiválóan fut, ugyanis nincs szüksége semmilyen driver telepítésére. A beszédszintetizátor több mint 43 nyelvet támogat, és a felhasználóknak lehetőségük van a hang különböző változatainak kiválasztására is.

### Microsoft Speech API version 4 (SAPI 4) {#SAPI4}

A SAPI4 a Windows egy régebbi szabványa a különböző beszédszintetizátorokhoz. Ez a Microsoft már nem támogatja, az ehhez tartozó kiegésztők már nem tölthetőek le a hivatalos oldalról.
Ha ön egy SAPI 4-es szintetizátort használ, akkor a hozzátartozó hangkaraktereket a [beszéd...](#VoiceSettings) beállításainál, vagy a [szintetizátor körön](#SynthSettingsRing) tudja módosítani, miután aktiválta a SAPI 4 szabványt a Beszédszintetizátor párbeszédablakon.

### Microsoft Speech API version 5 (SAPI 5) {#SAPI5}

A SAPI5 egy Windows szabvány a beszédszintetizátor programokhoz. Sok szintetizátor támogatja ezeket, néhány ingyenes, és számos fizetős található a piacon. Ezeknek többségét a gyártó honlapjáról letöltheti/megrendelheti.
Ha ön egy SAPI 5-ös szintetizátort használ, akkor a hozzátartozó hangkaraktereket a [beszéd...](#VoiceSettings) beállításainál, vagy a [szintetizátor körön](#SynthSettingsRing) tudja módosítani, miután aktiválta a SAPI 5 szabványt a Beszédszintetizátor párbeszédablakon.

### Windows OneCore hangok {#OneCore}

A Windows 10 új hangokat tartalmaz az úgynevezett "OneCore" hangokat.
Ezek a hangok több nyelven is elérhetők, és jobb minőségűek, mint a korábbi Microsoft SAPI5-ös hangok.

Az alábbi webcímen megtalálhatja az elérhető hangok listáját, ill. a telepítésükhöz szükséges instrukciókat: https://support.microsoft.com/hu-hu/help/22797/windows-10-narrator-tts-voices

Vegye figyelembe, hogy a Narrátor használatakor elérhető gyorsabb beszédsebesség az NVDA esetében jelenleg még nem működik.
Ezzel együtt a Windows beállításainál megadott beszédsebesség kihatással van az NVDA-ban beállított beszédsebességre.
Ezt a problémát kizárólag az NVDA oldaláról nem lehet orvosolni, szükség lenne hozzá bizonyos változtatásokra a windows fejlesztőitől is.
Reméljük, hogy valamelyik későbbi Windows-frissítésben ezt meg is teszik.

### Microsoft Speech Platform {#MicrosoftSpeechPlatform}

A Microsoft Speech Platform több nyelvhez tartalmaz beszédhangokat, melyeket általában szerverre szánt beszéd alapú alkalmazásokhoz használnak.
Az NVDA képes ezeket a beszédhangokat is használni.

Ezeknek a hangoknak a használatához két összetevőt kell telepíteni:

* Microsoft Speech Platform - Runtime (Version 11) , x86: https://www.microsoft.com/download/en/details.aspx?id=27225
* Microsoft Speech Platform - Runtime Languages (Version 11): https://www.microsoft.com/download/en/details.aspx?id=27224

Ez a honlap sok fájlt tartalmaz mind a beszédfelismeréshez, mind a beszédszintetizátorhoz (text-to-speech).  Válasszuk ki a kívánt nyelvhez szükséges tts adatokat tartalmazó fájlokat. Például: Az MSSpeech_TTS_en-US_ZiraPro.msi egy amerikai angol hang.

### Audiologic Tts3 {#toc231}

Ez egy fizetős szintetizátor, ami kizárólag olasz nyelven érhető el. Az NVDA-val való használat előtt ezt telepítenie kell a számítógépére. Bővebb információért keresse fel az AudioLogic weboldalát: [www.audiologic.it](http://www.audiologic.it)

### Vocalizer beszédhangok az NVDA-hoz {#toc232}

A Nuance Vocalizer egy magas minőségű, kereskedelmi beszédszintetizátor, amit a  Nuance Communications, Inc. készített. A hozzátartozó drivert a Tiflotecnia, Lda. készítette. A szintetizátorhoz több mint 50 külön    böző beszédhangot telepíthet fel, mintegy harminc különböző nyelven. Mindegyik beszédhang kiegészítőként telepíthető, így a hordozható verzióval is használható. A hangokról és a vásárlás menetéről bővebb információt olvashat a [magyar forgalmazó](https://vocalizer.nvda.hu) oldalán. Az összeg egy részét az NVDA további fejlesztésére fordítják.

## Támogatott braille kijelzők {#SupportedBrailleDisplays}

Ebben a fejezetben az NVDA által támogatott braille kijelzőkről olvashat.

### Freedom Scientific Focus/Pacmate kijelzők {#toc234}

A Freedom Scientific Focus/Pacmate kijelzőket tudja használni az NVDA programmal. Csak akkor jelenik meg a kijelzők listájában, ha fel van telepítve a Freedom Scientific braille driver. Ezeket a [Freedom Scientific hivatalos braille driverek angol nyelvű oldalán](https://www2.freedomscientific.com/downloads/focus-40-blue/focus-40-14-blue-downloads.asp) érheti el, a driverek telepítési információival együtt.
Ez ugyan a Focus  Blue kijelzőkhöz készült, de támogatja az összes többi Freedom Scientific terméket is.
Megjegyzés: Ha ön 64 bites operációs rendszert használ, amire már fel van telepítve a kijelző drivere egy másik képernyőolvasóval együtt, az NVDA programhoz külön telepíteniekell az eszköz illesztőprogramját.

Alapbeálítás szerint az NVDA ezeket a kijelzőket képes automatikusan felismerni és csatlakoztatni usb-n és bluetoothon keresztül is.
Azonban a kijelző beállításainál kifejezetten meghatározható, hogy a kijelzőt bluetoothon vagy usb-n kívánja-e használni, ezzel tehát korlátozni lehet a kijelző használatát a kiválasztott csatolófelületre.
Ez például hasznos lehet akkor, ha a Focus braille kijelzőt bluetooth-szal kívánja használni, de usb-n keresztül kívánja feltölteni.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Leírás |billentyű|
|---|---|
|Bal oldali görgő lenyomási műveletének váltása |Bal WizWheel Nyomva|
|Mozgás egy kijelzőnyivel visszafelé a bal oldali görgővel |bal WizWheel felfelé|
|Mozgás egy kijelzőnyivel előre a bal oldali görgővel |Bal WizWheel lefelé|
|Jobb oldali görgő lenyomási műveletének váltása |jobb WizWheel nyomva|
|mozgás egy kijelzőnyivel visszafelé a jobb oldali görgővel |Jobb WizWheel felfelé|
|Mozgás egy kijelzőnyivel előre a jobb oldali görgővel |Jobb WizWheel lefelé|
|A kurzor az aktuális braille cellához helyezése |routing|

<!-- KC:endInclude -->

### Optelec ALVA BC640/680 {#toc235}

Az [Optelec](https://www.optelec.com/) ALVABC 640 és 680 kijelzőket támogatja az NVDA. Nem kell semmilyen drivert telepítenie, mivel ezeket már az NVDA tartalmazza, csak csatlakoztassa a braille kijelzőjét a számítógéphez és végezze el az NVDA-ban a szükséges beállításokat a kijelző használatba vételéhez.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Leírás |Billentyű|
|---|---|
|Egy kijelzőnyivel visszalépés |t1 vagy etouch1|
|A kijelzőt az előző sorhoz helyezi |t2|
|Mozgatás a jelenlegi fókuszhoz |t3|
|A kijelzőt a következő sorhoz helyezi |t4|
|Egy kijelzőnyivel visszalép |t5 vagy etouch3|
|A kurzor az aktuális braille cellához helyezése |routing|
|Kiírja az adott cellához tartozó formázási információt |másodlagos routing|
|A kurzor a legfelső sorhoz helyezése áttekintő módban |t1+t2|
|A kurzor legalsó sorhoz helyezése áttekintő módban |t4+t5|
|a braille követés váltása |t1+t3|
|cím bejelentése |etouch2|
|Állapotsor bejelentése |etouch4|
|shift+tab billentyű |sp1|
|alt billentyű |sp2|
|Escape billentyű |sp3|
|tab billentyű |sp4|
|felnyíl |spUp|
|lenyíl |spDown|
|balra nyíl |spLeft|
|jobbra nyíl |spRight|
|enter billentyű |spEnter|
|Dátum/idő bejelentése |sp1+sp2|
|windows+b (fókusz a rendszertálcára) |sp3+sp4|
|ctrl+home |t3+spUp|
|ctrl+end |t3+spDown|
|home |t3+spLeft|
|end |t3+spRight|
|NVDA Menü |sp1+sp3|
|windows+d (az összes alkalmazás kisméretre helyezése) |sp1+sp4|
|windows billentyű |sp2+sp3|
|alt+tab |sp2+sp4|

<!-- KC:endInclude -->

### Handy Tech kijelzők {#toc236}

Az NVDA az összes [Handy Tech](https://www.handytech.de/) kijelzőt támogatja.
Ha ön egy usb-s kijelzőt használ, fel kell telepítenie a Handy Tech usb driverét a rendszerére. Továbbá telepítenie kell a Handy Tech általános driverét, amit a következő címről tölthet le:
ftp://ftp.handytech.de/public/Software/BrailleDriver/bsd1206a.exe

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Leírás |Billentyű|
|---|---|
|Egy kijelzőnyivel visszalép |left, up|
|Egy kijelzőnyivel előrelép |right, down|
|A kijelzőt az előző sorhoz helyezi |b4|
|A kijelzőt a következő sorhoz helyezi |b5|
|A kurzor az aktuális braille cellához helyezése |routing|
|shift+tab |esc|
|alt billentyű |b2+b4+b5|
|escape billentyű |b4+b6|
|tab billentyű |enter|
|enter billentyű |esc+enter|
|felnyíl |leftSpace|
|lenyíl |rightSpace|
|NVDA Menü |b2+b4+b5+b6|
|Handy Tech konfigurációs beállítások |b4+b8|

<!-- KC:endInclude -->

### MDV Lilli {#toc237}

Az NVDA támogatja az [MDV](https://www.mdvbologna.it/) által forgalmazott Lilli braille kijelzőket. A használathoz nincs szükség semmilyen driver telepítésére, egyszerűen csak csatlakoztassa a kijelzőt a számítógépéhez, és végezze el az NVDA programban a szükséges beállításokat.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Leírás |Billentyű|
|---|---|
|Egy kijelzőnyivel visszalép |LF|
|Egy kijelzőnyivel előrelép |RG|
|A kijelzőt az előző sorhoz helyezi |UP|
|A kijelzőt a következő sorhoz helyezi |DN|
|A kurzor az aktuális braille cellához helyezése |route|
|shift+tab |SLF|
|tab billentyű |SRG|
|alt+tab |SDN|
|alt+shift+tab |SUP|

<!-- KC:endInclude -->

### Baum/Humanware/APH/Orbit Braille kijelzők {#toc238}

Néhány [Baum](https://www.baum.de/cms/en/), [HumanWare](https://www.humanware.com/), [APH](https://www.aph.org/) és and [Orbit](https://www.orbitresearch.com/) kijelzővel az NVDA képes együttműködni, ha ezek usb vagy bluetooth kapcsolódással csatlakoznak a számítógéphez.
A következőket tartalmazzák:

* Baum: SuperVario, PocketVario, VarioUltra, Pronto!
* HumanWare: Brailliant, BrailleConnect, Brailliant2
* APH: Refreshabraille
* Orbit: Orbit Reader 20

Néhány egyéb Baum kijelző is működhet, bár ezek nem voltak tesztelve a programmal.
Az APH Refreshabraille használata előtt az USB mód serial állapotban kell hogy legyen.
Ha olyan kijelzőt csatlakoztat USB porton keresztül, ami nem használ HID protokollt, akkor először fel kell telepítenie a gyártó által biztosított drivereket.
A VarioUltra és a Pronto! HID protokollt használ.
A Refreshabraille és az Orbit Reader 20 megfelelő beállítás esetén Képes HID protokollt használni.

Az Orbit Reader 20 esetén az USB soros mód jelenleg az egyetlen támogatott kapcsolódási mód Windows 10 alatt.
Ehelyett USB HID protokollt kellene használni.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Leírás |Billentyű|
|---|---|
|Egy kijelzőnyivel visszalép |d2|
|Egy kijelzőnyivel előrelép |d5|
|A kijelzőt az előző sorhoz helyezi |d1|
|A kijelzőt a következő sorhoz helyezi |d3|
|A kurzor az aktuális braille cellához helyezése |routing|

A joystick-kal rendelkező kijelzőkhöz:

| Leírás |Billentyű|
|---|---|
|felnyíl |up|
|lenyíl |down|
|balra nyíl |left|
|jobbra nyíl |right|
|enter billentyű |select|

<!-- KC:endInclude -->

### hedo ProfiLine USB {#toc239}

Az NVDA támogatja a hedo ProfiLine USB kijelzőt (gyártó: [hedo Reha-Technik](https://www.hedo.de/)).
Használat előtt telepítse a gyártótól kapott USB vezérlőprogramot.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Léptetés visszafelé |K1|
|Léptetés előre |K3|
|A kijelző az előző sort mutatja |B2|
|A kijelző a következő sort mutatja |B5|
|Braille cella aktiválása |cellákhoz tartozó gombok|
|Beállítja, hogy mit kövessen a kijelző |K2|
|Folyamatos olvasás |B6|

<!-- KC:endInclude -->

### hedo MobilLine USB {#toc240}

Az NVDA támogatja a hedo MobilLine USB kijelzőt (gyártó: [hedo Reha-Technik](https://www.hedo.de/)).
Használat előtt telepítse a gyártótól kapott USB vezérlőprogramot.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Léptetés visszafelé |K1|
|Léptetés előre |K3|
|A kijelző az előző sort mutatja |B2|
|A kijelző a következő sort mutatja |B5|
|Braille cella aktiválása |cellákhoz tartozó gombok|
|Beállítja, hogy mit kövessen a kijelző |K2|
|Folyamatos olvasás |B6|

<!-- KC:endInclude -->

### HumanWare Brailliant BI/B sorozat / BrailleNote Touch {#HumanWareBrailliant}

Az NVDA támogatja a Brailliant BI és B sorozatába tartozó kijelzőket (gyártó: [HumanWare](https://www.humanware.com/)). Ez a sorozat magában foglalja a BI 14, BI 32, BI 40 és a B 80 modelleket, mind USB, mind bluetooth csatlakoztatási módban.
Ha a kijelzőt USB-n keresztül csatlakoztatja, használat előtt telepítse a gyártótól kapott USB vezérlőprogramot.
Az OpenBraille protokoll használata esetén nem szükséges az USB vezérlőprogram telepítése.
A BrailleNote Touch kijelző is támogatott, nem szükséges hozzá semmilyen egyéb driver feltelepítése.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.

#### Billentyűparancsok az összes modellhez {#toc242}

<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Léptetés visszafelé |bal|
|Léptetés előre |jobb|
|A kijelző az előző sort mutatja |fel|
|A kijelző a következő sort mutatja |le|
|Braille cella aktiválása |cellákhoz tartozó gombok|
|Beállítja, hogy a kijelző mit kövessen |fel+le|
|Felnyíl szimulálása |szóköz+1-es|
|Lenyíl szimulálása |szóköz+4-es|
|Balnyíl szimulálása |szóköz+3-as|
|Jobbnyíl szimulálása |szóköz+6-os|
|shift+tab szimulálása |szóköz+1-es+3-as|
|tab szimulálása |szóköz+4-es+6-os|
|alt szimulálása |szóköz+1-es+3-as+4-es (szóköz+m)|
|escape szimulálása |szóköz+1-es+5-ös (szóköz+e)|
|enter szimulálása |8-as|
|windows gomb szimulálása |szóköz+3-as+4-es|
|alt+tab szimulálása |szóköz+2-es+3-as+4-es+5-ös (szóköz+t)|
|NVDA Menü előhívása |szóköz+1es+3as+4es+5ös (szóköz+n)|
|windows+d szimulálása (az összes alkalmazás kis méretre állítása) |szóköz+1es+4es+5ös|
|Folyamatos olvasás |szóköz+1es+2es+3as+4es+5ö+6os|

<!-- KC:endInclude -->

#### Billentyűparancsok Brailliant BI 32, BI 40 and B 80 modellekhez {#toc243}

<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|NVDA Menü előhívása |c1+c3+c4+c5 (n parancs)|
|windows+d szimulálása (az összes alkalmazás kis méretre állítása)|
|Folyamatos olvasás |c1+c2+c3+c4+c5+c6|

 <!-- KC:endInclude -->

#### Billentyűparancsok Brailliant BI 32, BI 40 and B 80 modellekhez {#toc244}

<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Felnyíl szimulálása |joystick fel|
|Lenyíl szimulálása |joystick le|
|Balnyíl szimulálása |joystick bal|
|Jobbnyíl szimulálása |joystick jobb|
|enter szimulálása |joystick megnyomása|

<!-- KC:endInclude -->

### HIMS Braille Sense/Braille EDGE/Smart Beetle/Sync Braille sorozat [Hims] {#toc245}

Az NVDA támogatja a Braille Sense,  Braille EDGE, Smart Beetle, és Sync Braille kijelzőket (gyártó: [Hims](http://www.hims-inc.com/)), mind USB, mind bluetooth csatlakoztatási módban.
Ha a kijelzőt USB-n keresztül csatlakoztatja, használat előtt telepítse a gyártótól kapott USB vezérlőprogramot. Ezt a következő oldalról töltheti le: http://www.himsintl.com/upload/HIMS_USB_Driver_v25.zip

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Léptetés visszafelé |bal oldali scroll down|
|Léptetés előre |jobb oldali scroll down|
|A kijelző az előző sort mutatja |bal oldali scroll up|
|A kijelző a következő sort mutatja |jobb oldali scroll up|
|Braille cella aktiválása |cellákhoz tartozó gombok|
|shift+tab szimulálása |1-es+2-es+szóköz|
|alt szimulálása |1-es+3-as+4-es+szóköz|
|escape szimulálása |1-es+5-ös+szóköz|
|tab szimulálása |4-es+5-ös+szóköz|
|enter szimulálása |8-as|
|backspace szimulálása |7-es|
|felnyíl szimulálása |1-es+szóköz|
|lenyíl szimulálása |4-es+szóköz|
|capsLock |1-es+3-as+6-os+szóköz|
|shift+alt+tab szimulálása |advance2+advance3+advance1|
|alt+tab szimulálása |advance2+advance3|
|end szimulálása |4-es+6-os+szóköz|
|Control+end szimulálása |4-es+5-ös+6-os+szóköz|
|home szimulálása |1-es+3-as+szóköz|
|control+home szimulálása |1-es+2-es+3-as+szóköz|
|balnyíl szimulálása |3-as+szóköz|
|control+shift+balnyíl szimulálása |2-es+8-as+szóköz+advance1|
|control+balnyíl szimulálása |2-es+szóköz|
|shift+alt+balnyíl szimulálása |2-es+7-es+advance1|
|alt+balnyíl szimulálása |2-es+7-es|
|jobbnyíl szimulálása |6-os+szóköz|
|control+shift+jobbnyíl szimulálása |5-ös+8-as+szóköz+advance1|
|control+jobbnyíl szimulálása |5-ös+szóköz|
|shift+alt+jobbnyíl szimulálása |5-ös+7-es+advance1|
|alt+jobbnyíl szimulálása |5-ös+7-es|
|pageUp szimulálása |1-es+2-es+6-os+szóköz|
|control+pageUp szimulálása |1-es+2-es+6-os+8-as+szóköz|
|control+shift+felnyíl szimulálása |2-es+3-as+8-as+szóköz+advance1|
|control+felnyíl szimulálása |2-es+3-as+szóköz|
|shift+alt+felnyíl szimulálása |2-es+3-as+7-es+advance1|
|alt+felnyíl szimulálása |2-es+3-as+7-es|
|shift+felnyíl szimulálása |bal oldali scroll down + szóköz|
|pageDown szimulálása |3-as+4-es+5-ös+szóköz|
|control+pagedown szimulálása |3-as+4-es+5-ös+8-as+szóköz|
|control+shift+lenyíl szimulálása |5-ös+6-os+8-as+szóköz+advance1|
|control+lenyíl szimulálása |5-ös+6-os+szóköz|
|shift+alt+lenyíl szimulálása |5-ös+6-os+7-es+advance1|
|alt+lenyíl szimulálása |5-ös+6-os+7-es|
|shift+lenyíl szimulálása |jobb oldali scroll down + szóköz|
|delete szimulálása |1-es+3-as+5-ös+szóköz|
|f1 szimulálása |1-es+2-es+5-ös+szóköz|
|f3 szimulálása |1-es+2-es+4-es+8-as|
|f4 szimulálása |7-es+advance3|
|windows+b szimulálása |1-es+2-es+advance1|
|windows+d szimulálása |1-es+4-es+5-ös+advance1|

<!-- KC:endInclude -->

<<<<<<< .mine
||||||| .r43479

### HIMS SyncBraille {#toc246}

Az NVDA támogatja a SyncBraille kijelzőt (gyártó: [HIMS](http://www.hims-inc.com/)).
Használat előtt telepítse a HIMS cég USB vezérlőprogramját.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Léptetés visszafelé |bal oldali scroll down|
|Léptetés előre |jobb oldali scroll down|
|Braille cella aktiválása |cellákhoz tartozó gombok|

<!-- KC:endInclude -->

=======

### HIMS SyncBraille {#toc247}

Az NVDA támogatja a SyncBraille kijelzőt (gyártó: [HIMS](https://www.hims-inc.com/)).
Használat előtt telepítse a HIMS cég USB vezérlőprogramját.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Léptetés visszafelé |bal oldali scroll down|
|Léptetés előre |jobb oldali scroll down|
|Braille cella aktiválása |cellákhoz tartozó gombok|

<!-- KC:endInclude -->

>>>>>>> .r45280

### Seika braille kijelzők {#toc248}

Az NVDA támogatja a Seika 3, 4 és 5 (40 cellás), valamint a Seika80 (80 cellás) braille kijelzőket (gyártó: [Nippon Telesoft](https://www.nippontelesoft.com/)).
A https://www.seika-braille.com/ weboldalon bővebb információt talál ezekről a kijelzőkről.
Használat előtt telepítse a gyártótól kapott USB vezérlőprogramot.

Az alábbiakban felsoroljuk azokat a kijelzőn lévő parancsbillentyűket (és a hozzájuk tartozó parancsokat), amiket az NVDA programban használhat. A kijelző dokumentációjában találhatja meg, hogy ezek a billentyűk hol helyezkednek el.
<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Léptetés visszafelé |bal|
|Léptetés előre |jobb|
|A kijelző az előző sort mutatja |B3|
|A kijelző a következő sort mutatja |B4|
|Beállítja, hogy mit kövessen a kijelző |B5|
|Folyamatos olvasás |B6|
|tab |b1|
|shift+tab |b2|
|alt+tab |b1+b2|
|NVDA Menü előhívása |bal+jobb|
|Braille cella aktiválása |cellákhoz tartozó gombok|

<!-- KC:endInclude -->

### Papenmeier BRAILLEX újabb modelljei {#toc249}

Az NVDA ezek közül az alábbi kijelzőket támogatja:

* BRAILLEX EL 40c, EL 80c, EL 20c, EL 60c (USB)
* BRAILLEX EL 40s, EL 80s, EL 2d80s, EL 70s, EL 66s (USB)
* BRAILLEX Trio (USB és bluetooth)
* BRAILLEX Live 20, BRAILLEX Live és BRAILLEX Live Plus (USB és bluetooth)

Ha a BrxCom program telepítve van, az NVDA használni fogja azt.
A BrxCom programmal képernyőolvasó használata nélkül is lehetősége van braille bevitelre a kijelzőn.
A Papermeier cég hamarosan ki fog adni egy olyan új BrxCom verziót, ami kompatibilis az NVDA-val. Azomban a braille bevitel a BrxCom használata nélkül is lehetséges a Trio eszközökön.

A legtöbb modell rendelkezik egy egyszerűsített kezelést biztosító felülettel (easy access bar, EAB), amely szinte magától értetődő és gyors kezelést tesz lehetővé.
Ezen a felületen négy irányban mozoghat, és minden irányhoz általában két kapcsolóállás tartozik.
Csak a C sorozat tagjai működnek ettől eltérően.

A C sorozat tagjain és még néhány kijelzőn a cellákhoz két gomb is tartozik: a felső a formázási információ lekérdezésére szolgál.
Ha a C sorozat tagjain egyidejűleg megnyom egy cellához tartozó felső gombot, és használja az EAB felületet, akkor ezzel szimulálhatja az EAB-on a második kapcsolóállást.
A bal, jobb, fel, le gomb (vagy az EAB) lenyomásával és nyomva tartásával a hozzájuk tartozó művelet ismételtethető.

Ezeken a kijelzőkön általában az alábbi gombokat találja:

| Elnevezés |hol található|
|---|---|
|l1 |elülső bal oldali gomb|
|l2 |hátsó bal oldali gomb|
|r1 |elülső jobb oldali gomb|
|r2 |hátsó jobb oldali gomb|
|up |fel, első állás|
|up2 |fel, második állás|
|left |balra, első állás|
|left2 |balra, második állás|
|right |jobbra, első állás|
|right2 |jobbra, második állás|
|dn |le, első állás|
|dn2 |le, második állás|

Az NVDA-val az alábbi Papermeier parancsbillentyűket használhatja:
<!-- KC:beginInclude -->

| Parancs |Parancsbillentyű|
|---|---|
|Léptetés visszafelé |left|
|Léptetés előre |right|
|A kijelző az előző sort mutatja |up|
|A kijelző a következő sort mutatja |dn|
|Braille cella aktiválása |cellákhoz tartozó gombok|
|Megmutatja az áttekintő kurzornál lévő karaktert |l1|
|Aktiválja a navigátor kurzornál lévő elemet |l2|
|A braille követi |r2|
|Kiírja az ablak címét |l1+up|
|Megjeleníti az állapotsort |l2+down|
|Az aktuális elemet magában foglaló elemhez lép |up2|
|Az első olyan elemhez lép, ami benne van az aktuális elemben |dn2|
|Az előző elemhez lép |left2|
|A következő elemhez lép |right2|
|Kiírja az adott cellához tartozó formázási információt |cellához tartozó felső gomb|

<!-- KC:endInclude -->

### Papenmeier Braille BRAILLEX régebbi modellek {#toc250}

A következő Braille kijelzők támogatottak:

* BRAILLEX EL 80, EL 2D-80, EL 40 P
* BRAILLEX Tiny, 2D Screen

Megjegyzés: ezek a kijelzők csak soros port használatával csatlakoztathatóak.
Így ki kell jelölnie azt a portot ahová a kijelzőt csatlakoztatta,  miután ezt az illesztőprogramot kiválasztotta a Braille Beállítások párbeszédpanelen.
Ezen eszközök közül néhány rendelkezik egy egyszerű hozzáférési sávval (EAB Easy Access Bar), mely intuitív és gyors működést tesz lehetővé.
A sáv négy irányba mozgatható, melyeken belül általában két kapcsoló található.
A fel, le, jobbra vagy balra gombok lenyomásával és lenntartásával, vagy az EAB-bal a kapcsolódó művelet megismételtethető.
A régebbi eszközök nem tartalmaznak ilyen sávot. Azokon az első gombok használhatóak az EAB helyett.
Általában a következő billentyűk találhatóak a Braille kijelzőkön:

| Név |Billentyű|
|---|---|
|l1 |Bal első gomb|
|l2 |Bal hátsó gomb|
|r1 |Jobb első gomb|
|r2 |Jobb hátsó gomb|
|up |1 lépés felfelé|
|up2 |2 lépés felfelé|
|left |1 lépés balra|
|left2 |2 lépés balra|
|right |1 lépés jobbra|
|right2 |2 lépés jobbra|
|dn |1 lépés lefelé|
|dn2 |2 lépés lefelé|

A következők az NVDA Papenmeier parancshozzárendelései
<!-- KC:beginInclude -->
EAB-ot tartalmazó kijelzők:

| Név |Billentyű|
|---|---|
|A Braille kijelzés görgetése visszafelé |left|
|A Braille kijelzés görgetése előre |right|
|A Braille kijelzés mozgatása az előző sorra |up|
|A Braille kijelzés mozgatása a következő sorra |dn|
|Áthelyezés a Braille cellához |routing|
|Aktuális karakter bejelentése |l1|
|A navigátor kurzornál lévő objektum aktiválása |l2|
|Cím bejelentése |l1up|
|Státuszsor bejelentése |l2down|
|Mozgatás a tartalmazó objektumhoz |up2|
|Mozgatás az első tartalmazott objektumhoz |dn2|
|Mozgatás a következő objektumhoz |right2|
|Mozgatás az előző objektumhoz |left2|
|Kiírja az adott cellához tartozó formázási információt |Upper routing row|

BRAILLEX Tiny:

| Név |Billentyű|
|---|---|
|Az aktuális karakter bejelentése az áttekintő módban |l1|
|A navigátor kurzornál lévő objektum aktiválása |l2|
|A Braille kijelzés görgetése visszafelé |left|
|A Braille kijelzés görgetése előre |right|
|A Braille kijelzés mozgatása az előző sorra |up|
|A Braille kijelzés mozgatása a következő sorra |dn|
|A Braille követés ki- és bekapcsolása |r2|
|Mozgatás a tartalmazó objektumra |r1+up|
|Mozgatás az első tartalmazott objektumra |r1+dn|
|Mozgatás az előző objektumra |r1+left|
|Mozgatás a következő objektumra |r1+right|
|Kiírja az adott cellához tartozó formázási információt |Upper routing strip|

BRAILLEX 2D Screen:

| Név |Billentyű|
|---|---|
|Aktuális karakter bejelentése az áttekintő módban |l1|
|A navigátor kurzornál lévő objektum aktiválása |l2|
|A Braille követés ki- és bekapcsolása |r2|
|Kiírja az adott cellához tartozó formázási információt |upper routing strip|
|A Braille kijelzés mozgatása az előző sorra |up|
|A Braille kijelzés görgetése visszafelé |left|
|A Braille kijelzés görgetése előre |right|
|A Braille kijelzés mozgatása a következő sorra |dn|
|Mozgatás a következő objektumra |left2|
|Mozgatás a tartalmazó objektumra |up2|
|Mozgatás az első tartalmazott objektumra |dn2|
|Mozgatás az előző objektumra |right2|

<!-- KC:endInclude -->

### HumanWare BrailleNote {#toc251}

Az NVDA támogatja a Humanware BrailleNote jegyzetelőket [https://www.humanware.com] képernyőolvasóhoz történő kijelző terminálként való használat során.
A következő tipusok támogatottak:

* BrailleNote Classic (Csak soros kapcsolattal)
* BrailleNote PK (Soros és Bluetooth kapcsolattal)
* BrailleNote MPower (Soros és Bluetooth kapcsolattal)
* BrailleNote Apex (USB és Bluetooth kapcsolattal)

A BrailleNote Touch támogatásához nézze meg a [Brailliant BI Sorozat / BrailleNote Touch](HumanWareBrailliant) szekciót.

Ha az eszköze egynél több csatlakozási módot támogat, az NVDA-hoz való csatlakoztatás során meg kell adnia a Braille terminál portot a Braille terminál beállításoknál (Braille terminal options).
A részletekért kérjük olvassa át a BrailleNote kézikönyvét.

Az NVDA Braille beállítások párbeszédpanelén valószínűleg szintén ki kell választania a használni kívánt portot.
Ha az eszközt USB vagy Bluetooth kapcsolat segítségével csatlakoztatja, a portot beállíthatja az "Automatikus", "USB" vagy "Bluetooth" értékek valamelyikére, függően az elérhető lehetőségektől.
Ha az előzőek közül egyik lehetőség sem jelenik meg, esetleg szabvány soros port, vagy egy USB-soros port átalakító segítségével csatlakoztatja az eszközt, a hardveres portok listájából pontosan ki kell választani a használni kívánt portot.

A BrailleNote Apex USB kapcsolaton történő használata előtt telepítenie kell a HumanWare által kiadott illesztőprogramokat.
A következő BrailleNote parancshozzárendelések használhatók az NVDA programban
Az egyes billentyűk elhelyezkedésével kapcsolatosan kérjük tekintse át a BrailleNote dokumentációját.
<!-- KC:beginInclude -->

| Név |Billentyű|
|---|---|
|A Braille kijelzés görgetése visszafelé |back|
|A Braille kijelzés görgetése előre |advance|
|A Braille kijelzés mozgatása az előző sorra |previous|
|A Braille kijelzés mozgatása a következő sorra |next|
|Áthelyezés Braille cellához |routing|
|A Braille követés ki- és bekapcsolása |previous+next|
|Felfelé nyílbillentyű |Szóköz+1-es pont|
|Lefelé nyílbillentyű |Szóköz+4-es pont|
|Balra nyílbillentyű |Szóköz+3-as pont|
|Jobbra nyílbillentyű |Szóköz+6-os pont|
|Page up billentyű |Szóköz+1-es pont+3-as pont|
|Page down billentyű |Szóköz+4-es pont+6-os pont|
|Home billentyű |Szóköz+1-es pont+2-es pont|
|End billentyű |Szóköz+4-es pont+5-ös pont|
|Control+home |Szóköz+1-es pont+2-es pont+3-as pont|
|Control+end |Szóköz+4-es pont+5-ös pont+6-os pont|
|Space billentyű |Szóköz|
|Enter billentyű |Szóköz+8-as pont|
|Backspace billentyű |Szóköz+7-es pont|
|Tab billentyű |Szóköz+2-es pont+3-as pont+4-es pont+5-ös pont (Szóköz+t)|
|Shift+tab |Szóköz+1-es pont+2-es pont+5-ös pont+6-os pont|
|Windows billentyű |Szóköz+2-es pont+4-es pont+5-ös pont+6-os pont (Szóköz+w)|
|Alt billentyű |Szóköz+1-es pont+3-as pont+4-es pont (Szóköz+m)|
|Beviteli súgó ki- és bekapcsolása |Szóköz+2-es pont+3-as pont+6-os pont (Szóköz+h lecsúsztatva)|

<!-- KC:endInclude -->

### EcoBraille {#toc252}

Az NVDA támogatja az Once-féle EcoBraille kijelzőket [ONCE](https://www.once.es/).
A következő modelleket támogatják:

* EcoBraille 20
* EcoBraille 40
* EcoBraille 80
* EcoBraille Plus

Az NVDA-ban a braille beállítások párbeszédpanelen beállítható a soros port, melyhez a kijelző kapcsolódik.

Az Eco Braille kijelzők billentyűparancsai a következők.
Kérjük, tanulmányozza az [Eco Braille kijelzők dokumentációit](ftp://ftp.once.es/pub/utt/bibliotecnia/Lineas_Braille/ECO/) a leírásokért, ahol e billentyűparancsok találhatók.

<!-- KC:beginInclude -->

| Név |Billentyű|
|---|---|
|A braille kijelző visszagörgetése |T2|
|A braille kijelző előregörgetése |T4|
|A braille kijelző előző sorra léptetése |T1|
|A braille kijelző következő sorra léptetése |T5|
|Út a braille cellához |Routing|
|A navigátor kurzor alatti jelenlegi elem aktiválása |T3|
|Átkapcsolás a következő megjelenítési módra |F1|
|Lépés a szülőelemre |F2|
|Átkapcsolás az előző áttekintési módra |F3|
|Lépés az előző elemre |F4|
|A jelenlegi elem megjelenítése / jelentése |F5|
|Lépés a következő elemre |F6|
|Lépés a fókuszban lévő elemre |F7|
|Lépés az első szülőelemre |F8|
|A kurzor vagy a fókusz mozgatása a jelenlegi megtekintési pozícióba |F9|
|Az áttekintőkurzor helyének jelentése=megjelenítése |F0|
|A braille kurzor követése |A|

<!-- KC:endInclude -->

### SuperBraille {#toc253}

A főként tajvanon használt SuperBraille USB-n és soros porton keresztül egyaránt csatlakoztatható. Mivel a SuperBraille nem rendelkezik fizikai beviteli gombokkal, sem görgetőgombokkal, a bevitelhez hagyományos billentyűzetre van szükség. Ezen felül, a Tajvanon elérhető képernyőolvasókkal való kompatibilitás miatt, szükség van a kijelző görgetésére. Ez az alábbi parancsokkal lehetséges:
<!-- KC:beginInclude -->

| Név |Billentyű|
|---|---|
|braille kijelző visszafelé görgetése |numpadMinusz|
|braille kijelző előre görgetése |numpadPlusz|

<!-- KC:endInclude -->

### BRLTTY {#toc254}

A [BRLTTY](https://www.brltty.com/) egy különálló program, amely számos braille kijelzőt támogat. A használatához fel kell telepítenie a [BRLTTY Windows-os változatát](https://www.brltty.com/download.html).
Töltse le az ezen az oldalon található legfrissebb verziót (pl. brltty-win-4.2-2.exe). A kijelző beállításaikor figyeljen oda, hogy melyik portot használja. Ugyanis ez gyártónként változhat, különösen ha USB-s, és már fenn vannak a hozzátartozó driverek.
Alább a BRLTTY billentyűparancsait olvashatja, a kijelzők helyes beállításához kérjük olvassa el a [BRLTTY ide tartozó dokumentációját](https://mielke.cc/brltty/doc/KeyBindings/):

<!-- KC:beginInclude -->

| Leírás |BRLTTY billentyűparancs|
|---|---|
|Egy kijelzőnyivel visszalép |fwinlt|
|Egy kijelzőnyivel előrelép |fwinrt|
|A kijelzőt az előző sorhoz helyezi |lnup|
|A kijelzőt a következő sorhoz helyezi |lndn|
|A kurzor az aktuális braille cellához helyezése |route|

<!-- KC:endInclude -->

## Braille vezérlőtípus- és állapotrövidítések {#toc255}

Ahhoz, hogy a braille kijelzőn minél több információ elférjen, a következő rövidítéseket alkalmazzuk a vezérlőelemek típusának és állapotának a feltüntetésére.

| Rövidítés |Vezérlő típus|
|---|---|
|gb |gomb|
|klm |kombinált lista|
|jn |jelölőnégyzet|
|pbp |párbeszédpanel|
|szm |szerkesztőmező|
|ábra |kép|
|oN |táblázat oszlopszáma , pl. o1, o2.|
|sN |táblázat sorszáma , pl. s1, s2.|
|cN |címsorszint, pl. c1, c2.|
|hv |hivatkozás|
|lm |lista|
|mhv |meglátogatott hivatkozás|
|mnü |menü|
|mnüs |menüsor|
|rgb |választógomb|
|tbl |táblázat|
|fn |fanézet|
|N szt |a fanézet elemének hierarchikus szintjét mutatja N||
|`-----` |elválasztó|

Továbbá a következő állapotjelzőket alkalmazzuk:

| Rövidítés |Vezérlőelem állapota|
|---|---|
|... |Jelzi, ha egy elem támogatja az automatikus kiegészítést|
|⣏⣀⣹ |jelzi, ha egy elem (pl. egy jelölőnégyzet) - nincs bejelölve|
|⣏⣿⣹ |jelzi, ha egy elem (pl. egy jelölőnégyzet) be van jelölve|
|⣏⣸⣹ |jelzi, ha egy elem (pl. egy jelölőnégyzet) félig van bejelölve|
|⢎⣿⡱ |jelzi, ha egy elem (pl. egy többállapotú gomb) le van nyomva|
|⢎⣀⡱ |jelzi, ha egy elem (pl. egy többállapotú gomb) nincs lenyomva|
|- |jelzi, ha egy elem (pl. egy fanézetelem) összecsukható|
|+ |jelzi, ha egy elem (pl. egy fanézetelem) kiterjeszthető|
|kat |jelzi, ha egy elem kattintható|
|ol |jelzi, ha egy elem (pl. egy szerkesztőmező) csak olvasható|
|kv |jelzi, ha egy elem ki van jelölve|
|almenü |jelzi, ha egy elemnek van felugró további eleme (általában egy almenü)|

## Haladó témák {#toc256}
### Parancssori beállítások {#CommandLineOptions}

Az NVDA képes elfogadni egy vagy több olyan beállítást, mely az NVDA indulásakor módosítja a program működését.
Annyi beállítást adhat meg, amennyire csak szüksége van.
Ezeket a beállításokat az NVDA parancsikonjának tulajdonságlapján a parancsmezőben, a Windows futtatás (windows r) párbeszédpanelének parancsmezőjében, vagy a parancssorban lehet megadni.
A beállítási lehetőségeket az NVDA futtatható programfájljának nevétől és egymástól szóközzel kell elválasztani.
Például: az NVDA parancsikonjában, amely a telepítéskor keletkezik, benne van az -r kapcsoló, mely az NVDA-t arra utasítja, hogy zárja be a futó példányt, mielőtt az újat megnyitná.
Egy másik hasznos beállítás a --disable-addons, amely az NVDA-t arra utasítja, hogy minden futó bővítményt állítson le.
Ez a beállítás lehetővé teszi, hogy megállapítsuk, hogy egy problémát egy bővítmény okoz-e, és ha igen, azt elháríthassuk.
Például: a futtatás ablakban a következő parancs kiadásával kiléphet a futó NVDA-ból:

nvda -q

Egyes beállítások megadhatók rövid és hosszú változatban, mások csak hosszú változatban. Azoknál, amelyeknél van rövid és hosszú változat, ezek tetszőlegesen használhatók, például így:

|nvda -rm |Ez kilép az NVDA jelenleg futó példányából, majd elindítja az NVDA egy új példányát bejelentkező hangok és egyebek nélkül, stb.|
|nvda -rm --disable-addons |Ugyanaz, mint a fenti, csak a bővítményeket is tiltja.|

Egyes parancssori beállítások elfogadnak megadható paramétereket, mint a naplózás részletessége, a konfigurációs mappa helye. Ezeket a paramétereket a rövid változat esetén szóközzel, hosszú változat esetén egyenlőségjellel (=)  kell a beállítás után írni, például:

|nvda -l 10 |Arra utasítja az NVDA-t, hogy a naplózás szintje a nyomkövetés legyen.|
|nvda --log-file=c:\nvda.log |Arra utasítja az NVDA-t, hogy a naplóját a c:\nvda.log fájlba írja.|
|nvda --log-level=20 -f c:\nvda.log |Arra utasítja az NVDA-t, hogy a naplózási szintje az információ legyen, a naplóját a c:\nvda.log fájlba írja.|

Az NVDA parancssori beállításai a következők:

| Rövid |Hosszú |Leírás|
|---|---|---|
|-h |--help |Ismerteti a parancssori beállításokat és kilép|
|-q |--quit |Kilép az NVDA éppen futó példányából|
|-r |--replace |Kilép az NVDA aktuálisan futó példányából, és újat indít|
|-k |--check-running |Kilépési kóddal jelentést ad arról, hogy az NVDA fut-e. Ha fut, a kilépési kód 0, ha nem fut, 1.|
|-f NAPLÓFÁJLNÉV |--log-file=NAPLÓFÁJLNÉV |Megadja a naplófájlt, amibe az NVDA a naplóját írja|
|-l NAPLÓZÁSSZINT |--log-level=NAPLÓZÁSSZINT |A naplózott üzenetek legalacsonyabb szintje (nyomkövetés 10, információ 20, figyelmeztetés 30, hiba 40, kritikus hiba 50), az alapértelmezett a figyelmeztetés|
|-c BEÁLLÍTÁSMAPPA |--config-path=BEÁLLÍTÁSMAPPA |Annak a mappának az útvonala, ahol az NVDA a beállításait tárolja|
|-m |--minimal |Hang, interfész, üzenet stb. nélkül indul|
|-s |--secure |Biztonsági mód (tiltja a Python konzolt)|
|Nincs |--disable-addons |Nem indulnak el a bővítmények|
|Nincs |--debug-logging |Nyomkövetés naplózási szint engedélyezése kizárólag az NVDA legközelebbi bezárásáig. Ez a beállítás felülír minden más a naplózási szinttel kapcsolatos parancssori kapcsolót ( --loglevel, -l).|
|Nincs |--no-sr-flag |Nem változtatja meg a globális képernyőbeállítás jelölőnégyzetének állapotát|
|Nincs |--install |Telepíti az NVDA-t, majd a telepített verzió elindul.|

### Rendszerparaméterek {#SystemWideParameters}

A Beállítás-szerkesztő tartalmaz olyan paramétereket, melyek kihatással vannak az NVDA viselkedésére.
Ezek a paraméterek az alábbi kulcsoknál találhatók:

* 32-bites rendszer: "HKEY_LOCAL_MACHINE\SOFTWARE\nvda"
* 64-bites rendszer: "HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\nvda"

Az alábbi értékek beállítására van lehetőség:

| Név |Típus |Lehetséges értékek |Leírás|
|---|---|---|---|
|configInLocalAppData |DWORD |0: letiltás (Alapértelmezett érték), 1: Engedélyezés |Ha engedélyezve van, akkor az NVDA a felhasználói beállításokat a helyi application data mappában tárolja, és nem a roaming mappában|
|serviceDebug |DWORD |0: Letiltás (Alapértelmezett), 1: Engedélyezés |Ha engedélyezve van, akkor a Windows biztonsági képernyőin a biztonságos mód letiltásra kerül, így használható a  Python konzol és a Naplónéző. Komoly biztonsági kockázatok miatt az opció engedélyezése nem ajánlott.|

### Az írásjelek haladó testreszabása {#toc259}

Az írásjelek és egyéb szimbólumok egyénileg testreszabhatóak, azon túl ami az NVDA [Írásjel Kiejtés](#SymbolPronunciation) párbeszédablakában megadható.
Beállíthatja, hogy egy adott írásjel átadódjon a beszédszintetizátornak (pl. szünet vagy hangsúly megadásához), valamint egyéni szimbólumokat is létrehozhat.

Ehhez az NVDA írásjel konfigurációs fájl szerkesztése szükséges, melyet az NVDA felhasználói beállítások könyvtárában talál.
A fájl neve symbols-xx.dic, ahol xx a nyelvi kódot helyettesíti (pl. hu).
A fájl formája az NVDA fejlesztői útmutatójának Írásjelkiejtés fejezetében található, olvassa el hozzá az [[NVDA fejlesztői dokumentációt](https://community.nvda-project.org/wiki/Development).
Érdemes megjegyezni, hogy összetett szimbólumok megadása jelenleg nem lehetséges.

## További információk {#toc260}

Mivel az NVDA-t folyamatosan frissítik, nem lehet szavatolni, hogy az e felhasználói kézikönyvben írott útmutatások mindegyike alkalmazható lesz. Ha bármilyen észrevétele van az e kézikönyvben írott útmutatásokkal kapcsolatban, kérjük, magyar nyelvű javaslata, kérése, kérdése esetén látogassa meg az: [NVDA Honosítási project](https://www.nvda.hu) weboldalát, angol nyelvű kérés, kérdés, javaslat esetén pedig az [NVDA hivatalos weboldalát](https://www.nvda-project.org/) további segítségért.

## Fogalom meghatározások {#toc261}

Ebben a dokumentumban a következő fogalmakon az alábbi meghatározásokat értjük:

* Numerikus billentyűzet: A billentyűzet elkülönülő részén lévő, számok bevitelére, műveletek végzésére szolgáló billentyűzetrész, notebookokon a notebook billentyűzet jobb oldalán, általában az "M", "J", "U" betűktől indulva, rendszerint az FN-numlock bekapcsolásával érhető el. ez esetben a numerikus billentyűzet kurzorvezérlő vagy numerikus billentyűzetként viselkedik attól függően, hogy a numlock be van-e kapcsolva. Ideiglenesen az FN nyomvatartásával is használhatja. Szükség esetén külön, erre a célra készített billentyűzetet is csatlakoztathat notebookjához.
* FN-billentyű: A notebook (hordozható számítógép) olyan speciális billentyűje, amellyel a notebookon nem lévő billentyűket hívhat elő más billentyűkkel együtt, illetve más billentyűkkel együtt használva a hordozható számítógép speciális funkcióit érheti el (pl. hibernálás, készenlét, monitor kikapcsolása).
* NVDA gomb: Beállítástól függően a capslock (nagybetűzár), a normál insert, valamint a numerikus billentyűzeten lévő insert. Mind a három egyszerre is használható. Segítségükkel, más billentyűkkel együtt, az NVDA speciális billentyűparancsait érheti el.
* NVDA menü: Az NVDA+N billentyűparancsra előugró, az NVDA képernyőolvasó program speciális menüje.
* alfanumerikus, vagy normál billentyűzet: Tartalmazza az összes betűt, írás- és műveleti jelet, számot, számítógépvezérlő- és parancsbillentyűket, beleértve a funkcióbillentyűket, az enter és escape billentyűket, szövegszerkesztő és más hasonló billentyűket is.
* Kiterjesztett billentyűzet: A normál billentyűzetnek az a része, amely a szerkesztő és kurzormozgató billentyűket tartalmazza, ide tartoznak pl.: a nyilak, a home és end, page up / down, a normál insert és normál del, a printscreen, pause / break és a scroll lock.
* Beszédszintetizátor: Olyan szoftver, illetőleg hardver vagy szoftver együttese, amely az elektronikus szöveget az emberi beszédhez hasonló, a kiválasztott nyelv szabályai szerint képezett, hangzó beszéddé alakítja és valamilyen hangeszközön, leggyakrabban hangkártyán megjeleníti.
* Braille kijelző: Olyan készülék, amely az elektronikus szöveget a pontírás szabályai szerint, kidomborodó, tapintható jelek sorozataként írja ki.
* Képernyőolvasó: Olyan szoftver, amely a vakok (és gyengénlátók) számára - a beszédszintetizátorra vagy a braille kijelzőre küldve - közli a számítógépen zajló és a képernyőn látható lényeges eseményeket.
* Interfész: Az alkalmazásoknak és az operációs rendszernek azon, rendszerint a képernyőn látható része, amely lehetővé teszi az alkalmazással, operációs rendszerrel való emberi kommunikációt.
* Elem: Az alkalmazás vagy az operációs rendszer interfészének olyan logikailag elkülönült része, amely meghatározott információt közöl vagy meghatározott vezérlőelemet vagy vezérlőelemeket tartalmaz.
* Vezérlőelem: Olyan elem, amelynek segítségével tetszőlegesen irányíthatja az alkalmazás működését.
* Virtuális kijelző: Olyan speciális memóriaterület (puffer), amelyre a képernyőolvasó az összetett dokumentumok (pl. html, pdf) leegyszerűsített, átalakított  képét másolja abból a célból, hogy azt egy látássérült felhasználó könnyebben áttekinthesse.
* Böngészőmód: A képernyőolvasó olyan módja, amely segítségével a dokumentum a virtuális kijelzőben olvasható.
* Fókuszmód: A képernyőolvasónak az a módja, amely közvetlenül lehetővé teszi a böngészőben vagy pdf-olvasóban megjelenő vezérlőelemek kezelését. E mód segítségével lehet űrlapokat (formokat) kitölteni, illetőleg egyéb vezérlő műveleteket végezni (pl. távoli szolgáltatások beállításai).
* Navigációs gyorsbillentyűk: A böngészőmódban használható olyan egybillentyűs parancsok, amelyek az összetett dokumentum meghatározott részére helyezik a képernyőolvasó virtuális (böngésző) kurzorát.
* parancsikon: olyan speciális fájl, amellyel anélkül indíthat el egy programot vagy végezhet el egy műveletet, hogy a program indítófájlját meg kellene keresnie vagy a művelet parancsait be kellene gépelnie.
* A futtatás ablak: A Windowsnak az a része, ahová begépelhet egy parancsot, iletve kitallózhat egy indítandó programot, ha ahhoz nem tartozik ikon.
* Parancssor: A Windows olyan speciális alrendszere, mely karakteres üzemmódú működést tesz lehetővé, és parancsok, kulcsszavak begépelésével teszi lehetővé a számítógép használatát. Az MS-Dos, az OS/2 és más rendszerek parancsait tartalmazza.
* Konzol (vagy parancssori) alkalmazás: Olyan karakteres üzemmódú alkalmazás, mely a parancssori alrendszerben (vagy konzolon) fut.
* Asztal: A Windows fő képernyője, rendszerint parancsikonokkal, a tálcával és a start gombbal.
* Start menü: A Windows speciális menüje, amelyben az asztalon el nem férő ikonokat találja mappákba (almenükbe) szervezve.
* Menü: Az operációs rendszer, illetve az alkalmazások olyan része, amelyekben hierarchikus struktúrában szervezve találja meg az adott alkalmazással vagy a rendszer adott részével végezhető műveleteket, parancsokat.
* Almenü: A menünek az az elágazó része, amely további almenüket vagy parancsokat tartalmaz.
* Menüparancs: A menünek az a része, amely közvetlenül valamilyen műveletet végez vagy párbeszédpanelt nyit meg. A párbeszédpanelt megnyitó parancsot "..." jelzi.
* Ablak: A képernyőnek egy meghatározott területe, amelyben adott alkalmazás, vagy annak része jelenik meg. Rendszerint saját címsort és saját menüt is tartalmaz.
* Párbeszédpanel: Olyan speciális, rendszerint kis méretű ablak, amely az operációs rendszer adott része vagy egy program beállításainak megváltoztatását vagy információk bevitelét teszi lehetővé.
* Szerkesztőmező: Olyan terület, amely szövegek, információk bevitelére szolgál. Lehet
* egysoros
* többsoros
* "rich text" (összetet formázást lehetővé tevő)
* csak olvasható: amelybe nem lehet írni, csak információt jelenít meg
* jelszó bevitelére alkalmas: amely a begépelt karakterek helyett csillagokat jelenít meg a képernyőn, de a programnak a valódi karaktersort adja át).
* Kombinált: írhat bele, de tetszés szerint a korábban beírt lehetőségeket is kiválaszthatja (az alt le nyíllal megnyitva, korábbi lehetőséget kiválasztva és az alt-felnyíllal bezárva).
* Léptető: a nyilakkal fel-le lépkedve automatikusan csökkenti vagy növeli a bele írt értéket, de ezt tetszés szerint át is írhatjuk.
* Jelzőpont: A weblap készítője által a látássérültek számára elhelyezett pont, ezek elősegítik a gyorsabb navigációt a weboldalakon.
* Beágyazott objektum: Adobe Flash vagy Sun Java alkalmazás
* Objektum: A windows minden, a képernyőn megjelenő eleme. Ez lehet vezérlőelem, elemek csoportosítására szolgáló elemcsoport, gördítősáv, ablak, menü, stb.
* Szülőobjektum: A hierarchikus elrendezésben egy objektumot tartalmazó objektum. Ez lehet egy listaelemet tartalmazó lista, egy gombokat tartalmazó eszköztár, stb.
* Gyermekobjektum: A hierarchikus elrendezésben egy objektum, amely része egy másik objektumnak.
* Csúszka: Olyan vezérlőelem, amelyet az egérrel tolva / húzva (vagy valamelyik nyílpáros, fel-le vagy jobbra-balra segítségével) egy adott értéket állíthat be.
* Gomb: Olyan vezérlőelem, amelyre kattintva (vagy a szóközt használva) azt "megnyomva" valamilyen funkciót érvényesít, pl. menti a változtatásokat, vagy elveti azokat, újabb párbeszédpanelt nyit meg, stb).
* Füles panel: A füles panel segítségével a képernyőn el nem férő, de egymáshoz szorosan kapcsolódó párbeszédpaneleket jeleníthet meg a fülre kattintva, a fülsoron jobbra-balra lépkedve és a szóközt megnyomva vagy a control-tabbal lapról lapra haladva.
* Jelölőnégyzet: Olyan vezérlőelem, mely két állapot között enged választani, az egérrel vagy a szóközzel jelölheti be vagy veheti ki a jelölést.
* választógomb (rádiógomb): Olyan gombsor, amely több választható lehetőség közül egyet enged kiválasztani, a nyilak segítségével válthatjuk.
* Lista: Olyan vezérlőelem, amely meghatározott rend szerint rendezi csoportba az ugyanolyan jellemzőkkel rendelkező objektumokat (pl. fájllista). A nyilakkal mozoghat benne, de rendszerint az elem kezdőbetűinek begépelésével az adott elemre vagy a hozzá legközelebb esőre ugrik.
* kombinált listamező: Olyan lista, amelyből egyszerre csak egy elem választható. Használjuk a biztonságosab kijelöléshez az alt le parancsot, ezzel megnyitva a listamezőt, jelölje ki a kívánt értéket, majd az alt felnyíllal zárja be. A változtatások ekkor lépnek életbe.
* Többes kijelölésű lista: Olyan lista, amelyben egyszerre több elem is kijelölhető. A shift+nyilakkal a szomszédos, a controllt nyomva tartva és a kívánt elemen szóközt nyomva az egymástól távol eső elemeket jelölheti ki. A controlt csak a kijelölések legvégén engedje fel.
* Fanézet: Olyan vezérlőelem, melyen sok elem közül lehet választani, ezért az elemek logikailag, hierarchikusan vannak elrendezve. A fanézet legyezőszerű, ágakra, alágakra és végpontokra bomlik, a végpontokon érhetőek el az egyes lehetőségek, pl. súgótémakörök. A fel-le nyíllal lépkedhet az ágakon, a jobbra nyíllal kinyithatjuk őket, a balra nyíl először a nyitott ág tetejére tér vissza, másodszor megnyomva a nyitott ágat bezárja.

