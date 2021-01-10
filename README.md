# origin_destination_isolation
Steps taken to isolate origins (home) to destination (place of interest) using json nested origin values within a large dataset. 

Code within this repository was utilized to complete an ecological study which focused on determining change in community mobility pre- and post- COVID-19 policy mitigation. Observations (rows) of this data were unique in both destination (place of interest) and date. Included within this data was column of json type which held: fips code and the number of visitors to this location who resided within this fips code. 

The primary task included extracting json column values and re-matching to original place of interest to determine number of visitors (who resided in the same fips value) to places of interest on some date. 
