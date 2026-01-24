# AI Transparency Commons — Specification

> **Version 0.2 DRAFT** — Living document, open for discussion

This specification is designed to evolve. The AI landscape moves quickly, and this framework must adapt. Expect revisions as the community pressure-tests these ideas.

---

## Purpose

A simple, composable system for creators to disclose **how** they use AI—not just **whether** they do.

Inspired by Creative Commons: few elements, flexible combinations, human-readable.

---

## The Questions

Every ATC disclosure considers up to three questions:

| Code | Question | What it captures |
|------|----------|------------------|
| **O** | Origin | Where did the ideas come from? |
| **C** | Creation | Who made the primary output? |
| **V** | Verification | Who checked the work? |

Include only the dimensions relevant to your work. Omitting a dimension means it's not applicable—not that you're hiding something.

---

## Core Codes

Each dimension uses a two-letter code: **dimension + value**

### Origin (O)

| Code | Name | Meaning |
|------|------|---------|
| **OH** | Origin: Human | Ideas, concept, creative vision are human |
| **OA** | Origin: AI | AI contributed to the core concept or ideation |

### Creation (C)

| Code | Name | Meaning |
|------|------|---------|
| **CH** | Creation: Human | Human made the work |
| **CA** | Creation: Assisted | AI helped; human drove the process |
| **CC** | Creation: Contributed | AI made a distinct element; human made the rest |
| **CG** | Creation: Generated | AI produced the primary output; human curated/selected |

### Verification (V)

| Code | Name | Meaning |
|------|------|---------|
| **VH** | Verification: Human | Human reviewed for accuracy |
| **VA** | Verification: AI | AI checked facts, calculations, or consistency |

*Omit V entirely if verification isn't relevant to your work.*

---

## Building a Disclosure

Combine codes with hyphens:

| Badge | Reads as |
|-------|----------|
| `OH-CH` | Human origin, human created |
| `OH-CA` | Human origin, AI assisted |
| `OH-CC-VH` | Human origin, AI contributed, human verified |
| `OH-CG-VH` | Human origin, AI generated, human verified |
| `OA-CG` | AI-informed origin, AI generated |

---

## Examples by Field

| Field | Scenario | Badge |
|-------|----------|-------|
| **Music** | I wrote a song, used AI for drum track | `OH-CC-VH` |
| **Music** | I wrote and produced everything | `OH-CH` |
| **Journalism** | My investigation, AI fact-checked | `OH-CH-VA` |
| **Software** | My architecture, AI helped write code | `OH-CA` |
| **Art** | My concept, AI generated images, I curated | `OH-CG-VH` |
| **Education** | My lesson, AI checked my examples | `OH-CH-VA` |
| **Marketing** | AI drafted copy, I edited and approved | `OH-CG-VH` |
| **Writing** | AI checked grammar | `OH-CA` |
| **Writing** | AI wrote first draft, I rewrote heavily | `OH-CG-VH` |

---

## Gray Areas

Some tools blur the line. This framework doesn't mandate where AI begins—creators decide.

**Examples of gray areas:**
- Spell check / grammar tools
- Auto-tune / pitch correction
- Smart filters in photo apps
- Search engines for research
- Predictive text / autocomplete

**Guidance:** If you're unsure whether something "counts," consider whether your audience would want to know. When in doubt, disclose.

---

## Layered Disclosure

ATC supports three levels of detail:

1. **Badge** — The code itself (`OH-CA-VH`)
2. **Short description** — One sentence ("Human ideas, AI assisted with execution, human verified")
3. **Full disclosure** — Detailed explanation of what AI did and didn't do

Creators choose how much detail to provide.

---

## Principles

1. **Neutral** — No level is "better"; appropriate use varies by context
2. **Composable** — Elements combine flexibly across industries
3. **Evolvable** — Your disclosure can change as practices change
4. **Voluntary** — Adoption through value, not mandate
5. **Adaptable** — This spec will evolve as the landscape changes

---

## Open Questions

These are unresolved and welcome discussion:

### Is Origin necessary?

Most disclosures may default to OH (Human Origin). If AI prompts are just "idea starters" like any creative exercise, OA may rarely apply.

**When does OA clearly apply?**
- AI generated the core creative substance (melody, thesis, design concept)
- **Not:** AI gave me a prompt I ran with

*If Origin proves to be dead weight in practice, it may be removed in future versions.*

### Where is the line for "counts as AI"?

Spell check? Grammar tools? Smart filters? The framework deliberately doesn't define this—but community norms may emerge.

### Component vs. whole

If AI made one element (drums in a song), does that need different treatment than AI assisting throughout? Current approach: describe in the short description, not the badge.

### Verification relevance

V may not apply to creative works. Is it only relevant for factual content (journalism, education, research)?

### Training disclosure

Should there be a way to indicate "this content may/may not be used for AI training"? That's a separate concern from creation disclosure—but related.

---

## Relationship to Other Standards

ATC is **complementary** to technical standards like C2PA/Content Credentials.

| Standard | Purpose |
|----------|---------|
| **C2PA** | Cryptographic metadata embedded in files (provenance verification) |
| **ATC** | Human-readable creator declaration (intent communication) |

They can coexist. Use C2PA for technical verification, ATC for communicating to your audience.

---

## Versioning

This is a living document. Major changes will be versioned. Disclosures should include the spec version if precision matters:

`ATC v0.2: OH-CA-VH`

---

## This Document's Disclosure

`ATC: OH-CC-VH`

> Framework concept and direction by BeatKitchenSchool. Specification developed with AI assistance (significant portions of text). All content reviewed and approved by human author.

---

*Specification version: 0.2 DRAFT*
*Last updated: January 2026*
