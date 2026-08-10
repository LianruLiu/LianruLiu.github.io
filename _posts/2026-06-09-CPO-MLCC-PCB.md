---
layout: post
title: "The Hardware Layer Nobody Talks About: CPO, MLCC, and PCB as the Backbone of the AI Buildout"
date: 2026-06-09
categories: [Technology, Investment, Industry Analysis]
tags: [CPO, MLCC, PCB, semiconductor]
---

When investors discuss the AI infrastructure buildout, the conversation almost always centers on the same names: Nvidia for GPUs, TSMC for leading-edge fabrication, hyperscalers for capital expenditure commitments. These are legitimate focal points. But they represent the visible apex of a much deeper supply chain — one that extends downward through optical interconnects, passive components, and circuit boards that are just as indispensable to AI compute as the chips themselves.

Three industries sit at this layer: Co-Packaged Optics (CPO), Multi-Layer Ceramic Capacitors (MLCC), and Printed Circuit Boards (PCB). Each is undergoing a structural transformation driven by AI demand. Each has a distinct competitive landscape, a distinct set of investable names, and a distinct risk profile. None of them is as crowded with investor attention as the semiconductor names — which is precisely what makes them interesting.

This post maps all three.

---

## Part I: Co-Packaged Optics (CPO) — The Optical Interconnect Revolution

### What It Is and Why AI Demands It

Co-packaged optics integrates optical transceivers directly into the same package as the switching ASIC, replacing the traditional pluggable module that sits separately on the circuit board. The physics argument is straightforward: as data rates push through 800 gigabits per second toward 1.6 terabits, the electrical signal path between an ASIC and a separate transceiver module becomes a source of power waste and signal degradation that cannot be engineered away at reasonable cost. CPO eliminates that path.

The power reduction is significant — from approximately 30 watts per pluggable port to under 10 watts in CPO configurations, with roadmaps targeting below 5 watts. At the scale of a hyperscale AI data center with hundreds of thousands of ports, that difference translates into megawatts of saved power and millions of dollars annually in energy costs. For data centers where power availability is a binding constraint on AI cluster scale, CPO is not a nice-to-have. It is enabling infrastructure.

### The Supply Chain

CPO requires three distinct technology contributions: the **switch ASIC** (Broadcom, Marvell, Nvidia), the **silicon photonics die** that handles electro-optical conversion (Intel Foundry Services, GlobalFoundries, TSMC), and the **laser source** — the component that generates the light that silicon photonics modulates. The laser source is the most technically constrained and least easily substituted element in the chain.

Key laser suppliers: **Coherent (COHR)** and **Lumentum (LITE)** are the two companies with the most direct exposure to the laser component market. Lumentum holds a particular advantage: it is currently the only supplier shipping 200G-per-lane EML (electro-absorption modulated laser) chips at volume — the critical component for next-generation 1.6T transceivers. Nvidia's $2 billion investment commitment into each of Coherent and Lumentum signals that supply security at this layer is a strategic priority, not a procurement decision.

Beyond lasers, the CPO packaging layer itself — heterogeneous integration of photonic dies with switch ASICs — relies on advanced packaging capacity at TSMC (SoIC, CoWoS, COUPE platform) and to a lesser extent Intel Foundry Services.

### Competitive Landscape and Key Names

| Company | Role | Exchange | Ticker |
|---|---|---|---|
| Broadcom | Switch ASIC + CPO platform (Tomahawk/Bailly) | NASDAQ | AVGO |
| Nvidia | Switch ASIC + CPO platform (Quantum-X, Spectrum-X) | NASDAQ | NVDA |
| Marvell | Switch ASIC + CPO (Teralynx, acquired Celestial AI) | NASDAQ | MRVL |
| Coherent | Laser components, optical modules | NYSE | COHR |
| Lumentum | EML laser chips, optical components | NASDAQ | LITE |
| TSMC | Advanced packaging (SoIC, CoWoS) | NYSE / TWSE | TSM / 2330 |
| Fabrinet | Contract manufacturing for optical components | NYSE | FN |

### Market Trajectory

The CPO market is in its commercial inflection year. Broadcom confirmed shipments of more than 50,000 Tomahawk 5-Bailly CPO switches during 2025. Nvidia's Quantum-X800 InfiniBand integrates 144 ports of 800G CPO. The transition from pluggable to co-packaged in hyperscale data center networking is expected to move CPO penetration from under 1% of the optical networking market today to over 35% by 2030. The global CPO market is projected to exceed $20 billion by 2036 at a 37% CAGR.

### Investment Angle

