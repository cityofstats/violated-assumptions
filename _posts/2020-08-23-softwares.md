---
published: true
layout: post
date: '2020-08-23 11:30:00 +0800'
author: Billy Bluetooth
categories: software
tags: stats
cover: assets/wowpic.jpg
---
## Examining Different Statistical Softwares

Hello, friends.  Today, we will take a deep dive into the world of statistical softwares.  Software has become a necessity for statisticians, and 

## The Free and Open Source
# 1- R
R is the defacto free and open source statistical computing software.  While its reign is being seriously challenged by python, R (in our opinion) retains an advantage for a number of reasons.  For one, R is just a little easier to use and get started with.  All the statistical functions and plotting capabilities are available in base R, to get the equivalent data frame structures and plots in python, you need to be familiar with pandas and matplotlib.  If you do want to get fancy with R, there are also sublanguages you can verse yourself in, such as the tidyverse by Hadley Wickham, which is essentially another language written within R based on piping operators and fancy plots.  Alternatively, data.table package is faster than the tidyverse with almost all the capabilities, even if it is not quite as intuitive to use.  

The main advantage for R (again in our opinion) is just how incredible R-shiny is.  Yes, DASH and plotly in python are great (DASH and plotly can also be used for R).  But, R-Shiny is much older and has a much bigger online base.  With enough time and effort, you can make an R-shiny app that rivals that of Tableau or QLik, which are both quite expensive.  Additionally, R-Shiny gives users 5 free sites where they can store their apps.
<a href="https://miro.medium.com/max/521/1*bl7hSugBuCihsFz9CVYieA.png" data-lightbox="falcon9-medium" data-title="Rstudio">
  <img src="https://miro.medium.com/max/521/1*bl7hSugBuCihsFz9CVYieA.png" title="Rshiny">
</a>
# Python
Python is now generally regarded as one of the two must-know languages for the modern data scientist.  A powerful high level programming language, Python is popular amongst many different professions.  It reads like english.  Its got a huge online support system.  There are thousands, if not millions of packages.  It has (essentially) sub-languages that allow it to mimic statistical software such as R, and allow for complicated machine learning algorithms to be used pretty easily.  It's a language that introductory students don't fear, and top level programmers (sometimes) love.  You can interface with lower level languages, such as C. Finally, new plugins such as DASH allow for cool web applications to be made relatively easily. With all these features, python seems like an easy choice for the young statistician.  But, there are some flaws.

Like all high level languages, python suffers from speed issues.  One thing you sacrifice with readability is how long everything takes.  For example, C can be up to 100 times faster than python, and for some complicated simulations (like weather modeling), running code in python will crash your server.  But, it would be much easier to write and easier to explain to new hires/students who want to tamper/edit/expand on the code.  

<a href="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.vizteams.com%2Fwp-content%2Fuploads%2F2013%2F08%2Fpython-logo-master.png&f=1&nofb=1" data-lightbox="falcon9-medium" data-title="Python Logo">
  <img src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.vizteams.com%2Fwp-content%2Fuploads%2F2013%2F08%2Fpython-logo-master.png&f=1&nofb=1" title="Python Logo">
</a>
> Python was my first love- Marethyu
