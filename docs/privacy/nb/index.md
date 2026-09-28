# Personvernerklæring for Milli

**Ikrafttredelsesdato:** 1. august 2026
**Sist oppdatert:** 16. september 2026

## Kortversjonen

Milli samler ikke inn dataene dine. Det finnes ingen Milli-server, ingen analyseverktøy, ingen reklame, ingen sporing og ingen tredjeparts-SDK-er. Alt du legger inn, forblir på enheten din, og — bare hvis du slår på iCloud-synkronisering — i din egen private iCloud-konto, som vi ikke har tilgang til.

## Hvem vi er

Milli («appen») er utviklet av **IVAN CAYABYAB** («vi», «oss»).

Har du spørsmål om denne erklæringen eller personvernet ditt, kan du kontakte oss på **ivnsjdev@gmail.com**.

## Hva Milli lagrer, og hvor

Milli er en personlig økonomiapp. Informasjonen du legger inn, lagres på enheten din i en lokal database. Vi mottar den aldri.

| Hva du legger inn | Hvor det lagres | Ser vi det? |
| --- | --- | --- |
| Transaksjoner, beløp, notater, datoer | På enheten din | Nei |
| Kontoer og regnskap | På enheten din | Nei |
| Kategorier og budsjetter | På enheten din | Nei |
| Faste betalinger og påminnelser | På enheten din | Nei |
| Lønnsbenchmark-tall du legger inn | På enheten din | Nei |
| Profilbilde | På enheten din | Nei |
| Appinnstillinger og preferanser | På enheten din | Nei |
| Transaksjoner du legger inn på Apple Watch | På Apple Watch, deretter på iPhonen din | Nei |

Vi samler ikke inn, overfører, selger, leier ut eller deler noe av dette, fordi appen ikke har noen mulighet til å sende det noe sted. Milli gjør ingen nettverksforespørsler til noen server driftet av oss eller av tredjeparter.

## iCloud-synkronisering (valgfritt)

Hvis du slår på iCloud-synkronisering, bruker Milli Apples CloudKit til å kopiere dataene dine til **den private databasen i din egen iCloud-konto**, slik at de kan vises på dine andre enheter som er logget inn med samme Apple-konto.

