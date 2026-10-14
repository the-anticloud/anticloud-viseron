# VISERON

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-surveillance_camera-lightgrey)

> Anticloud-hardened packaging of the upstream project `VISERON` in category **SURVEILLANCE CAMERA**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SURVEILLANCE CAMERA · **Upstream:** https://github.com/roflcoopter/viseron · **Upstream pin:** `9f2336bf714b88b678480b9014b48c6be31321d1` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<div align="center">
    <a href="https://github.com/roflcoopter/viseron">
        <img width="150" height="150" src="docs/static/img/viseron-logo.svg">
    </a>
    <br>
    <h1>Viseron</h1>
    <p>
        Self-hosted, local only NVR and AI Computer Vision software.
    </p>
    <p>
        With features such as object detection, motion detection, face recognition and more, it gives you the power to keep an eye on your home, office or any other place you want to monitor.
    </p>
    <p>
        <a href="https://discord.gg/MxP5xpyvk7">
            <img src="https://img.shields.io/badge/Discord-Join%20the%20community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join the Viseron Discord server">
        </a>
    </p>
    <h1></h1>
    <br>
</div>

# Getting started

Getting started is easy! You simply spin up a Docker container and edit the configuration file using the built in web interface.

Head over to the [documentation](https://viseron.netlify.app) and follow the instructions on how to get started.

# Components

Viserons functionality is enabled by [components](https://viseron.netlify.app/docs/documentation/configuration#components).

You can find all the available components by using the [Component Explorer](https://viseron.netlify.app/components-explorer/).

# Community

Join the [Viseron Discord server](https://discord.gg/MxP5xpyvk7) to ask for help, share your setup and follow along with development.

Discord is the best place to get help with configuration and troubleshooting.
If you have found a confirmed bug or want to request a feature, open an [issue](https://github.com/roflcoopter/viseron/issues) instead.

# Contributing

Contributors to the project are very much appreciated.
See the [contribution guidelines](https://viseron.netlify.app/docs/contributing) on how to get started.

Some things you can help with:

- Implement an open feature request or issue from the [issue tracker](https://github.com/roflcoopter/viseron/issues)
- Improve the documentation
- Answer questions in issues, [discussions](https://github.com/roflcoopter/viseron/discussions) or on [Discord](https://discord.gg/MxP5xpyvk7)

You can also use the links below to sponsor Viseron or make a one time donation.

<a href="https://github.com/sponsors/roflcoopter" target="_blank"><img src="docs/static/img/sponsor_button.png" alt="Sponsor" style="height: 37px !important;width: 170px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5)" ></a>
<a href="https://www.buymeacoffee.com/roflcoopter" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: pyproject.toml, requirements.txt; scanned in UPSTREAM_CLONE)
- Top-level source layout: `azure-pipelines/`, `config/`, `docker/`, `frontend/`, `rootfs/`, `scripts/`, `tests/`, `viseron/`
- Snapshot size: **1072 files**, **145630 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (404), `.tsx` (222), `.ts` (115), `.mdx` (64), `.png` (58), `.json` (34)
- Upstream commit pinned for this packaging: `9f2336bf714b88b678480b9014b48c6be31321d1`

---

## Installation

Getting started is easy! You simply spin up a Docker container and edit the configuration file using the built in web interface.

Head over to the [documentation](https://viseron.netlify.app) and follow the instructions on how to get started.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

Getting started is easy! You simply spin up a Docker container and edit the configuration file using the built in web interface.

Head over to the [documentation](https://viseron.netlify.app) and follow the instructions on how to get started.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

Head over to the [documentation](https://viseron.netlify.app) and follow the instructions on how to get started.

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | pyproject.toml, requirements.txt |
| Files in snapshot | 1072 |
| Lines of code | 145630 |
| Dependency references | 152 |
| Dependencies by ecosystem | npm: 152 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @carbon/icons-react | ^11.87.0 | frontend/package.json |
| npm | @codemirror/autocomplete | 6.20.3 | frontend/package.json |
| npm | @codemirror/commands | 6.11.0 | frontend/package.json |
| npm | @codemirror/language | 6.12.4 | frontend/package.json |
| npm | @codemirror/legacy-modes | 6.5.4 | frontend/package.json |
| npm | @codemirror/search | 6.7.2 | frontend/package.json |
| npm | @codemirror/state | 6.7.4 | frontend/package.json |
| npm | @codemirror/view | 6.43.11 | frontend/package.json |
| npm | @emotion/react | ^11.14.0 | frontend/package.json |
| npm | @emotion/styled | ^11.14.1 | frontend/package.json |
| npm | @fontsource-variable/ibm-plex-sans | ^5.3.0 | frontend/package.json |
| npm | @fontsource/dejavu-sans | ^5.3.0 | frontend/package.json |
| npm | @jy95/material-ui-image | ^4.0.9 | frontend/package.json |
| npm | @mjackson/multipart-parser | ^0.10.1 | frontend/package.json |
| npm | @monaco-editor/react | ^4.7.0 | frontend/package.json |
| ... | (137 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

Head over to the [documentation](https://viseron.netlify.app) and follow the instructions on how to get started.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `VISERON` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
MIT License

Copyright (c) 2020 Jesper Nilsson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `VISERON` (category: SURVEILLANCE CAMERA)
- **Upstream URL:** https://github.com/roflcoopter/viseron
- **Pinned commit (SHA):** `9f2336bf714b88b678480b9014b48c6be31321d1`
- **Branch:** dev
- **Pin provenance:** GitHub API commits/dev. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`6c450422a17c554555b2f22068ea8fa49d306e76e46463f906da5627da9e351d`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

