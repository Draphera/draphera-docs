# Scope

**Document Version:** 1.0.0  
**Status:** Draft  
**Last Updated:** 2026-01-28

This document defines the scope of the **Draphera HP‑GL/HP‑GL/2 Bible**, outlining what is covered, what is excluded, and the intended boundaries of the specification.  
The goal is to provide clarity for developers, technicians, educators, and vendors who rely on this reference for interoperability and implementation.

---

# 1. In‑Scope Content

The Draphera Bible covers all aspects necessary to understand, implement, and validate HP‑GL and HP‑GL/2 in the context of apparel workflows.

### 1.1 Language Structure
- Syntax and grammar  
- Command formats  
- Coordinate systems  
- Units and scaling  
- Device model assumptions  

### 1.2 Command Semantics
- Behaviour of HP‑GL commands  
- Behaviour of HP‑GL/2 commands  
- Differences between the two languages  
- Ambiguities and undocumented behaviours  

### 1.3 Apparel‑Specific Interpretation
- Requirements for plotting patterns, markers, grading, and technical drawings  
- Constraints and best practices for apparel workflows  
- The Draphera **apparel‑safe subset**  

### 1.4 Interoperability and Normalization
- Rules for converting between HP‑GL and HP‑GL/2  
- Normalization pipelines  
- Unified command model  
- Error recovery strategies  

### 1.5 Vendor Dialects
- Documentation of vendor‑specific behaviours  
- Known deviations and extensions  
- Compatibility considerations  

### 1.6 Examples and Test Cases
- Annotated HP‑GL and HP‑GL/2 files  
- Mixed‑format examples  
- Conformance and edge‑case tests  

### 1.7 Draphera Standards and Tools
- Draphera Unified Plot Format (DUPF)  
- Conformance requirements  
- Validator and rendering guidelines  

---

# 2. Out‑of‑Scope Content

The Draphera Bible does **not** attempt to cover topics outside the technical and practical use of HP‑GL and HP‑GL/2 for apparel.

### 2.1 Non‑Apparel Use Cases
- Mechanical engineering plotting  
- Architectural plotting  
- Scientific visualization  
- General‑purpose vector graphics  

These domains may share the same languages but have different requirements and behaviours.

### 2.2 Non‑HP Plotting Languages
- G‑code  
- SVG  
- DXF  
- CGM  
- Proprietary vendor formats not based on HP‑GL/HP‑GL/2  

These may be referenced for comparison but are not documented in detail.

### 2.3 Hardware‑Level Specifications
- Electrical characteristics of plotters  
- Mechanical tolerances  
- Firmware‑level behaviour  
- Calibration procedures  

Only the logical behaviour of commands is considered.

### 2.4 Business or Operational Processes
- Production planning  
- Marker optimization strategies  
- Costing or material efficiency  
- Workflow management  

These topics fall outside the scope of a technical language specification.

---

# 3. Boundaries of Interpretation

The Draphera Bible provides a unified interpretation model, but:

- it does not override original HP documentation  
- it does not mandate vendor compliance  
- it does not enforce a single rendering style  
- it does not define device‑specific behaviour beyond what is necessary for interoperability  

The goal is clarity and consistency, not prescriptive control over vendor implementations.

---

# 4. Intended Use

This document is intended to serve as:

- a technical reference  
- an interoperability guide  
- an educational resource  
- a foundation for future standards  

It is not a replacement for original HP manuals, but a modern, consolidated, and apparel‑focused complement.

---

# 5. Evolution of Scope

As new information, archival material, or industry needs emerge, the scope of this document may expand or be refined.  
Changes will follow the Draphera governance and versioning process.

