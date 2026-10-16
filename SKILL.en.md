---
name: ecommerce-poster-ver-3
description: Design ecommerce key visuals from product materials. Lock the requested placements and plan the smallest sufficient series with clear page hierarchy. Prioritize commercial information; Chinese priced pages draw on main-image price presentation, while English priced images are exempt. Group and rank functions, preview directions before producing the selected series, and retain model-tier recommendations and time optimization. Use for poster production and rule revisions.
---

# Ecommerce Poster ver.3

An independent version saved from ver.2 on 2026-10-14. Adds adaptive series length within fixed placements, commercial and functional information hierarchy, and main-image price presentation across aspect ratios. Keep ver.2 and the historical baseline unchanged, preserving the complete reference library and AI production boundaries. The version-editing round involved rule editing and static validation only, without image generation. Do not describe earlier manually iterated results as successful image tests of this version.

## ver.3 information planning entry

Extract user-fixed requirements in stage 1. Before ideation in stage 3, read [Series length and information priority](references/series-information-priority.md); reuse that plan in stages 4, 6 and 7. It is this version's sole detailed authority for series length, price emphasis and page hierarchy. Older references, history and examples must not override it.

- Split pages when type must shrink, several focal points compete, or unrelated themes are forced together. Do not add pages without independent content value.
- A fixed placement does not mean one image. Lock confirmed placement, aspect ratio, language and price visibility. Choose the smallest sufficient series based on useful information and visual capacity. Do not add other placements without authorization or turn every specification into a page mechanically.
- Authorized prices, price conditions, campaign dates and required qualifiers form the highest-priority information group. The amount is its first focal point; conditions, dates and qualifiers must remain clear and adjacent. Do not hide conditions or shrink text to make room. Functional pages without a displayed price need not repeat it.
- Every Chinese page displaying a price, regardless of aspect ratio, must first read the main-image composition rules and actually inspect applicable main-image price references. Transfer prominent amounts, clear price types, separate price areas and high contrast, reconstructed for the target ratio. Do not merely borrow colors, stretch templates, copy an entire red frame, or inherit reference discounts. English priced images need not borrow main-image price styling. Use restrained layouts suited to the brand, objective and known platform or placement, while preserving commercial priority and complete readable conditions. Do not equate English with Amazon or claim readiness for direct advertising placement.
- Group and rank other information by distinctive benefits, evidence strength and purchase relevance. Brand or functional education tasks may raise core-benefit priority, but commercial information still ranks highest on priced pages. Check completeness by information group; keep one primary focal point per page.
- A/B/C are real direction-selection previews, not the series page count. Before selection, generate three representative-page previews for the same task in each placement, with each direction's series plan. After selection, complete the remaining planned pages. Reuse an existing actual selection; do not repeat A/B/C for every page or default to three times the series length.

## Execution entry and model categories

Load only files necessary for the current stage; do not preload the next stage. For skill revisions, read only the [Iteration protocol](references/iteration-protocol.md) and affected rules; do not start poster production. If the user stops testing, save the current state and stop generation.

Use [Model routing](references/model-routing.md): D = deterministic tools; L = low-cost lightweight model; M = main model; H = flagship model; I = image generation model. Recommendations: GPT-6 Luna for L, with GPT-5.6 Luna as an older fallback; GPT-6.1 Sol for M; GPT-6 Astra for H. Actual support, reasoning levels and permissions depend on the runtime. These are recommendations, not implemented automatic switching. Without scheduling capabilities, use the current model with restrained reasoning and do not claim a downgrade occurred.

Hand off models only at meaningful task boundaries. Do not create an agent for a single confirmation, filename or tool wait. Do not copy entire conversations by default; transfer only current structured state and necessary files. Multi-agent authorization follows host rules; this skill does not authorize subagents automatically.

## Image production method — mandatory user rule, 2026-10-11

- All key visuals, including main images, themed posters and banners, must use AI image generation or editing tools. AI may redraw packaging from the original reference and generate the product, background, lighting and text together. The original remains the factual verification baseline. Redrawing does not authorize changes to product facts, bottle shape, logos or quantity, invented details, or automatic changes to the product viewing angle.
- Local scripts are not authorized to cut out products, composite backgrounds, or lay out text, prices or campaign rules. Do not replace AI output with Pillow, OpenCV, Canvas, SVG or other local drawing/compositing, including as a fallback for fidelity failures, text errors or time optimization. Do not proactively ask the user to switch to that method. Repair spelling, amounts, packaging and integration defects through targeted AI edits and recheck. If repair fails, save drafts and explain the limitation.
- Local deterministic tools may retrieve materials, back up originals, inspect metadata/dimensions, name/copy files, perform pure resizing or format conversion, assemble comparison previews and package files. Do not modify products, backgrounds, lighting or text, or remove image text under the label of export or refinement. Qualified previews may be exported to specification directly; preview marks, typos and other visual content require AI editing.
- These rules override older advice about original-pixel protection, script compositing, layered compositing, post-production typography and manual shadow correction in all stages and optimization files. Frozen baselines and historical tests are audit records only, not current production instructions. Preserve per-draft factual, packaging, scene-integration and clarity checks, and the human A/B/C selection gate.

## Gates always retained

- Six input groups: product images; specifications; primary/secondary selling points and evidence; prices; campaign rules; placement/dimensions/format. Fill known materials first and ask only for missing items. Never invent unknowns. Confirm price visibility separately for non-main-image placements. If specifications are unsettled, list aspect ratio, pixel dimensions and orientation and await confirmation.
- Compose two or more placements independently, each with real A/B/C representative-page previews and its own series plan. Preserve facts and ratio for the same representative-page task. Cropping one template does not replace independent creation. Verify at least two substantive differences within each group and across placements from the actual images.
- Define camera, perspective, product proportion and supporting surface for every draft. Take positive and negative quality constraints verbatim from the stage 4 rules as their sole source, then combine them with that draft's parameters. Do not inherit another draft's product proportion or tabletop. 8K is only a prompt target.
- Use the original product image as the factual baseline. AI packaging redrawing is permitted, but do not change angles, product structure, price campaigns or the basis for qualifiers without authorization. Report fidelity and source-resolution limits honestly.
- After showing qualified previews, stop at awaiting human selection. Produce only after selection; reuse an existing valid choice.
- Do not skip hard defects involving fidelity, facts or perspective to save tokens. Never claim ungenerated or unchecked work is complete. Do not infer calls or costs from file counts in test records.

## Read by stage

| Current task | Model category | Reading scope |
|---|---|---|
| 1 Materials and specification confirmation | L; escalate conflicts to M | [Stage 1](references/stage-01.md), [Brief template](references/brief-template.md) |
| 2 Product classification | L; escalate category/use conflicts to M/H | [Stage 2](references/stage-02.md), current fields of the [Analysis template](references/product-analysis-template.md), and the matching category playbook |
| 3 Strategy and communication objective | M | [Stage 3](references/stage-03.md) and the relevant category section |
| 4 References, A/B/C ideation and generation | L filters candidates, M decides, I generates | [Stage 4](references/stage-04.md); read main-image composition and themed rules only for the applicable use |
| 5 Human direction selection | L | [Stage 5](references/stage-05.md) |
| 6 Selected-direction production | M plans, I generates, D exports | [Stage 6](references/stage-06.md); reuse only necessary quality constraints already loaded in stage 4 |
| 7 Evaluation and correction | L screens, M accepts, H handles difficult issues | [Stage 7](references/stage-07.md), [Evaluation rubric](references/evaluation-rubric.md) |
| 8 Delivery | Mainly D, L organizes | [Stage 8](references/stage-08.md) |

Read [Shared quality and capability boundaries](references/shared-quality.md) once before first production; for evaluation alone, read relevant provisions. The complete baseline is stored in references/baseline-ver1.md for difference audits, not default runtime input. The [English routing entry](references/SKILL.en.md) uses the same stage rules.

## Reference library and reading limits

The primary library is assets/电商图片参考库_2026-10-10. On first use, read its usage and tagging instructions; subsequently reuse recorded paths and roles. Enter the appropriate product directory by placement and read only that group's representative-image list, reading notes and annotations. Open a small number of candidates per placement and actually compare at least two composition mechanisms. Do not present a local mechanism as the entire layout or inherit reference product facts or brand assets. Supplement from the older library only when the primary library is insufficient, recording why.

Use scripts or rg to locate headings, CSV rows or candidate files before reading relevant excerpts. Do not traverse the whole library or send its full contents to the model. Concurrent reads of independent small files may reduce waiting, but do not claim they reduce input tokens. After truncation, read only the missing section instead of resending the entire document.

## State and context management

Maintain one state file per project containing: stage/status; confirmed facts and sources; missing items/conflicts; user-fixed requirements; placement specifications and price visibility; series length and rationale; each page's primary/secondary information, price group and transition; information-to-page coverage map; product paths; main-image price references for Chinese priced pages (optional for English), placement-reference paths and roles; concept parameters; human selection; defects/corrections; and call records. Update only changes after new messages, without repeating the complete confirmed brief.

Save complete prompts, parameters and inspection records to files. In conversation, present conclusions, evidence and pending decisions only. Refer to state for repeated product facts rather than repeating long descriptions. Read current fields from an existing state file, not all historical records.

When materials first become readable and copying is permitted, save them to the project's input directory and record original paths. Check readability before generation or repair. After access failure, perform one targeted path check; do not repeatedly scan all of WeChat or a disk. Reference images must not displace the only product-image input. Prefer verified valid paths and do not replace the original fidelity baseline with generated packaging.

Use running handles and bounded waits instead of second-by-second polling; follow host requirements for progress updates. Use tools for deterministic copying, dimension checks, price arithmetic, naming, exports and manifests; the model explains anomalies only.

Rework only affected drafts and one to three explicit defects. Diagnose the failure before deciding on targeted AI repair or simpler backgrounds; do not gamble on repeated long prompts. Model upgrades cannot solve a tool's inability to lock pixels. Disclose capability limits and respect tool permissions.

## Generation time management

Before production, read [Time optimization](references/time-optimization.md). Follow: stabilize original inputs → consolidate confirmation → consolidate ideation → generate concurrently when tools allow → repair defects only → batch export. Verify actual concurrency, targeted AI editing and output capabilities first; do not assume service support.

Every placement still requires independently generated real A/B/C previews. Run independent tasks with bounded concurrency only when the host and tools permit; otherwise run sequentially. Concurrency does not imply a shared template or automatically authorize subagents. After selection, do not regenerate an entire image by default. Qualified previews may receive targeted AI refinement and specification export; repair hard defects before delivery.

Follow the image production method: products, backgrounds, text and rules are produced or edited through AI. Do not promise original-pixel locking or fall back to local script compositing/typesetting. Recheck necessary repairs. If factual and packaging accuracy cannot be achieved, save drafts and explain limitations instead of gambling on repeated calls.

## Version and validation

See [Token review](references/token-review.md) for actual observations and call breakdowns from the editing round. Model routing describes responsibilities and handoff fields. Structural checks alone do not establish successful skill-content testing; subsequent testing requires a separate user instruction.
