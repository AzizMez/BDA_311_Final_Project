BDA-311 Final Project - README
================
Georgio Ghnatios, Aziz Mezraani
Fall 2023

# BDA-311 Final Project - MusicCamp

## Project Overview

As music enthusiasts, we wanted to create an innovation that improves
our community by understanding our user groups. Through interviews and
surveys, we identified three main frustrations:

1.  **Unorganized learning material** scattered across the internet.
2.  **Lack of a strong community** to connect with like-minded
    musicians.
3.  **Difficulties in sharing and publishing music work** effectively.

Using a **data-driven approach**, we employed various tools and
techniques, such as **R for clustering and NLP**, **persona maps to
understand our user group**, **Ideaboardz for brainstorming ideas**,
**Figma for prototyping**, and **Maze for user testing** through
descriptive and inferential statistics.

The final product, **MusicCamp** (inspired by DataCamp), is a **learning
platform for music** that provides guided courses, career tracks, and
structured learning paths while allowing users to earn XP and compete
with other learners. Additionally, it features a **community feed**
(similar to Reddit) for discussions and a **publish section** where
users can upload their work, announce live concerts, and connect with
their audience.

## Contents of this Repository

This repository contains all relevant files for the project, including
datasets, R scripts, and documentation:

### 1. **Data Files**

- `SurveyRawData.csv` – Raw survey responses collected from users.
- `Relation to Music Responses.csv` – Processed survey responses.
- `Relation to Music Responses Processed_Augmented.csv` – Augmented
  dataset used for clustering analysis.
- `music_data_cluster.csv` – Clustered data used in visualization.

### 2. **R Scripts**

- `Preprocessing code.R` – Script for cleaning and transforming the
  survey data into a structured format.
- `SuperHero_clusterAnalysis.R` – K-means clustering and visualization
  for user segmentation.
- `LDAScript.Rmd` – Topic modeling using Latent Dirichlet Allocation
  (LDA) for analyzing open-ended responses.

### 3. **Project Documentation**

- `BDA311_Final_Report.pdf` – The full project report including
  methodology, results, and insights.
- `README.Rmd` (this file) – Overview of the repository and its
  contents.

## Key Features of the Project

### Data Analysis & Clustering

- Conducted **k-means clustering** to segment users into four distinct
  groups based on their engagement with music.
- Used **heatmaps** to interpret cluster characteristics and identify
  the target user group.

### Natural Language Processing

- Applied **Latent Dirichlet Allocation (LDA)** to extract themes from
  user responses regarding music struggles.
- Identified key pain points: **lack of structured learning**,
  **difficulty sharing music**, and **limited community engagement**.

### Prototype Development & Testing

- Designed a **high-fidelity prototype** in Figma.
- Conducted **user testing via Maze** with 38 respondents.
- Identified UI improvements and user feedback for further development.

## Future Work & Improvements

- Integrate **AI-powered recommendations** for personalized music
  learning.
- Implement **live events and competitions** for better user engagement.
- Develop a **direct messaging** feature for community interactions.

For any questions or suggestions, feel free to contribute or reach out.
