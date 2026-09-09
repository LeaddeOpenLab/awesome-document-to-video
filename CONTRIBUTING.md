# Contributing a workflow

Contributions should help someone reproduce a useful business-video result. We welcome corrections, tested prompt patterns, document templates, comparison notes, and public examples.

## What to include

- A concrete use case and intended audience.
- The source format: PDF, PPTX, DOCX, Markdown, text, image, audio, or video.
- The exact reusable prompt or planning template.
- Model and tool names as shown by their providers.
- A `Last tested` date.
- A result link, screenshot, or clear description of the observed output.
- Known limitations and failed attempts.
- Attribution and the original source when the work is not yours.

## Suggested front matter

```yaml
title: SOP to multilingual training video
use_case: employee training
source_formats:
  - PDF
  - DOCX
models:
  - Leadde
tested: true
last_tested: 2026-09-09
result_available: true
```

## Quality rules

1. Do not describe an untested workflow as tested.
2. Do not claim ownership of third-party prompts, media, or outputs.
3. Separate exact prompts from reconstructed or inspired prompts.
4. Remove private company, customer, and employee information.
5. Prefer one complete, reproducible example over a long list of generic tips.

Place durable processes in `workflows/`, time-sensitive notes in `trending/`, and side-by-side evaluations in `comparisons/`.

