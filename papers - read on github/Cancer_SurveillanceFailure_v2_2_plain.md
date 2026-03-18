# Cancer as Surveillance Failure — Plain Language Summary

*A plain language summary of "Cancer as Surveillance Failure: A Detection Architecture from Molecular Threshold to Systemic Cascade" (v2.2, March 2026). No medical background required.*

*M. Finnegan · Preprint · Not yet peer reviewed*

*Full paper: [github.com/Sykopompos/Research-Papers](https://github.com/Sykopompos/Research-Papers)*

---

## What this paper is saying

Most people think of cancer as cells that suddenly start multiplying out of control. That framing misses something important. Before any cell can turn cancerous, the body has to fail to catch it — multiple times, in multiple ways, across multiple separate detection systems.

This paper argues that **cancer is fundamentally a detection failure problem.** Every characteristic of cancer — uncontrolled growth, immune evasion, spread to other organs, abnormal metabolism — reflects the disabling of a specific surveillance checkpoint. Understanding cancer through that lens changes what you look for, what you measure, and what you treat.

The paper also argues that cancer doesn't just live in the tumor. It communicates with the immune system, which communicates with the brain, which feeds back to affect the tumor. That loop runs continuously and bidirectionally — but because oncology, immunology, and neurology are separate specialties, nobody owns the whole loop.

---

## Part 1: How cancer starts — the barrier that has to be destroyed

Your cells are not supposed to divide without permission. There's a network of molecular gatekeepers — called tumor suppressors — that keeps cells quiescent unless there's a genuine reason to grow. Think of them as a series of locks on a door that says "don't open."

The key ones:
- **p53** — detects DNA damage and either repairs it or kills the cell
- **Rb** — blocks the cell from entering the division cycle without the right signal
- **PTEN** — suppresses the main "grow now" signal cascade
- **APC** — blocks a proliferative signal in the gut
- **E-cadherin** — keeps cells physically anchored to their neighbors
- **The immune system** — NK cells and cytotoxic T cells patrol for abnormal cells

Each suppressor contributes to the barrier. Losing one weakens it. Cancer requires losing enough of them — in the right sequence — that the barrier collapses entirely.

**Why does it take multiple hits?** Because the architecture is redundant by design. One lost suppressor isn't enough. Multiple independent gates all have to fail before a cell can divide without constraint. This is why cancer takes years to develop despite the fact that mutations happen constantly throughout your life. Each individual mutation is reversible — the cell dies or gets repaired. Only when a surviving clone accumulates enough hits does cancer initiate.

The paper notes this is a consistency check, not a forward derivation — nearly any multi-component redundant system would show structural consistency with a multi-hit requirement. The framework doesn't predict the number 5–7 from first principles; it shows the observation is consistent with the suppressor architecture having roughly that many meaningful contributors.

**Oncogenes are different.** Some cancer mutations don't disable a gate — they install a permanently active "divide now" signal (like a stuck accelerator). KRAS, EGFR, and MYC mutations work this way. These need only one mutation because they don't remove a lock — they add an override that no amount of locking can stop.

**The Warburg effect.** When the main growth signal pathway (mTOR) gets stuck in the "on" position, cancer cells switch to running on sugar even when oxygen is available. This produces large amounts of lactic acid, which acidifies the environment around the tumor — and that acid suppresses the immune cells trying to attack it. Cancer's abnormal metabolism is also an immune evasion strategy.

---

## Part 2: Spreading — a completely separate threshold

A cell becoming cancerous and a cell spreading to other organs are two distinct events separated by months to years. Many tumors stay local for a long time. Spreading requires crossing a **second, independent threshold**.

Your cells are normally held in place by adhesion molecules — molecular anchors that keep them attached to their home tissue. As long as those anchors hold, cells can't wander. The adhesion network is a positional surveillance system: cells in the wrong place get detected and destroyed.

**Metastasis occurs when those anchors are dismantled.** A molecular program called EMT (epithelial-mesenchymal transition) causes cancer cells to dissolve their attachments, change shape, and gain the ability to invade neighboring tissue, enter the bloodstream, survive the journey, and colonize a new organ.

Why does this matter clinically? Because treating the primary tumor doesn't address the metastatic threshold. A cancer that has already crossed into the bloodstream — even microscopically — requires targeting the adhesion surveillance architecture separately.

There's also a direct link to stress. The stress hormone norepinephrine (released by the sympathetic nervous system) activates receptors on tumor cells that upregulate a protein called Bcl-2, which helps circulating tumor cells survive in the bloodstream. Surgical stress produces a spike in norepinephrine — creating a window when tumor cells in circulation are more likely to establish at new sites. This is a mechanistic argument for giving beta-blockers (drugs that block norepinephrine's effects) around the time of cancer surgery.

