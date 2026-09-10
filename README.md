# Google Trends Analysis of Psychology-Related Searches

> **Master’s Psychology Research & Analytics Portfolio**
>
> This project was completed as part of my Master’s degree program in Psychology. It uses R and Google Trends data to examine public search interest in psychology-related terms across time, location, and search type.
>
> [View the complete Master’s Psychology Research & Analytics Portfolio](https://github.com/users/rickhegenbart/projects/1)

## Overview

This R Markdown project analyzes Google search-interest patterns for the term **“Psychologist.”** It examines trends over time, monthly patterns, geographic interest, and differences between searches for **“Psychologist”** and **“Psychiatrist.”**

The analysis also compares search interest in the United States and Canada and examines image-search trends for both professional terms.

## Analysis Questions

* How has search interest in “Psychologist” changed over time?
* Are there seasonal monthly patterns in searches for “Psychologist”?
* Which geographic areas show the highest relative search interest?
* How did search interest compare between the United States and Canada from 2015 through 2020?
* How do searches for “Psychologist” compare with searches for “Psychiatrist”?
* How do image-search patterns differ between the two terms?

## Methods

The analysis:

* Retrieves Google Trends data for selected keywords.
* Visualizes search-interest patterns over time.
* Calculates average monthly search-interest scores.
* Displays geographic search-interest data in an interactive table.
* Compares search patterns across countries and professional terms.
* Examines image-search interest for “Psychologist” and “Psychiatrist.”

## Tools

* R
* R Markdown
* `tidyverse`
* `ggplot2`
* `DT`
* `trendyy`
* `lubridate`

## Data

The analysis retrieves relative search-interest data through Google Trends using the `trendyy` R package.

Google Trends values represent relative search interest rather than the total number of searches. Results may vary if the report is rendered again because the underlying service and available trend data can change over time.

## Repository Contents

```text
├── README.md
└── trendyproj (1).Rmd
```

## Reproducing the Analysis

Install the required R packages:

```r
install.packages(c("tidyverse", "DT", "trendyy", "lubridate"))
```

Then open the R Markdown file and render it to HTML with an active internet connection.

## Project Status

This repository preserves the original analysis and can be expanded with a polished HTML report and GitHub Pages site.
