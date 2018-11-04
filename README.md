# Title

Fake News : What ? When ? and Why ? Who can tell ?

# Abstract
A 150 word description of the project idea, goals, dataset used. What story you would like to tell and why? What's the motivation behind your project?

The theme of this year is "Data Science for social goods". We will try to follow this theme by helping people not believing everything they see by giving certain directional axes. In order to do so, we will first establish some facts drawn from the data to show how much fake news can affect us and how the crowd can easily be fooled. We will also try to show that some news (not necessarily false or true : we will use for example the false-true or barely true labels) are made to create doubt and decredibilize some people or organizations. We will try to give some directions by trying to find recurrent patterns of fake news, their features, their trends and how they are delivered in order to warn people to always cross check their references to avoid being fooled half of the time. 



# Research questions
A list of research questions you would like to address during the project. 

- Repartition of the provenance of these fake news. (LIAR)
- Repartition in time of the aggregation of fake news in total, and according to their provenance (LIAR)
- Make the connection between a fake news (LIAR) and the number of tweet (and retweets) by subject (IRA) :
Are there some subjects that have buzzing way more than others, why ?? If it is possible to know when it happened, try to find a justification for it.
- Do most of the fake news come from one particular political party ? Are there reason for it ? Is it the opposing party versus the ruling power ? Is it the other way around -> Propaganda ?
- Is it possible to draw some inferences from it ? Is it more likely to have fake news from either region, party ? How to identify them ? what ressources are mostly used for fake news ? Social media? Press release ? ....
- Can we identify them ? Can we classify some sources as reliable from the dataset , through some credit history ?


# Dataset
List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show us you've read the docs and some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.

We use two data sets :  The LIAR and IRA datasets.

- LIAR Data set :
10269 human labeled short statements s from POLITIFACT.COM’s API.
** labels : pants-fire, false, barelytrue, half-true, mostly-true, and true (distribution pretty-well balanced)
** other attributes : subject, author of the statement, what the author represent (media, government..), geographic origin (Us state), political party of the author, the credit history vector of the author (counts of pants fire, false, barelytrue...) and the where the statement was emitted. (campaign debate, press release, website...)

-  Data Set : 
8 CSV sheets of more than 370k rows + 1 sheet of 37k rows(sheets differ by their author). Each row represent Tweets of IRA (Internet Research Agency) trolls about U.S politics. 77% of the tweets are in english while 13% in Russian and other languages represent 11% of the data. We will only consider english tweets here.
Each tweet is described by its author, the content, the region it comes from, the language used, its publication and harvested date, the number of people following the author and the number of people he is following, the number of update of the current tweet(I think it is the number of retweets, likes.. ?), and the post category, is it an original tweet or a retweet ?

# A list of internal milestones up until project milestone 2
Add here a sketch of your planning for the next project milestone.

The milestone 2 is due for November 25, until then, here is a tentaive schedule we will try to follow.

- November 11 : Data Exploration : Distribution of fake news among author/group/organisations, where they come from, when are they released if possible. Exploration of the IRA data set, can we find patterns, clusters ?
- November 18 : Draw some inferences from the data. Make some links/connections between the two data set and think on how best we can extract meaningful informations from the combination of both.
- November 25 : Complete Analysis description of the two previous steps and plan the next steps for milestone 3 : which direction do we need to continue to follow, which one to remove and think if we will need extra informations/data to complete our story. 

Hand over this milestone.


# Questions for TAa
Add here some questions you have for us, in general or project-specific.

Among the directionnal axes given/proposed, which one are more/less feasible and relevant ?
