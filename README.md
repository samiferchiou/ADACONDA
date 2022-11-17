# Applied Data Analysis - Project ADACONDA - 2023-2023

The purpose of this project is to analyse the [Youniverse](https://zenodo.org/record/4650046) database and to measure the impact of important NBA events on Youtube videos.


## Team Members
ABI FADEL Zad: zad.abifadel@epfl.ch <br/>
ADEYE ABiola: abiola.adeye@epfl.ch <br/>
BRUNO Etienne: etiene.bruno@epfl.ch <br/>
FERCHIOU Sami: sami.ferchiou@epfl.ch <br/>


## Abstract
With the rise of Youtube since 2005, the number of videos available on the internet tremendously grew. Youtube became a source for all kind od topics. This project intends to investigate the connection between NBA (National Basketball Association) videos available in our datasets (from 2006 to 2019) and some metrics of these NBA teams. In a first part, we try to get a global view of the dataset and mainly the evolution of sport videos and we compare it this development with the progression of NBA related videos. More precisely, we examine the overall tendencies that appear with time such as duration of sport and basketball videos or the interaction with these videos. In a further analysis we focus on the study of NBA videos and how they correlate with results, victory percentage and important events of NBA teams. This objective is to measure how key points impact popularity of teams and their videos on the Youniverse dataset. Finally, in a third part, 


We know that different audiences of different categories require specific treatment. Therefore, we first explore the entire dataset on a surface level before focusing on a handful of categories in our preliminary analysis to identify a possible gap with the most potential for a young person to become a renowned YouTuber. By investigating the key(s) to success we want to emphasize what is necessary with respect to commitment and volume to gain subscriptions and likes.

Abstract: A 150 word description of the project idea and goals. What’s the motivation behind your project? What story would you like to tell, and why?
Since its launch in 2015, Youtube became one of the most popular video sharing platform on the internet. Thanks to this popularity, 



## Reasearch Question:
- What is the evolution of the number of videos on Youtube within the study period ? Among all these videos, what is the proportion of videos discussing about sport ? Can we see an infatuation of the sport videos, and more precisely about basketball ?
- What the impact of large sport events and result on Youtube video interactions ?
- Is there a tendency in the length of sport videos (and of NBA related videos) ?
- How does the NBA calendar impact NBA videos on youtube ?
- How much does the results of a team impact their popularity ? (Popularity of a team is measured directly with the number of videos and of views ?
- Are some players more popular than their own team ? 
- How do players impact the popularity of their teams ?
- How does NBA teams manage to be more popular ? Is this popularity affecting their results ? 
- Is there a fan base in each NBA Team ? (Fans : people frequently interacting with a certain NBA team on Youtube) 
- Is the MVP always the most popular player ? 
- What is the correlation between the results of a team and the engagement of its fans for big market teams and small market teams 
- Can we predict the results of a team thanks to it’s popularity ?
- Can we predict the player’s transfers based on their popularity ?
- Is there seasonality in the basketball videos ?
- Are NBA fans following a single team or all of them ?
- How do the fans react to a bad performance of a team ? 
- How to develop a Fanbase on Youtube ? 
- Are small market teams fans more loyal than big market teams ? 


## Additional datasets
We used addional API to get infornation we can link to the Youniverse dataset.
  - [NBA API] (https://pypi.org/project/nba-api/) allows to obtain about game data (points, matches dates, teams info (nicknames, abbreviations, foundation year)...),
  - [Google Trend API] () giving popularity data
  - Scrapping from wikipedia to obtain, using Beautiful Soup, stadium data (location, attendance)
With this information, we have create a new SQL database hosted on our computer. This database is then used to query any information related to the performances of the NBA teams. This is mostly used in the second part of the project where we investigate the relation between teams' performances and the popularity of NBA videos on youtube.

For the example, our largest table is called `game_data` and has the following columns:
| Attendance | Time | Visitor | V PTS | Home | H PTS | Playoffs ? | V Pop | H Pop | Last Five | Capacity | Curr win % | Day of the week | Month | Match-ups | Rivalry | LS Win % |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|


List the additional dataset(s) you want to use (if any), and some ideas on how you expect to get, manage, process, and enrich it/them. Show us that you’ve read the docs and some examples, and that you have a clear idea on what to expect. Discuss data size and format if relevant. It is your responsibility to check that what you propose is feasible.

## Methods


## Proposed timeline


## Organization within the team: A list of internal milestones up until project Milestone P3.


ple around the globe. However, studying the platform is difﬁ-cult due to the lack of randomly sampled data and of system-atic ways to query the platform’s colossal catalog. In this pa-per, we present YouNiverse, a large collection of channel andvideo metadata from English-language YouTube. YouNiversecomprises metadata for over 136k channels and 72.9M videospublished between May 2005 and October 2019, as wellas channel-level time-series data of weekly subscriber andview counts. Leveraging channel ranks from socialblade.com,an online service that provides information about YouTube,we are able to assess and enhance the representativeness ofthe sample of channels. Additionally, the dataset also con-tains a table specifying which videos a set of 449M anony-mous users commented on. YouNiverse, publicly availableat https://doi.org/10.5281/zenodo.4650046, will empower thecommunity to do research with and about YouTube.

With the rise of YouTube since 2005, content creators rose to fame with an expanding follower base. Businesses saw this as an opportunity to sponsor their content, exploring marketing potential with creators. Nowadays, sponsorships are a common practice on the platform with many YouTubers making a living off of them.

But this practice does not come without its downsides. Spectators paying for a premium YouTube subscription are often annoyed by the ads that are forced upon them by their favorite YouTubers. Many creators have been accused of promoting services that they do not believe in, or even worse, that may be harmful to their audience.

This project aims to explore the relationship between YouTubers and their sponsors, and to determine whether or not sponsorships are beneficial to content creators. We hope to provide YouTubers with more information about their potential sponsors, and help them make more informed decisions.


## Overview
Here's a list of the relevant source files 

|Source file | Description|
|---|---|
|`notebook1.ipynb`           | The notebook you can run |
|`notebook2.ipynb`           | The notebook you can run |
|`notebook3.ipynb`           | The notebook you can run |
|`notebook4.ipynb`           | The notebook you can run |
|`notebook5.ipynb`           | The notebook you can run |

