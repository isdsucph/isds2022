---
title: Course readings
date: 2022-06-17
markup: mmark
---


Textbook for general introduction to social data science:  
- **[Big by Bit - Social research in the digital age](https://www.bitbybitbook.com/)** by Matthew J. Salganik **[BBB]**, free online version [here](https://www.bitbybitbook.com/en/1st-ed/preface/).

Textbooks for data science in Python   
- **[Python for Data Analysis, 3rd ed.](https://wesmckinney.com/book/)** (2022) by Wes McKinney **[PDA]**
- **[Python Machine Learning, 3rd ed.](https://www.packtpub.com/product/python-machine-learning-third-edition/9781789955750)** (2019) by Sebastian Raschka & Vahid Mirjalili **[PML]**


## Preparation and Assignment 0

The course begin with your preparation for the teaching. This consists in Assignment 0 which is a learning module and assignment together. In terms of teaching it provides  an overview of basic Python and how to use it for data analysis. We also introduce markdown for writing text that allows simple formatting in plain text.

#### Required reading

- DataCamp 2016, ‘Jupyter tutorial’, available [here](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
- PDA: sections 1.1-1.3, 4.1, 5.1-5.2 as well chapters 2-3.
- Nolan, John. 2015. "[How to Write Faster, Better & Longer: The Ultimate Guide to Markdown](https://blog.ghost.org/markdown/)."

#### Inspirational reading and other sources for learning

There are many good resources for learning how to master data structuring. See below for two ways of self-learning:

- DataCamp offers further smaller courses on pandas and data structuring
- Rada, Greg. 2013. "[Intro to pandas data structures](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/)"- read all three sections.


## Session 1: Introduction to the course and Python

We introduce the course and provide an overview of logistics. We also introduce git and GitHub that we are working with.

#### Required readings

**Introduction to Social Data Science**
- BBB: chapter 1

- Grimmer, Justin. ["We are all social scientists now: how big data, machine learning, and causal inference work together."](https://web.stanford.edu/~jgrimmer/bd_2.pdf) *PS: Political Science & Politics* 48.1 (2015): 80-83.
- Buyalskaya, A., Gallo, M. and Camerer, C.F. 2021. ["The golden age of social science."](https://www.pnas.org/doi/10.1073/pnas.2002923118) *Proceedings of the National Academy of Sciences* 118(5):

**Git - a tool for storing and sharing code**
- Jones, Zachery. 2015. "[Git & Github tutorial](http://zmjones.com/git-github-tutorial/)".

#### Inspirational reading `*`

If you’re interested, and want to delve deeper into coding and programming (it's optional!), we highly recommend the following posts and articles:

- [The Scientist: Get With the Program](http://www.the-scientist.com/?articles.view/articleNo/43632/title/Get-With-the-Program/)
- [Economist on the Rise of Python](https://www.economist.com/science-and-technology/2018/07/21/python-has-brought-computer-programming-to-a-vast-new-audience)
- [What is Code?](http://www.bloomberg.com/graphics/2015-paul-ford-what-is-code/?cmpid=twtr1)

A broad, early, and easy-to-read idea of data driven (social) science:

- Anderson, Chris. 2008. "[The end of theory: The data deluge makes the scientific method obsolete](https://www.wired.com/2008/06/pb-theory/)." *Wired*, 16-07.


## Sessions 2: Data structuring 1
We learn about data transformation and working with specific data types in pandas: string, missing, categorical and temporal.

#### Required reading

- PDA: Chapter 5, Chapter 7: section 7.2 p. 213-215 (Replacing Values and Renaming Axis Indices), section 7.4: p. 227-229 (Stop at Regular Expressions), section 7.5 p. 236-245 (Categorical Data) and Chapter 11: sections 11.1-11.2.

#### Inspirational reading `*`
- Lohr, Steve. 2014. "[For Big-Data Scientists, ‘Janitor Work’ Is Key Hurdle to Insights](https://www.nytimes.com/2014/08/18/technology/for-big-data-scientists-hurdle-to-insights-is-janitor-work.html)"


## Session 3: Data structuring 2

We round-off data structuring by learning two powerful tools in data structuring: combining different data sets and the-split-apply-combine framework which is called `groupby` in pandas.

#### Required reading
- PDA: Chapter section 7.1 + section 7.2 p. 210-211 (Removing Duplicates), Chapters 8 and 10.

#### Inspirational reading `*`
- Wickham, Hadley. 2011. “[The Split-Apply-Combine Strategy for Data Analysis](http://www.jstatsoft.org/article/view/v040i01)”. Journal of Statistical Software 40(1).

## Session 4: Intro to visualization

We introduce visualizations in Python. We use [pandas](http://pandas.pydata.org/pandas-docs/stable/) and [seaborn](https://seaborn.pydata.org/index.html). Both these modules are built on the fundamental and flexible plotting module [matplotlib](https://matplotlib.org).

#### Required reading
- PDA: chapter 9
- Christ Moffitt, 2017. ["Effectively Using Matplotlib"](http://pbpython.com/effective-matplotlib.html)

#### Inspirational reading `*`

- Schwabish, Jonathan A. 2014. "[An Economist's Guide to Visualizing Data](https://www.aeaweb.org/articles.php?doi=10.1257/jep.28.1.209)". *Journal of Economic Perspectives*, 28(1): 209-34.
- Healy, Kieran and James Moody. 2014. "[Data Visualization in Sociology](http://kieranhealy.org/files/papers/data-visualization.pdf)". *Annual Review of Sociology*, 40:105–128.
- Cherdarchuk, Joey. 2013. "[Data Looks Better Naked](https://www.darkhorseanalytics.com/blog/data-looks-better-naked/)", blog post.
- Read sections 1-3 in: Wickham, Hadley. 2010. "[A Layered Grammar of Graphics](http://byrneslab.net/classes/biol607/readings/wickham_layered-grammar.pdf)". *Journal of Computational and Graphical Statistics*, Volume 19, Number 1, Pages 3–28.




## Session 5: Strings, queries and APIs

We start to leverage our python knowledge to make queries on the web. This allows us to pull data directly from Statistics Denmark's API.

#### Required reading
- PDA: section 2.3 p. 36-38 (Strings), section 3.3: p. 77-80 (Stop at Bytes and Unicode with Files), section 6.1: p. 187-189 (JSON Data), section 6.3
- Gazarov, Petr. 2016. "[What is an API? In English, please.](https://medium.freecodecamp.org/what-is-an-api-in-english-please-b880a3214a82)"



## Session 6: Scraping 1 - Introduction to web scraping

We learn to create and collect data from the web. This means interacting with webpages and extracting information from them.

#### Required readings

- [Beautiful Soup: Build a Web Scraper With Python](https://realpython.com/beautiful-soup-web-scraper-python/)

- [A Practical Introduction to Web Scraping in Python](https://realpython.com/python-web-scraping-practical-introduction/)

- Shiab, Nael. 2015. [On the Ethics of Web Scraping and Data Journalism](http://gijn.org/2015/08/12/on-the-ethics-of-web-scraping-and-data-journalism/). Global Investigative Journalism Network.

#### Inspirational reading `*`

Below are some interesting academic papers using data scraped from online sources that might provide inspiration for your exam project.

- Stephens-Davidowitz, Seth. 2014. "[The cost of racial animus on a black candidate: Evidence using Google search data](http://www.sciencedirect.com/science/article/pii/S0047272714000929)." *Journal of Public Economics*, 118: 26-40.

- Stephens-Davidowitz, Seth, Hal Varian, and Michael D. Smith. 2016. "[Super Returns to Super Bowl Ads?](http://people.ischool.berkeley.edu/~hal/Papers/2015/super.pdf)". R & R, *Journal of Political Economy*.

- Stephens-Davidowitz, Seth, and Hal Varian. 2015 "[A Hands-on Guide to Google Data](https://www.aeaweb.org/conference/2016/retrieve.php?pdfid=14330&tk=S7QBBHGE)." Google working paper.

- Barberá, Pablo. 2015. "[Birds of the same feather tweet together: Bayesian ideal point estimation using Twitter data](http://pan.oxfordjournals.org/content/23/1/76.short)." *Political Analysis*, 23.1: 76-91.

- Cavallo, A. (2018). ["Scraped data and sticky prices"](https://www.mitpressjournals.org/doi/abs/10.1162/REST_a_00652). *Review of Economics and Statistics*, 100(1).

- Bond, Robert M., et al. 2012. "[A 61-million-person experiment in social influence and political mobilization](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3834737/)." *Nature*, 489.7415: 295-298.


## Session 7: Scraping 2 - Parsing

Here we develop our skills in parsing. I.e., processing the text we get from websites. This is a fundamental data science skill that goes beyond web scraping alone.

#### Required readings

- [Beautiful Soup: Build a Web Scraper With Python](https://realpython.com/beautiful-soup-web-scraper-python/)

- [A Practical Introduction to Web Scraping in Python](https://realpython.com/python-web-scraping-practical-introduction/)

## Session 8: Scraping 3 - Advanced Scrapers

Today we will learn about automated browsing with the python tool Selenium. I.e., how to let the computer do the pointing, clicking and writing on webpages for us.
You will also learn about RegEx, which is a great tool to process raw text.

#### Required readings

- Introduction to Web Scraping using Selenium: [An introduction to Selenium in Python](https://medium.com/the-andela-way/introduction-to-web-scraping-using-selenium-7ec377a8cf72)

- Introduction to pattern matching using regex: [An introduction to regex in python](https://www.digitalocean.com/community/tutorials/an-introduction-to-regex-in-python). Blog.

#### Inspirational reading `*`
- [Most Commonly used techniques to Prevent Scraping:](https://medium.com/@betoayesa/using-the-content-as-an-anti-scrape-weapon-draft-9bb10cd30e5c)
- [Advanced Web Scraping Tactics](https://www.pluralsight.com/guides/advanced-web-scraping-tactics-python-playbook)
- [Scraping Sites That Use JavaScript and AJAX](https://oup-arc.com/protected/files/content/file/1505319833942-CH9---Scraping-Sites-that-Use-JavaScript-and-AJAX.pdf)
- [Facebook Scraper 2020: How to Scrape Facebook Group with Python](https://www.bestproxyreviews.com/facebook-scraper/)


## Session 9: Ethics and Big Data Intro

Ethics
- BBB: chapter 6
- Vox.com ["The Cambridge Analytica Facebook scandal."]( https://www.vox.com/2018/4/10/17207394/cambridge-analytica-facebook-zuckerberg-trump-privacy-scandal)
- European Commission. [”Ethics in Social Sciences and the Humanities”]( http://ec.europa.eu/research/participants/data/ref/h2020/other/hi/h2020_ethics-soc-science-humanities_en.pdf)
- Consumer Data Research Center, UK [”The General Data Protection Regulation & Social Science Research.”](https://www.cdrc.ac.uk/wp-content/uploads/2018/05/6-GDPR-and-social-science-research-full-document-1.pdf)


## Session 10: Modeling and machine learning

We introduce basic machine learning (ML) concepts. We start with the simple machine learning models for classification problems.

#### Required readings
- PML: chapters 1,2 and the following section from chapter 3: 
  - Modeling class probabilities via logistic regression


## Session 11: Regression and regularization

We explain the overfitting problem of modelling. We show one possible solution is regularization of standard linear models.

#### Required readings
- PML: chapter 3, the following sections:
  - Tackling overfitting via regularization
- PML: chapter 4, the following sections:
  - Partitioning a dataset into separate training and test sets
  - Bringing features onto the same scale
  - Selecting meaningful features (up until p. 134)
- PML: chapter 10, the following sections:
  - Introducing linear regression
  - Implementing an ordinary least squares linear regression model
  - Evaluating the performance of linear regression models
  - Using regularized methods for regression
  - Turning a linear regression model into a curve – polynomial regression


## Session 12: Model selection and cross-validation

We introduce cross validation to gauge overfitting and review the linear model.

#### Required readings
- PML: chapter 6, the following sections:
  - Streamlining workflows with pipelines
  - Using k-fold cross-validation to assess model performance
  - Debugging algorithms with learning and validation curves
  - Fine-tuning machine learning models via grid search



## Session 13: Performance Metrics, Non-linear ML and Perspectives 

We give an overview of non-linear machine learning models and outline how machine learning tools can be applied in social science.

#### Required readings
- PML: chapter 6, the following sections:
  - Looking at different performance evaluation metrics

- Mullainathan, Sendhil, and Jann Spiess. 2017. ["Machine Learning: An Applied Econometric Approach."](https://www.aeaweb.org/articles?id=10.1257/jep.31.2.87) *Journal of Economic Perspectives*, 31 (2): 87-106.

- Varian, Hal. 2012 [Big Data: New Tricks for Econometrics](http://people.ischool.berkeley.edu/~hal/Papers/2013/ml.pdf)

- Athey, Susan. 2018. [The Impact of Machine Learning on Economics](http://www.nber.org/chapters/c14009.pdf) *NBER*



## Session 14: Text data
We introduce the concept of **Text as Data**, and apply our newly acquired knowledge of supervised learning to a text classification problem.

#### Required readings

- Gentzkow, M., Kelly, B.T. and Taddy, M., 2019. ["Text as data"](https://doi.org/10.1257/jel.20181020) *Journal of Economic Literature* 57(3).
  - Following sections:
    - 1. Introduction
    - 2. Representing Text as Data

- Chapter 2. Dan Jurafsky and James H. Martin: [Speech and Language Processing (3rd ed. draft)](https://web.stanford.edu/~jurafsky/slp3/)
  - Following sections:
    - 2.4 Text Normalization

- PML: following sections from chapter 8:
  - Introduction
  - Preparing the IMDb movie review data for text processing
  - Introducing the bag-of-words model
  - Training a logistic regression model for document classification
  - Topic modeling with Latent Dirichlet Allocation


#### Inspirational readings `*`
Gentzkow, M., Kelly, B.T. and Taddy, M., 2019. ["Text as data"](https://doi.org/10.1257/jel.20181020) *Journal of Economic Literature* 57(3).
  - Following sections:
    - 4. Applications

Gorrell, Genevieve et al. “Twits, Twats and Twaddle: Trends in Online Abuse towards UK Politicians.” ICWSM (2018). https://gate-socmedia.group.shef.ac.uk/wp-content/uploads/2019/07/Gorrell-Greenwood.pdf

Pang, Bo et al. “Thumbs up? Sentiment Classification using Machine Learning Techniques.” EMNLP (2002). https://www.aclweb.org/anthology/W02-1011.pdf




`*`: Note: There might be a paywall on some of the inspirational readings. Don't worry if you cannot get access - it *is* in fact only inspirational.
