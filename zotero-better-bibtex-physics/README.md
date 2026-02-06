# Zotero + Better BibTeX (Physics / LaTeX)

A **minimal, stable Zotero setup** for generating **clean APS/PRL-style BibLaTeX output**
for physics PhD theses and long LaTeX manuscripts (Overleaf compatible).

This workflow prioritizes **correctness, key stability, and zero manual BibTeX editing**.

---

## What this setup guarantees

- Stable, human-readable citation keys
- Automatic BibLaTeX export (`.bib`)
- No local file paths (`file = {...}`)
- No abstracts, keywords, URLs, or access dates
- DOI-centric, APS-compatible references
- Safe for long theses and late-stage edits

---

## Toolchain

- Zotero Desktop
- Zotero Connector (browser)
- Better BibTeX for Zotero
- LaTeX + BibLaTeX (`biber` backend)

---

## Installation (one-time)

1. Install **Zotero Desktop**  
   https://www.zotero.org/

2. Install **Zotero Connector** (browser extension)  
   https://www.zotero.org/download/connectors

3. Install **Better BibTeX for Zotero**  
   https://retorque.re/zotero-better-bibtex/

Restart Zotero after installing the plugin.

---

## Reference ingestion (recommended practice)

- Prefer **Add Item by Identifier (DOI)** via the magic-wand tool.
- Use the browser connector on publisher pages (APS, arXiv).
- Avoid PDF-only imports when a DOI exists.
- Verify metadata (authors, year, journal) once per entry.

---

## Citation key policy

```text
auth + year + journal
