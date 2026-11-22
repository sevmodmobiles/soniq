# SONIQ — Brand assets (reference-locked, 2026-11-22)

## Source of truth
The user-approved raster image supplied in the SONIQ conversation (1536×486) is the visual reference. Do not generate new lettering or modify the wave/Q proportions. The SVG paths are a manual trace of the approved silhouette, not an exact mathematically verified vectorization. Neon bloom and reflection are raster effects and cannot be claimed pixel-identical in the SVG.

## Production files
- `soniq-logo-flat.svg`: transparent, high-contrast vector for UI and print.
- `soniq-logo-stage.svg`: same paths with controlled glow for the Live Stage dark interface.
- `soniq-logo-monochrome-final.svg`: white single-color version.
- `soniq-logo-traced-v1.svg`: preserved earlier vector candidate.
- `soniq-logo-transparent.svg`: legacy path; not referenced by the site after migration.

## Rules
- Preserve geometry and viewBox across all three production files.
- White wordmark, violet/pink wave and Q tail. Never dark wordmark on dark stage.
- Use relative local asset paths; do not embed a font or regenerate the logo.
- Maintain aspect ratio, minimum clear space equal to height of a wave bar, and avoid distortion.
- Source raster remains the arbiter for future refinement. Do not claim measured similarity without reproducible pixel comparison.
- No trademark clearance implied.
