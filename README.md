# AI Transparency Commons (ATC)

> **v0.1 DRAFT** — Seeking feedback before public release

A simple, composable framework for creators to disclose how they use AI—inspired by Creative Commons.

---

## The Problem

"I use AI" is meaningless. "AI writes my songs" vs "AI checks my grammar" are vastly different. Current disclosure options are either:
- Vague ("AI-assisted")
- Binary ("AI-generated" or not)
- Platform-specific (YouTube, TikTok, etc.)
- Technical (C2PA metadata)

Creators need a simple, human-readable way to communicate **how** they use AI, not just **whether** they do.

---

## The Framework

ATC answers three questions:

| Question | What it captures |
|----------|------------------|
| **Origin** | Where did the ideas/knowledge come from? |
| **Creation** | Who/what made the primary output? |
| **Oversight** | How was quality ensured? |

### Core Elements

#### Origin
| Code | Name | Meaning |
|------|------|---------|
| **HO** | Human Origin | Core ideas, expertise, creative vision are human |
| **AO** | AI-Informed Origin | AI contributed to ideation or knowledge base |

#### Creation
| Code | Name | Meaning |
|------|------|---------|
| **HC** | Human Created | Human produced the primary work product |
| **AC** | AI-Assisted Creation | AI helped produce work; human shaped output |
| **AG** | AI Generated | AI produced primary output; human selected/curated |

#### Oversight
| Code | Name | Meaning |
|------|------|---------|
| **HV** | Human Verified | Human expert reviewed for accuracy |
| **AV** | AI Verified | AI checked facts, calculations, or consistency |
| **UV** | Unverified | No systematic verification (default if omitted) |

### Modifiers
| Code | Name | Use case |
|------|------|----------|
| **+T** | Tools Only | AI limited to technical tools (code, integrations, formatting) |
| **+P** | Process Only | AI used in workflow, not in output |
| **+D** | Disclosure | Detailed statement available |
| **+R** | Restricted Domain | AI use limited to specific stated area |

---

## Examples

| Badge | Meaning | Typical Use |
|-------|---------|-------------|
| `HO-HC` | Fully Human | Traditional creation, no AI |
| `HO-HC-AV` | Human + AI Check | Human work, AI verified facts/math |
| `HO-AC` | Human-Led | Human ideas, AI assists execution |
| `HO-AG-HV` | Human-Curated | AI generates, human expertise curates |
| `AO-AC` | Collaborative | AI contributes to both ideas and creation |
| `AO-AG` | AI Primary | AI-driven with human oversight |

### Industry Applications

| Field | Example | Meaning |
|-------|---------|---------|
| Education | `HO-HC-AV` | Teacher's knowledge, AI checks examples |
| Journalism | `HO-HC-AV` | Reporter's investigation, AI fact-checks |
| Software | `HO-AC+T` | Developer's design, AI assists coding |
| Art | `HO-AG-HV` | Artist's vision, AI generates, artist curates |
| Marketing | `AO-AC-HV` | AI helps with concepts, human approves |

---

## Human-Readable Format

A badge like `HO-AC-HV+D` expands to:

> **Human Origin, AI-Assisted Creation, Human Verified**
> Ideas and direction are mine. AI assisted with execution. All content reviewed and approved.

---

## Principles

1. **Neutral** — No level is "better"; appropriate use varies by context
2. **Composable** — Elements combine flexibly across industries
3. **Evolvable** — Your disclosure can change as practices change
4. **Layered** — Badge → Short description → Full disclosure
5. **Voluntary** — Adoption through value, not mandate

---

## Relationship to Other Standards

ATC is **complementary** to technical standards like [C2PA/Content Credentials](https://c2pa.org/).

- **C2PA** = cryptographic metadata embedded in files (verification)
- **ATC** = human-readable creator declaration (communication)

They can coexist. Use C2PA for provenance verification, ATC for communicating intent.

---

## Status

This is a **v0.1 draft** developed collaboratively with AI assistance.

**This project's own disclosure:** `HO-AC-HV+D`
> Framework concept and direction by BeatKitchenSchool. Specification developed with AI assistance. All content reviewed and approved by human author.

---

## Help Wanted

We're looking for feedback from:
- **Creators** — Does this capture how you'd describe your AI use?
- **Designers** — Can you help visualize badges?
- **Writers** — Can we make this clearer?
- **Domain experts** — How does this apply to your field?
- **Critics** — What's missing? What won't work?

See [CONTRIBUTING.md](CONTRIBUTING.md) for how to participate.

---

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt this framework for any purpose, provided you give appropriate credit.

---

**Founded by [BeatKitchenSchool](https://github.com/BeatKitchenSchool)**
