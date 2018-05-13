--- 
title: "`R` Examples for Statistical Learning"
author: "[Ruoqing Zhu](https://sites.google.com/site/teazrq/)"
date: "2018-05-13"
github-repo: teazrq/resl
url: 'http\://teazrq.github.io/resl/'
knit: "bookdown::render_book"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib]
biblio-style: apalike
favicon: "favicon.ico"
link-citations: yes
urlcolor: cyan
description: ""
---



# Preface {-}

Welcome to `R` examples for Statistical Learning! I started this project during the summer of 2018 when I was preparing for the Stat 432 course, which was taught by our former faculty member [David Dalpiaz](https://daviddalpiaz.com/teaching.html), currently at The Ohio State University. David introduced to me this awesome way of publishing website on GitHub, which is very efficient approach for developing courses. Since I also teach Stat 542 (Statistical Learning) during the previous two years, I figured it could be benifical to integrate what I have to this [existing book](https://daviddalpiaz.github.io/r4sl/) by David, and use it as the R material in both courses. As you can tell, I am not being very creative on the name, so `RESL' it is. You can find the source file of this book on my [GitHub](https://teazrq.github.io/resl/). 

## Target Audience {-}

This book is targeted at advanced undergraduate to MS students in Statistics who have some or no prior statistical learning experience. Previous experience with both statistical modeling and `R` are assumed.

## What's Covered? {-}

I currently plan to include the following topics:

1. Prerequisites (Statistics and Probability)
2. Using `R`, RStudio and RMarkdown
3. Linear and Penalized Linear Regressions
4. Optimization Basics
5. Unsupervised Learning
6. Classification
7. Nonparametric Statistical Models
8. Machine Learning Models
9. Appendix

The goal of this book is to introduce not only how to run some of the popular statistical learning models in `R`, but also touches some basic algorithms and programming techniques for solving some of these models. For each section, the difficulty may graduatly increase from an undergraduate level to a graduate level. 

It will be served as a supplement to [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) for [STAT 432 - Basics of Statistical Learning](https://go.illinois.edu/stat432) and [The Elements of 
Statistical Learning: Data Mining, Inference, and Prediction](https://web.stanford.edu/~hastie/ElemStatLearn/) for [STAT 542 - Statistical Learning](https://go.illinois.edu/stat542) at the [University of Illinois at Urbana-Champaign](http://illinois.edu/).

**This book is under active development** as I am teaching Stat 432 druing Fall 2018. Hence, you may encounter errors ranging from typos, to broken code, to poorly explained topics. If you do, please let us know! Simply send an email and I will make the changes as soon as possible. (`rqzhu AT illinois DOT edu`) Or, if you know `rmarkdown` and are familiar with GitHub, [make a pull request and fix an issue yourself!](https://github.com/teazrq/resl). These contributions will be acknowledged. 

## Acknowledgements {-}

The initial contents are derived from David Dalpiaz's book. And I also inccorperated many online resources, such as 

- [bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)
- [R Programming for Data Science](http://r4ds.had.co.nz/)
and others though google search.

## License {-}

![This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).](images/cc.png)