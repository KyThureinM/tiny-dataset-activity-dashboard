# Tiny Dataset Activity Dashboard

A small Excel-based data storytelling project built from a simple household activity log.

This project compares **weekday vs weekend activity patterns** using a lightweight dataset and shows how even a tiny dataset can produce clear, relatable insights when it is cleaned, grouped, and visualized well.

## Project purpose

The purpose of this project was to explore how a small manually tracked dataset could be turned into a simple and engaging dashboard.

The analysis focuses on:
- comparing weekday and weekend activity patterns
- grouping activities into broader categories
- distinguishing between solo and social activities
- presenting the results through an Excel dashboard

This is a **small data storytelling exercise**, not a formal behavioural study.

## Dataset overview

The dataset records average daily time spent on different activities across two day types:
- **Weekdays**
- **Weekends**

Each activity is described using a small set of categorical fields such as:
- activity name
- activity category
- average hours per day
- interaction mode (solo or social)
- simple parent engagement flag

To protect privacy, the repository uses a **sample/anonymized version** of the data.

## Workflow

### 1. Data collection
A simple activity log was created to track average daily time spent on activities.

### 2. Data preparation
The raw data was cleaned and enriched using Excel and Power Query.

This included:
- standardizing labels
- grouping activities into broader categories
- adding simple descriptive fields for interaction mode and parent engagement

### 3. Analysis and dashboard build
Pivot Tables and Pivot Charts were used to create an Excel dashboard showing:
- weekday vs weekend activity patterns
- overall activity mix
- social vs solo distribution

## Key insights

A few simple patterns stood out:
- total tracked activity time increased on weekends
- games took the largest share of time overall
- creative and learning activities also increased strongly on weekends
- some screen-based activities were social rather than purely solo

The project shows that simple structure and clear visuals can make even a very small dataset meaningful.

## Tools used

- **Excel** for analysis and dashboard design
- **Power Query** for data cleaning and transformation
- **Pivot Tables / Pivot Charts** for aggregation and visualisation

## Repository structure

```text
tiny-dataset-activity-dashboard/
│
├─ README.md
├─ .gitignore
│
├─ data/
│  ├─ raw/
│  │  └─ activity_log_sample.csv
│  ├─ processed/
│  │  └─ activity_log_enriched.csv
│  └─ data_dictionary.md
│
├─ dashboard/
│  └─ tiny_dataset_activity_dashboard.xlsx
│
└─ assets/
   ├─ dashboard-overview.png
   └─ linkedin-carousel-preview.pdf 
```

### How to use this repo

1. Open dashboard/tiny_dataset_activity_dashboard.xlsx

2. Review the sample input data in data/raw/

3. Review the enriched data in data/processed/

4. Explore the dashboard sheet to see the final visuals

### Notes

This project was created as a simple example of:

- small data analysis
- Excel dashboard design
- practical categorisation and feature creation
- visual storytelling with everyday data

It is intentionally lightweight and designed for clarity rather than technical complexity.

This repository uses a sample/anonymized version of the dataset for privacy. It is shared as a portfolio project and not intended as an open data resource.
