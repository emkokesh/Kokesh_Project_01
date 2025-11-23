# Kokesh_Project_01

This repository contains my BIOS 6621 project for Assignment: R Markdown and Git.

## Directory structure

- `Background/`  
  PDF documentation that describes the dataset.

- `Code/`  
  All analysis code, including R scripts and R Markdown files used to clean data, run analyses, and generate figures/tables.

- `Reports/`  
  Knit reports (HTML) and other write-ups that summarize data checking, methods, and results.

- `DataRaw/`  
  Original raw data files as received from the investigators.

- `DataProcessed/`  
  Cleaned and derived data sets created from the raw data.

**What this version covers (Part 2):**

- Reads the data from `DataRaw/lead-iq-01.csv`.
- Produces a **boxplot** of IQ by smelter status.
- Produces a **formatted table** of descriptive statistics using `kable`.
- Includes **inline calculations** (sample size and means).
- Has multiple R code chunks.

**What this version covers (Part 3):**

- The change from 999 → 99 is made **in a code chunk**.
- All summaries and plots use the corrected `lead` data.
- Create a cleaned file in `DataProcessed/`.
- R chunk comment mentions the correction explicitly.