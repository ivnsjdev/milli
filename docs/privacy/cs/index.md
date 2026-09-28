# Zásady ochrany osobních údajů pro Milli

**Datum účinnosti:** 1. srpna 2026
**Poslední aktualizace:** 16. září 2026

## Stručná verze

Milli neshromažďuje vaše údaje. Neexistuje žádný server Milli, žádná analytika, žádná
reklama, žádné sledování a žádné SDK třetích stran. Vše, co zadáte, zůstává ve vašem
zařízení a — pouze pokud zapnete synchronizaci s iCloud — ve vašem vlastním soukromém
účtu iCloud, ke kterému nemáme přístup.

## Kdo jsme

Milli („aplikace“) vyvíjí **IVAN CAYABYAB** („my“).

V případě jakéhokoli dotazu ohledně těchto zásad nebo vašeho soukromí nás kontaktujte
na **ivnsjdev@gmail.com**.

## Co Milli ukládá, a kde

Milli je aplikace pro osobní finance. Informace, které zadáte, se ukládají ve vašem
zařízení v místní databázi. Nikdy je nezískáváme.

| Co zadáváte | Kde se to nachází | Vidíme to my? |
| --- | --- | --- |
| Transakce, částky, poznámky, data | Ve vašem zařízení | Ne |
| Účty a účetní knihy | Ve vašem zařízení | Ne |
| Kategorie a rozpočty | Ve vašem zařízení | Ne |
| Opakované platby a připomenutí | Ve vašem zařízení | Ne |
| Referenční mzdové údaje, které zadáte | Ve vašem zařízení | Ne |
| Profilová fotka | Ve vašem zařízení | Ne |
| Nastavení a předvolby aplikace | Ve vašem zařízení | Ne |
| Transakce, které zadáte na Apple Watch | Na vašich Apple Watch, poté na vašem iPhonu | Ne |

Nic z toho neshromažďujeme, nepřenášíme, neprodáváme, nepronajímáme ani nesdílíme,
protože aplikace nemá žádnou možnost cokoli kamkoli odeslat. Milli neprovádí žádné
síťové požadavky na žádný server provozovaný námi ani třetí stranou.

## Synchronizace s iCloud (volitelná)

Pokud zapnete synchronizaci s iCloud, Milli použije Apple CloudKit ke zkopírování
vašich dat do **soukromé databáze vašeho vlastního účtu iCloud**, aby se mohla
zobrazit na vašich dalších zařízeních přihlášených ke stejnému Apple Account.

