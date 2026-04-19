# CRAFT Framework Overview Image

`craft_overview.png` — Figure 1 from the CRAFT paper showing the complete 3-stage pipeline.

To regenerate it, extract Figure 1 from the paper PDF:
```bash
# Using pdfimages (poppler-utils)
pdfimages -f 1 -l 1 -png datasets/CRAFT__TableRAG_Oct_2025.pdf static/images/craft_overview
# Rename the output to craft_overview.png
```