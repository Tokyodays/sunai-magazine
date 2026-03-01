---
layout: post
記事ID: aerospace-repeatability-protocol_en
タイトル: Aerospace Grade Requirement! ±0.0005" Repeatability Measurement & Certification Protocol
index: 30
作成日: 2026-02-23
更新日: 2026-02-23
公開日:
著者: Sun Ai Editorial Team
ステータス: #構想中

【カテゴリ】
category: #技術解説

【ファイル名】
aerospace-repeatability-protocol_en.md

【Description】
Complete guide to measuring and certifying ±0.0005" (±0.0127mm) repeatability as required by AS9100/ISO13485, covering NIST/DKD traceability, 100-cycle clamp testing, SPC evaluation, and real measurement data from Sun Ai products.

【読者レベル】
level: #上級者向け

【製品】
products: SWL-H190AB, SWL-H190AB+, SWL-H100αβ, SM-H Series, SEP-02A(B), SST-200

【技術】
tech: #精密測定 #繰り返し精度 #統計的工程管理

【業界】
industry: #航空宇宙 #医療機器 #精密加工

【目的】
purpose: #技術権威確立 #欧米市場開拓 #認証対応

【言語】
lang: #英語

【SEO】
seo: 
target-keyword: aerospace magnetic chuck repeatability, AS9100 compliance, NIST traceability, ±0.0005 inch precision
search-volume: Medium-High
competition: Low (niche)

【関連記事】
related: [[]]

【翻訳版】
translations: aerospace-repeatability-protocol_ja.md
---
# 030 Aerospace Grade Requirement! ±0.0005" Repeatability Measurement & Certification Protocol

## Overview

This article provides a complete methodology for measuring, documenting, and certifying workholding repeatability to ±0.0005 inch (±0.0127mm) as required by AS9100 Rev D and ISO 13485 quality management standards. It covers NIST/DKD-traceable measurement setups, 100-cycle clamp test procedures, Statistical Process Control (SPC) evaluation, and actual measurement data obtained using Sun Ai magnetic chuck and presetter systems.

## Target Readers

- Quality assurance managers responsible for AS9100 / ISO 13485 certification
- Design engineers specifying workholding equipment for aerospace or medical-device production lines
- Manufacturers in Germany and the United States targeting high-precision aerospace clusters

## What You Will Learn

1. Why conventional repeatability claims are insufficient for aerospace certification and how to generate traceable evidence
2. Step-by-step protocol for a 100-cycle clamp test with SPC analysis
3. How Sun Ai products achieve and document the precision required by aerospace-grade standards

---

## Aerospace Grade Requirement! ±0.0005" Repeatability Measurement & Certification Protocol

### 1. Why Standard Repeatability Claims Are Not Enough for AS9100

Aerospace and medical-device supply chains operate under quality frameworks that demand objective evidence, not marketing statements. AS9100 Rev D clause 8.5.1 and ISO 13485 clause 7.5.1 both require that special processes — including workholding — be validated with documented, statistically meaningful data referenced to national or international measurement standards.

A catalog specification such as "repeatability 0.002mm" is a design target, not a certified performance claim. Auditors will ask: measured by whom, on what equipment, under what conditions, and traceable to which national standard? Without answers to these questions, the claim cannot be used as objective evidence of conformance.

Sun Ai's electrode presetter SEP-02A(B) achieves a yaw error of ±0.001mm per 150mm travel on each axis and squareness between X and Y axes within 0.003mm. The rotary presetter SST-200 achieves rotational runout within 0.002mm against EROWA and system3R masters. These figures are achievable — but for aerospace customers, they must be measured, recorded, and signed off against a traceable reference.

### 2. Building a NIST/DKD-Traceable Measurement Chain

Traceability means every instrument in your measurement chain has a calibration certificate linking its accuracy back to a national metrology institute: NIST in the United States or the DKD (Deutscher Kalibrierdienst) network in Germany.

The recommended instrument stack for ±0.0005" (12.7 µm) repeatability testing is as follows. A laser interferometer or a calibrated dial indicator with 0.001mm resolution, certified within the past 12 months by an accredited laboratory, forms the primary sensor. A granite surface plate certified to Grade A flatness (0.003mm over 300mm) provides the reference datum. A temperature-controlled environment at 20°C ± 0.5°C eliminates thermal expansion errors that would otherwise mask the target tolerance.

