---
layout: post
title:  "Vienna Kaggle - Selected Competitions"
subtitle: "Rossmann Store Sales, Right Whale Recognition"
date:   2015-11-02 21:00:00
categories: [other]
---

On our last meetup we decided to vote for the competitions that will be solved in the next [Coding Session][meetup-event] and today I will announce the winners: [Rossmann Store Sales][rossman-store-sales] and [Right Whale Recognition][right-wale-recognition]. Both competitions are equally interesting and challenging!

## Rossmann Store Sales

In the [Rossman Store Sales competition][rossman-store-sales] we need to forecast sales using store, promotion, and competitor data. One of the challenges in this competition is to transform the store data into a robust numeric model.

The store data looks like this:

|Store|Store<br>Type|Assortment|Competition<br>Distance|Competition<br>OpenSinceMonth|Competition<br>OpenSinceYear|Promo2|Promo2<br>SinceWeek|Promo2<br>SinceYear|Promo<br>Interval|
|---|---|---|---|---|---|---|---|---|----|
|1|c|a|1270|9|2008|0||||
|2|a|a|570|11|2007|1|13|2010|Jan,Apr,Jul,Oct|

The training data looks like this:

|Store|DayOfWeek|Date|Sales|Customers|Open|Promo|StateHoliday|SchoolHoliday|
|---|---|---|---|---|---|---|---|----|
|1|5|2015-07-31|5263|555|1|1|"0"|"1"|
|2|5|2015-07-31|6064|625|1|1|"0"|"1"|

Christian Thiele did an [amazing analysis][rossman-analysis] of the provided data in R, you should check it out before getting started. Paul Shearer created an [interactive visualization][rossman-visualization] of the sales data using dygraph. You can find more information and insights about the 2 scripts on the [scripts of the week][kaggle-scripts-of-the-week] section on Kaggle.

## Right Whale Recognition

In the [Right Whale Recognition competition][right-wale-recognition] we need to automate the recognition process using a dataset of arial photographs of individual whales and identify [North Atlantic Right Whales][right-whale-wiki]. One of the challenge in this competition is to extract descriptive features out of the training images which have been hand-labeled by experts. To better identify the whales, we have to understand the [Right Whale Callosity Patterns][right-whale-docs]. I found [this little game][right-whale-game] to get started.

Mathworks is providing a [Complimentary Software for MATLAB][matlab-kaggle] for this competition; however, in the Coding Session we will only use Open Source Software.

[meetup-event]: http://www.meetup.com/de/Vienna-Kaggle-Meetup-Machine-Learning-Competitions/events/226456065/
[rossman-store-sales]: https://www.kaggle.com/c/rossmann-store-sales/
[right-wale-recognition]: https://www.kaggle.com/c/noaa-right-whale-recognition/
[right-whale-wiki]: https://en.wikipedia.org/wiki/Right_whale
[right-whale-game]: http://www.neaq.org/education_and_activities/games_and_activities/online_games/right_whale_identification_games.php
[right-whale-docs]: http://www.neaq.org/conservation_and_research/projects/endangered_species_habitats/right_whale_research/right_whale_projects/monitoring_individuals_and_family_trees/identifying_with_photographs/how_it_works/callosity_patterns.php
[matlab-kaggle]: http://www.mathworks.com/academia/student-competitions/kaggle/
[rossman-analysis]: https://www.kaggle.com/thie1e/rossmann-store-sales/exploratory-analysis-rossmann
[rossman-visualization]: https://www.kaggle.com/shearerp/rossmann-store-sales/interactive-sales-visualization/notebook
[kaggle-scripts-of-the-week]: http://blog.kaggle.com/2015/11/05/october-2015-scripts-of-week/