# v28 Implementation Protocol

This file explains the role of the archived v28 implementation protocol in the Paper I artifact package.

## Purpose

`Script_Contract_v28_original.pdf` is the original execution specification used to generate the frozen PythonApplication157 evidence boundary. It defines the implementation requirements for BTNS-native polynomial-coefficient construction, including:

- BTNS-native coefficient construction after ingress;
- full strict Windowed Fractional Canonization (WFC);
- UCC-governed certified decisions;
- adaptive certified rebuild;
- matched-depth fairness control;
- forbidden-arithmetic and Excel-input audits;
- reproducible workbook, CSV, JSON, trace, manifest, and settings-signature evidence.

The v28 protocol is not the mathematical theory itself. It is the frozen implementation and evidence-validation protocol used to enforce the manuscript's computational claims.

## Historical Terminology

The original v28 document uses legacy terminology, including:

- Certified Path;
- Non-Certified Path;
- Adaptive Certified Rebuild;
- Matched-Depth Fairness Control.

The final manuscript adopts the more formal terminology:

- FDNC: Fixed-Depth Native Construction;
- UCAC: UCC-Certified Adaptive Construction;
- MDNC: Matched-Depth Native Control.

The mapping between legacy and publication terminology is given in:

`v28_publication_nomenclature_addendum.pdf`

## No Modification of Historical Evidence

The publication-nomenclature addendum is editorial and interpretive only. It does not modify:

- algorithms;
- scripts;
- input files;
- output artifacts;
- campaign settings;
- evidence records;
- SHA-256 hashes;
- PythonApplication157.zip;
- btns_m10_output_157.zip;
- btns_m10_stress_output_157.zip;
- workbook_ready_tables_157.zip.

## Files

- `Script_Contract_v28_original.pdf`  
  Original frozen implementation protocol.

- `v28_publication_nomenclature_addendum.pdf`  
  Publication-nomenclature crosswalk from legacy v28 terminology to FDNC, UCAC, and MDNC.

## Recommended Citation Language

In the manuscript, v28 should be described as:

> the frozen v28 implementation protocol

or:

> the archived v28 execution-and-evidence specification

It should not be described as the theory itself.

The theory is the finite BTNS computational regime with native arithmetic, full strict WFC, UCC governance, and matched-depth fairness. The v28 protocol specifies how the PythonApplication157 implementation was required to execute and document that regime.