CPO is the most technically complex and highest-multiple investment in this trio. The pure-play optical names (COHR, LITE) offer direct exposure with binary risk tied to Nvidia's deployment pace. The platform players (AVGO, MRVL, NVDA) offer CPO exposure embedded within larger, diversified businesses — lower pure-play sensitivity but far more durable. TSMC, as the irreplaceable packaging infrastructure, captures value regardless of which CPO architecture wins. Fabrinet is the picks-and-shovels angle: it manufactures for Coherent, Lumentum, and others, benefiting from volume growth without architecture concentration risk.

**Key risk:** CPO requires new data center design standards, and the transition from pluggable to co-packaged involves switching costs and qualification cycles that slow adoption. Volume ramp is a 2027–2030 story; near-term revenue at pure-plays remains Nvidia-deployment-dependent.

---

## Part II: MLCC — The Passive Component Nobody Thinks About Until There Is a Shortage

### What It Is and Why AI Changes the Math

Multi-Layer Ceramic Capacitors are passive components — they store and discharge electrical energy, stabilize voltage, and suppress noise in electronic circuits. They are small, inexpensive individually, and utterly ubiquitous: a modern smartphone contains approximately 1,000 MLCCs. A traditional server contains perhaps 5,000. An AI server — an Nvidia GB300 rack unit — contains approximately 30,000 MLCCs, and an entire server rack can consume up to 440,000.

That multiplier is the core of the MLCC investment thesis. The AI buildout is not just a demand increase for MLCCs — it is a demand step-change that simultaneously:

- Multiplies unit count per server by 6–15x versus traditional servers
- Shifts the required specifications toward ultra-high capacitance, low-ESL (equivalent series inductance), and high-voltage variants that require advanced manufacturing and carry higher average selling prices
- Concentrates demand on the top-tier Japanese and Korean manufacturers who can produce at the required specifications

The result is a market where volume is growing and ASPs are rising simultaneously — the combination that produces operating leverage in manufacturing businesses.

### The Supply Chain

MLCC manufacturing is highly vertically integrated. The key inputs are **barium titanate** (the ceramic dielectric material), **nickel or copper electrodes**, and the **co-firing process** that sinters thin dielectric layers to sub-micron thickness. Process control at this scale requires decades of accumulated manufacturing knowledge and proprietary equipment — which is why the top-tier Japanese manufacturers have maintained their competitive position for 30+ years and why Chinese competitors, despite aggressive investment, have not displaced them in high-end specifications.

Murata, TDK, and Taiyo Yuden all ran full utilization in early 2026 and expanded capacity in the Philippines and India to satisfy friend-shoring mandates. This capacity expansion into Southeast Asia reflects both supply security demand from hyperscaler customers and geopolitical risk management following China+1 procurement strategies.

### The AI Demand Numbers

MLCC demand for AI servers is expected to grow at a CAGR of 30%, with projected needs in 2030 exceeding three times that of 2025. Murata's president noted that the number of MLCCs used in AI servers is eight times that of traditional servers — and Murata's book-to-bill ratio has returned above 1, signaling industry expansion.

The MLCC for AI Server and Automotive Market was valued at $4.8 billion in 2025 and is projected to reach $16.8 billion by 2034, growing at a CAGR of 21.2%. Japan and South Korea dominate the high-end MLCC market, holding a combined market share of over 80% for AI server MLCCs.

Beyond AI servers, EVs represent a parallel structural demand driver. Battery electric vehicles consume more than three times the MLCC count of internal-combustion platforms — traction inverters, onboard chargers, and thermal management circuits each require dense decoupling and EMI suppression. The automotive and AI demand vectors are simultaneous and non-overlapping, making the overall demand picture more durable than a single-application cycle.

### Competitive Landscape and Key Names

| Company | Role | Exchange | Ticker |
|---|---|---|---|
| Murata Manufacturing | Global leader, AI + automotive, ~30% market share | TSE | 6981.T |
| TDK Corporation | #2 globally, strong automotive, power magnetics | TSE | 6762.T |
| Taiyo Yuden | AI server + automotive specialist | TSE | 6976.T |
| Samsung Electro-Mechanics | Korean leader, expanding AI server capacity | KRX | 009150.KS |
| Yageo Corporation | Taiwan leader, NVIDIA supply chain, acquired Shibaura | TWSE | 2327.TW |
| Walsin Technology | Mid-tier Taiwan, cost-competitive | TWSE | 2492.TW |

The MLCC market remains highly concentrated: Murata, Samsung Electro-Mechanics, and TDK controlled an estimated 60–65% of revenue in 2025. Vertical integration into barium-titanate synthesis and nickel electrode plating shields their margins from raw-material swings, while proprietary co-firing ovens enable sub-0.6 µm dielectric layers — a capability gap that Chinese manufacturers have not closed.

### Investment Angle

