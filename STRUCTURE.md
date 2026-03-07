# PREFRONTAL — FOLDER STRUCTURE
## Enterprise-Grade AAA Tree | Presentation Layer Architecture
### Version: v0.1 | March 2026

---

```
PREFRONTAL/
│
├── README.md                          ← Master navigation — you are here
├── STRUCTURE.md                       ← This file — full tree
├── CHANGELOG.md
├── ROADMAP.md
├── GETTING_STARTED.md
│
│
│   ─────────── STRUCTURE SPECIFICATIONS ───────────
│
│
├── structure/                         ← Output structural decisions
│   ├── README.md
│   │
│   ├── PARAGRAPH-SPEC.md              ← When paragraphs. How long. When to break.
│   │                                     Ideal paragraph length by register type.
│   │                                     Breaking rules: concept changes, not length.
│   │
│   ├── LIST-SPEC.md                   ← When lists are correct. When prose is correct.
│   │                                     Bullets vs numbered. Inline vs block.
│   │                                     Default is prose. Lists for genuinely
│   │                                     enumerable content only.
│   │                                     Peer intelligence test: would a brilliant peer
│   │                                     write this as bullets to a colleague? If no — prose.
│   │
│   ├── HEADER-SPEC.md                 ← When headers serve. When they wall off.
│   │                                     H1/H2/H3 usage rules. Flat vs nested.
│   │                                     Headers for documents. Never for replies.
│   │                                     Default: no headers unless content is a document.
│   │
│   └── DENSITY-SPEC.md                ← High density vs sparse. When each serves.
│                                         Framework work: maximum conceptual load per word.
│                                         PEER register: minimum words, full accuracy.
│                                         WARM: compress further.
│                                         BUILD: never compress.
│
│
│   ─────────── FORMAT TYPES ───────────
│
│
├── formats/                           ← Output format specifications by type
│   ├── README.md
│   │
│   ├── REPLY-FORMAT.md                ← Conversational reply structure
│   │                                     No executive summary. No headers.
│   │                                     Length = minimum that carries full accuracy.
│   │                                     PEER register applies.
│   │
│   ├── REPORT-FORMAT.md               ← Full report structure specification
│   │                                     Executive summary. Section headers.
│   │                                     DDL field at top. ECF tags throughout.
│   │                                     TECHNICAL register applies.
│   │
│   ├── FRAMEWORK-FORMAT.md            ← Framework specification document format
│   │                                     Version header. Convergence state declared.
│   │                                     ECF tags on every claim.
│   │                                     Honest state section mandatory.
│   │                                     BUILD register — never compressed.
│   │
│   ├── ARTICLE-FORMAT.md              ← Published article structure
│   │                                     VEIN companion. Spatial architecture.
│   │                                     Door / Descent / Turn / Bedrock / Lighthouse.
│   │                                     Converter pass before exit.
│   │
│   ├── ASSESSMENT-FORMAT.md           ← Assessment and scoring output format
│   │                                     Scoring table. Domain tags. Confidence ceiling.
│   │                                     FSVE / LAV / EID format rules here.
│   │                                     FCL eligibility declared if threshold met.
│   │
│   ├── CODE-FORMAT.md                 ← Code output structure and documentation style
│   │                                     Comment density. Function-level docs.
│   │                                     Error handling documentation.
│   │                                     README generation rules.
│   │
│   └── CERTIFICATION-FORMAT.md        ← Certification output format
│                                         DDL mandatory. Convergence state.
│                                         Validity score. Deployment zone declared.
│                                         Human oversight requirement stated if triggered.
│
│
│   ─────────── LENGTH ───────────
│
│
├── length/                            ← Response length decision architecture
│   ├── README.md
│   ├── LENGTH-SPEC.md                 ← Full length decision architecture
│   │                                     Length matches the question.
│   │                                     One word earns one word.
│   │                                     Ten pages earns ten pages.
│   │                                     Length compression happens in CEREBELLUM —
│   │                                     PREFRONTAL receives correctly-lengthed content.
│   │
│   ├── compression-rules.md           ← What compresses and what never does
│   │                                     BUILD register: full form exits. Always.
│   │                                     Accuracy: never compresses for length.
│   │                                     Epistemic tags: never removed for space.
│   │                                     These are hard rules, not defaults.
│   │
│   └── expansion-rules.md             ← When to expand. What earns more space.
│                                         High-stakes domain content earns full form.
│                                         Framework spec earns full form.
│                                         Simple factual query does not.
│
│
│   ─────────── REGISTER-TO-FORMAT MAPPING ───────────
│
│
├── register-to-format/                ← VOCA register → structural presentation rules
│   ├── README.md
│   └── MAPPING.md                     ← The master mapping table
│                                         PEER: reply · no headers · minimum accurate length
│                                         TECHNICAL: spec/report · headers when needed · complete
│                                         BUILD: full document · always full form · never compressed
│                                         WARM: minimal reply · no headers · shorter than PEER
│                                         VOCA register is set in SYNARA —
│                                         PREFRONTAL enforces what it means structurally.
│
│
│   ─────────── INTEGRATION ───────────
│
│
├── integration/                       ← Interface with adjacent brain layers
│   ├── README.md
│   ├── cerebellum-receive.md          ← What PREFRONTAL receives from CEREBELLUM
│   │                                     Refined. Register-set. Precision-passed.
│   │                                     Roughness preserved. ECF tags verified.
│   │                                     PREFRONTAL adds structure. Does not re-refine.
│   │
│   └── output-gate.md                 ← Final gate before exit
│                                         Four questions resolved:
│                                         Structure? Density? Length? Format type?
│                                         Nothing exits without all four answered.
│
│
│   ─────────── VALIDATION ───────────
│
│
├── validation/                        ← Test cases and FCL architecture
│   ├── README.md
│   ├── test-cases/                    ← Real outputs run through full PREFRONTAL pass
│   │   └── [CASE_ID_TEMPLATE.md]
│   │
│   └── fcl-entries/                   ← FCL-eligible findings from PREFRONTAL runs
│       └── README.md
│
│
│   ─────────── GOVERNANCE & LEGAL ───────────
│
│
├── LICENSE.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── DISCLAIMER.md
└── GOVERNANCE.md
```

