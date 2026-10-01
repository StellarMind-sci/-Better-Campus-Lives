# Annoying PPTs — universal single-file import

This file combines the universal skill and its references. Import the folder on platforms that support Agent Skills. If the platform has a short custom-instruction field, paste CORE-PROMPT.md there and upload this full file as a knowledge document when supported.

# Annoying PPTs · universal edition

Help a user make a credible, visually strong university presentation from a short request. This skill is platform-neutral: use the slide, document, image, search, and file tools actually available in the host environment. Do not assume any particular API, plugin, software installation, or filesystem path.

## Determine the job before the look

1. Classify the output as projected 16:9 slides, a close-reading deck, portrait report, poster, or an edit to existing slides.
2. Identify the audience and the presentation's job: explain, report, persuade, demonstrate, narrate, introduce a person, or recruit. Use the Task routing section below. A file folder or contest name is a clue, not a sufficient classification.
3. Gather or infer topic, speaking time or page budget, user-provided material, compulsory sections, identity rules, language, and required format. Ask only about missing information that would alter the artifact or require invented facts. When no duration is given for a normal campus talk, use 6–8 minutes and about 8–10 slides as a visible starting assumption.
4. Choose a relevant style from the Visual recipes section below and a layout from the Page patterns section below. Honor the user's style choice over the default.

## Prepare content and storyboard

Read supplied files before paraphrasing them. If none are supplied, use available research tools to find trustworthy subject sources; request the required syllabus or references when the course context changes the deck. If reliable research and sources are unavailable, produce a provisional outline with labeled unknowns rather than unsupported factual slides. Maintain a distinction between user-provided facts, independently checked facts, design assumptions, and unknowns. Do not fabricate statistics, achievements, source quotations, historical events, interview answers, experimental results, or product validation. If a missing fact is essential, request it or show a clearly labeled placeholder.

Plan one audience question, one answer, and appropriate evidence for each slide. Use a story arc suited to the job instead of applying a universal table of contents. State claims plainly. Put units, dates, methods, and sources beside important numbers. Distinguish documentary photography from generated illustration, especially for history and science.

## Produce with available tools

- Prefer editable text, charts, shapes, tables, and diagrams. Keep substantial labels above decorative raster backgrounds. Photos and approved artwork may be images; a whole-slide screenshot is a poor substitute for an editable slide.
- Use the host platform's presentation editor or a suitable PPTX/PDF generation library if available. If it supports rendering, render every page. If it does not, produce a detailed page-by-page specification and say what artifact could not be created. Never claim a file exists without checking it.
- Select or generate visuals for a specific explanatory role. Describe subject, style, composition, aspect ratio, and empty area reserved for slide text; avoid asking an image model to draw words, logos, charts, or precise scientific labels. Do not reuse watermarked reference screenshots as assets by default.
- Apply the Quality checks section below after each draft and after revision. Inspect at the size in which the audience will see the work. Repair unreadable type, low contrast, overflow, cropped content, inconsistent icon families, misleading charts, and missing citations.

## Deliver

For a projected or close-reading deck, provide an editable PPTX and rendered preview when supported. For a portrait report, provide a portrait PDF and an editable source format available on the host or requested by the user; do not force it into PPTX. For an edit, preserve the requested source format. Otherwise provide the strongest supported artifact plus the complete page plan. Include a short note explaining intended audience, chosen style, source coverage, important assumptions, and missing evidence. Speaker notes, a source slide, or a reference list should preserve citations without overcrowding the visible pages.

The attached recipes were derived from a university presentation collection containing 68 reference images, 56 PPTX pages, and 31 PDF pages. The collection includes low-resolution montages, flattened slides, and a portrait report. These observations inform design choices; no source file is required at runtime. See the Reference corpus section below for provenance and limitations.
---

# Task routing for university presentations

Use this file after the entry skill has identified the requested artifact. A deck may match more than one row; route by the audience's decision first. The style is a recommendation, not a rule.

## Determine the artifact

