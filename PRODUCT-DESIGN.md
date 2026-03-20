# PRODUCT-DESIGN.md
## Double Diamond — Agentic Design Thinking Platform

> Dette dokument beskriver produktdesign-processen for selve platformen — kørt som et Double Diamond-forløb. Indsigter og interviews er konstruerede, men baseret på realistiske mønstre fra enterprise innovation-arbejde.

---

## DISCOVER (divergent)

### Research-tilgang
Vi kortlagde tre brugergrupper gennem deskresearch, ekspert-interviews og observationsstudier:
1. **Innovation Leads** i store danske virksomheder (Novo, Maersk, DSB, kommuner)
2. **Konsulenter** der faciliterer DT-workshops som ekstern part
3. **Startup-teams** der bruger DT ad hoc uden formel proces

### Markeds-analyse: Hvad eksisterer allerede?

| Værktøj | Styrker | Svagheder |
|---|---|---|
| **Miro** | Godt whiteboard, real-time samarbejde | Blank canvas — ingen DT-logik indbygget |
| **MURAL** | DT-templates, guided facilitation | Kræver human facilitator, ikke skalerbart |
| **Notion DT Templates** | Let at kopiere og tilpasse | Passivt dokument, ingen agent-logik |
| **pm-skills** | Agentisk, slash-commands, CLI-native | Kun PM-fokus, ingen DT eller ISO 56000 |
| **Liberating Structures** | Stærke metoder | Kun fysisk/facilitator-drevet |
| **IDEO Design Kit** | Autoritativ, velstruktureret | Statisk PDF, ingen automation |

**Konklusion:** Der er et markant hul mellem "blank canvas-tools" og "fuldt agentisk DT-flow". Ingen eksisterende løsning kombinerer struktureret Design Thinking med agentic AI og compliance-dokumentation.

---

### Bruger-indsigter (konstruerede interviews — 8 deltagere)

**Indsigt 1 — "Workshoppen dør efter workshoppen"**
> *"Vi holder en fantastisk 2-dages designsprint. Alle er energized. Og så er der ingen der gør noget ved det bagefter, for det er ikke sat op til at fortsætte uden mig som facilitator."*
> — Innovation konsulent, 12 års erfaring

**Indsigt 2 — "Forberedelse tager 80% af tiden"**
> *"Jeg bruger 3-4 dage på at forberede en DT-workshop. Researchen, interviewguides, templates, materialer. Selve workshoppen er kun 1 dag."*
> — Innovation Lead, Novo Nordisk-størrelse

**Indsigt 3 — "Dokumentationen er et mareridt"**
> *"Vi har ingen standard for hvordan vi dokumenterer innovation-projekter. Hvert team gør det forskelligt. Ledelsen kan ikke se portfolioen."*
> — Head of Innovation, dansk kommunekoncern

**Indsigt 4 — "Jeg ved ikke hvornår jeg skal involvere folk"**
> *"Det er svært at vide hvornår i processen man skal inddrage teknikere, økonomi, jura. Vi involverer dem enten for tidligt (for vagt) eller for sent (for låst)."*
> — Produktchef, fintech startup

**Indsigt 5 — "SCAMPER og Empathy Maps er for komplekse for mit team"**
> *"Metoderne er gode, men folk forstår dem ikke. Jeg skal forklare hvad et Affinity Diagram er hver eneste gang."*
> — Innovation facilitator, offentlig sektor

**Indsigt 6 — "Vi gentager de samme fejl fordi vi ikke lærer på tværs"**
> *"Hvert innovationsprojekt starter fra scratch. Vi har ingen systematisk måde at genbruge indsigter fra tidligere forløb."*
> — Senior Manager, Maersk-størrelse

**Indsigt 7 — "ISO 56000? Ingen aner hvad det er"**
> *"Vi ved godt at der er en standard. Men det er kun compliance-folk der kender den. Den er aldrig integreret i det faktiske innovationsarbejde."*
> — Innovation Director, pharma

**Indsigt 8 — "Jeg vil gerne bruge AI, men ikke en blank chatboks"**
> *"ChatGPT er for frit. Jeg vil have noget der ved hvad man gør i Discover-fasen, og hvad man gør næste. Struktur + AI."*
> — Innovation Lead, 35 år, teknisk baggrund

**Indsigt 9 — "Vi mister momentum mellem faser"**
> *"Mellem Ideate og Prototype er der altid en pause på 2-3 uger. Folk glemmer konteksten. Synteser går tabt."*
> — Design Thinker, konsulentbureau

