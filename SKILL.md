---
name: xxd-panel-223
description: "Create XXD Panel 223 raster artwork: a faithful photograph paired with a vintage engraving miniature-motif collection, small separate motifs, about seventy to eighty percent paper, woodcut line, black plus one accent and sparse editorial type. Accepts one image or a directory batch and supports top-bottom, left-right, design-only and four-device wallpaper outputs; multiple ratios or exact sizes; prompt-generated, user-exact or text-free typography. Use whenever the user invokes xxd-panel-223 or asks for this engraved miniature-motif style."
---

# XXD Panel 223

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed design is a sparse collection of small independent engraved motifs, not one large scene. Motifs stay unconnected, with about 70–80% of the field left as intentional paper. Draw them as vintage engraving and letterpress or woodcut: dark contours, cut lines, hatching and black-and-white masses, with slight uneven ink. Each motif is usually black plus one accent taken from the source. Type is sparse, small and editorial. It is not a modern flat icon set, a realistic sketch, a photo outline, connected decoration, a filled frame or a fully coloured illustration.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-223/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-223-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks
