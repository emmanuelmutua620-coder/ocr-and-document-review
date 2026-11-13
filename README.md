# OCR and Document Review

This repository documents a repeatable method for checking OCR-extracted text against a source document, correcting supported errors, and recording uncertain content for human review.

## Contents
- `templates/ocr-review-log-template.csv` — blank review log.
- `examples/fictional-ocr-review-example.md` — worked fictional example.
- `docs/ocr-review-procedure.md` — review process and decision rules.
- `docs/ocr-quality-checklist.md` — final QA checklist.
- `case-study/CASE-STUDY.md` — template for documenting your own work.

## Review principles
- Always compare the OCR output with the source image/document.
- Preserve the original meaning, order, and structure.
- Check names, dates, amounts, reference numbers, symbols, and punctuation carefully.
- Do not silently guess illegible characters. Flag uncertainty for escalation.
- Keep a record of meaningful corrections and the reason for them.

## Privacy
Only publish synthetic examples or documents that are public and safe to reuse. Never upload DDD/client scans, protected records, or confidential production samples.