MLCC is the most structurally compelling of the three industries for a patient investor. The demand drivers are dual (AI servers + EVs), the competitive moat is genuine and high-barriers-to-entry, the leading players are profitable and cash-generative today rather than pre-revenue, and the industry is entering a pricing cycle — MLCC manufacturers are considering price increases as AI demand outpaces supply — which creates operating leverage.

**Murata (6981.T)** is the anchor holding: deepest technology, highest market share, strongest balance sheet, most diversified end-market exposure. The JPY weakness of 2023–2024 compressed yen-denominated earnings for yen-reporting companies but boosted Murata's dollar revenue translation. A yen normalization scenario reduces this tailwind; the core business remains structurally advantaged regardless.

**Yageo (2327.TW)** is the Taiwan-listed name with the most direct Nvidia supply chain exposure — all Nvidia suppliers are Yageo customers — and the most aggressive M&A posture, which brings both growth optionality and integration risk. Its acquisition of Shibaura Electronics expanded into thermistors, adding a sensor dimension to what was previously a pure passive component business.

**TDK (6762.T)** offers MLCC plus power magnetics plus sensors — broader diversification, slightly lower MLCC pure-play sensitivity, but a strong automotive MLCC position and meaningful energy storage exposure through its battery business.

**Key risk:** MLCC is a cyclical industry with a history of inventory accumulation followed by correction. The consumer electronics MLCC cycle of 2022–2023, when oversupply collapsed prices, is a reminder that demand forecasts can be wrong and lead times can compress rapidly. The AI server segment is less cyclical than consumer electronics (longer qualification cycles, more stable procurement patterns), but it is not immune to capex pauses.

---

## Part III: PCB — The Physical Foundation of Every Electronic System

### What It Is and Why Complexity Is the Investment Thesis

Printed circuit boards are the physical substrates on which every semiconductor, passive component, and connector is mounted and interconnected. They are the literal platform on which the electronic system sits. Every AI server, every networking switch, every autonomous vehicle compute unit begins with a PCB.

The PCB market is not a growth story in the traditional sense — the overall market grows at roughly 5% annually, well below the AI-driven sectors discussed above. The investment thesis is more specific: **AI and defense applications are driving a structural shift toward ultra-high-complexity PCBs that carry ASPs four to five times those of standard consumer boards**, and the manufacturers capable of producing them are a much smaller set than the overall PCB industry would suggest.

Hyperscale data-center operators upgrading to 112 Gbps per-lane signaling now order 40-plus-layer backplanes that carry selling prices nearly four times those of eight-layer smartphone boards. These high-layer-count, tight-tolerance boards require specialized equipment, controlled-impedance processes, and manufacturing know-how that low-cost Asian PCB producers cannot replicate. The migration from commodity to complex is a mix shift story — the same factories that once made consumer electronics boards are competing for work in a market segment that requires completely different capabilities.

### The Supply Chain

PCB manufacturing sits at the intersection of **laminate materials** (copper-clad laminates from companies like Isola, Rogers, Panasonic), **drilling and imaging equipment** (dominated by Excellon, Mitsubishi Electric, and Orbotech/KLA), and **surface finishing chemistry**. The IC substrate sub-segment — the most technically demanding boards used directly under advanced chip packages — additionally requires photolithography-class patterning processes more similar to semiconductor fab than traditional PCB.

IC substrates for AI accelerators represent the fastest-growing and highest-value PCB sub-segment. Unimicron Technology committed TWD 15 billion to expand IC-substrate capacity in Taoyuan, targeting AI accelerators and high-bandwidth memory modules. The IC substrate market is dominated by a small group of Japanese and Taiwanese manufacturers with decade-long qualification relationships with Intel, AMD, and Nvidia.

### AI and Defense as Dual Demand Vectors

TTM Technologies' Data Center Computing segment grew by a staggering 57% year-over-year in late 2025. For Q1 2026, management projected an additional 66% increase in this vertical, driven by the specialized PCBs required for high-speed AI accelerators.

The defense dimension is equally significant and more durable. High-reliability PCBs for radar, avionics, and communications systems require MIL-spec qualification and domestic manufacturing — a requirement that structurally limits competition to US and allied-nation producers. TTM's Aerospace and Defense segment represents 44% of revenue with a record $1.61 billion backlog, providing multi-year revenue visibility that insulates it from typical consumer electronics cyclicality.

### Competitive Landscape and Key Names

| Company | Role | Exchange | Ticker |
|---|---|---|---|
| TTM Technologies | US leader, AI data center + defense | NASDAQ | TTMI |
| Tripod Technology | Taiwan, AI server PCBs, Nvidia supply chain | TWSE | 3044.TW |
| Unimicron Technology | Taiwan, IC substrates for AI accelerators | TWSE | 3037.TW |
| AT&S | Austria/Asia, IC substrates, automotive | Vienna | ATS.VI |
| Ibiden | Japan, IC substrates for Intel and others | TSE | 4062.T |
| Shinko Electric | Japan, IC substrates | TSE | 6967.T |

