---
icon: '7'
---

# Nøkkelbegreper

Registerdata har sin egen logikk og struktur, som skiller seg fra både spørreundersøkelser og kvalitativt datamateriale. I dette kapitlet får du derfor en oversikt over de mest sentrale begrepene du trenger for å orientere deg i «registerverdenen». Målet er ikke at du skal kunne alt med én gang, men at du skal få et tydelig rammeverk som hjelper deg å lese dokumentasjon, forstå datasett og kjenne igjen hvilke spørsmål du må stille for å vurdere kvalitet og relevans.

## Grunndataregister

Et grunndataregister refererer til data trukket fra ett spesifikt administrativt register. Her er informasjonen hentet direkte fra systemene som brukes til saksbehandling, kontroll, innrapportering eller tjenesteyting, uten at de nødvendigvis er bearbeidet eller tilrettelagt for analyse. Grunndataregistre kan inneholde detaljerte enkeltopplysninger om personer, virksomheter eller hendelser, slik de faktisk er registrert i forvaltningens systemer.

Siden grunndataregistre i utgangspunktet har et annet formål enn å utarbeide statistikk eller forske, kan de inneholde:

* Ubehandlede og lite standardiserte verdier
* kodeverk som varierer over tid
* mangler eller feil som skyldes registreringsrutiner
* detaljer som senere ikke inngår i ferdige statistikker

For deg som skal gjøre analyser basert på grunndataregistre er det viktig å være bevisst at dette vil kunne kreve merarbeid for å forstå definisjoner, datakvalitet og logikk.

### Eksempler:&#x20;

* Folkeregisteret gir opplysninger om alle personer som er bosatt i Norge (bosted, fødselsdato, sivilstand mv.)
* Arbeidsgiver– og arbeidstakerregisteret (Aa-registeret) inneholder informasjon om alle arbeidsforhold i Norge
* Navs ARENA-register som inneholder detaljer om arbeidssøkere som hva slags arbeidsrettet oppfølging personene mottar og eventuell deltakelse i arbeidsmarkedstiltak

<mark style="color:red;">·         ANDRE EKSEMPLER?</mark>

## &#x20;Statistikkregister

Et statistikkregister er et datasett som er spesielt tilrettelagt for å lage statistikk eller for å kunne brukes i forskning. I motsetning til grunndataregistre, som inneholder rå og ubehandlede opplysninger direkte fra forvaltningens systemer, består statistikkregistre av bearbeidede og kvalitetssikrede data. Disse dataene kan være hentet fra ett enkelt administrativt register, men ofte er de resultatet av koblinger mellom flere ulike kilder. Formålet med et statistikkregister er å gi et helhetlig og konsistent datagrunnlag som kan belyse et bestemt fenomen, for eksempel sysselsetting, helseforløp eller utdanningsløp. For å oppnå dette må dataene omkodes, harmoniseres og kvalitetssikres slik at de passer sammen på tvers av registre, tidsperioder og definisjoner.

### Typiske kjennetegn ved statistikkregistre:

* Data er bearbeidet og standardisert, ofte etter felles kodeverk og definisjoner.
* Informasjon kan være koblet på tvers av flere administrative kilder, som gir bredere og mer fullstendig datagrunnlag.
* Tidsserier er harmonisert, slik at variablene kan sammenlignes over år.
* Feil og mangler i grunndata er korrigert eller håndtert, for eksempel ved logiske kontroller.
* Data er strukturert etter et statistikkformål, ikke etter forvaltningens behov.

Sammenlignet med _grunndataregistre_ er _statistikkregistre_ ofte enklere å jobbe med for deg som skal besvare et forskningsspørsmål fordi en stor del av tilretteleggingen allerede er gjort.

### Eksempler:&#x20;

* _SSBs registerbaserte sysselsettingsstatistikk_. Dataene bygger på koblinger mellom flere administrative kilder, blant annet A-ordningen (arbeidsforhold og lønnsopplysninger), Registeret over vernepliktige og sivilarbeidere, Navs ARENA-register (for å avgjøre hvem som regnes som sysselsatt i referanseuken). Bearbeidingen gjør det mulig å produsere konsistent og sammenlignbar statistikk om sysselsetting på tvers av år og grupper.
* _FD-Trygd_ er en omfattende forløpsdatabase som SSB forvalter, hvor data om blant annet trygdeytelser, sysselsetting, utdanning, sosialhjelp og demografi er samlet. FD-Trygd er spesielt utviklet for forskning på velferd og sosialpolitikk, og gir mulighet til å følge enkeltpersoners bevegelser over tid.