**Indsigt 10 — "Stakeholders vil se noget konkret efter dag 1"**
> *"Ledelsen vil have output hele vejen. Ikke 'vi er stadig i discovery'. Det skaber pres der kompromitterer processen."*
> — Innovation Project Manager, energy sector

---

## DEFINE (konvergent)

### Primær Persona: Henrik

**Navn:** Henrik Lambert
**Titel:** Innovation Lead / Head of Innovation
**Virksomhed:** Enterprise, 500-5000 ansatte, dansk eller nordisk
**Alder:** 38-50
**Baggrund:** Kombination af forretning og facilitation. Ikke udvikler, men teknisk nysgerrig.

**Kontekst:**
- Ansvarlig for 3-8 innovation-projekter i parallel
- Arbejder med tværfaglige teams der ikke kender DT-metoderne
- Skal rapportere til C-suite og bestyrelse
- Er personligt ansvarlig for at processen holder standard

**Pain points:**
- Skalér sig selv: kan ikke facilitere alt manuelt
- Dokumentation til ledelse er tidskrævende og inkonsistent
- Teams mister motivation/fokus mellem sessioner
- Ingen audit-trail for beslutninger truffet undervejs

**Mål:**
- Køre strukturerede DT-forløb uden at være til stede i hvert trin
- Bevise innovationens ROI til ledelsen
- Blive anerkendt som den der "moderniserede innovationsprocessen"

---

### Problem Statement (HMW-format)

> **How Might We** give innovation leads som Henrik et autonomt system der kører Design Thinking-processen fra problem til prototype — og dokumenterer hvert trin i henhold til ISO 56000 — så han kan skalere sig selv og bevise innovationensværdi til ledelsen?

---

### Jobs to be Done

**Primær JTBD:**
> Når jeg har et komplekst innovationsproblem og et team der ikke kender DT, vil jeg have et system der guider teamet igennem den rigtige proces automatisk, så jeg kan fokusere på de beslutninger der kræver mit lederskab frem for at facilitere hvert enkelt trin.

**Sekundær JTBD:**
> Når jeg skal rapportere om vores innovationsaktiviteter til ledelsen eller ekstern revisor, vil jeg have dokumentation der automatisk er struktureret og sporbar, så jeg ikke bruger dage på at samle og formatere information.

**Tertiær JTBD:**
> Når et nyt DT-forløb starter, vil jeg kunne genbruge indsigter og mønstre fra tidligere forløb, så vi ikke opfinder den samme løsning to gange.

---

### Core Value Proposition

**For** innovation leads i enterprise-organisationer
**der** kæmper med at skalere strukturerede innovationsprocesser uden at være personligt til stede i hvert trin,
**er** innovation-bot
**et** agentisk Design Thinking-system
**der** kører hele DT-processen automatisk med human-in-the-loop checkpoints,
**i modsætning til** Miro, MURAL og manuelle workshop-facilitatorer
**fordi det** kombinerer metodisk stringens, AI-assistance og ISO 56000-dokumentation i ét installérbart system.

---

## DEVELOP (divergent)

### 5 Idé-retninger

**Retning 1 — "The Autopilot"**
Fuldt autonomt DT-system. Brugeren beskriver problemet, systemet kører alle faser og leverer et komplet output-pakke. Mennesket reviewes kun ved kritiske gates.
*Risiko: For sort boks. Mister buy-in fra teams.*

**Retning 2 — "The Co-Pilot"**
AI-assistent der sidder ved siden af facilitatoren. Genererer spørgsmål, syntetiserer noter, foreslår næste skridt — men facilitatoren bestemmer.
*Risiko: For passiv. Løser ikke skalerings-problemet.*

**Retning 3 — "The DT OS"**
Et operativsystem for innovation. Slash-commands per fase. Hver kommando er et komplet micro-workflow med inputs, AI-processing og struktureret output.
*Styrke: Modular, installérbart, kan integreres i eksisterende workflow (Claude, Cursor, VSCode).*

**Retning 4 — "The Innovation CRM"**
Database-centreret løsning. Alle innovation-projekter i ét system. AI hjælper med at søge og genbruge indsigter på tværs af projekter.
*Risiko: Kompleks infrastruktur. Svær at onboarde.*

**Retning 5 — "The ISO 56000 Compliance Engine"**
Primært compliance-fokus. Dokumenterer automatisk at DT-processen følger ISO 56000. Sælges til enterprise compliance-teams.
*Risiko: For snævert. Compliance er et middel, ikke målet.*

---

### SCAMPER-analyse — Retning 3: "The DT OS"