TTM's book-to-bill ratio of 1.35 and aerospace and defense backlog of $1.6 billion reinforce visibility into future demand. The company closed 2025 with record revenues of $2.91 billion and is investing $150 million in New York State for rigid-flex lines dedicated to avionics and radar — a domestic manufacturing investment that positions it well for defense procurement requirements regardless of trade policy environment.

**Tripod Technology (3044.TW)** is the Taiwan-listed pure play most directly levered to AI server PCB demand, with deep integration into the Nvidia supply chain and expanding capacity for high-layer-count boards. Less diversified than TTM but higher AI-specific growth sensitivity.

**Unimicron (3037.TW)** and **Ibiden (4062.T)** play in the IC substrate segment — the most technically demanding, highest-ASP corner of the PCB market. IC substrate demand is directly linked to advanced chip packaging volumes at TSMC, Intel, and Samsung, making these names effectively second-order plays on leading-edge semiconductor demand.

### Investment Angle

PCB investing requires distinguishing between the commodity producers (low ASP, high volume, subject to Chinese price competition) and the complex-board specialists (high ASP, limited competition, long qualification cycles). Only the latter group has a credible investment thesis in the current environment.

TTM is the most accessible US-listed name with the AI/defense dual exposure and the cleanest financial trajectory — revenue surging 22.1% year-over-year to $752.7 million with adjusted EBITDA margins expanding to 16.1% in Q3 2025. The defense backlog provides a floor; AI data center growth provides the upside.

The Japanese IC substrate names (Ibiden, Shinko) offer exposure to the highest-value PCB segment with the caveat that their revenue is directly correlated to Intel and Nvidia wafer packaging schedules, introducing single-customer concentration risk at the revenue level.

**Key risk:** PCB capacity additions require long lead times (2–3 years for new facilities), which creates the possibility of supply overshoot as the industry responds to current demand. The IC substrate segment has seen this dynamic before — aggressive capacity expansion followed by demand normalization. Qualification cycle length mitigates but does not eliminate this risk.

---

## Cross-Industry Synthesis: The AI Hardware Infrastructure Stack

These three industries are not independent. They are vertically related layers of the same physical infrastructure:

```
AI Compute Cluster
        │
        ├── GPU / ASIC (Nvidia, Broadcom, Marvell)
        │         mounted on...
        ├── PCB / IC Substrate (TTM, Tripod, Unimicron, Ibiden)
        │         populated with...
        ├── MLCC and Passive Components (Murata, TDK, Yageo)
        │         connected via...
        └── CPO / Optical Interconnects (Coherent, Lumentum, Fabrinet)
```

Each layer benefits from the AI buildout, but with different timing, different cyclicality, and different competitive dynamics. The investment implication is that a portfolio with exposure across all three layers is more resilient than concentration in any single one — when one layer is in an inventory correction cycle, the others may be at a different phase.

The structural commonality: all three are benefiting from **specification inflation** driven by AI. Servers require more MLCCs, more complex PCBs, and faster optical connections than any previous generation of compute infrastructure. That specification inflation raises average selling prices and gross margins across the supply chain simultaneously — a more durable growth mechanism than pure volume increases.

---

## Portfolio Construction: A Framework for Allocation

Given the analysis above, a structured approach to the hardware infrastructure layer might look like the following:

**Core holdings (higher conviction, more durable):**
- Murata (6981.T) — MLCC anchor, technology leadership, dual AI/EV demand
- TTM Technologies (TTMI) — AI + defense PCB, clean financial trajectory, domestic manufacturing advantage
- TSMC (TSM / 2330.TW) — CPO packaging enabler, benefits regardless of CPO architecture winner

**Growth exposure (higher sensitivity, higher risk):**
- Lumentum (LITE) — CPO laser pure-play, unique 200G EML capability, Nvidia-dependent
- Yageo (2327.TW) — Taiwan MLCC, Nvidia supply chain, M&A optionality
- Tripod Technology (3044.TW) — Taiwan AI server PCB, high AI growth sensitivity

**Infrastructure/picks-and-shovels:**
- Fabrinet (FN) — optical component contract manufacturing, benefits from CPO volume regardless of architecture
- TDK (6762.T) — MLCC + magnetics + sensors diversification, lower concentration risk

**Key cross-portfolio risk to monitor:**
All three industries share a common demand driver — hyperscaler AI capex. A sustained pause or reduction in Microsoft, Google, Meta, and Amazon data center spending would affect all three simultaneously. The AI capex cycle is the single most important variable to track for the entire hardware infrastructure layer.

---

*The chips get the headlines. The components that make the chips work — and the boards that hold them all together — are where the supply chain is quietly becoming the constraint.*