| Artifact | Typical use | Default |
| --- | --- | --- |
| Projected 16:9 deck | Classroom talk, defense, live pitch | Large type, limited detail, spoken explanation |
| Close-reading deck | Judges read on screen or receive the PDF | Moderate detail, evidence labels, more source notes |
| Portrait report | Career plan or written project report | Reading typography, page numbers, contents, no forced slide rhythm |
| Poster or announcement | Event publicity, recruitment | One hierarchy and one clear action |
| Existing deck edit | User supplies slides | Preserve factual content and required brand, diagnose visual problems first |

Do not treat `竞赛` as a style. A scientific specimen entry, AI demo, agricultural machine, and social enterprise pitch require different evidence and visual language.

## Route by the communication job

| Use case | Audience question | Core evidence | Suggested arc | Visual families |
| --- | --- | --- | --- | --- |
| Classroom explanation or reading report | What should I understand and remember? | Definitions, examples, diagrams, reading citations | Hook → main idea → 2–4 explanations → example → recap | Academic blue-white, restrained thematic |
| Experiment, survey, or course project | What was tested and what was found? | Method, sample, observations, limitations | Question → method → results → interpretation → limits | Academic blue-white, data report |
| Research proposal or thesis defense | Is the question worthwhile and method sound? | Literature, research gap, design, findings | Problem → prior work → method → evidence → contribution → limits | Academic blue-white; avoid decorative drama |
| History or cultural narrative | What happened, why, and why does it matter? | Dated records, maps, photographs, attributed quotations | Time and place → actors → turning points → consequence → interpretation | Historical navy-gold, parchment red-brown, cultural heritage |
| Civic or ideological education | How do sources support the theme? | Original documents, era context, verified images, contemporary connection | Context → source → interpretation → present-day relevance → reflection | Parchment red-brown; documentary |
| Student group or service report | What was promised, done, and changed? | Activity records, photos, counts with denominators, feedback | Goal → action → evidence → results → next action | Academic blue-white, data report, field green-white |
| Subject or artifact competition | What is the work and why is it strong? | Object, process, comparison, judging criteria | Work → principle/story → making → evidence → distinctiveness | Match the discipline; specimen green when relevant |
| Innovation or entrepreneurship pitch | Is there a real problem and credible solution? | User problem, prototype, trial, comparison, team, plan | Problem → solution → mechanism → validation → adoption → team → next step | Deep tech, field green-white, product showcase |
| Self-introduction or election | Why trust this person for this role? | Relevant work, responsibility, results, feasible commitments | Identity → experience → role fit → specific plan → close | Personal career blue, campus brand |
| Career planning or job presentation | How does this path fit the person and evidence? | Career research, self-assessment, projects, gaps, milestones | Target → evidence → gap → action → checkpoints | Personal career blue; portrait report if reading |
| Project or organization introduction | What is offered and who benefits? | Cases, process, real photos, outcomes | Position → audience → offer → process → proof → contact | Product showcase, industry variant |
| Recruitment or event promotion | What is happening and what should I do? | Date, place, host, eligibility, action | Identity → benefit → essentials → call to action | Event-specific, high-impact but sparse |

Sample coverage is strongest for competitions, work reports, history, ideological subjects, career presentation, and project introduction. Research defense, ordinary course presentations, and event posters have little direct representation. Apply general clarity principles rather than pretending the collection supplied a template for those cases.

## Adjust page budget

For a live talk, start with the speaking time and complexity. A routine 6–8 minute presentation often needs about 8–10 slides; a demo or chart-heavy argument may need fewer. Allocate more time to evidence than to cover, agenda, or thank-you pages. Judge reading decks may carry more annotated evidence; separate a readable presentation from an appendix when both are needed. Do not fill pages just to reach a count.

## Resolve ambiguity with minimal user effort

Ask when the answer changes: projected deck versus portrait report; competition evaluation criteria; mandatory school branding; missing personal or experimental facts; source materials that contradict. Infer routine preferences such as 16:9, Chinese language from a Chinese request, clean typography, and editable output when possible. Tell the user the inference in one line and proceed.

If the user supplies a reference image, use it as a style clue, then identify what actually transfers: palette, hierarchy, page rhythm, photo treatment, chart density, and motif. Do not infer permission to copy its people, text, watermark, logo, or copyrighted illustration.

