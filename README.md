# DIKWP OncoEvidence OS

**DIKWP OncoEvidence OS** is an offline-first, research-only oncology evidence ledger, molecular signal mapping, clinical trial review preparation, and research gap mining system.

It is designed for literature review, molecular tumor board preparation, research evidence organization, and oncology knowledge-base governance. It is **not** a diagnostic system, not a treatment recommendation system, not a prescription system, and not a patient-specific clinical decision system.

## Quick Start

```bash
pip install -e .
oncoevidence analyze examples/sample_oncology_research_corpus.json --out outputs/demo
oncoevidence static-audit src --out outputs/demo/static_boundary_audit_report.json
```

## Outputs

- `oncoevidence_report.json`
- `dikwp_oncology_ledger.json`
- `evidence_matrix.csv`
- `claim_cards.csv`
- `molecular_signal_table.csv`
- `trial_review_queue.csv`
- `semantic_closure_report.json`
- `research_gap_report.md`
- `tumor_board_prep_note.md`

## Boundary

This project is for research evidence organization and expert-review preparation only. It must not be used for diagnosis, therapy selection, drug prescribing, trial eligibility determination, or patient-specific decision automation.

## Attribution

This project is part of the DIKWP open-source ecosystem inspired by Yucong Duan's DIKWP framework.
