# Metrocar Funnel Analysis

This project analyzes the customer funnel of **Metrocar**, a ride-sharing app, 
to identify where users drop off and how the product can be improved to increase 
ride completions and user satisfaction.

**Project Walkthrough Video**: [Watch here](https://youtu.be/aLqlIuNNjD4)

---

## Objective

Conduct a data-driven analysis to answer key business questions:

* Where do users drop off in the funnel?
* What is the impact of customer ratings?
* Is the product ready for dynamic pricing?

---

## Technical Plan

1. Connected to a PostgreSQL database containing 5 tables:

   * `app_downloads`
   * `signups`
   * `ride_requests`
   * `transactions`
   * `reviews`

2. Merged datasets to unify user behavior at the individual level.

3. Performed funnel analysis and exploratory analysis using SQL, Pandas and Seaborn/Plotly.

---

## Project Structure

``` bash
metrocar_user_analysis/
├── docs/
│   ├── metrocar_presentation.ppt.pdf
│   └── metrocar_report.pdf         
│
├── notebook/
│   └── metrocar_analysis.ipynb 
│
├──.gitignore
├── README.md                       
                
```

