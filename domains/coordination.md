# Coordination Costs — How AI Transforms the Organization of Collective Action

## Category Overview

Coordination costs are the costs of organizing collective action: managing teams, aligning incentives, making group decisions, running institutions, structuring markets. In Coase's framework, they are the reason firms exist at all. Markets are efficient at allocating resources, but they impose transaction costs. Firms internalize activity when the cost of coordinating through internal hierarchy is lower than the cost of coordinating through markets. The boundary of the firm sits where internal coordination costs equal external transaction costs.

This makes coordination the pivotal category in the entire Transaction Cost Economics skeleton. Search, bargaining, enforcement, and production costs all matter, but coordination costs determine the *shape* of the entities that bear those other costs. If AI reshapes coordination, it reshapes the organizational topology of the entire economy.

The question that disciplines everything below: **Does AI reduce external coordination costs (market transactions) more than internal coordination costs (management), or the reverse?** The answer determines whether firms shrink or grow. As I will argue, the answer is "both, asymmetrically" — and the asymmetry itself is the most important structural finding.

---

## Premise 1: AI Collapses the Cost of Informational Coordination Within Hierarchies, Flattening Them

### Claim
AI drastically reduces the cost of transmitting, synthesizing, and acting on information within organizations, which eliminates the primary function of middle management and flattens organizational hierarchies.

### Reasoning
The core function of middle management is informational intermediation. Managers exist to aggregate information from the front line, translate it into formats legible to senior leadership, relay strategic decisions back downward, and monitor whether those decisions are being executed. This is not a caricature — it is the structural role that organizational theory assigns to middle management, following Garicano and Rossi-Hansberg's (2006) knowledge-based hierarchy model. In their framework, organizations form layers because individuals have bounded rationality: they can only process so much information, so problems get escalated upward to specialists who handle exceptions.

AI dissolves this bottleneck. An LLM can synthesize front-line data into executive-readable reports. It can translate strategic objectives into task-level instructions. It can monitor execution through dashboards and anomaly detection. Each of these capabilities attacks a specific reason why management layers exist. When the cost of information transmission across organizational levels approaches zero, the *economic rationale* for those levels weakens regardless of whether any individual manager is "replaced by AI."

The structural argument is simple: if bounded rationality is the reason for hierarchical layers, and AI extends the cognitive bandwidth of individuals at every level, then optimal hierarchy depth decreases. This is not a prediction about AI capability — it is a deduction from the economic logic that justified hierarchy in the first place.

### Evidence
- **Brookings/Babina et al. (2023):** A one-standard-deviation increase in firms' AI investments from 2010-2018 was associated with a 1.6% increase in the share of junior employees, a 0.8% decrease in middle managers, and a 0.7% decrease in senior management. This trend was *unique* to AI-investing firms — there was no general trend toward flatter structures during this period.
- **HBR (2025):** "How AI Is Redefining Managerial Roles" documents the shift from managers-as-information-relays to managers-as-context-providers, with AI handling the data synthesis and monitoring functions.
- **"The Headless Firm" (2025, arXiv):** Formalizes the "manager-to-managed inversion" — AI enables dramatically larger spans of control by solving the principal-agent monitoring problem at scale, citing Calvo and Wellisz's (1978) insight that stochastic monitoring (which AI enables cheaply) reduces loss of control more effectively than deterministic monitoring.
- **Brynjolfsson et al. (2023):** Generative AI tools increase worker productivity by 14% on average (34% for novice workers) by disseminating best practices and reducing information asymmetry — directly compressing the knowledge gap that hierarchy exists to manage.

### Implications
1. **The "span of control" metric changes structurally.** Where a manager might effectively oversee 7-10 direct reports, AI-augmented managers can oversee 20-50, because the monitoring and synthesis functions are automated. This means fewer managers per unit of output.
2. **The skills that matter for remaining managers shift from information processing to judgment and context-setting.** The managers who survive are those whose value lies in *taste*, *strategic judgment*, and *political navigation* — things AI cannot yet provide.
3. **Organizational redesign becomes continuous, not periodic.** When the cost of restructuring falls (because AI can rapidly reassign workflows and update coordination patterns), firms no longer need to stick with suboptimal structures out of switching costs.
4. **Investment implication:** Tools that help organizations dynamically restructure — real-time org design, AI-driven workflow routing, adaptive team formation — become infrastructure rather than consulting projects.

