# OSINT Reconnaissance and Social Engineering Attack Scenarios - ETH Zürich (D-INFK)

[![View PDF](https://img.shields.io/badge/View-PDF-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://alehshehda.github.io/APNWA-OSINT/APNWA-OSINT.pdf)
[![Download PDF](https://img.shields.io/badge/Download-PDF-success?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alehshehda/APNWA-OSINT/releases/download/latest/APNWA-OSINT.pdf)

Project documentation for the **Advanced Pentesting of Network and Web Application** course (*Zaawansowane testy penetracyjne sieci i aplikacji Web*) at Wrocław University of Science and Technology, Faculty of Information and Communication Technology (Cybersecurity).

## Authors

- Aleh Shehda (272277)
- Aliaksei Lapachuk (276711)
- Karyna Zahorskaya (272302)

**Supervisor:** mgr inż. Bartłomiej Balcerek

## Repository Structure

```text
main.tex                              main LaTeX document file
.github/
  workflows/
    compile.yml                       automated PDF build and release workflow
config/
  metadata.tex                        document metadata and optional section toggles
  theme-pwr.tex                       WUST visual theme and colors
preamble/                             packages, page styles, macros, and table settings
frontmatter/
  titlepage.tex                       title page layout
  abbreviations.tex                   list of abbreviations and acronyms
chapters/
  1_wstep.tex                         Introduction, theoretical foundations, and OSINT methodology
  2_organizacja.tex                   Organizational profile, economics, and physical environment
  3_infrastruktura.tex                Passive network infrastructure and protocol reconnaissance
  4_domeny_web.tex                    Passive web asset enumeration and application analysis
  5_personel_slady.tex                Personnel, digital footprints, document metadata, and repositories
  6_socjotechnika.tex                 Attack surface analysis and social engineering attack scenarios
  7_podsumowanie.tex                  Summary, defensive recommendations, and conclusions
appendices/
  A_przykladowy.tex                   Additional reconnaissance materials and raw data
bib/
  references.bib                      BibTeX bibliography database
  plabbrv-fixed.bst                   Polish bibliography style
images/                               figures and diagrams
logos/                                university logos
```

## Build

The document is automatically compiled to `APNWA-OSINT.pdf` and published to GitHub Releases and GitHub Pages via the GitHub Actions CI/CD workflow (`.github/workflows/compile.yml`) on every push to `main`.
