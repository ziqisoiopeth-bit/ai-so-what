# Production Costs — How AI Transforms the Costs of Actually Making Things

Production costs are the costs of creating goods, services, content, knowledge, and decisions. In Transaction Cost Economics, these are distinct from the costs of finding, negotiating, enforcing, or coordinating — they are the costs of the work itself.

AI's impact on production costs is arguably the most structurally dramatic of the five categories, because AI is fundamentally a production technology: it produces text, code, images, analysis, and decisions. The premises below are adjacent to and build on Ziqi's skill scarcity premise (the pyramid-to-cylinder flattening), which addresses the supply side of cognitive labor. These premises address the cost structure, quality distribution, and strategic implications of that same transformation.

---

## Premise 1: The Marginal Cost of Cognitive Production Approaches Zero — But the Fixed Cost of Directing It Does Not

### Claim
For any cognitive output that can be specified in a prompt (code, text, analysis, design drafts, legal documents, translations), the marginal cost of producing one more unit is collapsing toward zero, but the cost of knowing *what to produce* and *whether it's good* remains stubbornly human.

### Reasoning
This is a straightforward consequence of the economics of software. Once an AI model exists (massive fixed cost: $100M+ to train GPT-4-class models), each additional inference is nearly free — fractions of a cent per page of text, under $1 per line of code when amortized. Jonathan Fulton's analysis shows the cost per line of code dropping from $44 (human-only) to potentially under $1 with AI assistance. The structural reason this is near-certain: AI inference follows a deflationary cost curve (Sam Altman's claim of 10x cost reduction per year in per-token pricing is roughly borne out — GPT-4 to GPT-4o saw ~150x price decline). Meanwhile, the cost of *specifying what to build* — understanding a customer's problem, judging architectural tradeoffs, deciding what's worth building at all — remains a function of human experience, context, and taste. These are not promptable skills; they require situated judgment.

The key structural distinction: production splits into two layers. Layer 1 is "generation" — producing the artifact. Layer 2 is "direction" — deciding what to generate, evaluating whether it's right, and iterating. AI collapses Layer 1 costs. Layer 2 costs are unchanged or even *increasing* (because the volume of output to evaluate grows).

### Evidence
- Cost per line of code: $44 (pre-AI) to under $1 (AI-assisted), per Fulton's analysis (March 2026).
- BCG case study: pharmaceutical company reduced clinical study report drafting from 17 weeks to 5 weeks; summarizing a medical study went from 20-25 hours to "nearly instantaneously." But human review and approval time was largely unchanged.
- Marketing content: BCG reports unbranded website articles went from $20,000+ to "nearly free" to produce, but campaign strategy and judgment remained human-driven. Savings: $80M-$170M projected.
- 4% of all GitHub public commits are now authored by Claude Code (doubling monthly), but the humans are still deciding *what* to commit and *whether* it should ship.
- LinkedIn's Josh Berry: "AI has dramatically lowered the cost of building software. But it hasn't lowered the cost of building the wrong thing."

### Implications
1. **Value migrates from execution to direction.** The person who can correctly specify what to build, evaluate whether it's right, and know when to stop iterating becomes far more valuable than the person who can build it. This is a massive inversion: historically, the builder (developer, designer, analyst) captured most of the value. Now the specifier/evaluator does.
2. **Overproduction becomes the default failure mode.** When producing is nearly free, the bottleneck shifts to curation. Organizations will drown in AI-generated drafts, analyses, and code — unless they develop strong filtering and evaluation capacity.
3. **"Taste" becomes an economic input, not an aesthetic preference.** The ability to distinguish good output from mediocre output at volume is no longer a luxury — it's an operational necessity. This is not vague hand-waving about creativity; it's a concrete economic function: someone must evaluate outputs, and doing so correctly has direct cost and quality implications.

### Certainty Rating
**High.** The deflationary trajectory of inference costs is well-established and accelerating. The persistence of direction costs is evident in every case study: human review, judgment, and specification remain in the loop even when generation is automated. No plausible near-term technology eliminates the need for human direction of AI production.

