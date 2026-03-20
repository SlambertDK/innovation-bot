# innovation-bot
Design Thinking templates og processer — scraped fra amper.dk/designtools, struktureret i Markdown

## 🚀 Vision — Agentic Design Thinking

> "Hvad nu hvis Design Thinking ikke var en workshop, men et autonomt system?"

### Drømmen
Et installérbart repository der kører hele Design Thinking-processen agentisk — med mennesker som feedback-givere, ikke facilitatorer.

**Kort sagt:**
- Du beskriver et behov eller problem
- Systemet kører det igennem processen med de rigtige tools automatisk
- Mennesker involveres præcis når det giver mening (feedback, godkendelse, indsigter)
- Output er dokumenterede indsigter, prototyper og testresultater

### Fase-by-fase agentic flow
```
Problem Input
    ↓
[UNDERSTAND] Agent interviewer stakeholders → genererer insights
    ↓ (human: review insights)
[DEFINE] Agent kører Affinity Diagram + Empathy Map → problem statement
    ↓ (human: godkend problem statement)
[IDEATE] Agent kører Brainstorming + SCAMPER → idé-shortlist
    ↓ (human: prioritér idéer)
[PROTOTYPE] Agent bygger Storyboard + Paper Prototype → artefakter
    ↓ (human: review prototype)
[TEST] Agent genererer Test Cards + NABC Pitch → test-plan
    ↓ (human: kør test, giv feedback)
[REALISE] Agent laver Business Model Canvas + Lean Canvas → go-to-market
```

### ISO 56000 Integration (fremtidig vertikal)
På længere sigt: kobling til ISO 56000 Innovation Management Standard.

Det betyder at hvert Design Thinking-forløb automatisk mappes til:
- **Innovation Vision & Politik** — er dette i tråd med organisationens innovationsstrategi?
- **Opportunity Management** — registreres som formel innovation-opportunity
- **Portfolio Management** — indgår i innovation-pipeline
- **Realisering** — output dokumenteres i overensstemmelse med standarden

Resultatet: et system der ikke bare faciliterer innovation — men dokumenterer den i henhold til international standard. Klar til audit.

### Inspiration
Bygget med inspiration fra [pm-skills](https://github.com/phuryn/pm-skills) — samme Skills + Commands + Plugins-arkitektur, men for Innovation Management i stedet for Product Management.

### Hvad der mangler for at dette bliver virkeligt
- [ ] Slash-commands per fase (`/understand`, `/define`, `/ideate` osv.)
- [ ] Human-in-the-loop checkpoints som structured prompts
- [ ] ISO 56000 mapping-layer
- [ ] Multi-agent orchestration (research-agent, synthesis-agent, prototype-agent)
- [ ] Output-format standardisering (JSON + Markdown)
