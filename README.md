# NFL-Big-Data-Bowl-Hackathon-Dublin
This repository contains my submission for the NFL Big Data Bowl Hackathon Dublin 2025, focused on the relationship between linemen body type (height, and weight) and their performance on passing plays.
# NFL Big Data Bowl 2023 – Linemen Body Type & Performance Analysis

This repository contains my submission for the **NFL Big Data Bowl 2023 Hackathon**, focused on the relationship between **linemen body type (height, weight, BMI)** and their performance on passing plays.

## 📄 Project Overview
In NFL passing plays, success often depends on the hidden battles between offensive and defensive linemen.  
This analysis connects **physical traits** (height, weight, BMI) to **pass protection and pass rushing outcomes**, using the Big Data Bowl 2023 dataset.

### Highlights
- Offensive linemen are significantly heavier than defensive linemen.
- Each lineman position has a distinct body-type archetype.
- Heavier OL tend to allow fewer pressures; lighter DL tend to create more pressures.
- Four key visualizations demonstrate these patterns.

## 📂 Repository Contents
- `analysis_notebook.ipynb` – Jupyter notebook containing the full analysis code and visualizations.
- `report.pdf` – Written report (under 500 words) summarizing the findings and including the four graphs.
- `figures/` – Graphs generated from the analysis (PNG format).

**Note:** The raw NFL and PFF data files from the Big Data Bowl are **not included** in this repository due to competition licensing. See below for instructions to obtain the data.

## 🔗 Data Source
This analysis uses data from the **[NFL Big Data Bowl 2023](https://www.kaggle.com/competitions/nfl-big-data-bowl-2023)** competition on Kaggle.  
To reproduce the analysis:
1. Sign in to Kaggle and accept the competition rules.
2. Download the CSV files (players.csv, plays.csv, pffScoutingData.csv, tracking_weekX.csv, etc.).
3. Place them in a `data/` directory in this repository.
4. Update the file paths in the notebook if necessary.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/nfl-big-data-bowl-2023.git
   cd nfl-big-data-bowl-2023
