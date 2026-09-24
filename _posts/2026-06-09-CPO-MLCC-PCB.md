---
layout: post
title: "The Hardware Layer Nobody Talks About: CPO, MLCC, and PCB as the Backbone of the AI Buildout"
date: 2026-06-09
categories: Technology
tags: [CPO, MLCC, PCB]
---

When investors talk about the AI infrastructure buildout, the conversation always lands on the same names: Nvidia for GPUs, TSMC for leading-edge fab, hyperscalers for capex. Fair enough. But those are the visible apex of a much deeper supply chain — one that runs down through optical interconnects, passive components, and circuit boards just as indispensable to AI compute as the chips themselves.

Three industries sit at that layer: Co-Packaged Optics (CPO), Multi-Layer Ceramic Capacitors (MLCC), and Printed Circuit Boards (PCB). Each is being structurally reshaped by AI demand. Each has its own competitive map, its own investable names, its own risk profile. And none of them gets the attention the semiconductor names get — which is exactly what makes them interesting.

This post maps all three.

---

## Part I: Co-Packaged Optics (CPO) — The Optical Interconnect Revolution

### What It Is and Why AI Demands It

Co-packaged optics puts the optical transceiver in the same package as the switch ASIC, replacing the pluggable module that used to sit separately on the board. The physics is simple: as data rates push past 800 gigabits per second toward 1.6 terabits, the electrical path between an ASIC and a separate transceiver wastes power and degrades signal in ways you can't engineer away cheaply. CPO removes that path.

The power savings are large — roughly 30 watts per pluggable port down to under 10 watts with CPO, with roadmaps below 5. Across a hyperscale AI data center with hundreds of thousands of ports, that's megawatts saved and millions of dollars a year in energy. Where power availability caps how big an AI cluster can get, CPO isn't a nice-to-have. It's enabling infrastructure.

### The Supply Chain

CPO needs three things: the **switch ASIC** (Broadcom, Marvell, Nvidia), the **silicon photonics die** for electro-optical conversion (Intel Foundry Services, GlobalFoundries, TSMC), and the **laser source** — the part that makes the light the photonics die modulates. The laser is the most constrained and hardest-to-substitute link in the chain.

On lasers, **Coherent (COHR)** and **Lumentum (LITE)** have the most direct exposure. Lumentum has a specific edge: it's currently the only supplier shipping 200G-per-lane EML chips at volume — the critical part for next-generation 1.6T transceivers. Nvidia putting $2 billion into each of Coherent and Lumentum tells you supply security at this layer is strategy, not procurement.

Beyond lasers, the packaging itself — heterogeneous integration of photonic dies with switch ASICs — runs on advanced packaging capacity at TSMC (SoIC, CoWoS, COUPE) and, to a lesser extent, Intel Foundry Services.

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

CPO is hitting its commercial inflection now. Broadcom confirmed shipments of over 50,000 Tomahawk 5-Bailly CPO switches during 2025. Nvidia's Quantum-X800 InfiniBand packs 144 ports of 800G CPO. The shift from pluggable to co-packaged in hyperscale networking should take CPO from under 1% of the optical networking market today to over 35% by 2030. The global CPO market is projected past $20 billion by 2036, at a 37% CAGR.

### Investment Angle

CPO is the most technically demanding — and highest-multiple — of the three. The pure-play optical names (COHR, LITE) give direct exposure with binary risk tied to Nvidia's deployment pace. The platform players (AVGO, MRVL, NVDA) embed CPO inside bigger, diversified businesses — less pure-play torque, far more durability. TSMC, as the irreplaceable packaging layer, gets paid whichever CPO architecture wins. Fabrinet is the picks-and-shovels play: it builds for Coherent, Lumentum, and others, riding volume growth without betting on an architecture.

**Key risk:** CPO needs new data center design standards, and moving from pluggable to co-packaged means switching costs and qualification cycles that slow adoption. The volume ramp is a 2027–2030 story; near-term revenue at the pure-plays still depends on Nvidia's deployment pace.

---

## Part II: MLCC — The Passive Component Nobody Thinks About Until There Is a Shortage

### What It Is and Why AI Changes the Math

Multi-layer ceramic capacitors are passives — they store and discharge energy, stabilize voltage, suppress noise. Small, cheap individually, and everywhere: a modern smartphone holds about 1,000 MLCCs. A traditional server, maybe 5,000. An AI server — an Nvidia GB300 rack unit — holds around 30,000, and a full rack can consume up to 440,000.

That multiplier is the whole thesis. The AI buildout isn't just more MLCC demand — it's a step-change that simultaneously:

- Multiplies unit count per server 6–15x versus traditional servers
- Pushes specs toward ultra-high capacitance, low-ESL, high-voltage variants that need advanced manufacturing and carry higher ASPs
- Concentrates demand on the top-tier Japanese and Korean producers who can actually build to those specs

