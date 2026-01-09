# Exploring the Geography of Crime in Los Angeles

**Team:** Harshini Dinesh, Milo Leach, Samuel Castelein  
**Course:** DS 4200 - Fall 2024  
**Professor:** Xiaoyi Yang
**website** https://mleach05.github.io/DS4200_final_proj/
---

## About This Project

We analyzed crime patterns in Los Angeles from 2020 to 2024 to understand who is affected by crime, where it happens, and when people are most vulnerable.

**Live Website:** [[Link](https://mleach05.github.io/DS4200_final_proj/)]

---

## The Data

**Source:** [City of Los Angeles Crime Data](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)

- Over 1 million crime records from 2020-2024
- Includes crime type, victim demographics, location, and timing
- Cleaned and processed for analysis

---

## What We Made

**5 Visualizations:**

1. **Bar Charts** - Most common crimes each year (static)
2. **Bar Charts** - Crime rates by victim race (static)
3. **Interactive Histogram** - Victim age by crime type (Altair)
4. **Interactive Map** - Crime distribution across LA (Altair)
5. **Interactive Scatter Plot** - Victim age vs. time of day (D3)

---

## What We Found

- Theft and burglary are consistently the most common crimes
- Hispanic/Latino residents face disproportionately high victimization rates
- People in their 20s and 30s experience the most property crimes
- Crime concentrates in specific neighborhoods
- Younger people face more late-night crimes; older adults face more daytime crimes

---

## What's Next

- Target high-crime neighborhoods with focused prevention
- Develop culturally appropriate community programs
- Create age-specific safety education
- Study why certain areas have more crime
- Look at seasonal patterns and policy impacts

---

## How to Use

1. Clone this repository
2. Install: `pip install pandas matplotlib geopandas altair`
3. Open `docs/index.html` in a browser

---

## Project Files

```
├── data/                          # Crime data and maps
├── docs/                          # Website and visualizations
├── exploratory_analysis.ipynb     # Analysis notebook
├── README.md                      # This file
└── design_rationale.pdf           # Design explanations
```

---

## Tools Used

- Python (pandas, matplotlib, geopandas, altair)
- D3.js
- HTML/CSS

---

## References

1. [COVID-19 Impact on LA Crime Study](reference-link)
2. [Social Distancing and Crime Analysis](reference-link)

---

## Team Roles

**Harshini:** Dataset selection, 2 visualizations, website, design rationale  
**Milo:** GitHub setup, data cleaning, 2 visualizations, website  
**Samuel:** D3 visualization, website, design rationale

---

**GitHub:** https://github.com/mLeach05/DS4200_final_proj