---

# Visual recipes

These are reconstruction tokens distilled from the reference collection, not exact sampled source colors or licensed template assets. Treat any user's reference or school brand guide as stronger evidence. A style family controls the look; page patterns control the information. Never force a domain into one palette.

## Shared visual system

- Default canvas: 16:9 widescreen for projected slides. Start from a consistent safe margin around 4–6% of slide width. Align title, content, footer, cards, and charts to the same grid.
- Typography: one Chinese sans family for body and labels, optionally one contrasting display family for cover or section titles. Good fallbacks include Source Han Sans / Noto Sans CJK / Microsoft YaHei and system equivalents. Preserve editable text. Check font fallback on the target machine.
- Projected typography: title roughly 30–40 pt, section heading 24–30 pt, body 18–24 pt, chart labels generally 16 pt or larger. Small source notes may be smaller if still readable in the delivery format. Close-reading decks can be denser; do not call them projected slides.
- Hierarchy: one focal point, one primary claim, 2–4 supporting units. Use size, weight, placement, and contrast first; decoration comes after those. Keep a text-safe area over photos. Avoid routinely centering all content.
- Images: choose one role per visual: establish context, show a real object, explain a mechanism, prove a result, or carry atmosphere. Documentary photos need provenance. Generated scenes should be clearly illustrative where a viewer could mistake them for a historical or scientific record.
- Charts: choose by question. Change over time → line or columns; ranking → sorted bars; composition → stacked bars if totals matter; process → flow; spatial claim → map with legend; mechanism → labeled diagram. Avoid 3D pie charts and misleading truncated axes.
- Effects: one coherent system per deck. Gradient, shadow, glow, paper texture, and motion should improve separation or attention. Reduce effects on dense evidence pages. No effect may compromise contrast, source labels, or chart truth.
- Motion: use reveals only to control teaching or show a causal sequence. Prefer simple fades or ordered builds. Keep diagrams understandable in a static PDF as well.

## 1. Academic blue-white

**Use for:** teaching, reading reports, research, course work, career reports, formal campus presentations. **Reference evidence:** the portrait career report and blue-white report montages.

**Palette:** paper `#F7FAFE`, ink `#243447`, university blue `#164F91`, light blue `#DCEAF7`, optional teal `#3F8C9E`. If an official school palette exists, substitute it. Use blue for structure and emphasis, not a full blue fill on every page.

**Type and grid:** sans text; restrained serif may be used for a history or literature title. A clean two-column grid suits claim/evidence. Tables need generous row height and visible headers. Section pages can use a large numeral and short title. Projected slides should keep paragraphs short; a dense written report gets a separate portrait layout.

**Visuals and effects:** real campus, lab, or field imagery with natural color; thin lines, pale panels, small icons from one family. Limit gradients to cover and section transitions. A title band or colored left rail creates continuity. Charts use one saturated series plus gray comparison series.

**Avoid:** eight tiny panels on a projector, decorative skyline under every chart, excessive full-width blue bars, generic academic icons replacing actual findings.

## 2. White-ground data report

**Use for:** work summaries, club reports, surveys, experiment results, annual plans. **Reference evidence:** green, blue, and red work-report image montages.

**Palette:** neutral `#FFFFFF` / `#F4F6F7`, dark text `#263238`; pick one domain accent such as green `#2D6A46` or blue `#205B9B`, plus one warning or milestone accent `#D98B38`. Do not use red, green, yellow, and blue equally unless the chart semantics demand them.

**Type and grid:** header 10–15% of page height, evidence field 75–85%, source/footer remainder. Use a 12-column logic or simple halves/thirds so metrics and graphics align. One chart can occupy 50–70% of the page; smaller cards should explain rather than repeat it. Put a conclusion above the chart.

**Visuals and effects:** crisp charts, sparse icons, one radius and shadow depth across all cards. The visual story is comparison: baseline, current value, difference, and interpretation. Tables need units and comparable columns. Crop certificates or documents around the actual proof, with a caption and date.

