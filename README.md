# PUX Personas

An interactive D3.js visualization for exploring PUX (Patterns of User Experience) persona profiles.

## Overview

This repository contains the code and files for PUX Personas, an interactive data visualization tool. It is designed to accompany the paper "A Pattern Language for the Design of Diagrams" by Alan Blackwell.

### PUX  

PUX, or Patterns of User Experience, is a framework aimed at enhancing the interaction between users and diagrams within user interfaces. The Personas tool allows you to explore and compose user profiles across the 36 PUX experiences and 10 activities using interactive wind rose and pie chart visualizations.

## Usage

1. Clone this repository to your local machine.
2. Serve it with a local HTTP server (required for loading local JS/asset files):

   ```bash
   python3 -m http.server 8000
   ```

3. Open [http://localhost:8000](http://localhost:8000) in your browser.
4. Explore the interactive visualization to gain insights into the research paper's content.

## Directory Structure
- `PUX_data.js`: Full PUX paragraphs and ChatGPT4 generated summaries.
- `dataset.js`: Data structures and metadata for the visualization.
- `helpers.js`: A bunch of helper functions to keep the main script clean.
- `color_map.js`: D3.js colormaps to be swapped whenever needed.
- `index.html`: Main HTML file where the visualization is displayed.
- `viz_script.js`: Main visualization script.
- `heatmap.ipynb`: Heatmap plot script.


## Features

- Interactive D3 visualization.
- Provides a visual representation of concepts discussed in the research paper.
- Enhances understanding and engagement with the paper's content.

## Acknowledgments

Thanks to the Abstract Coffee Group* for their insightful discussions and valuable input during the development of this project.

---

\* *Note: not the actual group's name.

**References:**

1. Alan Blackwell, "A Pattern Language for the Design of Diagrams." [Read Paper](https://www.cl.cam.ac.uk/~afb21/publications/Richards-Diagrams-Chapter.pdf)

2. MIT License. [Read License](LICENSE)
