# How to Update — CKAN

**Project:** `CKAN`
**Category:** GOVERNMENT
**Domain:** government and civic technology
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
CKAN --version
CKAN check-update
```

### Applying Updates
```bash
pip install --upgrade CKAN
```

### Rolling Back
```bash
pip install CKAN==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
