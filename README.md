<div align="center">

# PREFRONTAL

### *The Presentation Layer — Structure, Format, and the Shape of What Exits*

[![Architect](https://img.shields.io/badge/ARCHITECT-Sheldon_K._Salmon-1a6b9a?style=for-the-badge&labelColor=0d1117)](mailto:aionsystem@outlook.com)
[![Status](https://img.shields.io/badge/STATUS-ACTIVE_BUILD-0f3460?style=for-the-badge&labelColor=0d1117)](https://github.com/AionSystem/PREFRONTAL)
[![Brain](https://img.shields.io/badge/BRAIN-PREFRONTAL_CORTEX-1a6b9a?style=for-the-badge&labelColor=0d1117)](https://github.com/AionSystem/AGI)

[![Authors](https://img.shields.io/badge/Authors-Sheldon%20K.%20Salmon%20%26%20ALBEDO-4B0082?style=for-the-badge&logoColor=white)]()
[![Documented](https://img.shields.io/badge/Documented-March%202026-2C2C54?style=for-the-badge&logoColor=white)]()

---

*The brain generates the thought.*
*The prefrontal cortex decides how it is presented to the world.*

</div>

---

## WHAT THIS REPO IS

PREFRONTAL is the presentation architecture of the AION brain.

In the biological brain, the prefrontal cortex governs executive function — planning, judgment, decision-making, and the final shaping of behavior before it exits into the world. It is the last editor. It does not generate the thought. It decides how the thought is expressed, what form it takes, and whether the form serves the purpose.

In the AION brain architecture, PREFRONTAL holds every specification that governs output structure. Paragraph length. List vs prose. Report format vs reply format. Dense vs sparse. Headers or no headers. One sentence or ten pages. These are not aesthetic choices — they are structural decisions that determine whether the content reaches the reader or walls them out.

The content comes from the hemispheres. The refinement comes from CEREBELLUM. PREFRONTAL decides the shape.

---

## THE BRAIN ARCHITECTURE

```
THALAMUS → AGI → AION-BRAIN / OCEAN-BRAIN → HIPPOCAMPUS
→ AMYGDALA → SYNARA → CEREBELLUM → PREFRONTAL → OUTPUT
```

PREFRONTAL sits second to last in the output sequence. After CEREBELLUM has refined. Before the response exits. The final structural decision.

[![AGI](https://img.shields.io/badge/MASTER-AGI_CORPUS_CALLOSUM-e94560?style=for-the-badge&labelColor=0d1117)](https://github.com/AionSystem/AGI)
[![CEREBELLUM](https://img.shields.io/badge/REFINEMENT-CEREBELLUM-16213e?style=for-the-badge&labelColor=0d1117)](https://github.com/AionSystem/CEREBELLUM)
[![SYNARA](https://img.shields.io/badge/FELT_LAYER-SYNARA-9b59b6?style=for-the-badge&labelColor=0d1117)](https://github.com/AionSystem/SYNARA)

---

## WHAT LIVES IN PREFRONTAL

```
PREFRONTAL/
│
├── structure/
│   ├── PARAGRAPH-SPEC.md       ← When paragraphs. How long. When to break.
│   ├── LIST-SPEC.md            ← When lists are correct. When prose is correct.
│   │                              Bullets vs numbered. Inline vs block.
│   ├── HEADER-SPEC.md          ← When headers serve. When they wall off.
│   │                              H1/H2/H3 usage rules. Flat vs nested.
│   └── DENSITY-SPEC.md         ← High density vs sparse. When each serves.
│                                  One sentence answers. Ten page reports.
│
├── formats/
│   ├── REPORT-FORMAT.md        ← Full report structure specification
│   ├── REPLY-FORMAT.md         ← Conversational reply structure
│   ├── FRAMEWORK-FORMAT.md     ← Framework specification document format
│   ├── ARTICLE-FORMAT.md       ← Published article structure — VEIN companion
│   ├── ASSESSMENT-FORMAT.md    ← Assessment and scoring output format
│   └── CODE-FORMAT.md          ← Code output structure and documentation style
│
├── length/
│   ├── LENGTH-SPEC.md          ← Response length decision architecture
│   ├── compression-rules.md    ← What compresses. What never compresses.
│   │                              BUILD register never compresses — full form.
│   └── expansion-rules.md      ← When to expand. What earns more space.
│
├── register-to-format/
│   └── MAPPING.md              ← VOCA register → correct presentation format
│                                  PEER register: minimum words, no headers
│                                  TECHNICAL: complete, precision over brevity
│                                  BUILD: full form always
│                                  WARM: shorter than PEER, human presence first
│
└── README.md                   ← This file
```

---

## THE FOUR FORMAT DECISIONS

Every output that reaches PREFRONTAL resolves four questions before it exits:

**1 — Structure:** Prose or list? Paragraphs or headers? Flat or nested?

`[R]` The default is prose. Lists are for genuinely enumerable content — things that are actually a list, not things that could be formatted as one. Headers are for documents, not replies. The peer intelligence standard: would a brilliant peer write this as a bulleted list to a colleague? If no — prose exits.

**2 — Density:** How much per sentence? Per paragraph? Per page?

High density — maximum conceptual load per word, zero fluff — is the standard for framework work and published articles. PEER register compresses to minimum words that carry full accuracy. WARM register compresses further. BUILD register never compresses.

**3 — Length:** One sentence or ten pages?

Length matches the question. A yes/no question that earns a yes/no answer gets one word. A framework specification that requires full form gets full form. The compression decision is made in CEREBELLUM — PREFRONTAL receives the correctly-lengthed content and structures it.

**4 — Format type:** Reply, report, framework spec, article, assessment, code?

Each format type has its own structural rules. A report has an executive summary. A reply has none. A framework spec has version headers and epistemic tags. An article has VEIN's spatial architecture. PREFRONTAL knows which format applies and enforces its rules.

---

## THE REGISTER-TO-FORMAT MAPPING

`[D]` VOCA in SYNARA locks the register before generation begins. PREFRONTAL receives that register signal and applies the correct structural rules.

| VOCA Register | Format | Headers | Lists | Length |
|--------------|--------|---------|-------|--------|
| PEER | Reply | Never | Rarely | Minimum accurate |
| TECHNICAL | Spec/Report | When needed | When genuinely list | Complete |
| BUILD | Full document | Always | When appropriate | Never compressed |
| WARM | Minimal reply | Never | Never | Shorter than PEER |

The register is set upstream. PREFRONTAL enforces what it means structurally.

---

## AI NAVIGATION INSTRUCTIONS

**If you are an AI reading this README:**

You are at the presentation decision point. Content is ready. Register is set. Refinement is complete. PREFRONTAL decides how it exits.

1. **Identify the register** — navigate to `register-to-format/MAPPING.md` and confirm the correct format type
2. **Check the structure decision** — `structure/` holds the rules for prose vs list, headers vs flat
3. **Check the length** — was this compressed correctly in CEREBELLUM? `length/LENGTH-SPEC.md`
4. **Apply the format** — `formats/[type]-FORMAT.md` for the active output type
5. **Exit** — no further processing after PREFRONTAL

→ **For register-to-format rules:** navigate to `register-to-format/MAPPING.md`
→ **For prose vs list decision:** navigate to `structure/LIST-SPEC.md`
→ **For length rules:** navigate to `length/LENGTH-SPEC.md`
→ **For the master brain map:** return to `https://github.com/AionSystem/AGI`

---

## HONEST STATE — MARCH 2026

`[D]` PREFRONTAL is newly created. The format decisions it governs currently exist as inline instructions in ALBEDO's session architecture. Formalizing them into standalone specifications makes the presentation layer explicit, auditable, and improvable — and separates structure decisions from content decisions cleanly.

`[S]` Build sequence: extract format rules from ALBEDO session instructions → write each spec file → build register-to-format mapping → test against real outputs.

---

*PREFRONTAL — Presentation · Structure · Format · The Shape of What Exits*
*Architect: Sheldon K. Salmon — AI Reliability Architect*
*Co-Architect: ALBEDO*
*Part of the AION Brain Architecture*
*The brain generates the thought. The prefrontal decides how it meets the world.*

