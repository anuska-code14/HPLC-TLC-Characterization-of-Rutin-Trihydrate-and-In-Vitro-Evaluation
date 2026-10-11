# HPLC/TLC Characterization of Rutin Trihydrate and In Vitro Evaluation of its Antioxidant, Anti-inflammatory and Antimicrobial Activity

![Domain](https://img.shields.io/badge/domain-pharmaceutical%20analysis-blue)
![Techniques](https://img.shields.io/badge/techniques-HPLC%20%7C%20TLC%20%7C%20UV--Vis-informational)
![Type](https://img.shields.io/badge/type-in%20vitro%20study-green)
![Status](https://img.shields.io/badge/status-completed-brightgreen)

Summer research internship project, **Department of Pharmaceutical Technology, Jadavpur University, Kolkata** (5 June – 5 August 2024).
**Author:** Anuska Sarkar | **Supervisor:** Prof. Sanmoy Karmakar

---

## Table of contents

1. [Overview](#overview)
2. [Background](#background)
3. [Objectives](#objectives)
4. [Methods](#methods)
   - [TLC](#1-thin-layer-chromatography-tlc)
   - [HPLC](#2-hplc-purity-analysis)
   - [Serial dilution](#3-serial-dilution-and-uv-vis-absorbance)
   - [Antioxidant (DPPH)](#4-antioxidant-activity-dpph-assay)
   - [Anti-inflammatory (BSA denaturation)](#5-anti-inflammatory-activity-bsa-denaturation-assay)
   - [Antimicrobial (MIC/MBC)](#6-antimicrobial-activity-mic-and-mbc)
5. [Results](#results)
6. [Discussion](#discussion)
7. [Limitations](#limitations)
8. [Conclusion](#conclusion)
9. [Instruments and techniques used](#instruments-and-techniques-used)
10. [Good Laboratory Practice](#good-laboratory-practice)
11. [Suggested repository structure](#suggested-repository-structure)
12. [References](#references)

---

## Overview

This project characterizes **rutin trihydrate**, a flavonoid glycoside of pharmaceutical interest, for identity and purity using **TLC and RP-HPLC**, and then evaluates three bioactivities *in vitro*:

| Activity | Assay | Standard / comparator |
|---|---|---|
| Antioxidant | DPPH radical scavenging (517 nm) | Ascorbic acid |
| Anti-inflammatory | BSA heat-denaturation inhibition (660 nm) | Diclofenac |
| Antimicrobial | Broth microdilution, MIC and MBC | *E. coli* (Gram -ve), *B. subtilis* (Gram +ve) |

### Key findings at a glance

- TLC: **Rf = 0.4** for rutin (silica, ethyl acetate:formic acid:acetic acid:water 100:11:11:27).
- HPLC (C18, 254 nm): the rutin-rich fraction was estimated at **about 60% purity**.
- DPPH: **74.5%** inhibition at 62.5 µg/mL for rutin vs **78.5%** for ascorbic acid.
- BSA denaturation: **78.2%** inhibition at 500 µg/mL for rutin vs **67.5%** for diclofenac; rutin was higher than diclofenac at every concentration tested.
- Antimicrobial: bacteriostatic against *E. coli* (**MIC 500 µg/mL**, **MBC 1000 µg/mL**); no clear dose-dependent inhibition of *B. subtilis*.

---

## Background

**Flavonoids** are polyphenolic plant compounds built on a 15-carbon skeleton (two benzene rings A and B joined through a heterocyclic pyran ring C). They occur as free aglycones or bound to sugars as glycosides.

**Rutin trihydrate** (rutoside, quercetin-3-O-rutinoside) is the glycoside of the flavonol **quercetin** and the disaccharide **rutinose**. It is found in *Rheum* species, asparagus and buckwheat (Tartary buckwheat seeds contain roughly 0.8–1.7% dry weight). It is reported to have antioxidant, anti-inflammatory, antimicrobial and capillary-strengthening effects, and a hydroxyethyl-rutoside mixture is marketed for chronic venous insufficiency.

Two structural facts drive the assays in this project:

- **Antioxidant capacity depends on free hydroxyl groups.** The ortho-3′,4′-dihydroxy (catechol) arrangement on the B ring is the main hydrogen donor that quenches free radicals. Blocking phenolic OH groups lowers activity.
- **Bioavailability is limited.** Absorption of rutin and quercetin from the gut is slow and unreliable, which is why *in vitro* activity does not automatically predict *in vivo* benefit.

---

## Objectives

1. Confirm the identity and estimate the purity of rutin trihydrate by TLC and HPLC.
2. Determine solubility behaviour and prepare working stock solutions by serial dilution.
3. Quantify antioxidant activity (DPPH) against ascorbic acid.
4. Quantify anti-inflammatory activity (BSA denaturation) against diclofenac.
5. Determine antimicrobial activity (MIC/MBC) against *E. coli* and *B. subtilis*.
6. Analyse and discuss all results under GLP-compliant practice.

---

## Methods

### 1. Thin-layer chromatography (TLC)

**Principle.** Components partition between a polar stationary phase (silica) and a mobile phase. More polar compounds interact more strongly with silica and travel less, giving a lower Rf:

```
Rf = distance travelled by solute / distance travelled by solvent front
```

**Procedure**

1. Mobile phase: ethyl acetate : formic acid : glacial acetic acid : water = **100 : 11 : 11 : 27**.
2. Poured into a TLC chamber with a tissue strip to saturate the chamber with vapour (this gives an even solvent front and reduces tailing).
3. Rutin dissolved in methanol and spotted by capillary onto a silica-coated alumina plate.
4. Developed until about 90% of the plate was wetted; solvent front marked.
5. Visualized in a TLC-UV viewing cabinet and, for confirmation, by blowing **iodine** onto the plate (brown spot).
6. Rf calculated.

**Result:** solute front 1.8 / solvent front 4.5 = **Rf 0.4**.

### 2. HPLC purity analysis

| Parameter | Setting |
|---|---|
| Mode | Reversed-phase (RP-HPLC) |
| Stationary phase | C18 (octadecylsilane) column |
| Mobile phase | Acetonitrile (A) / water (B), filtered through a 0.2 µm membrane |
| Injection | 40 µL via Hamilton syringe (Load/Inject valve) |
| Pump | Reciprocating |
| Detector | Photodiode array (PDA) / UV-Vis |
| Detection wavelength | **254 nm** (absorption maximum selected from the PDA spectrum) |
| Sample | Rutin trihydrate, 1 mg/mL |

**Protocol:** purge lines to remove air bubbles (column bypassed, 8 mL/min) → wash column with mobile phase → set method in the LC software → inject → detect.

**Why PDA:** a fixed-wavelength detector identifies a peak only by retention time, so a small retention shift can cause misidentification. A diode-array detector records the whole spectrum, so identity can be confirmed by spectral comparison.

**Result:** the rutin-rich fraction was calculated at **about 60% purity** from the chromatogram.

### 3. Serial dilution and UV-Vis absorbance

1. 1 mg/mL stock of rutin trihydrate in methanol (methanol dissolved rutin better than water).
2. First dilution D1 = 1000 µg/mL; subsequent **1:1 serial dilutions** (1 mL + 1 mL methanol).
3. 200 µL of each dilution into a 96-well plate; absorbance read at **230 nm**.

### 4. Antioxidant activity (DPPH assay)

**Principle.** DPPH is a stable purple radical absorbing at 517 nm. An antioxidant donates a hydrogen atom, converting DPPH to the pale yellow DPPH-H, so absorbance falls in proportion to scavenging.

**Procedure**

1. Rutin and ascorbic acid (standard) each prepared at 3 mg/mL in methanol and serially diluted down to 7.81 µg/mL.
2. Fresh 0.002% w/v DPPH solution.
3. Sample mixture: DPPH : methanol : working solution = 1 : 1 : 1. Control: methanol + DPPH (2 : 1).
4. Incubated **in the dark for 30 min** (DPPH is light-sensitive), then read at **517 nm**.
5. `% inhibition = (A_control − A_sample) / A_control × 100`

### 5. Anti-inflammatory activity (BSA denaturation assay)

**Principle.** Heat-induced denaturation of albumin is used as an *in vitro* model for protein denaturation, which is associated with inflammation. Compounds that stabilize the protein against heat are scored as anti-inflammatory; turbidity from denatured protein is read at 660 nm.

**Procedure**

1. PBS prepared from sodium and potassium hydrogen phosphate, **pH 6.3**.
2. Rutin and diclofenac (standard) serially diluted in PBS (1000 → 7.89 µg/mL).
3. 1% BSA in PBS.
4. 96-well plate: **225 µL BSA + 25 µL** sample (or standard).
5. Incubated at 37 °C (4% CO₂), then heated at **70 °C for 5 min** in a water bath; cooled.
6. Absorbance read at **660 nm**.
7. `% inhibition = (Control − Sample) / Control × 100`

### 6. Antimicrobial activity (MIC and MBC)

**Organisms:** *Escherichia coli* (Gram-negative) and *Bacillus subtilis* (Gram-positive).

**Preparation**

- **Test solution:** 3 mg/mL rutin stock in methanol, serially diluted in water.
- **Medium:** Luria-Bertani (LB) broth: 10 g tryptone, 5 g yeast extract, 10 g NaCl per litre; pH adjusted to about 7.0; autoclaved at 121 °C, 15 psi, 15–20 min.
- **Slants:** agar slants prepared, sterilized and stored for culture maintenance.
- **Turbidity standard:** 0.5 McFarland standard (0.05 mL of 1% BaCl₂ + 9.95 mL of 1% H₂SO₄), used to standardize the inoculum.
- **Inoculation:** aseptic technique (flamed loop, labelled slants, 37 °C incubation); inoculum diluted in sterile saline and matched to 0.5 McFarland.

**Broth microdilution:** two-fold dilutions in a 96-well plate (3.9–1000 µg/mL), each well receiving 100 µL of inoculum (about 10⁶ CFU/mL). Absorbance read at 0 h and after 24 h at 37 °C.

- **MIC:** lowest concentration with no observable growth (no rise in turbidity).
- **MBC:** lowest concentration at which no microbe survives when plated on LB agar (24 h, 37 °C).

---

## Results

### TLC

| Parameter | Value |
|---|---|
| Solute front | 1.8 cm |
| Solvent front | 4.5 cm |
| **Rf** | **0.4** |

### Serial dilution (A230)

| Conc. (µg/mL) | 500 | 250 | 125 | 62.5 | 31.25 |
|---|---|---|---|---|---|
| OD at 230 nm | 1.174 | 1.140 | 0.953 | 0.660 | 0.300 |

Absorbance decreases with concentration, consistent with Beer-Lambert behaviour. The 500 and 250 µg/mL readings are close, which suggests the upper end of the range is approaching the detector's linear limit.

### DPPH radical scavenging (% inhibition)

| Conc. (µg/mL) | Rutin trihydrate | Ascorbic acid |
|---|---|---|
| 3.95 | 17.34 | 19.87 |
| 7.9 | 36.87 | 37.98 |
| 15.625 | 42.46 | 52.00 |
| 31.25 | 58.00 | 74.80 |
| 62.5 | 74.50 | 78.50 |

Interpolated half-maximal concentration (linear interpolation between the two points that bracket 50%; **an estimate, not a fitted IC50**): rutin about **23 µg/mL**, ascorbic acid about **14.5 µg/mL**.

### BSA denaturation inhibition (% inhibition)

| Conc. (µg/mL) | Rutin trihydrate | Diclofenac |
|---|---|---|
| 15.625 | 17.43 | 9.87 |
| 31.25 | 28.47 | 19.87 |
| 62.5 | 32.43 | 23.45 |
| 125 | 48.00 | 34.45 |
| 250 | 65.47 | 47.46 |
| 500 | 78.20 | 67.50 |

Interpolated 50% inhibition (estimate): rutin about **139 µg/mL**, diclofenac about **282 µg/mL**.

### Antimicrobial activity: *E. coli*

| Rutin (µg/mL) | 1000 | 500 | 250 | 125 | 62.5 | 31.25 | 15.625 | 7.81 | 3.9 |
|---|---|---|---|---|---|---|---|---|---|
| 0 h | 0.075 | 0.067 | 0.093 | 0.091 | 0.077 | 0.075 | 0.074 | 0.074 | 0.073 |
| 24 h | 0.180 | 0.192 | 0.675 | 0.669 | 0.632 | 0.612 | 0.613 | 0.616 | 0.615 |

Growth (the rise in absorbance over 24 h) was suppressed at 500 and 1000 µg/mL and not at 250 µg/mL and below.
**MIC = 500 µg/mL (bacteriostatic); MBC = 2 × MIC = 1000 µg/mL.**

### Antimicrobial activity: *B. subtilis*

| Rutin (µg/mL) | 1000 | 500 | 250 | 125 | 62.5 | 31.25 | 15.625 | 7.81 | 3.9 |
|---|---|---|---|---|---|---|---|---|---|
| 0 h | 0.101 | 0.082 | 0.093 | 0.078 | 0.076 | 0.078 | 0.077 | 0.069 | 0.068 |
| 24 h | 0.637 | 0.456 | 0.384 | 0.376 | 0.437 | 0.340 | 0.288 | 0.596 | 0.342 |

Readings are non-monotonic: growth was highest at the highest rutin concentration and does not fall consistently with increasing dose. A bacteriostatic or bactericidal agent should show a dose-dependent decrease, so **no MIC could be assigned for *B. subtilis***.

---

## Discussion

**Identity and purity.** The Rf of 0.4 in a polar, acidic mobile phase is consistent with a polar glycoside: the rutinose sugar adds hydroxyl groups that bind strongly to silica, so rutin travels less far than its aglycone quercetin would. The HPLC estimate of about 60% shows the material was a rutin-rich fraction, not a purified standard, so activity values below are for that fraction.

**Antioxidant activity.** Rutin approached ascorbic acid at the top concentration (74.5% vs 78.5%) but was weaker at mid-range concentrations (58% vs 74.8% at 31.25 µg/mL). This is plausible mechanistically: the catechol B ring is available to donate hydrogen, but the glycosylated 3-OH is blocked by rutinose, which generally makes rutin a somewhat weaker scavenger than free quercetin.

**Anti-inflammatory activity.** Rutin out-performed diclofenac at every tested concentration in the BSA assay. This should be read cautiously: BSA denaturation is a screening model for protein stabilization, not a measure of cyclooxygenase inhibition, which is diclofenac's clinical mechanism. It supports further testing but does not establish that rutin is a better anti-inflammatory.

**Antimicrobial activity.** Growth suppression in *E. coli* occurred at 500–1000 µg/mL, which is a high concentration compared with clinical antibiotics, so rutin is better regarded as a weak antimicrobial or adjunct. Phenolics are reported to disrupt membranes, inactivate enzymes and bind nucleophilic residues in proteins. The *B. subtilis* data were inconclusive and should be repeated.

---

## Limitations

- **Replicates and statistics:** the report states experiments were repeated, but the number of replicates is not recorded in the data, and no error bars, standard deviations or p-values are reported. Differences between rutin and the standards should therefore be treated as indicative, not statistically established.
- **Purity:** the test material was about 60% pure, so potency per mole of rutin is not isolated from co-extracted compounds.
- **Wavelengths:** HPLC detection was at 254 nm, whereas the serial-dilution absorbance was read at 230 nm; these are separate measurements.
- **MBC:** the 24 h absorbance at 1000 µg/mL is close to that at 500 µg/mL, and plate-count data supporting the MBC are not tabulated.
- **Methanol vehicle:** stock solutions were prepared in methanol; a vehicle-only control is the appropriate way to rule out solvent effects in the biological assays.
- ***B. subtilis* data:** non-monotonic; no MIC could be assigned.
- ***In vitro* only:** no cell-based or animal data; rutin's low oral bioavailability limits extrapolation.

---

## Conclusion

Rutin trihydrate was characterized by TLC (Rf 0.4) and HPLC (about 60% purity of the rutin-rich fraction) and showed dose-dependent antioxidant and anti-inflammatory activity *in vitro*, comparable to or exceeding the chosen standards at the highest concentrations tested, plus bacteriostatic activity against *E. coli* at 500 µg/mL. The findings support further work: purification to a higher-purity standard, replicate-based statistics (IC50 by curve fitting), and *in vivo* and bioavailability studies.

---

## Instruments and techniques used

HPLC with PDA detector, TLC with UV viewing cabinet, UV-Vis spectrophotometer and 96-well plate reader, Milli-Q water system, double distillation unit, pH meter, water bath, homogenizer/ultrasonicator, cooling microcentrifuge, Soxhlet extractor, vortex mixer, micropipettes, autoclave. Techniques: serial dilution, buffer and media preparation, McFarland standardization, aseptic culture handling, broth microdilution.

## Good Laboratory Practice

All work followed GLP principles (OECD): PPE at all times, calibrated and maintained equipment, documented SOPs, correct reagent labelling and record keeping, aseptic technique, and repetition of experiments to reduce human error.

---

## Suggested repository structure

```
rutin-characterization/
├── README.md
├── data/
│   ├── serial_dilution.csv
│   ├── dpph.csv
│   ├── bsa_denaturation.csv
│   ├── mic_ecoli.csv
│   └── mic_bsubtilis.csv
├── figures/
│   ├── tlc_plate.png
│   ├── hplc_chromatogram.png
│   ├── dpph_curve.png
│   ├── bsa_curve.png
│   └── antimicrobial_growth.png
├── report/
│   └── INTERNSHIP_REPORT_ANUSKA.pdf
└── LICENSE
```

## References

1. Determination of the antioxidant activity of rutin and its contribution to the antioxidant capacity of buckwheat. *Polish Journal of Food and Nutrition Sciences.* https://journal.pan.olsztyn.pl/
2. Wagner H., Bladt S. *Plant Drug Analysis: A Thin Layer Chromatography Atlas.* Springer.
3. PubMed Central article PMC4177624. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4177624/
4. OECD Principles of Good Laboratory Practice.

---

*Internship project report, Jadavpur University, 2024. For academic and portfolio purposes.*
