# <span style="color:blue">Delaware Valley Region School Atlas</span>

Welcome to the **Delaware Valley Region School Atlas**! This project provides a comprehensive visual representation of schools in the Delaware Valley region, helping users explore the distribution and types of schools in this area.

## Overview

The atlas plots schools on an interactive map, categorized by type and visualized using distinct color-coded markers:  
- **District Public**: 🟦 **Blue**  
- **Charter Public**: 🟩 **Green**  
- **Secular Private**: 🟪 **Purple**  
- **Religious Private**: 🟥 **Red**

This tool is designed to make it easy to identify and understand the geographical distribution of educational institutions.

---

## Features

- **Interactive Visualization**: Navigate through a dynamic map to view school locations and types.  
- **School Categories**: Focus on four primary categories for simplicity and clarity.  
- **Region-Specific**: Tailored for the Delaware Valley region.

---

## Installation

To set up the project locally, clone the repository and install the necessary dependencies:

### Cloning the Project
To clone this repository, run the following command in your terminal:

```bash
git clone https://github.com/jlb719ru/ruc-sacj-research-schoolatlas.git
```

### Installing Poetry For Dependencies
Run the following command to install Poetry (if you don’t already have it installed):

``` bash
curl -sSL https://install.python-poetry.org | python3 -
```
### Project Usage
1. Clone the repository and navigate to the project directory:

``` bash
cd ruc-sacj-research-schoolatlas
``` 

2. Install dependencies using Poetry:

```bash
poetry install
```

3. Run the project by executing the code in SACJResearch-SchoolAtlas.ipynb

## Exporting Atlas to HTML
To improve the presentation of the Jupyter Notebook in a browser, you can export it to an HTML file. This will generate a clean HTML document with only the title, description, and visualization included.

Command to Convert Notebook to HTML:
Run the following command in the terminal:

``` bash
jupyter nbconvert --to html --TemplateExporter.exclude_input=True --no-input --TemplateExporter.exclude_output=False SACJResearch_SchoolAtlas.ipynb
```

This command will:

Exclude code cells from the output.
Keep the title, description, and visualization for a clear and professional view.
The resulting HTML file will be generated in the same directory as your notebook.

## Contributing to the School Atlas
To contribute to the building of the Delaware Valley Region School Atlas, please check out the **CONTRIBUTING.md** file!