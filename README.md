# Tres Sigmas: Automotive Data Analysis for Sustainable Mobility

## 🌍 Project Overview

A comprehensive data visualization and multivariate analysis project exploring vehicle performance characteristics and environmental impact using U.S. EPA Automotive Trends data (1975 - preliminary 2024). This research directly supports **Sustainable Development Goals 7 (Affordable and Clean Energy)** and **13 (Climate Action)** by analyzing fuel economy, CO₂ emissions, and technological advancements in the transportation sector.

## 👥 Team Members

- **Inventado, Charles Fredric G.**
- **Rodelas, John Vincent B.**
- **Valles, James Vincent V.**

**Course:** CS ELEC 3C - Data Analysis & Visualization

**Group:** 4CSE - Tres Sigmas

## 📂 Project Structure

### PDF Reports
- `Tres-Sigmas-EDA.pdf` - Exploratory data analysis
- `Tres-Sigmas-Data-Cleaning-Reflection-Report.pdf` - Data preprocessing
- `Tres-Sigmas-COMPARING-CATEGORIES.pdf` - Category comparisons
- `Tres-Sigmas-TIME-DISTRIBUTION.pdf` - Time-series analysis
- `Tres-Sigmas-LAB-ACT-MVDA-final.pdf` - Multivariate analysis results

### Project Proposal
- `TresSigmas_4CSE_DataViz-E1_CourseProjectProposal_Presentation.pptx` - Proposal presentation
- `TresSigmas_4CSE_DataViz-E1_CourseProjectProposal.pdf` - Project proposal document

### Analysis Files
- `Tres Sigmas - Data Exploration.twb` - Exploratory data analysis
- `DataCleaning - DataCleaning - TresSigmas.tflx` - Data cleaning workflow
- `Tres Sigmas - Comparing Categories.twb` - Category comparison visualizations
- `Tres Sigmas - Inventado,_Rodelas,_Valles_LAB_ACT_TIME_DISTRIBUTION.ipynb` - Time distribution analysis
- `Tres Sigmas - Lab_Activity_MVDA_final.ipynb` - Multivariate analysis code

### Others

- `A-Detailed-Real-World-Fuel-Economy-CO2-Emissions-and-Vehicle-Attribute-and-Technology-Data-2.csv` - raw dataset file

## 🎯 Research Objectives

### SDG-Aligned Analysis
- **SDG 7**: Examine fuel economy advancements and clean technology adoption
- **SDG 13**: Analyze CO₂ emissions reduction trends and climate impact mitigation

### Core Research Questions

#### Multivariate Analysis (MVDA)
1. How do vehicle characteristics influence fuel efficiency and CO₂ emissions?
2. How can we reduce complexity of vehicle metrics into key indicators for SDG goals?
3. How can we differentiate vehicles that align with sustainable transportation objectives?

#### Time-Distribution Analysis
4. How have manufacturer benchmarks evolved from 2003-2023?
5. How are CO₂ emissions distributed across vehicle types?
6. How have emissions and fuel economy changed across model years?

#### Category Comparison
7. Which manufacturers produce highest/lowest average CO₂ emissions?
8. Which manufacturers have highest performance by horsepower?
9. How do acceleration performances differ across vehicle types?

## 📊 Key Findings

### Environmental Impact
- **Top Emitters**: Stellantis, GM, and Ford lead in CO₂ emissions
- **Cleanest Performers**: Tesla shows lowest environmental impact
- **Vehicle Type Matters**: Trucks show higher emissions than cars

### Performance Trends (2003-2023)
- **Horsepower**: Upward trend across all manufacturers
- **Acceleration**: Overall improvement (decreased 0-60 times)
- **Weight**: Slow but steady increase

### Multivariate Insights
- **Latent Factors**: Identified 'Fuel Efficiency' and 'Vehicle Power/Size' dimensions
- **Dimensionality Reduction**: PCA compressed 10+ variables into 4 components
- **Clear Classification**: Effective separation of Cars (efficient) vs Trucks (powerful)

## 🛠️ Technical Implementation

### Data Preparation
- **Cleaning**: Hyphen replacement, null value imputation
- **Processing**: Encoding, feature scaling, outlier management
- **Tools**: Tableau Prep Builder for automated workflows

### Analytical Techniques
- **Factor Analysis**: Identify latent variables
- **Principal Component Analysis (PCA)**: Dimensionality reduction
- **Discriminant Analysis**: Vehicle classification
- **Time Series Analysis**: Trend identification

### Visualization Methods
- **Advanced Charts**: Radial, Sankey, Bump, Violin, Parallel Coordinates
- **Comparative Visuals**: Tree Maps, Lollipop Charts, Stacked Bar Charts
- **Multivariate Plots**: Factor loadings heatmaps, scatter plot matrices

## 💡 Key Insights

### Manufacturer Performance
- **American Brands**: Dominate in horsepower and larger footprints
- **Electric Focus**: Tesla and Kia prioritize efficiency over raw power
- **Competitive Landscape**: No single manufacturer dominates all categories

### Environmental Impact
- **CO₂ Patterns**: Clear distribution differences across vehicle types
- **Fuel Efficiency**: Cars outperform trucks/SUVs in MPG across all conditions
- **Historical Trends**: Steady MPG improvement with CO₂ decrease (2000-2020)

## 🚀 Business Implications

### For Automotive Industry
- **R&D Guidance**: Balancing performance and sustainability
- **Competitive Intelligence**: Market segment positioning
- **Technology Investment**: Evidence-based clean technology decisions

### For Policy Makers
- **Regulatory Design**: Evidence-based emissions standards
- **Progress Monitoring**: SDG alignment tracking framework
- **Incentive Structures**: Data-supported sustainability policies

## 🔧 Quick Start

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Tableau Desktop/Prep Builder

### Running Analysis
```bash
# Multivariate Analysis
jupyter notebook "Tres Sigmas - Lab_Activity_MVDA_final.ipynb"

# Time Distribution Analysis  
jupyter notebook "Tres Sigmas - Inventado,_Rodelas,_Valles_LAB_ACT_TIME_DISTRIBUTION.ipynb"
```

### 📈 Results Documentation
Complete findings are documented in PDF reports:
- **Data Cleaning Report**: Preprocessing methodology
- **EDA Report**: Dataset exploration
- **Category Comparison**: Manufacturer benchmarking
- **Time-Distribution Analysis**: Evolutionary trends
- **MVDA Final Report**: Advanced multivariate techniques

### 🌟 Future Work
- Real-time monitoring integration
- Global dataset expansion
- Predictive modeling for emission trends
- Interactive public dashboard
