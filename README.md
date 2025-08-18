# 📓 Soccer Tracking Analysis — Presentation Notebook

A single, presentation-ready Jupyter notebook showcasing soccer tracking analysis (defensive lines, team shape/convex hulls, and possession-adjusted positioning).

## File
- `soccer_tracking_analysis.ipynb`

## What it shows
- Methodology and reasoning behind the analysis
- Visuals: defensive line depth and team compactness (convex hulls)
- Key takeaways and polished narrative

## Internship Context

- This project builds on my experience as a Soccer Analytics Intern at Inter Miami CF, where I worked under the Director of Analytics to process and analyze player tracking and match metadata. I developed Python scripts to automate data cleaning and transformation, implemented visualizations (defensive lines, convex hulls for team shape), and created performance reports to support tactical decision-making. This role combined my computer science background with applied sports analytics, strengthening my skills in data analysis, visualization, and communicating insights for a professional sports environment.

## Important note about data
This notebook uses **proprietary tracking/metadata JSON files** from my work at Inter Miami CF. Those files **are not included** in this repo for confidentiality. The notebook is provided **for review of the approach and results**, not for execution.

## How to view
- GitHub renders notebooks automatically. You can open the `.ipynb` directly in the repo UI.

## (Optional) Environment — only if you have your own compatible tracking data
If you wish to adapt the notebook with your data, you’ll typically need:
```
python>=3.10
pandas
numpy
matplotlib
scipy
mplsoccer
```
> Install with: `pip install -r requirements.txt` (if you add one)

## Author
**Gabriel Arrano** — [@gaarrano](https://github.com/gaarrano)