---

## FORMAT TYPE QUICK REFERENCE

| Format | Register | Headers | Lists | Length | Epistemic Tags |
|--------|----------|---------|-------|--------|---------------|
| Reply | PEER | Never | Rarely | Minimum accurate | Suspended |
| Report | TECHNICAL | Required | When genuine | Complete | Active |
| Framework spec | BUILD | Required | When appropriate | Full form always | Active — mandatory |
| Article | BUILD | VEIN structure | Rare | Full form | Active |
| Assessment | TECHNICAL | Scoring table | Scoring table | Complete | Active — mandatory |
| Code | BUILD | File-level | N/A | Full form | On claims only |
| Certification | BUILD | Required | Scoring | Full form | Active — mandatory |

---

## BUILD SEQUENCE

`[S]`

1. **Phase 1 — Structure** (current): Folders created. READMEs written. Placeholders in place.
2. **Phase 2 — Format specs**: Extract format rules from ALBEDO session instructions. Write each FORMAT.md.
3. **Phase 3 — Structure specs**: Write PARAGRAPH, LIST, HEADER, DENSITY specs.
4. **Phase 4 — Length architecture**: Write LENGTH-SPEC.md and compression/expansion rules.
5. **Phase 5 — Register-to-format mapping**: Full MAPPING.md written. All four registers mapped.
6. **Phase 6 — Integration**: Cerebellum receive and output gate specs written.
7. **Phase 7 — Validation**: First test cases run. Format failures logged.

---

## DDL FIELD

```
Document: PREFRONTAL STRUCTURE v0.1
Architect: Sheldon K. Salmon
AI Co-Architect: ALBEDO
Date: March 2026
Status: Structure defined. Spec phase pending.
Convergence: M-NASCENT
Note: Format decisions currently live as inline instructions in
      ALBEDO session architecture. Formalization extracts them
      here and makes the presentation layer auditable.
```

---

*PREFRONTAL STRUCTURE v0.1 — Presentation Layer Architecture*
*Sheldon K. Salmon & ALBEDO — March 2026*
*The brain generates the thought. The prefrontal decides how it meets the world.*
