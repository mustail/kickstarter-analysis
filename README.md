# Kickstarting with Excel

## Overview of Project

This project uses Kickstarter data on more than 4000 campaigns to summarize indices of success and failure. This summary data is then presented visually using line charts, with a focus on rates of success and launch dates.

### Purpose

This project aimst to help playwright Louise understand the factors that make Kickstarter campaigns successful. Using the insight from this project, Lousie will make better informed decisions to launch an effective crowdfunding campaign for her upcoming play.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

[image embed theater outcomes]

As can be seen from the above chart titled "Theater Outcomes Based on Launch Date," the data at hand shows that those campaigns that were launched in the months of May, June, and July fared the best, followed by April and October.

As for the failed campaigns, while there is a limited correlation between successful campaigns and the failed ones, it can be said that failures were spread more a roughly consistent number of campaigns failed regardless of the launch date. Similarly, a very limited number of campaigns were canceled notwithstanding the timing. This more or less even spread of both the failed and the canceled campaigns indicates that the eventual failure does not directly depend on the timing of the crowdfunding campaign.

Also comparing the Theater subcategory to the rest of the campaigns in the dataset, one can see that there is an uptick in the Fall for most campaigns while the same kind of an increase in success is not replicated for the Theater. [Link Outcome based on launch date.]

### Analysis of Outcomes Based on Goals

[embed the image goals vs]

There is a clear indication that the lower the funding goal is, the higher the rate of success. This is true for the most part with the exception of the funding range between $35,000 and $45,000. This is difficult to explain with the data we have at hand, however, as I discuss below under the section "Challenges and Difficulties," there are two few number of campaigns that make up the data for the campaigns with the highest funding goals.  

In the case of failures, the goals-oriented analysis reveals a striking difference compared to my launch date-oriented analysis above. Here, the failure rate is clearly related to the original goals of the campaign.

### Challenges and Difficulties Encountered

A minor challenge was to conver the UNIX timestamps to human-readable dates, which I was able to overcome using the DATE function.

I noticed that my table for the Outcomes Based on Goal displayed no canceled campaigns in the Plays category. I went back to the original sheet to check and confirmed my formula. I think this is still an interesting point to think about. It may be a case of incomplete data or inaccurate identification.

Another issue has to do with the limited amount of data for the campaigns with higher funding goals. Compared to the campaigns with lower goals, the dataset for campaigns with the highest goals (e.g. above $25,000) is very limited. To give an example, there is a total of 1005 campaigns with a goal of less than $25,000 while the category for the $25,000-30,000 has only 42 campaigns. This stark gap in the amount of information between lower-aimed campaigns and the higher-aimed ones make it difficult to draw conclusions with the same degree of certainty in the latter category.

## Results

To launch a theater-related campaign, it seems that the best months are April, May (especially), and the early Summer months of June and July. It makes sense, therefore, that *Louse set up her campaign to launch no later than April, preferably in May*.

Seasonality is a clearer aspect of crowdfunding campaigns in the Theater subcategory. The decline from Summer to Fall is much clearer compared to a still strong showing of all other categories in the Fall. *The earlier in the Spring may be better as success rates for Theater campaigns decline into the middle of the Summer.* 

*Louise should set a moderate funding goal* for her crowdfunding campaign to be successful and should target the category average for her goal maximum.

As for the limitations of the data, I would like to cite two: The first is the live campaigns, which we could not use for this assignment. The insight from them would have added to our understanding of the problem. Secondly, as I said above, there are very few entries for certain categories across funding goals. This may be because the dataset is incomplete, or the values are misidentified, or another reason difficult to guess.

To show the limitations of the data and complement it with a broader understanding of all genres, we should create tables to display the total number of entries for the lower and upper half (or quarters) of the funding goal categories.
