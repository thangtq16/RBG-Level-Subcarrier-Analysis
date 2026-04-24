# LaTeX Project: RBG Level Subcarrier Analysis

This repository contains the LaTeX source code for the research paper/report on RBG (Resource Block Group) level subcarrier analysis in 5G NR.

## Project Structure

- `main.tex`: The main entry point of the document.
- `sections/`: Contains individual LaTeX files for each chapter/section.
- `tables/`: Contains TeX files for complex tables.
- `references.bib`: BibTeX file for bibliography management.
- `build/`: (Ignored by Git) Directory where all compiled outputs are stored.

## Prerequisites

To compile this project locally, you need:
1. A TeX distribution: **TeX Live** (Linux) or **MacTeX** (macOS).
2. **VS Code** with the **LaTeX Workshop** extension.

## Local Setup & Compilation

### Using VS Code (Recommended)
1. Clone this repository: `git clone <your-repo-url>`
2. Open the folder in VS Code.
3. Open `main.tex`.
4. Press `Ctrl+Alt+B` (Windows/Linux) or `Cmd+Alt+B` (Mac) to build.
5. The output PDF will be generated in the `build/` directory.

### Configuration
This project is configured to use an auxiliary build directory. If you are using VS Code, ensure your `settings.json` includes:
```json
"latex-workshop.latex.outDir": "build"