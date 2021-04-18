# Szoftverfejlesztés nagyvállalati környezetben beadandó
Komjáthy Benjamin (NK:C8RFH5)
- [Szoftverfejlesztés nagyvállalati környezetben beadandó](#szoftverfejlesztés-nagyvállalati-környezetben-beadandó)
  - [Első fejezet](#első-fejezet)
  - [Második fejezet](#második-fejezet)
  - [Harmadik fejezet](#harmadik-fejezet)
  - [Negyedik fejezet](#negyedik-fejezet)
  - [Ötödik fejezet](#ötödik-fejezet)
  - [Hatodik fejezet](#hatodik-fejezet)

## Első fejezet

Ha már szoftverfejlesztés, meg nagy vállalati környezet, akkor adódott bennem a kérdés, hogy miért ne írjam úgy, mintha tényleg egy céges projekt lenne. Az első ötlet az volt hogy akkor úgy vezetem végig, mintha egy Jira task lenne az egész, szóval most akkor vehetjük úgy, hogy megkaptam TODO-ban egy ticketet, legyen ez most az épp olvasott git repository neve. Beértem szépen a melóba, látom hogy rajtam van, akkor húzzuk át szépen In Progress-be és csináljuk. A git repository ötlet meg onnan jött, hogy akkor meg miért ne legyen már egyből verziókezelve az egész. Csináltam egy public repot, hogy akkor legyen szépen le is dokumentálva az egész. Persze élesben úgysem raknánk ki public-ra de ettől most tekintsünk el.
```bash
git clone https://github.com/bennydeep/szoftbeadando-muzli.git
cd szoftbeadando-muzli
code .
```
És most járunk itt, minden adott hogy készüljön a beadandó, az első fejezetet lassan lehet is felcommitolni.
A második fejezettől már ígérem érdekesebb lesz, csak fel akartam vázolni a miértjét, hogy miért is lett ilyen a beadandó amilyen.
```bash
git add .
git commit -m "elsofejezet done"
git push 
```

## Második fejezet

Közben rájöttem, hogy így githubon nem nagyon fog működni az oldalszámozás... De nembaj, remélem megelőlegezitek nekem hogy ez biztos lesz legalább három oldal. 

Na de térjünk a tárgyra, amiről mesélni szerettem volna. Maga az informatika már konkrétan nagyon kis korom óta érdekelt, már 6 évesen egy DOS-os gépen toltam a Wolfeinstein 3D-t. Általános iskolában is ilyen kezdetleges angol-info tagozatra jártam, volt persze minden féle office, még talán ECDL vizsgára is vittek minket minden ilyen húúdeérdekes dolog. Mellette meg volt ez a szokásos otthon kockulás, a mindenféle modem, router, telefon, tv, bármilyen ottoni tech eszköz javítás, tudod amikor reseteled a routert visszajön az internet, de a nagymamád úgy néz rád mint Dr. Strange-re hogy varázsolsz. Szóval így az átlag felhasználónál nagyobb tudás azért megvolt, de úgy túlzásba nem vitted ,hogy akkor most leülj kódolni vagy csinálj bármit hogy fejleszd magad ilyen téren, eltekintve persze attól az 1-2 sufni HTML oldaltól amire rá tudtad mondani, hogy NA ezt ÉN csináltam.

## Harmadik fejezet

Középsuliban sem igazán változott a helyzet, az indokolatlan kockulás persze ott már minden szabadidőt elvett, szokásos remek életpályamodell. Az előrehozott közép infó érettségit megcsináltam már 10.-ben, utána egy emelt infóval bepróbálkoztam még 12.-ben, de hát az a minimális C tudás amit infófakton összeszedtünk, az nem sok minden volt, így szóbelizni már el sem mentem, mert ígyis úgyis jobban jártam volna pont ügyileg a már meglévő közép-infó-érettségimmel. Meg volt az érettségi, felvettek az Óbudai Egyetemre mérnökinfóra.. Aha.. szép álom is volt. Egyszerűen túl nagy volt a váltás még éppen kiszállva a középiskolás padokból bele az Analízis, Nummat és hasonló remek tárgyak csodálatos világába belecsöppenni. Na meg persze lolozni kellett koliban sokat. Két-három hónap után inkább el is engedtem, elmentem diákmelózni, aztán félévkor inkább ki is iratkoztam.

## Negyedik fejezet

Elkezdtem egy rendszergazda OKJ-t, ott volt sok jó dolog, de szabadidőmben még ott sem foglalkoztam semmiféle érdemleges kódolással, önfejlesztéssel. Akkor még volt Flash, csináltunk játékot Flashben, menő volt. Utána dolgoztam egy évet bankban gyakornokként, szintén semmi önfejlesztés, de már legalább a Lolról leszoktam (nagyjából 8-9000 óra után.. ha ebben kódoltam volna...). Ééés átszoktam a Cocra, még több ezer órányi fölösleges játékidő.. Ekkor már úgy voltam vele, hogy már ha a kis zsebpénz is meg van rá, csak vissza kéne menni egyetemre, de annyira nagyon progos irányba nem akartam elmenni, meg nem is mertem volna bevállalni egy programtervező infót, szóval így gazdinfó lett belőle, amit amúgy nem bántam meg, magával a szakkal nem volt semmi baj, viszont a programozást még itt sem szerettették meg velem. A gazdasági dolgokat még ígyis közelebb éreztem magamhoz, például a szakdogám is inkább kontrolling és vállalatirányítási rendszerek témakörben írtam, nem mertem volna bevállalni egy nagyon IT-s témát. Volt például BSc-n is egy ehhez a szabválhoz hasonló tárgyunk a "Szoftverfejlesztés és tesztelés", de ott is csak így az agilitás, elméleti dolgok, megnéztük a Jirát, de ott sem írtunk egy deka kódot sem.. Egy ilyen nevű tárgynál pedig azért lehet nem ártott volna. Úgy ámblokk az egész tanterv érdekesen volt összerakva, mindenbe belekóstoltunk, kicsit, de semmibe sem igazán. Lett egy IT-s diplomám, de még mindig nem volt semmi közöm semmifélre developer dologhoz.

## Ötödik fejezet

Kedves Olvasó! Már biztos nagyon érdekel, hogy mégis mire akarok kilyukadni, igazánból én is, de ígérem már lassan ott vagyunk.  

Felvettek MSc-re, ugyanúgy gazdinfón. Pont ennek a keretei között hallgatom most ezt a kurzust is. E mellett már mindenképp szerettem volna dolgozni, mármint úgy rendesen szakmában, hogy rendes IT-s szakmai tapasztalatom is legyen, ne csak az a sok elméleti. És itt jött el az igazán nagy fordulópont az ÉN és a szoftverfejlesztés kapcsolatában. Felvettek egy kis Startuphoz részmunkaidőben(akik amúgy elsősorben CloudOps-al foglalkoznak, szóval az első előadás mindenképp hasznos volt), ami teljesen jól beillett a mesteres órarendem mellé. Egyből mélyvíz, csináld ezt, csináld azt, tanuld ezt, tanuld azt, kódold le ezt, debuggold amazt, tanulj meg markdown írni, csinálj zeneszervert, tanuld meg a linuxot, csinálj céges ZSH configot, csinálj backend-et, csinálj webshopot, automatizáld az IOS developmentet Flutterben Bitrise-al, szóval konkrétan így teljesen intuitív módon rá vagy utalva hogy fejleszd magad és legyél hasznos a cégnek. És itt már tényleg azt érzed, hogy csinálsz valamit, van haszna, és már így szabadidőmben is sokkal jobban rá veszem magam hogy foglalkozzak vele, nézzek utána dolgoknak, képezzem magam.

## Hatodik fejezet

Valahogy az egyetemi oktatásba is jó lenne ezt beleimplementálni. Sokkal több gyakorlat kéne, és sokkal kevesebb elmélet, na meg az Óbudai Egyetemes kiruccanácomból is levonva a tanulságot, sokkal kevesebb matek. Tényleg hasznos ez is, a mindenbe belekóstolunk kicsit dolog, de ha valakinek nem lesz rá motivációja, hogy szabadidejében kódoljon, lásd én, még az informatika irányába is teljesen elvesztheti az érdeklődését, lelkesedését. Persze ez az érdeklődés, lelkesedés vesztés így most távoktatásban a tanárokra is kihat, nem lehet jó órákon át egy monitornak beszélni, főleg olyan előadásokon amikor a diákoktól is kevés vagy esetleg zéró az interakció. Mindenkinek nagyon rossz most ez a helyzet. De attól még köszönjük hogy megtartottátok például ti is nekünk ezeket az előadásokat! Egy élmény volt! Köszönöm a figyelmet, bárki is olvastad!
