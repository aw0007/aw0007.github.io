---
layout: archive
title: "Code Samples"
permalink: /Code_sample/
author_profile: true
---

{% include base_path %}

Explore my GitHub repositories for code samples and project analyses:

1. [China Financial Flow](https://github.com/aw0007/China-financial-flow): Analysis of Chinese financial flows and their impact on economic development.

This repository contains replication files and documentation for the project "Chinese Financial Flows: A Growth Lever for Recipient Economies?" The analysis evaluates the impact of Chinese financial flows on the economic development of recipient countries using econometric and statistical tools.

Tools and Methods Used:
- R: Data preprocessing, visualization, and descriptive analysis.
- Stata: Econometric modeling and statistical analysis.
- Python: Advanced network graph creation and geographic mapping.

<details> <summary style="cursor: pointer; color: #007acc; text-decoration: underline;">Click to View Details</summary> <ul> <li><strong>Data Handling and Cleaning</strong> <ul> <li>Extensive processing of raw data from various sources.</li> <li>Integration of control variables for robust analysis.</li> <li>Creation of intermediate and final datasets for econometric models.</li> </ul> </li> <li><strong>Econometric Analysis</strong> <ul> <li>Estimation of impacts using advanced econometric models.</li> <li>Sub-sample analyses for Africa, Americas, and Asia to capture regional differences.</li> <li>Examination of gross fixed capital formation as a key development outcome.</li> <li>Use of within-country, instrumental variable, and dynamic panel methods.</li> </ul> </li> <li><strong>Visualization</strong> <ul> <li>Graphs and maps illustrating Chinese financial flows, investments, and project distributions.</li> <li>Network graphs showing connections between China and recipient countries.</li> <li>Heatmaps and time-series visuals for trends over time.</li> </ul> </li> <li><strong>Mapping and Cartography</strong> <ul> <li>Geospatial mapping of projects using precise geographic coordinates.</li> <li>Country-level mapping to highlight the dispersion of Chinese investments globally.</li> <li>Interactive maps for user exploration of investment patterns.</li> </ul> </li> </ul> </details>


2. [Tax Data Analysis](https://github.com/aw0007/Tax-Data-Analysis): Statistical analysis and insights into regional tax trends and revenue mobilization.

This repository contains scripts and replication files for the **Tax Data Analysis** project, which explores regional trends in taxation, focusing on direct taxes, VAT, property taxes, and international trade taxes as a percentage of GDP. The project uses Stata for data processing, econometric analysis, and visualization of results.

Tools and Methods Used:
- **Stata**: Data cleaning, panel setup, and graphical visualizations.
- **Excel**: Input data preparation and formatting.

<details> <summary style="cursor: pointer; color: #007acc; text-decoration: underline;">Click to View Details</summary> <ul> <li><strong>Data Preparation and Cleaning</strong> <ul> <li>Merging raw tax data with country-region mapping for comprehensive analysis.</li> <li>Removing duplicates to create a clean panel dataset.</li> <li>Generating unique country-year identifiers for accurate tracking.</li> </ul> </li> <li><strong>Variable Creation</strong> <ul> <li>Creation of normalized variables showing tax components as a percentage of GDP.</li> <li>Key variables include: <ul> <li>Direct Taxes (`DirectTaxesIncludingSCIncRe_pct`).</li> <li>Taxes on Income, Profits, and Capital (`TaxesonIncomeProfitsCapita_pct`).</li> <li>Property Taxes (`PropertyTaxes_pct`).</li> <li>Indirect Taxes (`IndirectTaxesTotal_pct`).</li> <li>VAT (`TaxesonGoodsandServicesVAT_pct`).</li> <li>Taxes on International Trade (Total, Imports, Exports).</li> </ul> </li> </ul> </li> <li><strong>Visualization</strong> <ul> <li>Line graphs showcasing trends in tax contributions across regions.</li> <li>Visualizations for specific tax categories (e.g., VAT, property taxes, international trade taxes).</li> <li>Regional breakdowns (Africa, Americas, Asia, Europe, Oceania).</li> </ul> </li> <li><strong>Regional Analysis of Tax Trends</strong> <ul> <li>Identification of differences in tax trends by region over time.</li> <li>Comparison of tax contributions to GDP across continents.</li> <li>Insights into revenue mobilization strategies in different regions.</li> </ul> </li> </ul> </details>

3. [ACLED Data Analysis](https://github.com/aw0007/Acled-Data-Analysis): 

This repository contains Python scripts and datasets for the **ACLED Data Analysis** project. The project visualizes armed conflict events by region and year, highlighting event typ s, their geographic distribution, and associated fatalities. Maps are generated to provide insights into conflict patterns and severity.

Tools and Methods Used:
- **Python**:
  - `pandas` for data handling and preprocessing.
  - `matplotlib` for plotting and visualization.
  - `geopandas` for geographic shapefile manipulation and mapping.

<details> <summary style="cursor: pointer; color: #007acc; text-decoration: underline;">Click to View Details</summary> <ul> <li><strong>Data Preparation</strong> <ul> <li>Loading and preprocessing ACLED datasets.</li> <li>Converting event dates to datetime format and extracting year information.</li> <li>Filtering data by year (e.g., 2024) for focused analysis.</li> </ul> </li> <li><strong>Mapping and Geographic Analysis</strong> <ul> <li>Loading and filtering geographic shapefiles for countries within specific regions.</li> <li>Highlighting countries affected by conflicts within the selected region.</li> <li>Overlaying event points with geographic data for enhanced visualization.</li> </ul> </li> <li><strong>Visualization</strong> <ul> <li>Plotting conflict events by type using scatter points differentiated by colors.</li> <li>Scaling point sizes based on fatalities to indicate event severity.</li> <li>Annotating country names at centroids for improved readability.</li> <li>Including custom legends to scale fatalities for easier interpretation.</li> </ul> </li> <li><strong>Regional Insights</strong> <ul> <li>Exploring conflict patterns and event types for each region.</li> <li>Identifying geographic hotspots of conflict activity within regions.</li> <li>Providing visual insights into the scale and severity of events across regions.</li> </ul> </li> </ul> </details>

4. [African Educational Data Analysis (PASEC)](https://github.com/aw0007/AFrican-Educational-Data-Analysis-PASSEC):
PASEC Data Visualization: Analysis and visual exploration of educational test scores from PASEC 2019, focusing on gender and country-level trends in mathematics and reading.
This repository contains two Python scripts for analyzing and visualizing educational test score data for Grade 6 students. The project uses box plots, KDE plots, and faceted visualizations to highlight gender and country-specific disparities.

Tools and Methods Used:
Python:
pandas: For data preprocessing and analysis.
matplotlib and seaborn: For creating detailed visualizations.
Pillow (PIL): For resizing and optimizing output images.

<details> <summary style="cursor: pointer; color: #007acc; text-decoration: underline;">Click to View Details</summary> <ul> <li><strong>Box Plot Visualization (`Box plot.py`)</strong> <ul> <li>Generated box plots for mathematics and reading scores by country and gender.</li> <li>Included custom legends showing the percentage of male and female students.</li> <li>Created a combined visualization for mathematics and reading scores with a shared legend.</li> <li>Added author signature and software details to all visualizations.</li> </ul> </li> <li><strong>Score Distribution Visualization (`Distribution.py`)</strong> <ul> <li>Created KDE plots for overall score distributions by gender in mathematics and reading.</li> <li>Generated faceted KDE grids to visualize score distributions by country and gender.</li> <li>Optimized visuals for high-quality outputs suitable for publications.</li> </ul> </li> <li><strong>Sample Visuals</strong> <ul> <li>Box Plot for Mathematics Scores: `BoxPlot_MATHS_PV5.png`</li> <li>KDE Plot for Overall Mathematics Scores: `Overall_Distribution_MATHS_PV5.png`</li> <li>Faceted KDE for Reading Scores by Country: `Facet_Distribution_LECT_PV5.png`</li> </ul> </li> </ul> </details>
   
For more projects, visit my [GitHub profile](https://github.com/aw0007).
