# CO2 Emissions Analysis: Saudi Arabia

**Student:** [Angel Rose G. Bermejo]  
**Country / ISO-3:** Saudi Arabia / SAU  
**Study period:** 1990 to 2024  
**Declared to instructor on:** [11/13/26]

## Research Question

How have annual CO2 emissions and per-capita emissions changed in Saudi Arabia?

## Data Source and Definitions

Our World in Data (OWID) CO2 and Greenhouse Gas Emissions dataset.

Dataset: https://github.com/owid/co2-data

Downloaded on: [11/13/26]

Selected columns: year, co2, co2_per_capita.

- `co2` is measured in million tonnes per year.
- `co2_per_capita` is measured in tonnes per person per year.

## How to Reproduce the Analysis

1. Install R, RStudio, and Git. Open this repository as an RStudio Project.
2. Use an internet connection for the first full CSV download.
3. In the RStudio Console, run:

   `source("scripts/analyze_co2.R")`

4. Inspect the `data/`, `figures/`, and `results/` folders.

## Results

- Earliest / latest valid years: [1990 and 2024].
- Annual emissions in those years: [181.7073 and 630.7646 million tonnes].
- Endpoint percentage change: [+247.1322]%.
- Peak emissions year: [2019] ([684.2299] million tonnes).
- Latest available per-capita value: [18.57225] tonnes/person.

## Interpretation (200–300 words)

[From 181.70 million tonnes in 1990, CO₂ emissions in Saudi Arabia grew sharply, reaching 630.76 million tonnes in 2024, which is an increase of 247.13%. In 2019, Saudi Arabia had its highest annual emissions, which are equal to 684.22 million tonnes. The increases show that over the period of time Saudi Arabia contributed significantly more to the total quantity of carbon emissions.

There are fluctuations along the trend. In 2020, emissions fell down by about 9.14%, then the increase was followed by 9.32% in 2021 and another decline of approximately 10.20% in 2022. The changes indicate that emissions did not grow in a consistent manner. One of the possible reasons for the decline in 2020 is the COVID-19 pandemic which led to reduced economic activities and energy demand. Luomi et al. (2021) studied the decrease in emissions from fuel combustion in Saudi Arabia in 2020 and discussed changes in energy consumption and industrial sectors that might have contributed to that decline. Aside from the pandemic's impact, changes in carbon dioxide emissions in Saudi Arabia can likely be attributed to policies on energy pricing, energy conservation, and switching to natural gas instead of oil. Energy price reform in 2016 and 2018 made energy consumption more sustainable, while the gradual transition from oil to gas resulted in the reduction of carbon intensity in energy production sector. Moreover, implementation of energy-efficiency standards in transportation and buildings led to decreased energy consumption.

Per capita emissions have evolved differently from the overall carbon emissions of Saudi Arabia. Rising from 17.07 tons per capita in 1990 to 18.57 tons per capita in 20224, per capita emissions have changed significantly over the past decades. This phenomenon shows that overall emissions of an entire country and the carbon emissions per person do not move in parallel. The patterns described here are important because CO₂ emissions are a factor in global climate change, affecting ecosystems, biodiversity, and conditions in the environment. Nevertheless, national emissions datasets only account for emissions produced within territorial borders, thus excluding emissions related to imported commodities, change of land use, and all other types of greenhouse gases.]

## Limitations

[This study made use of secondary data from Our World in Data instead of direct measurement and analysis limited to 1990–2024 and was bound to the available observations for Saudi Arabia. The CO₂ measure relates to emissions from fossil fuels and industrial activities while omitting land-use change and other greenhouse gases. Moreover, national data cannot show discrepancies between emissions from separate cities, economies, and communities. Finally, trends taken into consideration have no means to derive causes of emission fluctuations.]

## References

- Our World in Data. CO2 and Greenhouse Gas Emissions dataset.
- [Luomi, M., Braun, J. F., Thamir, A. S., & Gasim, A. (2021, December 29). What drove Saudi Arabia’s 2020 fall in CO2 emissions? https://testws.kapsarc.org/our-offerings/publications/what-drove-saudi-arabia-s-2020-fall-in-co2-emissions]
