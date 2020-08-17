# An Analysis of Kiskstarter Campaigns

## Overview of Project
Louise, I appreciate the time you have given me to analyize the crowdfunding data from Kickstarter.        I have completed my analysis and will provide details of my findings in the information below. I believe   the time I have put in to organize, sort and anaylize the data has led to some discoveries of specific factors that will help make your campaign successful as you consider how to best use your estimated $10,000 budget to hopefully fund your play; "Fever".
### Purpose
Just to recap, the purpose of this project is to provide you with actionable information to successfully fund a theatrical play in the United States using Kickstarter crowdfunding data as the research source. I believe this information will help you better understand how to set up your campaign to closely duplicate previously successful crowdfunding campaigns.
## Analysis and Challenges
Analysis
1.	Beginning to Understand the Data I began my analysis by becoming familiar with the dataset. Since it is a large amount of data spanning many years, countries and specific topics, I spent time making sure the data was in a  readable format and that I was familiar with the cloumn headings and general content, checked the data for errors and bugs. I used Pivot Tables and Pivot Charts to gain a different perspective on the data by combining several data arrays in a Pivot Chart to search for specific trends, tendencies and outcomes. I found that a few of the columns needed to have the data split into additional columns to better understand what the data was revealing about the crowdfunding process.
2.	Customizing the Data
I also made sure the data was customized to provide visual feedback. That is, I used conditional formatting to add color to the data and make it easier to spot interesting information quickly. For example, I added color to the 'outcomes' column: 
 
![Analysis1](https://github.com/peteremiller/mykickstarter-analysis/blob/master/Resources/Analysis1.pnghttp://url/to/img.png)

I also created various charts in the analysis to assist the visualization of the data in telling the story of my analysis and hopefully make better sense of the data: 
	 					 

3.	Applying Formulas to the Data
To get the most benefit from the Crowdfunding data I needed to make use of powerful tools resident in Excel. I used several Excel formulas to organize, sort and generally dig deeper into the data to better understand the tendencies and relationships of the Kickstarter campaign data. Some of the formulas I used include:
VLOOKUP:	=VLOOKUP(A2, Kickstarter!B:E, 3, FALSE)

SUM: 		=SUM(B2+C4)

PERCENTAGES:	=(B3/N2)

MEDIAN: 	=MEDIAN(‘Insert Your Data Source’!M:M)

AVERAGE:	=AVERAGE(‘Insert Your Data Source’!K:K)

All of the formulas begin with the equal sign (=) and include various types of punctuation to separate the required fields necessary to perform the formula’s task. Formulas make working with large datasets much more efficient. 

Challenges

One specific challenge I overcame was converting time to a format humans can readily understand. The data was formatted with a Unix timestamp.                                  
![Timestamp](https://github.com/peteremiller/mykickstarter-analysis/blob/master/Resources/TImestamp.pnghttp://url/to/img.png)
                                                            
I had to convert the timestamp using a DATE formula that went all the way back to January 1, 1970 and counted every second, minute and hour that had taken place since the epoch (January 1, 1970) and the actual launch of a specific campaign noted by a timestamp in the ‘deadline’ and ‘launched at’ columns (see picture above). Once the conversion was made I could use the time to determine how long campaigns lasted, what time of the year most of the successful and failed campaigns to place, and which years the campaigns took place.

Further Possible Challenges

I believe there could have been more challenges along the way had I not spent adequate time at the beginning of the process to understand the data and check it for errors. Had I not prepared the data for use I am sure there would have been many errors in the analysis and conclusions would have been much more difficult to make. Secondly, had there not been a clearly stated purpose of the project and the budget, country and type of crowdfunding project already decided, I would have to make too many assumptions about the data and would not have a clear picture of what outcomes were desirable. Finally, had I not been able to use Pivot Tables and Charts, to enhance the visualization, this project would have been a disaster. The dataset is so large that the challenge of managing the numerous variables would have been extremely difficult. 

 ## Results
### Analysis of Outcomes Based on Launch Date
I believe there are at least two conclusions I can draw about the Theater Outcomes based on Launch Date analysis.
1.	The best time to launch a campaign is in either May or June. The data suggests that May has the best campaign outcome in the U.S. of all the months included in the dataset for Theater crowdfunding through Kickstarter. The data suggests that May exceeds expectations of outcomes, while June meets the outcome expected of 100% funding.

![Theater_Outcomes_vs_Launch](https://github.com/peteremiller/mykickstarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)
 
2.	The longer one waits to launch a Theater campaign in the U.S. the data suggests it is more likely the campaign will not meet the outcome goal desired. The data suggests that beginning a campaign in the Fall, Winter or early Spring will not result in the desired outcome.

### Analysis of Outcomes Based on Goals
I believe the data concludes the following about the Outcomes based on Goals:
1.	Based on the data provided about completed U.S. Theater campaigns using Kickstarter crowdfunding, I believe the proposed budget of $10,000 represents approximately 50% of the successful U.S. Theater crowdfunding campaigns done through Kickstarter. 
2.	According to the data the most successful crowdfunding campaigns can be found in the $35,000 to $39,999 and $40,000 to $49,999 ranges representing over 60% of the campaigns that reached or exceeded the campaign goal. 

 ![Outcomes_vs_Goal.png](https://github.com/peteremiller/mykickstarter-analysis/blob/master/Resources/Outcomes_vs_Goal.png)

### Challenges and Difficulties Encountered
I believe there some limitations and difficulties associated with this datasheet that you should take into consideration, Louise. They are listed as follows:
1. The dataset is from only one crowdfunding source, Kickstarter.  Would there be additional data available on other Websites or from other crowdfunding sources? The data from Kickstarter is a good start, but I would definitely want to see additional data from other sources before I made a final decision.
2. Crowdfunding is used as the primary source for funding “Fever’. What other financial sources are available that have produced successful funding campaigns for theatrical plays in the U.S.? Are there additional ways of raising funds that will help you reach your goal?
3. From my analysis it is difficult to know at 99.9% that your campaign will be successful and reach its goal. I believe there needs to be additional graphs that delve more into the statistical analysis of the data. 

![Outcomes_Based_On_Goals_US.png](https://github.com/peteremiller/mykickstarter-analysis/blob/master/Outcomes_Based_On_Goal_US.png)

Specifically, what are the trends in today’s market given we are in the midst of a Pandemic? The dataset does not provide data for 2020 and may present skewed results based on the need for more recent data, recent events in the U.S. concerning racial tensions, loss of employment and changes in spending/giving habits, etc.
I look forward to speaking with you in more detail about the analysis, Louise.

kickstarter_analysis done

