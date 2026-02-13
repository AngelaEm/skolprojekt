Lärarblad: Grundläggande Python i matematikundervisningen

Detta lärarblad är tänkt att stödja dig i din första lektion där eleverna introduceras till textbaserad programmering i Python samtidigt som de arbetar med ett matematiskt projekt (planering av ett klassdisco). Materialet följer den svenska kursplanen (Lgr22), där digitala verktyg och programmering ska användas för att undersöka matematiska problem, göra beräkningar och presentera data. Lektionen anknyter också till forskningsbaserade modeller som PRIMM och UMC, där eleverna först kör och undersöker kod, sedan modifierar den och till sist skapar egen kod.

Lektionens syfte och lärandemål

Målet med denna lektion är att eleverna ska:
- Kunna använda print() för att skriva ut text och tal samt förstå skillnaden mellan strängar och tal.
- Deklarera och använda variabler av olika datatyper (sträng, heltal, lista och boolean) och förstå namngivningsregler.
- Använda input() för att hämta indata från användaren och vid behov konvertera den till tal.
- Utföra enklare beräkningar med addition, subtraktion, multiplikation och division samt förstå prioriteringsregler.
- Koppla programmeringen till ett konkret problem – att räkna ut intäkter och kostnader för klassens disco – och därmed se programmeringen som ett verktyg i matematik.

Genomförande steg för steg
1. Inledning och motivation

Berätta för eleverna om figurerna Py och Kode som ska anordna ett disco för att samla in pengar till en klassresa. För att deras lärare ska hjälpa till måste de lära sig grunderna i Python. Syftet är att skapa en berättelse som engagerar och ger eleverna en anledning att lära sig kod.

2. Visa presentationen

Använd den bifogade PowerPoint-presentationen för att strukturera lektionen:

Lärandemål & agenda – Presentera vad eleverna ska lära sig och hur lektionen är upplagd.

Utskrifter & strängar – Demonstrera hur print() fungerar. Skriv exempel på tavlan/skärmen och låt eleverna förutsäga vad som händer. Poängtera att strängar måste ha citattecken och visa hur man skapar radbrytningar med \n.

Variabler & datatyper – Förklara vad en variabel är, visa olika datatyper och diskutera regler för namn (inga mellanslag, inte börja med siffror). Kör exempel från presentationen och låt eleverna modifiera värdena.

Indata & interaktion – Visa hur man läser in text med input() och konverterar till heltal med int(). Be eleverna skriva sin egen kod där de frågar efter namn och ålder och skriver ut ett personligt meddelande.

Aritmetik & prioriteringsregler – Gå igenom de fyra räknesätten och låt eleverna prova kombinationer av multiplikation och addition för att upptäcka prioriteringsregler.

Övningar & utmaningar – Presentera de fyra övningarna som utmanar eleverna att kombinera det de lärt sig. Låt dem arbeta i par och uppmuntra dem att först testa de färdiga koden, sedan ändra parametrar och slutligen skriva eget program (PRIMM-modellen).

3. Differentiering och stöd

Låt eleverna arbeta i par eller små grupper för att diskutera och lösa problem tillsammans, vilket minskar stressen för ovana programmerare.
I grunder_rod finns uppgifter för de som vill gå vidare och ha mer utmaning.

4. Vanliga misstag och lösningar

Glömda citattecken: Elever skriver print(Hello) istället för print("Hello"). Påminn om att Python tolkar text utan citattecken som variabler och därför ger fel.
Fel i variabelnamn: Att använda mellanslag eller börja med en siffra i variabelnamnet ger syntaxfel. Visa exempel och öva på att skapa giltiga namn.
Datatyper blandas: När man försöker summera text och tal utan att konvertera talet till sträng (str()), får man fel. Visa hur man använder kommatecken i print() för att slippa konvertering.
Missing int(): Elever som använder input() för att läsa in tal glömmer ofta att konvertera resultatet. Betona att input() alltid returnerar en sträng och visa hur int() används.

5. Bedömning och uppföljning

Detta moment är främst explorativt och syftar till att göra eleverna bekanta med Python. Bedömning kan ske formativt genom observationer och samtal. Låt eleverna förklara sin kod och beskriva vad den gör. Notera vilka elever som självmant utvecklar koden vidare och vilka som behöver mer stöd.

För att följa upp över tid kan du:
Samla in elevernas Colab‑notebookar via Google Classroom. Du ser då vilka celler som kört och kan ge individuell feedback.
Låta eleverna skriva en kort reflektion: Vad var lätt? Vad var svårt? Hur kan programmering hjälpa oss i matematiken?

