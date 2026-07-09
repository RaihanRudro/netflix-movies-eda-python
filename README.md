# Netflix Movies EDA with Python

## Project Overview

This project analyzes Netflix movie data using Python. The main focus is to investigate movie duration patterns, especially for movies released during the 1990s.

This project is part of my data science learning journey after completing Introduction to Python and Intermediate Python.

## Objectives

- Load and inspect Netflix movie data
- Filter the dataset to include only movies
- Analyze movies released between 1990 and 1999
- Visualize movie duration distribution
- Identify the most frequent movie duration
- Count short action movies released in the 1990s

## Tools Used

- Python
- pandas
- matplotlib
- Jupyter Notebook
- GitHub
## Key Findings

- Most Netflix movies released in the 1990s had durations around the 90 to 120 minute range.
- Based on the histogram, the approximate most frequent movie duration in the 1990s was around 100 minutes.
- There were 7 short action movies released in the 1990s with a duration under 90 minutes.
- Filtering and visualization helped narrow the dataset from all Netflix titles to a specific decade, content type, and genre.

  ## Visualization

The histogram below shows the distribution of Netflix movie durations for movies released in the 1990s.

images/duration_distribution_1990s.png

## What I Learned

Through this project, I practiced the basic data analysis workflow using Python.

Key skills I improved:

- Loading CSV data using pandas
- Inspecting a dataset with `head()` and `info()`
- Filtering rows based on conditions
- Selecting specific columns for analysis
- Filtering data by year range
- Creating histograms with matplotlib
- Using conditional filtering to answer project questions
- Communicating findings clearly in a GitHub README

## Project Structure

```text
netflix-movies-eda-python/
│
├── data/
│   └── README.md
│
├── images/
│   └── README.md
│
├── notebooks/
│   ├── README.md
│   └── netflix_movies_analysis.ipynb
│
└── README.md
```

### Folder Description

- `data/`: Contains information about the dataset. The raw dataset is not included because redistribution may be restricted.
- `images/`: Reserved for charts and visualizations created during the analysis.
- `notebooks/`: Contains the completed Jupyter Notebook for the project.
- `README.md`: Provides the project overview, objectives, tools, findings, and learning outcomes.

## Current Status

Project completed.

Completed tasks:

- Completed the DataCamp project successfully
- Uploaded the completed analysis notebook to GitHub
- Added key findings and learning outcomes
- Documented the project structure
- Documented dataset sharing restrictions

Final polish remaining:

- Add visualization image to the `images` folder
- Add final README polish before sharing publicly

