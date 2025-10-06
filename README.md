# Airbnb Hotel Booking Analysis

### Internship: AICTE Edunet Foundation — Data Analysis using LLMs  
**Author:** Raghavendra Rao Kulkarni  
**Apply ID:** APPLY_175647250568b1a4b99b32a  
**Internship ID:** INTERNSHIP_17546440516895be537820f  

---

## Project Overview
This project focuses on analyzing Airbnb booking data to understand market dynamics, pricing patterns, host behavior, and review distribution in the hospitality industry.  
It includes multiple phases: data cleaning, transformation, visualization, and insight generation — all aimed at uncovering meaningful patterns that guide investment and operational decisions.

---

## Objectives
1. Convert currency fields from text (e.g., "$120") to numerical values for quantitative analysis.  
2. Process and standardize date columns for accurate temporal insights.  
3. Remove extreme outliers to prevent distortion of statistical trends.  
4. Perform exploratory data analysis to identify dominant accommodation types, host behavior, and pricing variations.  
5. Generate visual insights for decision-making.

---

## Research Questions
1. What accommodation categories exist in this dataset?  
2. Which neighborhoods or locations have the highest number of listings?  
3. Which neighborhood has the highest average price for Airbnb listings?  
4. Is there a relationship between the construction year of a property and its price?  
5. Who are the top 10 hosts by calculated host listing count?  
6. Are verified hosts more likely to receive positive reviews?  
7. Is there a correlation between the price of a listing and its service fee?  
8. What is the average review rate for listings, and how does it vary by neighborhood and room type?  
9. Are hosts with higher listing counts more likely to maintain higher availability throughout the year?

---

## Methodology

### Phase 1: Data Understanding
- Examined dataset structure, attributes, and missing data.
- Identified relevant features such as `price`, `neighbourhood_group`, `room_type`, and `reviews_per_month`.

### Phase 2: Data Quality Enhancement
- Cleaned currency and percentage columns.  
- Converted string-based date fields into proper datetime format.  
- Handled missing values and removed extreme outliers.  
- Standardized text data for consistent visualization.

### Phase 3: Visual Data Exploration
- Used **matplotlib** and **seaborn** for distribution and correlation analysis.  
- Produced bar charts, heatmaps, and scatterplots to illustrate relationships.  
- Derived conclusions for each research question with visual support.

---

## Key Findings

### Accommodation Categories
- **Entire home/apartment** is the most common accommodation type with **52,632 listings**.  
- **Private rooms** follow closely with **45,704 listings**, showing a difference of **6,928**.  
- **Shared rooms** and **hotel rooms** are far less frequent, with **2,178** and **114** listings respectively.  
- Indicates a clear user preference for entire properties over shared spaces.

### Neighborhood Trends
- Certain neighborhoods show higher density and average prices due to demand concentration.  
- Premium areas attract more listings and higher nightly rates.

### Host Behavior
- The **top 10 hosts** collectively manage a large portion of total listings.  
- **Verified hosts** receive slightly higher average review ratings, indicating more trust from guests.  
- Hosts with multiple properties often maintain higher **availability** throughout the year.

### Price Relationships
- **Price** and **service fee** exhibit a **moderate positive correlation**, implying proportional pricing.  
- **Older constructions** show marginally lower prices, though the relationship is weak.

---

## Technologies Used
- **Python 3.x**  
- **pandas** – Data manipulation and cleaning  
- **numpy** – Numerical operations  
- **matplotlib** – Visualization  
- **seaborn** – Statistical visualization  

---

## File Structure
Raghavendra_Rao_K_Airbnb_data_analysis/
├── README.md # Project documentation
├── Raghavendra_Rao_K_Airbnb_data_analysis.ipynb # Jupyter Notebook for full analysis
├── requirements.txt # Python dependencies
├── results_summary.csv # Summary of findings
└── analysis_results.png # Visualizations and plots

End Users

Property Investors – Identify profitable areas and property types.

Airbnb Hosts – Understand competitive pricing and customer preferences.

Tourism Industry Professionals – Track demand clusters and market gaps.

Urban Planners – Study the spatial distribution of short-term rentals.

Data Scientists – Practice data cleaning and visualization workflows.

Author

Name: Raghavendra Rao Kulkarni
Internship: AICTE Edunet Foundation — Data Analysis using LLMs
Apply ID: APPLY_175647250568b1a4b99b32a
Internship ID: INTERNSHIP_17546440516895be537820f
