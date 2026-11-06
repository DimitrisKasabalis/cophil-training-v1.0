# CoPhil EO AI/ML Training

Live site: https://dimitriskasabalis.github.io/cophil-training-v1.0/

A 4-day advanced training on AI/ML for Earth observation, built for Philippine EO professionals under the Copernicus Philippines (CoPhil) programme. Each day pairs slides (Quarto) with hands-on Jupyter notebooks.

| Day | Theme | Sessions and labs |
|---|---|---|
| 1 | EO data & fundamentals | Copernicus and Philippine EO; AI/ML fundamentals; Python geospatial data; Google Earth Engine |
| 2 | Machine learning | Random forest land-cover classification; Palawan lab; deep-learning theory; CNN classification and transfer learning |
| 3 | Deep learning | U-Net segmentation; Sentinel-1 flood-mapping lab; object detection theory and lab |
| 4 | Advanced topics | LSTM time series; LSTM drought lab; emerging AI (foundation models); synthesis |

Also included: setup guide, Philippine EO links, cheat sheets, FAQ and glossary (`resources/`).

## Layout
- `dayN/presentations/*.qmd`: slides
- `dayN/notebooks/*.ipynb`: labs, with student and instructor versions where relevant
- `_quarto.yml`: site configuration
- `.github/workflows/publish.yml`: builds the site and publishes it to GitHub Pages

## Build locally
```bash
quarto preview
```

Author: Dimitrios Kasampalis ([LinkedIn](https://www.linkedin.com/in/dimitris-kasabalis/))
