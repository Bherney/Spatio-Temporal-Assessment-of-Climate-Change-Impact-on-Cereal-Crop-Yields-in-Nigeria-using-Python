# Spatio-Temporal Assessment of Climate Change Impact on Cereal Crop Yields in Nigeria (Python)

This repository contains the analysis and visualization scripts for assessing the **impact of climate change on cereal crop yields (maize, sorghum, millet, wheat) across Nigerian states** under two climate scenarios:  
- **SSP3-7.0 (medium emissions)**  
- **SSP5-8.5 (high emissions)**  

The study evaluates yield projections for two future periods (**2021–2040** and **2041–2060**), compares state-level vulnerabilities, and identifies priority states for adaptation investments.

---

## Study Overview
- **Objective 1:** Analyze spatial variations in projected cereal yields under SSP3-7.0 and SSP5-8.5.  
- **Objective 2:** Compare vulnerability of Nigerian states to yield reductions across crops.  
- **Objective 3:** Determine priority states for climate adaptation by evaluating yield gaps between scenarios.  

**Data Source:** [CGIAR Adaptation Atlas](https://adaptationatlas.cgiar.org) 🌍  

---

## 📂 Repository Structure
- [**plots/**](plots/) → All generated plots (boxplots, maps, bar charts)  
- [**script/**](script/) → Jupyter Notebook / Python scripts for analysis  
- [**data/**](data/) → CSV and shapefiles (not included in repo if large)  
- [**README.md**](README.md) → Project documentation  

---

## Methodology

1. **Data Extraction**: Cereal yield data collected from CGIAR Adaptation Atlas for Nigeria’s 36 states + FCT.  
2. **Scenario Analysis**: Compared SSP3-7.0 vs SSP5-8.5 for two periods (2021–2040, 2041–2060).  
3. **Python Workflow**:
   - Data cleaning & structuring with **Pandas**  
   - Statistical summaries & boxplots with **Seaborn/Matplotlib**  
   - Yield gap analysis with **NumPy**  
   - Spatial visualization using **GeoPandas** & choropleth maps  

---

## Key Results (Highlights)

- **Highest negative yield gaps**: Plateau (−0.39), FCT (−0.36), Akwa Ibom (−0.33).  
- **Positive yield gaps (resilient states)**: Adamawa (+0.18), Yobe (+0.11), Jigawa (+0.08).  
- **Southwest states** (Oyo, Ondo, Osun, Ekiti) show moderate declines (−0.13 to −0.14), signaling emerging vulnerability.  
- Millet and sorghum in northern states show resilience, while maize and wheat are more climate-sensitive.  

---

## Output Visualizations
- Boxplot of Yield Projections → [View Here](plots/)  
- Spatial Distribution of Yield Gaps → [View Here](plots/)  

---

## How to Use

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/Spatio-Temporal-Assessment-of-Climate-Change-Impact-on-Cereal-Crop-Yields-in-Nigeria-using-Python.git
