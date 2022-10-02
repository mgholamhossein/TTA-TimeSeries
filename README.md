# TTA-TimeSeries
The goal is having a consistent recordered google trend data (https://trends.google.com/trends/explore?date=today%205-y&q=bitcoin) out of three datasets that each are scaled.
the data for each of these three datasets are scaled between 0 and 100.
we have to rescale the data after merging the three datasets to have a consistent hourly data.
for rescaling section (since we don't how they picked the data for example for a week of measurements), I tried mean, max and median of the hourly and wekkly data. 
The max rescaling gave the best result.
