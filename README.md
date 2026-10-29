# Katafacts skills

Free, open-licensed continuous-improvement skill files — lean fundamentals
(A3, VSM, FMEA, Hoshin Kanri, 5-Whys, and more) and their commercial
(sales/marketing) translations — structured so an AI agent can load one
directly and apply it as part of a broader task.

Generated from [katafacts.com](https://katafacts.com), a free kata
library, artifact generator, and coaching platform for continuous
improvement practice. Every kata here has a full companion guide on the
site — what it is, when to use it, a worked example, and where AI
genuinely helps versus where judgement has to stay human.

## What's in here

One directory per method, each with a single `SKILL.md`:

```
a3/SKILL.md
value-stream-map/SKILL.md
fmea/SKILL.md
...
```

Each `SKILL.md` carries:

- YAML frontmatter (`name`, `description`) an agent host uses to decide
  when to load it
- The method's full guide: what it is, when to use it (and when not to),
  how to fill it in, what good looks like, common mistakes, what it
  connects to, and where AI genuinely helps versus where judgement stays
  human
- A closing note on the one real limitation: **there is no generation
  API for this catalogue yet**. An agent following a skill here drafts
  the artifact's actual content itself, the same way a person filling it
  out by hand would — this teaches the method, it doesn't call out to
  compute it for you (yet).

## Using a skill

Apply it as part of whatever task, instructions, or deliverable you're
already working on — these are methods to use, not a separate chatbot
flow to start. Point your agent at the relevant `SKILL.md` (or install it
into whichever skill-loading mechanism your agent framework supports) and
it has everything it needs to run that method correctly.

## Staying current

This repo is generated, not hand-authored, and kept in sync automatically
from [`katafacts-app`](https://github.com/glen-hamilton/katafacts-app)'s
own catalogue (`content/templates.ts`) whenever it changes — a kata added,
removed, or edited there shows up here the same way. Never edit a file in
this repo directly; edit the source kata's guide content in
`katafacts-app` and the sync will pick it up.

Plain-markdown mirrors of every guide (no frontmatter) are also served
directly from the site: `https://katafacts.com/skills/<slug>.md`, and a
full manifest is at [`https://katafacts.com/llms.txt`](https://katafacts.com/llms.txt).

## License

[CC BY 4.0](LICENSE). Attribution: Katafacts (katafacts.com).
