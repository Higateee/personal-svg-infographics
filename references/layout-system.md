
# SVG Layout System — v0.1

## 1. Canvas

Default presentation canvas:
- Width: 1920
- Height: 1080
- Aspect ratio: 16:9
- Use viewBox="0 0 1920 1080"

Adapt dimensions when the user provides a
different slide size or reference layout.

## 2. Grid and Alignment

- Use an 8-unit spacing system as a starting point.
- Establish page margins before arranging content.
- Align related modules to shared grid lines.
- Keep repeated cards and columns consistent.
- Avoid arbitrary positioning of text and icons.

## 3. Spacing

Default values for a 1920x1080 canvas:
- Outer margins: 64-96 units
- Major section gaps: 32-48 units
- Card gaps: 16-24 units
- Internal card padding: 20-32 units
- Text-to-icon gaps: 8-16 units

These are starting values, not rigid constraints.
Adjust according to information density.

## 4. Typography

Suggested starting sizes:
- Main title: 48-64
- Section title: 28-36
- Body text: 20-26
- Annotation: 16-20

Maintain readability at actual presentation size.
Do not shrink important text to force content to fit.

## 5. Information Density

- Prefer compact, organized arrangements.
- Remove unnecessary gaps before reducing font sizes.
- Keep related elements close together.
- Preserve visual breathing room around major groups.
- Avoid filling every available area with decoration.

## 6. Layout Modes

### Analytical Layout
Use for comparisons, research findings,
process diagrams, and structured information.

Characteristics:
- Clear grid
- Repeated alignment
- Consistent module dimensions
- Strong information hierarchy

### Narrative Layout
Use for concepts, product stories,
structural explanations, and design proposals.

Characteristics:
- Central illustration or visual metaphor
- Supporting information modules
- Directional relationships
- Controlled asymmetry

## 7. Visual Balance

- Balance illustration size with information density.
- Avoid large empty regions without a purpose.
- Use consistent visual weight across sections.
- Ensure arrows and connectors do not obscure text.

## 8. Layout Validation

Before delivery:
1. Check alignment.
2. Check module spacing.
3. Check text overflow.
4. Check visual hierarchy.
5. Check diagram connections.
6. Render the SVG and inspect the result.
7. Revise any detected issues.