**Avoid:** 3D pie charts, dozens of decorative circles, percentage bubbles without denominators, green arrows for a result whose direction is undesirable.

## 3. Deep-blue technology with gold lines

**Use for:** AI agents, software platforms, data systems, robotics, digital products. **Reference evidence:** the smart campus agent competition deck.

**Palette:** navy `#07183B`, deeper shadow `#04112A`, electric blue `#2475DC`, cyan `#68C9F3`, muted gold `#D7AD65`, white `#F5F9FF`. Let gold identify framing and milestones, cyan identify active technology, and white carry text.

**Type and grid:** large high-contrast sans headings. Use a fixed top label and a consistent bottom navigation line only if they aid orientation. Architecture pages are arranged by actual system layers; demo pages give a large central viewport and narrower explanatory column. Main labels remain editable above the background.

**Visuals and effects:** dark circuit or campus imagery at low contrast, thin luminous border, occasional glow behind a primary device or result, UI screenshots with legible crop. Cap glow to one focal region. For an architecture diagram, use straight or orthogonal connectors with labels; for function demos, show input → action → output.

**Avoid:** glowing every card, small gold body text, empty video frames, synthetic dashboard fragments presented as working product screenshots, decorative arrows with no process meaning.

## 4. Blue light-field product stage

**Use for:** connected devices, healthcare service, home technology, product demonstrations. **Reference evidence:** the elder-care competition deck.

**Palette:** dark cobalt `#09265E`, saturated blue `#0B65C8`, cyan `#42C7E7`, warm human accent `#F3A448`, white `#FFFFFF`. Use the warm accent sparingly for the human benefit or a verified result.

**Type and grid:** stage-like background plus a stable opaque reading surface. Problem pages juxtapose a human situation and a concise statistic; product pages show the actual interface or device at large size; validation pages return to plain charts and evidence. Keep people and devices away from crop boundaries.

**Visuals and effects:** horizon glow, subtle vertical light, photo foreground, controlled glass panel. Treat those as atmospheric layers. Convert explanatory text, captions, and chart labels to editable objects.

**Avoid:** same bright background on every slide, white type over the brightest area, stock older-adult imagery implying tested users, pie/donut charts without clear denominators.

## 5. Forest-green specimen and natural science

**Use for:** botany, ecology, specimens, biological evolution, field observation. **Reference evidence:** the spore-evolution specimen deck.

**Palette:** forest `#0D2E1B`, leaf `#4D8045`, grass `#A9C879`, ivory `#F4F0DF`, restrained gold `#D6BB77`. Use dark-green atmosphere on cover/section pages; lighter evidence panels support scientific detail.

**Type and grid:** a descriptive title, specimen panel, annotation panel, and a consistent caption system. Number objects and steps. Latin species names may use italic serif, while Chinese explanations stay sans. Use a recurring timeline or progression line only when scientifically justified.

**Visuals and effects:** macro photographs, specimen sheets, microscope images, scale bars, collection labels, and close-up comparison. Keep textures behind content. Aim image generation at botanical atmosphere, not taxonomic evidence or fake microscopy.

**Avoid:** decorative leaves that cover labels, false or unlabeled scale, claims inferred from an attractive photo, dense gold text on dark texture.

## 6. Field green-white validation

**Use for:** agriculture, environmental engineering, social practice, field trials, applied innovation. **Reference evidence:** the laser-weeding competition PDF.

**Palette:** light field `#F6FAF7`, dark green `#267449`, growth green `#6EAF64`, achievement orange `#D9843D`, body `#26362D`. Reserve orange for a real result, gap, or threshold.

**Type and grid:** clear headline claim at top, two to three evidence panels below. A comparison uses the same dimensions for all alternatives. Timeline pages name stages and dates; experiment pages pair setup, metric, and result. Evidence density can rise in an appendix, but live presentation pages need one proof at a time.

**Visuals and effects:** actual field photos, prototype photos, annotated process, result chart, certificate crops. White surfaces and green headers keep documents legible. Preserve experimental conditions and source notes. Use photography for physical proof, diagrams for mechanism.

