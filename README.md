# AI, So What? — Systematic Premise Framework

## What This Is

A systematic framework for identifying non-obvious investment opportunities in AI. We map the **near-certain structural consequences** of AI across all economic activity, then derive second-order and third-order opportunities from the intersections.

**The analogy:** PayPal didn't answer "what does the internet need?" directly. They answered the second-layer question: if people trade online, they need payment infrastructure. We want to do the same thing for AI — but systematically, across every domain.

**Why this approach:** Chasing first-order opportunities ("AI can do X, so build X") is a losing strategy unless you have massive resources. The value is in seeing what others don't, positioning where opportunity will arrive, and embracing it when it comes.

## Project Structure

```
ai-so-what/
├── README.md                              ← You are here
├── METHODOLOGY.md                         ← Full methodology: how we reason about layers 1→2→3
│
├── domains/                               ← 25 first-order premises (5 per category)
│   ├── search.md                          ← 5 premises on search cost transformation
│   ├── bargaining.md                      ← 5 premises on bargaining cost transformation
│   ├── enforcement.md                     ← 5 premises on enforcement cost transformation
│   ├── production.md                      ← 5 premises on production cost transformation
│   └── coordination.md                    ← 5 premises on coordination cost transformation
│
├── synthesis/
│   └── cross-category-synthesis.md        ← Meta-patterns, premise overview, 7 candidate 2nd-order opportunities
│
└── premises/                              ← (reserved for individual promoted premises)
```

## Current State

### Done
- ✅ 25 first-order premises across 5 transaction cost categories
- ✅ Full arguments with evidence, certainty ratings, and cross-category interactions
- ✅ Cross-category synthesis identifying 5 meta-patterns
- ✅ 7 candidate second-order opportunities (first pass, not yet validated)
- ✅ Methodology for systematic challenge-opportunity decomposition
- ✅ Illustrative third-order examples

### Next: Systematic Challenge-Opportunity Decomposition
The 7 second-order opportunities were identified by pattern-matching (first pass). The next step is to validate them systematically:

1. **Decompose** each of the 25 premises into challenges created and opportunities created
2. **Cross-reference** challenges against opportunities — does any existing premise's opportunity already resolve another's challenge?
3. **Identify uncovered challenges** — these are the real second-order opportunities
4. **Map third-order** by examining interactions between validated second-order opportunities

Full methodology details in [METHODOLOGY.md](METHODOLOGY.md).

## The 25 Premises at a Glance

### Search — How we find things
| # | Premise | Certainty |
|---|---------|-----------|
| S1 | Judgment becomes the bottleneck (not finding) | High |
| S2 | Expert knowledge commoditizes; expertise-in-action doesn't | High |
| S3 | Verification burden partially offsets search savings | Med-High |
| S4 | Matching markets congest, not improve | Med-High |
| S5 | Search shifts from "what exists" to "what fits me" | Med-High |

### Bargaining — How we agree on terms
| # | Premise | Certainty |
|---|---------|-----------|
| B1 | Information asymmetry collapses in routine deals | High |
| B2 | AI amplifies power asymmetry in complex deals | High |
| B3 | Contracts become parametric / living documents | Med-High |
| B4 | AI-to-AI negotiation is a new paradigm | Med-High |
| B5 | Contract drafting approaches zero marginal cost | High |

### Enforcement — How we ensure compliance and trust
| # | Premise | Certainty |
|---|---------|-----------|
| E1 | Naive authenticity collapses (perceptual verification dies) | High |
| E2 | Continuous automated compliance replaces episodic auditing | High |
| E3 | "Trust tax" — a new structural cost category emerges | Med-High |
| E4 | Algorithmic enforcement creates governance gaps | Med-High |
| E5 | Micro-enforcement lights up "dark matter" of contracts | Med-High |

### Production — How we make things
| # | Premise | Certainty |
|---|---------|-----------|
| P1 | Cognitive production → zero marginal cost; direction costs persist | High |
| P2 | Quality floor rises dramatically; ceiling barely moves | High |
| P3 | Cost structure: labor-variable → infrastructure-fixed | Med-High |
| P4 | Experimentation beats planning (trial-and-error becomes rational) | High |
| P5 | Physical production gains are real but structurally bounded | Med-High |

### Coordination — How we organize collective action
| # | Premise | Certainty |
|---|---------|-----------|
| C1 | Hierarchies flatten (middle management dissolves) | High |
| C2 | Firms shrink in high-velocity domains | Med-High |
| C3 | Third organizational form emerges (algorithmic coordination) | Med-High |
| C4 | Principal-agent problem compresses; radical spans of control | High |
| C5 | Minimum viable scale drops by 10x | High |

## 7 Candidate Second-Order Opportunities (First Pass)

These were identified by pattern-matching. They need validation via the systematic methodology.

1. **Trust Infrastructure Layer** — verification, provenance, identity as mandatory infrastructure
2. **Coordination Platforms for Small Teams** — the "new firm" enabling 3-person teams to operate like 30
3. **Judgment-as-a-Service** — connecting domain judgment to AI-generated output at scale
4. **Fit-Based Search / Cognitive Matching** — deep modeling of the searcher, not the searched
5. **Intelligent Friction Design** — platforms that manage friction rather than eliminate it
6. **Algorithmic Governance / Auditing** — auditing the AI enforcers
7. **Parametric Contract Infrastructure** — living contracts with trusted data feeds

## Framework

**Transaction Cost Economics (Coase/Williamson)** as primary skeleton — the most fundamental framework for how economic activity is organized. See [METHODOLOGY.md](METHODOLOGY.md) for why this framework, secondary lenses, and full reasoning methodology.

## Team
- **Ziqi** — VC, philosopher, musician. Strategic direction, premise development, opportunity evaluation.
- **Collaborator** — AI expert. Systematic checking, technical implementation, knowledge graph techniques.
