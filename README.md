# CV

Tyler Weaver's CV, built with [RenderCV](https://github.com/rendercv/rendercv).

## Quickstart

Edit `Tyler_Weaver_CV.yaml` and push changes. The CI will compile the PDF and publish it to the `build` branch.

### Local rendering

```bash
pip install "rendercv[full]"
rendercv render Tyler_Weaver_CV.yaml --pdf-path cv.pdf
```

The compiled PDF is accessible at: https://tylerjw.github.io/cv/cv.pdf
