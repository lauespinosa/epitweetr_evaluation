# Epitweetr: Early warning of public health threats using Twitter data

This repository contains all additional code and data for the manuscript "Epitweetr: Early warning of public health threats using Twitter data".

## Code
The Github repository containing the code for `epitweetr` R package can be found [here](https://github.com/EU-ECDC/epitweetr).

`epitweetr` version 0.1.24 is included in [CRAN](https://cran.r-project.org/web/packages/epitweetr/index.html).

## Data
Data shared in this [repository](https://github.com/lauespinosa/epitweetr_evaluation/tree/main/data) corresponds to the list of anonymised signals and events detected by epitweetr and Twitter manual monitoring.

#### Metadata
- Sig_day: Day of the signal
- Sig_time: Time of the signal
- Validated: whether the signal was validated or not
- Val_day: Day of the validation
- Val_time: Time of the validation
- Label: Anonymised topics
- is_covid: whether the topic was related to COVID-19 or not
- Method: method used (epitweetr or Twitter manual monitoring)
- Person: epidemic intelligence (EI) expert who collected that signal
- Start_time: start time of the Twitter monitoring (either manual or using epitweetr)
- sig_day_time: Time and day of the signal
- val_day_time: Time and day of the validation
