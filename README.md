# PyBer Analysis

## Overview

### Purpose

The primary purpose of this report is to provide follow-up analysis to PyBer regarding ride-sharing data presented to CEO V. Isualize.  Information already presented includes scatter-plot visualization of city types, fares, and rides; high-level statistics summaries (both tables and box-and-whisker plots); and share-by-city-type pie graphs of fares and drivers.

Following the initial presentation, the CEO requested a written report addressing a line graph representing weekly fares by city type.

Although the initial analysis was thorough, the presentation did not address the data from a longitudinal perspective, and recommendations were therefore not informed by trends.  The _PyBer Fare Summary_ graph below closes that gap.

## Results

***Summary DataFrame***

![https://github.com/crkaide/PyBer_Analysis/blob/main/analysis/summary_dataframe.png?raw=true](https://github.com/crkaide/PyBer_Analysis/blob/main/analysis/summary_dataframe.png?raw=true)

***PyBer Fare Summary***

![https://github.com/crkaide/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true](https://github.com/crkaide/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true)

### Differences

***Differences in ride-sharing data among different city types***

The summary DataFrame and PyBer Fare Summary line graph above make clear a number of differences in the way ride-sharing is utilized, compensated, and valued between city types (rural, suburban, and urban).

* While urban drivers comprise 81% of the total workforce, they are responsible for only 68% of the total rides given.

* Following from the above, the average fare per ride and average fare per driver were substantially lower for urban drivers than either suburban or rural, but the real story is told in the disparities between city types regarding total workload versus compensation/perceived value.

* While rural drivers handle far less of the total share of business _($4,327.93 of $63,538.64 total)_ than suburban or urban, the rural fare per ride is significantly higher ($36.62, against $24.53 for urban).

* Even more dramatically, the average fare per driver is $16.57 in urban cities against $55.49 in rural (accounted for, most likely, by the simple proximity of locations in the city vs. the country).

### Recommendations

1. The figures in the summary DataFrame suggest that while rural rides might be more "valuable" per capita, urban drivers are shouldering the bulk of PyBer's business.  This crucial group of drivers is also least well-compensated.  If data is available, I recommend analyzing driver/employee retention for each of these city types, in light of the fare (and consequent gratuity) disparities.  Regardless of add'l analysis, PyBer might consider implementing policies aimed at bolstering driver security and compensation (ex: minimum fares, automatically applied minimum gratuities).
2. Rural drivers are giving the most expensive rides, most likely due to distance traveled per ride (another element I would recommend analyzing, if data is available).  While PyBer policies directed at increasing a fare's value for its urban drivers would be most beneficial in those cases, rural and suburban drivers may best be retained by company measures that offset damage/wear-and-tear/fuel consumption due to distance driven.
3. While this analysis appears exhaustive and clearly highlights disparities, it seeks to address neither the underlying causes of those disparities, nor the effects they have on driver retention or their behavior over more than a single season (a notable limitation of the original dataset).  Therefore I recommend expanding the analysis to include data from a longer time span (one year/cycle minimum, three ideal).  I would also directly survey PyBer drivers in urban areas to assess what supports the company might provide to offset the per-driver disparity in fares.
