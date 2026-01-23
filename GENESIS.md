# Genesis: How AI Transparency Commons Came to Be

> **Document disclosure:** `ATC: HO-AC-HV+D`
> This document preserves the actual conversation that created this project.

**Date:** January 23, 2026
**Participants:** BeatKitchenSchool (human) + Claude (AI)

---

## Part 1: The Spark

### BeatKitchenSchool:

> I thought it would be a good idea to try and spearhead some kind of disclosure system for who uses AI and how. I'm inspired by Creative Commons. Could you suggest a framework for how this might work? Below is the original text I wrote when I had the idea:
>
> "How about a Creative Commons type statement for AI use. I don't use AI to generate or edit my videos, write my scripts. My knowledge is my own and my teaching and marketing is always based on an idea kernel that is mine. I do use AI to double check my math, write code for things I am unable to do like school integration authorization codes and things like that. I periodically make note of my ideas or scripts using dictation and often feed those into an LLM when they are beyond spellcheck."

### Claude:

This is a thoughtful initiative. The current landscape is messy—either full disclosure that sounds defensive, no disclosure at all, or vague statements that don't mean much. A standardized framework could build trust.

**Proposed Framework: AI Transparency Labels (ATL)**

**Core Principle:** Disclosure should be specific to domain, not binary. "I use AI" is meaningless. "AI writes my scripts" vs "AI checks my grammar" are vastly different.

**Category Structure:**

**1. Content Creation**
- ATL-C0 — No AI in content creation
- ATL-C1 — AI assists (spell check, grammar, dictation cleanup)
- ATL-C2 — AI collaborates (brainstorming, outlining, revision suggestions)
- ATL-C3 — AI generates with human curation/editing
- ATL-C4 — AI generates final content

**2. Technical/Code**
- ATL-T0 — No AI in technical work
- ATL-T1 — AI for specific tools I couldn't build myself
- ATL-T2 — AI assists coding (copilot-style)
- ATL-T3 — AI generates significant code portions

**3. Knowledge/Expertise**
- ATL-K0 — All knowledge is personal expertise/research
- ATL-K1 — AI verifies facts/math
- ATL-K2 — AI supplements research
- ATL-K3 — AI provides primary information

**4. Media (Audio/Visual)**
- ATL-M0 — No AI in media production
- ATL-M1 — AI for technical cleanup (noise reduction, color correction)
- ATL-M2 — AI generates elements (stock replacement, backgrounds)
- ATL-M3 — AI generates primary media

**Your Statement as ATL:**

Based on what you wrote: `ATL-C1 | ATL-T1 | ATL-K0/K1 | ATL-M0`

Or in human-readable form:

> AI Transparency: Content is mine (AI assists with transcription/cleanup). Code tools built with AI assistance. Knowledge and teaching is personal expertise (AI verifies calculations). No AI in video/audio production.

---

## Part 2: Refining with Creative Commons as Model

### BeatKitchenSchool:

> Yes. And I would like you to anticipate other indications that might be necessary for other kinds of AI use, industry, etc. And we can do this efficiently with fewer badges, that's even better. But let's use Creative Commons as a model.

### Claude:

Let me study the Creative Commons structure first to model this properly.

The genius of Creative Commons is **composable elements** rather than many specific licenses. Four elements (BY, SA, NC, ND) combine into six licenses. Let me apply that thinking.

---

## AI Transparency Commons (ATC) — Draft Specification v0.1

### Design Philosophy

Like Creative Commons, ATC uses **composable elements** that answer fundamental questions about AI involvement. Rather than domain-specific badges (content, code, media), we identify **universal dimensions** that apply across all fields.

### The Three Questions

Every AI disclosure answers three questions:

| Question | What it captures |
|----------|------------------|
| **Origin** | Where did the ideas/knowledge come from? |
| **Creation** | Who/what made the primary output? |
| **Oversight** | How was quality ensured? |

