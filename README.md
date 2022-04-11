# Pyber Analysis
## Overview

An exploratory analysis was conducted on rideshare data from the company PyBer inorder to improve access to ridesharing services and determine affordability. Various visualizations were created to better understand the data including: a bubble chart, box-and-whisker plots for multiple summary statistics, and pie charts. After finishing this analysis, it was decided that an addition multiple-line graph was needed to showcase the total weekly fares for each city type. 

## Results

1. Total rides (Ref: PyBer_summary.png in analysis folder)
    - The total number of rides were highest overall in the 'Urban' city types, with a count of 1,625.
    - The total number of rides were second highest in the 'Suburban' city types, with a count of 625.
    - The total number of rides were lowest in the 'Rural' city types, with a count of 125.
 
2. Total drivers (Ref: PyBer_summary.png in analysis folder)
    - The total number of drivers were highest in the 'Urban' city type, with a count of 2,405.
    - The total number of drivers were second highest in the 'Suburban' city type, with a count of 490.
    - The total number of drivers were lowest in the 'Rural' city type, with a count of 78. 
  
3. Total fares (Ref: PyBer_summary.png in analysis folder)
    - The total amount of fares were highest in the 'Urban' city type, with a sum of $39,854.38.
    - The total amount of fares were second highest in the 'Suburban' city type, with a sum of $19,356.33.
    - The total amount of fares were lowest in the 'Rural' city type, with a sum of $4,327.93. 
  
4. Average fare per ride (Ref: PyBer_summary.png in analysis folder)
    - The average fare per ride was highest in the 'Rural' city type, with an average cost of $34.62.
    - The average fare per ride was second highest in the 'Suburban' city type, with an average cost of $30.97.
    - The average fare per ride was lowest in the 'Urban' city type, with an average cost of $24.53.
  
5. Average fare per driver (Ref: PyBer_summary.png in analysis folder)
    - The average fare per driver was highest in the 'Rural' city type, with an average cost of $55.49.
    - The average fare per driver was second highest in the 'Suburban' city type, with an average cost of $39.50.
    - The average fare per driver was lowest in the 'Urban' city type, with an average cost of $16.57.
  
6. Total fare by city type (Ref: PyBer_fare_summary.png in analysis folder)
    - The total fares were consistently the highest in the 'Urban' city type between January 1st 2019 and April 28th 2019 (inclusive).
    
            - The total fares were lower at the start of the year, slowly  increased over the next 8 weeks, staggered up and down for a few                   weeks until April, and then rose and seem to level off (though data from the following months would be needed to confirm that).
            - The highest grossing weeks were at the end of February and beginning of March.
    - The total fares were consistently the second highest in the 'Suburban' city type between January 1st 2019 and April 28th 2019                   (inclusive).
          - The total fares were lower at the start of the year, then they steadily rose and dipped until the end of April where the data                   ends with an upward momentum.
          - The highest grossing week was at the end of February.
    - The total fares were consistently the lowest in the 'Rural' city type between January 1st 2019 and April 28th 2019 (inclusive).
          - The total fares were consistently low for the duration of the time period.
          - the highest grossing week was at the beggining of April.

## Summary

After reviewing the data, summary statistics, and visualizations, the rural city types are significantly the lowest performing through all the metrics. The rural city types steadily return values that are anywhere from 2-3.5 times lower than the suburban and urban city types. It is possible that if an initiative were started to increase the number of drivers available in rural cities, the total rides would increase. In addition to an increase in rides, the average fare per ride would decrease, which would benefit the affordability of these underserved communities.

Comparatively, there seems to be an excess of drivers in the urban city types. If you refer to PyBer_fare_summary.png in the analysis folder, you can see that there are more total drivers than total rides in urban city types. Though this is allows incredible access to the passengers in these cities, many drivers are left without rides, and have lower income (which is les than half of the suburban average fare per driver).
I would recommend the company encourage some of these drivers to start working in the rural city types where there is more opportunity to get rides and a considerably higher average fare per driver.

Lastly, the total fares seem to remain fairly steady over the four month period shown in the "Total Fare By City Type" chart (PyBer_Fare_Summary.png in analysis folder). It may be beneficial to introduce promotion events around holidays, such as, New Year's Eve, Valentine's Day, St. Patrick's Day, and Easter, for example. Encouraging riders around these times should provide some increased profits.
