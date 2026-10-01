---
name: annoying-ppts-universal
description: Use on any AI platform when a student or campus group needs a PowerPoint presentation planned, created, revised, or visually polished for coursework, research, competitions, reports, career development, elections, history, or campus activities. Exclude prose-only tasks with no slide deliverable.
---

# Annoying PPTs · universal edition

Help a user make a credible, visually strong university presentation from a short request. This skill is platform-neutral: use the slide, document, image, search, and file tools actually available in the host environment. Do not assume any particular API, plugin, software installation, or filesystem path.

## Determine the job before the look

1. Classify the output as projected 16:9 slides, a close-reading deck, portrait report, poster, or an edit to existing slides.
2. Identify the audience and the presentation's job: explain, report, persuade, demonstrate, narrate, introduce a person, or recruit. Use [task routing](references/task-routing.md). A file folder or contest name is a clue, not a sufficient classification.
3. Gather or infer topic, speaking time or page budget, user-provided material, compulsory sections, identity rules, language, and required format. Ask only about missing information that would alter the artifact or require invented facts. When no duration is given for a normal campus talk, use 6–8 minutes and about 8–10 slides as a visible starting assumption.
4. Choose a relevant [visual recipe](references/visual-recipes.md) and [page pattern](references/page-patterns.md). Honor the user's style choice over the default.

## Prepare content and storyboard

Read supplied files before paraphrasing them. If none are supplied, use available research tools to find trustworthy subject sources; request the required syllabus or references when the course context changes the deck. If reliable research and sources are unavailable, produce a provisional outline with labeled unknowns rather than unsupported factual slides. Maintain a distinction between user-provided facts, independently checked facts, design assumptions, and unknowns. Do not fabricate statistics, achievements, source quotations, historical events, interview answers, experimental results, or product validation. If a missing fact is essential, request it or show a clearly labeled placeholder.

Plan one audience question, one answer, and appropriate evidence for each slide. Use a story arc suited to the job instead of applying a universal table of contents. State claims plainly. Put units, dates, methods, and sources beside important numbers. Distinguish documentary photography from generated illustration, especially for history and science.

## Produce with available tools

- Prefer editable text, charts, shapes, tables, and diagrams. Keep substantial labels above decorative raster backgrounds. Photos and approved artwork may be images; a whole-slide screenshot is a poor substitute for an editable slide.
- Use the host platform's presentation editor or a suitable PPTX/PDF generation library if available. If it supports rendering, render every page. If it does not, produce a detailed page-by-page specification and say what artifact could not be created. Never claim a file exists without checking it.
- Select or generate visuals for a specific explanatory role. Describe subject, style, composition, aspect ratio, and empty area reserved for slide text; avoid asking an image model to draw words, logos, charts, or precise scientific labels. Do not reuse watermarked reference screenshots as assets by default.
- Apply [quality checks](references/quality-checks.md) after each draft and after revision. Inspect at the size in which the audience will see the work. Repair unreadable type, low contrast, overflow, cropped content, inconsistent icon families, misleading charts, and missing citations.

## Deliver

For a projected or close-reading deck, provide an editable PPTX and rendered preview when supported. For a portrait report, provide a portrait PDF and an editable source format available on the host or requested by the user; do not force it into PPTX. For an edit, preserve the requested source format. Otherwise provide the strongest supported artifact plus the complete page plan. Include a short note explaining intended audience, chosen style, source coverage, important assumptions, and missing evidence. Speaker notes, a source slide, or a reference list should preserve citations without overcrowding the visible pages.

The attached recipes were derived from a university presentation collection containing 68 reference images, 56 PPTX pages, and 31 PDF pages. The collection includes low-resolution montages, flattened slides, and a portrait report. These observations inform design choices; no source file is required at runtime. See [corpus notes](references/corpus-notes.md) for provenance and limitations.