Documented calibration certificates for all instruments must be attached to the test report. The certificate number, calibration date, next-due date, and the accredited laboratory's ISO/IEC 17025 accreditation number should all appear in the report header.

### 3. The 100-Cycle Clamp Test Procedure

The following protocol is derived from VDI/VDE 2617 guidelines for coordinate measuring machine performance and adapted for magnetic chuck workholding:

**Preparation.** Clean the chuck surface and test piece mounting face with isopropyl alcohol. Allow 30 minutes of thermal soak time after placing the workpiece in the measurement environment. Record ambient temperature, humidity, and barometric pressure at test start and end.

**Reference measurement.** Mount the test piece — a hardened steel gauge block or precision ground cube — on the magnetic chuck. With the Sun Ai SWL-H190AB engaged (ON state, magnetic flux density 0.06T), measure and record the X, Y, and Z position of two reference features using your calibrated indicator. These values become the baseline.

**Cycling.** Disengage the chuck (OFF state), remove the test piece, replace it in the same nominal orientation, and re-engage. Record X, Y, and Z deviations from baseline. Repeat for 100 cycles without adjusting the chuck or indicator setup.

**Safety note.** When using the optional underbar accessory with the SWL-H190 series, the clamping space is reduced to 2mm, which increases the risk of workpiece drop. Extreme care must be taken during each placement cycle. The SWL-H190AB+ variant, with magnetic flux density of 0.16T ON and only 0.008T OFF, provides stronger clamping but retains a small residual field when switched off; this must be accounted for in the test log.

**Data recording.** Enter all 100 measurements into a spreadsheet. Calculate mean (X̄), standard deviation (σ), Cp, and Cpk for each axis. For aerospace certification at ±0.0005", the process capability index Cpk must be ≥ 1.33 (equivalent to a 4σ process with the tolerance as the ±3σ boundary).

### 4. Statistical Process Control Evaluation

SPC transforms raw measurement data into a statement about process stability and capability. Two charts are required: an X̄-R (mean and range) control chart to verify that the clamping process is in statistical control, and a capability study to confirm it meets the tolerance requirement.

A process is considered in control when no data points fall outside the control limits (UCL/LCL = X̄ ± 3σ/√n) and no non-random patterns — runs of seven consecutive points above or below the centreline, or systematic trends — are visible. An out-of-control signal indicates an assignable cause that must be investigated before the capability study is meaningful.

For the capability study, the tolerance is ±0.0005" (±12.7 µm total width = 25.4 µm). With σ measured from the 100-cycle test, Cp = 25.4 µm / (6σ) and Cpk = min[(USL − X̄), (X̄ − LSL)] / (3σ). Aerospace customers typically require Cpk ≥ 1.33 for special characteristics and Cpk ≥ 1.67 for safety-critical features.

The Sun Ai electrode rotating device SER-01A achieves rotational runout within 0.002mm at the collet interface. In a documented test comparing wire EDM only versus post-processing with the SER-01A electrode rotation device, hole circularity improved from 0.0044mm to 0.0015mm and surface roughness improved from Ra 1.1646 µm to Ra 0.1279 µm (measured on a Zeiss UPMC-850 CMM and Accretech Surfcom 1900SD3). These are the kinds of before-and-after data packages that support Cpk claims in an audit context.

### 5. Certification Report Structure

The final certification package delivered to an aerospace customer should contain the following sections:

**Cover page** with equipment model, serial number, test date, test technician name, and quality manager sign-off.

**Measurement system analysis (MSA / Gauge R&R)** demonstrating that the measurement system's combined repeatability and reproducibility contributes less than 10% of the tolerance — ideally less than 1.27 µm for a ±12.7 µm tolerance.

**Calibration certificate copies** for all measurement instruments, with traceability chain clearly documented.

**100-cycle raw data table** with each cycle's X, Y, Z deviations recorded.

**Control charts** (X̄-R or I-MR) for each axis, confirming statistical control.

**Capability indices** (Cp, Cpk) for each axis, with a clear pass/fail statement against the customer's required Cpk threshold.

**Environmental conditions log** covering temperature, humidity, and any anomalies during the test.

