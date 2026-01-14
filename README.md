# Python EDA — *The Good Place* (IMDb + Episode Data)

**Coursework Project: Python for Data Analytics**  
International Business School (IBS), Budapest

---

## 1. Project Overview

This project performs **exploratory data analysis (EDA)** in Python using episode-level data for *The Good Place*, combining:
- IMDb-derived information (ratings, votes, titles, descriptions, air dates)
- Episode metadata (writers, directors, season/episode structure, US viewership)

The notebook demonstrates a complete EDA workflow: data loading, cleaning, merging, descriptive statistics, visualization, and interpretation.

---

## 2. Key Questions Explored

The analysis focuses on questions such as:
- How do IMDb ratings vary across seasons and episodes?
- Which episodes are top-rated and which have the most votes?
- How does US viewership change over time?
- Are ratings correlated with votes, viewership, or description length?

---

## 3. Repository Structure

```text
python-data-analytics-imdb-eda/
├─ notebooks/
│  └─ eda_the_good_place.ipynb
├─ data/
│  ├─ raw/                # raw datasets (included)
│  └─ processed/          # optional cleaned outputs
├─ outputs/
│  ├─ figures/            # saved charts (optional)
│  └─ tables/             # exported tables (optional)
├─ report/
│  └─ eda_summary.pdf
└─ docs/
   ├─ AI_USAGE.md
   └─ ACADEMIC_INTEGRITY.md
````

---

## 4. Data

### 4.1 Included datasets

The raw datasets used in this project are **included in the repository** under `data/raw/`:

* `data/raw/the_good_place_imdb.csv`
* `data/raw/the_good_place_episodes.csv`

The datasets originate from Kaggle and are released under a **CC0 (Public Domain)** license, which permits redistribution and reuse without restriction.

Source reference:

* Kaggle notebook: *The Good Place Episode Data Analysis*
  [https://www.kaggle.com/code/bcruise/the-good-place-episode-data-analysis/notebook](https://www.kaggle.com/code/bcruise/the-good-place-episode-data-analysis/notebook)

Additional details on data sources and structure are provided in:

* `data/README_data.md`

---

## 5. How to run

### Option A — pip (recommended)

```bash
py -m pip install -r requirements.txt
```

### Option B — conda (reproducible environment)

```bash
conda env create -f environment.yml
conda activate python-data-analytics-eda
```

Then launch Jupyter and open:

* `notebooks/eda_the_good_place.ipynb`

---

## 6. Deliverables

* **Jupyter notebook:** `notebooks/eda_the_good_place.ipynb`
* **PDF export:** `report/eda_summary.pdf` (generated from the final notebook)

---

## 7. Notes on AI Usage and Academic Integrity

This project was completed as coursework and follows the course’s AI policy (Permitted Level: **Level 4**).

Full disclosure and integrity statements are available in:

* `docs/AI_USAGE.md`
* `docs/ACADEMIC_INTEGRITY.md`

---

## Author

Individual MSc coursework project
International Business School (IBS), Budapest
