Explanation of Statistic

For the sabermetrics final project, I choose to investigate and provide an argument based on data that either supports of denies the “hot hand fallacy” as it relates to a player’s batting performance. Then I created a hot hand statistic which determines how much an individual’s offensive results is affected by their hot hand. The hot hand fallacy, “is the purported phenomenon that a person who experiences a successful outcome has a greater chance of success in further attempts”  . In reference to a player’s batting, the hot hand fallacy means that if a player has a successful at-bat, how does that change the probability of them having a successful at-bat the next time that they are up to bat. Additionally, how does this probability change as the player has more than one successful at-bat in a row.

I began by choosing twenty players for whom I would collect batting data from the 2018 season using Statcast data. There were several prerequisites that each player that was chosen had to fulfill in order for me to choose them to calculate their hot hand statistic. For starters, they had to have played in at least 120 games in the 2018 season. I choose this number because it was the highest number of games that I could choose and still have an appropriately sized pool of eligible players remaining, but I set the number high enough that I would have the largest possible set of data from the 2018 season. Notice that this requirement had the side effect of disqualifying any pitchers since none had that quantity of games played but I was fine with this tradeoff since I wanted to maximize the amount of data I had to work with. Additionally, I tried to choose players from a variety of different teams and positions so that the statistic was not skewed in any way but things such as park factor, or a specific teams game strategy that might in some way bias the statistic. After selecting 20 players, I then began collecting their relevant batting data which I would use to generate a player’s hot hand statistic. The method for this was to go through each of a players at-bats from a player’s 2018 season chronologically. For each at-bat I would track how many of the previous at-bats were a success. As a note, I interpreted a successful at-bat as one that resulted in either a hit, walk, or sacrifice fly as I consider all of these to be successful outcomes although I see how one might argue that point regarding, specifically, sacrifice files. Now, knowing how many of the previous at-bats in a row were a success, I can gather the relevant offensive data going from 0 successful attempts in a row, to as many as 4 previous at-bats in a row being successful attempts.

I took this data and turned it into a useful and clear to read and interpret statistic by creating the following equation; Hot Hand (HH)=1∗(BA after 1 successful AB - Overall BA)+2∗(BA after 2 successful AB - Overall BA)+3∗(BA after 3 successful AB - Overall BA)+4∗(BA after 4 successful AB - Overall BA). To summarize the equation, I find the difference between the modified batting average (includes walks and sac flies) and the players regular modified batting average and then multiply that number by n where n is the number of previous at-bats that were a success up to 4. The reason that I multiply it by a higher number based on the number of successful previous attempts is that I believe it is more and more indicative of a player’s hot hand, if they are seeing increased success as their streak continues to increase. Something to observe about the method of calculating this statistic is that it is possible for a player to have a negative hot hand statistic. In fact, when calculating the hot hand statistic, there are quite a few players who have negative values. I call this having a cold hand since a value of zero means that past successful attempts had no effect on the players batting average, so for the value to be negative means that the player performed worse when coming off of successful batting attempts.

The statistic that was discussed in class that is most similar to the hot hand statistic that I have create would probably be the statistic determining the clutchness of a player. I know that this is not one of the more traditional baseball statistics, but I do think that it shares a lot in common with the statistic that I created in the sense that there is some general debate over the topic of whether or not a player can actually be clutch just like there is debate whether or not players can actually have a hot hand and do better after having recent previous success. Additionally, the statistics share the fact that they take data from specific scenarios that batters find themselves in during a game such as those that constitute a clutch situation for the clutchness statistic or one in which the player has had four consecutive successful at-bats for my hot hand statistic.


The reason that I believe that this is a good statistic is because it provides a value to something that is not easily quantified which, at a base level, is how streaky a player is. I believe that one issue with many existing baseball statistics, especially as they relate to offense and batting, is that it does not take into account any of a players previous at-bats in predicting their current performance. On a per game basis I think that this can be flawed because a player, might for example perform particularly well against the specific pitcher who they are against and so if they have a batting average of, say, 0.300 for the entire season up until that point, I think that it would be incorrect that they have a 30% chance of hitting the ball because there are other factors at play that are influencing the chance of success. This is the reason that I believe that this is a valuable statistic and one that could be part of a larger statistic which takes into account many factors such as, hot hand, who the pitcher is, what park you’re in, and potentially more to predict the chances of a players success for a specific at-bat instead of simply looking at a more static statistic such as batting average. On a more practical level, I think that an additional benefit that this statistic could provide to a team, is that if the team is trying to determine who to substitute in as a pinch hitter, one helpful thing to look at could be the players hot hand statistic in addition to how many of their previous at-bats have been a success as this might be a reason to choose one player over another if, for example, a player’s batting average increases from 0.250 to 0.350 when they’ve had zero successful at-bats versus four consecutive successful at-bats, if that player happens to have had four successful at-bats in a row, it could be a better decision to put them into pinch hit. This kind of reasoning is something that could only be done using the hot hand statistic as other existing offensive batting metrics are not going to take into account recent past performance as a tool for predicting the players batting outcome.