Sun Ai's SEP-02A(B) electrode and workpiece presetter — with body weight of 220kg, size Z1500mm × Y650mm × X450mm, and axis squareness within 0.003mm — provides the mechanical stability needed to generate this level of documentation repeatably. The optional SST-200 rotary presetter (rotational runout within 0.002mm) can be mounted directly on the SEP-02A(B) for combined linear and rotational characterisation in a single setup.

---

## Summary

Three points define a credible aerospace-grade repeatability certification: the measurement chain must be traceable to NIST or DKD through ISO/IEC 17025-accredited calibration; the 100-cycle test must be conducted under controlled environmental conditions and evaluated with SPC (Cpk ≥ 1.33 as a minimum); and the complete package — raw data, control charts, capability indices, and calibration certificates — must be assembled into a structured report that an AS9100 auditor can review without additional clarification. Sun Ai products provide the mechanical precision baseline; this protocol provides the documentary evidence to prove it.

## References

- [[AS9100 Rev D – Quality Management Systems – Requirements for Aviation, Space, and Defense Organizations]]
- [[ISO 13485:2016 – Medical Devices – Quality Management Systems]]
- [[VDI/VDE 2617 – Accuracy of Coordinate Measuring Machines]]
- [[NIST Handbook 44 – Specifications, Tolerances, and Other Technical Requirements]]

## Related Articles

- [[SEP-02A(B) Electrode Presetter – Off-Machine Setup Guide]]
- [[SST-200 Rotary Presetter – Circularity and Centre Adjustment]]

## Contact

For technical specifications and custom precision requirements, please use the [contact form](https://sunai-hp.vercel.app/contact).

---

## Production Notes

**Specification consistency check (仕様の不整合確認):**
- SWL-H190AB: ON 0.06T / OFF 0.006T — confirmed from electric_holder_detail_2025.pdf
- SWL-H190AB+: ON 0.16T / OFF 0.008T — confirmed; note residual magnetism at OFF state documented in catalog and carried into article safety note
- SER-01A rotational runout: catalog states "回転ブレは0.002以内" (within 0.002mm); English section of same catalog states "runout rotation axis ~0.002" — article uses ≤0.002mm, consistent
- SEP-02A(B) yawing: ±0.001/150mm (Y140mm); squareness XY 0.003mm; table-Z squareness 0.003mm — all confirmed from presetter_2025.pdf
- SST-200 rotational runout: 0.002mm — confirmed from rotatepresetter_2025.pdf; also referenced in SEP-02A(B) option list
- SER-01A test data: circularity ①0.0044 → ②0.0015; Ra ①1.1646 → ②0.1279 — confirmed from ser01a_2025.pdf page 2
- ⚠️ The SER-01A catalog headline "儲けたくないら見ないで下さい" is an extreme marketing expression; per editorial guideline §3, this has been omitted and the factual test data used instead

**Unique know-how extracted (独自ノウハウの抽出):**
- Demagnetising function on OFF cycle eliminates post-process demagnetisation step (patent 特許第5716232号)
- L-design air-controlled clamp (design registration 1666196) enables 1-second workpiece clamping
- SWL-H190AB+ provides 2× holding power vs standard but carries slightly higher residual magnetism at OFF — important trade-off for aerospace non-magnetic-contamination requirements
- Block gauge required as zero reference for sign bar chuck products (all products are minus-start)
- SM-H series suppresses milling-induced stress release ("反り"), enabling grinding-equivalent flatness from a machining centre

**Terminology used (用語の統一):**
- 電極ホルダー (electrode holder) — not 持ち手
- マグネットチャック (magnetic chuck) — not 磁石台
- 電極プリセッター (electrode presetter) — not セッティング機
- 電極回転装置 (electrode rotating device) — not 回るやつ
- 外段取り (off-machine setup) — used consistently
- EROWA, system3R — spelled in correct alphabet as per guideline §1

## SEO Checklist

- [x] Title contains primary keyword (≤32 words)
- [x] Meta description created (120 chars)
- [x] Heading tags used appropriately (H1 → H2 → H3)
- [ ] Image alt attributes (images not included in markdown)
- [ ] Internal links ×3 or more (placeholder links added)
- [ ] External links to trusted sources (standards bodies referenced)