### Certainty Rating
**High.** The mechanism is already empirically validated (Babina et al.), the theoretical logic is clean (Garicano-Rossi-Hansberg → bounded rationality dissolution), and the direction of change is consistent across every signal. The only uncertainty is pace and degree, not direction.

### Interactions
- **Search costs:** Flatter hierarchies work only if individuals can find the right information without going through a chain. AI's reduction of search costs is a *precondition* for hierarchy collapse — these two premises are mutually reinforcing.
- **Production costs:** If individual workers are more productive (production premise), they need *less* coordination, further reducing the need for management layers.
- **Enforcement costs:** Flatter organizations with wider spans of control require better monitoring — which connects to whatever the enforcement agent writes about AI-enabled verification.

---

## Premise 2: AI Reduces External Transaction Costs Faster Than Internal Coordination Costs for High-Velocity Domains, Causing Firms in Those Domains to Shrink

### Claim
In domains where knowledge changes rapidly (software, content, marketing, design, data analysis), AI reduces the cost of market-based coordination more than it reduces internal management costs, pushing the optimal firm boundary inward — toward smaller, more specialized firms that coordinate through markets rather than hierarchy.

### Reasoning
This is the Coasean question applied with specificity. The naive version — "AI reduces all costs, so who knows what happens to firms" — is analytically useless. The productive version asks: *which* costs fall faster?

Internal coordination costs have a floor that external transaction costs do not. Inside a firm, you still face: (a) incentive alignment problems (employees have their own career goals, political dynamics, risk preferences), (b) organizational inertia (legacy processes, sunk costs in existing structures, change management), and (c) what "The Headless Firm" calls the "complexity wall" — the cost of continuously rewriting internal systems to track the frontier of knowledge scales superlinearly with firm size, because larger firms have more interdependencies and more legacy.

External transaction costs, by contrast, are falling toward near-zero for many coordination tasks. Finding a freelancer (AI-powered matching), specifying a task (natural language is now a valid specification language), monitoring quality (AI review), and making payment (already solved by platforms) — each of these has been individually compressed by at least an order of magnitude by AI and platform infrastructure combined.

The key variable is *knowledge decay rate*. In high-velocity domains — software, content creation, marketing, design — the relevant knowledge base turns over quickly. Large firms in these domains pay a "complexity tax" to keep their internal systems updated. Small firms don't, because they have less to update. When external transaction costs are also low, the advantage of being large (amortizing fixed costs of coordination infrastructure) disappears, and the disadvantage (organizational inertia, slow adaptation) remains.

In low-velocity domains — logistics, manufacturing, regulated industries — knowledge is more stable, the complexity wall is lower, and AI's reduction of internal monitoring costs (Premise 1) dominates. Here, firms may actually *grow*.

### Evidence
- **"The Headless Firm" (arXiv, 2025):** Formally derives this bifurcation: "AI will enable larger firms in domains with stable knowledge (logistics, manufacturing, routine transaction processing), where Williamson's mechanism dominates. But in high-velocity domains, AI will accelerate unbundling."
- **"The Algorithmic Boundary" (Zhang, SSRN 2025):** Models AI as creating "non-monotonic transitions: firms initially move toward markets, then selectively re-integrate complex tasks, ultimately converging to hybrid forms."
- **Revenue-per-employee data (Forbes, 2026):** AI-native startups generate $2M-$4M in revenue per employee vs. $300K for average public SaaS companies. Midjourney: ~$200M revenue with ~40-50 employees. Cursor: $500M+ ARR with under 50 people. These are firms in high-velocity domains that have radically shrunk.
- **Fortune (March 2026):** Bank of America Institute data shows "high propensity businesses" up 15.1% year-over-year, while business applications with explicit plans to hire employees fell 4.4%. More businesses, fewer employees per business.
- **Block/Square (March 2026):** Laid off approximately half its workforce, with CEO Jack Dorsey citing AI tools "enabling a new way of working which fundamentally changes what it means to build and run a company."
- **TurboAI example (Fortune, 2026):** Two college-age founders, 13 employees, 8.5 million users, ~$1M/month revenue. Founder states: "If we were a company two-and-a-half years ago, it would take over 100 employees."
- **INSEAD field experiment (Kim, Kim, Koning, 2026):** Across 515 startups, treated firms that discovered AI use cases generated 1.9x higher revenue while their demand for external capital investment fell 39.5% and labor demand remained unchanged — more output without proportional input scaling.

