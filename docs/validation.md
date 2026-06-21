# Validation notes

This repository is documentation-first. There is no application build or automated software test suite.

## Appropriate checks

- open every `.docx` and `.xlsx` container and enumerate its content structure;
- extract text from the PDF and confirm its page count;
- parse Draw.io XML sources;
- decode/render PNG and JPEG artifacts;
- confirm local Markdown links resolve;
- compare suspected duplicate folders by relative path and SHA-256 hash;
- scan filenames and readable content for obvious credential patterns;
- check the repository for unexpectedly large files and generated caches.

## Interpretation limits

These checks establish file integrity and traceability between briefs and submissions. They do not establish business acceptance, correctness against undocumented stakeholder intent, a course grade, production readiness, or runtime behavior.

