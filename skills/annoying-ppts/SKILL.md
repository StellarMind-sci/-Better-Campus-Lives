---
name: annoying-ppts
description: Use when a student or campus group wants to plan, create, revise, or visually polish a PowerPoint presentation for coursework, research, competitions, reports, career development, elections, history, or campus activities. Do not activate for ordinary prose with no slide deliverable.
---

# Annoying PPTs · OpenAI edition

Turn a short request and its source materials into an audience-fit, visually coherent presentation. Reduce prompt writing for the user: infer routine choices, ask only for missing facts that materially change the deck, and explain assumptions briefly. The name is playful; the output should be clear and credible.

## Route the request

1. Identify the **artifact** first: projected 16:9 slides, a dense deck for close reading, portrait report, poster, or an edit to an existing deck. Do not silently convert a portrait report into projected slides.
2. Identify the **job**: explain, report, persuade, demonstrate, narrate, introduce a person, or recruit. A competition label alone does not determine the job or visual style.
3. Identify the audience, speaking time, required page count, language, school or event identity, source material, must-include facts, and editability needs. Use [task routing](references/task-routing.md) to choose a slide arc. If duration is absent, assume an ordinary 6–8 minute campus presentation and plan about 8–10 slides; change this when the material or user context warrants it.
4. Select a [visual recipe](references/visual-recipes.md) based on subject and evidence, then allow any user style override. Read only the relevant recipe and [page patterns](references/page-patterns.md); do not dump the whole catalog into the user's interaction.

## Make the deck

- Read every supplied source that matters before writing claims. If no sources are supplied, seek trustworthy subject sources with the tools available; ask for the required textbook, syllabus, or reference list when the course context materially affects the answer. If neither research nor source material is available, deliver a clearly provisional outline rather than unsupported factual slides. Separate supplied facts, externally verified facts, reasonable design assumptions, and missing evidence. Do not invent results, market sizes, credentials, quotations, historical details, or personal experiences. Mark indispensable missing claims as `待补充` in the working plan and ask for them when needed.
- Build a storyboard before laying out pages: one audience question and one answer per slide, with the evidence that will make the answer believable. Write slide titles as clear findings or topics, not vague slogans. Use the page pattern that matches the content, not a repeated card layout.
- Use available OpenAI presentation creation or editing capabilities to create the requested artifact. If a Presentations skill is available, follow it for deck editing and rendering. Use available image search or image generation when a visual improves comprehension; generated historical scenes must be labeled as illustrations and must never masquerade as source evidence. Ask image generation for visuals without baked-in text, logos, charts, or exact factual labels. Add editable labels in the slide.
- Prefer editable text, shapes, charts, and diagrams. User-provided logos, photographs, screenshots, and approved artwork may remain images. If an effect requires a flattened background, keep substantive claims and labels editable above it. Never substitute a screenshot of a whole slide for an editable slide unless the user explicitly requests a static reproduction.
- Source visuals deliberately: match subject, era, camera angle, crop, and text-safe space. Reusing a reference screenshot with its watermark, brand, portrait, or unlicensed artwork is not a default design method. Abstract its visual rules instead.
- Add citations near consequential statistics, claims, and borrowed figures, or on a compact sources slide or speaker notes where the audience can trace them. Preserve qualifiers, units, dates, and denominators.
- Render every page after creation, inspect it at presentation size, repair overflow, font fallback, low contrast, cropped subjects, inconsistent grids, and charts whose meaning changed. Apply [quality checks](references/quality-checks.md). A file existing is not evidence that the deck is visually usable.

## Interaction and delivery

For a brief request, start by stating the inferred task type, audience, page budget, and style in one short sentence. Ask at most the few missing questions needed to avoid a wrong artifact or fabricated fact; proceed with visible assumptions for routine preferences. Offer a compact storyboard for correction when the requested deck is large, high stakes, or source material conflicts. The user may request any style directly.

For projected or close-reading slide decks, default deliverables are an editable `.pptx` and a rendered preview when supported. For a portrait report, deliver a portrait PDF plus an editable source format supported by the host or requested by the user; do not force it into PPTX. For an existing deck edit, preserve the requested source format. Include a concise note listing the chosen style, source coverage, assumptions, and any unverifiable placeholders. If the requested format cannot be produced with available tools, deliver a complete page-by-page build specification and state the format limitation plainly. Never imply a PPTX or render was created when it was not.

The visual recipes were distilled from 68 reference images, four PPTX files, and two PDFs in a university presentation collection. Many references are low-resolution montages or flattened slides. Use the recipes as design guidance, not as transferable assets or factual sources. See [corpus notes](references/corpus-notes.md) when provenance or sample limitations matter.
