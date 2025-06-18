![image](https://github.com/user-attachments/assets/d08d5d5d-95c4-45fb-9830-89a6dd2a2023)

## Project Title - 🚗💡 Electric Vehicle Sales Dashboard 📊⚡

This repository presents an extensive analysis of Electric Vehicle Sales data, offering profound insights and facilitating strategic decision-making within the EV market.

### 📃 Description

The Electric Vehicle Sales Dashboard provides a detailed examination of EV adoption and market trends. Featuring visualizations of total vehicles, average electric range, sales by city and make, BEV vs. PHEV share, sales by model year, and clean alternative fuel vehicle eligibility, this dashboard offers valuable insights into the burgeoning EV landscape. With filters for City, Electric Utility, and Electric Vehicle Types, the dashboard enables a nuanced analysis of trends and areas for growth, facilitating data-driven decision-making for manufacturers, policymakers, and consumers alike. This paper discusses static forms of visualization created to analyze the adoption and distribution of electric vehicles (EVs) throughout the states of the United States. The visualizations originate from a collected curated dataset that consists of more than 230,000 EV records where more attention is given to geographical trends, contributions by the manufacturer, and technological preference.


### 🚀 Project Goal

The aim of this project is to provide an in-depth evaluation of Electric Vehicle sales, facilitating a clearer understanding of market performance, adoption trends, and areas for growth. It is critical for planning infrastructures as well as formulating policies and strategic investments to know the spatial and categorical distribution of EVs.

### Project Motivation

This project is driven by the desire to convert raw EV sales data into actionable intelligence, fostering advancements in electric vehicle adoption and supporting the transition to sustainable transportation. The phenomenon of electric vehicles adoption is a trend that is highly influenced by various economic, technological and environmental aspects.

### ⏳ Dataset

The Electric Vehicle Sales data is presented in a dashboard format, derived from underlying datasets that include information on vehicle type, make, model, sales figures, and eligibility for clean alternative fuel vehicle (CAFV) incentives. This paper gives static visualizations using a cleaned and structured dataset.

### 📑 Dataset Description

The dashboard visualizes various aspects of EV sales, including:

* **Total Vehicles by Model Year (Line Chart):** Depicts the registration of electric vehicles over a number of years. The x-axis represents the year of registration, and the y-axis shows the total number of EVs. Lines of different colors can depict trends for BEVs and PHEVs separately.
    * **Insights Gained:** Overall Growth Rate (slope of the line), Identifying Key Growth Periods, Comparing BEV and PHEV Growth, Forecasting Potential Trends.
    * **Justification:** Standard for Time-Series Data, Highlights Trends and Patterns, Directly Addresses Temporal Analysis, Supports Forecasting and Planning.
* **Geographical Distribution of EV Density (Filled Map):** Uses a filled map of the United States where each geographical unit (states, counties, or ZIP codes) has a color based on EV density. Color intensity indicates density (darker for higher density). Tooltips show exact EV count and density.
    * **Insights Gained:** Identification of High-Adoption Zones, Pinpointing Low-Adoption Areas, Urban vs. Rural Disparities, Regional Trends.
    * **Justification:** Directly Addresses Spatial Disparities, Intuitive Interpretation, Supports Granular Analysis, Contextual Awareness.
* **Market Trends by Vehicle Type and Make (Stacked Bar Chart - appears as a Tree Map in the image):** Each bar represents an EV manufacturer, with its height showing total registered EVs. Sections within each bar, in different colors, indicate the proportion of vehicle volume by city.
    * **Insights Gained:** Market Share by Manufacturer, Technology Preference by Brand, Identifying Emerging Players.
    * **Justification:** Effective for Comparing Categories, Clear Part-to-Whole Relationship, Easy to Understand.
* **Total Vehicles by Make (Horizontal Bar Chart):** Ranks vehicle makes by the number of registered EVs.
    * **Insights Gained:** Market dominance of top brands, Identification of central players in the EV ecosystem.
    * **Justification:** Bar charts make comparison between separate categories easy and define ranking metrics clearly.
* **Total Vehicles by Model (Vertical Bar Chart):** Shows leading models based on total registration, enabling fine tracking of individual vehicle performance.
    * **Insights Gained:** Popularity of specific models, Model-based segmentation for policy targeting.
    * **Justification:** Model level data is crucial to comprehend consumer preference and provide direction for incentives.
* **Summary – Total Vehicles by CAFV Eligibility (Donut Chart):** Denotes the percentage of vehicles capable of meeting Clean Air Vehicle (CAV) standards. Approximately 31% of vehicles are CAV eligible.
    * **Insights Gained:** Effectiveness of environmental policy mechanisms, Scope for increasing compliance.
    * **Justification:** Donut charts are suitable for visualizing part-to-whole relationships, especially where categories are limited.
* **Card Visuals BEV vs. PHEV Breakdown:** Two cards summarize the split between BEVs (79%) and PHEVs (21%) out of 223K total vehicles.
    * **Insights Gained:** Clear overview of EV type dominance, Quick reference for strategic comparison.
    * **Justification:** Cards are effective for presenting KPIs and summary statistics. They are visually appealing and can be easily viewed.

### Requirement

* **To analyze** the geographical distribution by mapping EV density by ZIP code, county, and state.
* **To evaluate** market trends based on registered EV makes and models by separating battery electric vehicles (BEVs) and plug-in hybrid electric vehicles (PHEVs).
* **Show** year-over-year trends of EV adoption through time-series graphs.
* **Develop an** interactive dashboard which enables to select data filters about location and vehicle types for recommending which areas need more charging facilities.

### 🚀 My Project

Comprehensive analysis has been conducted on the dataset, illustrated through a variety of engaging plots and charts. The dashboard provides an interactive experience, allowing users to filter data by City, Electric Utility, and Electric Vehicle Types for enhanced data exploration. This version is a static copy of the insights and will be made more dynamic in the final live implementation.

### The Operations performed are:

* Applied Sorting and Filters
* Applied necessary Functions
* Visualized data through various charts including line graphs, filled maps, stacked bar charts (tree map), horizontal bar charts, vertical bar charts, donut charts, and card visuals.

### Author

* **Deepak Mahato Tharu**

### Lessons Learnt

* Understanding key metrics in electric vehicle adoption.
* Identifying trends in EV sales over time.
* Analyzing market distribution by geography and manufacturer.
* Gaining insights into the BEV and PHEV market segments.
* The importance of visualizing complex data for clear understanding and decision-making.

### Technical Skills

* Data Visualization
* Dashboard Design
* Data Analysis
* **Power BI**
