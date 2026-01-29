# Changelog
This document records all notable changes to the **Draphera HP‑GL/HP‑GL/2 Bible**.  
The changelog follows a structured, transparent, and traceable format to ensure clarity and long‑term maintainability.

All entries follow the format:

- **Added** — new sections, features, or concepts  
- **Changed** — modifications to existing content  
- **Fixed** — corrections, clarifications, or resolved inconsistencies  
- **Removed** — deprecated or eliminated content  
- **Notes** — non‑technical remarks or editorial updates  

---

## Versioning Policy
The Draphera Bible uses a **semantic documentation versioning model**:

- **MAJOR** — structural changes, new chapters, breaking conceptual updates  
- **MINOR** — new pages, expanded sections, added examples  
- **PATCH** — fixes, clarifications, editorial improvements  

Example: `1.3.2`  
- `1` → major edition  
- `3` → new content added  
- `2` → corrections or refinements  

---

# Release History

## **1.0.0 — Initial Public Draft**
**Date:** YYYY‑MM‑DD  
**Status:** Draft

### Added
- Complete directory structure for the Draphera Bible  
- Front matter: preface, mission, scope, legal notice, acknowledgements, references, history, format status, introduction, versioning, changelog  
- Overview section: HP‑GL overview, HP‑GL/2 overview, apparel context, terminology  
- Core specification: syntax, coordinate system, units, pens & layers, device model, semantics  
- Commands section: HP‑GL commands and HP‑GL/2 command groups  
- Draphera interpretation: normalization pipeline, unified command model, apparel‑safe subset, error recovery, coordinate & layer normalization, compatibility rules, rendering model  
- Vendor profiles: Gerber, Lectra, Investronica, Optitex, Tukatech, Assyst, others  
- Examples: shapes, contours, notches, drill holes, grading, markers, HP‑GL/2 examples, mixed files  
- Test suite: conformance tests, edge cases, malformed input, normalization tests, rendering tests, vendor‑specific tests  
- Appendices: grammar (EBNF), coordinate tables, unit conversion, historical devices, glossary, future work  
- Standard section: specification, conformance, governance, versioning  
- Tools section: validator, renderer, CLI, API  
- Root files: README, index, contributing guidelines, code of conduct  

### Notes
- This version establishes the foundational structure of the Draphera Bible.  
- Content is intentionally skeletal and will be expanded in subsequent releases.  

---

## **1.0.1 — Editorial Refinements**
**Date:** YYYY‑MM‑DD  
**Status:** Patch

### Fixed
- Minor formatting inconsistencies in front‑matter pages  
- Corrected folder naming conventions for consistency  

### Notes
- No technical content changes.  

---

## **1.1.0 — First Content Expansion**
**Date:** YYYY‑MM‑DD  
**Status:** Minor

### Added
- Initial drafts for HP‑GL command pages  
- First version of the apparel‑safe subset definition  
- Expanded terminology and glossary entries  

### Changed
- Improved structure of the normalization pipeline  
- Updated device model description  

---

## **1.2.0 — Interoperability Framework**
**Date:** YYYY‑MM‑DD  
**Status:** Minor

### Added
- Draft of Draphera Unified Plot Format (DUPF)  
- Interoperability rules between HP‑GL and HP‑GL/2  
- New examples for mixed‑format files  

### Changed
- Updated semantics section with clarified behaviour for ambiguous commands  

---

# Unreleased Changes
This section tracks ongoing work before the next tagged release.

### Added
-  

### Changed
-  

### Fixed
-  

### Removed
-  

---

# Contribution Guidelines
All changes must be documented in this file.  
Contributors should follow the versioning policy and categorize updates appropriately.

