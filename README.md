# Comparative efficacy and safety of medical therapies for Crohn's disease: a living systematic review and Bayesian network meta-analysis

**Protocol release v1.0-protocol** (protocol version 2.4, 24 October 2026)

Authors: Tomáš Lintner, Ivan Ropovik, Michaela Nesrstová, Zuzana Derflerová Brázdová

Corresponding author: Tomáš Lintner (tomas.lintner@mail.muni.cz, ORCID 0000-0002-1448-4064), Department of Public Health, Faculty of Medicine, Masaryk University, Brno, Czech Republic.

Registration: PROSPERO (registration number pending; it will be added here once assigned).

## Contents

| Folder | What it holds |
|---|---|
| `protocol/` | The review protocol, version 2.4 (`Crohn_LSR_protocol_v2.4.pdf`, `.docx`), and the completed PRISMA-P 2015 checklist (Supplementary Material S3, `Crohn_LSR_S3_PRISMA-P_checklist_v2.4.pdf`, `.docx`). |
| `supplements/` | S1: the pool of 83 earlier systematic reviews used to seed the legacy trial set (citations only; abstracts are not redistributed). S2: full search strategies, version 1.0 (`.pdf`, `.docx`), and the completed PRESS 2015 peer review of the strategies. S4: network node definitions, version 1.0 (`.xlsx` with all sheets, `.docx`, `.pdf`), and the authoritative list of node decisions (`Crohn_LSR_S4_node_decisions_FINAL_2026-10-22.txt`). |
| `screening/` | The title/abstract screening prompt adopted for the review (`prompt_v0.2_title_abstract.txt`), the registry-record prompt (`prompt_registry_v0.1.txt`) and the prompt change log; the validation summary of the title/abstract workflow (`VALIDATION_SUMMARY_title_abstract_2026-10-24.txt`: Claude Sonnet 5.5 and GPT-6.1 Sol); the Claude pilot summary, the prompt v0.2 re-check report and the GPT pilot report; the known-positive trial set version 1.1 as identifiers only (`known_positives_v1.1_identifiers.csv`: trial ID, status, first author, year, journal, PMID, DOI, NCT number); and the scripts (`scripts/`: pilot R scripts and launchers; `scripts/screening_full/`: the shared batch-screening engine and the full-screening runner). |

Not included: raw bibliographic database exports, any file containing record titles or abstracts, and full-text articles (copyright), and API keys. The scripts read API keys only from environment variables (`ANTHROPIC_API_KEY`, `OPENAI_API_KEY`); no key is stored in any file.

## Licence

Documents and data are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0); see `LICENSE`. Code (the R scripts in `screening/scripts/`) is licensed under the MIT licence; see `LICENSE-CODE`. The PRISMA-P checklist template is © the PRISMA-P Group, distributed under CC BY 4.0.

## How to cite

Lintner T, Ropovik I, Nesrstová M, Derflerová Brázdová Z. Comparative efficacy and safety of medical therapies for Crohn's disease: a living systematic review and Bayesian network meta-analysis. Protocol, version 2.4 (release v1.0-protocol). Zenodo; 2026. doi:[DOI to be assigned at release]

See also `CITATION.cff`.
