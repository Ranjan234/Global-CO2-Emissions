# Global-CO2-Emissions
This data set includes global fossil fuel emissions data from 1750 - 2021 by country, paired with population data for the same year/country detail. Historical CO2 datapoints are estimated based off of the industrial factors reflected in each time period.

# Profile & QA the data
The first objective is to explore and profile the data while optimizing the source for visualization, including filtering out records that aren't at the country level, updating field types, and creating a parameter.
- Connect to visualizing_global_co2_data.csv, extract the data, and find which countries are the largest contributors of CO₂.
- Add a data source filter to exclude NULL ISO codes.
- Convert all fields with “Co2” in their name to number (whole) data types and change them to continuous measures.
- Create a new integer-type parameter named "Top N" with a default value of 10.

# Visualize the data Your
 The second objective is to visualize the data using a line chart, map and scatter plot to show the trends and relationships between CO₂ emissions and country populations.
- Create a sheet with a line chart showing the % of total CO₂ emissions by country and year, use the TOP N parameter to filter for the top 10 countries, and remove any nulls.
- Create a sheet with a map showing country-level CO₂ per capita for the year 2021, and address any country/region errors or null values.
- Create a sheet with a scatter plot comparing CO₂ and population at the country-level, with bubbles sized by temperature change from co2 for the year 2021 (bonus: add a linear trend line).
- Color all 3 visualizations using co2 per capita and apply a divergent color scale.

 # Build an interactive dashboard
  The final objective is to build an interactive dashboard combining your 3 visualizations in addition to filters/parameters for user interaction.
- Add sheets to your dashboard to show the % of the CO₂ trend as a line chart, CO₂ per capita as a map, and the relationships between CO₂ and population as a scatter plot.
- Assemble the charts into a rough dashboard layout and include a title and top n parameter at the top (design your own layout or follow the solution walkthrough).
- Add an in-context filter for country and apply it to all sheets on the dashboard (tip: create a copy of the country field to avoid impacting your top function).
- Adjust formatting, alignment, and polish to finalize the dashboard as you see fit.
- Do you notice any interesting patterns or trends? How would you describe how global CO₂ emissions differ by country and have changed over time?.

 # Insights
<h1> 1. CO₂ Emissions by Country (Map)</h1>

Highest per capita emitters:
- **Qatar (35.59)**, **Kuwait (24.7)**, and **the UAE (21.79)** are among the top, reflecting their oil-based economies and high energy consumption per person.
Large emitters with big populations:
- China (8.05 per capita) and the United States (14.86 per capita) stand out due to both their population size and high per capita emissions.
Low emitters:
- Many African and South Asian countries (e.g., Sudan 0.46, Yemen 0.38, Bangladesh 0.55) contribute very little per capita.

<h1> 2. CO₂ Emissions (2021) vs. Population (Scatter Plot)</h1>

- China: Largest total emitter (~11,472 Mt), reflecting its huge population and high industrial activity.
  
- United States: Lower population but still very high emissions (~5,007 Mt), meaning emissions per capita are disproportionately large.
  
<h1> 3. CO₂ Emissions Global Share by Year (Line Graph)</h1>

- The chart shows how global shares of CO₂ emissions have shifted over time:

- China’s share has sharply increased in recent decades, overtaking traditional emitters.

- United States & Europe: Their share has gradually declined, though absolute emissions are still high.

- Emerging economies (India, Southeast Asia) are slowly rising in contribution.
  
- India: Large population (~1.4B) but lower per capita emissions, total ~2,710 Mt.
  
- Russia: Moderate population, but very high emissions (~1,756 Mt), indicating high industrial and energy dependence. 3. CO₂ Emissions Global Share by Year (Line Graph) The chart shows how global shares of CO₂ emissions have shifted over time: China’s share has sharply increased in recent decades, overtaking traditional emitters.
 
- United States & Europe: Their share has gradually declined, though absolute emissions are still high. Emerging economies (India, Southeast Asia) are slowly rising in  contribution.
