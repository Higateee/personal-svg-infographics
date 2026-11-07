# SVG reference analysis and generation rules

This public edition distills visual methods into written guidance. Original reference artwork is not distributed. The directions below are working design choices, not an instruction to reproduce any particular work. No image inspection is required to use the written rules.

## Shared principles

- Illustrations explain objects, actions, locations or relationships. Choose topic-specific people, products and environments when they improve understanding; use simple icons when the meaning is sufficient.
- Decide the main takeaway before placing modules. Distinguish title, section heading, label, body and annotation using size, weight, position and selective color.
- Select composition from content relationships. Repeated cards are suitable for parallel dimensions, not every kind of information.
- Keep a coherent palette and line family while allowing a main scene, comparison area, annotations and mini-diagrams to coexist.
- Increase useful detail rather than shrinking text. Remove redundant wording before reducing readability.

## Visual directions

### Warm orange narrative — default

Use for product stories, fieldwork summaries, packaging or everyday experiences. Combine a cream ground, deep brown text and selective orange accents. A topic-specific object or scene may connect smaller analytical sections through paths or annotations. Use asymmetry where it creates a clear reading order.

Suggested starting palette, not measured source values: background `#FFF7E6`, panel `#FFFDF7`, orange `#E88A2B`, light orange `#F5C477`, deep brown `#5B3823`. Soft gradients may describe volume; avoid ornamental effects competing with information. Change the subject and actions with the topic rather than reusing unrelated mascots or props.

### Blue editorial atlas

Use for materials, categories, object comparisons and information placement. Light backgrounds, blue outlines and restrained hatching can support precise object drawings. Align viewing angles, baselines and scale across comparable objects. Use columns for stable comparison fields and a vertical editorial column for layered explanations.

### Pale blue stage comparison

Use for development stages, changing roles and multivariable comparisons. Pair ordered nodes or an axis with aligned attribute fields. A theme-related object may shape the nodes. Stage count comes from the content. A curved line must not imply measured growth or superiority unless its scale has been defined.

### Purple interaction narrative

Use for user journeys, decisions, support and system processes. People, devices, document cards and dialogue may show what happens in a scene. Distinguish user actions from system responses. A journey path expresses sequence; a shared multi-track timeline expresses synchronization. Use purple for key actions and pale surfaces for supporting groups.

### Dark brown and gold mechanism

Use for product mechanisms and unfolding experiences. Draw sections, state changes, waterlines or direction arrows only where the topic requires them. Define the meaning of dashed and solid lines. Keep text and fine lines visible against dark gradients. Separate schematic relations from measured engineering values.

## Match the layout to the question

| Content relationship | Candidate composition |
|---|---|
| A product or person moving through situations | Main scene with linked explanatory sections |
| Different channels and their tasks | Row-wise process comparison |
| Parallel research dimensions | Module grid with content-dependent interiors |
| Locations, information and corresponding actions | Aligned columns with object annotations |
| Distinct object types | Atlas with consistent views and captions |
| A concept explained in layers | Vertical editorial column with local diagrams |
| Changing attributes over stages | Ordered axis with comparable fields |
| User steps and system support | Journey path or scene-based sequence |
| Synchronized event types | Multiple tracks sharing a defined timeline |
| Internal spatial mechanism | Section drawing with labels and direction arrows |
| Object states during use | Consecutive state drawings with explanations |
| Respondent or sample attributes | Faithful detail records with carefully defined summaries |

For respondent tables, retain each record and the source meaning of missing or ambiguous labels. Aggregate counts use a stated unit such as respondents, not an unstated mixture of people, children, devices or households. Do not infer identity, appearance, occupation, causality or non-use from absent information.

## Density, typography and drawing

For a 1600-unit-wide draft, suggested starting values are: outer margin 48–72, module gap 24–40, internal padding 20–32; title 48–64, section title 28–36, body 20–26, annotation 16–20; line height around 1.35–1.55 times font size. Main outlines may be 3–5 units, ordinary diagram lines 1.8–3, separators 1–1.5. These are adjustable suggestions rather than measurements or acceptance thresholds. For the 1920 × 1080 default, also consult layout-system.md and judge the actual viewing size.

Use an available readable CJK sans-serif for Chinese content unless another face serves the chosen direction. A serif title can suit the dark mechanism direction. Declare font families and fallbacks, check line breaks and keep text editable. Do not identify a font solely from outlined shapes.

Arrow starts, ends and labels must express an actual relationship. Keep leader lines near the relevant part and away from body text. Use labels and positional grouping together; do not make color carry all meaning.

## Using local reference images

1. Read these rules and select one main direction and composition.
2. If permitted reference artwork is available, inspect a main reference and one or two relevant structural references. Skip unavailable images and describe the actual inspection limit.
3. Carry over palette roles, hierarchy and drawing principles; derive objects, actions and module count from the new content.
4. Draw the information structure first, illustrations second and necessary surface detail last.

Do not combine several unrelated palettes just because several references are available. Do not promote a failed test output into the reference set without the user's selection.

## SVG implementation and review

Use an explicit canvas and viewBox. Group titles, modules and illustrations with readable unique IDs. Keep text as text and geometry as native shapes or paths. Use self-contained gradients, clips and markers when necessary; avoid whole-page embedded bitmaps, external fonts or web resources, scripts and foreignObject-dependent labels. Simplify texture into editable strokes rather than reproducing thousands of incidental points.

Render the full canvas, not a cropped system thumbnail. Inspect hierarchy, readability, overlaps, clipping, connectors and faithful content at the intended size. Validate XML and external-resource references. Compatibility with Figma must be checked by actual import when tools are available; otherwise report that it remains unverified. A valid SVG alone does not prove identical font rendering or complete editability in every application.