**S — Substitute (hvad kan erstattes?)**
- Erstat manuel facilitering med slash-commands der kører som structured prompts
- Erstat Miro-whiteboards med Markdown-output der er versionsstyret i git

**C — Combine (hvad kan kombineres?)**
- Kombiner pm-skills-arkitekturen med DT-metodologi
- Kombiner agentisk AI med ISO 56000 compliance-layer

**A — Adapt (hvad kan tilpasses fra andre domæner?)**
- Adaptor pm-skills' plugin-struktur til DT-faser
- Adaptor GitOps-principper: innovation-projekter som git repositories

**M — Modify/Magnify (hvad kan forstærkes?)**
- Forstærk human-in-the-loop: gør checkpoints til eksplicitte gate reviews
- Forstærk output: JSON + Markdown = maskinlæsbart OG menneskelæsbart

**P — Put to other uses (andre anvendelser?)**
- Samme arkitektur kan bruges til agil produktudvikling, strategiprocesser, OKR-forløb
- Kan bruges som undervisningsplatform for DT-uddannelse

**E — Eliminate (hvad kan fjernes?)**
- Fjern behovet for at kende metoderne (systemet ved dem)
- Fjern manuelle dokumentationsopgaver

**R — Reverse/Rearrange (hvad kan vendes om?)**
- I stedet for at samle folk til workshop: distribuér processen over tid med asynkrone AI-sessioner
- I stedet for top-down facilitation: bottom-up input der syntetiseres til oppe

---

### Feature-idéer: MVP vs. Later

**MVP (version 1.0)**
- `/dt-understand` — genererer stakeholder-interview guide + syntetiserer svar til insights
- `/dt-define` — kører Empathy Map + genererer HMW problem statement
- `/dt-ideate` — kører struktureret brainstorm + SCAMPER på bedste idé
- `/dt-test` — genererer Test Cards + NABC Pitch
- Markdown-output for alle faser
- Human-in-the-loop checkpoints som structured review-prompts
- `/run-dt` — kører fuld proces med alle gates

**Later (version 2.0+)**
- `/dt-prototype` — storyboard + paper prototype som ASCII/Markdown artefakt
- `/dt-realise` — Business Model Canvas + Lean Canvas auto-generering
- ISO 56000 mapping-layer (`/iso56000-map`)
- Multi-agent orchestration (parallelle research-agenter)
- Persistens: innovation-projekter gemt som git repos med full history
- Cross-project insights: søg og genbrug indsigter på tværs af projekter
- Integrations: Notion, Jira, Confluence output

---

## DELIVER (konvergent)

### Valgt retning: "The DT OS" (Retning 3)

**Begrundelse:**
Retning 3 løser den primære smertepunkt (skalering uden manuel facilitation), passer til den tekniske arkitektur vi allerede kender fra pm-skills, er installérbar og versionsstyret (low friction onboarding), og kan gradvist udvides med ISO 56000-lag og multi-agent capabilities.

Retning 1 (Autopilot) er for ambitiøs til MVP. Retning 5 (ISO Engine) er for snæver. Retning 3 er det rigtige middelpunkt.

---

### MVP-scope: Version 1.0

**Scope statement:**
> Version 1.0 er et installérbart Claude-plugin (inspireret af pm-skills) der giver innovation leads én enkelt slash-command per DT-fase. Hvert command genererer et struktureret Markdown-output baseret på brugerens input. Human-in-the-loop er implementeret som eksplicitte review-gates.

**Hvad er med:**
- 5 slash-commands: `/dt-understand`, `/dt-define`, `/dt-ideate`, `/dt-test`, `/run-dt`
- Struktureret output-template per fase (Markdown)
- Human review-checkpoints efter Understand og Define
- README med installationsvejledning

**Hvad er ikke med:**
- `/dt-prototype` og `/dt-realise` (version 2.0)
- ISO 56000 compliance (version 2.0)
- Persistens og cross-project search (version 3.0)
- Multi-agent (version 3.0)

---

### Arkitektur-skitse: Skills-struktur

Inspireret af pm-skills (`https://github.com/phuryn/pm-skills`):