---

## Part 3: Why immunotherapy works on some cancers and not others

The immune system can recognize and kill cancer cells — but tumors have developed a clever way to shut this down. They express a protein called PD-L1 that puts T cells to sleep when they make contact, essentially telling them "nothing to see here."

Immunotherapy drugs (like pembrolizumab and nivolumab) block this shutdown signal, waking the T cells back up. This works well in some patients and does nothing in others. Why?

**Because the immune system has to have noticed the cancer in the first place.**

For a T cell to attack a cancer cell, it first needs to recognize that the cell is abnormal. It does this by detecting mutant proteins on the cell's surface. The more mutations a tumor has, the more abnormal proteins it displays, and the higher the chance the immune system has already been alerted.

This is measured as **Tumor Mutational Burden (TMB)** — the number of mutations per unit of DNA. Research suggests there's a threshold of roughly 10 mutations per megabase above which the immune system is likely to have been activated. Below it, the immune system never noticed — and reactivating T cells that were never triggered produces nothing.

This explains the ~20% response rate to immunotherapy across unselected populations: only the fraction of tumors above the TMB threshold were ever recognized by immune surveillance. Tumors with very high mutation rates (like certain melanomas and colorectal cancers) paradoxically respond better — the sheer volume of mutations overwhelms the tumor's ability to evade recognition.

---

## Part 4: The loop nobody's managing — the tumor-brain-immune cascade

This is the section of the paper that is most absent from oncology practice.

The tumor doesn't just sit there. It releases inflammatory signals (cytokines) into the bloodstream. Those signals cross into the brain, activate the brain's immune cells (microglia), and trigger a metabolic pathway called the **IDO/kynurenine pathway**. Here's what that does:

1. An enzyme called IDO diverts the amino acid tryptophan away from producing serotonin, toward producing a compound called kynurenine.
2. Kynurenine gets converted in two directions:
   - → **Quinolinic acid (QUIN):** toxic to brain cells, directly damages the hippocampus via NMDA receptor overactivation
   - → **Kynurenic acid (KYNA):** protective, counteracts QUIN
3. When inflammation is sustained, the toxic arm dominates.

This produces two simultaneous brain effects: direct hippocampal damage (from QUIN), and reduced serotonin (from diverted tryptophan). These are two separate mechanisms that have often been described as one — but they require different measurements and potentially different interventions.

**The loop also runs in reverse.** Psychological stress → stress hormone (cortisol) production → cortisol suppresses NK cells and cytotoxic T cells → immune surveillance of the tumor is weakened → tumor grows with less resistance. Chronic stress and cancer aren't just associated — there's a mechanistic pathway connecting them.

And it compounds: high cortisol damages the hippocampus → the hippocampus normally puts the brakes on cortisol production → with the brakes damaged, cortisol rises further → more NK cell suppression → more tumor surveillance failure. It's a positive feedback loop that no single intervention fully addresses without tackling hippocampal health.

---

## Part 5: Cancer fatigue — a proposed mechanism

70–80% of cancer patients experience significant fatigue. The standard explanation is "cytokines, anemia, treatment side effects." The paper proposes a more specific mechanism for a subset of that fatigue — and is explicit that this integrated cascade has not been directly demonstrated in cancer patients. It is a mechanistically plausible hypothesis, not an established finding.

Tumor-driven inflammatory signals activate the brain's norepinephrine system. Normally during deep sleep, norepinephrine drops close to zero — and that drop is what activates the brain's waste clearance system (the glymphatic system) and allows immune cells to prune excess connections. When norepinephrine stays elevated because of tumor-driven inflammation, both processes are impaired simultaneously. Waste accumulates. The brain can't maintain itself.

This would explain the characteristic pattern of cancer fatigue that doesn't respond to rest in the normal way — it's not deconditioning, it's a maintenance deficit.

---

## Part 6: Exercise — four parallel mechanisms, not a lifestyle suggestion

Exercise is commonly described as "good for cancer patients" in a general, soft way. The paper characterizes it as a four-channel immune surveillance support system with specific molecular mechanisms:

**Channel 1 — NK cell mobilization:** Acute exercise drives NK cells out of the spleen and bone marrow into circulation. Regular exercise maintains NK cell number and cytotoxic function.

**Channel 2 — HPA normalization:** Regular moderate exercise reduces cortisol output and improves hippocampal neurogenesis, which strengthens the brain's brake on cortisol production. Less cortisol = more NK cell activity.

**Channel 3 — AMPK/mTOR competition:** Exercise activates a metabolic switch (AMPK) that suppresses the same growth pathway (mTOR) that cancer cells use to outcompete immune cells for glucose. Less mTOR-driven lactate = less acid in the tumor environment = less immune cell suppression.

