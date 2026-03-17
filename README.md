# /build-a-brand

A Claude Code skill that walks you through the [StoryBrand](https://storybrand.com/) framework to build a complete brand messaging kit — interactively, one section at a time.

## What it does

- Guides you through all **7 BrandScript elements** (Character, Problem, Guide, Plan, CTA, Failure, Success)
- Generates your **one-liner / elevator pitch**
- Writes **website wireframe copy** (hero, stakes, value prop, guide, plan, CTA)
- Drafts **nurture and sales email sequences**
- Brainstorms **lead generator ideas** with outlines
- Compiles a **brand summary** quick-reference

For every suggestion, it provides **3 variations** so you can pick, remix, or ask for more.

## Output files

The skill saves everything to markdown files in your current working directory:

| File | Contents |
|------|----------|
| `brandscript.md` | The complete 7-part BrandScript |
| `one-liner.md` | Your chosen elevator pitch |
| `website-copy.md` | Website wireframe copy for each section |
| `email-sequences.md` | Nurture + sales email sequences |
| `lead-generator.md` | Lead magnet ideas and outlines |
| `brand-summary.md` | Quick-reference summary of the full brand |

## Installation

Copy `SKILL.md` into your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/build-a-brand
cp SKILL.md ~/.claude/skills/build-a-brand/SKILL.md
```

## Usage

In Claude Code, run:

```
/build-a-brand
```

Optionally pass your brand/product name:

```
/build-a-brand acme
```

The skill will check for existing brand files and offer to continue refining or start fresh.

## License

MIT
