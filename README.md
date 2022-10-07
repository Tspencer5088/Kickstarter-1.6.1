# Kickstarting with Excel

## Overview of Project

### Analysis of Kickstarter campaigns with focus on parent category *Theater*, subcategory *Plays*.

## Analysis and Challenges

Analysis was performed strictly utilizing Excel functions. A filtered pivot table was used to create a line chart of outcomes based on launch date and filtered to parent category *Theater*. Also used to extract relevant data were three excel formulas: COUNTIF, SUM, and a simple division formula formatted as a percentage and rounded to nearest whole number. A final line chart was created with the formula data to illustrate the percentage of successful and failed fundraiser monetary goals specific to subcategory *Plays*.

What I found particularly challenging was getting the COUNTIF formula to return the correct count for the successful campaigns less than $1000. At first, I performed a simple filter and highlighted the cell to check the totals. The sum of all campaigns was significantly more than the previously filtered and highlighted cells. I rewrote the formula multiple times with the same outcome. Not trusting my count and needing to see the data in a different format, I created another pivot table to count the plays in each Goal category (less than 1000, 5000 to 9999, etc etc). Once all totals were confirmed via pivot table, I went back to my COUNTIF formula. It was then I discovered that I had erroneously made the formula to count *if greater than* 1000! After the minor correction, everything else flowed smoothly.

### Analysis of Outcomes Based on Launch Date

Two very prominent data point conclusions can immediatley be seen based on parent category *Theater* launch date outcomes.

* Successful campaings launched in the month April thru August have the highest success rates, with a peak in May. Therefore, we can conclude that summer fundraisers are optimum.
* Successful campaigns begin to decline out of normal range in October, with the lowest success rate occuring in December.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/112881617/194611012-f05a575b-5c35-4c65-af15-3464361d5f87.png)

### Analysis of Outcomes Based on Goals

Outcomes based on Goal and expressed as a successful or failed line graph also shows a few conclusions.

* As expected, the campaigns with a lower monetary goal are more successful and decline in success as the goal value increases. This is best illustrated by the charted percentage of failed fundraisers inversely mirroring the successful campaigns.
* Surprisingly, the sucessful campaigns experience a peak when the goal is between $35,000 to $44,999. As the below chart shows, setting a goal higher than $49,999 is a  death sentence for a fundraiser.
* Finally and also of note, there were zero (0) canceled campaigns within the subcategory of *Plays*.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/112881617/194614349-cbd2de58-a604-49b1-b1d4-c2cab3235d68.png)


### Challenges and Difficulties Encountered

## Results


- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