### Implications
1. **The "one-person company" thesis is directionally correct but conceptually wrong.** It is not that individuals become self-sufficient. It is that the *minimum viable coordination unit* shrinks, because the cost of coordinating with external AI-augmented specialists through markets falls below the cost of employing them internally. The solo founder is not a lone wolf — they are a node in a market that has become cheaper to use than a firm.
2. **The "make vs. buy" decision shifts massively toward "buy" for knowledge work.** If you can specify a task in natural language, have AI review the output, and pay on completion — why would you hire someone full-time and manage their career development, office politics, and health insurance?
3. **Platform businesses that reduce external coordination costs become the new "firms."** The Coasean logic does not disappear — it migrates. If firms shrink because external coordination is cheaper, the entities that *provide* that cheap external coordination (marketplaces, agent platforms, API providers) capture the value that used to sit inside firms.
4. **Investment implication:** The "picks and shovels" of this transition are platforms and protocols that make market-based coordination frictionless for small teams — task marketplaces, AI agent orchestration layers, shared infrastructure that replaces what departments used to provide internally.

### Certainty Rating
**Medium-High.** The theoretical logic is strong (Coase + knowledge decay rate as the key variable is analytically clean), and the empirical signals are loud (revenue-per-employee data, new business formation patterns). I rate it Medium-High rather than High because the *pace* of transition depends on trust infrastructure that is not yet fully built — you still need to trust external providers, which connects to enforcement costs. Also, the bifurcation prediction (some domains shrink, others grow) adds complexity that makes it harder to be certain about any specific domain.

