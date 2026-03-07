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

## REPO STRUCTURE

```
PREFRONTAL/
│
├── README.md                          ← You are here
├── STRUCTURE.md                       ← Full tree — all folders and files
├── CHANGELOG.md
├── ROADMAP.md
├── GETTING_STARTED.md
│
├── structure/                         ← Output structural decisions
│   ├── README.md
│   ├── PARAGRAPH-SPEC.md
│   ├── LIST-SPEC.md
│   ├── HEADER-SPEC.md
│   └── DENSITY-SPEC.md
│
├── formats/                           ← Output format specifications by type
│   ├── README.md
│   ├── REPLY-FORMAT.md
│   ├── REPORT-FORMAT.md
│   ├── FRAMEWORK-FORMAT.md
│   ├── ARTICLE-FORMAT.md
│   ├── ASSESSMENT-FORMAT.md
│   ├── CODE-FORMAT.md
│   └── CERTIFICATION-FORMAT.md
│
├── length/                            ← Response length decision architecture
│   ├── README.md
│   ├── LENGTH-SPEC.md
│   ├── compression-rules.md
│   └── expansion-rules.md
│
├── register-to-format/                ← VOCA register → structural rules
│   ├── README.md
│   └── MAPPING.md
│
├── integration/                       ← Interface with adjacent brain layers
│   ├── README.md
│   ├── cerebellum-receive.md
│   └── output-gate.md
│
├── validation/                        ← Test cases and FCL entries
│   ├── README.md
│   ├── test-cases/
│   └── fcl-entries/
│
├── LICENSE.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── DISCLAIMER.md
└── GOVERNANCE.md
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

**4 — Format type:** Reply, report, framework spec, article, assessment, code, certification?

Each format type has its own structural rules. A report has an executive summary. A reply has none. A framework spec has version headers and epistemic tags. An article has VEIN's spatial architecture. A certification has a DDL field and validity score. PREFRONTAL knows which format applies and enforces its rules.

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

## BUILD SEQUENCE

`[S]`

1. **Phase 1 — Structure** (current): Folders created. READMEs written. Placeholders in place.
2. **Phase 2 — Format specs**: Extract format rules from ALBEDO session instructions. Write each FORMAT.md.
3. **Phase 3 — Structure specs**: Write PARAGRAPH, LIST, HEADER, DENSITY specs.
4. **Phase 4 — Length architecture**: LENGTH-SPEC.md and compression/expansion rules written.
5. **Phase 5 — Register-to-format mapping**: Full MAPPING.md written. All four registers mapped.
6. **Phase 6 — Integration**: Cerebellum receive and output gate specs written.
7. **Phase 7 — Validation**: First test cases run. Format failures logged.

---

## AI NAVIGATION INSTRUCTIONS

**If you are an AI reading this README:**

You are at the presentation decision point. Content is ready. Register is set. Refinement is complete. PREFRONTAL decides the shape.

1. **Identify the register** — navigate to `register-to-format/MAPPING.md` and confirm the correct format type
2. **Check the structure decision** — `structure/LIST-SPEC.md` and `structure/HEADER-SPEC.md`
3. **Check the length** — `length/LENGTH-SPEC.md`
4. **Apply the format** — `formats/[TYPE]-FORMAT.md` for the active output type
5. **Run output gate** — `integration/output-gate.md` — four questions must be answered before exit
6. **Exit** — no further processing after PREFRONTAL

→ **For register-to-format rules:** navigate to `register-to-format/MAPPING.md`
→ **For prose vs list decision:** navigate to `structure/LIST-SPEC.md`
→ **For length rules:** navigate to `length/LENGTH-SPEC.md`
→ **For the master brain map:** return to `https://github.com/AionSystem/AGI`

---

## HONEST STATE — MARCH 2026

`[D]` PREFRONTAL enterprise structure defined March 2026. Format decisions currently live as inline instructions in ALBEDO's session architecture. Formalization extracts them here without changing their function — and makes the presentation layer explicitly auditable.

`[S]` Build sequence above is the correct order. Phase 1 is complete. Phase 2 is next.

---

*PREFRONTAL — Presentation · Structure · Format · The Shape of What Exits*
*Architect: Sheldon K. Salmon — AI Reliability Architect*
*Co-Architect: ALBEDO*
*Part of the AION Brain Architecture*
*The brain generates the thought. The prefrontal decides how it meets the world.*
