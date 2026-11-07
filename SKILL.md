---
name: personal-svg-infographics
description: Create and revise native editable SVG infographics, comparison charts, flowcharts, structural diagrams and visual research presentations. Use for SVG deliverables with topic-specific illustrations and clear information hierarchy.
---

# Personal SVG Infographics

Turn research and design content into editorial SVG graphics with meaningful illustrations, readable text and a structure suited to the information.

## Read before working

- [Visual language](references/visual-language.md): hierarchy, illustrations, density and revision rules.
- [Layout system](references/layout-system.md): canvas, spacing and analytical or narrative composition.
- [Reference analysis](references/reference-analysis.md): visual directions, content-to-layout routing and reference use.

## Workflow

1. Extract the supplied content and identify comparisons, sequences, relationships or mechanisms. Preserve essential facts and ambiguity; do not invent missing data.
2. Choose a composition that expresses those relationships. Use a warm orange narrative direction unless the user or existing project specifies another style.
3. If the user supplies reference images, inspect selected originals in `assets/style-examples/` or the provided locations when inspection is available. Apply visual principles rather than copying subject matter or an entire composition.
4. Build topic-specific illustrations and explanatory mini-diagrams. Use consistent line weights, typography and palette roles. Do not force all content into identical cards or a central four-quadrant layout.
5. Generate native SVG with editable text and vector shapes. Default to 1920 × 1080 unless the task needs another canvas.
6. Render the complete canvas and inspect at the intended viewing size. Correct clipping, overlaps, unreadable labels and ambiguous connections.
7. Deliver the SVG and a raster preview when rendering is available. State any rendering or Figma import checks that could not be performed.

## Output requirements

- Valid XML, explicit `viewBox`, editable `<text>` / `<tspan>` and native vector elements.
- Group related elements and use unique meaningful IDs.
- Keep assets self-contained; avoid scripts, external resource requests and `foreignObject`-dependent text.
- Do not rasterize an entire layout to simulate editable SVG. If a requested photo is necessary, distinguish it from editable vector content.
- When revising, preserve approved elements and change the requested scope.
- Keep factual content and visual illustration separate. Do not infer causes or numerical values from decorative positions, curves or symbols.

## Optional references

The public distribution contains no reference artwork or respondent records. It works from the written rules without those files. Users may add their own permitted images locally; missing images are not an error and must not be described as inspected.

User-supplied styles and approved existing artwork take precedence over defaults. Do not automatically treat failed outputs as target references.