- Tato data se ukládají pod vaším Apple Account, nikoli naším.
- Nemáme k nim žádný přístup ani možnost je číst, exportovat nebo obnovit.
- Apple zpracovává tato data způsobem popsaným v dokumentu
  [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

Synchronizaci s iCloud můžete kdykoli vypnout v nastavení aplikace, nebo ji vypnout
pro celý systém v **Nastavení → vaše jméno → iCloud** na vašem zařízení.

## Apple Watch

Milli obsahuje aplikaci pro Apple Watch, dostupnou jako součást prémiových funkcí,
pro zobrazení dnešních čísel a přidávání transakcí přímo ze zápěstí.

**Jak se tam data dostávají.** Aplikace pro hodinky nemá vlastní databázi, účet ani
přístup k síti. Vše, co zobrazuje, přichází přímo z vašeho spárovaného iPhonu
prostřednictvím **WatchConnectivity** od Apple, systémového propojení mezi iPhonem
a Apple Watch s ním spárovanými. Toto propojení probíhá přímo mezi zařízeními,
řízené systémy iOS a watchOS; neprochází přes žádný náš server a žádná data Milli
se nám v žádném okamžiku neodesílají.

**Co putuje přes toto propojení.** Pouze to, co obrazovka hodinek potřebuje: vaše
účty a jejich názvy, ikony, barvy a měny; dnešní transakce a dnešní čistou částku
pro tyto účty; názvy a ikony vašich kategorií; vaše jazykové a číselné předvolby
formátu; a zda jsou odemčené prémiové funkce. Vaše kompletní historie transakcí,
poznámky, rozpočty a profilová fotka zůstávají na iPhonu. V opačném směru transakce,
kterou zadáte na hodinkách, putuje na iPhone jako částka, kategorie a účet, a tam
se uloží do vaší účetní knihy.

**Co si hodinky uchovávají.** Hodinky ukládají nejnovější snímek dat, který obdržely,
plus jakoukoli transakci, kterou jste zadali a kterou iPhone ještě nepotvrdil, ve
vlastním soukromém úložišti aplikace přímo na hodinkách. Díky tomu se aplikace
otevře s reálnými čísly a umožní vám zaznamenávat výdaje, i když je váš iPhone
mimo dosah. Cokoli je zadáno, zatímco jsou obě zařízení odděleně, zůstává uloženo
na hodinkách, dokud není iPhone opět dostupný, a poté je mu to doručeno.

- Aplikace pro hodinky **ne**používá iCloud a neuchovává žádnou kopii vašich dat
  mimo hodinky.
- Aplikace pro hodinky **ne**provádí žádné síťové požadavky.
- **Ne**přistupuje k údajům o zdraví, kondici, srdečním tepu, tréninku ani poloze
  a o taková oprávnění nežádá.

**Chcete-li odstranit kopii na hodinkách,** odinstalujte Milli z hodinek — na
hodinkách přidržte ikonu aplikace a odstraňte ji, nebo na iPhonu otevřete aplikaci
**Watch**, vyberte Milli a vypněte volbu *Show App on Apple Watch*. Odpárování
hodinek také vymaže jejich aplikace a data.

## Face ID, Touch ID a zámek kódem

Pokud zapnete zámek aplikace, Milli požádá iOS o vaše ověření. S vašimi biometrickými
údaji pracuje výhradně Secure Enclave od Apple a **nikdy nejsou sdíleny s aplikací**
— iOS sděluje Milli pouze to, zda ověření uspělo, nebo selhalo. Pokud nastavíte kód
aplikace, je uložen pouze ve vašem zařízení.

## Fotoaparát a knihovna fotografií

Milli žádá o přístup k fotoaparátu nebo knihovně fotografií pouze tehdy, když se
rozhodnete nastavit profilovou fotku. Obrázek se ukládá ve vašem zařízení (a ve
vašem vlastním iCloud, pokud je synchronizace zapnutá). Milli nikam nenahrává
fotografie a nepřistupuje k vaší knihovně na pozadí.

## Oznámení

Pokud zapnete připomenutí pro opakované platby, Milli naplánuje **místní oznámení**
ve vašem zařízení. Ta jsou generována přímo v zařízení systémem iOS. Nezapojuje se
žádný push server a žádný obsah připomenutí neopouští vaše zařízení.

## Nákupy

Milli nabízí jednorázový nákup v aplikaci pro odemčení prémiových funkcí. Nákup
zcela zpracovává **Apple** prostřednictvím App Store. Nikdy nezískáváme vaše
platební údaje, číslo karty ani fakturační adresu. Milli se Apple pouze ptá, zda
aktuální Apple Account vlastní tento nákup, aby věděla, zda má odemknout prémiové
funkce. Aplikace pro Apple Watch se App Store nemůže zeptat sama, takže jí iPhone
přes stejné soukromé propojení sdělí, zda je nákup odemčen — jedinou hodnotu
ano/ne, bez jakýchkoli platebních informací. Nákupy se řídí
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Zálohy, které exportujete

Milli vám umožňuje exportovat záložní soubor vašich dat. Jakmile jej exportujete,
tento soubor je pod vaší vlastní kontrolou a tyto zásady se na něj již nevztahují
— ať už jej uložíte nebo odešlete kamkoli (Files, iCloud Drive, e-mail, jiná
aplikace), řídí se podmínkami dané služby. Se záložním souborem zacházejte jako
s bankovním výpisem.

## Widgety

Widgety Milli na ploše čtou malé množství vašich dat ze soukromého úložného
prostoru sdíleného mezi aplikací a jejím vlastním rozšířením pro widgety ve vašem
zařízení. Nic z tohoto sdíleného prostoru se nepřenáší mimo zařízení.

## Co Milli NEDĚLÁ

Aby bylo jasno, Milli **ne**:

- shromažďuje ani nepřenáší vaše osobní nebo finanční údaje k nám
- používá služby analytiky, hlášení pádů ani telemetrie
- obsahuje reklamu ani reklamní identifikátory
- sleduje vás napříč aplikacemi nebo weby, ani nesdílí data s obchodníky s daty
- vytváří uživatelské účty ani nevyžaduje e-mailovou adresu, telefonní číslo nebo
  přihlášení
- čte údaje o zdraví, kondici ani poloze z vašeho iPhonu nebo Apple Watch
- používá vaše data k trénování modelů strojového učení

Štítek ochrany osobních údajů Milli v App Store to odráží: **Data Not Collected
(údaje nejsou shromažďovány)**.

## Podpůrná komunikace

Pokud nám napíšete e-mail kvůli podpoře, obdržíme vaši e-mailovou adresu, vaši
zprávu a jakékoli informace o zařízení, verzi aplikace, snímek obrazovky nebo jiné
informace, které se rozhodnete přiložit. Používáme je pouze k odpovědi, prošetření
problému a vylepšení Milli. Neposílejte nám prosím svou účetní knihu, výpisy ani
jiné finanční záznamy — nepotřebujeme je k zodpovězení dotazu na podporu.

Tam, kde se uplatňuje GDPR nebo UK GDPR, zpracováváme podpůrnou poštu na základě
našeho oprávněného zájmu odpovídat lidem, kteří nám píší, a řešit problémy, které
nahlásí. Neexistuje žádné jiné zpracování, pro které bychom museli hledat právní
základ, protože Milli nám z vlastní iniciativy nic neposílá.

E-mailová podpora je volitelná a probíhá mimo Milli. Zpracovává ji váš poskytovatel
e-mailu a Google, který hostuje naši podpůrnou schránku, podle
[Google Privacy Policy](https://policies.google.com/privacy). Poštovní servery
Google se nacházejí ve Spojených státech, takže podpůrná zpráva, kterou nám
pošlete, je zpracována tam. Podpůrné zprávy uchováváme až 24 měsíců, déle pouze
tam, kde to vyžaduje právní, bezpečnostní nebo archivační povinnost. Můžete nás
požádat o vymazání vaší podpůrné korespondence e-mailem na adresu níže.

## Uchovávání a mazání dat

Milli nám nic neposílá, takže neuchováváme žádná vaše finanční data a nemáme nic
k uchovávání ani mazání. Jedinou výjimkou je podpůrná pošta, kterou se rozhodnete
nám poslat, popsaná výše.

- **Chcete-li smazat místní data:** smažte aplikaci ze svého zařízení, nebo použijte
  vlastní možnosti resetu/smazání v aplikaci.
- **Chcete-li smazat data na Apple Watch:** odeberte Milli z hodinek, jak je
  popsáno výše v sekci Apple Watch.
- **Chcete-li smazat synchronizovaná data:** vypněte synchronizaci s iCloud a
  odeberte data aplikace v **Nastavení → vaše jméno → iCloud → Spravovat úložiště
  účtu**.

Smazání aplikace automaticky neodstraní data již synchronizovaná s vaším účtem
iCloud; k tomu použijte krok výše. Smazání aplikace na iPhonu také odstraní jejího
doprovodného průvodce na Apple Watch.

## Vaše práva

V závislosti na tom, kde žijete, můžete mít práva podle GDPR, UK GDPR, CCPA/CPRA
nebo podobných zákonů — včetně práva na přístup, opravu, export nebo smazání
vašich osobních údajů a práva nebýt diskriminováni za jejich uplatnění.

Milli je navrženo tak, abyste tato práva uplatňovali přímo: vaše data jsou ve
vašem vlastním zařízení a ve vašem vlastním účtu iCloud, pod vaší kontrolou po
celou dobu. Neuchováváme žádnou kopii, takže ji nemůžeme za vás vytvořit, upravit
ani vymazat. Neprodáváme ani nesdílíme osobní údaje a nikdy jsme to neudělali.

Pokud se domníváte, že jsme nesplnili naše povinnosti, můžete nás kontaktovat na
adrese výše a máte právo podat stížnost u místního úřadu pro ochranu osobních
údajů.

## Děti

Milli není určeno dětem a vědomě neshromažďuje žádné informace od nikoho, včetně
dětí mladších 13 let (nebo odpovídajícího minimálního věku ve vaší zemi). Vzhledem
k tomu, že aplikace vůbec neshromažďuje žádná data, nemohou nám být takové
informace předány.

## Změny těchto zásad

Pokud se tyto zásady změní, aktualizujeme tuto stránku a upravíme výše uvedené
datum „Poslední aktualizace“. Podstatné změny budou také uvedeny v poznámkách
k vydání aplikace. Doporučujeme vám tuto stránku pravidelně kontrolovat.

## Kontakt

Dotazy, připomínky nebo žádosti:

**ivnsjdev@gmail.com**
