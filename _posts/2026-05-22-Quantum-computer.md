---
layout: post
title: "Quantum Computing, new investment opportunities"
date: 2026-05-22
categories: [Technology, Investment]
tags: [quantum-computing, infrastructure, deep-tech]
---

In 2012, most enterprise technology buyers thought cloud computing was an interesting experiment for startups. The idea that a serious company would run its core workloads on someone else's servers seemed, to many, like a category error. Amazon Web Services had been quietly building infrastructure for six years. Microsoft Azure had been live for three. The revolution was already underway — it just wasn't visible yet to the people who would eventually depend on it most.

Quantum computing in 2026 occupies a structurally similar position. The technology is real, the investment is substantial, the milestones are accelerating, and the commercial applications are still — for most industries — a few years away from being undeniable. That gap between "real" and "obviously useful" is precisely where the most durable infrastructure investments tend to get made.

This is my read on where quantum computing stands, where it is going, and why I think now is the right moment to understand — and begin positioning around — this transition.

---

## Part I: What Quantum Computing Actually Is (And Isn't)

The single biggest source of confusion about quantum computing is the tendency to think of it as a faster classical computer. It is not. It is a fundamentally different computational architecture — one that solves certain classes of problems that classical computers cannot solve at any practical scale, while being entirely unsuited to most of what classical computers do every day.

Classical computers — every laptop, server, and smartphone — process information as **bits**: binary values of 0 or 1. Every calculation reduces to sequences of these binary operations. This architecture is extraordinarily powerful for most tasks: running applications, storing and retrieving data, rendering graphics, executing business logic. It is also fundamentally sequential in structure, and for certain problem types — particularly those involving enormous combinatorial search spaces — it becomes intractably slow regardless of how many classical processors you throw at it.

Quantum computers process information as **qubits**. A qubit can exist in a superposition of 0 and 1 simultaneously — not as a metaphor, but as a physical reality governed by quantum mechanics. Two qubits can represent four states simultaneously. Fifty qubits can represent over one quadrillion states simultaneously. This property, combined with **quantum entanglement** (which creates correlated relationships between qubits) and **quantum interference** (which amplifies correct answers and cancels incorrect ones), enables quantum computers to explore vast solution spaces in parallel ways that classical architectures cannot replicate.

The practical consequence: for problems where the solution space grows exponentially with problem size — drug molecule simulation, cryptographic factoring, portfolio optimization across thousands of variables, materials science, certain machine learning tasks — quantum computers offer a theoretical speedup that is not incremental but categorical. Google's Willow chip completed a benchmark computation in approximately five minutes that would take the best classical supercomputers an estimated 10²⁵ years. That is not a performance improvement. That is a different category of capability.

The critical caveat: **most problems are not like this**. Quantum computers will not replace classical computers for the overwhelming majority of computational tasks. They will augment them — handling specific workloads where quantum advantage is decisive, while classical systems continue doing everything else. The future architecture is hybrid: quantum processors for specific high-value computations, classical systems for everything surrounding them.

---

## Part II: The History in Brief — From Thought Experiment to Commercial Hardware

Quantum computing has a longer history than most people realize, and understanding that history helps calibrate where we are in the maturity curve.

**1980s — Theoretical foundations.** Richard Feynman proposed in 1982 that a quantum mechanical computer could simulate quantum systems far more efficiently than classical machines — a problem classical computers fundamentally cannot solve at useful scale. David Deutsch formalized the first quantum computing model in 1985. These were thought experiments supported by physics, with no hardware path in sight.

**1994 — The cryptography moment.** Peter Shor published his quantum algorithm for factoring large integers in polynomial time — the mathematical foundation of RSA encryption. This was the first demonstration that a quantum computer, if built, could break the cryptographic infrastructure underpinning global finance and communications. It transformed quantum computing from an academic curiosity into a national security priority for every major government.

**1990s–2000s — First hardware, fragile qubits.** IBM, MIT, and others built the first physical quantum systems — systems measured in single-digit qubits, extraordinarily fragile, requiring temperatures colder than outer space to operate. Progress was real but slow, and the gap between laboratory demonstrations and anything commercially useful remained vast.

**2011 — D-Wave enters.** D-Wave Systems sold the first commercial quantum computing system to Lockheed Martin, using a quantum annealing architecture suited to optimization problems. The sale was controversial among physicists — many disputed whether it was "truly" quantum — but it marked the first moment a company paid money for quantum computation.

