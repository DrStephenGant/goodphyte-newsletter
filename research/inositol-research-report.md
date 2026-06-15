# Inositol and IP6 (Phytate): From Plant Seed Store to Human Cell Signal

*A deeply-sourced research report for the GoodPhyte newsletter. Compiled from five
parallel web-research sweeps with adversarial cross-checking of contested claims.
Last updated: 2026-06-15.*

> **Evidence labels used throughout:** **[ESTABLISHED]** = strong, consistent, multi-source;
> **[EMERGING]** = real but limited/low-certainty human data; **[CONTESTED]** = sources
> genuinely disagree; **[PRECLINICAL]** = cell/animal only; **[MARKETING OVERREACH]** =
> claim outruns the human evidence. Citations are inline by short title; full URLs in the
> reference list at the end.

---

## Executive summary

Inositol is a small six-carbon sugar alcohol (a cyclohexanehexol) that life has used for
billions of years as a chemical "pegboard": its six hydroxyls can each carry a phosphate,
letting cells encode information in how many phosphates sit where. The fully loaded form —
**myo-inositol hexakisphosphate, IP6, also called phytic acid or phytate** — is the dominant
phosphorus and mineral store in plant seeds, and the same molecule does structural and
signaling jobs inside animal cells. The de-loaded form, **free myo-inositol**, is the backbone
of cell-membrane phosphatidylinositol and the source of the calcium-releasing second messenger
IP3 (Ins(1,4,5)P3).

For the newsletter's core theme, the key fact is mechanical: **IP6's six negatively-charged
phosphates chelate iron, zinc, calcium and magnesium into insoluble complexes that block
absorption.** The enzyme **phytase** strips those phosphates one at a time (IP6 → IP5 → … →
inositol). Crucially, **only IP6 and IP5 strongly inhibit mineral absorption in humans; once
degraded to IP4/IP3 the inhibition largely disappears.** Humans make almost no gut phytase of
their own, so mineral release depends on plant-intrinsic phytase (activated by soaking,
sprouting, sourdough fermentation) and on colonic microbiota — which is exactly why food
processing changes how much iron and zinc you actually absorb.

Inositol itself is **not a vitamin** for humans (the old "vitamin B8" label is deprecated): we
synthesize grams per day from glucose-6-phosphate in kidney and liver. Frank dietary deficiency
is therefore rare in people, though it readily produces fatty liver in inositol-deprived rodents
and gerbils. The clinically interesting human situations are *functional, tissue-local* depletion
(nerve tissue in diabetes; follicular fluid in PCOS) and *supplementation* trials.

On therapy, the honest picture is layered. **Established:** phytase as an animal-feed enzyme.
**Genuinely promising but low-certainty:** myo-inositol for gestational-diabetes prevention and
for PCOS metabolic markers, and IP6 (as the IV drug SNF472) for vascular calcification.
**Preliminary/small:** mood disorders, IVF. **Evidence reversed toward harm:** myo-inositol for
preterm respiratory distress — a large NICHD trial was stopped early for *increased* mortality.
**Marketing overreach:** "IP6 Gold"-type cancer-cure claims, which rest on preclinical data only.

The arc of this report follows the molecule: how IP6 is broken down, how inositol enters the
body and the cell, what systems it touches, how cells build it back up to IP6 and beyond, its
deep evolutionary history, what deficiency does, how plants use it, and what medicine has
actually done with it.

---

## The IP6 ↔ inositol cycle, in words

```
PLANT SEED                         GUT / DIET                         INSIDE THE CELL
----------                         ----------                         ---------------
IP6 stored in globoids   --->   phytase (plant, microbial,    --->   free myo-inositol absorbed
(aleurone/protein                negligible human) strips              via SMIT2 (apical gut),
storage vacuoles),               phosphates: IP6→IP5→IP4→IP3            SMIT1, HMIT
chelating K,Mg,Ca,Fe,Zn          →IP2→IP1→ myo-inositol
                                                                        |
   mineral release as            mineral inhibition lost                v
   phosphates come off           below IP5 (IP4/IP3 don't          membrane phosphatidylinositol
                                 block Fe in humans)               (PI) ──PLC──> IP3 (Ins-1,4,5-P3)
                                                                        |          + DAG → Ca2+, PKC
de novo route (also in           also: dietary free inositol            |
animal cells): glucose-6-P       + phosphatidylinositol;            kinase ladder rebuilds:
──MIPS/ISYNA1──> Ins(3)P1        endogenous synthesis (kidney,      inositol→Ins(3)P1→…→IP3→IP4
──IMPA1──> myo-inositol          liver) makes grams/day            ──IPMK/ITPK1──>IP5──IPPK/IPK1──>IP6
                                                                    ──IP6K──>IP7──PPIP5K──>IP8
```

The single most important conceptual warning: **the "IP3" of cell signaling (Ins(1,4,5)P3, made
at the membrane by phospholipase C) is a different isomer and a different pool from the "IP3"
that appears transiently while dietary phytate is being dephosphorylated in the gut.** Same gross
formula, different molecule, different job. Do not conflate them.

---

## 1. Chemistry and nomenclature

- **Inositol** is cyclohexane-1,2,3,4,5,6-hexol. Of its nine stereoisomers, **myo-inositol** is
  overwhelmingly the biological form; **D-chiro-inositol (DCI)**, **scyllo-** and **neo-** isomers
  matter in specific niches. ["Inositol — ScienceDirect Topics"]
- The phosphorylation ladder: free inositol → InsP1 → InsP2 → InsP3 → InsP4 → InsP5 → **InsP6
  (IP6 / phytic acid / phytate)** → **inositol pyrophosphates IP7 (5-PP-InsP5) and IP8
  (1,5-(PP)2-InsP4)**, which carry high-energy phosphoanhydride bonds.
- **Phytic acid** is the free acid; **phytate** is its mineral-salt form. Its phosphate pKa
  values (~1.8, 2.3, 2.5 … 9.3) mean the phosphate oxygens are already deprotonated and available
  to grab metal cations even at gastric/intestinal pH. ["Phytic acid — ChemicalBook"]
- **Terminology the requester raised:** "myoline" is almost certainly **myo-inositol** (and in a
  nervous-system context could be confused with **myelin** — an unrelated axonal lipid sheath; see
  §4). "Cytokine" effects are covered under inflammation/immunity (§4).

