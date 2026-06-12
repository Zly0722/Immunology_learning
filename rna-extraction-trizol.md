<div align="center">

# Total RNA Extraction — TRIzol Method

**Standard Operating Procedure**

`Molecular Biology` · `RNA` · `Acid Phenol–Chloroform Method`

</div>

---

> [!NOTE]
> **Scope**　Extraction of total RNA from cultured cells, animal tissues, and similar samples.
> **On the numbers**　All volumes, speeds, and times below are **typical reference values**. Reagents and centrifuges vary by brand — always follow your product's manual for actual work.

---

## Contents

1. [Before You Start](#before-you-start)
2. [Step 1 — Lysis](#step-1--lysis)
3. [Step 2 — Chloroform & Phase Separation](#step-2--chloroform--phase-separation)
4. [Step 3 — Collect the Aqueous Phase](#step-3--collect-the-aqueous-phase)
5. [Step 4 — Isopropanol Precipitation](#step-4--isopropanol-precipitation)
6. [Step 5 — 75% Ethanol Wash](#step-5--75-ethanol-wash)
7. [Step 6 — Drying & Resuspension](#step-6--drying--resuspension)
8. [Step 7 — DNase I Digestion (Optional)](#step-7--dnase-i-digestion-optional)
9. [Quality Control](#quality-control)
10. [Method Summary](#method-summary)

---

## Before You Start

> **An RNase-free environment is the single most important factor for success.**

| Aspect | Practice |
| :--- | :--- |
| Consumables & reagents | Certified RNase-free tips and tubes; DEPC-treated water |
| Personal protection | Gloves throughout, changed often; wipe bench and pipettes with RNase-removal solution |
| Safety | Phenol and chloroform are toxic and corrosive — work in a fume hood |
| Temperature | Keep precipitation and centrifugation steps at `4°C` where possible |

> [!IMPORTANT]
> **Principle**　RNases are everywhere — skin, sweat, dust — and are extremely stable, resisting routine sterilization. They are the main cause of RNA degradation. **Preventing contamination beats trying to fix it afterward.**
>
> **Notes**　Even with gloves, do not touch surfaces that will enter the reaction. Keep RNA samples on ice or at `-80°C` as soon as possible.

---

## Step 1 — Lysis

> Disrupt membranes to release contents while inactivating RNases.

```text
Adherent cells ── ~1 mL TRIzol per 10 cm², pipette repeatedly
Tissue         ── 1 mL TRIzol per 50–100 mg, homogenize thoroughly
                    ↓
              Stand 5 min at room temperature
```

> [!TIP]
> **Principle**　TRIzol contains **phenol** and **guanidinium thiocyanate**. The latter is a strong chaotropic agent and protein denaturant that rapidly inactivates RNases as the cell lyses — protecting RNA the moment it is exposed. The room-temperature incubation lets nucleoprotein complexes fully dissociate, releasing intact RNA.
>
> **Notes**
> - Don't overload the starting material; incomplete lysis lowers yield and purity.
> - After adding TRIzol, samples can be stored long-term at `-80°C`.

---

## Step 2 — Chloroform & Phase Separation

> Three layers form; RNA partitions into the aqueous phase.

```text
Per 1 mL TRIzol  +  0.2 mL chloroform
       ↓  shake vigorously 15 s, stand 2–3 min at RT
       ↓  4°C, 12,000 ×g, centrifuge 15 min
   ┌──────────────────────────────────┐
   │  Upper   colorless aqueous → RNA  │
   │  Middle  white interphase  → DNA  │
   │  Lower   pink phenol       → protein │
   └──────────────────────────────────┘
```

| Layer | Appearance | Contents |
| :---: | :--- | :--- |
| **Upper** | Colorless aqueous | **RNA** |
| Middle | White interphase | DNA |
| Lower | Pink phenol phase | Protein, lipids |

> [!IMPORTANT]
> **Principle**　The key is TRIzol's **acidic environment (pH ≈ 4–5)**. Under acidic conditions DNA's phosphate backbone is partially protonated and becomes more hydrophobic, partitioning into the organic phase and interphase; RNA stays hydrophilic and remains in the aqueous phase. This is exactly why the *acidic* phenol–chloroform method separates RNA specifically — at neutral/alkaline pH, DNA would instead stay in the aqueous phase (the condition used for DNA extraction).
>
> **Notes**　Shake thoroughly; after centrifugation, handle gently so the three layers don't remix.

---

## Step 3 — Collect the Aqueous Phase

> Take only the target; avoid contamination.

- Carefully draw off the upper colorless aqueous phase into a fresh RNase-free tube.
- It makes up about half the total volume — collecting roughly `50%` is enough.

> [!WARNING]
> **Never touch the white interphase.** Contact carries genomic DNA into your sample, contaminating it and compromising downstream quantification and amplification. **Take less rather than risk the layer.**

---

## Step 4 — Isopropanol Precipitation

> RNA loses solubility and precipitates out.

```text
Per 1 mL starting TRIzol  +  0.5 mL isopropanol
       ↓  mix by inversion, stand 10 min at RT
       ↓  4°C, 12,000 ×g, centrifuge 10 min
   →  RNA pellets at the bottom (white, gel-like)
```

> [!TIP]
> **Principle**　Isopropanol lowers the solution's dielectric constant and strips RNA's hydration shell; cations neutralize RNA's negative charge, causing it to aggregate and precipitate.
>
> **Notes**　For low starting amounts, extend the incubation or chill at `-20°C`, and add **glycogen** as a co-precipitant carrier to boost recovery. When discarding the supernatant, don't aspirate the pellet.

---

## Step 5 — 75% Ethanol Wash

> Rinse away salts and impurities.

- Discard supernatant; add ~1 mL `75%` ethanol (made with RNase-free water) per 1 mL starting TRIzol.
- Wash gently by inversion; centrifuge at `4°C`, ~`7,500 ×g` for 5 min. Repeat once if needed.

> [!IMPORTANT]
> **Principle**　75% ethanol dissolves and removes residual salts and trace impurities, yet is concentrated enough not to redissolve and lose the RNA.
>
> **Notes**　Don't use ethanol that's too dilute, or RNA will partially dissolve and yield drops. This step is critical for removing guanidinium salts — residue lowers `A₂₆₀/A₂₃₀` and inhibits downstream enzymatic reactions.

---

## Step 6 — Drying & Resuspension

> Rehydrate to obtain the finished product.

- Remove all ethanol and **air-dry the pellet briefly**, 5–10 min.
- Dissolve in an appropriate volume of RNase-free water or TE buffer; warm to `55–60°C` for a few minutes if needed.

> [!CAUTION]
> **Do not over-dry!** A fully dried RNA pellet becomes extremely difficult to redissolve.
>
> **Notes**　Choose the resuspension volume based on target concentration. Place on ice immediately after dissolving, store long-term at `-80°C`, and avoid repeated freeze–thaw cycles.

---

## Step 7 — DNase I Digestion (Optional)

> Remove residual DNA when high purity is required.

Recommended for purity-sensitive applications such as qPCR and RNA-seq.

- Add DNase I and its buffer per the kit instructions; incubate to digest, then inactivate or re-purify.

> [!TIP]
> **Principle**　Although TRIzol greatly reduces DNA, trace genomic DNA may remain in the aqueous phase. DNase I specifically degrades DNA without affecting RNA.
>
> **Notes**　After treatment, fully inactivate or remove the enzyme and its buffer, or downstream reactions will be affected. Choose the inactivation method (EDTA + heat vs. column purification) based on the downstream use, and avoid heat-induced RNA degradation.

---

## Quality Control

> After extraction, assess **purity** and **integrity**.

| Metric | Method | Acceptable reference |
| :--- | :--- | :--- |
| Concentration & purity | Spectrophotometer (e.g. NanoDrop) | `A₂₆₀/A₂₈₀ ≈ 1.8–2.1`; `A₂₆₀/A₂₃₀ ≥ 1.8` |
| Integrity | Agarose gel / Bioanalyzer | Sharp 28S & 18S rRNA bands, ratio ≈ `2:1`; higher RIN is better |

**Troubleshooting**

| Symptom | Likely cause | Action |
| :--- | :--- | :--- |
| Low `A₂₆₀/A₂₈₀` | Protein contamination | Touched the interphase — be more careful next time |
| Low `A₂₆₀/A₂₃₀` | Residual phenol / guanidinium | Strengthen the ethanol wash |
| Smeared / degraded bands | RNase contamination or warming | Check RNase-free conditions; keep everything cold |

---

## Method Summary

> **The logical thread**

```text
Lyse & inactivate RNase → chloroform phase split → collect aqueous phase
   → isopropanol precipitation → ethanol salt wash → resuspend
   → (optional) DNase removal of DNA → QC
```

> **Two core principles**
>
> ① **Guanidinium thiocyanate inactivates RNases throughout**, protecting RNA from degradation.
> ② **Acidic pH** keeps RNA in the aqueous phase while DNA moves to the organic phase, achieving specific separation.

<div align="center">

---

*Total RNA Extraction · TRIzol Method*

</div>