**2016 — IBM goes to the cloud.** IBM launched IBM Quantum Experience, putting a 5-qubit quantum processor on the cloud and making it accessible to researchers and developers worldwide. This was a pivotal moment: quantum computing ceased to be purely a laboratory phenomenon and became something developers could interact with directly. The ecosystem began.

**2019 — Google's quantum supremacy claim.** Google announced that its 53-qubit Sycamore processor had completed a specific computation in 200 seconds that would take the best classical supercomputer approximately 10,000 years. IBM contested the framing; the debate about what "supremacy" meant was legitimate. But the underlying technical achievement was real: a quantum processor had done something classically intractable at any practical timescale.

**2023 — IBM's 100-qubit milestone.** IBM demonstrated that quantum computers could generate accurate outcomes on problems exceeding 100 qubits, surpassing classical computing methods on specific tasks. The result was published on the cover of *Nature* — a signal that the field had crossed from engineering demonstration into scientifically validated capability.

**2025 — The hardware inflection.** Three developments in 2025 marked what may be remembered as the year quantum computing became undeniable. Google's Willow chip demonstrated exponential error reduction as qubit count scaled — solving a longstanding technical problem where errors had previously grown faster than capabilities. Microsoft unveiled Majorana 1, a topological qubit architecture theoretically capable of scaling to a million qubits per chip. And D-Wave demonstrated quantum supremacy on a *useful* real-world problem — simulating complex magnetic materials in minutes versus nearly a million years for classical supercomputers. IBM outlined its Starling roadmap targeting 200 logical qubits capable of 100 million operations by 2029.

We are now in the transition from "demonstrated capability on contrived benchmarks" to "demonstrated capability on real problems." That transition is the infrastructure investment inflection.

---

## Part III: Classical vs. Quantum — Where Each Excels

Understanding the investment thesis requires being clear about where quantum computing creates genuine value and where it does not.

| Dimension | Classical Computing | Quantum Computing |
|---|---|---|
| Basic unit | Bit (0 or 1) | Qubit (superposition of 0 and 1) |
| Computation model | Sequential / parallel binary logic | Quantum parallelism via superposition |
| Error rates | Extremely low, mature | Currently high, improving rapidly |
| Operating environment | Room temperature | Near absolute zero (superconducting) or controlled ion traps |
| Best suited for | General-purpose computation, data storage, applications | Optimization, simulation, cryptography, specific ML tasks |
| Scalability | Well understood | Active research challenge |
| Commercial maturity | Fully mature | Early commercial stage |

The key insight from this comparison: quantum computing is not a replacement technology. It is a **specialized accelerator** for a specific — but economically very important — subset of computational problems.

The industries where those problems are most concentrated, and therefore where quantum advantage translates most directly into economic value:

**Pharmaceuticals and materials science** — Simulating molecular behavior to discover new drugs or materials. Classical computers cannot simulate molecules of meaningful complexity accurately. A quantum computer that can simulate how a drug candidate interacts with a target protein could compress years of laboratory iteration into weeks. McKinsey estimates quantum applications in life sciences alone could generate $60–80 billion in value by 2035.

**Financial services** — Portfolio optimization across thousands of assets, risk modeling for complex derivatives, fraud detection in transaction networks. The banking and finance sector is projected to hold the largest near-term quantum computing market share, leveraging quantum for risk modeling, trading strategies, asset pricing, and portfolio optimization.

**Cryptography and cybersecurity** — Shor's algorithm's eventual ability to break RSA encryption is driving massive government and enterprise investment in quantum-safe cryptography, independent of whether anyone has yet built a quantum computer powerful enough to execute the attack.

**Logistics and supply chain** — Route optimization, scheduling, and resource allocation problems that are NP-hard classically become tractable with quantum approaches at scale.

**AI and machine learning** — Quantum machine learning is the least mature application, but the potential for quantum hardware to accelerate specific training and inference tasks has attracted significant research investment from every major AI lab.

---

## Part IV: The Competitive Landscape in 2026 — Four Architectures, One Race

Four distinct hardware architectures are competing for dominance in quantum computing, each with different physical principles, technical trade-offs, and commercial strategies. Understanding the differences matters for investors because the architecture race is not settled — and the winner, if there is one, will shape which companies capture the majority of long-term value.

### 1. Superconducting Qubits

The architecture used by **IBM**, **Google**, and **Rigetti** is currently the most mature at scale. Superconducting qubits are fabricated using standard semiconductor manufacturing processes, which gives them a meaningful advantage in production scalability. The trade-off is operating environment: they require cooling to approximately 15 millikelvin — colder than outer space — which constrains deployment flexibility and adds infrastructure cost.

