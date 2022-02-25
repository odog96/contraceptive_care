# contraceptive_care
### Process
1. Collect geo-data
2. Calculate county centroid data
3. Clean up data frame with country centroid detail<br>

**Load clinic Data**<br>

4. Make all counties lower case
5. For each time period (2010 and 2015), generate 2 lists:
    * Counties with no clinic
    * Counties with clicic
6. For each time period, generate a list that finds closest county with a clinic. This is only for counties with no clinic in that time period
7. The resultant data frame has fields: Closest counties / Counties. Groupby Closest counties to see catchment area

**Estimate New Female Popultion with Catchment included**<br>

8. Create 2 columns per time peried
    * catchment area female pupulation that includes only catchment counties
    * 'new' total that includes catchment plus a counties own population


#### Texas Country Geo-Perimeter Data from:  


https://gis-txdot.opendata.arcgis.com/datasets/TXDOT::texas-county-boundaries-detailed/about
