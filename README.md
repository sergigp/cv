# CV

Personal CV, written in YAML and rendered with [RenderCV](https://github.com/rendercv/rendercv).

## Files

- `Sergi_Gonzalez_CV.yaml` — the CV content, design and render settings (single source of truth)
- `rendercv_output/` — generated PDF, Typst and Markdown (ignored by git)

## Setup

```bash
pipx install rendercv
```

## Render

```bash
rendercv render Sergi_Gonzalez_CV.yaml
```

Output goes to `rendercv_output/Sergi_Gonzalez_CV.pdf`.

## Editing

- Content lives under `cv.sections` in the YAML. Markdown links/bold work everywhere.
- Theme and layout live under `design` (currently `engineeringresumes`).
- Search for `TODO` in the YAML for placeholders still to fill in.
- Schema reference: https://docs.rendercv.com