### Core Elements

#### Origin Elements
| Code | Name | Meaning |
|------|------|---------|
| **HO** | Human Origin | Core ideas, expertise, creative vision are human |
| **AO** | AI-Informed Origin | AI contributed to ideation or knowledge base |

#### Creation Elements
| Code | Name | Meaning |
|------|------|---------|
| **HC** | Human Created | Human produced the primary work product |
| **AC** | AI-Assisted Creation | AI helped produce work; human shaped output |
| **AG** | AI Generated | AI produced primary output; human selected/curated |

#### Oversight Elements
| Code | Name | Meaning |
|------|------|---------|
| **HV** | Human Verified | Human expert reviewed for accuracy |
| **AV** | AI Verified | AI checked facts, calculations, or consistency |
| **UV** | Unverified | No systematic verification (default if omitted) |

### Modifiers

Optional tags for additional context:

| Code | Name | Use case |
|------|------|----------|
| **+T** | Tools Only | AI limited to technical tools (code, integrations, formatting) |
| **+P** | Process Only | AI used in workflow, not in output (scheduling, organization) |
| **+D** | Disclosure | Detailed statement available (link provided) |
| **+R** | Restricted Domain | AI use limited to specific stated area |

### Standard Combinations

Like CC's six licenses, common patterns emerge:

| Badge | Shorthand | Typical Use |
|-------|-----------|-------------|
| **HO-HC** | "Fully Human" | Traditional creation, no AI |
| **HO-HC-AV** | "Human + AI Check" | Human work, AI verified math/facts |
| **HO-AC** | "Human-Led" | Human ideas, AI assists execution |
| **HO-AG-HV** | "Human-Curated" | AI generates, human expertise selects/verifies |
| **AO-AC** | "Collaborative" | AI contributes to both ideas and creation |
| **AO-AG** | "AI Primary" | AI-driven with human oversight |

### Your Disclosure (Revised)

Based on your original statement: `ATC: HO-HC-AV+T+D`

**Human-readable:**

> **Human Origin, Human Created, AI Verified, Tools Only**
> Ideas, scripts, teaching, and videos are my own. AI verifies calculations and builds technical integrations I specify. Dictated notes cleaned up via AI transcription.

### Industry Applications

The same elements work across contexts:

| Field | Example Disclosure | Meaning |
|-------|-------------------|---------|
| **Journalism** | HO-HC-AV | Reporter's investigation, AI fact-checks |
| **Legal** | HO-AC-HV+R | Lawyer's strategy, AI drafts documents, lawyer reviews |
| **Medical** | HO-HC-AV+D | Doctor's diagnosis, AI cross-references literature |
| **Software** | HO-AC+T | Architect's design, AI assists coding |
| **Marketing** | AO-AC-HV | AI helps with copy concepts, human approves |
| **Art** | HO-AG-HV | Artist's vision, AI generates, artist curates |
| **Research** | HO-HC-AV+D | Original research, AI assists literature review |
| **Education** | HO-HC-AV | Teacher's knowledge, AI checks examples |
| **Customer Service** | AO-AG-HV | AI responds, humans review escalations |
| **Music** | HO-HC+T | Artist creates, AI masters/mixes |

### Visual System (Conceptual)

```
┌─────────────────────────────────────┐
│  ◯ ─ ◉ ─ ◯    ORIGIN               │
│  H       A    (Human ← → AI)        │
│                                     │
│  ◯ ─ ◉ ─ ◯    CREATION             │
│  H   A   G    (Human ← Assisted → Generated) │
│                                     │
│  ◯ ─ ◉ ─ ◯    OVERSIGHT            │
│  H   A   U    (Human ← AI → None)   │
│                                     │
│  [+T] [+D]    MODIFIERS            │
└─────────────────────────────────────┘
```

A visual badge could show three sliders or filled circles indicating position on each spectrum.

### Principles