Volume growing and ASPs rising at the same time — that's what creates operating leverage in a manufacturing business.

### The Supply Chain

MLCC manufacturing is deeply vertically integrated. The inputs: **barium titanate** (the ceramic dielectric), **nickel or copper electrodes**, and the **co-firing process** that sinters dielectric layers down to sub-micron thickness. Controlling that process takes decades of accumulated know-how and proprietary equipment — which is why the top Japanese producers have held their position for 30+ years, and why Chinese competitors, for all their investment, haven't displaced them at the high end.

Murata, TDK, and Taiyo Yuden all ran at full utilization in early 2026 and are expanding capacity in the Philippines and India to meet friend-shoring requirements. That Southeast Asia buildout is about supply security for hyperscaler customers and China+1 risk management at the same time.

### The AI Demand Numbers

MLCC demand for AI servers is expected to compound at 30%, with 2030 needs running more than triple 2025. Murata's president put the AI-server MLCC count at eight times a traditional server — and Murata's book-to-bill is back above 1, which is what expansion looks like.

The AI-server and automotive MLCC market was $4.8 billion in 2025, projected to $16.8 billion by 2034 at a 21.2% CAGR. Japan and South Korea hold over 80% combined share of high-end AI server MLCCs.

EVs are a parallel structural driver. A battery-electric vehicle uses more than three times the MLCCs of an internal-combustion car — traction inverters, onboard chargers, thermal management all need dense decoupling and EMI suppression. AI and auto demand are simultaneous and non-overlapping, which makes the total picture more durable than any single-application cycle.

### Competitive Landscape and Key Names

| Company | Role | Exchange | Ticker |
|---|---|---|---|
| Murata Manufacturing | Global leader, AI + automotive, ~30% market share | TSE | 6981.T |
| TDK Corporation | #2 globally, strong automotive, power magnetics | TSE | 6762.T |
| Taiyo Yuden | AI server + automotive specialist | TSE | 6976.T |
| Samsung Electro-Mechanics | Korean leader, expanding AI server capacity | KRX | 009150.KS |
| Yageo Corporation | Taiwan leader, NVIDIA supply chain, acquired Shibaura | TWSE | 2327.TW |
| Walsin Technology | Mid-tier Taiwan, cost-competitive | TWSE | 2492.TW |

The market stays highly concentrated: Murata, Samsung Electro-Mechanics, and TDK controlled an estimated 60–65% of 2025 revenue. Vertical integration into barium-titanate synthesis and nickel electrode plating shields their margins from raw-material swings, and proprietary co-firing ovens get dielectric layers below 0.6 µm — a gap Chinese manufacturers still haven't closed.

### Investment Angle

MLCC is the most structurally compelling of the three for a patient investor. Dual demand drivers (AI servers + EVs), a real moat with genuinely high barriers, leaders that are profitable and cash-generative today — not pre-revenue — and an industry walking into a pricing cycle, with manufacturers considering price increases as AI demand outruns supply. That's operating leverage.

**Murata (6981.T)** is the anchor: deepest technology, biggest share, strongest balance sheet, most diversified end markets. Yen weakness in 2023–2024 compressed yen-denominated earnings but boosted dollar revenue translation; if the yen normalizes, that tailwind fades — the core business stays structurally advantaged either way.

**Yageo (2327.TW)** is the Taiwan name with the most direct Nvidia exposure — every Nvidia supplier is a Yageo customer — and the most aggressive M&A posture, which means growth optionality plus integration risk. The Shibaura Electronics acquisition added thermistors, giving a sensor dimension to what was a pure passives business.

**TDK (6762.T)** bundles MLCC with power magnetics and sensors — more diversified, less MLCC torque, but a strong automotive MLCC position and real energy-storage exposure through batteries.

**Key risk:** MLCC is cyclical, with a history of inventory gluts followed by corrections. The 2022–2023 consumer MLCC cycle — oversupply, collapsed prices — is the reminder that forecasts can be wrong and lead times can compress fast. AI servers are less cyclical than consumer (longer qualifications, steadier procurement), but a capex pause would still hurt.

---

## Part III: PCB — The Physical Foundation of Every Electronic System

### What It Is and Why Complexity Is the Investment Thesis

Printed circuit boards are the physical substrate everything mounts to — every chip, every passive, every connector. Every AI server, every networking switch, every autonomous-vehicle compute unit starts with a PCB.

The overall PCB market isn't a growth story — about 5% a year, well below the AI-driven sectors above. The thesis is narrower: **AI and defense are forcing a structural shift to ultra-high-complexity boards at four to five times the ASP of standard consumer boards**, and far fewer manufacturers can build them than the industry's headcount suggests.

Hyperscalers moving to 112 Gbps per-lane signaling now buy 40-plus-layer backplanes at nearly four times the price of eight-layer smartphone boards. Those boards need specialized equipment, controlled-impedance processes, and know-how that low-cost producers can't replicate. It's a mix-shift story: the same industry that used to make consumer boards is now competing for work that requires entirely different capabilities.

