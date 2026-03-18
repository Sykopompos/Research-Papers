# Why Cancer Returns — Plain Language Summary

*A plain language summary of "Why Cancer Returns: The Incomplete Treatment Map and What a Full Surveillance Architecture Requires" (v1.2, March 2026). No medical background required.*

*M. Finnegan · Preprint · Not yet peer reviewed*

*Full paper: [github.com/Sykopompos/Research-Papers](https://github.com/Sykopompos/Research-Papers)*
*Companion paper: [Cancer as Surveillance Failure v2.2](https://github.com/Sykopompos/Research-Papers)*

---

## The one-sentence version

Cancer comes back because treatment addresses one or two nodes of a multi-node failure cascade while leaving the others intact — and the surviving tumor evolves around whatever was applied.

---

## Why recurrence isn't random

The common experience of cancer recurrence — it was gone, then it came back — feels like bad luck. The paper argues it is substantially mechanistically predictable. Not in the sense that we can predict which individual patient will relapse, but in the sense that the failure modes are structurally inevitable given what current treatments do and don't address.

A few examples make this concrete:

**Hormone-receptor-positive breast cancer** can recur 10–15 years after completing endocrine therapy. That's not a new cancer appearing out of nowhere — it's a dormant cluster of cells that survived under anti-estrogen pressure, waiting for conditions to become permissive. The treatment suppressed the visible tumor. It didn't correct the conditions that allowed it to grow.

**Castration-resistant prostate cancer** typically emerges within 18–24 months of hormone-deprivation therapy alone. This isn't failure of the drug — it's the predictable result of removing the tumor's primary growth signal and watching it evolve a workaround: amplifying its androgen receptor, developing versions that don't need the hormone, or synthesizing the hormone internally. The drug created a selection pressure. The tumor adapted to it.

**Cold tumors failing immunotherapy** — the ~80% of patients who don't respond to checkpoint blockade drugs — aren't experiencing drug failure. The checkpoint drugs work by waking up T cells that were already attacking the tumor. If the tumor's mutation load was too low for the immune system to recognize it in the first place, there are no alerted T cells to wake up. The gate was restored, but nobody was waiting on the other side.

Each of these is a structural consequence of treating one node of a multi-node cascade. Understanding why cancer returns requires mapping what was corrected and what wasn't.

---

## The incomplete treatment map

The paper maps every standard cancer treatment against the full failure architecture — what each one addresses, what it leaves intact, what the predictable failure mode is, and what the architecture says is missing.

**Surgery** removes the primary tumor but doesn't restore any of the molecular defenses that failed to stop it. The tumor microenvironment remains permissive, circulating tumor cells may already be in transit, and surgery itself triggers a stress response that temporarily spikes norepinephrine — a stress hormone that helps circulating tumor cells survive in the bloodstream. The window right around surgery may be the highest-risk window for establishing metastatic disease, for mechanistic reasons that are currently unmanaged.

**Chemotherapy** kills rapidly dividing cells but leaves slower-cycling cancer stem cells intact. It also disrupts the gut microbiome (which affects immune function), depletes NK cells and cytotoxic T cells, and worsens the stress hormone dysregulation that suppresses immune surveillance. The immune system that would ideally clean up what chemo doesn't kill is itself being damaged by the treatment.

**Immunotherapy (checkpoint blockade)** restores the T-cell activation gate, but doesn't address:
- The ~80% of tumors with insufficient mutation burden for T cells to recognize them
- The cortisol-mediated suppression of NK and T-cell activity that operates independently
- The IDO/kynurenine pathway that suppresses T cells inside the tumor environment
- The sympathetic nervous system-driven signals that push immune cells in the tumor toward a tumor-promoting mode

**Hormone therapies** (for breast and prostate cancer) remove the primary hormonal growth driver but leave other growth pathways intact. Resistance emerges when the tumor finds alternative routes — mutating the hormone receptor to work without the hormone, or activating the PI3K/mTOR pathway that runs parallel to the hormonal one.

**Psycho-oncology** addresses psychological distress and quality of life, but the trials show inconsistent survival benefit. The paper's reading: the mechanism is real (stress suppresses immune surveillance through cortisol and sympathetic activation), but the trials don't measure the mechanistic parameters — cortisol levels, NK cell function, heart rate variability — so the effect gets obscured in noise.

**Exercise** is prescribed for fitness and fatigue reduction, often under-dosed, rarely timed strategically, and never monitored for its immune effects. The paper (companion) established four parallel mechanisms by which exercise supports immune surveillance. None of them are tracked in oncology trials of exercise, so the actual mechanistic benefit is unmeasured and the dose-response is unknown.

---

## Five upstream targets that nobody manages

Across all the failure modes above, five system-level parameters determine whether immune surveillance can actually operate — and none of them are managed as primary endpoints in standard oncology:

**1. The HPA/cortisol axis**

Cortisol suppresses NK cells and cytotoxic T cells simultaneously. A patient with chronically elevated cortisol receiving immunotherapy is fighting against cortisol-mediated immune suppression at the same time — the checkpoint gate has been nominally restored, but a separate force is holding it partially closed. Cortisol levels are not measured in oncology.

There's a feedback loop that makes this worse: high cortisol damages the hippocampus, which normally puts the brakes on cortisol production. With the brakes weakened, cortisol rises further, suppressing more immune activity. This loop can run independently of tumor biology once established.

**2. IDO activation state (kynurenine:tryptophan ratio)**

Inside tumors, an enzyme called IDO converts tryptophan (which T cells need to proliferate) into kynurenine (which directly suppresses T cells). This is one of the most potent immune suppression mechanisms in the tumor microenvironment — and it's currently not measured in standard oncology.

A Phase III trial of an IDO inhibitor (epacadostat + pembrolizumab, ECHO-301) failed. The oncology field largely concluded IDO was not a valid target. The paper's reading: the trial combined IDO-high and IDO-low patients without stratifying by who actually had IDO suppression active. IDO inhibition is only mechanistically relevant in tumors with high kynurenine:tryptophan ratios. Giving it indiscriminately is the same category error as giving immunotherapy without checking whether the immune system recognized the tumor.

**3. Sympathetic/parasympathetic balance (heart rate variability)**

The balance between the stress nervous system (sympathetic) and the calming nervous system (parasympathetic) in the tumor microenvironment determines macrophage behavior, NK cell activity, and angiogenic signaling simultaneously. High sympathetic dominance — measurable as low heart rate variability — means the tumor environment is being pushed toward permissiveness in real time. No oncology protocol measures or adjusts for this.

**4. mTOR metabolic competition**

Cancer cells have their growth machinery locked in the "on" position, consuming glucose at maximum rate and producing lactic acid. This acidic environment suppresses NK cells and T cells — they can't compete metabolically or function properly in a low-pH environment. Drugs and interventions that activate the cellular energy sensor AMPK (exercise, metformin) can suppress this metabolic advantage, improving the conditions under which immune cells operate. This is not managed as an oncology endpoint.

**5. Sleep and circadian immune amplitude**

NK cell cytotoxicity peaks during the day; T-cell trafficking and proliferation peak overnight under melatonin control. Cancer patients with untreated sleep apnea, chronic sleep disruption from stress hormones, or irregular sleep schedules are missing a nightly immune surveillance peak — silently, invisibly, without any current oncology monitoring capturing it.

The tumor itself may be actively suppressing this nightly peak: tumor-driven inflammatory signals activate the brain's norepinephrine system, which delays melatonin release, which reduces the overnight NK cell activation that normally occurs. The tumor is suppressing its own overnight surveillance through the autonomic-pineal axis — and nobody is tracking it.

---

## The monitoring gap

Standard oncology monitoring measures tumor response (imaging, blood markers) and treatment toxicity (blood counts, organ function). What it doesn't measure is the upstream system that determines whether immune surveillance is actually operating.

The result is an inverted monitoring architecture: measuring the output of the failure cascade while the inputs go untracked.

By the time a tumor marker rises, recurrence is already established. The upstream parameters that determine whether the conditions for recurrence were ever corrected — cortisol, IDO activation, sympathetic balance, NK cell function, circadian immune amplitude — are not in the monitoring stack.

One striking data point: a flat cortisol diurnal slope (elevated evening cortisol, blunted morning peak) independently predicted earlier mortality in a study of metastatic breast cancer patients (n=104, 7-year follow-up). Cortisol measurement is available, cheap, and not used in oncology.

---

## Combinations that address different nodes

The most valuable combinations in cancer treatment aren't ones that add more of the same — they're ones where each component addresses what the other cannot. The paper identifies the highest-priority non-redundant combinations:

**Exercise + immunotherapy:** Exercise activates four separate immune pathways (NK mobilization, cortisol reduction, metabolic competition, parasympathetic anti-inflammatory tone). Immunotherapy restores the checkpoint gate. Neither addresses what the other addresses. Exercise before immunotherapy may "warm" cold tumors — improving metabolic and cortisol conditions so that more tumors cross the threshold where immune surveillance activates. Not yet tested in a trial with immune infiltrate as a primary endpoint.

**Cortisol normalization + immunotherapy:** Pre-treating patients with elevated cortisol (via exercise, psychological support, or sleep improvement) before immunotherapy removes a suppressive force that the checkpoint drugs don't address. Not yet tested.

**IDO inhibition + immunotherapy, stratified:** The failed ECHO-301 trial tested this combination without measuring who had IDO suppression active. Redoing it in patients with confirmed high kynurenine:tryptophan ratios is the obvious next step. Not yet done.

**Sleep apnea treatment + any immune intervention:** Treating sleep apnea restores the nightly NK cell activation peak. Doing that before or alongside immune-activating interventions means the immune system is operating at fuller capacity. Not studied as an oncology co-intervention.

**Beta-blockers + perioperative care:** Blocking the stress hormone norepinephrine around the time of surgery reduces tumor cell survival signals and slows the pro-metastatic cascade during the highest-risk window. Two randomized trials have shown signals (Haldar 2020, COMPIT 2023). Phase III confirmation is needed.

---

## What cascade-complete intervention would look like

A treatment program that addresses the full failure cascade would require coordinating five specialties around a shared target map:

| What to address | Who manages it now | Who should co-manage it |
|---|---|---|
| HPA / cortisol suppressing NK and T cells | Psycho-oncology (partially) | Oncology as primary endpoint |
| IDO/kynurenine suppressing T cells in tumor | Nobody | Oncology + immunology |
| Sympathetic dominance driving tumor microenvironment | Nobody in oncology | Autonomic medicine + oncology |
| mTOR metabolic competition impairing immune cells | Endocrinology (for metformin in diabetics) | Oncology + metabolic medicine |
| Sleep/circadian immune amplitude | Sleep medicine (if referred for QoL) | Oncology as immune surveillance endpoint |
| Tumor checkpoint | Oncology | Already managed |

Every intervention required already exists. What doesn't exist is the architecture for deploying them together, with shared monitoring endpoints, by specialists who communicate with each other.

The paper is explicit about the barriers: reimbursement is fragmented across specialties, trial infrastructure isn't designed for multi-modal lifestyle-plus-pharmacological combinations, and off-patent drugs like propranolol and metformin that feature prominently in the non-redundant combination logic generate no commercial development incentive.

---

## Seven trial designs the paper proposes

The architecture generates specific trial designs, not just general suggestions. The highest priority:

1. **Exercise before immunotherapy** — 12-week exercise program before initiating checkpoint blockade, in patients with intermediate tumor mutation burden. Primary endpoint: immune cell density in tumor, not just tumor shrinkage.

2. **Cortisol normalization before immunotherapy** — Pre-treat patients with flat cortisol diurnal slope before starting immunotherapy. Track NK cell function as the intermediate mechanism.

3. **IDO inhibition + immunotherapy, stratified by K:T ratio** — The ECHO-301 trial that failed, run correctly with patients stratified by who actually has IDO suppression active.

4. **Sleep apnea treatment as an immune intervention** — CPAP initiation in cancer patients with untreated sleep apnea; primary endpoint NK cell function at 3 and 6 months.

5. **Metformin + immunotherapy, stratified by insulin resistance** — Testing whether AMPK activation improves immunotherapy outcomes specifically in patients with metabolically hostile tumor microenvironments.

6. **Comprehensive upstream monitoring** — Tracking TMB, IDO activation, cortisol, HRV, NK function, and circadian immune amplitude in a large prospective cohort, asking whether the upstream panel predicts recurrence before tumor markers rise.

7. **Perioperative beta-blockade, Phase III** — Powered trial of propranolol around surgery in high-risk solid tumors, building on the Phase II signals already in hand.

---

## The bottom line

Cancer recurrence is treated in oncology as an unfortunate event — sometimes inevitable, sometimes manageable with second-line treatment. The paper argues it is largely structurally predictable from the architecture of what was and wasn't corrected.

The immune surveillance system, the stress hormone axis, the IDO/kynurenine pathway, the autonomic nervous system balance in the tumor microenvironment, and the circadian immune clock are all part of the system that determines whether a tumor can grow or is held in check. Current oncology manages one or two of those nodes. The others are managed — if at all — by separate specialists who don't communicate with oncology and who don't use cancer recurrence as their primary endpoint.

The surveillance architecture already exists in the body. The coordination infrastructure to manage it doesn't yet exist in medicine.

---

*Full paper, references, and data: [github.com/Sykopompos/Research-Papers](https://github.com/Sykopompos/Research-Papers)*
*v1.2 — March 2026 — Preprint — Not yet peer reviewed*