1. **Neutral** — No level is "better"; appropriate use varies by context
2. **Composable** — Elements combine; don't need new badges for new industries
3. **Evolvable** — Your disclosure can change as practices change; date it
4. **Layered** — Badge → Short description → Full disclosure (+D link)
5. **Voluntary** — Adoption through value, not mandate

### Open Questions

1. **Training disclosure** — Was this content used to train AI? (Reverse direction)
2. **Real-time vs. batch** — Live AI assistance vs. used during creation
3. **Percentage thresholds** — When does AC become AG? (Deliberately vague for now)
4. **Certification** — Self-reported vs. verified claims
5. **Child content** — If you embed AI-generated stock footage in HO-HC video

---

## Part 3: The Meta-Test

### BeatKitchenSchool:

> How would you designate the code for this project using your current system?

### Claude:

Good meta-test. Let me assess this conversation:

**Origin:** You came to me with the core concept ("Creative Commons type statement for AI use") and your personal use case. The fundamental idea is yours.
→ **HO** (Human Origin)

**Creation:** I structured the framework, invented the terminology, wrote the specification, and generated the industry examples. You're directing and will iterate/approve, but I'm producing substantial portions of the actual document.
→ **AC** (AI-Assisted Creation)

**Oversight:** You're reviewing, questioning, and will ultimately approve or modify what gets published.
→ **HV** (Human Verified)

**This Project's Disclosure:** `ATC: HO-AC-HV+D`

**Human-readable:**

> **Human Origin, AI-Assisted Creation, Human Verified**
> Framework concept and direction by BeatKitchenSchool. Specification developed collaboratively with AI assistance. All content reviewed and approved by human author.

**Why This Is a Good Test Case:**

It's honest about what actually happened:
- You didn't claim you wrote every word (you didn't)
- I don't get false credit for the idea (I didn't have it)
- It's clear a human is accountable for the final output

This is exactly the kind of work where vague disclosures fail. "I used AI" undersells your contribution. "I wrote this" oversells it. **HO-AC-HV** captures the actual collaboration.

---

## Part 4: Open Source Strategy

### BeatKitchenSchool:

> Could this be open sourced but moderated on GitHub for transparency and inclusiveness? How might I take the spring work and ask others to help bring it to life?

### Claude:

Yes, absolutely. This is a good fit for open source—it's a standard, not a product. Like Creative Commons itself, it gains value through adoption, not control.

**License Choice:**

For a specification/standard (not software), consider:

| License | Fit |
|---------|-----|
| **CC BY 4.0** | Anyone can use/adapt with attribution. Simple. CC licensing a CC-like project is poetic. |
| **CC0 (Public Domain)** | Maximum adoption, no friction. You give up control but gain ubiquity. |
| **Open Web Foundation Agreement** | Used by specs like OpenID. More formal governance. |

**Recommendation:** Start with **CC BY 4.0**. Attribution keeps your name attached as originator while allowing free use and adaptation.

**Repository Structure:**

```
ai-transparency-commons/
├── README.md                 # What this is, why it matters
├── SPECIFICATION.md          # The formal spec
├── CONTRIBUTING.md           # How to participate
├── CODE_OF_CONDUCT.md        # Community standards
├── GOVERNANCE.md             # How decisions get made
├── LICENSE                   # CC BY 4.0
│
├── badges/                   # Visual assets (SVG, PNG)
├── translations/             # i18n
├── examples/                 # Industry-specific examples
└── tools/                    # Generators, validators
```

**Governance Model:**

Start simple, formalize later:

- **Phase 1: Benevolent Dictator (You)** — You approve PRs and make final calls
- **Phase 2: Core Team** — Invite 3-5 trusted contributors as maintainers
- **Phase 3: Foundation (If It Grows)** — Formal nonprofit or join existing org

---

## Part 5: Landscape Research

### BeatKitchenSchool:

> Is there anything like this already? Would I'd be better off lending my support to an existing framework that already has traction? Should I use Beat Kitchen as more than just a way to get the word out? Do I need to secure a website or other social media names or branding?

### Claude:

*[After searching existing frameworks]*

**What exists:**

| Framework | Purpose | Gap |
|-----------|---------|-----|
| **C2PA / Content Authenticity Initiative** | Technical standard, cryptographic metadata | Not human-readable, binary, requires tools |
| **EU AI Act Code of Practice** | Regulatory compliance (Aug 2026) | Mandatory, not creator-friendly |
| **Platform Rules (YouTube, TikTok, Meta)** | Platform-specific disclosure | Fragmented, focused on synthetic media |
| **IAB Framework** | Advertising-specific | Industry-limited |

**The Gap Your Idea Fills:**

| What exists | What's missing |
|-------------|----------------|
| Technical metadata (C2PA) | Human-readable badges |
| Binary "AI or not" | Spectrum of involvement |
| Platform-specific rules | Cross-platform standard |
| Regulatory compliance | Voluntary creator choice |
| Tool-dependent | Simple self-declaration |
| "Was AI used?" | "How was AI used?" |

**My Assessment:** Create it. Nothing currently does what you're proposing. The framework is **complementary to C2PA**, not competitive. Consider reaching out to C2PA/CAI about partnership.

**Beat Kitchen's Role:** Launch it independently, but use Beat Kitchen to announce and promote. Your story ("I needed this for my own work") is compelling. Credit yourself as founder, but don't make it a Beat Kitchen product.

**Securing Names:** Yes, do this now. Names get taken fast once an idea gets attention.

---

## Part 6: Launch Decisions

### BeatKitchenSchool:

> I'm not very good at waiting and I'm inclined to just create an announcement on Threads now and see if it has support. I just need some kind of framework in place that people can go to and contribute. How fast can I get something up safely and still retain some degree of ownership?

### Claude:

I can help you get something live in the next 30 minutes.

**Why CC BY 4.0 Protects You:**
- Anyone can use, adapt, share
- **They MUST credit you as originator**
- You can still do whatever you want with it (including commercialize later)
- It's irrevocable, but so is your attribution right

You're not giving up ownership—you're giving up *exclusivity* while keeping *credit*.

### BeatKitchenSchool:

> I want to share it with two or three people first. Is that still the right way to go?

### Claude:

Yes—private repo is exactly right for that.

**How it works:**
1. Create private repo
2. Go to Settings → Collaborators → Invite by GitHub username or email
3. They can view, comment, open issues, submit PRs
4. When ready, flip to public with one click

Your 2-3 people get early access, you refine based on their feedback, then you do the Threads announcement with something polished.

---

## Part 7: Repository Created

**Date:** January 23, 2026
**Repository:** https://github.com/BeatKitchen/AI-Transparency-Commons
**Status:** Private (seeking initial feedback)

**Files committed:**
- `README.md` — The full spec
- `LICENSE` — CC BY 4.0
- `CONTRIBUTING.md` — How people can help

**Commit message:**
> Initial draft: AI Transparency Commons v0.1
>
> A composable framework for creators to disclose AI use, inspired by Creative Commons.
>
> ATC: HO-AC-HV+D
>
> Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>

---

## Summary

This project emerged from a single frustration: "I use AI" tells people nothing useful. Over the course of one conversation, we:

1. Identified the problem
2. Proposed domain-specific labels (too complex)
3. Refined using Creative Commons as a model (composable elements)
4. Developed the three-question framework (Origin, Creation, Oversight)
5. Tested it on itself (meta-validation)
6. Researched existing frameworks (found a gap)
7. Chose a license (CC BY 4.0)
8. Created the repository

**Total time:** ~2 hours from idea to published repo.

**This project's disclosure:** `ATC: HO-AC-HV+D`

---

*Document created: January 23, 2026*