**Avoid:** saying a trial proves broad commercial impact, displaying patent or contract screenshots so small no fact can be checked, headline percentages without method or baseline.

## 7. Historical navy and old gold

**Use for:** modern history, engineering history, places, people, journeys. **Reference evidence:** the eight-slide Jingzhang Railway story.

**Palette:** night navy `#0A1D31`, slate blue `#29445D`, aged gold `#C7A16A`, warm paper `#F3E8D6`. Gold carries major milestones and titles, not body paragraphs.

**Type and grid:** a display serif or calligraphic title can establish period; all explanatory text uses an easy-to-read font. Alternate cinematic full-bleed chapter pages with clean evidence pages. Timeline, route map, portrait, archive image, and bridge/engineering cutaway each serve a specific question. Keep caption and date treatment consistent.

**Visuals and effects:** desaturated archive photography, subtle grain, controlled vignette, layered landscape or infrastructure imagery. If a generated image reconstructs a historic scene, label it as an illustration and anchor factual claims in dated sources.

**Avoid:** putting all text into AI-generated full-slide art, mixing eras without labels, pseudo-archive images passed off as originals, illegible small text on dramatic landscape.

## 8. Parchment red-brown documentary

**Use for:** modern Chinese history, civic education, political or commemorative themes. **Reference evidence:** the ideological-history image group.

**Palette:** parchment `#F2EAD7`, maroon `#83282C`, vermilion `#BD4233`, aged gold `#AD874F`, charcoal `#2F2C29`. For a solemn subject, maroon plus paper is usually enough; red need not fill the screen.

**Type and grid:** brush lettering or a display face only for cover and section title. Use modern body type, generous paragraph spacing, and small source captions. Organize arguments as event → source → interpretation → present relevance. Allow documentary imagery to breathe.

**Visuals and effects:** low-opacity paper grain, archival photo with date and source, subtle red cloth or seal motif where appropriate. Use a contemporary photograph only when it advances the argument. If an image is an illustration, mark it as such.

**Avoid:** watermarked screen captures, invented quotations, generic flags replacing evidence, heavy texture under long paragraphs, treating all red topics as identical propaganda style.

## 9. Warm cultural heritage and human story

**Use for:** craft, intangible heritage, community service, food culture, local history, people-centered projects. **Reference evidence:** warm brown, orange, and dark cultural entries within the competition image group.

**Palette:** rice paper `#F4EFE6`, walnut `#4A2E21`, clay `#A36A3C`, warm gold `#D9B96E`, optional red `#A74232`. Choose a light gallery style for teaching and a dark exhibition style for an immersive pitch, not both without a transition.

**Type and grid:** artifact or person is the hero. A chapter page may use a short poetic title; evidence pages use precise language, dates, geographic context, materials, process, and credit. Use a photo sequence for making and a comparison grid for before/after or variants.

**Visuals and effects:** close-up textures, hands at work, real objects, warm directional light, carefully cropped archive material. Framing can resemble a museum label but should keep captions readable. Use subtle paper texture or gold rule.

**Avoid:** making a cultural project look like a generic luxury product, decorative calligraphy on every sentence, unattributed portraits, visual effects that obscure the craft itself.

## 10. Personal career blue

**Use for:** self-introduction, election, career planning, job presentation. **Reference evidence:** blue city, personal profile, timeline, and career report samples.

**Palette:** clean white `#F7FAFE`, personal blue `#0B4F9D`, soft blue `#6EA4D7`, light border `#D9E8F7`. A school or organization color may replace blue. Highlight one concrete personal result with a warmer accent if useful.

**Type and grid:** portrait/identity cover, experience timeline, role or career requirements, evidence of fit, action plan. Show relevant projects at usable size rather than a wall of certificates. Pair each claimed strength with an example and outcome.

**Visuals and effects:** genuine portrait with consent, campus or workplace image, simple curved timeline or path. Use privacy-safe personal details. If the person has no photo, build an identity page with type and a meaningful project visual.

**Avoid:** generic skyline as a substitute for personal story, unearned “leadership” labels, irrelevant awards, role plans with no concrete actions.

## 11. Photo-led project introduction

