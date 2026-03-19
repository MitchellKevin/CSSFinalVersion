# Rubiks Cube | CSS
Tijdens de minor Webdesign & Development kregen we bij het vak CSS to the rescue de mogelijkheid om als opdracht te kiezen om een rubiks cube te maken wat mij veel aansprak als iemand die vroeger helemaal gek was rubiks cube.

## 🗣️ Daily Checkups
### Dag 1 | 
**Gedaan:**
- Vandaag hadden we de introductie presentatie waar ik clip-path, color-scheme en accent-color. De presentatie ging redelijk en het eindresultaat van de website was wel grappig, maar verder ook niet.


---

### Dag 2 | 
**Gedaan:**
- Vandaag hadden we de introductie presentatie waar ik clip-path, color-scheme en accent-color. De presentatie ging redelijk en het eindresultaat van de website was wel grappig, maar verder ook niet.

**Oplossingen / inzichten:**
- Inzichten gekregen van andere onderwerpen waar mensen een presentatie over hadden en hoe de eindopdracht eruit ging zien.

---

### Dag 3 | 
**Gedaan:**
- Ik heb vandaag geconceptualiseerd hoe ik de 3x3 kubus kon laten werken en uitdenken hoe ik dit ging opbouwen.

---

### Dag 4 | 
**Gedaan:**
- Vandaag ben ik thuis gebleven, maar heb wel behoorlijke progressie geboekt ik had in de bus een brilliant idee hoe ik het probleem van meerdere onderdelen in verschillende animaties kon omzeilen. Ik had als idee om na elke animatie de kubus ontzichbaar gemaakt en de volgende state zichtbaar te maken en niet met opacity maar met diplay. Hierdoor kan ik per kubus bedenken hoe ik deze wil laten draaien. Elke state is dan ook zelf custom gemaakt op basis van de eind patroon van de vorige state. Vandaag heb ik dit gedaan voor 4 states tot een oplossing maar nog zonder animaties.


---

### Dag 5 | 
**Gedaan:**
- Vandaag heb ik verder gewerkt aan meerdere states (moves) te maken heb nu 9 states, ik heb er vandaag dus 5 bij gemaakt verder heb ik alle horizontale turns werkend gekregen en een paar andere kleine dingen. En heb ik geconceptualiseerd op hoe ik mijn blog wil maken en ben hier opgekomen: Een old school vibe zoals de vroegere jaren op het internet.


---

### Dag 6 | 
**Gedaan:**
- Vandaag heb ik gewerkt aan de verticale axen, maar kwam er niet helemaal uit, maar ik dacht door de cube te draaien kan ik dezelfde animaties gebruiken, hierdoor moest ik wel van de states met verticale turns de kleuren van elke cubie weer op de juist plek zetten.

**Problemen:**
- Te zien waar welke kleur waar hoorde, door het draaien van de cube werd het soms een beetje onoverzichtelijk wat nou de 'bovenkant' etc was.

---

### Dag 7 | 
**Gedaan:**
- Vandaag heb ik een 2x2 gemaakt die volledig interactief was die tot 7 moves kan gaan en een animerende titel gemaakt en een switch waarmee je kan kiezen tussen een 2x2 of een 3x3.


---

### Dag 8 | 
**Gedaan:**
- Vandaag heb ik alles bij elkaar moeten toevoegen, ik heb er voor gekozen om ipv 7 moves bij de 2x2 te doen 3 moves te doen voor de eindoplevering, want de code is hetzelfde. Hierdoor ging ik van 8600+ states naar 64 voor de 2x2 en was het minder zwaar voor mijn laptop/browser. Ook heb ik scroll bars toegevoegd met js van Sanne om de kubus te kunnen laten draaien, vandaag heb ik ook alle cubies weer de juiste kleuren gegeven bij de 3x3.

**Problemen:**
- Een html met 430k regels was moeilijk en onbeheersbaar om te tevoegen aan mijn huidige code voor de 3x3.

