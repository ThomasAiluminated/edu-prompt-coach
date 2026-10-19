# Edu Prompt Coach

**Een Claude-skill die docenten een kant-en-klare AI-prompt geeft, en kort uitlegt waarom die prompt werkt.**

🇬🇧 [English version](README.en.md) · 📄 [Voorbeelden](examples/)

Docenten willen vandaag een bruikbaar resultaat, maar ook morgen zelf betere prompts kunnen schrijven. Deze skill doet allebei: je krijgt een prompt om meteen te plakken, plus een korte didactische toelichting die elke prompttechniek koppelt aan een onderwijsprincipe.

*English summary: a Claude skill that turns a teacher's request into a ready-to-paste prompt for any AI tool, and briefly explains the pedagogy behind it so teachers learn to prompt better themselves.*

## Wat de skill doet

- **Werkt met elke AI-tool.** De prompts gebruiken gewone, gelabelde secties (Context, Opdracht, Vorm), dus ze werken in ChatGPT, Claude, Gemini en Copilot.
- **Vertrekt vanuit goede didactiek:** het leerdoel staat vooraan, alles sluit erop aan (constructive alignment), het gewenste denkniveau wordt benoemd en waar nodig wordt gedifferentieerd.
- **Voor elk onderwijsniveau,** van lager tot hoger onderwijs, met Vlaamse of Nederlandse onderwijstermen naargelang de context.
- **Beschermt leerlingen:** studentwerk wordt eerst geanonimiseerd (GDPR), de AI geeft nooit cijfers en de docent houdt het laatste woord.
- **Leert itereren:** elk antwoord eindigt met een vervolgprompt.

## Wat je terugkrijgt

1. **De prompt**, klaar om te kopiëren
2. **Invullen**: wat je in de placeholders zet
3. **Waarom dit werkt**: 2 à 4 korte punten die techniek en didactiek verbinden
4. **Volgende stap**: één vervolgprompt

## Voorbeeld

> *"Maak een prompt om feedback te geven op betogende teksten van leerlingen uit het 4e middelbaar"*

De skill levert een prompt die het leerdoel (argumentatie) centraal zet, de feedback beperkt tot maximaal drie verbeterpunten en geen cijfer laat geven. Daarbij legt hij uit waarom elk van die keuzes de feedback beter maakt voor de leerling.

Deze skill hoort bij **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, een open reeks voor onderwijs en L&D:
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessen ontwerpen van leerdoel tot exit-check
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): beoordelingsrubrics met observeerbare niveaus
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): toets- en examenvragen met sleutel en feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specifieke, haalbare feedback op leerlingenwerk
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): lesmateriaal toegankelijk maken met UDL
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): opleidingen en leertrajecten ontwerpen
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): een ruwe vraag omzetten in een sterke prompt voor Claude

## Installeren

**In Claude (claude.ai of de app):**
1. Download [`edu-prompt-coach.skill`](edu-prompt-coach.skill)
2. Upload het bij de Skills in je Claude-instellingen
   (of open het bestand in een gesprek met Claude en klik op *Save skill*)

**In Claude Code:** kopieer de map `edu-prompt-coach/` naar `~/.claude/skills/`.

Daarna volstaat een gewone vraag, zoals *"maak een prompt voor een rubric voor stageverslagen"*. De skill start vanzelf.

## Structuur

```
edu-prompt-coach/
└── SKILL.md          # de volledige instructies van de skill
examples/                 # voorbeelden van input en output
edu-prompt-coach.skill  # installeerbaar pakket
```

## Bijdragen

Ideeën, verbeteringen of voorbeelden uit je eigen lespraktijk zijn welkom via een issue of pull request.

## Licentie

[CC BY 4.0](LICENSE): vrij te gebruiken, aan te passen en te delen, met naamsvermelding.

---

Gemaakt door **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI-geletterdheid voor het onderwijs.
