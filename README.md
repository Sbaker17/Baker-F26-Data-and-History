# Proctor-F26-Data-and-History

This repository is a course workspace for practicing Python using [Melanie Walsh's](https://melaniewalsh.github.io/Intro-Cultural-Analytics/) open-access textbook *Introduction to Cultural Analytics & Python*, alongside homework assignments from Cameron Blevins' Spring 2025 course *HIST 4261 — Working with Data*. It supports HIST 280 / DH 200 — Data and History, Fall 2026.

It is **not** the original textbook repository. It's a trimmed-down, reorganized copy that pulls in only the data and text files needed for the units assigned in this course, and replaces Walsh's pre-filled practice workbooks with blank starter notebooks — so that students write and retype code themselves rather than starting from a completed example.

## Credit and sources

**Textbook:** Melanie Walsh, *Introduction to Cultural Analytics & Python*, Version 1 (2021). https://doi.org/10.5281/zenodo.4411250
Online textbook: https://melaniewalsh.github.io/Intro-Cultural-Analytics/
Source repository: https://github.com/melaniewalsh/Intro-Cultural-Analytics

The `data/`, `images/`, and `texts/` folders in this repository contain a subset of files drawn directly from Walsh's repository, copied here only to reduce the size of what students need to download and to keep this course's materials in one place. All original content, datasets, and instructional writing in the textbook remain hers. Please consult her repository directly for the complete book and dataset collection, and for licensing/reuse terms on the original materials.

**Homework assignments:** The assignments in the `Python-Homework/` folder are adapted from Cameron Blevins' Spring 2025 course *HIST 4261 — Working with Data*. Source repository: https://github.com/cblevins/sp25-data

## Repository structure

```
Proctor-F26-Data-and-History/
├── README.md
├── data/                    ← datasets referenced by textbook code (e.g. ../data/...)
├── images/                  ← image files referenced by textbook code (e.g. ../images/...)
├── texts/                   ← text files referenced by textbook code (e.g. ../texts/...)
├── Python-Notebooks/
│   ├── 1-Proctor-Template-Notebook.ipynb   ← blank starter notebook; duplicate this for every unit
│   ├── Markdown-Cheatsheet.html            ← quick reference for formatting Markdown cells
│   └── [LastName]-##-UnitTopic-Notebook.ipynb   ← student copies go here, one per unit
└── Python-Homework/
    └── ...                  ← assignments adapted from Cameron Blevins' sp25-data repository
```

`Python-Notebooks/` sits alongside `data/`, `images/`, and `texts/` at the same folder depth as Walsh's own chapter folders (like `02-Python/`) sit alongside her `data/` and `texts/` folders. This means relative file paths copied directly from the textbook pages (like `../texts/literature/...`) work without modification from inside any notebook in `Python-Notebooks/`.

## How to use this repository

1. Read the assigned chapter(s) on the [textbook website](https://melaniewalsh.github.io/Intro-Cultural-Analytics/).
2. In `Python-Notebooks/`, locate `1-Proctor-Template-Notebook.ipynb`.
3. Duplicate it, and rename the copy following the pattern `[LastName]-##-UnitTopic-Notebook.ipynb` (e.g. `Proctor-02-Python-Basics-Notebook.ipynb`).
4. Open the renamed copy in Jupyter and work through the chapter, writing your own code and notes rather than copying from a completed workbook.
5. When finished, save the notebook, export a copy as HTML, and submit both the `.ipynb` and the `.html` file to the corresponding assignment on Canvas.

Full student-facing instructions for this workflow are also posted separately on Canvas.

## License

Textbook and dataset content originates from Melanie Walsh's *Introduction to Cultural Analytics & Python* — refer to the [original repository](https://github.com/melaniewalsh/Intro-Cultural-Analytics) for its license terms. Homework content originates from Cameron Blevins' *sp25-data* repository, developed for his Spring 2025 course *HIST 4261 — Working with Data* — refer to that repository for its license terms. Course-specific materials (blank notebook templates, this README, and the assignment instructions) in this repository are provided for use by students enrolled in HIST 280 / DH 200 — Data and History, Fall 2026.