IBM's Heron R2 156-qubit processor now powers cloud systems in the US and EU, supports up to 5,000 two-qubit gates, and is targeting a quantum advantage demonstration in 2026 on practically relevant problems. IBM Condor has crossed 1,121 qubits. IBM's enterprise sales motion — built over decades in enterprise technology — is the deepest in the sector, and its cumulative $1 billion in quantum business since 2017 gives it the most tangible commercial track record.

Google's superconducting roadmap received a further boost with its October 2025 acquisition of Atlantic Quantum, which brought fluxonium-based qubit designs aimed at improving coherence times and reducing error rates. Notably, Google is now pursuing a *dual-architecture* strategy, having also moved into neutral atoms — a signal that even the most committed superconducting players are hedging.

### 2. Trapped Ions

**IonQ** and **Quantinuum** (a joint venture of Honeywell and Cambridge Quantum) represent the trapped-ion approach. Trapped-ion systems use individual charged atoms suspended in electromagnetic fields as qubits. They trade raw qubit count for dramatically higher gate fidelity: ion-trap qubits hold their quantum state longer and execute operations more accurately than superconducting qubits at equivalent scale, making them better suited for near-term commercial applications where error rates are critical.

Quantinuum's Helios system delivered 48 logical qubits in November 2025 — a meaningful logical qubit milestone. IonQ is the largest pure-play by revenue, with roughly $130 million in 2025 sales and 2026 guidance of $225–245 million, backed by $1.6 billion in cash following its latest capital raise. IonQ's acquisitions of Oxford Ionics (ion-trap-on-a-chip technology), ID Quantique (quantum-safe cryptography), and Capella Space (space-based quantum key distribution) are building a vertically integrated quantum stack that extends well beyond hardware.

### 3. Neutral Atoms

Neutral atoms are the architecture that has moved most rapidly from relative obscurity to serious commercial contention in 2024–2025 — and it is arguably the most underappreciated by generalist investors.

Neutral-atom systems use arrays of individual atoms — typically rubidium or strontium — held in place by laser-generated optical tweezers. Unlike trapped ions, which use charged particles, neutral atoms interact with their environment less, offering potential advantages in coherence and scalability. Crucially, neutral-atom systems can be reconfigured mid-computation, enabling a flexibility of qubit connectivity that superconducting and trapped-ion systems struggle to match.

The leading players are **QuEra** (partnered with Google), **Atom Computing** (partnered with Microsoft), and **Pasqal** (the French leader, now deployed in HPC environments across Europe). Current systems operate with 1,000–10,000 atoms achieving single-qubit fidelities around 99.9% and two-qubit fidelities of 99.7% — competitive with the best superconducting systems. QuEra demonstrated 96 verified logical qubits, and Atom Computing's Phoenix system reached 1,200 atoms. The Microsoft-Atom Computing collaboration is targeting the Magne system with 50 logical qubits built from approximately 1,200 physical qubits, expected operational by early 2027.

Pasqal achieved a significant milestone by reaching 1,000 qubits in 2024 and has announced plans to scale to 10,000 qubits by 2026. Pasqal delivered a 140-qubit system to CINECA in Bologna in February 2026, integrated with the Leonardo supercomputer — the first neutral-atom QPU deployed inside a major European HPC facility.

Google's neutral-atom expansion follows its October 2025 acquisition of Atlantic Quantum, and Google is positioning its expansion into neutral atoms alongside continued investment in superconducting systems, framing the two approaches as complementary paths toward scalable quantum computing. That a company with Google's superconducting depth is hedging into neutral atoms is one of the clearest signals available that the architecture race remains genuinely open.

### 4. Photonic Quantum Computing

Photonic quantum computing encodes information in photons — individual particles of light — rather than in matter-based qubits. This approach has a distinctive and commercially important advantage: photonic quantum computing offers room-temperature operation and fiber-network compatibility. No dilution refrigerators, no exotic cooling infrastructure — photonic systems can in principle be integrated directly into existing telecommunications and data center environments.

The technical barriers are real: photon loss, deterministic photon generation, and scalable error correction remain active engineering challenges. But the commercial logic is compelling for specific applications, and the investment behind photonics is substantial.

PsiQuantum has raised over $2 billion in total funding, including a $1 billion Series E round completed in September 2025, and partners with GlobalFoundries for chip production. PsiQuantum is building deployment sites in Brisbane, Australia and Chicago, with systems expected to come online in the coming years. The GlobalFoundries partnership is significant: it means PsiQuantum is manufacturing quantum hardware in a commercial semiconductor foundry, rather than in a physics laboratory — a production scalability argument that no other architecture can currently match.

