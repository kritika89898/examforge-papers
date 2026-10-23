# examforge-papers

Question-paper PDFs for [ExamForge](https://exam-forge-coral.vercel.app), served through GitHub Pages at
`https://kritika89898.github.io/examforge-papers/papers/...`.

The catalogue (subject, year, exam type, branch) lives in the main ExamForge repo in `client/data/papers.json`;
each entry's `file_path` is relative to this repo's root.

## Extracted text

`text/` mirrors `papers/` with one JSON file per PDF: the text of each page, how it was obtained
(`text-layer` for digital PDFs, `ocr` for photos/scans via Tesseract after flattening uneven lighting),
the OCR confidence (0–100) and any rotation applied. It is used to build AI Studio's stored answers.
