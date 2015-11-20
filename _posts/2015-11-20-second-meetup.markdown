---
layout: post
title:  "Vienna Kaggle - First Hands On Meetup"
subtitle: "How it all starts"
date:   2015-11-20 06:00:00
categories: [meetup]
---

Yesterday our [second Meetup][meetup-event] concluded successfully. In short, the amount of people could be higher, but the quality of the people who showed and the fun were definitely there. This time the sponsor was our hosts company [GESIM][sponsor], who took care of pizza, coke and beer. As always, people with an entire different background and different skills came together with but at least one common interest: Data Science. Even though we didn't reach our first goal, i.e., submitting a proper result to the Kaggle competition page, we defined a few things, that will guide us through the upcoming event. These things are summarized here.'

The first big thing to remark is, that we - quite naturally - decided to only not team up in teams of two, but to work together as a whole Vienna Kaggle group. Everyone is suppposed to share ideas and skills and submit some code to the common [Rossmann repository][rossmann-repo]. This implies, you noticed correctly, that we worked on only one of the two previously chosen competitions. This is also the best way to get the most out of these Meetups: 
* having fun
* getting to know each other and
* learning new useful and interesting stuff all at the same time.

As mentioned before, we are a heterogenous group with one common interest. Everyone can work with their preferred tools and skills (python, R, Java,...), but we definitely found, that the people who were there yesterday, want to use python. In order to not leave anyone behind and get everyone productive we guided the ones without python background through the setup process of their data science environment. We basically defined, the most basic packages that they need and helped installing them. If you choose to join the next time you can already install the following packages or just drop by completely unprepared - we will help you anyway:
* pandas
* matplotlib
* scikit-learn

On Windows download and install the [Anaconda][anaconda] python distribution frome here and then use the "conda" command line tool to add this packages via "conda install <package-name>".
On iOS installing pip first is an easy way to get started: sudo homebrew install <python-pip>. Then add the packages via "sudo pip install <package-name>"
On your favourite linux distribution use the installed package manager to install python-pip and add packages using pip the same way.

Some of us were a little more productive, others were talking about their common past (Seriously, it's amazing how small the world is...'). Anyway, we defined some guidelines on how to work together this day and any future meetup. It boils down to:
* Each competition we work on is a new repository
* As mentioned before, we work individually on our "IPython notebooks" but as a team
* Therfore we will have an upper level project structure like /data, /python, /R, /XYZ
* In the data directory, we will share the challenge data, if and only if it is below 5 MB.
* The a few directories follow named by the general tool set/language we will use.
* The "language" directory such as the /python dir contains a utils.py file in which we put methods and classes, useful and to be reused by all of us.
* Furthermore the language directory contains a directory, named individually by the Kaggler who is working on it. We defined it to be the first name, but I guess it doesn't matter as long as it is a unique name. For the python case, this is the place to store the Ipython notebook file(s).
* Another thing we evaluated is, that we would enjoy working on a data set every time instead only every second time we meet.
* Instead I suggest - something I come up as of writing this, so please leave a comment if you like my suggestion: I think it would be nice if one person could prepare some features of, e.g., scikit-learn and talk about it for about 10 min. to introduce useful topics to all of us. Even if the person, who is talking about it, is not previously familiar with the topic. What do you think about it?

In summary, if you have not been there personally you seriously missed out on something. If you want to join the project anyway, just leave a comment and your github username to get access to the repo. Nevertheless, I would recommend you to join us personally next time - it was really fun (Don't make me mention it another time).

See you the next time,

\Stefan

[anaconda]: https://www.continuum.io/downloads
[meetup-event]: http://www.meetup.com/de/Vienna-Kaggle-Meetup-Machine-Learning-Competitions/events/226055752/
[rossmann-repo]: https://github.com/ViennaKaggle/rossmann-store-sales/
[sponsor]: http://http://gesim.ch/