```
innovation-bot/
├── README.md
├── PHASE-MAPPING.md
├── PRODUCT-DESIGN.md
│
├── phases/                        # Eksisterende DT-templates (scraped)
│   ├── understand/
│   ├── define/
│   ├── ideate/
│   ├── prototype/
│   ├── test/
│   └── realise/
│
├── skills/                        # Agentic skills (fremtidig)
│   ├── dt-facilitation/           # Core facilitation plugin
│   │   └── README.md
│   ├── dt-understand/             # /dt-understand command
│   │   ├── skill.md
│   │   └── output-template.md
│   ├── dt-define/                 # /dt-define command
│   │   ├── skill.md
│   │   └── output-template.md
│   ├── dt-ideate/                 # /dt-ideate command
│   │   ├── skill.md
│   │   └── output-template.md
│   ├── dt-prototype/              # /dt-prototype command (v2.0)
│   │   └── skill.md
│   ├── dt-test/                   # /dt-test command
│   │   ├── skill.md
│   │   └── output-template.md
│   ├── dt-realise/                # /dt-realise command (v2.0)
│   │   └── skill.md
│   └── iso56000/                  # ISO 56000 compliance (future)
│       └── skill.md
│
└── templates/                     # Eksisterende Markdown templates
```

**Slash-commands (MVP):**

| Command | Beskrivelse | Output |
|---|---|---|
| `/run-dt` | Kører fuld DT-proces med alle gates | Komplet DT-pakke i Markdown |
| `/dt-understand` | Genererer interview-guide + insights-synthese | Insights dokument |
| `/dt-define` | Empathy Map + HMW problem statement | Define-output |
| `/dt-ideate` | Struktureret brainstorm + SCAMPER | Idé-shortlist |
| `/dt-test` | Test Cards + NABC Pitch | Test-plan |

---

### Success Metrics

**Adoption metrics (3 måneder efter launch):**
- 50+ GitHub stars
- 20+ aktive brugere (målt via discussions/issues)
- 5+ fork-baserede tilpasninger

**Usage metrics:**
- Gennemsnitlig tid fra problem-input til første insights: < 15 minutter
- % af brugere der når alle 5 faser i ét forløb: > 40%
- Human gate completion rate (gennemfører review-checkpoints): > 70%

**Kvalitets-metrics:**
- User-reported: "Ville jeg anbefale dette til en kollega?" (NPS > 30)
- Facilitator replacement rate: "Jeg behøvede ikke en ekstern facilitator til dette forløb"

---

## NÆSTE SKRIDT (til Henrik at auditere)

### Hvad kræver Henriks input/beslutning?

1. **Prioritering af faser** — Skal `/dt-prototype` med i MVP, eller er Understand → Define → Ideate → Test nok til version 1.0?

2. **Målgruppe-validering** — Er "innovation lead i enterprise" den rigtige beachhead, eller skal vi starte med DT-konsulenter der er mere teknisk orienterede?

3. **ISO 56000-timing** — Skal vi bygge compliance-laget parallelt med core DT-commands, eller vente til v2.0?

4. **Distributionstrategi** — Kun GitHub repo (som pm-skills), eller også Claude.ai plugin marketplace?

5. **Sprog** — Primært dansk output eller engelsk? (Påvirker skill-templates markant)

### Hvad kan bygges autonomt (ingen beslutning nødvendig)?

- [ ] `skills/dt-understand/skill.md` — første slash-command implementation
- [ ] `skills/dt-define/skill.md` — anden slash-command implementation
- [ ] Output-templates for Understand og Define
- [ ] Human-in-the-loop review-prompt templates
- [ ] `skills/dt-ideate/skill.md`

### Forslag til Sprint 1 (2 uger)

**Mål:** Første kørbare end-to-end flow: Problem → Insights → Problem Statement

**Sprint 1 backlog:**

| # | Task | Estimat | Prioritet |
|---|---|---|---|
| 1 | Byg `skills/dt-understand/skill.md` med interview-guide generator | 2t | Must |
| 2 | Byg output-template: Insights Dokument (Markdown) | 1t | Must |
| 3 | Byg `skills/dt-define/skill.md` med HMW-generator | 2t | Must |
| 4 | Byg output-template: Define Dokument (Markdown) | 1t | Must |
| 5 | Implementér human review-checkpoint mellem Understand → Define | 1t | Must |
| 6 | Test end-to-end flow med realistisk case (Henrik selv) | 2t | Must |
| 7 | Opdater README med installationsvejledning | 1t | Should |
| 8 | Første `/run-dt` prototype (kæder Understand + Define) | 3t | Should |

**Definition of Done for Sprint 1:**
En bruger kan skrive `/dt-understand` med et problem-statement, modtage en interview-guide, indsætte 3-5 svar, og få en syntetiseret insights-rapport. Dernæst køre `/dt-define` og modtage et HMW problem statement klar til godkendelse.

---

*Dokument oprettet: 2026-03-20 | Forfatter: Henrik Lambert / innovation-bot | Version: 1.0-draft*