Xanadu, established in 2017, has raised over $287 million and announced plans to go public in early 2026. The company achieved a significant technical milestone in 2025 with its work on GKP states for error correction in photonic systems.

**Quantum Computing Inc. (QUBT)** represents a different photonic angle — focused on quantum optics and integrated photonics for near-term commercial applications including AI acceleration, cybersecurity, and remote sensing. QCi operates its own thin-film lithium niobate chip foundry (Fab 1) in Tempe, Arizona, and is planning Fab 2 for higher-volume production. Its photonic approach operates at room temperature and is designed for integration with existing computing infrastructure — a nearer-term commercialization path than the gate-based photonic approaches of PsiQuantum and Xanadu.

---

The four-architecture landscape means the quantum hardware race is structurally different from most technology competitions: there is no obvious incumbent, no dominant standard, and no settled consensus among researchers about which physical approach will scale most effectively to fault-tolerant systems. This creates both risk and opportunity — the risk that any single architecture bet could be disrupted, and the opportunity that the infrastructure layer (cloud access, error correction software, control electronics, cryogenic systems) will be valuable regardless of which hardware approach ultimately wins.

Beyond pure-play hardware companies, the cloud hyperscalers have embedded quantum access across all four architectures into their platforms: IBM Quantum, Amazon Braket, Microsoft Azure Quantum (supporting superconducting, trapped-ion, and neutral-atom systems), and Google Cloud Quantum AI. This cloud-access model is significant — it means quantum computing revenue is already flowing through existing enterprise relationships, and customers can experiment across architectures without committing to hardware ownership.

---

## Part V: The Investment Case — Why Now Looks Like 2012

Boston Consulting Group estimates $450–850 billion in economic value by 2040 from quantum computing applications. The global quantum computing market is valued at $2.01 billion in 2025 and is predicted to reach $40.45 billion by 2035 at a 36% CAGR. The market reached $3.52 billion in 2025, marking a 170% increase from 2024's $1.3 billion valuation.

These numbers matter less than the structural logic. The cloud computing analogy is instructive not because the numbers are similar but because the *phase* is similar.

In 2012, cloud computing had demonstrated technical viability, major technology companies had made irreversible infrastructure commitments, enterprise customers were beginning (cautiously) to experiment, and the killer applications that would eventually drive mass adoption — SaaS, mobile backends, AI training infrastructure — were either embryonic or not yet conceived. The investors who recognized that the infrastructure was being laid, regardless of uncertainty about which applications would win, captured the majority of the decade's returns.

Quantum computing in 2026 exhibits the same structure:

**Technical viability is demonstrated.** Multiple independent organizations have shown quantum advantage on specific problem classes. The debate has shifted from "will it work?" to "when will it be practically useful at scale?" — a fundamentally different question.

**Irreversible infrastructure commitments are in place.** IBM, Google, Microsoft, Amazon, and every major government with a technology strategy have made multi-billion-dollar, multi-year quantum commitments. These are not pilot programs. They are infrastructure bets with long capital tails.

**The hardware roadmaps are credible and accelerating.** IBM targets fault-tolerant quantum computing modules by 2027, while IonQ projects systems with over 2 million physical qubits by 2030. The gap between current capability and commercially transformative capability is measured in years, not decades.

