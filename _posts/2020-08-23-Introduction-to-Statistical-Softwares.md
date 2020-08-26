---
published: true
layout: post
date: '2020-08-23 11:30:00 +0800'
author: Billy Bluetooth
categories: software
tags: stats
cover: null
---
## Examining Different Statistical Softwares

Hello, friends.  Today, we will take a deep dive into the world of statistical softwares.  Software has become a necessity for statisticians, and will only become more important in the coming years.  This is reading just like any medium post about data science...we need to pick up our game...and soon.

## The Free and Open Source
#  R (9.5/10)
R is the defacto free and open source statistical computing software.  While its reign is being seriously challenged by python, R (in our opinion) retains an advantage for a number of reasons.  For one, R is just a little easier to use and get started with.  All the statistical functions and plotting capabilities are available in base R, to get the equivalent data frame structures and plots in python, you need to be familiar with pandas and matplotlib.  If you do want to get fancy with R, there are also sublanguages you can verse yourself in, such as the tidyverse by Hadley Wickham, which is essentially another language written within R based on piping operators and fancy plots.  Alternatively, data.table package is faster than the tidyverse with almost all the capabilities, even if it is not quite as intuitive to use.  

The main advantage for R (again in our opinion) is just how incredible R-shiny is.  Yes, DASH and plotly in python are great (DASH and plotly can also be used for R).  But, R-Shiny is much older and has a much bigger online base.  With enough time and effort, you can make an R-shiny app that rivals that of Tableau or QLik, which are both quite expensive.  Additionally, R-Shiny gives users 5 free sites where they can store their apps.

R-studio remains one of the most powerful arguments for choosing R.  R-studio is the default IDE for most R users. It is easy to download, easy to read, allows the user to easily import datasets and packages, and is easy to update.  Additionally, R-studio makes it 

To summarize, R gets the top nods because it is the easiest, has great web-interfacing capabilities, R-studio is a great IDE, and is specifically designed for statistical computing.  The negatives are the computation speed lags as well as the limitations for general purpose programming, an issue which is largely caused by R not being a good language to use for object oriented programming.  
<a href="https://miro.medium.com/max/521/1*bl7hSugBuCihsFz9CVYieA.png" data-lightbox="falcon9-medium" data-title="Rstudio">
  <img src="https://miro.medium.com/max/521/1*bl7hSugBuCihsFz9CVYieA.png" title="Rshiny">
</a>
# Python (9/10)
Python is now generally regarded as one of the two must-know languages for the modern data scientist.  A powerful high level programming language, Python is popular amongst many different professions.  It reads like english.  Its got a huge online support system.  There are thousands, if not millions of packages.  It has (essentially) sub-languages that allow it to mimic statistical software such as R, and allow for complicated machine learning algorithms to be used pretty easily.  It's a language that introductory students don't fear, and top level programmers (sometimes) love.  You can interface with lower level languages, such as C. Finally, new plugins such as DASH allow for cool web applications to be made relatively easily. With all these features, python seems like an easy choice for the young statistician.  But, there are some flaws.

Like all high level languages, python suffers from speed issues.  One thing you sacrifice with readability is how long everything takes.  For example, C can be up to 100 times faster than python, and for some complicated simulations (like weather modeling), running code in python will crash your server.  But, it would be much easier to write and easier to explain to new hires/students who want to tamper/edit/expand on the code.  

<a href="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.vizteams.com%2Fwp-content%2Fuploads%2F2013%2F08%2Fpython-logo-master.png&f=1&nofb=1" data-lightbox="falcon9-medium" data-title="Python Logo">
  <img src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.vizteams.com%2Fwp-content%2Fuploads%2F2013%2F08%2Fpython-logo-master.png&f=1&nofb=1" title="Python Logo">
</a>
> Python was my first love- Marethyu


## The Pay to Play bois
Hate these.  But, many have cool logos. 

# Microsoft Excel (6/10)

This is a tough one.  Excel obviously has its limitations: its slow, its clunky, it crashes a lot, its hard to reproduce, and it doesn't have great looking graphics.  But, and this is a big but, it is the best way to get going in statistics.  For many, excel is the first software they use in college.  It is a cool way to visualize your data, it allows the user to easily edit and filter data, and allows for immediate visualization.  If you really push the macros in excel, you can actually program some impressive things.  The plugins allow you to do stuff like regression or finite difference methods, which are big tools used a lot.  

But, as a statistician, the most important thing is reproducibility.  To use some excel plugins, you need to watch a video and mimic what they did.  With a scripting language like python, you just copy written code and run. The code is written in English and is often commented so you know what is going on.  If you edit data in R or python, you leave a paper trail of exactly what you did, whereas in Excel there is no evidence.  Given the importance of data ethics, this is very dangerous.  

Also, excel costs money.  You pay for it alongside word and powerpoint with the microsoft package, so that breaks the cardinal rule of the VA: "If it's free, it's for me".


## Visualization Specifics
These are not as powerful modelers, but allow for pretty graphics and interaction.

# Flourish (10/10)

Flourish is the best visualizing software when all things are considered.  It is free, it is very easy to use, and it is a pioneer for different types of visualizations.  Here is an example of the bar-chart race, where they  <a href="https://public.flourish.studio/visualisation/1005923/" class="readmore">flourish</a>.  Flourish also gives users free server storage, so you can make a cool visual and send it to people via a link, or put it on a site, and the recipient need not be well versed in coding or have access to your data to see the visual.  Cannot stress enough how cool that is.

# Qlik (7/10)
The only experience we have with <a href="https://www.qlik.com/us">Qlik</a> was a free trial.  It was pretty powerful, and relatively easy to get cool dashboards up and running with good looking visualizations.  However, we found the online help community to be lacking, meaning once you run into a problem, you're toast in the water.  However, Qlik is typically used at companies (certainly not for research or academics), so presumably you'd have colleagues to help you.   

Qlik is definetly limited in terms of modeling.  For one, in order to be able to study big datasets, you'd have to pay big bucks.  Otherwise, you're basically cleaning and visualizing small datasets, which is fine in the exploratory stage, but limits you in more intense endeavours.  In that case, we'd recommend going to R or python. When R and python's computational limits hinder you, then C++/Fortran (or maybe one day Rust) is the go to (this applies if you are implementing a machine learning algorithm from scratch, for example).  


# Tableau (NA)
Personally, have never used tableau, but check out their site <a href="https://www.tableau.com/trial/tableau-software?utm_campaign_id=2017049&utm_campaign=Retargeting-CORE-ALL-ALL-ALL-ALL&utm_medium=Paid+Search&utm_source=Bing&utm_language=EN&utm_country=USCA&kw=tableau&adgroup=WEB-Brand-Core-E&adused=&matchtype=e&placement=&msclkid=02f6331261bc1e46a5c16c5729ea611b&gclid=CLbX1tnutusCFY_FfgodlSkGyQ&gclsrc=ds">tableau</a>

