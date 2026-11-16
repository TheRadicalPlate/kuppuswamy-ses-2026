# Modified Kuppuswamy Scale for Socioeconomic Status (2026 Update)

[![License: MIT](https://img.shields.io/badge/License-MIT-4338ca.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24143455.svg)](https://doi.org/10.5281/zenodo.24143455)

An open-source, multilingual web-based calculator and batch Excel template implementing the 2026 revision of the **Modified Kuppuswamy Socioeconomic Status (SES) Scale** for Indian households and epidemiological research.

Income thresholds are updated using the All-India Consumer Price Index for Industrial Workers (CPI-IW) for January 2026 (base index 2016 = 100, index value = 148.6) with statutory linking factors across historical series (1960, 1982, 2001, and 2016).

---

## Methodological Restoration Note (7-Tier Education Scoring)

While the 2026 monthly family income thresholds strictly follow **Yadav, Mondal, & Debnath (*Int J Community Med Public Health*, April 2026)**, Table 3 of that publication erroneously omitted the **"High school certificate" (4 points)** category and shifted the scores for Middle school (from 3 to 4) and Primary school (from 2 to 3), leaving a gap at 2 points.

To ensure epidemiological accuracy and backward compatibility with national health surveys, both the web calculator (`index.html`) and batch spreadsheet (`Kuppuswamy_SES_Calculator_2026-v2.xlsx`) **restore the canonical 7-tier Kuppuswamy (1976) education scoring rubric**.

---

## Live Web Application

- **Live Calculator**: [https://theradicalplate.github.io/kuppuswamy-ses-2026/](https://theradicalplate.github.io/kuppuswamy-ses-2026/)
- **Zenodo Archive**: [https://doi.org/10.5281/zenodo.24143455](https://doi.org/10.5281/zenodo.24143455)

---

## Features

- **5-Language Bilingual Field Interface**: Supports English, Hindi (`?lang=hi`), Tamil (`?lang=ta`), Marathi (`?lang=mr`), and Bengali (`?lang=bn`) with English Kuppuswamy terms in parentheses to prevent interviewer bias.
- **Dual Income Entry**: Type exact monthly income in ₹ (auto-categorized) or choose from the 2026 bracket dropdown.
- **Batch Cohort Excel Workbook**: Includes `Kuppuswamy_SES_Calculator_2026-v2.xlsx` with automated `VLOOKUP` scoring and dropdown validation for multi-subject cohorts.
- **100% Client-Side Privacy**: Zero participant data is stored, logged, or transmitted.

---

## 2026 Scale Scoring Rubric

### 1. Monthly Family Income Brackets (CPI-IW Jan 2026 — Yadav et al., 2026)
| Income Range (₹) | Score |
| :--- | :---: |
| ≥ ₹66,007 | 12 |
| ₹33,004 – ₹66,006 | 10 |
| ₹24,753 – ₹33,003 | 6 |
| ₹16,502 – ₹24,752 | 4 |
| ₹9,901 – ₹16,501 | 3 |
| ₹3,301 – ₹9,900 | 2 |
| ≤ ₹3,300 | 1 |

### 2. Education of Head of Family (Restored Canonical 7-Tier Kuppuswamy Rubric)
| Educational Level | Score |
| :--- | :---: |
| Profession or honors | 7 |
| Graduate | 6 |
| Intermediate or diploma | 5 |
| High school certificate *(restored)* | 4 |
| Middle school certificate *(realigned from 4)* | 3 |
| Primary school certificate *(realigned from 3)* | 2 |
| Illiterate | 1 |

### 3. Occupation of Head of Family
| Occupational Category | Score |
| :--- | :---: |
| Legislators, senior officials, managers | 10 |
| Professionals | 9 |
| Technicians / associate professionals | 8 |
| Clerk | 7 |
| Skilled worker, shop and market sales workers | 6 |
| Skilled agricultural and fishery workers | 5 |
| Craft and related trade workers | 4 |
| Plant and machine operators and assemblers | 3 |
| Elementary occupation | 2 |
| Unemployed | 1 |

### 4. Socioeconomic Class Classification
| Total Score | Socioeconomic Class | Class Code |
| :---: | :--- | :---: |
| 26 – 29 | Upper class | Class I |
| 16 – 25 | Upper middle class | Class II |
| 11 – 15 | Lower middle class | Class III |
| 5 – 10 | Upper lower class | Class IV |
| < 5 | Lower class | Class V |

---

## How to Cite

### 1. Software Citation (APA)
```text
Alphonso, R. (2026). Modified Kuppuswamy Scale for Socioeconomic Status (2026 Update) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.24143455
```

### 2. Methodological Paper Reference (APA)
```text
Yadav, A., Mondal, A., & Debnath, A. (2026). Revamping socioeconomic assessment: 2026 updates to the B. G. Prasad and modified Kuppuswamy scales. International Journal of Community Medicine and Public Health, 13(4), 2050–2054. https://doi.org/10.18203/2394-6040.ijcmph20260759
```

### 3. Original Scale Reference (APA)
```text
Kuppuswamy, B. (1976). Manual of Socio-economic Status (Urban). Manasayan, Delhi.
```

---

## License

Released under the **MIT License**. See [LICENSE](LICENSE) for details.
