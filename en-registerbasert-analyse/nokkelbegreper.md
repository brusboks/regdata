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

### Temporalitet – data i tid

Et sentralt kjennetegn ved registerdata er at de alltid er knyttet til tid. Dette kalles temporalitet. Det betyr at opplysningene gjelder for et bestemt tidspunkt eller en bestemt tidsperiode. For å kunne tolke dataene riktig, må du vite når de gjelder for. Uten slik informasjon risikerer man å trekke gale slutninger, enten fordi man sammenligner data fra ulike tidspunkter, eller fordi man overser endringer som skjer over tid.

Et godt eksempel er inntektsopplysninger fra Skattemeldingsregisteret. Disse gjelder vanligvis hele kalenderåret, og viser hvor mye en person har tjent i løpet av året. Sykemeldingsdata, derimot, kan være knyttet til en konkret måned, uke eller til og med en spesifikk dag. Dersom man ikke tar hensyn til slike forskjeller, kan sammenligninger mellom ulike datakilder eller tidspunkter bli misvisende.

Registerdata kan ha ulike former for temporalitet:

**Fast:** Enkelte opplysninger endrer seg ikke over tid og har derfor ingen dato knyttet til seg. Eksempler er fødeland eller fødekommune. Disse er konstante og gjelder for hele livsløpet.

**Forløp:** Her registreres både start- og sluttdato for en hendelse eller tilstand. Dette gjelder for eksempel sivilstand, deltakelse på arbeidsmarkedstiltak eller perioder med mottak av trygdeytelser. Slike data gjør det mulig å følge individers bevegelser og endringer over tid.

**Tverrsnitt:** Disse gir et øyeblikksbilde og er registrert på én bestemt dato. Eksempelvis viser statuskode i folkeregisteret (bosatt, utvandret, død) hva som gjelder akkurat på referansedatoen.

**Akkumulerte data:** Enkelte variabler summeres opp over en periode. Et typisk eksempel er inntekt, som gjerne oppgis som total for året. I slike tilfeller kan man velge et referansetidspunkt (for eksempel 31. desember) og bruke akkumulerte tall fram til den datoen.

Å forstå hvordan tid er strukturert i registerdata er avgjørende når man skal følge utviklingstrekk i befolkningen eller sammenligne grupper over tid. Temporalitet er med andre ord ikke bare et teknisk aspekt, det er helt grunnleggende for god analyse.

&#x20;

### Andre aktuelle begreper:

**·       Microdata med «c»**

**·       Mikrodata med «k»**

·  **Grunndataregister:** Inneholder data hentet fra ett konkret administrativt register. Eks.: Folkeregisteret, Navs Arena register som gir opplysninger om oppfølging i Nav, Skatteoppgjørsregisteret...eksempler

**·       Statistikkregister:** Sammensetting av data fra flere administrative kilder for produksjon av statistikk eller analyse av et bestemt fenomen. Eks.: Statistisk sentralbyrås registerbaserte sysselsettingsstatistikk som kobler data fra A-ordningen, registeret over vernepliktige og sivilarbeidere fra Forsvarets personell og vernepliktsenter, Navs Arena-register for å klassifisere personer som sysselsatte.
