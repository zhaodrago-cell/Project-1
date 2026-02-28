# Project 1 — Replication (Phase 1)

## Track & Paper Choice
**Track A: The Causal Policy Track (Difference-in-Differences)**  
**Paper:** Card, D., & Krueger, A. B. (1994). *Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania.*

## Main Causal Question 
This paper examines whether New Jersey’s 1992 minimum wage increase affected employment in fast-food restaurants compared with neighboring Pennsylvania. Using a Difference-in-Differences (DiD) design, it compares the pre-to-post employment change in NJ (treated) to the same time change in PA (control), under the assumption of parallel trends.

## Data Source 
Data are provided as `njmin.zip` on David Card’s Berkeley data page. Download the zip and unzip into `data/raw/` to obtain `public.dat` (fixed-width) and `codebook` (column positions), plus survey files.

- Download: https://davidcard.berkeley.edu/data_sets/njmin.zip

## Repository Structure
- `data/raw/` — immutable raw data (or download instructions)
- `data/processed/` — cleaned outputs (CSV/Parquet)
- `notebooks/01_Data_Cleaning.ipynb` — loads raw data and displays `df.head()` (Phase 1 requirement)
