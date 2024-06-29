# Unveiling Patterns: Exploratory Analysis of Biodiversity Data

## Project Description
This project analyzes species observations across parks, revealing trends and insights to aid conservation efforts and enhance our understanding of biodiversity.

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Visualizations](#visualizations)
- [Conclusions](#conclusions)
- [Future Work](#future-work)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
This project aims to explore biodiversity data from various national parks, uncovering patterns and trends in species observations. The analysis focuses on understanding the distribution of species, their conservation status, and the overall biodiversity in these parks.

## Datasets
The project utilizes two main datasets:
1. **Observations Dataset**: Contains information about species observations in different parks.
2. **Species Info Dataset**: Provides details about species, including their category, common names, and conservation status.

## Data Cleaning
- Merged datasets based on `scientific_name`.
- Handled missing values, particularly in the `conservation_status` column.
- Ensured consistency in species names and park names.

## Exploratory Data Analysis
The analysis includes:
- Total number of observations per species.
- Number of observations per park.
- Distribution of observations by species category.
- Analysis of species by conservation status.

## Visualizations
Several visualizations were created to aid the analysis:
1. Bar chart of the number of observations per park.
2. Bar chart of the distribution of species categories.
3. Bar chart of species counts by conservation status.
4. Bar chart of observations by conservation status.

## Conclusions
The analysis provided valuable insights into the biodiversity across different parks, highlighting key trends and areas needing conservation focus.

## Future Work
- Perform temporal analysis to identify seasonal patterns.
- Conduct a detailed analysis of specific species with high or low observations.
- Examine park-specific conservation efforts.

## Installation
1. Clone the repository:
   ```bash
   git clone [repository link]
