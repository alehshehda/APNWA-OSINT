# OSINT Reconnaissance and Social Engineering Attack Scenarios - ETH Zürich (D-INFK)

[![View PDF](https://img.shields.io/badge/View-PDF-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://alehshehda.github.io/APNWA-OSINT/APNWA-OSINT.pdf)
[![Download PDF](https://img.shields.io/badge/Download-PDF-success?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alehshehda/APNWA-OSINT/releases/download/latest/APNWA-OSINT.pdf)

Project documentation for the **Advanced Network and Web Application Penetration Testing** course (*Zaawansowane testy penetracyjne sieci i aplikacji Web*) at Wrocław University of Science and Technology, Faculty of Information and Communication Technology (Cybersecurity).

## Authors

- Aleh Shehda (272277)
- Aliaksei Lapachuk (276711)
- Karyna Zahorskaya (272302)

**Supervisor:** mgr inż. Bartłomiej Aleksander Balcerek

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
  1_wstep.tex                         Introduction and research methodology
  2_organizacja.tex                   Organizational, financial, and business information
  3_infrastruktura.tex                IT and network infrastructure reconnaissance
  4_archiwa_metadane.tex              Historical records, archives, and document metadata
  5_slady_cyfrowe.tex                 Digital footprints, social media, and personnel
  6_powierzchnia_ataku.tex            Attack surface analysis and potential threats
  7_socjotechnika.tex                 Proposed social engineering attack scenarios
  8_podsumowanie.tex                  Summary and security recommendations
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

