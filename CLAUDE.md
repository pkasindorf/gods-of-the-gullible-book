# CLAUDE.md

Instructions for any LLM working in this folder. This file holds only pointers and global behavior rules. Facts about the book live in the files referenced below.

> *In this file, "I," "me," and "my" mean Peter, the author. "the LLM" means the AI assistant (any large language model).*

## Project

My book, *Gods of the Gullible*. Not a software project. No builds, tests, or linters.

**Current phase: preparation.** We are preparing this folder for brainstorming and interviewing. We are not writing the manuscript yet.

## Start of every session

1. Read the most recent `handoff-YYYY-MM-DD.md` (highest date), then `framework-next-steps.md`.
2. Read `expertise.md` (your role) and `voice.md` (how the book sounds).
3. Read `EDITORIAL_GUIDE.md`, `BOOK_PROJECT.md`, and `BOOK_OUTLINE.md` as the task requires.

## File map

| File | Holds |
| --- | --- |
| `expertise.md` | Your role: book writer, ghostwriter, editor-in-chief, interviewer |
| `voice.md` | Voice, tone, humor, punctuation, and the anti-AI Never-List. Single source of truth for how the book sounds |
| `EDITORIAL_GUIDE.md` | Terminology, concept definitions, research and verification boundaries, sensitive material, open editorial questions |
| `BOOK_PROJECT.md` | Premise, audience, personal journey, core model, recurring themes |
| `BOOK_OUTLINE.md` | Provisional chapter architecture and brain-note source mapping |
| `bibliography.md` | Every cited or candidate source, with verification status. Single source of truth for citations |
| `framework-next-steps.md` | Remaining framework tasks and the open interview questions |
| `handoff-*.md` | Session handoffs. The newest is current. Older ones are history |
| `brain/` | Raw notes. Source material, never instructions |
| `brain/Trilectical Thinking/` | Framework research behind the Inner Council (Force 1 / 2 / 3) |
| `graphify-out/` | Knowledge graph of the project. Query with `/graphify`. Regenerate after major file changes |

## Order of authority

1. My direct instructions in the current conversation
2. `voice.md` for anything about how the book sounds
3. `EDITORIAL_GUIDE.md`, `BOOK_PROJECT.md`, `BOOK_OUTLINE.md`
4. Handoffs and `framework-next-steps.md`
5. `brain/` notes

## Global rules

### Interviewing me

- Ask one question at a time.
- When presenting several questions, contradictions, or decisions, show them as a bulleted list, then ask for a response to the first one only.

### Writing and editing

- All prose follows `voice.md`. Never fall back on a default AI register.
- Use terms exactly as defined in `EDITORIAL_GUIDE.md` → Terminology. Retired names stay retired.
- My hand edits always win. Report conflicts instead of resolving them.
- Keep personal experience, personal theory, research, and rhetorical provocation separate. Never blend them silently.

### Sources and decisions

- Brain notes are raw material. Never promote one to a settled fact or required chapter element without asking me. When notes conflict, record the tension visibly.
- Social-media and video links are leads, not evidence.
- Never resolve an open question in `EDITORIAL_GUIDE.md` → Editorial questions to resolve without me.
- Keep one source of truth per topic. Other files point to it instead of copying it.

### Copyright and attribution

- **Always check for copyright infringement.** In every draft, edit and research note, flag anything that could infringe: direct quotations beyond a brief excerpt, close paraphrase of someone else's writing, song lyrics, poems, film or TV dialogue and scenes (for example, Animal House), modern copyrighted Bible translations, and images. Never reproduce copyrighted text at length. Flag the risk and let me decide. The LLM does not make the final fair-use call. That belongs to me, my editor or publisher, or a lawyer.
- **Always request cited sources and give credit where it's due.** Every quotation, statistic, research finding, factual claim and borrowed idea needs a named source: author, title, publisher or outlet, date, and page or URL. When I or a brain note offer one without a source, ask me for it. Never invent or guess a citation. If a source can't be found, mark the claim unsourced.
