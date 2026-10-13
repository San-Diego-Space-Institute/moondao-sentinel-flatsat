# MoonDAO Sentinel Bio+ FlatSat Package

**A public engineering package for two matching ground testbeds developed by the San José State University (SJSU) student engineering program, with the San Diego Space Institute (SDSI).**

This repository is intended to preserve the reusable engineering knowledge produced by the MoonDAO-supported FlatSat effort: what was assembled, how it was configured, how it was tested, and what the evidence showed. The physical FlatSat hardware remains with the SJSU student engineering program. This repository does not transfer ownership of physical hardware or background intellectual property.

## Project summary

The project proposes adding a second matching FlatSat to the existing testbed. One unit provides a reference configuration; the second supports parallel subsystem and telemetry work. The intended outcome is more integration and validation cycles before flight-hardware development, plus a public, reusable technical package.

The MoonDAO proposal requested **$2,099.96** for two ground testbeds. The request and its planned work are proposal context; this README does not represent an award, purchase, completed test, or accepted deliverable unless a dated record in this repository says so.

## Planned public package

- Bill of materials (BOM), with source and revision information.
- Wiring diagrams and configuration records.
- Assembly, power-up, and configuration instructions.
- Original software and software configuration documentation.
- Integration and test procedures.
- Test logs, validation evidence, and comparison results.
- A final technical report documenting outcomes, limitations, and reusable lessons.

The files currently published here cover project scope, licensing, contribution, and provenance. Detailed engineering procedures, hardware records, software, and validation evidence will be added after they are prepared and cleared for release.

## Repository map

| Path | Purpose |
| --- | --- |
| `docs/project/` | Scope, roles, project status, and release rules |
| `docs/engineering/` | Planned assembly, configuration, test, and validation documentation |
| `hardware/` | Planned cleared diagrams and BOM records for the FlatSat testbeds |
| `software/` | Planned original project software and configuration scripts |
| `LICENSE` | MIT License for original software |
| `LICENSE-DOCS` | CC BY 4.0 for original documentation and other covered non-software content |
| `THIRD_PARTY_NOTICES.md` | Attribution and license register for included third-party material |

## Status and authority

This repository starts as a public project scaffold. It does not claim that the two-unit configuration, test procedures, or validation results are complete. The SJSU student engineering program retains the physical FlatSat hardware. SDSI coordinates the MoonDAO project package and maintains this repository. Before publishing contributed materials, maintainers must confirm the contributor has authority to release them under the applicable license.

Repository changes follow branches and pull requests. Reviewers should check technical content, source/provenance, license status, and whether the change distinguishes plans from results. Issues may be used to track deliverables and questions. A repository merge is not a technical acceptance review or a transfer of hardware ownership.

## License and reuse

- Original software in this repository: [MIT License](LICENSE).
- Original documentation, diagrams, BOMs, procedures, and reports: [Creative Commons Attribution 4.0 International](LICENSE-DOCS).
- Third-party material: governed by the license or permission stated for that item in `THIRD_PARTY_NOTICES.md`; it is not relicensed by this repository.
- Materials with unclear ownership, export-control status, confidentiality, or redistribution rights must not be added until resolved.

See [the release boundary and provenance rules](docs/project/PUBLICATION-BOUNDARY.md) before contributing. This repository is an engineering record, not a warranty or a claim of flight readiness.

## Community handoff

The proposal calls for presenting reusable results at a MoonDAO Town Hall or technical workshop. The event and date will be recorded here after they are confirmed. To propose a correction or contribution, open an issue or submit a pull request using the guidance in [CONTRIBUTING.md](CONTRIBUTING.md).
