# LICENSE-DATA

**Scope.**  
This file governs the *data* contained in this repository; namely the canonicalized exports of Rich Skill Descriptors (RSDs) from Western Governors University’s **Open Skills Management Tool (OSMT)** that have been packaged here as a single Turtle ontology file and related manifests. It does **not** apply to any code or documentation in this repository (see `LICENSE` for that).

## Ownership & Source

- The underlying RSD content is © Western Governors University / Open Skills Network and/or their respective rights holders (“**Upstream**”).  
- This repository only normalizes filenames/IRIs and aggregates content for reproducible distribution. **No edits were made to the underlying text/data.**
- Per-item provenance is embedded in the TTL via `dct:source` links to OSMT (e.g., `https://osmt.wgu.edu/api/skills/<uuid>`).

## License Status

- **No additional rights are granted by this repository.** Use of the data is governed by Upstream’s terms and policies.
- If Upstream publishes a specific license (e.g., an open data license) for OSMT exports, **that license controls**. You must consult the source and comply with any stated terms.

## Permitted Use (Subject to Upstream Terms)

- You may **download** and **analyze** the packaged data.
- You may **redistribute the unmodified payload** *as a whole* for scholarly/archival purposes **with proper attribution** (see below) and with a clear notice that Upstream terms govern.
- Do **not** imply endorsement by WGU/OSN/OSMT.

## Attribution

When citing or redistributing, include:

- Source: *Western Governors University; Open Skills Management Tool (OSMT)*  
- Link: <https://osmt.wgu.edu/> (and per-item `dct:source` URLs where relevant)  
- Packager: *Craig Trim (canonicalization/packaging only)*  
- Version of this package: e.g., **2025.11.01**  
- Persistent vocabulary/ontology namespace (if used): `https://w3id.org/wgu/osmt/skills#`

**Suggested citation (human-readable):**  
“WGU OSMT Rich Skill Descriptors, exported from OSMT and repackaged without modification. © Western Governors University / Open Skills Network. Packaged by Craig Trim, version 2025.11.01. Upstream terms apply.”

## Trademarks

All trademarks, service marks, and logos are the property of their respective owners. No rights to trademarks are granted.

## No Warranty

THE DATA IS PROVIDED “AS IS,” WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ACCURACY, COMPLETENESS, OR FITNESS FOR A PARTICULAR PURPOSE.

## Takedown / Rights Requests

If you are a rights holder and want content changed or removed, please open an issue on this repository or contact the maintainer listed in `README.md`. Include URLs/IRIs and any relevant identifiers so we can locate the material.

---
**Summary:** This repo repackages OSMT exports for reproducible access; **Upstream terms govern all data rights.** See `LICENSE` for code/docs license.
