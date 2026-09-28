# Az Milli adatvédelmi szabályzata

**Hatálybalépés dátuma:** 2026. augusztus 1. **Utolsó frissítés:** 2026. szeptember 16.

## A rövid változat

Az Milli nem gyűjti az Ön adatait. Nincs Milli szerver, nincs elemzés, nincs reklám, nincs nyomon követés, és nincsenek harmadik féltől származó SDK-k. Minden, amit beír, az eszközén marad, és – csak ha bekapcsolja az iCloud szinkronizálást – a saját privát iCloud fiókjában, amelyhez nem tudunk hozzáférni.

## Kik vagyunk

Az Milli-et ("az alkalmazás") a **IVAN CAYABYAB** ("mi", "mi") fejlesztette ki.

Ha bármilyen kérdése van a szabályzattal vagy az Ön adataival kapcsolatban, lépjen kapcsolatba velünk a **ivnsjdev@gmail.com** telefonszámon.

## Mit és hol tárol az Milli

Az Milli egy személyes pénzügyi alkalmazás. A megadott információkat a készülék egy helyi adatbázisban tárolja. Soha nem kapjuk meg.

| Amit beírsz | Hol él | Látjuk? |
| --- | --- | --- |
| Tranzakciók, összegek, megjegyzések, dátumok | Az Ön készülékén | Nem |
| Számlák és főkönyvek | Az Ön készülékén | Nem |
| Kategóriák és költségvetések | Az Ön készülékén | Nem |
| Ismétlődő kifizetések és emlékeztetők | Az Ön készülékén | Nem |
| Ön által megadott fizetési referenciaadatok | Az Ön készülékén | Nem |
| Profilkép | Az Ön készülékén | Nem |
| Alkalmazásbeállítások és -beállítások | Az Ön készülékén | Nem |
| Az Apple Watch | oldalon megadott tranzakciók Az Apple Watch, majd az iPhone | Nem |

Nem gyűjtjük, továbbítjuk, eladjuk, béreljük vagy megosztjuk, mert az alkalmazás nem képes sehova elküldeni. Az Milli nem küld hálózati kéréseket az általunk vagy harmadik fél által üzemeltetett szerverekhez.

## iCloud szinkronizálás (opcionális)

Ha engedélyezi az iCloud szinkronizálást, az Milli az Apple CloudKit használatával másolja át adatait **saját iCloud-fiókja privát adatbázisába**, így azok megjelenhetnek a többi eszközén is, amelyen ugyanazzal az Apple Account-szel jelentkezett be.