- Disse dataene lagres under din Apple-konto, ikke vår.
- Vi har ingen tilgang til dem og ingen mulighet til å lese, eksportere eller gjenopprette dem.
- Apple behandler disse dataene slik det er beskrevet i [Apple Privacy Policy](https://www.apple.com/legal/privacy/).

Du kan slå av iCloud-synkronisering når som helst i appens innstillinger, eller deaktivere det systemomfattende under **Innstillinger → navnet ditt → iCloud** på enheten din.

## Apple Watch

Milli inkluderer en Apple Watch-app, tilgjengelig som en del av premiumfunksjonene, for å se dagens tall og legge til transaksjoner rett fra håndleddet.

**Slik kommer dataene dit.** Klokkeappen har ingen database, ingen konto og ingen egen nettverkstilgang. Alt den viser, kommer direkte fra den tilkoblede iPhonen din via Apples **WatchConnectivity**, systemforbindelsen mellom en iPhone og Apple Watch som er paret med den. Denne forbindelsen er enhet-til-enhet, håndtert av iOS og watchOS; den går ikke via noen av våre servere, og ingen Milli-data sendes til oss på noe tidspunkt.

**Hva som sendes over forbindelsen.** Bare det klokkeskjermen trenger: kontoene dine og deres navn, ikoner, farger og valutaer; dagens transaksjoner og dagens nettotall for disse kontoene; kategorinavnene og -ikonene dine; språk- og tallformatpreferansene dine; og om premiumfunksjonene er låst opp. Hele transaksjonshistorikken din, notater, budsjetter og profilbilde blir værende på iPhonen. I motsatt retning sendes en transaksjon du legger inn på klokken, til iPhonen som et beløp, en kategori og en konto, og lagres i regnskapet ditt der.

**Hva klokken beholder.** Klokken lagrer det siste øyeblikksbildet den mottok, pluss eventuelle transaksjoner du har lagt inn som iPhonen ennå ikke har bekreftet, i klokkeappens egen private lagring på selve klokken. Dette er det som gjør at appen kan åpne med reelle tall, og lar deg registrere utgifter, når iPhonen din er utenfor rekkevidde. Alt som legges inn mens de to er fra hverandre, holdes på klokken til iPhonen er tilgjengelig igjen, og leveres deretter til den.

- Klokkeappen bruker **ikke** iCloud, og har ingen kopi av dataene dine utenfor klokken.
- Klokkeappen gjør **ingen** nettverksforespørsler.
- Den har **ikke** tilgang til helse-, kondisjons-, puls-, treningsøkt- eller posisjonsdata, og ber ikke om slike tillatelser.

**For å fjerne kopien på klokken,** avinstallerer du Milli fra klokken — på klokken trykker og holder du på appikonet og fjerner det, eller på iPhonen åpner du **Watch**-appen, velger Milli, og slår av *Show App on Apple Watch*. Hvis du fjerner paringen med klokken, slettes også appene og dataene deres.

## Face ID, Touch ID og kodelås

Hvis du slår på appelåsen, ber Milli iOS om å autentisere deg. Biometriske data håndteres utelukkende av Apples Secure Enclave og **deles aldri med appen** — iOS forteller Milli bare om autentiseringen lyktes eller mislyktes. Hvis du angir en appkode, lagres den kun på enheten din.

## Kamera og bildebibliotek

Milli ber om tilgang til kamera eller bildebibliotek bare når du velger å angi et profilbilde. Bildet lagres på enheten din (og i din egen iCloud, hvis synkronisering er slått på). Milli laster ikke opp bilder noe sted og får ikke tilgang til biblioteket ditt i bakgrunnen.

## Varsler

Hvis du slår på påminnelser for faste betalinger, planlegger Milli **lokale varsler** på enheten din. Disse genereres på enheten av iOS. Ingen push-server er involvert, og intet påminnelsesinnhold forlater enheten din.

## Kjøp

Milli tilbyr et engangskjøp i appen for å låse opp premiumfunksjonene. Kjøpet behandles i sin helhet av **Apple** gjennom App Store. Vi mottar aldri betalingsopplysningene, kortnummeret eller fakturaadressen din. Milli spør Apple kun om den gjeldende Apple-kontoen eier kjøpet, slik at appen vet om den skal låse opp premiumfunksjonene. Apple Watch-appen kan ikke selv spørre App Store, så iPhonen forteller den over samme private forbindelse om kjøpet er låst opp — en enkel ja/nei-verdi, uten noen betalingsinformasjon i seg. Kjøp reguleres av [Apple Media Services Terms and Conditions](https://www.apple.com/legal/internet-services/itunes/).

## Sikkerhetskopier du eksporterer

Milli lar deg eksportere en sikkerhetskopifil av dataene dine. Når du har eksportert den, er filen under din egen kontroll, og denne erklæringen beskytter den ikke lenger — uansett hvor du lagrer eller sender den (Filer, iCloud Drive, e-post, en annen app), reguleres det av den tjenestens vilkår. Behandle en sikkerhetskopifil som du ville behandlet et kontoutskrift.

## Widgeter

Millis widgeter på hjemskjermen leser en liten mengde av dataene dine fra et privat lagringsområde som deles mellom appen og dens egen widget-utvidelse på enheten din. Ingenting i dette delte området overføres ut av enheten.

## Hva vi IKKE gjør

For å være tydelig: Milli gjør **ikke** følgende:

- samler inn eller overfører dine personlige eller økonomiske data til oss
- bruker analyseverktøy, krasjrapportering eller telemetritjenester
- inkluderer reklame eller reklame-ID-er
- sporer deg på tvers av apper eller nettsteder, eller deler data med databrokere
- oppretter brukerkontoer, eller krever en e-postadresse, et telefonnummer eller innlogging
- leser helse-, trenings- eller posisjonsdata fra iPhonen eller Apple Watch
- bruker dataene dine til å trene opp maskinlæringsmodeller

Millis personvernmerking i App Store gjenspeiler dette: **Data Not Collected (data samles ikke inn)**.

## Support-kommunikasjon

Hvis du sender oss en e-post for support, mottar vi e-postadressen din, meldingen din, og eventuell informasjon om enhet, appversjon, skjermbilder eller annet du velger å inkludere. Vi bruker dette bare til å svare, undersøke problemet og forbedre Milli. Ikke send oss regnskapet ditt, kontoutskrifter eller andre økonomiske dokumenter — vi trenger dem ikke for å besvare et supportspørsmål.

Der GDPR eller UK GDPR gjelder, behandler vi support-e-post på grunnlag av vår berettigede interesse i å besvare dem som skriver til oss og i å løse problemene de rapporterer. Det finnes ikke noe annet behandlingsgrunnlag å finne, fordi Milli ikke sender oss noe av seg selv.

Support-e-post er valgfritt og skjer utenfor Milli. Det behandles av e-postleverandøren din og av Google, som er vert for support-postkassen vår, i henhold til [Google Privacy Policy](https://policies.google.com/privacy). Googles e-postservere ligger i USA, så en support-melding du sender oss, behandles der. Vi oppbevarer support-meldinger i inntil 24 måneder, og lenger bare der en juridisk, sikkerhetsmessig eller arkiveringsmessig forpliktelse krever det. Du kan be oss slette support-korrespondansen din ved å sende en e-post til adressen nedenfor.

## Oppbevaring og sletting av data

Milli sender oss ingenting, så vi har ingen av dine økonomiske data å oppbevare eller slette. Det ene unntaket er support-e-post du velger å sende oss, som er omtalt ovenfor.

- **For å slette lokale data:** slett appen fra enheten din, eller bruk appens egne tilbakestillings-/sletteinnstillinger.
- **For å slette data på Apple Watch:** fjern Milli fra klokken, som beskrevet i Apple Watch-avsnittet ovenfor.
- **For å slette synkroniserte data:** slå av iCloud-synkronisering og fjern appens data under **Innstillinger → navnet ditt → iCloud → Administrer kontolagring**.

Å slette appen fjerner ikke automatisk data som allerede er synkronisert til iCloud-kontoen din; bruk trinnet ovenfor for det. Å slette iPhone-appen fjerner også dens Apple Watch-følgeapp.

## Dine rettigheter

Avhengig av hvor du bor, kan du ha rettigheter under GDPR, UK GDPR, CCPA/CPRA eller lignende lover — inkludert retten til å få innsyn i, rette, eksportere eller slette personopplysningene dine, og retten til ikke å bli diskriminert for å utøve dem.

Milli er utformet slik at du utøver disse rettighetene direkte: dataene dine er på din egen enhet og i din egen iCloud-konto, under din kontroll til enhver tid. Vi har ingen kopi, så vi kan ikke fremskaffe, endre eller slette en på dine vegne. Vi selger eller deler ikke personopplysninger, og det har vi aldri gjort.

Hvis du mener vi ikke har oppfylt våre forpliktelser, kan du kontakte oss på adressen ovenfor, og du har rett til å klage til din lokale datatilsynsmyndighet.

## Barn

Milli er ikke rettet mot barn og samler ikke bevisst inn informasjon fra noen, inkludert barn under 13 år (eller tilsvarende minstealder i ditt land). Siden appen ikke samler inn noen data i det hele tatt, kan ingen slik informasjon overføres til oss.

## Endringer i denne erklæringen

Hvis denne erklæringen endres, oppdaterer vi denne siden og reviderer datoen «Sist oppdatert» ovenfor. Vesentlige endringer vil også bli nevnt i appens versjonsnotater. Vi oppfordrer deg til å se gjennom denne siden med jevne mellomrom.

## Kontakt

Spørsmål, bekymringer eller forespørsler:

**ivnsjdev@gmail.com**
