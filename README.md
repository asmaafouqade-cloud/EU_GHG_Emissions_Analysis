# Trends in EU GHG Emissions: A Panel data analysis of country and sector contributions (2018-2023)


**Research questions**  
- which EU-countries and sectors contributed the most to recent GHG emissions reductions ?
- How did emissions reductions trends differ across sectors ?
- Are reductions broad based or concentrated in a few countries ?


**Data sources**
- GHG Emissions : Eurostat (sectoral GHG emissions per country)
  - Sectors : Energy, Industry, Transport 
- Population : Eurostat (annual population by country)  


**Methodology**
- Cleaning and harmonising emissions and population data
- Merging datasets at the country-year level
- Computing key indicators:
  - Total emissions by sector and year
  - Year-to-year sectoral emissions changes
  - Per-capita emissions 
  - Total emissions change over the study period 
  - Ranking country-sector combinations based on the total emissions change

**Key outputs**
  - Descriptive tables for each key indicator
  - Visuals illustrating sectoral and country levels trends

**Key findings**
- Between 2018 and 2023, reductions in GHG emissions across the energy, industry and transport sectors were primarily driven by Germany's energy sector, wich decreased by nearly 1 x 10⁸ tCO₂eq, smaller reductions were observed in Germany's Industry, as well as in the energy and industry sectors of Poland and Spain, the energy sectors of Italy, Greece and Czechia, and the industry sector of France
- The energy sector shows the most consistent reductions averaging around 1.15 x 10⁷ tCO₂eq, followed by the industry sector decreasing nearly by 0.6 x 10⁷ tCO₂eq, in contrast, the transport sector displays a slight increase in emissions, with an average rise of about 0.05 x 10⁷ tCO₂eq
- Reductions are largely concentrated in a few countries, with larger EU economies driving most of the decrease
- 2023 Per-capita emissions show a broad dispersion indicating significant differences in emissions levels between countries


**Policy insights**
- Transport emissions remain close to initial levels over the study period and show only minor reductions compared to the energy and industry sectors. In contrast, the energy sector—fully covered by the EU ETS—records the largest emissions reductions, highlighting differences in emissions outcomes between sectors with limited versus extensive exposure to carbon pricing.
- EU-wide emissions reductions are driven disproportionately by a limited number of countries and sectors, raising questions about the distribution of mitigation efforts across Member States.
- EU-wide averages conceal substantial differences in emissions levels and trends across Member States, indicating uneven progress toward decarbonisation.



**Tools and libraries**
- Python
- Pandas
- Matplotlib
