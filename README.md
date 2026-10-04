# GHSA-xqgj-m5ww-8jcp - Local Privilege Escalation in Omarchy

**Found by:** Comr. Ibrahim Babagana Masba 🇳🇬
**Date:** October 2026
**Severity:** High
**CWE:** CWE-59, CWE-367 (TOCTOU Symlink Attack)

## Summary
Discovered a Time-of-Check Time-of-Use (TOCTOU) vulnerability in basecamp/omarchy install scripts where unsafe file operations allow symlink attack leading to Local Privilege Escalation.

## Impact
An attacker with local access can gain root privileges by exploiting race condition in /tmp file handling.

## Status
- Reported to maintainer
- GHSA issued: GHSA-xqgj-m5ww-8jcp
- Fix pending

## Researcher
Security Researcher | Bash Installer Auditor | Maiduguri, Nigeria
GitHub: @ibrahimbabaganamasba748-alt