### Interactions
- **Enforcement costs:** The shift to market coordination only works if you can verify quality cheaply. If the enforcement agent finds that AI makes verification easy, this premise gets stronger. If verification remains expensive, firms stay large.
- **Bargaining costs:** Smaller firms doing more market transactions means more bargaining. If AI makes bargaining cheap (the bargaining agent's domain), the shift to markets accelerates.
- **Search costs:** The entire premise depends on being able to *find* the right external provider quickly. Search cost reduction is a precondition.

---

## Premise 3: AI Creates a New Organizational Primitive — the Algorithmic Coordination Layer — That Is Neither Market Nor Hierarchy

### Claim
AI enables a third mode of coordination — algorithmic governance — that sits between Coase's market and Williamson's hierarchy, and this hybrid mode will become the dominant organizational form for knowledge work.

### Reasoning
Coase's original framework presents a binary: you coordinate through markets (price signals) or through hierarchies (managerial authority). Williamson refined this by identifying when each is optimal (asset specificity, uncertainty, frequency). But AI creates something genuinely new: coordination through algorithmic systems that have the flexibility of markets and the integration of hierarchies.

Consider what an AI orchestration layer does: it takes a complex objective, decomposes it into subtasks, assigns those subtasks to agents (human or AI), monitors progress, handles exceptions, synthesizes outputs, and iterates. This is what a project manager does inside a firm. But the orchestration layer does not require employment relationships, does not create principal-agent problems (it has no career goals), does not accumulate organizational debt, and can coordinate across firm boundaries as easily as within them.

This is not merely a "platform" in the Uber/Airbnb sense. Those platforms still fundamentally use price signals to coordinate (market mechanism). Algorithmic coordination goes further: it can manage complex, interdependent tasks that previously required tight hierarchical control — the very tasks that Williamson argued markets could not handle because of asset specificity and opportunism.

The key insight: AI coordination layers reduce the *transaction cost difference* between internal and external coordination, making the boundary of the firm blurry rather than sharp. A team of five people, three AI agents, and two external contractors, all coordinated by an AI project manager, is neither a firm nor a market. It is something new.

### Evidence
- **Zhang (SSRN, 2025):** Formally models "algorithmic governance" as a third organizational form between markets and hierarchies. Shows it increases organizational heterogeneity rather than pushing uniformly toward either pole.
- **CMR/Berkeley (April 2025):** "From Coase to AI Agents" argues that the proliferation of independent AI agents within organizations creates entropy that will increasingly be absorbed by the *platform layer* rather than by management — the platform becomes the coordinator.
- **AI agent orchestration tools (2025-2026):** The rapid growth of multi-agent frameworks (CrewAI, AutoGen, LangGraph, etc.) demonstrates that the technical infrastructure for algorithmic coordination is being built. These tools explicitly frame complex work as decomposable workflows managed by AI.
- **Wagner (2020):** "The Nature of the Artificially Intelligent Firm" proposes that "AI is a factor of production that can perforate the boundaries of the firm" and "AI can lead to triangular agency relationships" — the AI mediates between what would otherwise be market counterparties.
- **Krier (Substack, 2025):** "Coasean Bargaining at Scale" argues that AI agents could enable the "cognitive glue" of a free society by empowering individual bargainers — essentially making Coasean bargaining work at scale where it previously could not due to cognitive limitations.

### Implications
1. **The "firm vs. market" binary becomes a spectrum.** Organizations will exist at many points along a continuum from tight hierarchy to pure market, with most knowledge work happening in the hybrid zone. Legal and regulatory frameworks built around the binary (employment law, corporate liability, tax structures) will increasingly misfit reality.
2. **The scarce resource shifts from management talent to "coordination design."** Who designs the algorithmic coordination layer? Who decides how to decompose objectives, what to keep internal vs. external, how to handle exceptions? This is a new skill — call it "organizational architecture" — that is distinct from both traditional management and traditional engineering.
3. **Platform companies that provide algorithmic coordination become systemically important.** Just as AWS became infrastructure by providing compute, the companies that provide coordination layers (task decomposition, agent orchestration, quality routing) become infrastructure for how work itself is organized.
4. **Investment implication:** The coordination layer is the highest-leverage point. It is not the AI models themselves (those commoditize), nor the end applications (those are fragmented), but the orchestration/coordination infrastructure that connects models to workflows to humans. This is where the "new firm" lives.

### Certainty Rating
**Medium-High.** The theoretical argument is strong — Coase's binary was always a simplification, and AI creates clear mechanisms for a third mode. The technical infrastructure is being built rapidly. I rate it Medium-High rather than High because the *social and legal* infrastructure has not caught up. Employment law, liability frameworks, and regulatory structures still assume the firm/market binary. The hybrid form may be economically optimal but legally ambiguous for some time, which slows adoption.

### Interactions
- **All other categories:** This premise is the meta-premise. If algorithmic coordination layers become the dominant organizational form, they reshape how search, bargaining, enforcement, and production happen — not just how coordination happens. The coordination layer *is* the integration point.
- **Enforcement:** Algorithmic coordination requires algorithmic enforcement. The two are inseparable — you cannot coordinate through an AI layer if you cannot also verify through it.

---

## Premise 4: AI Compresses the Principal-Agent Problem, Enabling Radical Spans of Control

### Claim
AI's ability to monitor, evaluate, and align agent behavior at near-zero marginal cost compresses the principal-agent problem that has constrained organizational scale, enabling individual decision-makers to effectively oversee far more agents (human and artificial) than was previously possible.

### Reasoning
The principal-agent problem is the foundational coordination challenge: how do you ensure that people (agents) act in the interest of the person who hired them (the principal), given that agents have their own interests and information advantages? This problem is why firms have management layers, performance reviews, incentive structures, compliance departments, and internal auditing.

AI attacks this problem on three fronts simultaneously:

**Monitoring costs collapse.** AI can observe and analyze the output of every agent continuously, at near-zero marginal cost. It can detect anomalies, flag quality issues, and identify underperformance without requiring a human manager to personally review each output. This is the Calvo-Wellisz insight: stochastic monitoring (unpredictable AI audits) is more effective at deterring shirking than deterministic monitoring (scheduled human reviews), and AI makes stochastic monitoring essentially free.

**Information asymmetry shrinks.** The classic agency problem depends on the agent knowing more about their own effort and circumstances than the principal. AI tools that track work output, analyze code commits, evaluate writing quality, and synthesize customer interactions reduce this information gap. The principal does not need to rely on the agent's self-report.

**Incentive design improves.** AI can model the likely behavioral responses to different incentive structures, identify misalignment before it manifests, and personalize incentive schemes. More importantly, AI agents (as opposed to human agents) have no misaligned incentives to begin with — they do not shirk, do not empire-build, do not politic. Every task delegated to an AI agent is a task where the principal-agent problem is eliminated entirely, not merely compressed.

The structural result: the maximum effective span of control increases dramatically. If one person can effectively oversee 50 AI agents and 20 human workers (with AI handling routine monitoring), the minimum management overhead per unit of output drops sharply.

### Evidence
- **Babina et al. (Brookings, 2023):** AI-investing firms hire more "independent, deputized workers" and fewer managers — direct evidence that AI enables wider spans of control with less supervision.
- **Calvo and Wellisz (1978) + "The Headless Firm":** The theoretical framework predicts that AI-driven stochastic audits reduce loss of control below what Williamson's deterministic model suggests, enabling "dramatically larger hierarchical firms" — or, equivalently, dramatically wider spans within existing ones.
- **Cursor, Lovable, Midjourney:** These companies' revenue-per-employee ratios ($3M+/employee) are only possible because founders and small leadership teams effectively oversee vast amounts of AI-executed work. The management overhead per unit of output has compressed by an order of magnitude.
- **Block layoffs (2026):** The decision to cut ~50% of workforce explicitly because AI enables remaining workers to handle larger scopes of responsibility is a direct manifestation of span-of-control expansion.

### Implications
1. **The "manager" role bifurcates into "architect" and "overseer."** Architects design the system (what AI agents do, how they coordinate, what humans handle). Overseers handle exceptions and judgment calls. The middle ground — routine supervision — disappears.
2. **Compensation concentrates.** If one person can oversee what previously required ten managers, the economic value of that one person increases while the value of the other nine goes to zero. This is a structural driver of income inequality within organizations.
3. **The optimal organizational shape becomes "hourglass" — few senior leaders, few middle managers, many individual contributors and AI agents.** This is the "headless firm" architecture: a thin strategic layer at the top, a thin coordination layer in the middle (mostly AI), and a broad execution layer at the bottom (AI agents plus specialized humans).
4. **Investment implication:** Tools that help principals manage larger spans — AI-powered performance dashboards, automated quality assurance, agent orchestration platforms — are the management infrastructure of the future. The market for "management technology" is about to be reinvented.

### Certainty Rating
**High.** The principal-agent problem is one of the most well-established frameworks in organizational economics, the mechanisms by which AI compresses it are concrete and already operational, and the empirical evidence is consistent. The direction is certain; the degree is the only open question.

### Interactions
- **Enforcement costs:** Principal-agent compression *is* enforcement applied within organizations. Whatever the enforcement agent writes about AI-enabled monitoring applies internally as well as externally.
- **Production costs:** If AI agents have no principal-agent problems, they are not just cheaper producers but also cheaper *to coordinate*. The interaction between production and coordination is multiplicative — AI reduces both simultaneously.

---

## Premise 5: The Minimum Viable Scale for Competitive Market Participation Drops by an Order of Magnitude

### Claim
AI reduces the minimum amount of coordination infrastructure needed to participate competitively in a market, lowering barriers to entry and increasing the number of viable competitors in most knowledge-work industries.

### Reasoning
To compete in a market, you need certain coordination capabilities: you need to manage a product development process, handle customer support, run marketing, do accounting, maintain legal compliance, and coordinate all of these with each other. Historically, each of these functions required at least one dedicated person (often more), creating a minimum viable team size of 15-50 people for any serious market participant.

AI compresses each of these functions. Not by making one person 10% better at them, but by making it possible for one person to *perform* the function at an adequate level without specialization. A founder using AI can now: generate marketing copy, build and ship software, handle tier-1 customer support, do basic financial modeling, draft legal documents, and manage a simple product roadmap — all at a quality level that, while not best-in-class, is sufficient to compete.

This is the structural argument beneath the "one-person company" discourse. The discourse is shallow when it fixates on individual heroism. The structural point is about *barriers to entry*. When the minimum viable team drops from 30 to 3, the number of potential market entrants in any given domain increases by an order of magnitude. This increases competition, compresses margins, and accelerates innovation in every affected market.

The compounding effect matters: it is not just that each function gets cheaper. It is that the *coordination overhead* between functions — which scales combinatorially with the number of functions and people — also shrinks. A three-person team coordinating with AI has perhaps 3 coordination links. A 30-person team has 435 (n*(n-1)/2). The coordination cost reduction is superlinear.

### Evidence
- **Fortune/Bank of America (March 2026):** "High propensity businesses" up 15.1% year-over-year, while applications with explicit plans to hire fell 4.4%. The modal new business is forming with fewer employees.
- **TurboAI (Fortune, 2026):** 13 employees, $1M/month revenue, 8.5M users. Founder: "If we were a company two-and-a-half years ago, it would take over 100 employees."
- **Lovable (2025):** Reached $17M ARR with 15 employees in 3 months. Now at $400M ARR with 146 employees.
- **Newfund Capital data (2025):** Where $100M ARR used to require 500+ employees in the early 2000s, AI-era startups are reaching it with fewer than 100. The ARR-per-employee benchmark has shifted from $200K-$350K (PLG era) to $1M-$2M+ (AI era).
- **AI tool ecosystem (2025-2026):** The proliferation of AI tools explicitly designed for solo founders and small teams — covering everything from code generation to customer support to financial planning — demonstrates the infrastructure for low-coordination-overhead competition is being built.
- **INSEAD field experiment (Kim et al., 2026):** Treated startups that mapped AI into their production processes generated 1.9x higher revenue while demanding 39.5% less external capital — achieving competitive output with radically less input.
- **Gartner prediction:** A new wave of unicorns by 2030 generating $2M+ in ARR per employee, up from $250K-$350K benchmarks of the previous era.

### Implications
1. **Competitive intensity increases in nearly every knowledge-work market.** Lower barriers to entry → more entrants → more competition → margin compression for incumbents. This is bad for existing firms with large coordination overhead and good for consumers and agile new entrants.
2. **The "moat" migrates from operational scale to something else.** If coordination capacity is no longer a barrier, what is? Likely: proprietary data, network effects, regulatory capture, brand trust, and access to physical infrastructure. The "operational excellence" moat weakens.
3. **Market structure becomes more "Cambrian."** More viable competitors means more experimentation, more niche strategies, and more frequent market turnover. Industries that have been stable oligopolies may fracture — not because the oligopolists do anything wrong, but because the minimum viable competitor just got 10x cheaper to build.
4. **Investment implication:** The returns to being *first* and *fast* increase, because competitive advantage becomes more temporary. The "blitzscaling" logic gets both more and less valid: more valid because speed matters more, less valid because you do not need massive capital to move fast anymore. Capital-efficient, fast-moving small teams may beat capital-intensive blitzscalers.

### Certainty Rating
**High.** The mechanism is already demonstrably operational (the revenue-per-employee data is not speculative — it is current). The direction is certain. The uncertainty is about *which* specific industries are affected and *how quickly* incumbents respond, not about whether the general trend holds.

### Interactions
- **Production costs:** Lower minimum viable scale is partly a production cost story (one person can produce more), but the coordination cost reduction is the bigger factor because coordination overhead scales superlinearly with team size while production scales linearly.
- **Search costs:** More competitors in a market means search costs for buyers increase (more options to evaluate), which creates demand for AI-powered curation and recommendation — a secondary effect that feeds back into search.
- **Bargaining costs:** More small firms doing more market transactions means more bargaining events, which increases demand for AI-powered negotiation and pricing.

---

## Synthesis: The Coasean Answer

Returning to the central question — does AI shrink or grow firms? — the answer emerging from these premises is: **it depends on the knowledge decay rate of the domain, and the net effect is bifurcation, not uniform change.**

In **high-velocity knowledge domains** (software, content, marketing, consulting, design): external transaction costs fall faster than internal coordination costs. Firms shrink. Markets expand. The "one-person company" is an extreme case of a general trend toward smaller, more specialized entities coordinating through algorithmic platforms.

In **low-velocity, asset-heavy domains** (logistics, manufacturing, regulated finance, healthcare operations): internal monitoring costs fall faster because the complexity wall is lower and AI's span-of-control enhancement is more valuable than market coordination gains. Firms may grow or at least maintain scale.

In **both cases**, the organizational form becomes more hybrid — neither pure hierarchy nor pure market, but algorithmically coordinated networks with variable degrees of integration.

The **most investable implication** across all five premises: the coordination layer itself — the platforms, protocols, and tools that enable small teams to coordinate as effectively as large firms, and that enable large firms to coordinate internally without management bloat — is the highest-leverage infrastructure opportunity. This is the new "firm" in the Coasean sense: the entity that reduces coordination costs for everyone else.
