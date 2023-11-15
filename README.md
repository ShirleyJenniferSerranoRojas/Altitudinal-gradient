Code for the following paper:

# The effect of climate change on the elevational range shifts of amphibians along a tropical gradient
------
by

Shirley J. Serrano Rojas, Lauren O'Connell, Rodolfo Dirzo

## Project description

This project aims to analyze historical (a decade ago) and contemporary data (2022) on the elevational distribution of frogs, with the goal of detecting potential shifts in amphibian elevational ranges.
This altitudinal gradient is situated in the Piñi-Piñi mountain range, within the Manu Biosphere Reserve in Southeast Peru. It covers a straight-line distance of 4 km that spans from the lowest areas next to the bank of the Alto Madre de Dios River (~450 m asl) to the peaks of the range (~1200 m asl). 

## File organization

Inside the R folder you will find...

- `modern_data_raw`: The pre-processed data including information of each amphibian individual along this gradient with information on its species name, elevation, date, time, weight, SVL, substrate type, height and notes. This is amphibian data collected in 2022.

- `historical_data_raw`: This is amphibian data collected in 2023. Contains the same information of the modern data.

- `cleaning_data.R`: This file contains the functions to clean and prepare the data for further analysis.

- `elevational_shifts.R`: The elevational_shifts function that estimates range shifts in mean elevation.

- `diversity_measures.R`: This will have the functions use to estimate diversity measurements such as sp_richness, beta_diversity, community_evenness.




