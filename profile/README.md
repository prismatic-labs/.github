## Prismatic Labs

Making systemic complexity legible.

### Why we build

AI runs on the physical world: the minerals, energy, and water it consumes, and the invisible human "ghost work" that keeps it running. Almost none of that flows back, and nothing in the system even registers how lopsided the exchange has become. We don't think that's a law of nature, it's a design choice, and the good news about design choices is that they can be remade.

What we're working toward is symbiotic AI: technology and the living planet structurally bound, each sustaining the other, with AI's dependence on the world wired in rather than ignored. The first step is the concrete, unglamorous one, and it's where everything we build begins: taking the hidden dependencies AI runs on, and the costs they carry, and making them visible, sourced, and something you can actually act on.

### What we cover

The physical footprint of AI is the energy a call draws, the water a facility cools with, the hardware it wears through, the land and grid capacity it occupies, and the materials and supply chains that sit underneath all of that, long before a prompt ever reaches a model.

Here is how much of it our work actually reaches today, and where it doesn't. **Strong** means a layer is measured and published. **Partial** means the structure exists but the data is thin or narrow. **Missing** means nobody here is working on it yet.

| Layer | Coverage | Covered by | What is missing |
|---|---|---|---|
| Compute / data centres | **Strong** | London Compute Ring, Yorkshire Compute Belt, Culm | Two UK regions, 100 sites. Nothing on the US, EU or Asian build-out. |
| Electricity | **Strong** | Cloud Kettle Index, Vetch, the compute maps | Load is modelled from national statistics, never metered. GB and Northern Virginia only. A power figure exists for 80% of London sites, 54% of Yorkshire. |
| Water | **Partial** | Vetch, the compute maps | Annual water is recorded for 3 of 89 London sites and 1 of 11 in Yorkshire — operators don't disclose it. Vetch's WUE is usually a fleet average, not a region-published figure. No catchment or water-stress context. |
| Chips | **Strong** | Culm | Six of Culm's eight layers: EUV, EDA, leading-edge fab, HBM, advanced packaging, accelerators. Measured as concentration, not as fab energy, water or emissions. Legacy nodes absent. |
| Critical minerals | **Strong** | Alyssum, Culm | Alyssum covers the 17 EU strategic raw materials; 15 have country figures, boron and germanium have none USGS can compare. No mine-level environmental cost — tailings, water, energy. EU shares are floors, not totals. |
| Construction | **Missing** | — | The build itself: concrete, steel, groundworks, embodied emissions. The maps hold planning refs and timelines, but nothing on what construction costs physically. |
| Networking | **Missing** | — | Subsea cable, long-haul fibre, interconnect, transit. Culm's stack stops at cloud; Vetch has no network fields. |
| Land | **Partial** | The compute maps | Land type is recorded for every site, but an area figure for only 15% of London sites (63% in Yorkshire). No cumulative land take, no greenbelt or agricultural-loss totals. |
| Hardware lifecycle | **Partial** | Vetch | Embodied manufacturing carbon is amortised into each call from a single factor, not per-accelerator data. Nothing on refresh cycles, resale, reuse or end of life. |
| Cooling | **Partial** | The compute maps, Vetch | Cooling type is recorded for 3 of 89 London sites and 3 of 11 in Yorkshire. Vetch separates cooling water in its accounting. No link drawn between cooling choice and the water and power it costs. |
| People | **Missing** | — | Labelling, annotation and moderation labour. Construction and operations workforce. The job numbers claimed in planning applications are recorded as claims, and nobody has checked them. |
| Logistics | **Missing** | — | Freight of chips, transformers and plant. Tare models how shocks travel through shipping and energy into prices; the method transfers, it has not been pointed at AI hardware. |
| Waste | **Missing** | — | E-waste, decommissioned servers, spent coolant. One London site is recorded as decommissioned and nothing follows it. (Vetch and the Waste Booth cover *wasted inference* — a different sense of the word.) |
| AI ↔ environment feedback | **Missing** | — | The loop closing: AI demand reshaping grids, water and land, and those limits bounding AI in turn. Culm's shock mode and Tare both model propagation; neither completes the circle. |
| Inference waste (demand side) | **Strong** | Vetch, AI Waste Booth | Twelve detection patterns, with warn / kill / reroute. The only layer where our tooling acts rather than observes. Not yet validated against third-party production fleets. |
| Grid connection & queue | **Partial** | The compute maps | Connection data for 3 of 89 London sites, 6 of 11 in Yorkshire. The queue, not generation, is what actually gates the build-out. |
| Siting & local consent | **Partial** | The compute maps | Controversies, claims on record and operator responses are held per site. No systematic tracking of objections, consultations or how they resolve. |

Last reviewed 5 October 2026. Corrections and missing sources are welcome as issues on any repo.

### The projects

🌱 **[vetch](https://github.com/prismatic-labs/vetch)** - Inference waste control for production LLM systems. Detect stalled agents, RAG bloat, and runaway inference, then stop them automatically. Open source, Apache 2.0.

🌾 **[culm](https://github.com/prismatic-labs/culm)** - AI Stack Concentration Map. A sourced, layer-by-layer measurement of how few actors and countries control each physical layer of the AI hardware stack.

🌼 **[alyssum](https://github.com/prismatic-labs/alyssum)** - Who makes the EU's 17 strategic raw materials? A periodic table of world supply, built from USGS figures, against the Critical Raw Materials Act's 65% benchmark.

🫖 **[Cloud Kettle Index](https://github.com/prismatic-labs/cloud-kettle-index)** - Britain's data-centre electricity load, translated into kettle-boils per second.

🏙️ **[The London Compute Ring](https://github.com/prismatic-labs/ldn-compute)** - A public, sourced map of the physical footprint of AI and cloud data centres across Greater London and the M25 fringe: power, land, and water.

🏭 **[The Yorkshire Compute Belt](https://github.com/prismatic-labs/yorkshire-compute-belt)** - A public, open-source map of the physical footprint of AI and cloud infrastructure across Yorkshire and the Humber.

🌿 **[tare](https://github.com/prismatic-labs/tare)** - Your food depends on the Strait of Hormuz. A live tracker of the crisis costs hidden in everyday food: energy, fertilizer, and shipping. Open data, open source.

🧾 **[AI Waste Booth](https://github.com/prismatic-labs/ai-waste-booth)** - A pop-up booth that prints you a receipt for the hidden footprint behind your AI use. Built for Ox Tech Week 2026.

🍀 **[clover](https://github.com/prismatic-labs/clover)** *(beta)* - The cost-of-living crisis, in your community's mental health. Maps how economic stressors flow through to regional mental health pressure across 10 countries. Evidence-based, open data.

### Learn more

- 🌐 [prismaticlabs.ai](https://prismaticlabs.ai)
- 📜 [A Tiny Manifesto for Planet-Aware AI](https://www.linkedin.com/posts/mzdifraia_ai-depends-on-what-it-degrades-it-cant-activity-7424399227121741824-8R4n)
