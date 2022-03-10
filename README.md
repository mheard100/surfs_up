# surfs_up
## Deliverable 3: A written report for the statistical analysis
For this part of the Challenge, write a report that describes the key differences in weather between June and December and two recommendations for further analysis.

### The analysis should contain the following:

1. **Overview of the analysis:** Using Python, Pandas functions and methods, and SQLAlchemy, we’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the months of June and December. We'll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics. Once our dataframe is created we are able to get our summary statistics by using the `df.describe()` code and method. 
> Below our Analysis that what we found:

2. **Results:** Data Provided shows that on months of June and December, the Hawaii location had total Temps of:

**June Temps - Analysis and Result**
* Count of 1700 
* Mean of 74.94 
* Std of 3.26 
* Min of 64.00 
* 25% of 73.00 
* 50% of 75.00
* 75% of 77.00
* Max of 85.00



**December Temps - Analysis and Result**
* Count of 1517 
* Mean of 71.04 
* Std of 3.75
* Min of 56.00 
* 25% of 69.00 
* 50% of 71.00
* 75% of 74.00
* Max of 83.00



3. **Summary:** Based on our Data Analysis, Data Provided, we can state as a high-level summary of results that Standard deviation is 3.25 in June and 3.75 in December, meaning June has more consistant weather. Both months have good weather, meaning ice cream and surfing is ideal almost year round.
 
    In addition, queries for precipitation and months in fall and spring can give more of a full picture for opening the surf shop.  
