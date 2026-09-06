# SSV 26.1 Documentation

Documentation and reference materials for the **Cadence SSV 26.1 (SSV26.10)** release.

This repository contains the generated Cadence documentation set, including user guides, command references, HTML documentation, supporting files, indexes, and PDF manuals.

## Documentation

The repository contains documentation for several Cadence tools and components. The main documentation areas include:

- **Tempus** — timing signoff and analysis documentation.
- **Voltus** — power integrity, power analysis, and IR-drop documentation.
- **DBcom** — database/object reference documentation.
- **LEF/DEF** — LEF/DEF reference and user documentation.
- **CPF** — Common Power Format reference and user documentation.
- **IEEE 1801** — IEEE 1801 / UPF-related documentation.
- **Certus** — Certus-related user guides and references.
- **Tcl/text command references** — command and API reference material.
- **CUI documentation** — command-line/user-interface reference material.
- **Release notes, known-problem documents, migration guides, and supporting documentation**.

The documentation is organized into separate directories so that the original generated HTML structure and its supporting assets are preserved.

## PDF Manuals

Several major manuals are included as PDF files, including:

- **DBcom/DBcom.pdf** — DBcom reference manual.
- **tempusUG/tempusUG.pdf** — Tempus User Guide.
- **voltusUG/voltusUG.pdf** — Voltus User Guide.

The corresponding HTML documentation is also retained in the repository where available.

## Using the HTML Documentation

The HTML documentation is intended to be used as a local documentation set.

### Recommended method

1. Clone or download this repository.
2. Keep the directory structure unchanged.
3. Open the relevant table-of-contents HTML file in a web browser.
4. Navigate through the documentation using the built-in links.

For example, the Tempus and Voltus documentation directories contain their HTML pages, images, styles, indexes, and table-of-contents files.

> **Note:** GitHub's normal file viewer displays HTML source rather than running arbitrary HTML pages as a website. For the full interactive documentation experience, download/clone the repository and open the HTML files locally, or publish the repository through GitHub Pages.

## Git LFS

This repository currently uses **Git LFS** for two large documentation index files.

The LFS-managed files are:

- `docindex/71dae491d65a0499c4e79fad3eef4e_cis/_9.cfs`
- `docindex/71dae491d65a0499c4e79fad3eef4e_cs/_9.cfs`

This is defined in the repository's `.gitattributes` file.

**Git LFS is currently required to obtain the complete contents of these two files when cloning/downloading the repository.**

If the goal is to make the repository work without Git LFS, these two large index files can be split into smaller Git-tracked parts while preserving their original functionality, similar to the approach used for the INNOVUS251 documentation repository.

## Release Information

The repository's `doc.cfg` identifies the documentation release as:

```
Release=SSV26.10
```

## Repository Contents

In addition to the documentation itself, the repository contains:

- HTML documentation and table-of-contents pages.
- PDF manuals.
- Images, stylesheets, attachments, and other documentation assets.
- JSON/XML documentation metadata.
- Documentation indexes.
- Command references.
- Installation and configuration documentation.
- Release notes and known-problem/solution documents.
- Supporting and third-party information.

## Repository

This repository contains documentation collected for the **Cadence SSV 26.1 / SSV26.10** release.

For the original directory structure and complete documentation set, see the repository contents directly.
