# AI Transparency Commons — Specification

> **Version 0.3 DRAFT** — Living document, open for discussion

This specification is designed to evolve. The AI landscape moves quickly, and this framework must adapt. Expect revisions as the community pressure-tests these ideas.

---

## Purpose

A simple, composable system for creators to disclose **how** they use AI—not just **whether** they do.

Inspired by Creative Commons: few elements, flexible combinations, human-readable.

---

## Dimensions and Qualifiers

The framework uses **dimensions** (the questions being asked) and **qualifiers** (the answers).

Every disclosure considers up to four dimensions:

| Dimension | Code | Question |
|-----------|------|----------|
| **Authorship** | A | Where did the ideas come from? |
| **Execution** | E | Who made the primary output? |
| **Refinement** | R | Who polished or cleaned it up? |
| **Verification** | V | Who checked the final result? |

Each dimension takes one of three qualifiers:

| Qualifier | Code | Meaning |
|-----------|------|---------|
| **Human** | h | Human did this |
| **Assisted** | a | Human and machine together |
| **Machine** | m | Machine did this |

Include only the dimensions relevant to your work. Omitting a dimension means it's not applicable—not that you're hiding something.

---

## Code Format

Codes are two-letter pairs: **uppercase dimension + lowercase qualifier**, separated by hyphens.

**Canonical format:** `Ah-Ea-Rm-Vh`

| Format | Example | When to use |
|--------|---------|-------------|
| **Preferred** | `Ah-Ea-Rm-Vh` | Anywhere case is preserved |
| **All caps** | `AH-EA-RM-VH` | Hashtags, case-insensitive systems |
| **All lower** | `ah-ea-rm-vh` | Case-flattened contexts |
| **No hyphens** | `AhEaRmVh` | Compact display |

Case and hyphens improve readability but are not required for parsing. Codes degrade gracefully across formats.

---

## The Full Matrix

| | Human (h) | Assisted (a) | Machine (m) |
|---|---|---|---|
| **Authorship (A)** | `Ah` — My idea | `Aa` — We ideated together | `Am` — Machine's idea |
| **Execution (E)** | `Eh` — I made it | `Ea` — Machine helped make it | `Em` — Machine made it |
| **Refinement (R)** | `Rh` — I polished it | `Ra` — Machine helped polish | `Rm` — Machine polished it |
| **Verification (V)** | `Vh` — I checked it | `Va` — Machine helped check | `Vm` — Machine checked it |

4 dimensions × 3 qualifiers = 12 possible codes.

---

## Building a Disclosure

Combine codes with hyphens. Only include dimensions that are relevant:

| Badge | Reads as |
|-------|----------|
| `Ah-Eh` | My idea, I made it |
| `Ah-Ea` | My idea, machine helped make it |
| `Ah-Ea-Rm-Vh` | My idea, machine helped make it, machine polished, I verified |
| `Ah-Em-Vh` | My idea, machine made it, I verified |
| `Am-Em` | Machine's idea, machine made it |
| `Ah-Eh-Rm` | My idea, I made it, machine polished |

---

## Examples by Field

| Field | Scenario | Badge |
|-------|----------|-------|
| **Music** | My song, I produced, AI mastered | `Ah-Eh-Rm` |
| **Music** | My song, AI made the drum track, I approved | `Ah-Ea-Vh` |
| **Music** | I wrote and produced everything | `Ah-Eh` |
| **Journalism** | My investigation, AI fact-checked | `Ah-Eh-Vm` |
| **Software** | My architecture, AI helped write code, I reviewed | `Ah-Ea-Vh` |
| **Art** | My concept, AI generated images, I curated | `Ah-Em-Vh` |
| **Education** | My lesson, AI checked my examples | `Ah-Eh-Vm` |
| **Writing** | My essay, AI cleaned up grammar | `Ah-Eh-Rm` |
| **Writing** | My ideas, AI wrote first draft, I rewrote heavily | `Ah-Em-Rh-Vh` |
| **Photography** | My shot, AI retouched | `Ah-Eh-Rm` |
| **Video** | My concept, I shot, AI color graded, I reviewed | `Ah-Eh-Rm-Vh` |

---

## Gray Areas

Some tools blur the line. This framework doesn't mandate where AI begins—creators decide.

**Examples of gray areas:**
- Spell check / grammar tools
- Auto-tune / pitch correction
- Smart filters in photo apps
- Search engines for research
- Predictive text / autocomplete
- Drum machines / virtual instruments

**Guidance:** If you're unsure whether something "counts," consider whether your audience would want to know. When in doubt, disclose. Anyone using this system is making a good-faith attempt at transparency.

---

## Layered Disclosure

The framework supports three levels of detail:

1. **Badge** — The code itself (`Ah-Ea-Rm-Vh`)
2. **Short description** — One sentence ("My ideas, AI helped execute, AI refined, I verified")
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

### Is Authorship necessary?

Most disclosures may default to `Ah` (Authorship: Human). If AI prompts are just "idea starters" like any creative exercise, `Am` may rarely apply.

**When does `Am` clearly apply?**
- AI generated the core creative substance (melody, thesis, design concept)
- **Not:** AI gave me a prompt I ran with

*If Authorship proves to be dead weight in practice, it may be removed in future versions.*

### Where is the line for "counts as AI"?

Spell check? Grammar tools? Smart filters? The framework deliberately doesn't define this—but community norms may emerge.

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

`ATC v0.3: Ah-Ea-Vh`

---

## This Document's Disclosure

`Ah-Ea-Vh`

> Framework concept and direction by Nathan Rosenberg / BeatKitchenSchool. Specification developed with AI assistance (significant portions of text). All content reviewed and approved by human author.

---

*Specification version: 0.3 DRAFT*
*Last updated: January 2026*
