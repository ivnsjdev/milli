# Integritetspolicy för Milli

**Gäller från:** 1 augusti 2026
**Senast uppdaterad:** 3 oktober 2026

## Kortversionen

Milli samlar inte in dina uppgifter. Det finns ingen Milli-server, ingen analys,
ingen reklam, ingen spårning och inga SDK:er från tredje part. Allt du skriver in
stannar på din enhet, och — endast om du aktiverar iCloud-synkronisering — i ditt
eget privata iCloud-konto, som vi inte har tillgång till.

## Vem vi är

Milli (”appen”) utvecklas av **IVAN CAYABYAB** (”vi”, ”oss”).

Om du har frågor om denna policy eller din integritet, kontakta oss på
**ivnsjdev@gmail.com**.

## Vad Milli lagrar, och var

Milli är en app för privatekonomi. Informationen du skriver in lagras på din
enhet i en lokal databas. Vi tar aldrig emot den.

| Vad du skriver in | Var det lagras | Ser vi det? |
| --- | --- | --- |
| Transaktioner, belopp, anteckningar, datum | På din enhet | Nej |
| Konton och huvudböcker | På din enhet | Nej |
| Kategorier och budgetar | På din enhet | Nej |
| Återkommande betalningar och påminnelser | På din enhet | Nej |
| Lönebenchmarksiffror du skriver in | På din enhet | Nej |
| Profilbild | På din enhet | Nej |
| Appinställningar och preferenser | På din enhet | Nej |
| Ord Milli lär sig av dina rättelser i chatten | På din enhet | Nej |
| Transaktioner du skriver in på Apple Watch | På din Apple Watch, sedan på din iPhone | Nej |

Vi samlar inte in, överför, säljer, hyr ut eller delar något av detta, eftersom
appen inte har någon möjlighet att skicka det någonstans. Milli gör inga
nätverksanrop till någon server som drivs av oss eller av tredje part.

## Smart Chat och intelligens på enheten

Millis **Smart Chat** låter dig registrera en transaktion genom att skriva in den
på vardagsspråk — ”kaffe 4,50” eller ”matvaror 62 i går” — och Milli räknar ut
beloppet, kategorin och datumet åt dig.

Allt detta sker **på din enhet**. Milli använder Apples intelligens på enheten
och de textfunktioner på enheten som är inbyggda i iOS, med en enkel regelbaserad
läsare som reserv när dessa inte är tillgängliga. Det finns ingen AI-server: ditt
meddelande läses på enheten och skickas aldrig till oss eller till någon tredje
part.

När du väljer eller korrigerar kategorin för en anteckning kommer Milli ihåg det
ordet så att samma anteckning sorterar sig själv nästa gång. Dessa inlärda
kopplingar mellan ord och kategori lagras endast på din enhet, tillsammans med
resten av dina uppgifter, och överförs aldrig. Du kan granska dem, och ta bort
vilka som helst av dem, i appen. Milli använder inte det du skriver, eller något
annat du matar in, för att träna någon maskininlärningsmodell.

## iCloud-synkronisering (valfritt)

Om du aktiverar iCloud-synkronisering använder Milli Apples CloudKit för att
kopiera dina uppgifter till den **privata databasen i ditt eget iCloud-konto**,
så att de kan visas på dina andra enheter som är inloggade med samma
Apple-konto.

- Dessa uppgifter lagras under ditt Apple-konto, inte vårt.
- Vi har ingen tillgång till dem och kan inte läsa, exportera eller återställa
  dem.
