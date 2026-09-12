# TOGAF EA Practitioner Body of Knowledge — Markdown

Markdown conversion of the two source PDFs, split into the twelve documents they bundle.

| Set | Source PDF | Documents |
|---|---|---|
| [Set 1](Set-1/00-index.md) | `TOGAF-EA-BoK-Set-Distr1.pdf` (550 pp.) | 6 |
| [Set 2](Set-2/00-index.md) | `TOGAF-EA-BoK-Set-Distr2.pdf` (502 pp.) | 6 |

## Set 1 — TOGAF Standard, 10th Edition (Fundamental Content)

1. [Introduction and Core Concepts](Set-1/01-introduction-and-core-concepts.md)
2. [Architecture Development Method](Set-1/02-architecture-development-method.md)
3. [ADM Techniques](Set-1/03-adm-techniques.md)
4. [Applying the ADM](Set-1/04-applying-the-adm.md)
5. [Architecture Content](Set-1/05-architecture-content.md)
6. [Enterprise Architecture Capability and Governance](Set-1/06-enterprise-architecture-capability-and-governance.md)

## Set 2 — TOGAF Series Guides

1. [A Practitioners' Approach to Developing EA Following the TOGAF ADM](Set-2/01-a-practitioners-approach-to-developing-ea-following-the-to.md)
2. [The TOGAF Leader's Guide to Establishing and Evolving an EA Capability](Set-2/02-the-togaf-leaders-guide-to-establishing-and-evolving-an-ea.md)
3. [Enabling Enterprise Agility](Set-2/03-enabling-enterprise-agility.md)
4. [Using the TOGAF Standard in the Digital Enterprise](Set-2/04-using-the-togaf-standard-in-the-digital-enterprise.md)
5. [Integrating Risk and Security within a TOGAF Enterprise Architecture](Set-2/05-integrating-risk-and-security-within-a-togaf-enterprise-ar.md)
6. [Business Scenarios](Set-2/06-business-scenarios.md)

## How the conversion was done

- **Structure** — each file opens with the document title and a generated table of contents; headings come from the PDF bookmarks, with levels normalised to the section numbering (`## 3`, `### 3.3`, `#### 3.3.1`).
- **Figures and tables** — 185 diagrams were cropped from the pages at 2.6× and saved as PNGs under each set's `images/` folder, linked from the Markdown under their original caption. Scrambled diagram label text was removed from the prose.
- **Text repair** — the source PDFs carry zero-width spaces inside words (`suppor t`, `enter prise`); these were detected by glyph advance and removed. Ligatures were expanded, justified line fragments rejoined, and words hyphenated across line breaks reassembled.
- **Removed** — running heads and feet, page numbers, the per-page copyright line, and the printed tables of contents, lists of figures and back-of-book indexes (the generated TOC replaces them).
- **Footnotes** — collected per document into a `## Footnotes` section at the end of each file; the in-text markers remain attached to the word they follow (e.g. `architecturally significant.12`).

Not converted: the two text-only tables in *ADM Techniques* and one in *Introduction and Core Concepts* keep their content as flowing text rather than a Markdown grid, since they have no ruling lines to reconstruct.

The source documents are © The Open Group. This conversion is a format change of your own copies for personal use.
