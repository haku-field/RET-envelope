# CHANGELOG

All notable changes to RET-envelope are documented here.
This log records structural and boundary changes only.
Interpretation and fragment content changes are out of scope.

---

## [v0.2.1] – Structural Clarification

### Added
- Canonical separation of fragment types:
  - core
  - bridge
  - guard (core-adjacent, user-authoritative)
- Explicit AI-facing boundary definition (`ret-envelope.ai.yaml`)
- Clear delegation of canonical authority to user-defined guard fragments

### Changed
- `index.yaml` established as the single source of structural truth
- Guard fragments repositioned as core-adjacent rather than bridge-level
- RET-envelope clarified as non-semantic and non-authoritative

### Clarified
- RET-core acknowledged as an invariant premise, not indexed
- Fragment relations constrained to upward reference only
- AI interaction limited to reference and continuity roles

---

## [v0.2.0] – Preprint Alignment

### Added
- Alignment with RET-envelope preprint v0.2
- DOI-based citation via Zenodo
- Initial publication of structural index and envelope scope

---

## Notes

RET-envelope versions track boundary and structural changes only.
Fragment versions are tracked within their respective repositories.
