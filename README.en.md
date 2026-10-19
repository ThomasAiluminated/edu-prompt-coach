# Edu Prompt Coach

**A Claude skill that gives teachers a ready-to-use AI prompt, and briefly explains why that prompt works.**

🇧🇪 [Nederlandstalige versie](README.md) · 📄 [Examples](examples/)

Teachers want a usable result today, and better prompting skills tomorrow. This skill does both: a prompt to paste right away, plus a short pedagogical note that links each prompting technique to a teaching principle.

It works in English, Dutch and French: it replies in the language you write in.

## What the skill does

- **Works in any AI tool.** Prompts use plain labelled sections (Context, Task, Format), so they work in ChatGPT, Claude, Gemini and Copilot.
- **Starts from good teaching:** learning objective first, cognitive level, differentiation and a clear output format.
- **Protects learners:** reminds teachers to anonymise student work, and keeps grading with the teacher.
- **Teaches as it goes:** 2–4 bullets explain the moves that make the prompt work, plus a follow-up prompt.

## What you get

1. **The prompt**, in one copyable block
2. **What to fill in**, if there are placeholders
3. **Why this works**: 2–4 bullets
4. **Next step**: one follow-up prompt

See [examples/](examples/) for a full input and output.

## Who it's for

Teachers and lecturers at any level who want better results from AI, and trainers who teach prompting to teachers.

This skill is part of **[Claude Skills for Education](https://github.com/ThomasAiluminated/claude-skills-for-education)**, an open collection for education and L&D:
- [Lesson Designer](https://github.com/ThomasAiluminated/lesson-designer): lessons designed from objective to exit check
- [Rubric Builder](https://github.com/ThomasAiluminated/rubric-builder): assessment rubrics with observable levels
- [Assessment Item Writer](https://github.com/ThomasAiluminated/assessment-item-writer): test and exam questions with answer key and feedback
- [Feedback Writer](https://github.com/ThomasAiluminated/feedback-writer): specific, actionable feedback on student work
- [Inclusive Lesson Adapter](https://github.com/ThomasAiluminated/inclusive-lesson-adapter): accessible lesson materials using UDL
- [Learning Program Designer](https://github.com/ThomasAiluminated/learning-program-designer): training programs and learning journeys
- [Prompt Architect](https://github.com/ThomasAiluminated/prompt-architect): rough requests turned into strong prompts for Claude

## Install

**In Claude (web, desktop or mobile):**
1. Download [`edu-prompt-coach.skill`](edu-prompt-coach.skill)
2. Upload it under Skills in your Claude settings
   (or open the file in a Claude conversation and click *Save skill*)

**In Claude Code:** copy the `edu-prompt-coach/` folder to `~/.claude/skills/`.

Then just ask, for example *"make a prompt to give feedback on argumentative essays from 16-year-olds"*. The skill starts automatically.

## Contributing

Ideas and improvements are welcome via an issue or pull request.

## License

[CC BY 4.0](LICENSE): free to use, adapt and share, with attribution.

---

Made by **Thomas Donvil**, [Ailuminated](https://ailuminated.org), AI literacy for education.