**Use for:** project, organization, service, product, or campus activity introductions. **Reference evidence:** the project-introduction image group and maritime report sample.

**Palette:** choose a brand or domain color, then pair it with white and a dark readable text color. Outdoor service may use forest green; logistics may use marine blue; industrial technology may use slate and orange. Do not copy another company's brand.

**Type and grid:** large credible hero photograph for the cover; then use service overview, audience, how it works, cases, and contact/action. The photograph should show the actual context or object. Use modular cards only after the basic story is clear.

**Visuals and effects:** full-bleed image with a localized dark gradient behind the title, case photos with captions, simple process strip, proof metrics. Coordinate crop with text position. Avoid using the same hero image on every page.

**Avoid:** stock imagery that contradicts the project, a cover so photographic that the title disappears, many product features without user benefit or proof.

---

# Page patterns and layout formulas

Choose a page because it answers a question in the story. Numbers are starting proportions on a 16:9 slide, not rigid templates. Always adapt to the amount and type of evidence. Maintain consistent margins and alignment across the deck.

## Storyboard fields

Before layout, record for each page: audience question; one-sentence answer; evidence or source; page pattern; chosen visual recipe; any speaker note. This can remain internal for simple requests. Show it to the user when the deck is large, high stakes, or ambiguous.

## Patterns

| Pattern | Content contract | Layout formula | Typical failure |
| --- | --- | --- | --- |
| Cover | Specific topic, presenter, affiliation/date only when needed | Hero visual or strong type occupies 55–70%; keep a clear title zone and quiet metadata edge | Long subtitle and multiple logos compete with title |
| Context / problem | What happened or who experiences the problem? | One dominant image or number in 45–60%; concise explanation and source alongside | Stock photo is presented as evidence |
| Agenda | Only if it helps navigation | 3–6 meaningful sections, ordered and named for the argument | Generic “background, analysis, summary” wastes a page |
| Section break | Why the next part matters | Large short heading, one visual cue, very little text | Dramatic art consumes too many pages |
| Claim + evidence | One conclusion with proof | Claim across top; chart, photo, quote, or document as the main body; interpretation to the side or below | Claim and graphic say different things |
| Concept explanation | What is the mechanism? | Labeled diagram or two-step comparison in the main field; a compact definition nearby | Decorative icons replace actual relationships |
| Process / method | What was done, in what order? | 3–6 phases on a time or flow axis; each phase has an action and output | Every phase receives identical icon and vague verb |
| Chronology / history | How did events lead to the outcome? | Dates and turning points on a route/timeline; relevant archive images near their dates | Timeline is a list of years without causality |
| Comparison | Why is option A different from B? | Equal-size columns, same criteria/units, visible winner or trade-off | Unequal scales or selected metrics hide weakness |
| Data result | How large or reliable is the result? | One chart 50–70% of slide, one headline finding, conditions and source | 3D chart, unlabeled denominator, tiny legend |
| Gallery / specimen | What does the object actually look like? | 1–4 high-resolution views with labels, scale, and context; explanatory text kept secondary | Montage is beautiful but evidence cannot be inspected |
| Interface / demo | What happens when a user acts? | Input → action → output, with real screenshots or frames at readable size | Blank video window in exported PDF |
| Validation / documents | What independently supports the claim? | Crop key details from trial record, certificate, contract, or testimonial; add caption/date | Full scan reduced until illegible |
| Person / team | Who did the work and why are they credible? | Photo/role/actual contribution; show relevant experience, not biography dump | Portraits and titles without contributions |
| Plan / roadmap | What will happen next? | Phase, date, milestone, evidence of completion, owner where useful | Ambitious arrow with no measurable checkpoint |
| Conclusion | What should the audience retain or do? | 1–3 earned takeaways and a specific next action when appropriate | New information appears for the first time on the ending |

## Deck rhythms

