<!-- ELUCENIA technical documentation · peso-ideal-e-ajustado · en · no clinical/professional/rights approval -->

# Ideal and adjusted body weight

[conditions, sources and permissions](https://elucenia.org/en/tools/peso-ideal-e-ajustado)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Sex

`sexo`

- `F` — Female
- `M` — Male

### Height

`altura`

cm · range: 120–230

### Actual body weight (for adjusted weight)

`peso`

kg · optional · range: 25–350

## Method edition

Devine 1974/Robinson 1983/Miller 1983; Pai–Paloucek review 2000; adjusted weight local factor 0.4

## Documented formula

Ideal weight (Devine): men 50 kg + 2.3 kg per inch above 5 feet; women 45.5 kg + 2.3 kg per inch above 5 feet. In centimeters: 50 (45.5) + 2.3 × (height − 152.4) ÷ 2.54.

Adjusted weight = Ideal weight + 0.4 × (actual weight − Ideal weight).

## Limits and population

Ideal weight is an estimate from height/weight tables, not a measurement of lean mass. The pharmacokinetic relationship varies by drug; this abstract does not confirm a universal adjusted factor of 0.4. Choice of weight for dosing must follow the drug source and corresponding population.

## References

- [Pai MP, Paloucek FP. The origin of the "ideal" body weight equations. Ann Pharmacother, 2000.](https://doi.org/10.1345/aph.19381)

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

Ideal weight by the Devine formula


### 2

Actual weight > 120% of ideal: for hydrophilic drugs and aminoglycosides, use adjusted weight

| Result details | |
| --- | --- |
| Actual weight relative to ideal | 160% |
| Adjusted weight (IBW + 0,4 × excess) | 93.0 kg |


### 3

Ideal weight by the Devine formula


### 4

Ideal weight by the Devine formula

