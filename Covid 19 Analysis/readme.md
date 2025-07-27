# COVID-19 Analysis

## 📌 Project Overview

This project aims to analyze the global impact of the COVID-19 pandemic using publicly available data. It involves performing descriptive, exploratory, and inferential analysis to extract key insights regarding infection rates, mortality, recovery trends, and testing patterns across different countries and continents. This project for me is the favourite because it uses "Plotly" libraray to present the visulaizations and finding. I prefer Plotly library for the visualization because we can present so many insights / findings in just 1 plot. We can include the findings not just on X and Y axis but we can present more insights in its colors and also on the hover over data. Also the plotly libray brings to life the visualization than the normal boring visualization provided by Matplot Lib.  

By leveraging data visualization and statistical techniques, the project seeks to answer critical questions such as:

- Which countries / continents / region were most affected i.e, Total cases, Total Death, Total Tests?
- How did testing correlate with case and death rates?
- What are the trends in recovery and mortality?
- How did population size influence COVID-19 spread?

---

## 📊 Dataset Description

Here we are using 3 different data sets named as "Covid Dataset", "Covid Grouped Dataset", "Covid Death Dataset". I have mentioned the detailed explaition of each dataset below. 

# 1. Covid_dataset

| Column Name           | Description |
|-----------------------|-------------|
| **Country/Region**    | Name of the country or region |
| **Continent**         | Continent to which the country belongs |
| **Population**        | Total population of the country |
| **TotalCases**        | Cumulative confirmed COVID-19 cases |
| **NewCases**          | New COVID-19 cases reported in the latest update |
| **TotalDeaths**       | Cumulative number of deaths due to COVID-19 |
| **NewDeaths**         | New deaths reported in the latest update |
| **TotalRecovered**    | Total number of recovered cases |
| **NewRecovered**      | Number of new recoveries reported |
| **ActiveCases**       | Current active COVID-19 cases |
| **Serious,Critical**  | Number of serious or critical cases |
| **Tot Cases/1M pop**  | Total cases per 1 million people |
| **Deaths/1M pop**     | Total deaths per 1 million people |
| **TotalTests**        | Total COVID-19 tests conducted |
| **Tests/1M pop**      | Tests per 1 million people |
| **WHO Region**        | WHO-defined regional classification |
| **iso_alpha**         | ISO 3166-1 alpha-3 country code |



# 2. Covid_Grouped_dataset

| Column Name           | Description |
|-----------------------|-------------|
| **Date**              | Date of the covid confirmation |
| **Country/Region**    | Name of the country or region |
| **Confirmed**         | Number of confirmed cases |
| **Deaths**            | Number of deaths |
| **Recovered**         | Number of recovered cases |
| **Active**            | Number of Active cases |
| **New cases**         | Number of New cases |
| **New recovered**     | Number of New recovered	 |
| **WHO Region**        | WHO-defined regional classification	 |
| **iso_alpha**         |ISO 3166-1 alpha-3 country code |


# 3. Covid_Death_dataset

| Column Name                   | Description |
|-------------------------------|-------------|
| **Data as of**                | Date of the covid confirmation |
| **Start Week**                | Indicates the start of week |
| **End Week**                  | Indicates the end of week |
| **State**                     | The state that belongs to in US |
| **Condition Group**           | Medical group to which it belongs to |
| **Condition**                 | It states what medical condition the patient is facing with |
| **ICD10_codes**               | The medical code for that condition |
| **Age Group**                 | The age group to which the patient belongs to |
| **Number of COVID-19 Deaths** | Indicated the start of week |




---

## 🔍 Objectives

1. **Understand global and regional COVID-19 trends**
2. **Analyze the relationship between testing and infection/death rates**
3. **Identify high-risk and low-risk countries based on severity indicators**
4. **Evaluate healthcare burden using serious/critical case numbers**
5. **Visualize the data through charts, heatmaps, and comparative plots**

---

## 🧪 Methods and Tools Used

- **Python Libraries**: pandas, numpy, matplotlib, seaborn, plotly
- **Data Cleaning**: Handling missing values, standardizing column names, type conversion
- **Data Visualization**: Bar plots, line charts, scatter plots, choropleth maps
- **Statistical Analysis**: Per capita metrics, distribution analysis, regional comparisons

---

## 📈 Sample Analyses

- Top 10 countries with highest total cases and deaths
- Correlation between population, cases, deaths, and tests
- Comparative analysis of testing rates vs. infection rates
- Active vs. recovered cases over time per continent
- Mapping deaths per million using geo-visualization

---

## ✅ Outcomes

This project helps stakeholders such as researchers, policymakers, and the general public to better understand how the pandemic unfolded globally and regionally. It highlights key patterns and anomalies that may inform responses to future pandemics.

---

## 📁 Project Structure