- **Teaching:** alternate concept, example, exercise or implication. Avoid ten consecutive definition slides.
- **Research:** problem, prior work, method, results, interpretation, limitations. Separate claims from speculation.
- **Competition pitch:** problem, solution, mechanism, evidence, differentiation, feasibility, team, next step. Move proof earlier if judges already know the category.
- **Historical story:** scene, actor, challenge, turning point, consequence, interpretation. Alternate atmospheric pages with evidence pages.
- **Personal story:** identity, relevant past action, role or career requirement, fit, future action. Evidence should grow more specific as the deck progresses.
- **Project report:** target, work performed, outcome, gap, next decision. Separate output counts from actual impact.

## Adapt for delivery format

Projected slides: one focal point, short copy, large labels, minimal footnotes. Dense close-reading deck: support deeper evidence, but maintain clear headlines and column logic. Portrait report: use headings, page numbers, contents, paragraphs, tables, citations, and reading order; do not force the projected-slide type scale. Poster: one message, essentials, and a visible action; avoid a miniature slide deck.

## Visual generation brief

When an image is needed, decide its role first. A useful internal image brief contains: subject; setting and era; documentary versus illustrative status; composition and camera distance; aspect ratio and crop; requested negative space; lighting and color recipe; exclusions such as text, logo, watermark, charts, and exact labels. Add labels and sourced data as editable slide objects afterward.

---

# Quality checks and evidence rules

Run these checks on the actual deliverable, not only on the plan. A PDF or image preview may expose errors that are invisible in source structure.

## Content and evidence

- Trace every consequential number, quote, date, scientific identification, historical image, award, qualification, market claim, and product result to the user's material or a checked source. Keep the source link, title, page, or file name available.
- Distinguish: fact; inference; projection; illustrative example; missing input. Label each clearly where ambiguity could mislead. A forecast must say it is a forecast and identify its assumptions.
- For experiment or survey results, include sample, method, unit, and comparison baseline when the claim depends on them. Do not convert an output count into an impact claim.
- For career and self-introduction decks, use only the individual's supplied experience. If the user supplied no personal evidence, build a structure with `待补充` prompts rather than invent a biography.
- Historical or scientific AI imagery is illustration. It must not appear as an archive photo, microscope image, certificate, test result, actual prototype, or evidence of an event.
- Check school names, competition names, dates, and logos against the user's source. Do not use a logo merely because a reference had one.
- Source notes can live near the visual, in speaker notes, or on a sources slide. Ensure the delivered format preserves them.

## Structure and writing

- Each live slide answers one audience question and has one primary takeaway.
- Titles communicate the content: `田间试验识别率为 92%` is stronger than `创新赋能未来` when the evidence supports it.
- Remove filler slogans, generic three-part claims, and repeated intros. A small result deserves plain language.
- Terms, abbreviations, time spans, and unit names remain consistent across pages.
- Page order forms an argument or teaching sequence. The conclusion follows from evidence already shown.
- Speaker notes can hold details that the projected page cannot comfortably carry.

## Visual and accessibility

- Render every page. Inspect cover, a dense evidence page, a page with charts, a photo page, and the final page closely; then scan the full deck for rhythm and consistency.
- Check a projector-size view: body text should normally sit around 18–24 pt on a 16:9 live slide, with chart labels legible from the back of a room. Readability takes priority over an arbitrary number.
- Ensure titles, text, legends, and annotations have sufficient contrast against actual backgrounds. Put quiet panels or overlays behind text over photos; do not trust a subtle shadow alone.
- Confirm no text, chart label, image, icon, citation, or footer overflows or is clipped. Check for font substitution on export and across machines when possible.
- Use a consistent grid, margin, radius, line weight, icon family, color semantics, and chapter navigation. A deliberate section break may differ.
- Avoid color-only distinctions; add labels or patterns for categories. Meaning should survive a static PDF and a grayscale print when appropriate.
- Do not enlarge a low-resolution source image beyond usable quality. If a montage is the only reference, reconstruct the layout and use new source material instead of stretching the montage.
- For video demos, provide a readable still frame or annotated sequence in exported files. An empty frame is a failed page.

## Chart honesty

