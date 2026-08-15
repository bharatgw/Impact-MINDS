# Impact analysis for MINDS Yishun Training and Development Centre

> Historical portfolio project. This repository is preserved as an academic analysis and is not an official MINDS operational report.

## Overview

This project studied a methodology for assessing how activities at MINDS Yishun Training and Development Centre might relate to beneficiaries' wellbeing and capability measures. The analysis uses pre- and post-service indicators and regression-based comparisons.

## Important data notice

The original project involved internal data. The notebook published here uses randomized presentation data so that the methodology can be shown without publishing the original records. Results produced from the randomized data must not be interpreted as evidence about individual beneficiaries, programme effectiveness, or MINDS.

The material concerns people with intellectual disabilities and should be read with appropriate care. The repository is intended to demonstrate an analytical workflow, not to support clinical, policy, or service-delivery decisions.

## Repository contents

| Path | Purpose |
| --- | --- |
| `MINDS_analysis.ipynb` | Data preparation, descriptive analysis, visualisation, and regression workflow. |

## Historical environment

The notebook records a Python 3.8.5 32-bit kernel and uses:

- pandas
- NumPy
- Matplotlib
- statsmodels

The environment is not pinned and compatibility with current package releases has not been verified. The saved notebook output is retained as part of the historical artifact.

## Measures represented

The notebook works with activity, assessment stage, question, rating, text, and indicator fields. Ratings include MISO-style indicators and general wellbeing scores. See the notebook for the precise transformations used in the original analysis.

## License and reuse

No open-source license has been applied. The project is shared for viewing as portfolio work. The organization name, methodology context, and any third-party materials remain subject to their respective rights.