# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends in theater kickstarters success and failures based on kickstarter goals and launch dates.
---
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater Outcome vs Goals](https://github.com/mmdemars/kickstarter-analysis/blob/resources/Outcomes_vs_Goals.png)
---
The highest number of theater kickstarters were launched in May when there were also the highest number of successes, and the lowest number were launched in December. The high number of kickstarters launched in May corresponds to the high number of successes, and while the number of failures in May was also the highest, the second highest number of failures were launched in October with a lower number of successes to match. The proportionally higher number of successes to failures in May seems to indicate that a theater kickstarter launched in May has a better chance of success than any other time of the year, while a theater kickstarter launched in October has a higher chance of failure.

### Analysis of Outcomes Based on Goals

![Theater Outcomes vs Goals](https://github.com/mmdemars/kickstarter-analysis/blob/resources/Theater_Outcomes_vs_Launch.png)
---
The highest number of successful play kickstarters were in the less than 1000$ range at a 76% success rate, followed by the 1000-4999$ range with a 73% success rate. The highest rate of failures at 100% was in the 45000-49999$ range, followed by the 50000$ or more at 86%. 

### Challenges and Difficulties Encountered

When looking at the Outcome of Goals data, it's east to get distracted by the percentages when the raw numbers aren't taken into account. A 100% failure rate has to be weighed against the fact that it was a singular campaign launched in that goal range, and the campaign was launched in November - the month with the second highest failure rate. The lower 88% failure rate in the 50000$ and up range has a higher weight with a higher number of campaigns launched within those goal parameters. 

## Results

- Theater kickstarters are more likely to have a successful outcome if launched in May, and are more likely to fail if launched in October.
- Theater kickstarters are more likely to succeed if a goal of under 4999$ is set (or 1000$, but the percentages are close); and are more likely to fail in the 45000-49999$ range. In the theater genre, lower goals seem to have a higher rate of success.
- Niether of these sets take into account the subject matter of the plays, or the cross section of goals and time launched. The failure of the singular 45,0000$ campaign for The Lizard King could have just as much to do with a disinterest in Jim Morrison as the goal or the launch date.
- Success rates of theater kickstarters over a span of years could be useful in determining the trends in theater interest over a larger span of time. A box and whiskers chart showing outliers in ranges of goals coud also be useful in identifying data that could be culled from the set for a more accurate picture of success vs failure.

