# Firearm Background Checks
## Investigating Firearm Background Checks Using FBI Gun Data
Firearm background check trends were analyzed using datasets from the FBI's National Instant Criminal Background Check System (NICS) and US Census. This project focuses on going through the entire data analysis process from posing questions to sharing findings.

## Datasets
FBI Gun data was retrieved from this [BuzzFeed News GitHub repository](https://github.com/BuzzFeedNews/nics-firearm-background-checks). The US Census data can be found on the [census website](https://data.census.gov/cedsci/). Both datasets are included in this repo titled 'gun_data.xlsx' and 'census_data.csv' respectively. 

## Software
The following was used to build this analysis: 
* Python and libraries:
  * Matplotlib 
  * NumPy
  * pandas
  * SciPy
  * Seaborn
* Jupyter Notebooks

## Summary of Findings
Through the exploration of the U.S. Census and FBI Gun Datasets, the following insights were revealed:
1. The census data most associated with high background checks is 'Total Manufacturers' Shipment.'
2. Firearm shopping has seasonality with background checks increasing in the winter and decreasing in the summer.
3. The most frequently registered gun type is a long gun and is positively correlated with the total number of firearm checks.
4. Kentucky has had the greatest number of firearm background checks since 1998.

## Additional Insights and Current Events
**A one-to-one comparison can not be made between firearm background checks and gun sales**

* While the dataset is limited to providing firearm background check trends, organizations have incorporated methods to estimate gun sales using this data. [The New York Times](https://www.nytimes.com/interactive/2015/12/10/us/gun-sales-terrorism-obama-restrictions.html?mtrref=localhost&gwh=F7A86A47A6B45B9FBE47E7BE10AF9C83&gwt=pay&assetType=REGIWALL) and [The Trace](https://www.thetrace.org/rounds/how-many-guns-do-americans-own/) are some of the organizations that estimate gun sales using a method provided in the [Small Arms Survey](http://www.smallarmssurvey.org/fileadmin/docs/F-Working-papers/SAS-WP14-US-Firearms-Industry.pdf) by Jurgen Brauer, a professor at Georgia Regents University. In their calculations, hand gun and long gun checks are counted as 1.1 sales and multiple gun checks are counted as 2 sales. Permits and other types of sales are omitted. Given the Small Arms Survey multiplier, a broader context on gun sales can be provided from the FBI gun data.

**Census data associated with high gun per capita**

* 'Veterans' and 'households' are the second and third most associated categories with the FBI gun data. 

**Seasonality associated with firearm shopping**

* A spike in background checks is seen every December and has been recorded during [Black Friday sales](https://www.americanrifleman.org/articles/2019/12/2/black-friday-2019-second-highest-gun-sales-volume-ever/). Additional peaks that occur outside of winter are likely the result of [new gun restrictions](https://www.nytimes.com/interactive/2015/12/10/us/gun-sales-terrorism-obama-restrictions.html?mtrref=localhost&gwh=60BB3760A77C1B9D06006361F88E198E&gwt=pay&assetType=REGIWALL).

**Kentucky's high firearm background check rate**

* Kentucky has had the highest activity in background checks for guns since 1998. The state has some of the [least restrictive gun control](https://lawcenter.giffords.org/scorecard/#KY) in the country with [over 80% of legistlatures receiving a high grade from the NRA](https://www.thetrace.org/2016/11/nra-gun-record-rating-system-straight-a-students/) on gun legislation. Kentucky also runs a new check on each concealed carry license holder on a monthly basis, adding to the high number of firearm background checks in the FBI gun data. In light of [recent gun violence](https://www.cnn.com/2018/01/23/us/kentucky-high-school-shooting/index.html), stricter [gun laws](https://www.wkyt.com/content/news/Gun-control-bill-introduced-to-Ky-House-475227283.html) have been introduced in Kentucky.

**Gun Sales happening without background checks**

* Although the ratio of background checks to gun sales has been debated in the past, researchers are discovering that a significant amount of gun sales take place without background checks. According to a [national survey](https://news.northeastern.edu/2017/01/05/new-study-finds-1-in-5-us-gun-owners-obtained-firearm-without-background-check/) conducted by researchers at Northeastern University and Harvard University in 2017, one in five Americans who obtained a firearm in the past two years did so without a background check.

**Improving the future of the NICS**

* [Since 2018](https://www.thetrace.org/2018/03/gun-background-check-staff-shortage-justice-department-budget/), experts have reported concerns that the NICS is overburdened and understaffed making the organization vulnerable to mistakes and workers at risk of burnout. Due to an NRA-backed loophole in federal law, if a background check takes longer than 3 days, the sale can proceed without verification. In 2018, NICS workers were reportedly so overloaded they did not have time to start a check until nearing the end of the 72-hour window. 

* With the current pandemic, [the federal background check loophole has been made even deadlier](https://everytownresearch.org/covid-default-proceed/). From mid-March through July, the [FBI has recieved 13.6 million background checks](https://www.thetrace.org/2020/07/gun-background-checks-june-record/) with an 80% increase from this time last year.  According to [Everytown for Gun Safety](https://everytownresearch.org/covid-default-proceed/), these numbers result in the following:

>> *That translates to at least 91,500 potential “default proceeds” during the March to May gun-buying frenzy alone. Less than one third of those checks will ever be completed before the records are deleted from the system. The completed checks show at least 1,300 sales to prohibited persons including close to a quarter to prohibited domestic abusers. Given constrained government resources in a state of emergency, these figures are likely much higher.*

* While experts say that sufficient NICS staffing is a necessity for the federal gun background check system to function as intended and prevent dangerous people from obtaining lethal weapons, it would be interesting to evaluate the technology being used. The integration of current technology that complies with safety regulations could potentially automate and alleviate tasks for NICS staff allowing them to focus on more demanding responsibilities, such as completing a check within 72-hours. The improved systems could also be built to anticipate the volatility of surges like the current pandemic. Beyond the necessary staffing and technological improvements, the future reformation of gun laws could also be based on [machine learning insights](https://towardsdatascience.com/what-can-machine-learning-tell-us-about-americas-gun-laws-da01d9fb7413).


## Limitations
1. Number of background checks does not equal number of gun sales
2. States can not be compared directly
3. US Census data limited to one year
4. Correlation does not imply causation

## Credits
**Data**
* [FBI National Instant Criminal Background Check System](https://www.fbi.gov/services/cjis/nics)
* [Udacity](https://www.udacity.com/course/data-analyst-nanodegree--nd002)
* [US Census Bureau](https://data.census.gov/cedsci/)

**Reports**
* <a href='https://lawcenter.giffords.org/scorecard/#KY'>Annual Gun Law Scorecard</a>
* <a href='https://www.americanrifleman.org/articles/2019/12/2/black-friday-2019-second-highest-gun-sales-volume-ever/'>Black Friday 2019—Second Highest Gun Sales Volume Ever</a>
* <a href='https://www.thetrace.org/2020/07/gun-background-checks-june-record/'>Gun Background Checks Surged to New High in June</a>
* <a href='https://www.wkyt.com/content/news/Gun-control-bill-introduced-to-Ky-House-475227283.html'>Gun control bill introduced to Ky. House</a>
* <a href='https://everytownresearch.org/covid-default-proceed/#foot_note_9'>How COVID-19 Has Made a Federal Background Check Loophole Even Deadlier</a>
* <a href='https://www.cnn.com/2018/01/23/us/kentucky-high-school-shooting/index.html'>Kentucky school shooting: 2 students killed, 18 injured</a>
* <a href='https://news.northeastern.edu/2017/01/05/new-study-finds-1-in-5-us-gun-owners-obtained-firearm-without-background-check'>New Study Finds 1 in 5 US Gun Owners Obtained Firearm without Background Check</a>
* <a href='http://www.smallarmssurvey.org/fileadmin/docs/F-Working-papers/SAS-WP14-US-Firearms-Industry.pdf'>Small Arms Survey</a>
* <a href='https://www.thetrace.org/2018/03/gun-background-check-staff-shortage-justice-department-budget/'>The Gun Background Check System Is Overburdened and Understaffed, DOJ Budget Request Shows</a>
* <a href='https://www.thetrace.org/2016/11/nra-gun-record-rating-system-straight-a-students/'>The NRA’s Straight-A Students</a>
* <a href='https://www.thetrace.org/rounds/how-many-guns-do-americans-own/'>The Trace: Just How Many Guns Do Americans Own? (And Why Do Estimates Vary So Widely?</a>
* <a href='https://towardsdatascience.com/what-can-machine-learning-tell-us-about-americas-gun-laws-da01d9fb7413'>What can Machine Learning Tell Us About America’s Gun Laws?</a>
* <a href='https://www.nytimes.com/interactive/2015/12/10/us/gun-sales-terrorism-obama-restrictions.html'>What Happens After Calls for New Gun Restrictions? Sales Go Up</a>

**Additional Resources**
* <a href='https://lilithelina.tumblr.com/post/135265946959/data-analysis-pearson-correlation-python'>Data Analysis (Pearson Correlation) - Python</a>
* <a href='https://support.minitab.com/en-us/minitab-express/1/help-and-how-to/modeling-statistics/regression/how-to/correlation/interpret-the-results/'>Interpret the Key Results for Correlation</a>