- Apple hanterar dessa uppgifter enligt beskrivningen i
  [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

Du kan när som helst stänga av iCloud-synkronisering i appens inställningar,
eller inaktivera den systemövergripande under **Inställningar → ditt namn →
iCloud** på din enhet.

## Apple Watch

Milli innehåller en Apple Watch-app, tillgänglig som en del av
premiumfunktionerna, för att visa dagens siffror och lägga till transaktioner
direkt från handleden.

**Hur uppgifterna kommer dit.** Klockappen har ingen databas, inget konto och
ingen egen nätverksåtkomst. Allt den visar kommer direkt från din ihopparade
iPhone via Apples **WatchConnectivity**, systemlänken mellan en iPhone och den
Apple Watch som är ihopparad med den. Den länken är direkt mellan enheterna,
hanterad av iOS och watchOS; den går inte via någon av våra servrar, och ingen
Milli-data skickas till oss vid något tillfälle.

**Vad som skickas över länken.** Endast det klockskärmen behöver: dina konton
och deras namn, ikoner, färger och valutor; dagens transaktioner och dagens
nettosiffra för dessa konton; dina kategorinamn och ikoner; dina inställningar
för språk och talformat; samt om premiumfunktionerna är upplåsta. Din
fullständiga transaktionshistorik, anteckningar, budgetar och profilbild
stannar på iPhonen. I andra riktningen skickas en transaktion du skriver in på
klockan till iPhonen som ett belopp, en kategori och ett konto, och sparas i
din huvudbok där.

**Vad klockan sparar.** Klockan lagrar den senaste ögonblicksbilden den
mottagit, samt eventuella transaktioner du har skrivit in som iPhonen ännu
inte har bekräftat, i klockappens egen privata lagring på själva klockan. Det
är detta som gör att appen öppnas med riktiga siffror, och låter dig
registrera utgifter, när din iPhone är utom räckhåll. Allt som skrivs in
medan de två är åtskilda hålls kvar på klockan tills iPhonen kan nås igen, och
levereras då till den.

- Klockappen använder **inte** iCloud, och har ingen kopia av dina uppgifter
  utanför klockan.
- Klockappen gör **inga** nätverksanrop.
- Den kommer **inte** åt hälso-, fitness-, puls-, träningspass- eller
  platsdata, och begär inga sådana behörigheter.

**För att ta bort klockans kopia,** avinstallera Milli från klockan — tryck
och håll in appikonen på klockan och ta bort den, eller öppna **Watch**-appen
på iPhonen, välj Milli och stäng av *Show App on Apple Watch*. Om du kopplar
bort klockan raderas även dess appar och deras data.

## Face ID, Touch ID och kodlås

Om du aktiverar applåset ber Milli iOS att autentisera dig. Din biometriska
data hanteras helt av Apples Secure Enclave och **delas aldrig med appen** —
iOS talar bara om för Milli om autentiseringen lyckades eller misslyckades.
Om du anger en appkod lagras den endast på din enhet.

## Kamera och fotobibliotek

Milli begär åtkomst till kameran eller fotobiblioteket endast när du väljer
att ställa in en profilbild. Bilden lagras på din enhet (och i ditt eget
iCloud, om synkronisering är aktiverad). Milli laddar inte upp foton
någonstans och kommer inte åt ditt bibliotek i bakgrunden.

## Aviseringar

Om du aktiverar påminnelser för återkommande betalningar schemalägger Milli
**lokala aviseringar** på din enhet. Dessa genereras på enheten av iOS. Ingen
push-server är inblandad och inget påminnelseinnehåll lämnar din enhet.

## Köp

Milli erbjuder ett engångsköp i appen för att låsa upp premiumfunktionerna.
Köpet hanteras helt av **Apple** via App Store. Vi tar aldrig emot dina
betalningsuppgifter, kortnummer eller faktureringsadress. Milli frågar bara
Apple om det aktuella Apple-kontot äger köpet, så att appen vet om
premiumfunktionerna ska låsas upp. Apple Watch-appen kan inte fråga App Store
på egen hand, så iPhonen talar om för den via samma privata länk om köpet är
upplåst — ett enda ja- eller nej-värde, utan någon betalningsinformation. Köp
regleras av
[Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Säkerhetskopior du exporterar

Milli låter dig exportera en säkerhetskopia av dina uppgifter. När du har
exporterat den är filen under din egen kontroll och denna policy skyddar den
inte längre — var du än sparar eller skickar den (Filer, iCloud Drive,
e-post, en annan app) styrs den av den tjänstens villkor. Behandla en
säkerhetskopia som du skulle behandla ett kontoutdrag.

## Widgetar

Millis widgetar på hemskärmen läser en liten mängd av dina uppgifter från ett
privat lagringsutrymme som delas mellan appen och dess egen widget-tillägg på
din enhet. Inget i det delade utrymmet överförs bort från enheten.

## Vad vi INTE gör

För att vara tydliga gör Milli **inte** följande:

- samlar in eller överför dina personliga eller finansiella uppgifter till oss
- använder analys-, kraschrapporterings- eller telemetritjänster
- innehåller reklam eller reklamidentifierare
- spårar dig mellan appar eller webbplatser, eller delar data med datamäklare
- skapar användarkonton, eller kräver en e-postadress, ett telefonnummer eller
  inloggning
- läser hälso-, fitness- eller platsdata från din iPhone eller Apple Watch
- skickar dina uppgifter till någon AI-tjänst, eller använder dem för att träna
  maskininlärningsmodeller — Smart Chat körs helt på din enhet

Millis integritetsmärkning i App Store återspeglar detta: **Data Not
Collected (uppgifter samlas inte in)**.

## Supportkommunikation

Om du mejlar oss för support tar vi emot din e-postadress, ditt meddelande
och eventuell information om enhet, appversion, skärmdump eller annat du
väljer att inkludera. Vi använder det endast för att svara, utreda problemet
och förbättra Milli. Skicka inte din huvudbok, dina kontoutdrag eller andra
finansiella uppgifter till oss — vi behöver dem inte för att besvara en
supportfråga.

Där GDPR eller UK GDPR gäller hanterar vi supportmejl med stöd av vårt
berättigade intresse av att svara de som skriver till oss och att åtgärda de
problem de rapporterar. Det finns ingen annan behandling att hitta en grund
för, eftersom Milli inte skickar något till oss på egen hand.

Support via e-post är valfritt och sker utanför Milli. Det behandlas av din
e-postleverantör och av Google, som är värd för vår supportbrevlåda, enligt
[Google Privacy Policy](https://policies.google.com/privacy). Googles
e-postservrar finns i USA, så ett supportmeddelande du skickar till oss
behandlas där. Vi sparar supportmeddelanden i upp till 24 månader, och längre
endast där en rättslig, säkerhetsmässig eller bokföringsmässig skyldighet
kräver det. Du kan be oss radera din supportkorrespondens genom att mejla
adressen nedan.

## Datalagring och radering

Milli skickar inget till oss, så vi lagrar inga av dina finansiella uppgifter
och har inget att spara eller radera. Det enda undantaget är supportmejl du
väljer att skicka till oss, vilket beskrivs ovan.

- **För att radera lokala data:** ta bort appen från din enhet, eller använd
  appens egna återställnings-/raderingsalternativ.
- **För att radera data på din Apple Watch:** ta bort Milli från klockan,
  enligt beskrivningen i avsnittet om Apple Watch ovan.
- **För att radera synkroniserade data:** stäng av iCloud-synkronisering och
  ta bort appens data under **Inställningar → ditt namn → iCloud → Hantera
  kontolagring**.

Att ta bort appen tar inte automatiskt bort data som redan har synkroniserats
till ditt iCloud-konto; använd steget ovan för det. Att ta bort iPhone-appen
tar även bort dess Apple Watch-följeslagare.

## Dina rättigheter

Beroende på var du bor kan du ha rättigheter enligt GDPR, UK GDPR, CCPA/CPRA
eller liknande lagar — inklusive rätten att få tillgång till, korrigera,
exportera eller radera dina personuppgifter, och rätten att inte
diskrimineras för att utöva dem.

Milli är utformad så att du utövar dessa rättigheter direkt: dina uppgifter
finns på din egen enhet och i ditt eget iCloud-konto, under din kontroll hela
tiden. Vi har ingen kopia, så vi kan inte ta fram, ändra eller radera en å
dina vägnar. Vi säljer eller delar inte personuppgifter, och har aldrig gjort
det.

Om du anser att vi inte har uppfyllt våra skyldigheter kan du kontakta oss på
adressen ovan, och du har rätt att lämna in ett klagomål till din lokala
tillsynsmyndighet för dataskydd.

## Barn

Milli riktar sig inte till barn och samlar inte medvetet in någon information
från någon, inklusive barn under 13 år (eller motsvarande lägsta ålder i ditt
land). Eftersom appen inte samlar in några uppgifter alls kan ingen sådan
information överföras till oss.

## Ändringar av denna policy

Om denna policy ändras uppdaterar vi denna sida och reviderar datumet för
”Senast uppdaterad” ovan. Väsentliga ändringar noteras även i appens
versionsanteckningar. Vi uppmuntrar dig att regelbundet granska denna sida.

## Kontakt

Frågor, funderingar eller önskemål:

**ivnsjdev@gmail.com**