### The Supply Chain

PCB manufacturing sits where **laminate materials** (copper-clad laminates from Isola, Rogers, Panasonic), **drilling and imaging equipment** (Excellon, Mitsubishi Electric, Orbotech/KLA), and **surface-finishing chemistry** meet. The IC substrate sub-segment — the most demanding boards, sitting directly under advanced chip packages — needs photolithography-class patterning closer to semiconductor fab than traditional PCB.

IC substrates for AI accelerators are the fastest-growing, highest-value PCB corner. Unimicron committed TWD 15 billion to expand IC-substrate capacity in Taoyuan, aimed at AI accelerators and HBM modules. The segment is dominated by a handful of Japanese and Taiwanese producers with decade-long qualification relationships at Intel, AMD, and Nvidia.

### AI and Defense as Dual Demand Vectors

TTM Technologies' Data Center Computing segment grew 57% year-over-year in late 2025. For Q1 2026, management guided another 66% in the vertical, on the specialized boards that high-speed AI accelerators require.

Defense is the equally significant, more durable leg. High-reliability boards for radar, avionics, and comms need MIL-spec qualification and domestic manufacturing — which structurally limits competition to US and allied producers. TTM's Aerospace and Defense segment is 44% of revenue with a record $1.61 billion backlog: multi-year visibility that insulates it from consumer-electronics cyclicality.

### Competitive Landscape and Key Names

| Company | Role | Exchange | Ticker |
|---|---|---|---|
| TTM Technologies | US leader, AI data center + defense | NASDAQ | TTMI |
| Tripod Technology | Taiwan, AI server PCBs, Nvidia supply chain | TWSE | 3044.TW |
| Unimicron Technology | Taiwan, IC substrates for AI accelerators | TWSE | 3037.TW |
| AT&S | Austria/Asia, IC substrates, automotive | Vienna | ATS.VI |
| Ibiden | Japan, IC substrates for Intel and others | TSE | 4062.T |
| Shinko Electric | Japan, IC substrates | TSE | 6967.T |

TTM's book-to-bill of 1.35 and $1.6 billion defense backlog give real forward visibility. The company closed 2025 with record revenue of $2.91 billion and is putting $150 million into New York State rigid-flex lines for avionics and radar — domestic capacity that positions it for defense procurement whatever trade policy does.

**Tripod Technology (3044.TW)** is the Taiwan pure play most levered to AI server boards, deep in the Nvidia supply chain and expanding high-layer-count capacity. Less diversified than TTM, more AI torque.

**Unimicron (3037.TW)** and **Ibiden (4062.T)** play IC substrates — the most demanding, highest-ASP corner of the market. Their demand tracks advanced packaging volumes at TSMC, Intel, and Samsung directly, making them second-order plays on leading-edge semiconductors.

### Investment Angle

PCB investing is about separating commodity producers (low ASP, high volume, Chinese price competition) from complex-board specialists (high ASP, limited competition, long qualifications). Only the second group has a real thesis right now.

TTM is the most accessible US-listed name: AI-plus-defense exposure, a clean financial trajectory — revenue up 22.1% year-over-year to $752.7 million in Q3 2025, adjusted EBITDA margin expanding to 16.1%. The defense backlog is the floor; AI data centers are the upside.

The Japanese IC substrate names (Ibiden, Shinko) offer the highest-value segment, with the caveat that revenue correlates directly to Intel and Nvidia packaging schedules — single-customer concentration at the revenue line.

**Key risk:** PCB capacity takes 2–3 years to build, which invites overshoot as the industry chases current demand. IC substrates have seen this movie before — aggressive expansion, then demand normalization. Long qualification cycles dampen the risk; they don't remove it.

---

## Cross-Industry Synthesis: The AI Hardware Infrastructure Stack

These three aren't independent industries. They're vertical layers of the same physical stack:

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

Each layer rides the AI buildout with different timing, different cyclicality, different competitive dynamics. A portfolio spread across all three is more resilient than concentration in any one — when one layer works through an inventory correction, the others may be at a different point in the cycle.

The common thread: **specification inflation** driven by AI. Servers need more MLCCs, more complex boards, and faster optical links than any previous compute generation. That lifts ASPs and gross margins across the chain simultaneously — a more durable growth engine than volume alone.

---

## Portfolio Construction: A Framework for Allocation

One structured way to own the hardware infrastructure layer:

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
All three share one demand driver — hyperscaler AI capex. A sustained pause or cut in Microsoft, Google, Meta, and Amazon data center spending hits all three at once. The AI capex cycle is the single most important variable for the entire hardware layer.

---

*The chips get the headlines. The components that make the chips work — and the boards that hold them all together — are where the supply chain is quietly becoming the constraint.*
