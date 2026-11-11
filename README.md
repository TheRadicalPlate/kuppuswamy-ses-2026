# Modified Kuppuswamy Scale for Socioeconomic Status (2026 Update)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.YOUR_ZENODO_ID.svg)](https://doi.org/10.5281/zenodo.YOUR_ZENODO_ID)

An open-source, web-based calculator software implementing the 2026 revision of the **Modified Kuppuswamy Socioeconomic Status (SES) Scale** for Indian households and epidemiological research.

Income thresholds have been updated using the All-India Consumer Price Index for Industrial Workers (CPI-IW) for January 2026 (base index 2016 = 100, index value = 148.6) with statutory linking factors across historical series (1960, 1982, 2001, and 2016).

---

## Features

- **Dual Income Entry**: Type the exact monthly income in ₹ (auto-categorized) or choose from the 2026 bracket dropdown.
- **Instant Composite Scoring**: Displays real-time breakdown of Income (1–12), Education (1–7), and Occupation (1–10) sub-scores, cumulative score (3–29), and SES classification (Classes I to V).
- **Privacy-First Analytics**: Pre-integrated with [GoatCounter](https://www.goatcounter.com/) to count visits and calculations without tracking personal data or setting cookies.
- **One-Click Citation**: Ready-to-copy academic citations (APA and BibTeX) for both the software and the published methodological study.
- **Zero Dependencies**: Pure HTML5, CSS3, and vanilla JavaScript in a single, lightweight, mobile-responsive file.

---

## 2026 Scale Scoring Rubric

### 1. Monthly Family Income Brackets (CPI-IW Jan 2026)
| Income Range (₹) | Score |
| :--- | :---: |
| ≥ ₹66,007 | 12 |
| ₹33,004 – ₹66,006 | 10 |
| ₹24,753 – ₹33,003 | 6 |
| ₹16,502 – ₹24,752 | 4 |
| ₹9,901 – ₹16,501 | 3 |
| ₹3,301 – ₹9,900 | 2 |
| ≤ ₹3,300 | 1 |

### 2. Education of Head of Family
| Educational Level | Score |
| :--- | :---: |
| Postgraduate and above | 7 |
| Graduate | 6 |
| Higher secondary | 5 |
| Middle school | 4 |
| Primary school | 3 |
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

## Deployment to GitHub Pages

1. Fork or clone this repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/kuppuswamy-ses-2026.git
   ```
2. In `index.html`, replace:
   - `YOUR-GOATCOUNTER-CODE` with your GoatCounter username/subdomain.
   - `YOUR_GITHUB_USERNAME` with your GitHub username.
   - `YOUR_ZENODO_ID` with your Zenodo DOI identifier after archiving.
3. Push to GitHub and navigate to **Settings** > **Pages**.
4. Set source to **Deploy from a branch** > branch: `main` / root (`/`).
5. Your calculator will be live at `https://<YOUR_GITHUB_USERNAME>.github.io/kuppuswamy-ses-2026/`.

---

## How to Cite

### 1. Software Citation
```text
Alphonso, R. (2026). Modified Kuppuswamy Scale for Socioeconomic Status (2026 Update) [Computer software]. GitHub. https://doi.org/10.5281/zenodo.YOUR_ZENODO_ID
```

### 2. Methodological Paper Reference
```text
Yadav, A., Mondal, A., & Debnath, A. (2026). Revamping socioeconomic assessment: 2026 updates to the B. G. Prasad and modified Kuppuswamy scales. International Journal of Community Medicine and Public Health, 13(4), 2050–2054. https://doi.org/10.18203/2394-6040.ijcmph20260759
```

### BibTeX
```bibtex
@article{yadav2026revamping,
  author  = {Yadav, Ankit and Mondal, Anubhav and Debnath, Aninda},
  title   = {Revamping socioeconomic assessment: 2026 updates to the B. G. Prasad and modified Kuppuswamy scales},
  journal = {International Journal of Community Medicine and Public Health},
  volume  = {13},
  number  = {4},
  pages   = {2050--2054},
  year    = {2026},
  doi     = {10.18203/2394-6040.ijcmph20260759}
}

@software{alphonso2026kuppuswamy,
  author  = {Alphonso, Rachael},
  title   = {Modified Kuppuswamy Scale for Socioeconomic Status (2026 Update)},
  year    = {2026},
  url     = {https://github.com/YOUR_GITHUB_USERNAME/kuppuswamy-ses-2026},
  doi     = {10.5281/zenodo.YOUR_ZENODO_ID}
}
```

---

## License

This software is released under the **MIT License**. You are free to use, modify, and distribute this tool with proper attribution to the author and the underlying research paper. See [LICENSE](LICENSE) for details.