---

## 📋 Weekelijkse voortgang gesprekken
### Week 1
Focus: Oriëntatie & context begrijpen
Gedaan:
* Introducties gevolgd over o.a. clip-path, color-scheme en accent-color
* Eerste presentatie gegeven
* Inzicht gekregen in mogelijke richtingen voor de eindopdracht

Beoordeling:
* Lage output, maar logisch: dit was een verkenningsfase
* Je noemt je werk “wel grappig maar niet bijzonder” → dat is geen analyse, dat is ruis
Werkelijke voortgang:
* Begrip van tools en opdrachtkader opgebouwd
* Richting bepaald voor project (Rubik’s Cube)

---

### Week 2
Focus: Architectuur & systeemdenken
Gedaan:
* Concept uitgewerkt voor een 3x3 cube structuur
* Slim workaround bedacht voor animatiebeperkingen met states (display i.p.v. opacity)
* Eerste 4 states gebouwd (zonder animaties)

Beoordeling:
* Dit is je eerste echte doorbraakmoment
* Je verschuift van “volgen” → naar zelf systemen ontwerpen
* Werkelijke voortgang:
* Core technische aanpak bepaald
* Grootste technische risico (animatiestructuur) opgelost

---

### Week 3
Focus: Schalen & complexiteit managen

Gedaan:
* Uitgebreid naar 9 states (+5 toegevoegd)
* Horizontale rotaties werkend gekregen
* Eerste poging tot verticale rotaties (met workaround via cube-rotatie)
* Blogconcept bedacht (old-school webstijl)

Beoordeling:
* Hier begint het zwaar te worden → en dat zie je ook
* Je workaround (cube draaien i.p.v. nieuwe animaties) is slim, maar ook een signaal:
* je systeem begint tegen grenzen aan te lopen

Werkelijke voortgang:
* Functionele uitbreiding van systeem
* Eerste tekenen van technische schuld / complexiteit

---

### Week 4 (Eindgesprek)
**Eindresultaat:**
Focus: Optimalisatie & oplevering

Gedaan:
* Werkende interactieve 2x2 cube gebouwd (tot 7 moves → later teruggebracht naar 3)
* Performance probleem opgelost (8600+ states → 64 states)
* 3x3 cube visueel gecorrigeerd (kleuren kloppend gemaakt)
* UI verbeteringen toegevoegd (switch + scroll interactie)

Beoordeling:
* Dit is je tweede grote doorbraakmoment
* Je maakt hier een volwassen keuze: scope verkleinen voor performance

Werkelijke voortgang:
* Werkend eindproduct
* Complexiteit teruggebracht naar beheersbaar niveau
* Interactie + usability toegevoegd


## 🪞 Reflectie
Ik vond dit vak leuker dan BT, omdat ik iets meer mijn oplossend denken kon toepassen op een andere manier. Met CSS is wel totaal anders dan hoe ik het normaal zou doen. Ik zou snel naar JavaScript gaan omdat dit vaak effecinter is dan CSS en voorkomt dat ik D.R.Y. programmeer. Maar ik erkende wel dat het bij dit vak niet ging om snelheid, maar om het begrijpen wat CSS allemaal kan. Dit is nu dan ook gebeurt, heb het proberen te verminderen door technieken als nesting en has: toe te passen, maar met js was het sneller. Maar daarnaast was het wel een te zware maar ook leuke uitdaging. Ben redelijk tevreden met het resultaat, er zijn altijd dingen die je anders/mogelijk beter had willen doen, maar er zit ook een kunst in accepteren wat je hebt gemaakt en daar tevereden mee te zijn. Ik denk persoonlijk ook dat mijn code vaardigheid in CSS zwaar is verbeterd ten opzichte van hoe het was. Ik ga er wel op letten om mijn README bij de aankomende vakken meer bij te houden, want dit was echt verschrikkelijk.
