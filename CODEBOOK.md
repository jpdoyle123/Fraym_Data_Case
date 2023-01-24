# An outlook on Food insecurity for children under 5 in Nigeria.

In this readme file, I will provide a general codebook, which aims to explain, and describe the data wrangling processs, as well as document the variable list. 


Variable List:

  1. hhid - **Household id** the unique household identification number. Used throughout the data wrangling process as the argument in the merge's of different datasets, as each dataset contained this household id. 
  2. Monthly_food_spending -  this is an indicator of the level of monthly food spending for each household.
  3. ADMIN 1 - region the household is located in.
  4. Geometry - point geometry used primarily to locationally assign food-security designations from the fews to the correct households. 
  5. Current_food_security - ranges from 1:5, with 5 being famine, 4 being Emergency, 3 being crisis, 2 being stressed, and 1 being minimal food security issues. 
  6. lon_dd_mod and lat_dd_mod: latitude and longitude coordinates for the households. 
  7. indiv_x: the individual identifier amongst each household.
  8. father_education_level: The level of education achieved by the father of the household. Values range from -9:424.
  9. father_occupation: The type of occupation the father of the household has. Values range from 1-15, each matching to a generic descriptor of an industry. 
  10. mother_education_level: The level of education achieved by the mother of the household. Values range from -9:424.
  11. The type of occupation the mother of the household has. Values range from 1-15, each matching to a generic descriptor of an industry. 
  12. Under-5 population: the size of the population under-5 in each region (ADMIN1). 
  13. plot_measured_yes_or_no: whether or not each household had a plot measured during the last visit. Values are binary, taking 1 for no, 2 for yes. 
  14. pre-filled-gps-area: the size of the households plot according to gps.
  15. HH_access_to_plot: Does the household have full access/ do they retain access to their plot? Binary again
  16. Cultivated_or_not: Is the households plot cultivated or not? 





          