### Interactions
- **Search costs:** As production becomes cheap, the cost of searching for the *right thing to produce* (market research, customer understanding) becomes relatively more important. Search and production costs are inversely correlated in weight.
- **Enforcement costs:** Cheap production + expensive evaluation = a quality assurance challenge. Enforcement mechanisms must scale to match output volume.
- **Coordination costs:** When any team member can produce at scale, coordinating who produces what (and avoiding duplication/contradiction) becomes harder.

---

## Premise 2: The Quality Floor Rises Dramatically, But the Quality Ceiling Barely Moves

### Claim
AI raises the minimum quality of cognitive output (the "floor") far more than it raises the maximum quality (the "ceiling"), compressing the quality distribution and commoditizing the middle of the skill range.

### Reasoning
Consider the distribution of quality for any cognitive task — say, writing a contract, producing a marketing email, or writing a Python script. Pre-AI, there was enormous variance: a junior's first draft might be 30% as good as an expert's. AI compresses this distribution from the bottom. A junior lawyer using AI can now produce a contract draft that's perhaps 75-80% as good as an expert's, because the AI encodes the median of professional practice. But the expert, also using AI, only moves from 95% to maybe 97% — diminishing returns at the top.

This is structurally inevitable because of how LLMs work: they are trained on the statistical center of human performance (the internet's aggregate output). They are excellent at reproducing median-quality work and poor at exceeding the frontier. The skill scarcity premise describes the supply-side flooding; this premise describes the quality-side consequence. When supply floods, it floods at a specific quality level: good-enough.

### Evidence
- CIO.com reports developers increased output by up to 40% with AI assistants, but code quality (including security) has become a concern: "the volume of unverified code entering production is also rising."
- Sam Schillace (Microsoft) predicts software will look more like manufacturing: a few highly talented engineers overseeing "factories," most engineers becoming low-paid "line workers." This is the quality-floor-rise in action — the line work is commoditized.
- Siemens reports AI-enabled robots "reduce automation costs by 90%" while also empowering manual workers with "AI-guided systems, enhancing productivity and quality" — the floor rises, not the ceiling.
- Midea Group: "53% reduction in poor quality" — explicitly a floor-raising metric.
- In legal work, Thomson Reuters reports legal professionals spend 40-60% of time on document work. AI tools like CoCounsel produce competent first drafts, but attorneys still provide "judgment, architecture, complex integrations, and accountability." The floor rises; the ceiling is still human.

### Implications
1. **The middle of the professional skill distribution is the kill zone.** If you're a mid-tier developer, writer, analyst, or designer, your output quality is now achievable by a junior-with-AI at a fraction of the cost. The value of being "pretty good" collapses.
2. **Premium positioning becomes both harder and more valuable.** If the floor is 75% of the ceiling, justifying the remaining 25% requires clear articulation of what that gap buys. In domains where "good enough" is actually good enough (routine contracts, standard marketing copy, boilerplate code), the premium collapses. In domains where the last 25% matters enormously (litigation strategy, novel architecture, creative direction), the premium increases.
3. **Hiring shifts from filtering for competence to filtering for excellence.** When AI guarantees competence, the interview question changes from "can you do this?" to "can you do the part AI can't?"

### Certainty Rating
**High.** This is observable right now. The floor-raising effect is a direct, mechanical consequence of how LLMs generate output (interpolation from training data, which clusters around median quality). The ceiling-stagnation is a direct consequence of the same mechanism: models cannot reliably exceed the quality of their training data's best examples.

### Interactions
- **Skill scarcity premise (Ziqi's):** Directly complementary. The pyramid flattens *because* the quality floor rises. The cylinder is a cylinder of "good enough."
- **Enforcement costs:** When the floor rises, the *type* of enforcement needed changes — less about catching incompetence, more about distinguishing "good enough" from "actually good."
- **Bargaining costs:** Harder to justify premium pricing when AI-generated alternatives look similar to the untrained eye. Bargaining becomes about demonstrating the value of the quality ceiling.

---

## Premise 3: Production Economics Shift from "Labor-Variable" to "Infrastructure-Fixed"

### Claim
AI transforms the cost structure of cognitive production from primarily variable (scaling with human headcount) to primarily fixed (scaling with infrastructure investment), making cognitive production economically resemble manufacturing or software distribution.

### Reasoning
Pre-AI, if you wanted to produce twice as many legal briefs, marketing campaigns, or code modules, you hired roughly twice as many people. Cost scaled linearly with output. With AI, the economics change: you invest in AI infrastructure (subscriptions, API costs, fine-tuning, prompt engineering, evaluation pipelines) as a fixed cost, and then the marginal cost of each additional unit of output is near-zero (just inference costs, which are small and declining).

This is the same structural shift that happened when manufacturing moved from artisan production to factory production: high fixed costs (build the factory), low marginal costs (run the factory). And it's the same shift that happened with software: high fixed costs (write the code), zero marginal costs (distribute it). Now cognitive work follows the same pattern.

However — and this is a crucial nuance — AI-powered production is not *purely* fixed-cost like traditional software distribution. Inference costs create a new kind of variable cost: each AI-generated output consumes real compute. As Sam Schillace argues, this pushes software economics toward looking more like manufacturing (with a "cost of goods sold") than like traditional software (with near-zero COGS). The net effect is that cognitive production moves from labor-variable to infrastructure-variable, with much lower variable costs per unit but non-zero COGS.

### Evidence
- Daniel Fernandez (Medium): "Tasks that once required teams of people — customer service, data entry, content production — can now be handled by AI at scale. Fixed costs begin to resemble variable ones, transforming significant upfront investments into flexible, pay-as-you-go operations."
- Inference costs dominate: 80-90% of total AI compute spend goes to inference, not training. This is the new COGS.
- Sam Schillace (Microsoft CVP): "There is an incremental cost now to shipping AI-based software (inference) — each new user costs money to serve... All of that is pushing software to look more like that chocolate company, where there isn't as much leverage from scale."
- Fulton's analysis: at 2x developer productivity, AI adds less than 10% to total development costs (even at the high end). The cost of the AI infrastructure is dwarfed by existing salary budgets — for now. But as the ratio shifts, the infrastructure becomes the primary cost.
- NVIDIA State of AI 2026: 87% of companies report AI reduced annual costs; 88% report increased revenue. The mechanism is headcount leverage — same people, more output.

### Implications
1. **Scale advantages shift from labor markets to infrastructure.** Companies that can amortize AI infrastructure costs across more output (more products, more customers, more markets) win. This favors larger firms and platforms — or very small firms that can rent infrastructure cheaply.
2. **The "missing middle" widens.** Mid-sized firms that are too large to be nimble but too small to amortize fixed AI costs may get squeezed. Either you're small enough that API costs are trivial (a solo developer with Claude Code) or large enough that enterprise AI infrastructure is amortized across thousands of employees.
3. **SaaS pricing models must change.** If vendors' production costs drop dramatically but they maintain per-seat pricing, customers will demand better terms. The CIO.com article explicitly identifies this: "If a vendor claims major internal productivity gains, enterprise buyers should ask where that shows up." Expect migration toward usage-based, outcome-based, or value-based pricing.
4. **The "inference COGS" creates a new cost discipline.** Unlike traditional software (write once, serve forever at near-zero cost), AI-powered products have real per-use costs. This changes unit economics fundamentally and requires new financial disciplines around AI cost management.

### Certainty Rating
**Medium-High.** The direction of the shift is certain; the magnitude and speed are less clear. The shift from labor-variable to infrastructure-fixed is already observable. The nuance about inference COGS creating a new variable cost layer is also well-established. What's less certain is the equilibrium: as inference costs continue to fall (10x/year), the variable cost component may become negligible, making it look more like traditional software. Or, if model capabilities require ever-larger models and context windows, inference costs may stay material.

### Interactions
- **Coordination costs:** When production is infrastructure-fixed, coordinating capital allocation (where to invest in AI infrastructure) replaces coordinating labor allocation (who works on what). Different coordination problem, different skills needed.
- **Search costs:** Fixed-cost production means the unit cost of *trying things* drops. This has massive implications for experimentation and search (see Premise 4).
- **Bargaining costs:** Labor negotiations decline in importance; infrastructure/vendor negotiations increase. Procurement of AI services becomes a core strategic function.

---

## Premise 4: The Cost of Experimentation Collapses, Making Trial-and-Error Rational Where Planning Was Previously Required

### Claim
When producing a prototype, draft, or proof-of-concept costs nearly nothing, the rational strategy shifts from "plan carefully, then build" to "build many, then select." This inverts the traditional production logic in most knowledge-intensive industries.

### Reasoning
The cost of experimentation has historically been a function of the cost of production. If building a prototype takes six engineers two months, you plan carefully to make sure you're building the right thing. If building a prototype takes one person and one afternoon with AI, you build five prototypes and test them all. The expected-value calculation changes: when the cost of each experiment approaches zero, the optimal number of experiments approaches infinity (bounded only by evaluation costs — see Premise 1).

This is not a speculative claim about future capability; it's a direct mathematical consequence of near-zero marginal production costs. The shift from planning-heavy to experiment-heavy strategies is structurally analogous to what happened in software when cloud computing eliminated the cost of provisioning servers: you stopped planning capacity and started auto-scaling.

### Evidence
- Eaton's generative AI reduced product design time by up to 87% (aPriori case study). This doesn't just mean faster design — it means you can explore 8x more design alternatives in the same time.
- BCG pharma case study: drug development documents that took 17 weeks now take 5. The time saved enables more iteration, not just faster completion.
- UX Collective (Feb 2026): "AI app-building tools have made it inconsequential and mundane to turn an idea into a working prototype. You only need a couple prompts, a design file, or even a sketch to quickly generate something that looks (even behaves) like a real product."
- Vibe coding: entire applications built from natural language descriptions in hours. The implication is not that these apps are production-ready, but that the cost of testing an idea has dropped from weeks/months to hours.
- OpenMetal on fixed AI infrastructure: "You can run 50 training experiments or 5 without changing your monthly bill. This removes the psychological and bureaucratic barriers to innovation."

### Implications
1. **Planning becomes less valuable than selection.** The skill of carefully planning what to build (waterfall-style project management, extensive requirements gathering) decreases in value relative to the skill of rapidly evaluating multiple alternatives (taste, judgment, A/B testing at scale).
2. **Industries that relied on high planning costs as barriers to entry lose that moat.** Pharma, legal, financial modeling — all fields where "it costs a lot to even try" protected incumbents. When trying costs nothing, the barrier shifts from "can you afford to try?" to "can you evaluate what you tried?"
3. **Error tolerance increases.** If you can produce ten drafts for the cost of one, the cost of any single draft being wrong is trivially low. The emphasis shifts from preventing errors to selecting the best output from many trials. This is a profound cultural shift for industries (law, medicine, engineering) built around error prevention.
4. **The "build vs. buy" calculus tilts sharply toward "build."** Custom solutions become more attractive when production costs collapse. Why buy an imperfect off-the-shelf solution when building a custom one costs nearly nothing? This potentially inverts decades of enterprise software economics.

### Certainty Rating
**High.** This is a direct, mathematical consequence of near-zero marginal production costs. The only question is scope — how many domains does this apply to? For purely digital production (code, content, analysis, design), it applies now. For physical production with digital design phases, it applies to the design stage. For purely physical production, it applies only indirectly (via simulation and digital twins).

### Interactions
- **Search costs:** Cheap experimentation is a *substitute* for expensive search. Instead of searching exhaustively for the right answer, you generate many candidates and search among them. This blurs the boundary between search and production.
- **Enforcement costs:** More experiments = more outputs to verify. The enforcement burden increases proportionally.
- **Coordination costs:** When anyone can prototype anything, coordinating which prototypes to pursue (and preventing redundant effort) becomes harder. The organization needs strong selection mechanisms, not strong planning mechanisms.

---

## Premise 5: Physical Production Gains Are Real But Indirect — AI's Impact is Mediated Through Information, Not Through Atoms

### Claim
AI's transformation of physical production (manufacturing, construction, agriculture, logistics) is structurally real but operates one layer removed: AI improves the *information layer* that governs physical production, not the physical production itself. This creates an asymmetry where digital-native industries see 10-100x production cost reductions while physical industries see 20-50% efficiency gains.

### Reasoning
An LLM cannot pour concrete, assemble a circuit board, or harvest wheat. AI's impact on physical production is always mediated: better predictive maintenance (information about machine state), better quality control (information about defects), better supply chain optimization (information about logistics), better design (information about product geometry). This mediation creates a structural ceiling on AI's impact that doesn't exist for digital production.

The asymmetry is important because most economic analysis lumps "production" together. But the structural dynamics are completely different. In digital production, AI *is* the production tool — it literally generates the output. In physical production, AI *informs* the production process — it tells humans (or robots) what to do differently. The former approaches zero marginal cost; the latter approaches some optimized efficiency level that's still bounded by physical constraints (materials cost, energy, logistics, physics).

### Evidence
- Siemens: AI-enabled robots reduce automation costs by 90%, but this is about the *programming* of robots (an information task), not the physical assembly itself.
- Midea Group: 25% reduction in development cycles, 53% reduction in poor quality, 29% optimization of logistics paths. Significant, but note the scale: 25-53%, not 10-100x. These are efficiency improvements to existing physical processes.
- McKinsey estimates generative AI adds $2.6-4.4 trillion to the global economy, with manufacturing and supply chain capturing a "significant share" — through "improved productivity and operational efficiency," not through replacing physical production.
- Accedia (manufacturing AI, 2025): "the pressure is sharpest for small and mid-sized plants running older equipment with lean teams" — AI helps optimize within physical constraints, not transcend them.
- Lowe's: AI-powered digital twins of 1,750+ stores; 3D model generation from 2D images "at less than $1 per model." The digital twin is AI-produced; the physical store is not.

### Implications
1. **A structural divergence opens between digital and physical economies.** Digital production costs collapse by orders of magnitude; physical production costs decline by percentages. This means digital goods become radically cheaper relative to physical goods. The price of a custom-generated legal brief approaches the price of a cup of coffee; the cup of coffee doesn't get much cheaper.
2. **Competitive advantage in physical production shifts toward information advantage.** The factory that wins isn't the one with the best machines (those are increasingly commoditized) but the one with the best predictive models, quality control AI, and supply chain optimization. Information becomes the scarce input even in physical production.
3. **"Atoms vs. bits" becomes the defining economic divide.** Investing in AI-native digital production (software, content, financial products, professional services) offers fundamentally different return profiles than investing in AI-augmented physical production. Both are real; the magnitudes differ by orders of magnitude.
4. **Physical scarcity reasserts itself.** As cognitive production costs collapse, the remaining cost of any good or service is increasingly the physical component: materials, energy, space, logistics. This re-emphasizes the importance of physical infrastructure, supply chains, and resource access.

### Certainty Rating
**Medium-High.** The directional claim (digital >> physical in AI impact) is near-certain. The specific magnitude of the asymmetry is less certain — robotics and embodied AI may narrow the gap over a longer timeline. But the structural argument (AI generates information, not atoms) holds for the foreseeable future and creates a reliable planning asymmetry.

### Interactions
- **All five categories:** This premise modulates every other premise. Claims about production cost collapse should be read with an asterisk: *for digital production. Physical production sees meaningful but structurally bounded gains.
- **Coordination costs:** The digital/physical asymmetry means that coordinating digital production (which scales infinitely) requires different mechanisms than coordinating physical production (which faces bottlenecks). Organizations operating across both face a coordination challenge.
- **Enforcement costs:** Quality enforcement in physical production (did the bridge actually hold up?) remains expensive and physical. In digital production, it may be partially automatable. The asymmetry propagates through enforcement as well.

---

## Summary: What Remains Scarce When Production Costs Collapse?

These five premises point to a consistent answer about where value accrues:

1. **Direction over execution** (Premise 1) — Knowing *what* to build and *whether* it's good.
2. **Excellence over competence** (Premise 2) — The last 25% of quality, not the first 75%.
3. **Capital over labor** (Premise 3) — Infrastructure investment, not headcount.
4. **Selection over planning** (Premise 4) — Choosing among many options, not carefully designing one.
5. **Atoms over bits** (Premise 5) — Physical production, not digital production.

The common thread: AI makes *producing* cheap but doesn't make *choosing*, *evaluating*, or *physically instantiating* cheap. The scarce resources are taste, judgment, capital, and physical reality. Value will accrue to those who command these.