## **Populasjon**

Populasjonen er den gruppen av personer eller enheter som et datasett omfatter. I registerdata består den som regel av alle som faller inn under et bestemt kriterium. Populasjonen kan være veldig bred, som i Folkeregisteret. Dette registeret omfatter alle som er bosatt i Norge. Den kan også være smal og spesialisert, som i et register over mottakere av arbeidsavklaringspenger, som kun vil inneholde personer med den aktuelle ytelsen.

### Eksempel

Dersom du analyserer data hentet fra Navs register over personer som har fått utbetalt uføretrygd, sier resultatene dine kun noe om denne gruppen, ikke om hele befolkningen. Skal du derimot studere flytting, er Folkeregisteret ofte riktig populasjon, fordi det dekker alle bosatte.

## Enhet (analyseenhet)

Enheten er det nivået dataene er registrert på, og utgjør byggesteinene i datasettet ditt. I registerdata er enheten ofte individet, men den kan også være en husholdning, en familie, en bedrift, et arbeidsforhold eller en kommune, avhengig av hva registeret er laget for.

Å kjenne analyseenheten er avgjørende fordi den bestemmer hva du faktisk kan si noe om. Har du individdata, kan du analysere individuelle utfall som inntekt, utdanning eller trygdehistorikk. Men skal du studere forhold som gjelder flere personer samlet, for eksempel husholdningens totale inntekt eller antall barn i familien, må dataene først aggregeres til et nivå som matcher problemstillingen.

#### Eksempel

Et inntektsregister gir i utgangspunktet informasjon om hvor mye hver enkelt person har tjent i et gitt år. Enheten er altså _individet_. Hvis du skal beregne om noen tilhører lavinntektsgruppen, tar du imidlertid ikke utgangspunkt i personens egen inntekt alene. Lavinntekt vurderes på husholdningsnivå, der inntektene til alle i husholdningen legges sammen og deretter justeres for husholdningsstørrelse. For å gjøre en slik analyse må du derfor først konstruere en ny enhet: _husholdningen_. Dette innebærer å:

* identifisere hvilke personer som bor i samme husholdning
* summere inntektene deres
* knytte dette tilbake til hver enkelt person som analyseenhet (dersom analysen fortsatt skal gjøres på individnivå)

Selv om dataene opprinnelig er registrert per person, er det altså husholdningen som er riktig analyseenhet for spørsmålet du ønsker å belyse.

## Variabel

En variabel er en bestemt egenskap, opplysning eller kjennetegn som er registrert om hver enhet i datasettet.

### Eksempler:&#x20;

Variabler kan være

* kontinuerlige, som inntekt eller alder
* kategoriske, som kjønn, sivilstand eller utdanningsnivå
* datoer og tidsperioder, som start- og sluttdato for en ytelse
* koder som for eksempel angir yrke, næring, diagnoser osv.

## Kodeverk/kodelister

Et kodeverk er en systematisk liste som oversetter koder i registerdata til meningsfulle kategorier. Mange variabler er ikke lagret som tekst, men som tall- eller bokstavkoder, som for eksempel for yrke, næring, diagnose eller utdanningsnivå. Kodelister gjør det mulig å tolke disse kodene riktig, og de kan endre seg over tid.

**Eksempler**

• Yrkeskoder etter STYRK

• Næringskoder etter SN (NACE)

• Diagnosekoder etter ICD-10

• Utdanningskoder etter NUS

## Identifikator (ID-variabel)

En identifikator er en unik nøkkel som brukes til å knytte dataene til riktig enhet. I personregistre er dette vanligvis fødselsnummeret, mens virksomheter identifiseres med organisasjonsnummer. Disse identifikatorene gjør det mulig å følge en enhet over tid og å koble informasjon på tvers av ulike registre.

Når data utleveres til forskning, brukes imidlertid ikke de faktiske identifikatorene. Av hensyn til personvern og datasikkerhet erstattes de med pseudonyme løpenummer (ofte kalt _løpenr_, _pseudonym-ID_ eller _koblingsnøkkel_). Dette betyr at forskeren kan analysere sammenhengene i dataene, for eksempel følge et individ over tid eller koble inntektsdata med helsedata, uten å vite hvem personen eller virksomheten faktisk er. De opprinnelige ID-ene lagres kun i et sikkert «koblingsregister» hos dataeier og er ikke tilgjengelige for forskeren.

### Temporalitet – data i tid

