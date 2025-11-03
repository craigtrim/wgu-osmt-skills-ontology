# WGU OSMT Skills Ontology (v2025.11.01)

Compact RDF/Turtle ontology derived from Western Governors University’s **Open Skills Management Tool (OSMT)** Rich Skill Descriptors (RSDs).  
**Base IRI:** `https://w3id.org/wgu/osmt/skills#` (persistent via w3id)

[![Latest Release](https://img.shields.io/github/v/release/craigtrim/wgu-osmt-skills-ontology?include_prereleases&label=release&style=flat)](../../releases)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.17517047-7952b3?style=flat)](https://doi.org/10.5281/zenodo.17517047)
[![IRI](https://img.shields.io/badge/IRI-w3id.org%2Fwgu%2Fosmt%2Fskills-black?style=flat)](https://w3id.org/wgu/osmt/skills)
[![License: MIT](https://img.shields.io/badge/License-MIT-0a66c2?style=flat)](./LICENSE)
[![Data Terms](https://img.shields.io/badge/Data-OSMT%2FWGU%20terms-f39c12?style=flat)](./LICENSE-DATA.md)

---

## What is this?
A single Turtle file:
- `wgu-osmt-skills-ontology_v2025.11.01.ttl` (~16 MB)  
- Contains RSD resources (skills, collections, alignments, occupations, keywords) normalized to a stable namespace.

**Note:** This repository contains the **ontology only** (no raw CSV/JSON inputs). The raw inputs are archived in a separate payload-only dataset repo.

---

## Namespace / Prefix

```
@base <https://w3id.org/wgu/osmt/skills#> .
@prefix :    <https://w3id.org/wgu/osmt/skills#> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix skos:<http://www.w3.org/2004/02/skos/core#> .
# ...any others you use...
```

Example resources: `:rsd-<uuid>`, `:col-<uuid>`, `:kw-<slug>`, `:bls-<code>`.

---

## Quick use

### Download
- GitHub Release asset (recommended), or clone and use the `.ttl` directly.

### Validate file
```
# macOS
shasum -a 256 wgu-osmt-skills-ontology_v2025.11.01.ttl

# Linux
sha256sum wgu-osmt-skills-ontology_v2025.11.01.ttl
```

### Load in Protégé
- File → Open… → select `wgu-osmt-skills-ontology_v2025.11.01.ttl`
- Ensure base IRI shows as `https://w3id.org/wgu/osmt/skills#`

### cURL test (content negotiation via w3id)
```
curl -L -H 'Accept: text/turtle' https://w3id.org/wgu/osmt/skills | head
```

---

## Versioning

- **Current version:** `2025.11.01`
- Tag format: `vYYYY.MM.DD`
- The w3id target may redirect to the latest stable release; older tags remain available via GitHub Releases.

---

## Licensing

- **Code/Docs:** MIT. See `LICENSE`.
- **Data/Content:** Subject to upstream OSMT/WGU terms.  See `LICENSE-DATA.md`.  
  This repo does **not** grant additional rights beyond upstream terms.

---

## Citation

If you use this ontology, please cite:

**CFF (preferred):**
Add a `CITATION.cff` in your project referencing this repo and version.

**BibTeX:**
```
@dataset{wgu_osmt_skills_ontology_2025_11_01,
  title   = {WGU OSMT Skills Ontology},
  author  = {Trim, Craig},
  version = {2025.11.01},
  year    = {2025},
  url     = {https://w3id.org/wgu/osmt/skills}
}
```

---

## Contact / Takedown
Rights holder and attribution notes are in `NOTICE`.  
Open a GitHub issue for corrections or takedown requests.
