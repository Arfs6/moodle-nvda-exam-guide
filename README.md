# A Beginner's Guide to Moodle with NVDA

This repository contains a beginner-friendly guide for using Moodle with
NonVisual Desktop Access (NVDA). It was created to help staff of the
University of Jos guide blind students towards writing Moodle examinations
independently. The guide was written during an internship in the University's
ICT Directorate, in the Web Accessibility and Support (WAS) Unit.

## Download the latest PDF

[Download the latest PDF from GitHub Releases](https://github.com/Arfs6/moodle-nvda-exam-guide/releases/latest/download/moodle-nvda-exam-guide.pdf)

## Building locally

The document requires a LaTeX installation with the `qrcode`, `hyperref`,
`booktabs`, `enumitem`, and `microtype` packages. Run the compiler twice so
that the table of contents and PDF links are resolved:

```sh
pdflatex -interaction=nonstopmode -halt-on-error moodle-nvda-exam-guide.tex
pdflatex -interaction=nonstopmode -halt-on-error moodle-nvda-exam-guide.tex
```

The source is configured for A4 paper and uses black-and-white-safe styling.
The PDF provides a text-based document structure and navigation links; the
QR code on the title page is an optional shortcut to the download page.

## Help with NVDA

For NVDA problems, contact the NVDA users' mailing list at
[`nvda@nvda.groups.io`](mailto:nvda@nvda.groups.io) or visit
[`nvda.groups.io`](https://nvda.groups.io).

## License

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0
International License. See [`LICENSE`](LICENSE) for details.