**The ecosystem is forming.** Cloud access, developer toolkits (Qiskit, Cirq, Q#), curriculum programs, and a growing pipeline of quantum-trained engineers are building the human capital layer that commercial deployment will require.

The case for positioning now is not that quantum computing will definitely transform your industry by 2028. It is that the infrastructure investment cycle is already underway, the hardware is crossing capability thresholds that make commercial applications viable within the decade, and the companies building the foundational layer of this transition are identifiable today.

---

## Part VI: How to Think About Positioning

The investment landscape breaks into three layers with meaningfully different risk/return profiles.

### Layer 1: Embedded Exposure — Lower Risk, Lower Pure-Play Upside

**IBM (IBM)**, **Alphabet/Google (GOOGL)**, and **Microsoft (MSFT)** offer quantum exposure embedded within large, profitable technology businesses. IBM has booked over $1 billion in cumulative quantum business and has the deepest enterprise sales motion in the sector. Google's Quantum AI division produced the Willow milestone and has a credible path to quantum advantage demonstrations on practical problems in 2026. Microsoft's Majorana 1 bet, if it succeeds, could be the most significant quantum computing development of the decade.

For these companies, quantum is one of many growth vectors. The investment is not a pure quantum bet — which is both its safety and its limitation.

### Layer 2: Pure-Play Hardware — Higher Risk, Direct Exposure

**IonQ (IONQ)** is the most credible pure-play quantum investment currently available. Its revenue rests on trapped-ion hardware and partnerships with AWS Braket, Microsoft Azure, and US government programs. The aggressive acquisition strategy — Oxford Ionics, ID Quantique, Capella Space — is building a vertically integrated quantum stack that goes beyond hardware to networking, cryptography, and space-based quantum communication.

IonQ runs at a large adjusted EBITDA loss and has repeatedly issued equity. The multiple depends on the 256-qubit target for late 2026 translating into commercial workloads by 2028–2030. This is a high-conviction, long-duration position — not a trade.

**D-Wave (QBTS)** occupies a distinct niche with quantum annealing rather than gate-based quantum computing. Its advantage is near-term commercial deployability for optimization problems; its limitation is that annealing systems cannot execute the full range of quantum algorithms that gate-based systems can. D-Wave's March 2025 demonstration of quantum supremacy on a real-world materials simulation problem — and its January 2026 acquisition of Quantum Circuits Inc. for $550 million — suggests a company making serious bets on near-term commercial viability.

**Rigetti Computing (RGTI)** and **D-Wave** are higher-risk positions with smaller balance sheets and less diversified revenue. They are venture-like bets on specific technical approaches — appropriate for risk-tolerant investors with genuine conviction in those approaches, but not core positions.

### Layer 3: Enabling Infrastructure — The Picks-and-Shovels Angle

The most overlooked quantum investment category is the enabling infrastructure that every quantum hardware approach requires: cryogenic systems, specialized control electronics, quantum-safe cryptography, photonic components, and the error correction software layer.

Companies supplying into quantum computing programs — analogous to the semiconductor equipment companies that captured significant value from the semiconductor buildout regardless of which chip architecture won — represent a lower-profile but potentially durable exposure to the quantum transition without the binary risk of specific hardware architectures.

---

## Part VII: The Risks — Honest Assessment

The bull case is strong. The risks are also real.

**The timeline problem.** Quantum computing has been "ten years away" from commercial viability for approximately thirty years. The hardware milestones of 2024–2025 are genuinely different in character from previous iterations — but so has every previous wave of optimism felt at the time. Commercial "quantum advantage" for real-world problems is still a work in progress. Useful chemistry, cryptography, and optimization workloads at scale remain a late-decade story.

**Error correction overhead.** The path from physical qubits to logical qubits — from raw hardware that makes errors to reliable computation — requires enormous physical qubit redundancy. Current estimates suggest hundreds to thousands of physical qubits per logical qubit for fault-tolerant computation. This means the qubit counts announced in hardware roadmaps are not directly comparable to the logical qubit counts needed for transformative applications.

**Architecture disruption risk.** Four distinct hardware approaches — superconducting, trapped-ion, neutral atom, and photonic — are competing simultaneously, and none has established a decisive lead toward fault-tolerant computing at scale. If Microsoft's topological qubit approach succeeds, or if PsiQuantum's photonic architecture proves manufacturable at volume, it could disrupt the roadmaps of every current superconducting and trapped-ion player. If neutral atoms scale to millions of qubits as their proponents claim, the current generation of superconducting hardware investments could face a ceiling. The architecture race is genuinely open — which is both the source of the sector's potential and a material source of single-company risk.

**Valuation and dilution.** Pure-plays regularly issue equity to fund R&D, so shareholders absorb dilution as the science advances. This is structural, not a sign of distress — but it means that even correct long-term theses can generate poor returns if entry valuations are elevated and dilution is continuous.

**The killer app problem.** No quantum computing application has yet demonstrated clear, commercially quantified ROI at scale in a real enterprise deployment. The absence of a killer app is the single most important near-term uncertainty.

---

## The Core Thesis

Quantum computing is not a speculative technology waiting for proof of concept. It is a proven technology with demonstrated advantage on specific problem classes, supported by irreversible infrastructure commitments from every major technology company and government, with a hardware roadmap that credibly closes the gap to practical commercial utility within this decade.

The investment is not about betting on which company will win. It is about recognizing that the infrastructure layer of a transformative computing transition is being built right now — and that the companies building it, supplying it, and embedding access to it are identifiable today, before the applications that will depend on it become obvious to everyone.

That is what 2012 cloud looked like. This is what 2026 quantum looks like.

The window for early-infrastructure positioning does not stay open indefinitely.

---

*The best infrastructure investments are made before the applications that justify them are obvious. That is not a flaw in the thesis — it is the thesis.*