## 2. How IP6 is broken down by phytase

**Enzyme classes.** Four structurally distinct phytase families: **histidine acid phosphatases
(HAP)**, **β-propeller phytases (BPP)**, **purple acid phosphatases (PAP)**, and **cysteine/
PTP-like phytases**. ["Phytase — ScienceDirect Topics"] They are also classified by which
phosphate they remove first: **3-phytase (EC 3.1.3.8)** attacks the 3-position first (typical of
fungi and most bacteria), **6-phytase (EC 3.1.3.26)** the 6-position first (plants and *E. coli*).
["3-Phytase — ScienceDirect Topics"]

**The cascade.** Phytases remove phosphates one at a time, each product feeding the next:
**IP6 → IP5 → IP4 → IP3 → IP2 → IP1 → free myo-inositol.** Different enzyme origins release
different positional isomers in different orders. **[Caveat / CONTESTED endpoint]** Many phytases
stop at **myo-inositol 2-monophosphate (Ins(2)P)** — liberating only 5 of 6 phosphates; full
release to free inositol needs an additional phosphatase. ["4-Phytase — ScienceDirect Topics"]

**Sources of phytase in digestion.**
- **Human endogenous intestinal phytase is negligible** — "plays a minor role" — unlike ruminants
  (rumen microbes) and rodents (higher intrinsic activity). ["Phytase and phytate degradation in
  humans — PubMed 2541385"]
- **Gut microbiota** can degrade phytate substantially in the colon, and diet-dependently: a
  fruit/vegetable-rich diet shifted microbiota so that up to **100%** of phytate was degraded in
  vitro. Probiotic lactobacilli/bifidobacteria make phytases. ["Diet shapes microbiota to degrade
  phytate — Markiewicz 2013"]
- **Plant-intrinsic phytase** is the main practical lever: high in whole-grain rye, wheat,
  triticale, buckwheat, barley; **oats have almost none**; maize/rice are low. Optima ≈ 45–60 °C,
  pH 5. ["Effects of temperature, pH on intrinsic phytase of wheat, barley, rye"]
- **Microbial/fungal feed phytases** (added to monogastric feed): first commercial product was an
  *Aspergillus niger* 3-phytase (1991); bacterial *E. coli* AppA (a 6-phytase) later outperformed
  it. ["Microbial phytase: sources, production, role"]

**Food processing → IP profile shift.** Soaking ~24–32% reduction (up to 100% optimized);
germination ~25–35% (up to 68–87% for sorghum, raising phytase 3–5×); **sourdough fermentation
~60%** in whole-wheat; combined soak+germinate+ferment up to ~85%. Ordinary boiling is relatively
ineffective. Processing lowers IP6/IP5 and generates IP4/IP3/IP2/IP1. ["Effects of soaking,
germination and fermentation on phytic acid — WUR"; "Bioavailability during soaking/germination
of sorghum — PMC3189212"]

**The mineral payoff (core newsletter theme).** As phosphates come off, chelation weakens and
minerals are released. The pivotal nutritional nuance: **in humans, IP6 and IP5 inhibit iron
absorption, but IP3 and IP4 in isolation do not** — so degrading IP6 down to IP4/IP3 abolishes
most of the inhibition. ["Inositol phosphates with different numbers of phosphate groups influence
iron absorption in humans"] Metal–phytate complex stability runs **Cu > Zn > Co > Mn > Fe > Ca**;
zinc binds tightest, but calcium drives the largest real-world effect because it is abundant and
Ca–phytate co-precipitates zinc. ["Formation and stability of phytate complexes"] Practical
thresholds widely used: **phytate:Zn < 15** (ideally < 5), **phytate:Fe < 1** (ideally < 0.4),
and a **phytate × Ca / Zn** ratio when calcium is high. ["Gibson 2010 — Review of Phytate, Iron,
Zinc, Calcium"] **[CONTESTED nuance]** Caco-2 cell studies show *all* inositol phosphates (IP3–IP6)
reduce iron uptake 50–65%, conflicting with the human-absorption finding above — i.e., the
IP4/IP3 "safe" conclusion is system-dependent. ["Inositol phosphates inhibit uptake of iron and
zinc in a human intestinal cell line — PubMed 8145081"]

## 3. How inositol gets into the body

**Dietary forms & amount.** Inositol arrives as **free myo-inositol**, **phospholipid-bound
(phosphatidylinositol)**, and as **phytate** that microbes/phytase hydrolyze to release inositol.
A typical 2000-kcal diet supplies ~**720 mg/day** myo-inositol (~56% lipid-bound; range ~250–1650
mg/day); rich sources include fruit, beans, grains, nuts. ["Myo-inositol content of common foods —
AJCN"]

**Endogenous synthesis.** The body makes several grams per day: **ISYNA1/MIPS** converts
glucose-6-phosphate → myo-inositol-3-phosphate (4-step, NAD⁺-dependent, rate-limiting), then
**IMPA1 (inositol monophosphatase)** → free myo-inositol. Kidney and liver are major sites.
["Regulations of myo-inositol homeostasis"]

**Intestinal transporters** (secondary-active cotransporters):
- **SMIT2 / SLC5A11** — the apical intestinal transporter; in rat small intestine it mediates
  *all* apical myo-inositol uptake; ~2 Na⁺:1 inositol, Km ≈ 120 µM; also carries DCI.
  ["SMIT2 mediates all myo-inositol uptake in apical membranes of rat small intestine — PubMed
  17932225"]
- **SMIT1 / SLC5A3** — ubiquitous Na⁺-coupled osmoregulatory transporter; does not carry DCI.
- **HMIT / SLC2A13** — H⁺-coupled, mainly brain; minor in gut.

**Is intact IP6 absorbed? [CONTESTED — genuinely unresolved].** The **Grases group** reports
measurable plasma IP6 that tracks diet (basal ~0.07 mg/L on low-IP6 diet vs ~0.26 mg/L on normal
diet; plasma peak ~4 h; urinary IP6 after a 400 mg oral dose), arguing intact IP6 is absorbed.
["Absorption and excretion of orally administered IP6 in humans — Grases 2001"] **Counter-evidence:**
a newer high-sensitivity method found *no* phytate detectable in human plasma or urine, suggesting
the earlier signal was an artifact. ["Conundrum of IP6 — PMC4680566"] The prevailing nutrition
view: dietary IP6 is largely hydrolyzed in the gut, and **inositol — not intact IP6 — is what is
meaningfully absorbed**; oral-IP6 supplement bioavailability is disputed. Intracellular IP6 (made
endogenously, §6) is a separate pool from dietary IP6.

**Distribution.** Inositol concentrates in brain, kidney medulla, testis, and the eye lens; nerve
tissue concentrates free myo-inositol ~90–100× over plasma. Kidney sets circulating levels via
synthesis and reabsorption.

## 4. Systems inositol/IP6 affects

**Cell signaling — the phosphoinositide cycle [ESTABLISHED].** Phospholipase C hydrolyzes membrane
**PIP2 (PI(4,5)P2)** into **DAG** (stays in membrane, activates PKC) and soluble **IP3
(Ins(1,4,5)P3)**, which opens **IP3 receptors on the ER** to release Ca²⁺. PLC is switched on by
GPCRs and receptor tyrosine kinases; PIP2 is continuously resynthesized by the PI cycle.
["PIP2 signal pathway — News-Medical"; "Mammalian PI-PLC isozymes — MDPI"] The broader **lipid
code**: Class I PI3K makes **PIP3 (PI(3,4,5)P3)** to recruit PDK1/AKT; **PTEN** reverses it
(3-phosphatase) and **SHIP1/2** make PI(3,4)P2 (5-phosphatase); PI3P, PI4P each mark distinct
membranes. ["The PI3K signaling pathway in normal and malignant B cells — PMC3414724"]

**Insulin, diabetes, PCOS [EMERGING — see §10 for trial grades].** Both myo-inositol and DCI feed
**inositol phosphoglycan (IPG)** insulin second messengers; an insulin-dependent epimerase
converts MI→DCI most in liver/muscle, least in brain/heart, setting tissue-specific **myo:DCI
ratios** (plasma ~40:1; follicular fluid ~100:1). Reduced DCI availability is linked to insulin
resistance. ["PCOS and Inositols — Frontiers 660381"]

**Nervous system / neuropsychiatry.** **Clarification [ESTABLISHED]: myo-inositol ≠ myelin.**
Myo-inositol is an astroglial **osmolyte** (~6 mM in astrocytes, near-zero in neurons), an MRS
glial-proliferation marker; myelin is the axonal lipid sheath — unrelated. ["Myo-inositol and
grading of cerebral astrocytomas — AJNR"] The **lithium inositol-depletion hypothesis** (lithium
inhibits IMPase → depletes inositol → damps PI signaling) is mechanistically plausible but
clinically **[CONTESTED]**: an MRS trial found lithium did not change prefrontal myo-inositol.
["Lithium and bipolar… inositol-depletion hypothesis revisited"] Small 1990s crossover RCTs
(12–18 g/day) showed benefit in depression, panic, and OCD but none in schizophrenia/Alzheimer's/
ADHD/autism — small, old, unreplicated at scale.

**Inflammation / cytokines / immunity [PRECLINICAL].** IP6 enhances NK-cell activity, modulates
TNFα/IL-1β, polarizes macrophages toward an anti-inflammatory M2a phenotype, and acts via PI3K/
MAPK/PKC/AP-1/NF-κB; its iron chelation suppresses Fenton-reaction hydroxyl radicals (antioxidant).
["IP6 modulates macrophages — PMC8194914"; "IP6 on TGF-β isoforms — PMC3891539"] All data are
cell/animal; no human RCT supports IP6/inositol as an anti-inflammatory drug.

**Cancer [PRECLINICAL-rich, human-WEAK].** IP6 is taken up and dephosphorylated to lower IPs that
interfere with signal transduction → cell-cycle arrest (↑p27, ↓pRb via PKCδ), apoptosis, PI3K/Akt
suppression, antiangiogenesis (↓VEGF/HIF-1α); 2% IP6 in drinking water cut prostate xenograft
growth 52–59%. ["IP6 suppresses prostate carcinoma via PI3K-Akt — PMC2819750"; "Broad-spectrum
anticancer activity of myo-inositol and IP6"] **But human evidence is only case reports/small
studies; no large RCTs.** See §10 marketing flag.

**Bone, kidney stones, vascular calcification [strongest IP6 clinical data].** IP6 is a potent
crystallization inhibitor binding hydroxyapatite and calcium-oxalate growth sites. The IV drug
**SNF472 (hexasodium IP6)** reached **Phase 3 (CALCIPHYX)** for calciphylaxis and slowed coronary/
aortic-valve calcification in hemodialysis patients in Phase 2. ["SNF472… therapeutic phytate
levels — J Nephrol"; "Relevance of phytate for CKD — PMC11469791"] Oral phytate for **kidney-stone
prevention is [CONTESTED]**: an in-vivo human study found "no hard evidence" it changes stone-risk
factors. ["Phytate ingestion, urinary excretion, renal stone risk — J Renal Nutrition"]

**Briefly:** NAFLD (small human RCTs: MI improved liver/metabolic markers), fertility/IVF (small
RCTs, signal concentrated in PCOS), and preterm RDS (now negative — §10).

## 5. How inositol gets into cells and mitochondria

**Cellular uptake** uses the same **SMIT1, SMIT2, HMIT** transporters; SMIT1 is osmotically
regulated (a major brain/kidney osmolyte system) and even tunes electrical excitability by
adjusting PI(4,5)P2. ["Inositol transport proteins — FEBS Lett"; "SMIT1 modulates electrical
activity by adjusting PI(4,5)P2 — PNAS"]

**Glucose competition / diabetic depletion [CONTESTED].** Hyperglycemia competitively inhibits the
Na⁺-coupled inositol transporter, and the classic theory holds that nerve inositol depletion →
reduced Na⁺/K⁺-ATPase → diabetic neuropathy. ["Role of myo-inositol in diabetic complications —
Trends Endocrinol Metab"] But the "**inositol paradox**" undercuts the simple model: after
prolonged high glucose, transport is *up-regulated*, and a Mayo/NEJM nerve-biopsy study found
nerve myo-inositol **not decreased** in diabetic patients — sorbitol, not inositol, tracked fiber
loss. ["Upregulation of myo-inositol transport compensates for glucose inhibition — Diabetes 1993";
"Nerve glucose, fructose, sorbitol, myo-inositol… NEJM 1988"] Robust in rats, inconsistent in
humans.

**Intracellular remodeling** is run by kinases/phosphatases — IPMK/IPK2, ITPK1, IP6K1/2/3,
PPIP5K/VIP, PTEN, SHIP — covered in §6.

**Mitochondria [THIN — flag].** The strongest concrete data: deleting **IP6K2** in mouse cerebella
lowered phosphocreatine and ATP and impaired **ETC Complex III**, via 5-IP7 acting on
creatine-kinase-B. ["IP6K2 determines cellular energy dynamics via creatine kinase-B — PMC8017945"]
But a defined inositol-phosphate pool *inside the mitochondrial matrix* is not established; most
"mitochondrial" effects are inferred from whole-cell knockouts and phosphate-homeostasis signaling
(strongest in yeast). Treat mitochondrial inositol bioenergetics as the thinnest area.

## 6. How inositol is built back up into IP6

The intracellular kinase ladder reverses the gut breakdown:
- **MIPS/ISYNA1** → Ins(3)P1; **IMPase** → free inositol (also the lithium target).
- **IPMK (IPK2)** and **ITPK1** phosphorylate IP3 → IP4 → IP5 (IPMK is a promiscuous multikinase,
  also acting on lipids).
- **IPPK / IP5-2K (= IPK1)** catalyzes the final **IP5 → IP6**.
- **IP6K1/2/3** make **5-IP7** from IP6; **PPIP5K1/2 (VIP1/2)** add the 1-position to make 1-IP7
  and, with IP6K, **IP8**. ["Inositol phosphate kinases: expanding biological significance —
  PMC9364425"; "Structural insights into IP-kinase inhibitors — PMC12823050"]

**Inositol pyrophosphates (IP7/IP8) [ESTABLISHED as phosphate sensors].** They control cellular
phosphate homeostasis through **SPX-domain** receptors (the conserved **INPHORS** system across
yeast, plants, animals); in yeast the decline of **1,5-IP8** specifically triggers the
phosphate-starvation program. IP6K isoforms also tie 5-IP7 to insulin secretion and (paradoxically)
Akt inhibition, with IP6K3 knockout protecting against age-related insulin resistance. ["Metabolism
and Functions of Inositol Pyrophosphates — PMC7583957"; "Targeting inositol pyrophosphate enzymes
in metabolic diseases — PMC7144392"; "IP6K3 regulates metabolism and lifespan — Sci Rep"]

**IP6 as a structural cofactor in proteins [ESTABLISHED].** IP6 is buried in the **ADAR2** RNA-editing
core (required for folding/activity); inositol phosphates act as "intermolecular glue" activating
**HDAC3–SMRT** corepressor complexes; IP6 + Gle1 activates the **Dbp5** helicase for mRNA export;
IP6 mediates **cullin-RING ligase / COP9** function; and IP6 is an essential cofactor in **HIV-1
Gag/capsid assembly** (~1 IP6 per Gag hexamer), extending mature-capsid lifetime from minutes to
hours. ["IP6 bound in ADAR2 core — PMC1850959"; "Inositol phosphates are assembly co-factors for
HIV-1 — Nature 2018"; "Mature HIV-1 capsid stabilization by IP6 — Sci Adv"] (A 2026 ADAR1-cofactor
preprint extends this — flagged as not yet peer-reviewed.)

## 7. Appearance in other organisms and evolutionary history

- **Antiquity [ESTABLISHED, with interpretive edges].** Inositols are ancient, likely present in a
  common ancestor of Archaea and Eukarya; phosphoinositide signaling and inositol-phosphate kinases
  are ubiquitous in eukaryotes. ["Inositol derivatives: evolution and functions — Nat Rev Mol Cell
  Biol"]
- **Bacteria/Archaea.** **Di-myo-inositol-phosphate (DIP)** is a major heat-protective osmolyte in
  hyperthermophiles (Pyrococcus, Thermotoga, Aquifex), rising at supraoptimal temperatures.
  ["Biosynthesis of DIP in hyperthermophilic archaea — J Bacteriol"]
- **Fungi.** Yeast is the workhorse model: Ipk2→IP4/IP5, Ipk1→IP6, Kcs1→IP7/IP8; roles in stress,
  trafficking, autophagy, energy. ["Kcs1 and Vip1 in S. cerevisiae — PMC10886477"]
- **Protists.** *Dictyostelium* slime mold carries unusually high IP6 (≈520 µM) and enabled the
  *discovery* of IP7/IP8; *Entamoeba histolytica* uses an unusual **neo-inositol** phosphate.
  ["Dictyostelium inositol pyrophosphate metabolism — PMC3887064"; "neo-inositol polyphosphates in
  Entamoeba — PubMed 10744695"]
- **Deep conservation [ESTABLISHED].** The IP-binding consensus **PxxxDxKxG** is conserved across
  fungi, animals and plants; IP3-receptor orthologs trace to the unicellular *Capsaspora*; the
  **INPHORS/SPX** phosphate-sensing system is conserved across kingdoms. Lineages diverged in
  emphasis — metazoans amplified IPK enzymes, plants expanded ITPKs. ["Origin/evolution of IP3
  3-kinases — BMC Genomics"; "IP3 receptor history in Capsaspora — Mol Biol Evol"]
- **Evolutionary hypotheses [FLAGGED interpretive].** IP6/inositol-pyrophosphates likely act as an
  ancient phosphate/energy-charge sensor (ITPK1 can even run 5-IP7→IP6 in reverse to regenerate ATP
  at low energy charge). Seed phytate is framed as an evolved phosphorus reserve *and* an
  antinutrient in a plant–herbivore "arms race" — interpretation, not settled fact. ["Biosynthesis
  and functions of inositol pyrophosphates in plants — PMC4325660"; "Seed biofortification and
  phytic acid reduction — PMC4844270"]

## 8. What happens in deficiency (animals and humans)

**Animals [ESTABLISHED in models].** Inositol-deprived **rats** develop **fatty liver** (2.6–5.3×
liver triglycerides) via impaired hepatic triglyceride/VLDL secretion — most striking as a
**lactation-dependent fatty liver** in dams. **Gerbils** show hepatic lipid accumulation plus a
characteristic **intestinal lipodystrophy**, fully reversible within 1–4 days by inositol. Inositol
(and phytate) are **lipotropic**, blunting sucrose-induced steatosis. ["Myo-inositol-responsive
liver lipid accumulation in the rat — J Nutr"; "Inositol deficiency in gerbils: intestinal
lipodystrophy"] **Species-specificity is the key nuance:** *female* gerbils have a true dietary
requirement; *males* synthesize enough (testicular synthesis) — which is why frank deficiency is
hard to produce in most mammals, including humans.

**Humans [largely functional, not dietary].** Inositol is **not a vitamin** ("vitamin B8" is
deprecated) — we synthesize grams/day in kidney/liver, so frank deficiency is rare. ["Is there a
vitamin B8? — Biology Insights"] The relevant human contexts are *functional/tissue-local*
depletion: the **diabetic-neuropathy depletion theory** (robust in rats, **[CONTESTED]** in humans,
§5), and **preterm infants**, where serum inositol is 2–20× adult levels and a premature drop
predicts worse RDS — preterm colostrum is the richest natural source (4.22 mM vs formula
0.09–0.39 mM). ["RDS and inositol supplementation in preterm infants — PMC1778095"] Note this is a
*physiological* observation; the *therapeutic* trial reversed (§10).

## 9. How plants use inositol and IP6

- **Storage [ESTABLISHED].** Phytate is the primary seed phosphorus store — up to ~80% of seed P,
  ~1–1.5% of dry weight — held as **globoids in protein-storage vacuoles**, concentrated in the
  **aleurone** (wheat/barley/rice) or embryo/scutellum (maize), nearly absent from starchy
  endosperm; it chelates K, Mg, Ca, Fe, Mn, Zn. ["Globoids and Phytase — PMC7589363"; "Phytate:
  impact on environment and human nutrition — JZUS B"]
- **Germination [ESTABLISHED].** Endogenous phytases (cereal HAP/MINPP-type and purple acid
  phosphatases) hydrolyze phytate to free phosphate, myo-inositol, and minerals for the seedling.
  ["Structure of a cereal purple acid phytase — PMC9073318"]
- **Phosphate sensing [ESTABLISHED].** **InsP8** is an intracellular Pi signal in Arabidopsis,
  synthesized by **VIH1/VIH2**; it binds **SPX1**, enabling SPX1–**PHR1** interaction that governs
  the phosphate-starvation transcriptional program. ["InsP8 as intracellular phosphate signal in
  Arabidopsis"; "Inositol pyrophosphates + SPX–PHR — PMC7810988"]
- **Hormone signaling [ESTABLISHED].** **IP6** is a cofactor in the auxin receptor **TIR1**; **IP5
  (Ins(1,2,4,5,6)P5)** is built into the jasmonate co-receptor **COI1–JAZ**. ["Jasmonate perception
  by IP-potentiated COI1–JAZ — Nature"]
- **Guard cells [ESTABLISHED].** ABA generates IP6 in guard cells, which mobilizes endomembrane
  Ca²⁺ and inhibits inward K⁺ current to drive **stomatal closure**. ["IP6 regulates K⁺-inward
  rectifying conductance in guard cells — PNAS"]
- **Other inositol derivatives.** **Galactinol/raffinose-family oligosaccharides** (desiccation/
  cold/drought protection), **methylated inositols pinitol/ononitol** (osmolytes via IMT), and the
  **MIOX** pathway (myo-inositol → glucuronic acid → cell-wall sugar nucleotides; stress/ROS roles).
  ["Galactinol and RFO synthesis in plants — PMC4549555"; "OsMIOX and salinity stress — PMC10462604"]
- **Agriculture [ESTABLISHED].** **Low-phytic-acid (lpa) mutants** in maize/barley/rice cut
  phytate-P 50–>95% (lpa2 maize is a mutated inositol-phosphate kinase); monogastrics excrete ~90%
  of phytate-P (P pollution), motivating **phytase feed supplementation**; lpa foods raised
  fractional Fe absorption to 8.2% (vs 5.5%) and Zn to 30% (vs 17%). ["Low phytic acid crops: four
  decades of research — PMC7076677"; "Maize lpa2 is a mutation in an inositol phosphate kinase gene
  — PMC166827"; "Progress in breeding low-phytate crops"]

## 10. Use in treatments (evidence-graded)

| Use | Population | Evidence level | Key finding | Caveat |
|---|---|---|---|---|
| **Phytase as feed enzyme** | Poultry/swine | **[ESTABLISHED]** | Releases phytate-P, cuts inorganic-P need & manure-P pollution | Veterinary/agricultural, not human |
| **SNF472 (IV IP6)** | ESRD/dialysis vascular calcification, calciphylaxis | **[EMERGING — Phase 3]** | Slowed coronary/aortic-valve calcification (Ph2); CALCIPHYX Ph3 | Industry-sponsored (Sanifit/Vifor) |
| **Myo-inositol — GDM prevention** | Pregnancy (mostly Italian RCTs) | **[EMERGING — low/very-low certainty]** | GDM roughly halved (RR ~0.42–0.53); dose 4 g/day | Cochrane rates low; single-country, small |
| **MI / MI+DCI — PCOS** | Reproductive-age women | **[EMERGING — low/very-low]** | Improves insulin/androgen markers; comparable to metformin, fewer GI effects | 2023 guideline: "may consider"; optimal 40:1 ratio is **[CONTESTED]**, industry-influenced |
| **MI — metabolic syndrome / NAFLD** | Adults (small RCTs) | **[EMERGING]** | ↓triglycerides, LDL, HOMA; improved liver markers | Small, few trials |
| **MI — IVF / oocyte quality** | Infertility (small RCTs) | **[EMERGING]** | ↑oocyte/MII/embryo counts | Signal concentrated in PCOS; no live-birth confirmation |
| **Inositol — depression/panic/OCD** | Psychiatric (1990s crossovers) | **[EMERGING — preliminary]** | 12–18 g/day positive in small trials | n≤21, old, unreplicated; SSRI-augmentation negative |
| **Myo-inositol — preterm RDS/ROP** | Preterm infants | **[REVERSED — trend to HARM]** | NICHD RCT (n=638) stopped early; mortality 18% vs 11%; no ROP benefit | Cochrane 2019: no benefit |
| **IP6 + inositol ("IP6 Gold")** | Cancer prevention/treatment | **[MARKETING OVERREACH]** | Large preclinical antitumor literature only | No large human RCTs; authors say Phase I/II "needs to be determined" |
| **Oral phytate — kidney stones** | Stone formers | **[CONTESTED]** | In-vitro crystallization inhibitor | Human study: "no hard evidence"; one positive pilot |

**Dosing/safety.** Doses studied 28 mg–18 g/day; common MI 1–4 g/day (PCOS/GDM typically 2 g BID,
split). Generally well tolerated; only mild GI effects above ~12 g/day; considered safe in
pregnancy. **Key interaction:** IP6/phytate chelates Ca/Fe/Mg/Zn (the antinutrient concern,
distinct from free inositol) and has antiplatelet activity (bleeding risk with anticoagulants).
["Inositol and antioxidant supplementation safety in pregnancy — Formoso 2019"]

**Conflicts of interest to keep in view:** much PCOS/GDM inositol literature comes from a few
Italian/supplement-affiliated groups; MI:DCI-ratio products are commercial; SNF472 research is run
by its developer; "IP6 cancer cure" content is largely retailer/blog material, not primary evidence.

---

## Open questions / research frontiers

1. **Does any intact IP6 cross the human gut?** Grases (yes) vs newer null methods (no) remain
   unreconciled — central to whether oral-IP6 supplements can do anything systemic.
2. **Is there a genuine mitochondrial inositol-phosphate pool**, or are all effects whole-cell/
   signaling-mediated? Currently the thinnest evidence area.
3. **Human relevance of the inositol-depletion theory of diabetic neuropathy** — rat-robust,
   human-inconsistent (the "inositol paradox").
4. **The MI:DCI ratio debate** — is 40:1 genuinely optimal, or an artifact of commercial framing?
5. **Why did preterm-RDS inositol reverse from benefit to harm**, and does timing/dose explain it?
6. **Can SNF472's calcification-inhibitor success generalize** beyond dialysis populations?
7. **IP4/IP3 and iron** — reconcile the human-absorption "safe below IP5" finding with Caco-2 data
   showing all IPs inhibit.

## Glossary

- **Myo-inositol** — the dominant biological inositol isomer; membrane PI backbone + osmolyte.
- **D-chiro-inositol (DCI)** — epimer involved in insulin signaling; tissue ratio to MI matters.
- **Phytic acid / phytate / IP6** — myo-inositol hexakisphosphate; plant seed P/mineral store and
  the dietary mineral chelator.
- **Phytase** — enzyme that dephosphorylates IP6 stepwise to lower IPs and inositol.
- **IP3 (Ins(1,4,5)P3)** — the *signaling* second messenger releasing ER Ca²⁺ (≠ the gut IP3
  intermediate of phytate breakdown).
- **PIP2 / PIP3** — membrane phosphoinositides; PLC and PI3K substrates.
- **IP7 / IP8** — inositol pyrophosphates; high-energy phosphate/energy sensors via SPX domains.
- **SMIT1/SMIT2/HMIT** — myo-inositol membrane transporters (Na⁺-, Na⁺-, H⁺-coupled).
- **MIPS/ISYNA1, IMPA1** — enzymes of de novo inositol synthesis from glucose-6-phosphate.
- **IPMK, ITPK1, IPPK/IPK1, IP6K, PPIP5K** — kinases that rebuild inositol up to IP6 and pyrophosphates.
- **INPHORS / SPX** — conserved inositol-pyrophosphate phosphate-sensing system.
- **IPG** — inositol phosphoglycan insulin second messenger.
- **Globoid** — phytate-rich mineral deposit in seed protein-storage vacuoles.
- **lpa** — low-phytic-acid crop mutant.

---

## References (by short title)

**Phytase, breakdown, absorption, minerals**
- Phytase — ScienceDirect Topics: https://www.sciencedirect.com/topics/agricultural-and-biological-sciences/phytase
- 3-Phytase — ScienceDirect Topics: https://www.sciencedirect.com/topics/agricultural-and-biological-sciences/3-phytase
- 4-Phytase — ScienceDirect Topics: https://www.sciencedirect.com/topics/agricultural-and-biological-sciences/4-phytase
- Phytate and phytase in fish nutrition — Wiley: https://onlinelibrary.wiley.com/doi/full/10.1111/j.1439-0396.2011.01169.x
- Phytate and phytase degradation in humans — PubMed 2541385: https://pubmed.ncbi.nlm.nih.gov/2541385/
- Diet shapes microbiota to degrade phytate (Markiewicz 2013) — Wiley: https://enviromicro-journals.onlinelibrary.wiley.com/doi/abs/10.1111/jam.12204
- Intrinsic phytase of wheat/barley/rye (temp, pH) — ScienceDirect: https://www.sciencedirect.com/science/article/abs/pii/S0377840112002003
- Soaking, germination, fermentation on phytic acid — WUR: https://edepot.wur.nl/52788
- Bioavailability during soaking/germination of sorghum — PMC3189212: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3189212/
- Enhancing Fe/Zn bioavailability in maize via phytate reduction — PMC11646714: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11646714/
- Microbial phytase: sources, production, role — ScienceDirect: https://www.sciencedirect.com/science/article/pii/S2666154323000662
- Inositol phosphates and iron absorption in humans — ScienceDirect: https://www.sciencedirect.com/science/article/pii/S000291652204045X
- Inositol phosphates inhibit Fe/Zn uptake in intestinal cells — PubMed 8145081: https://pubmed.ncbi.nlm.nih.gov/8145081/
- Formation and stability of phytate complexes — ScienceDirect: https://www.sciencedirect.com/science/article/abs/pii/S0010854507002111
- Phytic acid — ScienceDirect Topics: https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/phytic-acid
- Phytic acid — ChemicalBook: https://www.chemicalbook.com/ChemicalProductProperty_EN_CB4321770.htm
- Gibson 2010, Phytate/Fe/Zn/Ca review — SAGE: https://journals.sagepub.com/doi/10.1177/15648265100312S206
- Phytate × Ca/Zn molar ratios — Illinois Experts: https://experts.illinois.edu/en/publications/phytate-calciumzinc-molar-ratios-are-they-predictive-of-zinc-bioa
- Myo-inositol content of common foods — AJCN: https://ajcn.nutrition.org/article/S0002-9165(23)44053-1/fulltext
- Regulations of myo-inositol homeostasis — ScienceDirect: https://www.sciencedirect.com/science/article/pii/S2212492622000616
- SMIT2 mediates all apical MI uptake in rat small intestine — PubMed 17932225: https://pubmed.ncbi.nlm.nih.gov/17932225/
- Conundrum of IP6 (absorption debate) — PMC4680566: https://pmc.ncbi.nlm.nih.gov/articles/PMC4680566/
- Absorption/excretion of oral IP6 in humans (Grases 2001) — PubMed 11673644: https://pubmed.ncbi.nlm.nih.gov/11673644/
- IP6: From Seeds to Science — MDPI Biomolecules: https://www.mdpi.com/2218-273X/15/12/1652

**Cell signaling, transporters, kinases, mitochondria, structural cofactor**
- PIP2 signal pathway — News-Medical: https://www.news-medical.net/life-sciences/PIP2-signal-pathway.aspx
- Mammalian PI-PLC isozymes — MDPI: https://www.mdpi.com/1648-9144/61/6/1054
- PI3K signaling in normal/malignant B cells — PMC3414724: https://pmc.ncbi.nlm.nih.gov/articles/PMC3414724/
- PTEN tumor suppressor network — PMC3092286: https://pmc.ncbi.nlm.nih.gov/articles/PMC3092286/
- Inositol transport proteins — FEBS Lett: https://febs.onlinelibrary.wiley.com/doi/full/10.1016/j.febslet.2015.03.012
- SMIT1 modulates electrical activity via PI(4,5)P2 — PNAS: https://www.pnas.org/doi/10.1073/pnas.1606348113
- Role of myo-inositol in diabetic complications — Trends Endocrinol Metab: https://www.cell.com/trends/endocrinology-metabolism/abstract/1043-2760(91)90017-H
- Upregulation of MI transport compensates glucose inhibition — Diabetes 1993: https://diabetesjournals.org/diabetes/article/42/8/1119/8203/
- IP kinases: expanding biological significance — PMC9364425: https://pmc.ncbi.nlm.nih.gov/articles/PMC9364425/
- Structural insights into IP-kinase inhibitors — PMC12823050: https://pmc.ncbi.nlm.nih.gov/articles/PMC12823050/
- Metabolism and functions of inositol pyrophosphates — PMC7583957: https://pmc.ncbi.nlm.nih.gov/articles/PMC7583957/
- IP6K2 determines cellular energy dynamics via creatine kinase-B — PMC8017945: https://pmc.ncbi.nlm.nih.gov/articles/PMC8017945/
- Targeting inositol pyrophosphate enzymes in metabolic disease — PMC7144392: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7144392/
- IP6K3 regulates metabolism and lifespan — Sci Rep: https://www.nature.com/articles/srep32072
- IP6 bound in ADAR2 core, required for RNA editing — PMC1850959: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1850959/
- IP6 are assembly co-factors for HIV-1 — Nature 2018: https://www.nature.com/articles/s41586-018-0396-4
- Mature HIV-1 capsid stabilization by IP6 — Sci Adv: https://www.science.org/doi/10.1126/sciadv.abc6465

**Health systems / clinical**
- PCOS and Inositols — Frontiers 660381: https://www.frontiersin.org/journals/endocrinology/articles/10.3389/fendo.2021.660381/full
- Inositol for PCOS, 2023 guideline systematic review — JCEM/PMC11099481: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11099481/
- 2023 International Evidence-based PCOS Guideline recommendations — PubMed 37580314: https://pubmed.ncbi.nlm.nih.gov/37580314/
- Antenatal myo-inositol for preventing GDM — Cochrane CD011507.pub3: https://www.cochranelibrary.com/cdsr/doi/10.1002/14651858.CD011507.pub3/full
- Myo-inositol prevents GDM, meta-analysis — PMC10574514: https://pmc.ncbi.nlm.nih.gov/articles/PMC10574514/
- Myo-inositol GDM prevention meta-analysis — PubMed 35460931: https://pubmed.ncbi.nlm.nih.gov/35460931/
- Inositol on lipid profiles in metabolic diseases — PMC5968598: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5968598/
- Myo-inositol and grading of cerebral astrocytomas — AJNR: https://www.ajnr.org/content/21/9/1645
- Lithium and bipolar: inositol-depletion hypothesis revisited — Mol Psychiatry: https://www.nature.com/articles/4001618
- Lithium effects on myo-inositol in adolescent bipolar — PMC1761698: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1761698/
- Controlled trials of inositol in psychiatry — Eur Neuropsychopharmacol: https://www.sciencedirect.com/science/article/abs/pii/S0924977X97004094
- Inositol treatment of OCD — PubMed 8780431: https://pubmed.ncbi.nlm.nih.gov/8780431/
- Double-blind crossover trial of inositol for panic disorder — PubMed 7793450: https://pubmed.ncbi.nlm.nih.gov/7793450/
- IP6 modulates macrophages/cytokines — PMC8194914: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8194914/
- IP6 on TGF-β isoforms (intestinal epithelium) — PMC3891539: https://pmc.ncbi.nlm.nih.gov/articles/PMC3891539/
- Cancer inhibition by IP6 and inositol: lab to clinic — ScienceDirect: https://www.sciencedirect.com/science/article/pii/S002231662302535X
- Broad-spectrum anticancer activity of myo-inositol and IP6 — Wiley: https://onlinelibrary.wiley.com/doi/10.1155/2016/5616807
- IP6 suppresses prostate carcinoma via PI3K-Akt — PMC2819750: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2819750/
- IP6 blocks breast cancer proliferation via PKCδ — PubMed 15868430: https://pubmed.ncbi.nlm.nih.gov/15868430/
- SNF472 to attain therapeutic phytate levels — J Nephrol: https://academic.oup.com/joneph/article/31/2/287/8371420
- Relevance of phytate for CKD treatment — PMC11469791: https://pmc.ncbi.nlm.nih.gov/articles/PMC11469791/
- Phase 3 SNF472 calciphylaxis (CALCIPHYX) — ClinicalTrials NCT04195906: https://cdn.clinicaltrials.gov/large-docs/06/NCT04195906/Prot_000.pdf
- Phytate ingestion, urinary excretion, renal stone risk — J Renal Nutrition: https://www.sciencedirect.com/science/article/abs/pii/S1051227619304157
- Myo-inositol improves cardiometabolic factors in NAFLD — PMC9941177: https://pmc.ncbi.nlm.nih.gov/articles/PMC9941177/
- Myo-inositol in IVF/ICSI double-blind RCT — PMC9596930: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9596930/
- Myo-inositol on type 1 ROP in preterm infants (NICHD RCT) — PubMed 30357297: https://pubmed.ncbi.nlm.nih.gov/30357297/
- Inositol for preterm RDS — Cochrane CD000366: https://www.cochrane.org/CD000366/NEONATAL_inositol-preterm-infants-risk-or-having-respiratory-distress-syndrome
- RDS and inositol supplementation in preterm infants — PMC1778095: https://pmc.ncbi.nlm.nih.gov/articles/PMC1778095/
- Inositol & antioxidant supplementation safety in pregnancy (Formoso 2019) — Wiley: https://onlinelibrary.wiley.com/doi/10.1002/dmrr.3154

**Evolution, organisms, plants**
- Inositol derivatives: evolution and functions — Nat Rev Mol Cell Biol: https://www.nature.com/articles/nrm2334
- DIP osmolyte biosynthesis in hyperthermophiles — PNAS: https://www.pnas.org/content/104/11/4279
- Biosynthesis of DIP in hyperthermophilic archaea — J Bacteriol: https://journals.asm.org/doi/10.1128/jb.180.15.3785-3792.1998
- IP kinases in the eukaryote landscape — ScienceDirect: https://www.sciencedirect.com/science/article/pii/S2212492620300932
- Origin/evolution of IP3 3-kinases in plants and animals — BMC Genomics: https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-024-10257-7
- IP3 receptor evolutionary history (Capsaspora) — Mol Biol Evol: https://academic.oup.com/mbe/article/32/9/2236/1027733
- Kcs1 and Vip1 inositol pyrophosphate signaling in yeast — PMC10886477: https://pmc.ncbi.nlm.nih.gov/articles/PMC10886477/
- Dictyostelium inositol pyrophosphate metabolism — PMC3887064: https://pmc.ncbi.nlm.nih.gov/articles/PMC3887064/
- neo-inositol polyphosphates in Entamoeba — PubMed 10744695: https://pubmed.ncbi.nlm.nih.gov/10744695/
- Biosynthesis/functions of inositol pyrophosphates in plants — PMC4325660: https://pmc.ncbi.nlm.nih.gov/articles/PMC4325660/
- Seed biofortification and phytic acid reduction — PMC4844270: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4844270/
- Globoids and phytase: seed mineral storage/release — PMC7589363: https://pmc.ncbi.nlm.nih.gov/articles/PMC7589363/
- Phytate: impact on environment and human nutrition — JZUS B: https://link.springer.com/article/10.1631/jzus.B0710640
- Cereal purple acid phytase structure — PMC9073318: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9073318/
- InsP8 as intracellular phosphate signal in Arabidopsis — ScienceDirect: https://www.sciencedirect.com/science/article/pii/S1674205219302631
- Inositol pyrophosphates + SPX–PHR interaction — PMC7810988: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7810988/
- Jasmonate perception by IP-potentiated COI1–JAZ — Nature: https://www.nature.com/articles/nature09430
- IP6 regulates K⁺-inward conductance in guard cells — PNAS: https://www.pnas.org/doi/10.1073/pnas.140217497
- Galactinol and RFO synthesis in plants — PMC4549555: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4549555/
- OsMIOX and salinity stress — PMC10462604: https://pmc.ncbi.nlm.nih.gov/articles/PMC10462604/
- Low phytic acid crops: four decades of research — PMC7076677: https://ncbi.nlm.nih.gov/pmc/articles/PMC7076677
- Maize lpa2 = mutation in inositol phosphate kinase gene — PMC166827: https://pmc.ncbi.nlm.nih.gov/articles/PMC166827/
- MRP transporters and low-phytic-acid mutants in crops — PMC7481554: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7481554/

**Deficiency / animal models / vitamin status**
- Myo-inositol-responsive liver lipid accumulation in the rat — J Nutr: https://jn.nutrition.org/article/S0022-3166(23)27918-3/abstract
- Lactation-dependent fatty liver in myo-inositol-deficient rats — J Nutr: https://jn.nutrition.org/article/S0022-3166(23)27231-4/abstract
- Inositol deficiency in the gerbil: hepatic lipid/triglyceride secretion — ScienceDirect: https://www.sciencedirect.com/science/article/abs/pii/S0022316623275112
- Inositol deficiency in gerbils: intestinal lipodystrophy — ScienceDirect: https://www.sciencedirect.com/science/article/abs/pii/S0022316623267085
- Inositol requirement of the gerbil (sex difference) — J Nutr: https://jn.nutrition.org/article/S0022-3166(23)26542-6/abstract
- Polyol pathway and myo-inositol in diabetic neuropathy — Diabetes (ADA): https://diabetesjournals.org/diabetes/article/32/11/988/5679/
- Nerve glucose/fructose/sorbitol/myo-inositol in diabetic neuropathy — NEJM 1988: https://www.nejm.org/doi/full/10.1056/NEJM198809013190904
- Is there a vitamin B8? The truth about inositol — Biology Insights: https://biologyinsights.com/is-there-a-vitamin-b8-the-truth-about-inositol/
- Inositol — ScienceDirect Topics: https://www.sciencedirect.com/topics/agricultural-and-biological-sciences/inositol
- MSKCC Inositol Hexaphosphate monograph: https://www.mskcc.org/cancer-care/integrative-medicine/herbs/inositol-hexaphosphate

---

### Methodology & limitations

Findings were gathered by five parallel research agents (phytase/absorption; cell & mitochondrial
biology; health systems; evolution & plants; deficiency & treatments), each running multiple web
searches and extracting falsifiable, individually-cited claims. Contested claims that surfaced in
more than one agent (the diabetic inositol-depletion theory, intact-IP6 absorption, the preterm-RDS
reversal, PCOS/GDM low certainty) were cross-checked for agreement, which strengthens the grading
above. Several publisher domains (PMC, ScienceDirect, Nature) returned HTTP 403 to direct fetch in
this environment, so a subset of quantitative figures (transporter Km, molar ratios, plasma
concentrations, trial Ns) were drawn from search-result abstracts; **before publishing any specific
number in the newsletter, verify it against the primary PDF** at the cited URL. The 2026 ADAR1-cofactor
result is a preprint and not yet peer-reviewed.
