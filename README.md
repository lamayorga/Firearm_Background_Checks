# Firearm Background Checks
## Investigating Firearm Background Checks Using FBI Gun Data
Firearm background check trends were analyzed using datasets from the FBI's National Instant Criminal Background Check System (NICS) and US Census. This project focuses on going through the entire data analysis process from posing questions to sharing findings.

## Datasets
The FBI Gun data can be found in this [BuzzFeed News GitHub repository](https://github.com/BuzzFeedNews/nics-firearm-background-checks) and the US Census dataset can be found on the [census website](https://data.census.gov/cedsci/). Both datasets are included in this repo titled 'gun_data.xlsx' and 'census_data.csv' respectively. 

## Software
The following software was used to build this analysis: 
* Python and libraries:
  * Matplotlib 
  * NumPy
  * pandas
  * SciPy
  * Seaborn
* Jupyter Notebooks

## Summary of Findings/Explored Questions
Through the exploration of the U.S. Census and FBI Gun Datasets, the following insights were revealed:
> * The census data most associated with high background checks is 'Total Manufacturers' Shipment.'
> * Firearm shopping has seasonality with background checks increasing in the winter and decreasing in the summer.
> * The most frequently registered gun type is a long gun and is positively correlated with the total number of firearm checks.
> * Kentucky has had the greatest number of firearm background checks since 1998.

## Additional Insights
* While the dataset is limited to providing firearm background check trends, organizations have incorporated methods to estimate gun sales using this data. The New York Times and The Trace are some of the organizations that estimate gun sales using a method provided in the Small Arms Survey by Jurgen Brauer, a professor at Georgia Regents University. In their calculations, hand gun and long gun checks are counted as 1.1 sales and multiple gun checks are counted as 2 sales. Permits and other types of sales are omitted. Given the Small Arms Survey multiplier, a broader context on gun sales can be provided from the FBI gun data.
* 'Veterans' and 'households' are the second and third most associated categories with the FBI gun data. 
* A spike in background checks is seen every December and has been recorded during Black Friday sales. Additional peaks that occur outside of winter are likely the result of new gun restrictions.
* Kentucky has had the highest activity in background checks for guns since 1998. The state has some of the least restrictive gun control in the country with over 80% of legistlatures receiving a high grade from the NRA on gun legislation. Kentucky also runs a new check on each concealed carry license holder on a monthly basis, adding to the high number of firearm background checks in the FBI gun data.
* Although the ratio of background checks to gun sales has been debated in the past, researchers are discovering that a significant amount of gun sales take place without background checks. According to a national survey conducted by researchers at Northeastern University and Harvard University in 2017, one in five Americans who obtained a firearm in the past two years did so without a background check.
* Since 2018, experts have reported concerns that the NICS is overburdened and understaffed making the organization vulnerable to mistakes and workers at risk of burnout. Due to an NRA-backed loophole in federal law, if a background check takes longer than 3 days, the sale can proceed without verification. In 2018, NICS workers were reportedly so overloaded they did not have time to start a check until nearing the end of the 72-hour window. With the current pandemic, the federal background check loophole has been made even deadlier. From mid-March through July, the FBI has recieved 13.6 million background checks with an 80% increase from this time last year.  According to Everytown for Gun Safety, these numbers result in the following: "That translates to at least 91,500 potential “default proceeds” during the March to May gun-buying frenzy alone. Less than one third of those checks will ever be completed before the records are deleted from the system. The completed checks show at least 1,300 sales to prohibited persons including close to a quarter to prohibited domestic abusers. Given constrained government resources in a state of emergency, these figures are likely much higher."

## Limitations

1. Number of background checks does not equal number of gun sales
2. States can not be compared directly
3. Limited US Census data
4. Correlation does not imply causation

## Credits




