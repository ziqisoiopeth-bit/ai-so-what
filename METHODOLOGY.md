# AI, So What? — Methodology

## What This Project Is

A systematic framework for identifying non-obvious investment opportunities in AI by mapping structural, near-certain consequences of AI across all economic activity — then deriving second-order and third-order opportunities from the intersections of those consequences.

**The analogy:** Before the internet, "people will trade online" was a near-certain premise. PayPal didn't answer "what does the internet need?" directly — they answered the second-layer question: if people trade online, they need payment infrastructure. We are doing the same thing for AI, but systematically.

**What we are NOT doing:** Chasing first-order opportunities ("AI can do X, so build X"). Those are visible to everyone, will become commodities, and are risky bets for anyone without massive resources.

## The Vision

### Layer 0: AI can do X (commodity observation — everyone sees this)
### Layer 1: "So what?" → First-order premises
Structural, near-certain consequences of AI capability. Example: "The skill scarcity pyramid flattens to a cylinder because AI makes rare cognitive skills instantly scalable."

### Layer 2: Second-order opportunities (the "PayPal moves")
Emerge from INTERACTIONS between first-order premises. These are non-obvious and defensible because they require chaining multiple layers of reasoning.

### Layer 3: Third-order opportunities (the "DeFi moves")
Emerge when second-order solutions create their own structural problems, and a new enabling technology or premise arrives to solve them. Example: PayPal → centralized payment problems → blockchain arrives → DeFi/stablecoins.

**The deeper we go, the more defensible the position.** Third-order opportunities have the strongest barriers because:
1. Few people can see them (requires chaining three layers of reasoning)
2. They depend on "missing premises" (technology not yet mature), so timing matters
3. When the missing premise arrives, the person already positioned captures it

---

## Primary Framework: Transaction Cost Economics (Coase/Williamson)

All economic activity involves five categories of cost. AI transforms each differently:

| # | Category | What it covers | File |
|---|----------|---------------|------|
| 1 | **Search** | Finding information, people, resources, opportunities | `domains/search.md` |
| 2 | **Bargaining** | Negotiating terms, contracts, pricing, agreements | `domains/bargaining.md` |
| 3 | **Enforcement** | Ensuring compliance, quality, trust, verification | `domains/enforcement.md` |
| 4 | **Production** | Actually making things — goods, services, content, knowledge | `domains/production.md` |
| 5 | **Coordination** | Organizing collective action — teams, markets, institutions | `domains/coordination.md` |

### Why Transaction Cost Economics?
- It's the most fundamental framework for economic organization
- It's what drove the internet revolution (the internet primarily reduced search and coordination costs)
- It provides a MECE (mutually exclusive, collectively exhaustive) skeleton grounded in established economics
- It lets us draw clear parallels to the internet era

### Secondary Lenses (cross-reference, not primary)
- **Factors of Production:** Labor, Capital, Land/Resources, Entrepreneurship
- **Value Chain (Porter):** R&D → Production → Distribution → Marketing → Transaction → Consumption → Support

---

## Current State: 25 First-Order Premises

We have 25 premises (5 per category), each argued in full with:
- **Claim** — one-sentence statement
- **Reasoning** — structural argument for near-certainty
- **Evidence** — current signals and data
- **Implications** — the "so what" of the "so what"
- **Certainty Rating** — High / Medium-High / Medium
- **Interactions** — how this premise connects to other categories

See `domains/*.md` for the full arguments and `synthesis/cross-category-synthesis.md` for the overview and meta-patterns.

---

## Next Step: Systematic Challenge-Opportunity Decomposition

### The Problem with the First Pass
The initial synthesis identified 7 second-order opportunities by pattern-matching — eyeballing where multiple premises converged on similar structural gaps. This was a first attempt, not systematic. It likely missed opportunities and may have included false positives.

### The Better Methodology

**Step 1: Decompose each premise into three columns**

For each of the 25 premises, extract:

| Premise | Challenges Created | Opportunities Created |
|---------|-------------------|----------------------|
| [What's happening] | [What problems/demands does this generate?] | [What solutions/value does this enable?] |

Important distinctions:
- **Not every premise creates both.** Some are pure challenge (e.g., "fakes become free" is mostly a problem). Some are pure opportunity (e.g., "cheap experimentation" is mostly upside). Most are both.
- **Distinguish internal vs external challenges.** Internal = problems within the same domain. External = problems imposed on OTHER domains. External challenges are more likely to produce cross-category second-order opportunities.

Example:
| Premise | Challenges | Opportunities |
|---------|-----------|---------------|
| S1: Judgment becomes bottleneck | Information flood can pollute judgment quality; decision fatigue; people over-rely on AI synthesis without verification | AI-ready information enables rapid judgment and action; judgment becomes the premium service; decision-support tools become valuable |

**Step 2: Cross-reference challenges against opportunities**

Take the full list of challenges across all 25 premises and the full list of opportunities across all 25 premises. Then match:

- **Does any existing premise's opportunity already resolve another premise's challenge?**
  - If YES → The system self-corrects. Mark both as "covered."
  - If NO → **Uncovered challenge = potential second-order opportunity**

This is demand-driven, not speculation-driven. Second-order opportunities emerge from actual unmet structural needs, not from pattern-matching.

**Step 3: Validate the uncovered challenges**

For each uncovered challenge (not resolved by any existing premise's opportunity):
- Is this challenge real and structural, or is it speculative?
- What would a solution look like?
- Is the solution a product/service, infrastructure layer, or policy/governance?
- How certain is the underlying premise that creates this challenge?

**Step 4: Third-order mapping**

Take the validated second-order opportunities pairwise:
- When Opportunity A and Opportunity B both exist, what does their coexistence produce?
- Is the result already absorbed by another second-order opportunity or first-order premise?
- If not → potential third-order opportunity or a missing premise in our model

Key insight for third-order: "If A is sure to happen and B is also sure to happen, then when A and B coexist they are likely to produce some outcome. We need to check whether this outcome is already absorbed by other premises in our model. If it isn't, we either have a missing premise or a genuine third-order opportunity."

---

## Already-Identified Second-Order Opportunities (First Pass — To Be Validated)

These 7 were identified via pattern-matching in the first pass. They should be re-validated using the systematic methodology above.

1. **Trust Infrastructure Layer** — verification, provenance, identity as mandatory infrastructure (from E1+E3+S3+S4)
2. **Coordination Platforms for Small Teams** — the "new firm" that lets 3-person teams coordinate like 30 (from C2+C3+C5+P3)
3. **Judgment-as-a-Service** — connecting domain judgment to AI-generated output (from S1+S2+P1+P2)
4. **Fit-Based Search / Cognitive Matching** — deep modeling of the searcher, not the searched (from S5+S4)
5. **Intelligent Friction Design** — platforms that manage friction rather than eliminate it (from S4+E1+congestion paradox)
6. **Algorithmic Governance / Auditing** — auditing the AI enforcers (from E4+E2+C3)
7. **Parametric Contract Infrastructure** — living contracts with trusted data feeds and auto-adjustment (from B3+B5+E5)

---

## Third-Order Example (Illustrative, Not Validated)

**Internet era example:**
```
Layer 1: People trade online (premise)
Layer 2: They need payment rails → PayPal
Layer 3: Centralized payment rails create problems (censorship, fees, access barriers)
         + Missing enabling premise arrives (blockchain)
         → DeFi / stablecoins
```

**AI era sketch (illustrative):**
```
Layer 1: Naive authenticity collapses (E1) + Trust tax emerges (E3)
Layer 2: Trust Infrastructure Layer becomes mandatory
Layer 3: Centralized trust infrastructure creates gatekeepers and single points of failure
         + Missing enabling premise: decentralized verification technology (ZK proofs, etc.)
         → Decentralized trust networks — provenance without central authority
```

These are examples of the pattern, not validated opportunities. The systematic methodology above should be used to identify genuine third-order plays.

---

## Premise Format

Each premise follows this format:

```markdown
## Premise: [Title]

### Claim
[One-sentence statement of the premise]

### Reasoning
[Why this is near-certain, not speculative. Structural argument.]

### Evidence
[Current signals that support this — what's already happening]

### Implications
[What follows if this premise holds — the "so what" of the "so what"]

### Certainty Rating
[High / Medium-High / Medium] — with justification

### Interactions
[How this premise connects to other categories]
```

---

## Project Context

- **Owner:** Ziqi — VC, philosopher, musician. Looking for non-obvious, defensible investment opportunities.
- **Collaborator:** AI-expert friend who will continue the systematic checking.
- **Not academic:** This is a strategic framework for identifying real opportunities, not a research paper.
- **Preference:** Full arguments, not summaries. Show reasoning so it can be interrogated.
- **Focus on certainty:** Prioritize premises that are structurally near-certain. Uncertainty enters when certain premises interact with unpredictable ones — acknowledged but not the focus.