- Ezeket az adatokat az Ön Apple Account tárolja, nem a miénk.
- Nem férünk hozzá, és nem tudjuk elolvasni, exportálni vagy visszaállítani.
- Az Apple ezeket az adatokat az alábbiak szerint dolgozza fel
  [Apple adatvédelmi szabályzat](https://www.apple.com/legal/privacy/).

Az iCloud szinkronizálást bármikor kikapcsolhatja az alkalmazás beállításaiban, vagy letilthatja az egész rendszerre vonatkozóan az eszköz **Settings → az Ön neve → iCloud** menüpontjában.

## Apple Watch

Az Milli tartalmaz egy Apple Watch app-et, amely a prémium szolgáltatások részeként érhető el, a mai adatok megtekintéséhez és a tranzakciók hozzáadásához a csuklójáról.

**Hogyan kerülnek oda az adatok.** Az óra alkalmazásnak nincs adatbázisa, nincs fiókja és nincs saját hálózati hozzáférése. Minden, amit mutat, közvetlenül a párosított iPhone-ről érkezik az Apple **WatchConnectivity**-ján keresztül, amely az iPhone és a vele párosított Apple Watch közötti rendszerkapcsolat. Ez a kapcsolat eszköz-eszköz, iOS és watchOS kezeli; nem megy át egyetlen szerverünkön sem, és semmilyen Milli adat nem érkezik hozzánk.

**A linken áthaladó dolgok.** Csak az, amire az óra képernyőjének szüksége van: az Ön fiókjai és azok nevei, ikonjai, színei és pénznemei; a mai tranzakciók és ezen számlák mai nettó száma; a kategóriák nevei és ikonjai; nyelvi és számformátum-beállításai; és hogy a prémium funkciók fel vannak-e oldva. A teljes tranzakciós előzményei, megjegyzései, költségvetései és profilképei az iPhone készüléken maradnak. A másik irányban az órán beírt tranzakció összegként, kategóriaként és számlaként az iPhone-re kerül, és ott elmentődik a főkönyvébe.

**Amit az óra megőriz.** Az óra az óra alkalmazás saját privát tárhelyén, magán tárhelyén tárolja a legutóbb kapott pillanatfelvételt, valamint minden olyan tranzakciót, amelyet az iPhone még nem erősített meg. Ez az, ami lehetővé teszi, hogy az alkalmazás valós számokon nyíljon meg, és így rögzítheti a kiadásokat, ha az iPhone hatótávolságon kívül esik. Bármi, amit beírt, amíg a kettő egymástól távol van, az órán marad, amíg az iPhone újra elérhetővé válik, majd átadják neki.

- Az óraalkalmazás **nem** használja az iCloud iCloud-et, és nem tárolja kívülről adatait
  az órát.
- Az óra alkalmazás **nincs** hálózati kéréseket.
- **nem** fér hozzá az egészségügyi, fitnesz-, pulzus-, edzés- vagy helyadatokhoz,
  és nem kér ilyen engedélyeket.

**Az óra másolatának eltávolításához** távolítsa el az Milli alkalmazást az óráról – az órán tartsa lenyomva az alkalmazás ikonját, és távolítsa el, vagy az iPhone készüléken nyissa meg a **Watch** alkalmazást, válassza ki az Milli lehetőséget, és kapcsolja ki az *Show App on Apple Watch* funkciót. Az óra párosításának megszüntetése törli az alkalmazásokat és azok adatait is.

## Face ID, Touch ID és jelkódzár

Ha engedélyezi az alkalmazás zárolását, az Milli megkéri az iOS-t, hogy hitelesítse Önt. Az Ön biometrikus adatait teljes egészében az Apple Secure Enclave kezeli, és **soha nem osztják meg az alkalmazással** – az iOS csak azt mondja meg az Milli-nek, hogy a hitelesítés sikeres volt-e vagy nem. Ha beállít egy alkalmazás-jelszót, azt csak az eszköz tárolja.

## Fényképezőgép és fotótár

Az Milli csak akkor kér hozzáférést a kamerához vagy a fotókönyvtárhoz, ha profilkép beállítása mellett dönt. A kép az eszközén van tárolva (és a saját iCloud készülékén, ha a szinkronizálás engedélyezve van). Az Milli nem tölt fel fényképeket sehova, és nem éri el a könyvtárát a háttérben.

## Értesítések

Ha engedélyezi az emlékeztetőket az ismétlődő fizetésekhez, az Milli ütemezi a **helyi értesítéseket** az eszközén. Ezeket az iOS generálja az eszközön. Nincs benne push szerver, és nem hagyja el az emlékeztető tartalom az eszközt.

## Vásárlások

Az Milli egyszeri alkalmazáson belüli vásárlást kínál a prémium funkciók feloldásához. A vásárlást teljes egészében az **Apple** dolgozza fel az App Store-en keresztül. Soha nem kapjuk meg fizetési adatait, kártyaszámát vagy számlázási címét. Az Milli csak azt kérdezi az Apple-től, hogy a jelenlegi Apple Account tulajdonosa-e a vásárlás, így tudja, hogy fel kell-e oldania a prémium funkciókat. Az Apple Watch app önmagában nem tudja megkérdezni az App Store-et, így az iPhone ugyanazon a privát linken keresztül közli vele, hogy a vásárlás feloldva van-e – egyetlen igen vagy nem érték, fizetési információ nélkül. A vásárlásokat az [Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/) szabályozza.

## Exportált biztonsági másolatok

Az Milli lehetővé teszi az adatok biztonsági másolatának exportálását. Az exportálás után a fájl az Ön ellenőrzése alatt áll, és ez a házirend már nem védi – bárhová menti vagy küldi (Fájlok, iCloud meghajtó, e-mail, más alkalmazás), az adott szolgáltatás feltételei érvényesek. A biztonsági másolatot úgy kezelje, mint a bankszámlakivonatot.

## Widgetek

Az Milli kezdőképernyőjének widgetjei beolvasnak egy kis mennyiségű adatot az alkalmazás és az eszközön lévő saját widget-bővítmény között megosztott privát tárterületről. A megosztott területen semmi sem kerül átvitelre az eszközről.

## Amit NEM csinálunk

Hogy egyértelmű legyen, az Milli **nem**:

- személyes vagy pénzügyi adatait gyűjteni vagy továbbítani nekünk
- analitikai, hibajelentési vagy telemetriai szolgáltatások használata
- tartalmazzon reklámot vagy reklámazonosítókat
- nyomon követheti Önt alkalmazásokban vagy webhelyeken, vagy megoszthat adatokat adatbrókerekkel
- felhasználói fiókok létrehozása, vagy e-mail cím, telefonszám vagy bejelentkezés szükséges
- egészségügyi, fitnesz- vagy helyadatok olvasása az iPhone vagy Apple Watch készülékről
- használja adatait a gépi tanulási modellek betanításához

Az Milli App Store adatvédelmi címkéje ezt tükrözi: **Data Not Collected (nem gyűjtött adatok)**.

## Támogassa a kommunikációt

Ha e-mailt küld nekünk támogatásért, megkapjuk e-mail-címét, üzenetét, valamint bármilyen eszközt, alkalmazásverziót, képernyőképet vagy egyéb olyan információt, amelyet megadni szeretne. Csak válaszadásra, a probléma kivizsgálására és az Milli fejlesztésére használjuk. Ne küldje el nekünk főkönyvét, kimutatásait vagy egyéb pénzügyi nyilvántartásait – nincs szükségünk rájuk a támogatási kérdés megválaszolásához.

Ahol a GDPR vagy az Egyesült Királyság GDPR vonatkozik, a támogatási leveleket azon jogos érdekünk alapján kezeljük, hogy válaszoljunk a hozzánk írt személyeknek, és kijavítsuk az általuk jelentett problémákat. Nincs más feldolgozás, aminek alapot kellene találni, mert az Milli önmagában semmit sem küld nekünk.

A támogatási e-mail nem kötelező, és az Milli-en kívül történik. Ezt az Ön e-mail-szolgáltatója és a támogatási postafiókunkat üzemeltető Google dolgozza fel a [Google adatvédelmi irányelvei](https://policies.google.com/privacy) értelmében. A Google levelezőszerverei az Egyesült Államokban találhatók, így az Ön által nekünk küldött támogatási üzeneteket ott dolgozzuk fel. A támogatási üzeneteket legfeljebb 24 hónapig őrizzük meg, és csak akkor, ha azt jogi, biztonsági vagy nyilvántartási kötelezettség megköveteli. Az alábbi e-mail címre küldve kérhet minket, hogy töröljük a támogatási levelezését.

## Adatmegőrzés és törlés

Az Milli nem küld nekünk semmit, így nem tároljuk az Ön pénzügyi adatait, és nincs mit megőriznünk vagy törölnünk. Az egyetlen kivétel az Ön által nekünk küldendő támogatási e-mailek, amelyekről fentebb beszélünk.

- **Helyi adatok törléséhez:** törölje az alkalmazást az eszközről, vagy használja az alkalmazást
  saját visszaállítási/törlési lehetőségek.
- **Az adatok törléséhez az Apple Watch készüléken:** távolítsa el az Milli-et az óráról,
  a fenti Apple Watch szakaszban leírtak szerint.
- **A szinkronizált adatok törlése:** kapcsolja ki az iCloud szinkronizálást, és távolítsa el az alkalmazás adatait
  **Settings → az Ön neve → iCloud → Fióktárhely kezelése**.

Az alkalmazás törlése nem távolítja el automatikusan az iCloud-fiókjával már szinkronizált adatokat; ehhez használja a fenti lépést. Az iPhone alkalmazás törlésével eltávolítja az Apple Watch társát is.

## Az Ön jogai

Élethelyétől függően a GDPR, az Egyesült Királyság GDPR, a CCPA/CPRA vagy hasonló törvények értelmében jogai lehetnek – beleértve a személyes adataihoz való hozzáférés, helyesbítés, exportálás vagy törlés jogát, valamint azt a jogot, hogy ne érje hátrányos megkülönböztetés gyakorlása miatt.

Az Milli úgy lett megtervezve, hogy Ön közvetlenül gyakorolja ezeket a jogokat: adatai a saját eszközén és a saját iCloud fiókjában vannak, mindenkor az Ön ellenőrzése alatt. Nem tartunk másolatot, így nem tudunk másolatot készíteni, módosítani vagy törölni az Ön nevében. Nem adunk el és nem osztunk meg személyes adatokat, és soha nem is tettünk ilyet.

Ha úgy gondolja, hogy nem tettük eleget kötelezettségeinknek, a fenti címen fordulhat hozzánk, és joga van panaszt benyújtani a helyi adatvédelmi hatósághoz.

## Gyerekek

Az Milli nem gyermekeknek szól, és nem gyűjt tudatosan semmilyen információt senkitől, beleértve a 13 éven aluliakat (vagy az Ön országában ezzel egyenértékű alsó korhatárt). Mivel az alkalmazás egyáltalán nem gyűjt adatokat, ilyen információkat nem lehet továbbítani számunkra.

## A szabályzat változásai

Ha ez az irányelv megváltozik, frissítjük ezt az oldalt, és felülvizsgáljuk a fenti „Utolsó frissítés” dátumát. A lényeges változásokat az alkalmazás kiadási megjegyzései is feltüntetik. Javasoljuk, hogy rendszeresen ellenőrizze ezt az oldalt.

## Kapcsolat

Kérdések, aggályok vagy kérések:

**ivnsjdev@gmail.com**