**Channel 4 — Cholinergic anti-inflammatory reflex:** Exercise improves vagal tone (measurable via heart rate variability). Vagal nerves suppress tumor-promoting inflammatory signals in the tumor microenvironment, reducing the IDO cascade that suppresses T cells.

All four channels are simultaneously withdrawn by physical inactivity. No single drug currently activates all four at once.

---

## Part 7: The hormonal architecture

**Breast cancer:** ~70–75% of breast cancers are driven by estrogen — it directly activates genes for cell division. Treatments that block estrogen (tamoxifen, aromatase inhibitors) or block the downstream cell cycle machinery (CDK4/6 inhibitors like palbociclib) directly target this driver.

**Prostate cancer:** Testosterone and its active form DHT drive prostate cell division through the androgen receptor. Androgen deprivation therapy removes this drive. When resistance emerges, it's because the tumor has found ways around the blockade — amplifying the receptor, developing versions that don't need the hormone, or synthesizing the hormone internally.

**Cortisol:** The stress hormone suppresses both arms of immune surveillance simultaneously — NK cells (innate immunity) and cytotoxic T cells (adaptive immunity). A patient with chronically elevated cortisol is running with their immune system partially disabled regardless of what oncology is doing.

---

## Part 8: The nervous system in the tumor

Solid tumors receive direct sympathetic nerve input. Stress hormones (norepinephrine) act directly on receptors in the tumor to:
- Grow new blood vessels (VEGF upregulation)
- Break down surrounding tissue (MMP upregulation)
- Help circulating tumor cells survive (Bcl-2 upregulation)
- Shift immune cells in the tumor toward a tumor-promoting mode

A Phase II randomized trial (Haldar 2020, n=60) showed that giving the beta-blocker propranolol before surgery reduced markers of tumor aggressiveness in breast cancer. A pilot randomized trial (COMPIT, Ricon-Becker 2023, n=34) showed 0/11 recurrences vs 8/17 in the placebo group at 5 years in colorectal cancer. These are small trials; Phase III confirmation is needed. But the mechanism is established.

The parasympathetic nervous system (via the vagus nerve) runs in the opposite direction — acetylcholine release suppresses inflammatory signals in the tumor environment. Low heart rate variability (a proxy for low vagal tone) means this protective signal is reduced.

---

## Part 9: The biomarker panel the paper proposes

Standard oncology monitors tumors. This paper argues that monitoring the surveillance system itself would be more informative, earlier. The proposed panel uses existing tests that are just not ordered together in oncology:

| Biomarker | What it tells you | Currently used in oncology? |
|---|---|---|
| Tumor Mutational Burden (TMB) | Whether the immune system can recognize the tumor | Yes, for immunotherapy selection |
| Immune infiltrate (NK cells, CD8+ T cells in tumor) | Whether surveillance is actively operating | Increasingly yes |
| Kynurenine:tryptophan ratio | Whether IDO is suppressing T cells AND driving the brain cascade | No |
| Cortisol diurnal slope | Whether HPA axis is suppressing NK and T cell activity | No |
| Heart rate variability (HRV) | Real-time balance between pro-tumor (sympathetic) and anti-tumor (parasympathetic) signaling | No |
| NK cell cytotoxicity (functional) | Whether NK cells can actually kill — number alone is insufficient | Rarely |
| Circadian immune amplitude | Whether the nightly immune surveillance peak is intact | No |

The panel logic: TMB tells you if the gate has been triggered. Immune infiltrate tells you if surveillance is active. K:T ratio tells you if IDO is suppressing it. Cortisol tells you if HPA is suppressing it. HRV tells you if the tumor microenvironment is being driven toward permissiveness in real time. None require new technology. They require ordering existing tests across specialties that don't currently communicate in oncology.

---

## What this paper is, and what it isn't

**It is:** A unified framework for understanding cancer as a multi-system surveillance failure. A mechanistic argument that the tumor-brain-immune loop is real, bidirectional, and currently unmanaged. A proposal for a surveillance-derived biomarker panel. Seven testable predictions, each with specified direction of effect and what would falsify them.

**It is not:** A clinical protocol. A claim that any of the proposed combinations are proven. A dismissal of standard oncology — the framework extends standard treatment rather than replacing it.

The individual mechanisms are established across decades of research in separate literatures. The synthesis — mapping them as a single integrated cascade — is new, and its value depends on whether the predictions hold.

---

*Full paper, references, and data: [github.com/Sykopompos/Research-Papers](https://github.com/Sykopompos/Research-Papers)*
*v2.2 — March 2026 — Preprint — Not yet peer reviewed*