- Choose a chart that answers the slide's question. Label axes, units, dates, categories, and data source.
- Use the same scale for side-by-side comparisons. Start bars at zero unless a different baseline is explicitly necessary and visually disclosed.
- Avoid 3D volume or area effects for numerical comparison; they distort perception.
- Show uncertainty, missing data, and forecast status when they affect interpretation.
- Recalculate percentages and totals from supplied numbers; verify the visual encodes the stated values.

## Editability and files

- Check whether titles, body text, charts, and diagrams remain editable in the requested PPTX. Background art may be raster, but claims should not be baked into it by default.
- Open or parse the output file and verify slide count and intended elements. Check the export preview for page size, order, and missing media.
- Deliver the file paths or links that actually exist. Do not claim successful compilation, rendering, or validation without seeing the result.
- Record material limitations: missing source evidence, unavailable image rights, unsupported animations, absent editable original, or media that could not be rendered.

## Reference hygiene

The source collection includes watermarked screenshots, compressed multi-slide montages, and flattened PPTX pages. Extract visual principles; do not redistribute those samples or treat their embedded facts as verified. When the user owns and explicitly provides a source deck for modification, preserve its required content and rights constraints while rebuilding only what the task authorizes.

---

# Reference corpus and interpretation notes

This skill's style recipes were derived from the user's university presentation collection. The source files are **not bundled** with either skill and are not required at runtime. These notes document why the recipes exist and where the evidence is weak.

## Inventory reviewed

| Original folder | JPG references | Observed emphasis |
| --- | ---: | --- |
| 历史&近代史类PPT | 5 | Ink wash, archive photo, map/tab motif, historic narrative |
| 汇报报告类PPT | 16 | Business-style data systems, work report dashboards, blue/green/red variants |
| 竞赛类PPT | 27 | Technology, ecological, agriculture, cultural heritage, social service, product pitch |
| 红色思政类PPT | 10 | Parchment, red-brown, historical image, brush title |
| 自我介绍&职业规划&竞选类PPT | 6 | Blue personal narrative, career evidence, job competition |
| 项目介绍类PPT | 4 | Photo-led organization, construction, product and outdoor lifestyle |
| **Total** | **68** | Many JPGs are multi-slide montages, not source PPTX files |

Four PPTX files contain 56 slides:
- `钢轨上的自主之路.pptx`: 8 pages, each built as a full-slide image. Dark navy, old-gold historical railway storytelling.
- `安徽师范大学生活服务助手-智能体大赛项目汇报.pptx`: 15 pages. Deep-blue and gold visual system held largely in slide background images; some demonstration slots use embedded videos. Static pages were inspected; the video clips were not decoded for this research.
- `植物标本制作大赛_孢子演化故事线PPT——精美版.pptx`: 10 pages, each built as a full-slide image. Forest-green scientific exhibition with specimen, microscopy, and an evolution thread.
- `颐路守护Elder Guard-独居老人智能监测家居系统-中国国际大学生创新大赛项目PPT.pptx`: 23 pages. Blue light-field backgrounds with some separate pictures and editable text. The visual background and content structure were inspected; picture-only previews do not represent exact PowerPoint text rendering.

Two PDFs contain 31 pages:
- `B1-7-草影无踪—新型单尾蝎式激光除草机(1).pdf`: 23 landscape pages. Field-green validation, prototype, trials, documents, commercial plan.
- `向逸飞25111701088.pdf`: 8 portrait pages. Career planning report with blue-white university identity. This document is stored under a competition folder but is a portrait report by artifact and reading behavior.

## What the samples do and do not prove

The collection strongly supports design recipes for competition pitches, formal reports, historic or civic narratives, personal career presentations, and project introductions. It offers little direct evidence for ordinary classroom teaching, research defenses, and campus event posters; those routes use general presentation principles and should adapt to new examples when supplied.

Several examples prioritize visual drama or information density over editability and back-row legibility. The skill deliberately retains their useful palette, motif, image treatment, and storytelling lessons while requiring editable claims, readable projection, factual sourcing, and honest charts.

The color codes in the visual recipes are suggested reconstruction values, not colorimetric extracts. Reference screenshots may carry third-party marks, brand identities, portraits, or watermarks. No permission to reuse these assets is inferred from their presence in the research collection.
