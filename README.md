# 2022-Franklin-CTD-Rosette

## Hi there 👋

🙋 Welcome to the repository for the CTD and Rosette nutrient, and oxygen data from thr CCGS Sir John Franklin from 2022 as part of the International Year of the Salmon High Seas Expedition.

🐟 The repository is structured as follows:

* `original_data` contains processed data files that have been sent to the IYS Data Scientists that have not been formatted to the IYS Data Template. This dataset in incomplete/raw and doesn't include the event data to associate the CTD and rosette bottle data to. This file is provided for provenance and the IYS Data Template or Standardized version of the data will likely be more useful for you.
* `IYS_data_template` contains the processed data files that have been provided in the IYS Data Template. This dataset is complete and contains some other data from the Franklin including Trawl catch and specimen data.
* `standardized_data` contains the standardized data tables as they will be published to OBIS or ERDDAP.
* `scripts` contains the code used to format the data files from either the original_data or IYS_data_template folder to the data tables as found in standardized_data.
* `docs` contains any supplementary material, protocols, changelogs etc relevant for data interpretation.

🦐 Check out our about page for more info! https://international-year-of-the-salmon.github.io/about/index.html
