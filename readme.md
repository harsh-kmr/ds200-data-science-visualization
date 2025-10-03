
# DS200 Assignment: Data Science Visualization Project

This assignment is part of the **DS200 course** to demonstrates basic data analysis and visualization as required by the assignment.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/harsh-kmr/ds200-data-science-visualization/blob/main/visualizations.ipynb)

## Overview

This project visualizes and analyzes key economic data (GDP, Population, and GDP Per Capita) for major global economies, using scatter plots, box plots, and time-series graphs.

Project uses the data from "data.gov.in".

## Dataset
The data for this project is from data.gov.in, from the title: "Area, Population and Income of G-20 Countries Upto 2013".

**Data Source:**
<a href="https://www.data.gov.in/resource/area-population-and-income-g-20-countries-upto-2013#api" target="_blank">
    <img src="https://www.data.gov.in/_nuxt/img/logo.f9fcba1.svg" alt="data.gov.in logo" width="60" style="vertical-align:middle; margin-right:8px;"/>
    Area, Population and Income of G-20 Countries Upto 2013 (data.gov.in)
</a>




## Project Structure

```
ds200-data-science-visualization/
├── Area, Population And Income Of G-20 Countries upto 2013.csv
├── visualizations.ipynb
├── readme.md
└── plots/
    ├── Box Plots of Population, GDP, and GDP per Capita (2013).png
    ├── GDP over Time (2010–2013).png
    └── GDP vs Population (Top 5 Countries by GDP, 2013).png
```
## Visualizations

1. **Box Plots of Population, GDP, and GDP per Capita (2013)** - Comparative distribution analysis across G-20 countries
2. **GDP over Time (2010-2013)** - Temporal trends for USA, China, Japan, and India
3. **GDP vs Population (Top 5 Countries by GDP, 2013)** - Relationship between economic size and population

## Observations and Inferences

### 1. GDP over Time (2010-2013)

**Growth Trajectories:**
- **USA**: Stable growth from ~$14,500B to ~$16,200B (+11.7%) - maintained largest economy
- **China**: Rapid expansion from ~$6,000B to ~$9,000B (+50%) - steepest growth, closing gap with USA
- **Japan**: Decline from ~$5,500B to ~$5,000B (-9%) - economic contraction, particularly sharp 2012-2013
- **India**: Modest growth from ~$1,600B to ~$2,000B (+25%) - steady but slower pace

**Key Insights:**
- China's exceptional growth rate far outpaces other economies
- Japan's contraction reflects "Lost Decades" and post-2011 tsunami economic struggles
- Economic hierarchy remained unchanged: USA → China → Japan → India

---

### 2. Box Plots of Population, GDP, and GDP per Capita (2013)

**Population Distribution:**
- Heavily right-skewed with most countries having small populations (<300 million)
- Two extreme outliers at ~1,250M and ~1,360M (India and China)
- Median around 80-100 million

**GDP Distribution:**
- Right-skewed with significant economic disparities
- Extreme outliers at ~$16,500B (USA) and ~$9,000B (China)
- Most countries cluster in lower ranges ($1,000-2,500B)

**GDP per Capita Distribution:**
- Widest IQR (~$10,000-42,000), indicating vast differences in living standards
- Median at ~$25,000
- Fewer outliers, suggesting wealth per person varies within a broader but more defined range

**Key Insight:** Population and total GDP show extreme outliers (economic superpowers), but GDP per capita reveals that  dominance in absolute terms doesn't guarantee individual prosperity.

---

### 3. GDP vs Population (Top 5 Countries by GDP, 2013)

**Country Profiles:**
- **USA**: 320M population, $16,200B GDP → ~$50,600 per capita 
- **China**: 1,360M population, $9,000B GDP → ~$6,600 per capita 
- **Japan**: 127M population, $5,100B GDP → ~$40,100 per capita
- **Germany**: 81M population, $3,700B GDP → ~$45,700 per capita
- **France**: 66M population, $2,800B GDP → ~$42,400 per capita

**Key Insights:**
- No linear relationship between population and GDP
- China has 4.25× USA's population but only 0.56× its GDP
- Developed economies (USA, Japan, Germany, France) have higher GDP.
- Emerging economies (China) rely on scale to compensate for lower per-capita output


## Getting Started

### Prerequisites

```bash
pip install pandas matplotlib seaborn
```

### Running the Notebook

1. Clone this repository:
```bash
git clone https://github.com/harsh-kmr/ds200-data-science-visualization.git
cd ds200-data-science-visualization
```

2. Open the Jupyter notebook:
```bash
jupyter notebook visualizations.ipynb
```

Or click the "Open in Colab" badge at the top to run directly in Google Colab.

### Running Locally

The notebook automatically loads the dataset from the GitHub repository, so no additional setup is required. Simply run all cells sequentially.

## Author

- **harsh-kmr** ([GitHub](https://github.com/harsh-kmr))

## Citations

**Dataset:** Government of India. *Area, Population and Income of G-20 Countries Upto 2013*. Data.gov.in.  
**URL:** [https://www.data.gov.in/resource/area-population-and-income-g-20-countries-upto-2013#api](https://www.data.gov.in/resource/area-population-and-income-g-20-countries-upto-2013#api)


---

*This project was created as part of the DS200 assignment.*
