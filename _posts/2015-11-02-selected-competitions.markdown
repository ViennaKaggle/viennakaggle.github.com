---
layout: post
title:  "Vienna Kaggle - Selected Competitions"
subtitle: "Rossmann Store Sales, Right Whale Recognition"
date:   2015-11-02 21:00:00
categories: [other]
---

On our last meetup we decided to vote for the competitions that will be solved in the next [Coding Session][meetup-event] and today I will announce the winners: [Rossmann Store Sales][rossman-store-sales] and [Right Whale Recognition][right-wale-recognition]. Both competitions are equally interesting and challenging!

## Rossmann Store Sales

In the [Rossman Store Sales competition][rossman-store-sales] we need to forecast sales using store, promotion, and competitor data. One of the challenges in this competition is to transform the store data into robust numeric model.

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

## Right Whale Recognition

In the [Right Whale Recognition competition][right-wale-recognition] we need to automate the recognition process using a dataset of arial photographs of individual whales and identify [North Atlantic Right Whales][right-whale-wiki]. One of the challenge in this competition is to extract descriptive features out of the training images which have been hand-labeled by experts.

Mathworks is also providing a [Complimentary Software in MATLAB][matlab-kaggle] for this competition.

[meetup-event]: http://www.meetup.com/de/Vienna-Kaggle-Meetup-Machine-Learning-Competitions/events/226456065/
[rossman-store-sales]: https://www.kaggle.com/c/rossmann-store-sales/
[right-wale-recognition]: https://www.kaggle.com/c/noaa-right-whale-recognition/
[right-whale-wiki]: https://en.wikipedia.org/wiki/Right_whale
[matlab-kaggle]: http://www.mathworks.com/academia/student-competitions/kaggle/