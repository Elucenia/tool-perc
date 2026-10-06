<!-- ELUCENIA technical documentation · perc · en · no clinical/professional/rights approval -->

# PERC criteria

[conditions, sources and permissions](https://elucenia.org/en/tools/perc)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Age ≥ 50 years

`idade`

### Heart rate ≥ 100 bpm

`fc`

### O₂ saturation \< 95% on room air

`sat`

### Unilateral lower-limb swelling

`edema`

### Hemoptysis

`hemoptise`

### Surgery or trauma requiring hospitalization in the last 4 weeks

`cirurgia`

### Previous DVT or PE

`tev`

### Estrogen use (contraception or hormone replacement)

`hormonio`

## Method edition

PERC/Kline 2004: 8 negative criteria with low prior suspicion; no automatic decision

## Documented formula

Eight yes/no questions. PERC is negative only if all answers are “no”. Use only when the clinician already considers low probability clinically (gestalt \< 15%).

## Limits and population

PERC 2004 was derived in emergency patients evaluated for pulmonary embolism and tested in low- and very-low-risk groups. All eight criteria must be simultaneously negative, including age \< 50 years, pulse \< 100/min and saturation \> 94% in the original study. The rule does not establish zero risk, and its applicability depends on prior population selection; temporal definitions and inclusion criteria must be checked in the version used.

## References

- [Kline JA et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism. J Thromb Haemost, 2004.](https://doi.org/10.1111/j.1538-7836.2004.00790.x)

- [Freund Y et al. Effect of the Pulmonary Embolism Rule-Out Criteria on subsequent thromboembolic events among low-risk emergency department patients: the PROPER randomized clinical trial. JAMA, 2018.](https://doi.org/10.1001/jama.2017.21904)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

PERC negative: PE excluded without D-dimer, if pretest probability is low (< 15%)

No additional PE investigation is needed in this context.


### 2

PERC positive: does not exclude PE

Proceed with D-dimer (or with the Wells/Geneva algorithm).


### 3

PERC positive: does not exclude PE

Proceed with D-dimer (or with the Wells/Geneva algorithm).

