# Luiz Dione B. De-Melo

**Full Professor at the Federal Institute of Rio de Janeiro (IFRJ), Brazil.**
Molecular biologist with a doctorate in Biophysics from UFRJ and a research background in *Trypanosoma cruzi* and *Leishmania*. I build software for diagnostics, omics analysis and research assessment, with an emphasis on results that other researchers can check.

[ORCID](https://orcid.org/0000-0003-2445-9943) · [Lattes](http://lattes.cnpq.br/2503582131532101) · [Molecular Genetics Laboratory, IFRJ](https://www.ifrj-crj-geneticamolecular.online/) · [luiz.melo@ifrj.edu.br](mailto:luiz.melo@ifrj.edu.br)

## Research software

| Tool | What it does | Try it | License |
|---|---|---|---|
| [LAMPrime](https://github.com/luizdione/LAMPrime_browser-based) | Browser-based LAMP primer designer. Sequences never leave the device. | [Web app](https://www.ifrj-crj-geneticamolecular.online/aplicativos/LAMPrime/LAMPrime.html) | MIT |
| [KANON-Index](https://github.com/luizdione/kanon-index) | Multidimensional alternative to the h-index that credits authorship structure and methodological sophistication. | [Calculator](https://www.ifrj-crj-geneticamolecular.online/kanon/html/kanon_index.html) · [Preprint](https://doi.org/10.2139/ssrn.6896838) | MIT |
| [Docking Suite](https://github.com/luizdione/Platform_docking_suite) | Umbrella platform for antiparasitic drug discovery: protozoan and mammalian protein targets, a compound library, docking with AutoDock Vina, molecular dynamics with OpenMM and ADMET. | Source code | Non-commercial |
| [PPI Docking](https://github.com/luizdione/Platform_ppi_docking) | Confidence funnel for protein-protein interactions: AI structure prediction, scoring, confidence gates and HADDOCK3 refinement. | [HADDOCK3 engine image](https://github.com/luizdione/Platform_ppi_docking/pkgs/container/ppi-haddock3) | Non-commercial |
| [CoIP-MS / AP-MS Analysis](https://github.com/luizdione/Platform_Analysis_CoIP-MS-AP-MS) | Local platform (browser and Docker) for CoIP-MS and AP-MS analysis in the mouse proteome. | [Container](https://github.com/luizdione/Platform_Analysis_CoIP-MS-AP-MS/pkgs/container/platform_analysis_coip-ms-ap-ms) · [DOI](https://doi.org/10.5281/zenodo.24063134) | Non-commercial |
| [Platform_TBP](https://github.com/luizdione/Platform_TBP) | Surveillance of bovine parasitic diseases, combining PCR and LAMP results with climate data. | Source code | Non-commercial |
| [Soil Analyzer](https://github.com/luizdione/Software_Soil_Analyzer) | Turns a soil lab report into a liming and fertilization plan. | [Windows app](https://github.com/luizdione/Software_Soil_Analyzer/releases/latest) | Freeware |

*Non-commercial: free for personal use and teaching; research use requires the author's prior authorization by [email](mailto:luiz.melo@ifrj.edu.br); commercial use is not permitted. See each repository's `LICENSE`.*

### Container images

Published to the GitHub Container Registry, built by GitHub Actions from the public source.

```bash
docker pull ghcr.io/luizdione/platform_analysis_coip-ms-ap-ms:latest
docker pull ghcr.io/luizdione/ppi-haddock3:latest
```

The second one is the HADDOCK3 refinement engine that the PPI Docking funnel calls; point
`PPI_DOCK_HADDOCK_IMAGE` at it. Each image carries only code and configuration — no research data.

## Independent software

Personal projects, developed without institutional affiliation.

| Tool | What it does | Try it | License |
|---|---|---|---|
| [LILO](https://github.com/luizdione/Platform_LILO_IA) | Fully local research assistant: Ollama, Open WebUI and an MCP tool bridge. | [Installer](https://github.com/luizdione/Platform_LILO_IA/releases/latest) | Non-commercial |
| [CEM](https://github.com/luizdione/Platform_CEM) | Backup, restore and migration of Claude Code environments. | [Installer](https://github.com/luizdione/Platform_CEM/releases/latest) | Non-commercial |

## What I work on

- Computational biology and multi-omics integration
- Molecular parasitology and host-parasite interaction (*Trypanosoma cruzi*, *Leishmania*)
- Molecular diagnostics
- Protein interactions and molecular docking
- Livestock genomics
- Scientometrics and research assessment
- AI agents for research, and reproducible open-source scientific software

**Languages:** Python, R
**Omics:** Nextflow, Snakemake, SAMtools, BCFtools, BEDTools, deepTools, HOMER, Bioconductor, SRA Toolkit
**Structure:** AutoDock Vina, OpenMM, GROMACS, Boltz, HADDOCK3
**Infrastructure and AI:** Docker, PyTorch, Ollama

## Selected publications

- [The KANON-Index: Crediting Authorship Structure and Methodological Sophistication in Research Assessment](https://doi.org/10.2139/ssrn.6896838). Preprint, 2026.
- [Functional studies of TcRjl, a novel GTPase of *Trypanosoma cruzi*, reveals phenotypes related with MAPK activation during parasite differentiation and after heterologous expression in *Drosophila* model system](https://doi.org/10.1016/j.bbrc.2015.09.110). *Biochemical and Biophysical Research Communications*, 2015.
- [Novel role for the double-stranded RNA-activated protein kinase PKR: Modulation of macrophage infection by the protozoan parasite *Leishmania*](https://doi.org/10.1096/fj.09-140053). *FASEB Journal*, 2010.
- [Intranasal delivery of naked DNA encoding the LACK antigen leads to protective immunity against visceral leishmaniasis in mice](https://doi.org/10.1016/j.vaccine.2006.11.060). *Vaccine*, 2007.
- [TcRho1, a farnesylated Rho family homologue from *Trypanosoma cruzi*: cloning, trans-splicing, and prenylation studies](https://doi.org/10.1074/jbc.M102920200). *Journal of Biological Chemistry*, 2001.

Full list on [ORCID](https://orcid.org/0000-0003-2445-9943).

## Collaboration

I welcome collaborations in molecular parasitology, diagnostics, omics analysis and research software. The best way to reach me is by [email](mailto:luiz.melo@ifrj.edu.br).