Temporalitet handler om _når_ en opplysning gjelder, og er et av de viktigste særtrekkene ved registerdata. Fordi opplysninger i offentlige registre alltid er knyttet til et tidspunkt eller en tidsperiode, er forståelsen av temporalitet avgjørende for både tolkning og analyse. To like variabler kan bety helt ulike ting hvis de gjelder for ulike tidspunkter.

I registerdata finner vi flere typer tidsangivelse, avhengig av hvordan opplysningen brukes i forvaltningen:

* Fast: Noen kjennetegn endrer seg ikke over tid og har derfor ingen dato. Eksempler er fødeland eller fødekommune.
* Forløp: Her registreres både start- og sluttdato, slik som perioden en person har vært ansatt hos en bestemt arbeidsgiver, har mottatt behandling fra spesialisthelsetjenesten, eller mottatt en trygdeytelse.
* Tverrsnitt: Disse viser status på én bestemt dato, for eksempel om en person er sysselsatt, i gang med utdanning eller arbeidsledig på en referansedato (referansetidspunkt).
* Akkumulerte data: Noen variabler summeres opp over en periode. Et typisk eksempel er årsinntekt, som viser summen av inntekter i løpet et kalenderår.

**Eksempler**

i) Inntektsopplysninger fra Skattemeldingsregisteret. Disse gjelder vanligvis hele kalenderåret, og kan angi hvor mye sykepenger en person har mottatt i løpet av året. Sykemeldingsdata kan derimot være knyttet til en konkret måned, uke eller til og med en spesifikk dag. Dersom man ikke tar hensyn til slike forskjeller, kan sammenligninger mellom de ulike datakildene misvisende.&#x20;

ii) Data fra SSBs registerbaserte sysselsettingsstatistikk angir om en person er sysselsatt i én bestemt uke i november. Data fra Arbeidsgiver–arbeidstakerregisteret (Aa-registeret) inneholder derimot start- og stoppdatoer for alle arbeidsforhold, og gir dermed et løpende bilde av hvor lenge og når en person faktisk har vært ansatt. Så hva betyr dette for analysene? Den registerbaserte sysselsettingsstatistikken egner seg godt til å beskrive nivåer og sammenligne grupper på ett fast tidspunkt, men den gir lite informasjon om bevegelser inn og ut av arbeid. Aa-registeret gjør det mulig å studere detaljerte forløp, som hvor lenge ansettelsesforhold varer, hyppige jobbytter eller perioder med ustabil tilknytning. Valg av datakilde styrer derfor hvilke typer spørsmål du kan besvare: Tverrsnitt gir oversikt, mens forløpsdata gir mulighet til å analysere endringer, varighet og dynamikk.

## Pseudonymisering

Pseudonymisering betyr at direkte identifiserende opplysninger, som fødselsnummer, navn eller organisasjonsnummer, erstattes med en kunstig identifikator, ofte et løpenummer.\
Dette gjør at forskeren kan følge samme enhet over tid og koble data på tvers av registre, uten å vite hvem personen eller virksomheten faktisk er.

Eksempel: Når du får tilgang til individdata fra SSB eller Nav, vil en variabel som opprinnelig inneholder fødselsnummer, erstattes med et unikt løpenummer (f.eks. _lopenr = 104823_). Koblingsnøkkelen mellom fødselsnummer og dette løpenummeret lagres hos dataeier og er aldri tilgjengelig for forskeren.

&#x20;

## Anonymisering

Anonymisering betyr at alle muligheter for å identifisere en person er fjernet, både direkte og indirekte. Når data er anonymisert, kan ingen gjenopprette koblingen til den opprinnelige personen, heller ikke dataeier. Anonymiserte data er ikke lenger personopplysninger etter lovverket.

Eksempel: Offentlig statistikk som publiseres av SSB er anonymisert. Tallene gjelder grupper (f.eks. "andel sysselsatte 20–24 år"), aldri enkeltpersoner.

&#x20;

## Koblingsnøkkel

En koblingsnøkkel er en variabel som brukes når data fra flere registre skal knyttes sammen. For personer er dette ofte (pseudonymiserte) fødselsnummer, mens for bedrifter er det organisasjonsnummer. Kvaliteten på koblingsnøkkelen er avgjørende for kvaliteten på hele datasettet.

<mark style="color:$danger;">(Kommentar: Andre begreper som kan tas med: Ulike typer data – Anonyme, indirekte identifiserbare, direkte identifiserbare. Grønne, gule, røde data (sensitive data))</mark>
