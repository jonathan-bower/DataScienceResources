##Data Science Resources

Hi - welcome to the Data Science Resources Repo.  I originally built this repo so that I could have a location to host resources that are helpful to me.  Through building the repo I realized that other people might be interested in the content so I have tried to curate content on data science topics, high quality resources to learn from, and relevant blog posts.  

The intended goal was to cover more than just the technical component  of data science.  Data Science as a discipline is still really fresh and many business are learning to properly integrate teams and to understand the value proposition that data science can provide and how to structure those teams effectively.

As a result I tried to find topics that cover building data science teams, business practices, use-cases, product metrics and data science career paths.  

This is a constant work in progress and I hope to refactor and update in some kind of meaningful time frame.

If you find this resource helpful - please send it around to other people or you can [upvote it on datatau](http://www.datatau.com/item?id=4593), share it on linkedIn, twitter, Facebook, add it to Quora or just send me a note.   Good luck, I hope this helps you find what you are looking for now, or in the future.

Remember - If you’re not prepared to be wrong, you’ll never come up with anything original.

#Table Of Contents
1. [Data Science Getting Started](#data-science-getting-started)
  * [Start](#start)
  * [Data Science Courses](#data-science-courses)

1. [Data Pipeline & Tools](#data-pipeline--tools)
  * [Python](#python)
  * [Data Structures & CS topics](#data-structures--cs-topics)
  * [Statistics](#statistics)
  * [Stats/Engineering Libraries](#statsengineering-libraries)
  * [Databases/Frameworks](#databasesframeworks)
  * [Data Acquisition](#data-acquisition)
  * [Processing & EDA](#processing--exploratory-data-analysis)
  * [Machine Learning](#machine-learning)
    * [Machine Learning Theory](#machine-learning-theory)
    * [Deep Learning](#deep-learning)
    * [Model Selection](#model-selection)
    * [Model Evaluation](#model-evaluation)
    * [Feature Engineering](#feature-engineering)
  * [Additional Tools or Processes](#additional-tools-or-processes)
  * [Data Visualization](#data-visualization)
  * [ipython Notebook Tutorials](#ipython-notebook-tutorials)
  * [Data Sources](#data-sources)
  * [New Data Tools](#new-data-tools)

1. [Product](#product)
  * [Product Metrics](#product-metrics)
  * [Team Communication & Business Tools](#team-communication--business-tools)  
  * [Best Practices](#best-practices)

1. [Career Resources](#career-resources)
  * [Data Science Career Path](#data-science-career-path)
  * [Types of Data Scientists](#types-of-data-scientists)
  * [Data Science Applications/Use Cases](#data-science-applicationsuse-cases)
  * [Data Science Websites/Books](#data-science-websitesbooks)
  * [Data Science Meetups in the Bay Area](#data-science-meetups-in-the-bay-area)
  * [Data Science Blogs](#data-science-blogs)
  * [Data Science Conferences](#data-science-conferences)
  * [Data Science Presentations](#data-science-presentations)
  * [Relevant Business Processes](#relevent-business-processes)

1. [Open Source Data Science Resources](#open-source-data-science-resources)
  * [Additional Open Source Content](#other-open-source-data-science-content)
  * [Auxiliary Content & Apps](#auxiliary-content--apps)

1. [About Me](#about-me)

## Data Science Getting Started
Data Science is a multidisciplinary field covering at the very minimum - statistics, programming, machine learning [Drew Conway's venn diagram](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram) or [Cheat Sheet of a Modern Data Scientist](http://www.marketingdistillery.com/2014/08/30/data-science-skill-set-explained/).  These topics are covered throughout this repo.  I personally find the best way to learn a topic is to get my hands dirty quickly - with that in mind I would get to work in python and then implement different tools or theory into my toolkit as they are understood.  If you haven't used python before I would strongly urge you to use the codecademy course to familiarize yourself with the content and how to program.  Good luck and have fun.

A note about order - I framed the contents in the Pipeline & Tools section order of the data pipeline starting with acquisition, exploratory data analysis, cleaning data, model section & evaluation and then visualization.

### Start
* [Data Science Pipeline](http://machinelearningmastery.com/wp-content/uploads/2014/05/Overview-of-the-Applied-Machine-Learning-Process.png) - Detailed overview of data pipeline from MachineLearningMastery.com
* [Intro to ipython](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks/_edit#entire-books-or-other-large-collections-of-notebooks-on-a-topic) - A curation of Ipython Notebooks great for introductory level to python, programming, comp sci, data science and other topics.
* [How do I Become a Data Scientist?](http://www.quora.com/How-do-I-become-a-data-scientist) - Some more great starting points from William Chen.

### Data Science Courses:
* [Coursera](https://www.coursera.org/specialization/jhudatascience/1) - Data Science Specialization at Coursera - many other courses available as well.
* [Udacity](https://www.udacity.com/courses#!/data-science) - Online MOOCs that are the Data Science related courses. by I
* [Data Science Bootcamps](http://yet-another-data-blog.blogspot.com/2014/04/data-science-bootcamp-landscape-full.html) - A collection of all bootcamps currently on the market as of April 5, 2014 by Ikechukwu Okonkwo.
* [Coursera Machine Learning Course](https://www.coursera.org/course/ml) - Andrew Ng's pinnacle Machine Learning course.
* [Edx](https://www.edx.org/course/mitx/mitx-6-00-2x-introduction-computational-2836#.VEANx9TF-tw) - EDX courses related to data science.

## Data Pipeline & Tools

###Python
Python is my workhorse language specifically as it has many data science and statistic library, the ability to work in production environments, and work on other problems outside of data science.  There are many other languages that could be useful but are not covered here: Julia, R, Cython, Pig, Scala, Java, etc.

* [Python @ Codecademy](http://www.codecademy.com/en/tracks/python) - If you have never used Python, right this way..
* [The Python Wiki](https://wiki.python.org/moin/FrontPage) - Good resource with lots of info about Python.
* [Python for Data Science Tutorial - Kaggle](https://www.kaggle.com/wiki/GettingStartedWithPythonForDataScience) - Stepping into Data Science with Kaggle and installing some libraries.
* [Introduction to Data Processing with Python](http://opentechschool.github.io/python-data-intro/) - Just as the name says - some introductory level information and exercises.
* [Git tutorial](https://try.github.io/levels/1/challenges/1) - Git for Version Control.  Simple tutorial for Git from Github.
* [Anyone Can Code](http://dhruvbird.com/61.html) - Languages, tutorials, cheat sheets, algorithms and data structures

#### Data Structures & CS Topics
* [Algorithms & Data Structures](http://www.bogotobogo.com/Algorithms/algorithms.php) - Binary trees, hash tables, linked lists, big(O) notation and more.
* [Algorithm & Data Structures](http://interactivepython.org/courselib/static/pythonds/index.html) - Well organized detailed and digestible site full of content covering data structures, algorithms, recursion and assignments!
* [Big O Notation](http://interactivepython.org/courselib/static/pythonds/AlgorithmAnalysis/BigONotation.html) - Great details and visual of big-O notation.
* [Visualizations of Data Structures](http://www.cs.usfca.edu/~galles/visualization/Algorithms.html) - Collection of different algorithms (graph problems) and data structures (queues, heaps, hashes) that walks through the visualization to get a better intuitive understanding. 
* [Data Structures CheatSheet & Big Oh Notation](http://bigocheatsheet.com/)
* [Data Structures CheatSheet -smaller more readable](https://www.clear.rice.edu/comp160/data_cheat.html)
* [Coursera: Stanford Algorithms Design & Analysis ](https://class.coursera.org/algo-006) - Course on algorithm design & analysis

####Statistics
Some primers on understanding statistics and other resources to get a deeper understanding.
* [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) - John Rauser's really great video on statistics - funny and engaging with a good message.
* [Probability Programming and Bayesian Methods for Hackers](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Prologue/Prologue.ipynb) - full book all online through ipython notebooks.
* [Probabilistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Github Repo for the book above.
* [Statistics Cheat Sheet in Ipython Notebook](http://nbviewer.ipython.org/url/trust.sce.ntu.edu.sg/~gguo1/blogs/Statistics/Statistics.ipynb)
* [The only probability Cheatsheet you'll ever need](https://bayesrule.files.wordpress.com/2014/07/probability_cheatsheet_140718.pdf) - Self explanatory - (thanks William Chen @ http://datastories.quora.com/) for pointing me this great cheat sheet out - wish I had that back at college.
* [Khan Academy: Statistics](https://www.khanacademy.org/#statistics) - Tons of videos to help learn statistics concepts.
* [Statistical Distributions in iPython Notebook](http://nbviewer.ipython.org/urls/gist.github.com/mattions/6113437/raw/c5468ea930d6960225d83e112d7f3d00d9c13398/Exploring+different+distribution.ipynb) - Discrete, Bernoulli, Poisson, Binomial, Alpha, Beta etc.  The descriptions are mathematical - will find another resource to explain.

####Stats/Engineering Libraries
A collection of workhorse libraries that are elemental for any python data scientist.
* [Pandas](http://pandas.pydata.org/) Wes McKinney's pandas library for EDA on small to medium sized data sets when you don't want to put the infrastructure for SQL or when it isn't necessary.  It has many other great applications other than just better than SQL on small to medium data sets.
  * [Numpy/Pandas/Scipy Cheatsheet](https://s3.amazonaws.com/quandl-static-content/Documents/Quandl+-+Pandas,+SciPy,+NumPy+Cheat+Sheet.pdf) - self explanatory
* [SciPy](http://www.scipy.org/) - Open-source software for mathematics, science and engineering.
* [NumPy](http://www.numpy.org/) - Fundamental package for scientific computing with Python.
* [StatsModels](http://statsmodels.sourceforge.net/) - Module that allows users to explore data, estimate statistical models and perform statistical tests.
* [PyMC](https://pypi.python.org/pypi/pymc) - Bayesian estimation useful for Markov chain Monte Carlo analysis (among other things).


####Data Acquisition
Libraries that are very helpful for abstracting away some of the complications of scraping or working with HTTP.
* [BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) - A python library to make web-scraping HTML easier.
  * [Beautiful Soup Cheat Sheet](http://youkilljohnny.blogspot.com/2014/03/beautifulsoup-cheat-sheet-parse-html-by.html)
* [Requests](http://docs.python-requests.org/en/latest/) - HTTP for Humans - python library that makes working with http and api's more effortless

####Processing & Exploratory Data Analysis
A collection of documents explaining some of the ways to do processing & EDA.
* [Unix for Processing](http://www.theunixschool.com/p/awk-sed.html) - sed & awk for data processing.
* [Pandas](http://pandas.pydata.org/) - Already mentioned is great for data processing - cleaning, filtering and getting rid of nan's, normalizing, scaling, replacing values, etc.
* [SciKit Learn for Preprocessing](http://scikit-learn.org/stable/modules/preprocessing.html#preprocessing) - Doc on sklearn's preprocessing methods.
* [Regular Expressions](http://www.zytrax.com/tech/web/regex.htm) - Regex explained.

###Databases/Frameworks
A collection of databases & frameworks that are helpful for data management and are the industry standard.
* [SQL](http://www.postgresql.org/) - SQL Database - I linked to Postgres since that is the version I use.
* [Psycopg](http://initd.org/psycopg/) - Python <> Postgres.  Able to adapt PostgreSQL for the python environment.
  * [SQL Cheet Sheet](http://www.sql-tutorial.net/sql-cheat-sheet.pdf)
  * [SQLZoo](http://sqlzoo.net/wiki/Main_Page) - Develop your skills
  * [SQLSchool](http://sqlschool.modeanalytics.com/) - Develop your skills
[MongoDB](http://www.mongodb.org/) - NoSQL database
* [PyMongo](http://api.mongodb.org/python/current/tutorial.html) - Python Mongo Driver.
  * [MongoDB - cheatsheet](https://blog.codecentric.de/files/2012/12/MongoDB-CheatSheet-v1_0.pdf) - Cheat sheet for MongoDB
* [Apache Hive](https://hive.apache.org/) - Uses Hive Query Language (HQL) - similar to SQL for data at scale.
  * [Hive Cheatsheet](http://hortonworks.com/wp-content/uploads/downloads/2013/08/Hortonworks.CheatSheet.SQLtoHive.pdf) - Self Explanatory.
* [ElasticSearch](http://www.elasticsearch.org/) - For scalable, fast text search/analysis.
* [Neo4j](http://www.neo4j.org/) - Leading graph database.
* [Redis](http://redis.io/) - Key-value open source data structure server.
* [Redshift](http://aws.amazon.com/redshift/) - AWS petabyte-scale data warehouse solution.
* [Hadoop - the definitive guide](http://ce.sysu.edu.cn/hope/UploadFiles/Education/2011/10/201110221516245419.pdf) - Hadoop ecosystem.
* [Spark](https://spark.apache.org/) - Lightening fast cluster computing.
* [MRjob](https://github.com/Yelp/mrjob) - Run MapReduce jobs on Hadoop or AWS.

###Machine Learning
There is a lot of information available online about the theory, mathematical intuition, tuning for this discipline.  Here are some tools that are currently available.
* [A visual introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) - Awesome d3 visualization to help understand machine learning.
* [SciKit-Learn](http://scikit-learn.org/stable/) - Simple and efficient machine learning tools for data mining and data analysis
* [NLTK](http://www.nltk.org/) - Natural Language Toolkit to work with human languages data.
* [Tour of Machine Learning Algorithms](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/) - Blog post about some of the high level ML methods
* [VIDEO - How to get started w/mL](https://www.youtube.com/watch?v=uBorfxosVYs) - Melanie Warrick @ PyCon 2014.
* [Some ML methods classified](http://nyghtowlblog.files.wordpress.com/2014/04/ml_algorithms.png?w=535&h=311) - Classification for some sample ML algorithms by Melanie Warrick.
* [SciKit-image](http://scikit-image.org/) - Algorithms for image processing.
* [Machine Learning CheatSheet](https://github.com/soulmachine/machine-learning-cheat-sheet) - I would actually say this is more than just a cheat sheet given that there are > 100 pages of notes.
* [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning) - List of machine learning libraries in all languages and also Kaggle competition source code by Joseph Misiti.

###Machine Learning Theory
* [MathematicalMonk ML videos](https://www.youtube.com/playlist?list=PLD0F06AA0D2E8FFBA) - Amazingly concise and digestible videos detailing how different machine learning algorithms function (e.g. logistical, sums, knn, Bayes, etc.)  
* [Logistic Regression Explained](http://www.appstate.edu/~whiteheadjc/service/logit/intro.htm#hypothesis) - Detailed explanation of how logistic regression works.
* [Video explaining how Random Forests Algorithm works](https://www.youtube.com/watch?v=o7iDkcpOr_g) - Random Forests Algorithm explained.
* [Random Forest Explained](http://citizennet.com/blog/2012/11/10/random-forests-ensembles-and-performance-metrics/) - Write up about Random Forest in layman's terms.
* [Machine Learning 101](http://www.erogol.com/large-set-machine-learning-resources-beginners-mavens/) - Large set of ML resources for beginners.


###Deep Learning
Getting a lot of media traction is deep learning - get your feet wet with some of these resources:
* [HackerNews for Deep Learning](http://news.startup.ml/) - As the name says - a hacker news for Deep Learning
* [Deeplearning4j](http://deeplearning4j.org/) - Deep Learning in Java.
* [Neural Networks Explained - Video](https://www.youtube.com/watch?v=bxe2T-V8XRs) - High level and intuitive explanation how Neural Networks (deep learning) works.
* [Deep Learning Tutorial](http://deeplearning.net/tutorial/deeplearning.pdf)
* [What is Deep Learning](http://blog.shakirm.com/2015/06/a-statistical-view-of-deep-learning-vi-what-is-deep/?utm_content=bufferae750&utm_medium=social&utm_source=linkedin.com&utm_campaign=buffer)
* [Free Online Deep Learning Book](http://neuralnetworksanddeeplearning.com/) - in-depth book about NN & deep learning
* [The Brain vs Deep Learning - Blog Post](https://timdettmers.wordpress.com/2015/07/27/brain-vs-deep-learning-singularity/)

######Time-Series
* [ANN & Computational Intelligence Forecasting Competition](http://www.neural-forecasting-competition.com/index.htm)
* [Neural Networks for Time Series Slidedeck](http://www.cs.cmu.edu/afs/cs/academic/class/15782-f06/slides/timeseries.pdf) 

####Model Selection
Resources about how to decide on your model.
* [SciKit Learn Flow Chart for Model Selection](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html) - A helpful for a starting point selecting SKlearn algorithms.

####Model Evaluation
Resources to help with understanding model evaluation.
* [Evaluating ML Algorithms](http://machinelearningmastery.com/how-to-evaluate-machine-learning-algorithms/) - Blog Post from MachineLearningMastery about how to evaluate your performance.
* [Cross-Validation](http://robjhyndman.com/hyndsight/crossvalidation/) - Critical concept to evaluate the performance of your models.
  * [K-fold & Grid Search in Scikitlearn](http://randomforests.wordpress.com/2014/02/02/basics-of-k-fold-cross-validation-and-gridsearchcv-in-scikit-learn/) - Demo on how to implement kfold cross validation and grid-search using scikit-learn.
  * [Scikit-learn Cross Validation doc](http://scikit-learn.org/stable/modules/cross_validation.html) - Self explanatory title.
  * [Cross Validation - how to select your final Kaggle Model](http://www.chioka.in/how-to-select-your-final-models-in-a-kaggle-competitio/) - Importance of cross-validation described specifically in how it effects Kaggle competition scores.

####Feature Engineering
A critical element of Data Science to improve your performance but minimally talked about.
* [Ipython Notebook for Feature engineering](http://nbviewer.ipython.org/urls/raw2.github.com/yhat/DataGotham2013/master/notebooks/7%20-%20Feature%20Engineering.ipynb?create=1) - Some discussion about Feature Engineering.
* [CS Princeton Course](http://www.cs.princeton.edu/courses/archive/spring10/cos424/slides/18-feat.pdf) - Course content on Feature Engineering.
* [Blog Post about Feature Engineering / Data Exploration](http://deblivingdata.net/machine-learning-tricks/) - Blog post about topic.

### Additional Tools or Processes
Resources on other topics that are very helpful for data scientists and product.
* [A/B Testing](http://conversionxl.com/how-to-build-a-strong-ab-testing-plan-that-gets-results/#.) - Blog about A/B testing.
* [A/B Testing](http://unbounce.com/a-b-testing/5-ways-youre-screwing-up-your-a-b-testing/) - And how you are screwing it up.
* [Bloom Filters](http://nbviewer.ipython.org/github/ctb/2013-pycon-awesome-big-data-algorithms/blob/master/04-bloom-filters.ipynb)  - Python notebook about bloom filters.
* [Bloom filters](http://billmill.org/bloomfilter-tutorial/)  - Bloom Filters.
* [Reservoir Sampling](http://blog.cloudera.com/blog/2013/04/hadoop-stratified-randosampling-algorithm/) - A primer on Reservoir Sampling.
* [Reservoir Sampling Again](http://www.geeksforgeeks.org/reservoir-sampling/)
* [Monte Carlo for the Monty Hall Problem](http://slantedwindows.com/monty-hall-meet-mr-monte-carlo/) - Hyon Chu puts on a good explanation to MC for the Monty Hall Problem.
* [Markov Chain Monte Carlo](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter3_MCMC/IntroMCMC.ipynb) - Opening the black box of MCMC.
* [Multithreading and Queues](http://pymotw.com/2/Queue/) - How to build multithreading and queues.
* [Basics of Multithreading and queses](http://www.troyfawkes.com/learn-python-multithreading-queues-basics/)  - More about multithreading.
* [Multithreading & Queuing](http://www.shanelynn.ie/using-python-threading-for-multiple-results-queue/) - Another great resource for multithreading & queuing.
* [Building a Recommender System](http://www.quora.com/How-can-I-start-building-a-recommendation-engine) - Quora answer to this question.  Helpful starting point.

### Data Visualization
Collection of the best libraries that I know for easy and powerful data visualizations.
* [ggplot](http://ggplot.yhathq.com/) - ggplot for python ported by the team at yhat.
* [matplotlib](http://matplotlib.org/) - Awesome plotting library for python.
* [d3](http://d3js.org/) - Mike Bostock's viz library - the de facto gold standard for polished visualization - in js, steep learning curve but beautiful outcomes.
* [bokeh](http://bokeh.pydata.org/) - Interactive visualization library.
* [d3py](https://github.com/mikedewar/d3py) - Another library for data viz.
* [vincent](http://vincent.readthedocs.org/en/latest/)  - Help with python for d3.
* [seaborn](http://web.stanford.edu/~mwaskom/software/seaborn/) - Clean statistical data visualization library.

Other available Visualization Resources.
* [Scott Murray's D3 Tutorials](alignedleft.com/tutorials/d3/) Tutorials from *Interactive Data Visualization for the Web*
* [tributary.io](http://tributary.io) - live code visualization platform designed specifically for D3.js
* [plot.ly](http://plot.ly) - A web visualization and data processing platform
* [blockspring](http://blockspring.com) - Share code and visualizations through a single platform
* [dot.append](http://enjalot.github.io/dot-append/) - Ian Johnson (enjalot) goes through several live-coding examples using D3
* [Text Visualization Plots](#http://textvis.lnu.se/) - Interactive site with different types of text visualization for different problems.  

### Design Theory
The importance of design theory in data visualization, story telling and presentations could not be understated.  It can take great content and make it confusing or virtually unusable, or it can make content sing and connect with the audience.  Through better understanding of design theory, UI principles, a data scientist (or anyone) can convey more understandable information to the intended audience and give a strong story to their content.
* [Slidedeck on Data Storytelling & Visualization ](http://higherlogicdownload.s3.amazonaws.com/AMSTAT/62ac7e8c-c7ec-4e98-b58b-dd540bf9e0d9/UploadedImages/dvc2014/Veena%20MendirattaASA%20Storytelling%20with%20Data%20Visualization.pdf) - Overview of different story structures and how to tell a story with data.
* [Accelerating Understanding Through Data Visualization](http://www.accenture.com/SiteCollectionDocuments/PDF/Accenture-Accellerating-Understanding-Through-Data-Visualization.pdf) - Accenture White paper on Data Visualization

### Ipython Notebook Tutorials
Collection of ipython notebooks that are helpful as examples to either using tools or to explain certain topics.
* [Pandas Tutorial](http://nbviewer.ipython.org/github/twiecki/financial-analysis-python-tutorial/blob/master/1.%20Pandas%20Basics.ipynb) - Basic intro to Pandas in notebook form.
* [Pandas / Stats Tutorial](https://github.com/fonnesbeck/pytenn2014_tutorial) - Intermediate tutorial by Christopher Fonnesbeck Feb 2014.
* [Scipy Tutorial](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-3-Scipy.ipynb) - Basic Scipy Tutorial.
* [Numpy Tutorial](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-2-Numpy.ipynb) - Basic Numpy Tutorial.
* [Multiple Regressions using Statsmodels](http://nbviewer.ipython.org/urls/s3.amazonaws.com/datarobotblog/notebooks/multiple_regression_in_python.ipynb) - Using statsmodels for regression.
* [Intro to PyMC](http://nbviewer.ipython.org/github/fonnesbeck/Bios366/blob/master/notebooks/Section4_3-Introduction-to-PyMC.ipynb) - Intro to PyMC.
* [More on PyMC](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter2_MorePyMC/MorePyMC.ipynb) - More PyMC.
* [Kaggle Titanic Comp Tutorial](http://nbviewer.ipython.org/github/agconti/kaggle-titanic/blob/master/Titanic.ipynb) - Kaggle Titanic Tutorial using RandomForests.
* [Psycopg2 tutorial in Python](https://wiki.postgresql.org/wiki/Psycopg2_Tutorial) - How to use Psycopg2.
* [SQL in iPython](http://nbviewer.ipython.org/gist/catherinedevlin/6588378) - SQL in Python.
* [Mongo in Python](http://api.mongodb.org/python/current/tutorial.html) - Mongo in Python.
* [Beautiful Soup Tutorial](http://nbviewer.ipython.org/github/kcranston/2013-08-ku/blob/master/beautifulsoup/notebooks/00-BeautifulSoup.ipynb) - Beautiful Soup!
* [Sci-Kit Learn Basics](http://nbviewer.ipython.org/urls/raw2.github.com/yhat/DataGotham2013/master/notebooks/4%20-%20scikit-learn%20basics.ipynb?create=1)  - Machine Learning Basics with scikit-learn.
* [MatPlotLib](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb) - Some of the possibilities of data-viz with MatPlotLib.
* [Choosing the right priors - Bayesian](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter6_Priorities/Priors.ipynb) - Bayesian statistics and prior selection.
* [Some Basic Data Analysis in Python](http://nbviewer.ipython.org/github/jvns/talks/blob/master/pyconca2013/pistes-cyclables.ipynb) - Basic data analysis with python.
* [Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182) - Ipython Notebook for Scientists!
* [Regular Expressions](http://nbviewer.ipython.org/gist/rjweiss/7577022) - Regex to match patterns in strings - very powerful.
* [MapReduce](http://nbviewer.ipython.org/github/cs109/content/blob/master/labs/lab8/lab8_mapreduce.ipynb) - Classes, inheritance and map-reduce exercises.
* [Recursion](http://nbviewer.ipython.org/github/gumption/Motivating_and_Visualizing_Recursion_in_Python/blob/master/Motivating_and_Visualizing_Recursion_in_Python.ipynb)  Notebook visualization recursion "The single most powerful idea in algorithms".
* [Recursion](http://anandology.com/python-practice-book/functional-programming.html) More about Recursion and Functional Programming
* [Hash Table, Bloom Filter, HyperLogLog](http://nbviewer.ipython.org/github/mlaprise/pydata2013-pds-talk/blob/master/pydata2013.ipynb) - Explaining and demoing some of these concepts.
* [Hash tables, Binary Trees](http://nbviewer.ipython.org/github/iit-cs429/main/blob/master/lectures/lec04/Dictionaries.ipy)
* [Time Series- Arima & Arma](http://nbviewer.ipython.org/github/qwu-hab/geogg121/blob/master/tsa_temp.ipynb)

### Data Sources
Collection of sites to access data if you want to build out a project or just use some of the tools for EDA.
* [Data.Gov](https://www.data.gov/) - The US government portal to open data.
* [California Water Resources](http://www.water.ca.gov/data_home.cfm) - California's water resource data.
* [Data for Cool DS projects](http://101.datascience.community/2014/10/17/data-sources-for-cool-data-science-projects-part-1-guest-post/)
* [Academic Torrents](http://academictorrents.com/) - Sharing Data is hard, torrents make it easier for academics.
* [Data Basin](http://databasin.org/) - Science based mapping and analytics platform.
* [Open Energy Data Initiative](http://en.openei.org/wiki/Main_Page) - Over 800 data sets covering energy issues.
* [UCI Machine Learning Datasets](https://archive.ics.uci.edu/ml/datasets.html) - Data for machine learning - lots of labeled data and description of the problem types.
* [London Data Store](http://data.london.gov.uk/) - Lots of datasets on London, UK

### New Data Tools
Aim to keep track of developing trends and new tech that is helpful for the practicing Data Scientist.  New might be a misnomer.
* [BigML](https://bigml.com/) - machine learning for the everyday user, also useful for EDA.
* [GraphLab](http://graphlab.com/) - graph-based, high performance, distributed computation framework.  They just implemented deep learning onto their platform.
* [ModeAnalytics](https://modeanalytics.com/) - platform to share analysis/data science.
* [Apache Mahout](https://mahout.apache.org/) - Scalable machine learning library.  Not in python.
* [Apache Hadoop](http://hadoop.apache.org/) - Open-source software for reliable, scalable, distributed computing.  Not really new (10 years old at this point)

### Other Useful Scripts
* [Spinning up EC2 instances](https://github.com/drewconway/data_science_box) - Drew Conway's scripts to easily spin up AWS EC2 instances. 

## Product

###Product Metrics
Understanding product, user behavior, and product metrics is helpful for data scientists in industry. Being able to help your product manager and team execute on strategies by understanding the problem, metrics and what they understand facilitates a more fruitful relationship.
* [Actionable Metrics](http://practicetrumpstheory.com/3-rules-to-actionable-metrics/) - Funnel reports, cohort analysis, actionable metrics.
* [Analytics for Product Managers](http://www.mindtheproduct.com/2013/02/everything-a-product-manager-needs-to-know-about-analytics/) - Everything a PM needs to know about analytics - or the minimum amount your PM should know about analytics as a Data Scientist.
* [Startups, you are doing data science wrong!](https://gigaom.com/2013/09/28/notice-to-startups-you-are-doing-data-science-wrong/) - High level explanation about how to use data science in a start-up company.
* [Product Psychology](http://www.productpsychology.com/category/user-behavior/)  - Understanding user behavior.
* [Understanding Cohort Analysis](http://amarnath14.tumblr.com/post/69790103060/understanding-cohort-analysis) - Blog about cohort analysis, conversions, customer lifetime value, etc.  Great starting point understanding product metrics.
* [Tech Product Management](http://techproductmanagement.com/) - More product focused than Data Science but can provide a good sense to view product management.  
* [Mind The Product](http://www.mindtheproduct.com/) - Another solid PM blog.

### Team Communication & Business Tools
There are some very innovative new companies that are producing very effective tools to minimize and abstract away inefficient processes at companies.  While it isn't strictly data science related, these products could be very help to integrate with your teams to improve overall productivity.
* [Aha!](http://www.aha.io/) - Clean product roadmapping software for PMs.
* [Slack](https://slack.com) - Amazing team communication tool - abstracting away unnecessary e-mails.
* [Harvest](https://www.getharvest.com) - Effortless time tracking for business.
* [Trello](https://trello.com) - Helping organize everything - great for project management.
* [Zapier](https://zapier.com/zapbook/harvest/slack/) - Bringing together Harvest + Slack + Trello and a lot more...
* [Thoughtbot Playbook](http://playbook.thoughtbot.com/) -  A detailed account of how thought book runs is software consulting company talking about guiding principles, design sprints, code reviews to sales and operations.  A content packed post.
* [IFTTT](http://www.ifttt.com) - 'Putting the internet to work for you'.  Great for small companies to automate social media, marketing or to have your own personal recipes set up.
* [Github](https://github.com) - Clearly a great product - 'Build software better, together'.
* Web Analytics & Reporting Software:
  * [Google Analytics](http://www.google.com/analytics/) - In depth real-time analytics.
  * [Mixpanel](https://mixpanel.com/) - provides real-time analytics and solid cohort analysis.
  * [Clicky](http://clicky.com/) - Pride themselves on ease of use.
 * [Evernote](https://evernote.com/) - Great for keeping notes

### Best Practices
Source control and keeping accurate documentation so that you and your colleagues can follow and reproduce your work is very important.  I will add some best coding practices & data science practices.  
* [Python Code Style](http://docs.python-guide.org/en/latest/writing/style/) - Allows for better understanding for everyone involved on the project.  
* [Slide Deck for BMPs](https://python.g-node.org/python-summerschool-2011/_media/materials/best_practices/haenel-best-practices-2011-09-standrews.pdf)  - Slide deck about best practices for coding or the [repo](#https://github.com/esc/best-practices-talk).       
* [Engineering Practices in Data Science](http://blog.kaggle.com/2012/10/04/engineering-practices-in-data-science/) A blog post about the lack of source control in Data Science.  It's a challenging topic - I believe mode analytics is trying to solve it.  

## Career Resources

### Data Science Career Path
* [Data Science @ Google](http://www.quora.com/What-is-the-Quant-Data-Science-Career-ladder-at-Google) - Quora answer about Data Science career trajectory @ google.

### Types of Data Scientists
Not all Data Scientists are the same and it's critical for organizations to understand what it is they need, and how best to fill those roles and/or complement the skills of their team.  Finding the organizational structure that enables the data scientists/data engineers within the organization and generates better results is also crucial.  It should be given thorough consideration.
* [Kind's of Data Scientist](http://radar.oreilly.com/2013/06/theres-more-than-one-kind-of-data-scientist.html) - O'Reilly's classification of 4 different data scientists.
* [Data Science For Startups](http://tomtunguz.com/data-science-types/) - Which of the Five Types of DS does your startup need?  Different classification from O'Reilly.
* [Building Data Science Teams](http://radar.oreilly.com/2011/09/building-data-science-teams.html) - posted from 2011 about how to build data science teams.
* [Data Science Team Building - The Power of Collaborative Analytics](http://www.experfy.com/blog/data-science-team-building-power-collaborative-analytics/) - Post post about different team org structures,  difference between DS & BI.

### Data Science Applications/Use Cases
Data Science has so many different applications and use cases within industry - many are continuously discovered.  These resources provide some potential ideas.
* [Kaggle Data Science Use Cases](https://www.kaggle.com/wiki/DataScienceUseCases) - Helpful to generate ideas for new uses in different industries
* [Data Science for each Industry](http://www.mastersindatascience.org/industry/) - Description of uses for different industries.
* [Big Data Analytics News - use Cases](http://bigdataanalyticsnews.com/big-data-use-cases/) - For Big Data but that's almost synonymous with Data Science.

### Data Science Websites/Books
More resources for community based information or hard copy books.
* [Data Science Handbook](https://medium.com/@pericarus/introducing-the-data-science-handbook-b2bfa216bf4b) - Not yet released but should be interesting providing stories from academia and industry about data science - go read the post for a better description!
* [CrossValidated](http://stats.stackexchange.com/) - A question and answer site for people interested in statistics, machine learning, data analysis, data mining, and data visualization.
* [StackOverflow](stackoverflow.com) - Language-independent collaboratively edited question and answer site for programmers.
* [Kaggle](http://www.kaggle.com) - Model building competition and great resources for training and data.
* [O'Reilly Media](http://shop.oreilly.com/category/get/data-science-kit.do) - A lot of content rich books available and tutorials on using the tools.
* [Quora](http://www.quora.com/) - Question and answer site - lots of data science content and career content.
* [Data Science @ StackExchange](http://datascience.stackexchange.com/) - Still in beta.

### Data Science Meetups in the Bay Area
A great way to meet other Data Scientists and keep up to date with best practices.
* [SF Data Science](http://www.meetup.com/SF-Data-Science/)
* [Data Science for Sustainability](http://www.meetup.com/Data-Science-for-Sustainability/)
* [Python Meetup Group](http://www.meetup.com/sfpython/)
* [USF Seminar Series in Analytics](http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/)
* [DataKindSF](http://www.meetup.com/DataKind-SF-Bay-Area/)
* [SF Bayarea Machine Learning](http://www.meetup.com/SF-Bayarea-Machine-Learning/)
* [AirBnB Tech Talks](http://nerds.airbnb.com/tech-talks/)

### Data Science Blogs
* [Data Stories @ Quroa](http://datastories.quora.com/) - William Chen's (DS@Quora) blog about data science.
* [FastML](http://fastml.com/)
* [FiveThirtyEight Blog](http://fivethirtyeight.com/) - Nate Silver's blog.
* [Data Science Hanbook](http://www.datasciencehandbook.me/) - Data Science Handbook Project (not quite a blog but it fits here).
* [Simply Statistics Blog](http://simplystatistics.org/)
* [All The Things Tech](http://nyghtowl.io/)
* [Musings in Data Science](http://deblivingdata.net/)
* [Zipfian Data Science Blog](http://www.zipfianacademy.com/blog/) - Zipfian Academy DS Blog.
* [Machine Learning Mastery](http://machinelearningmastery.com/)
* [DataTau](http://datatau.com) - Hackernews for Data Science.
* [HackerNews](https://news.ycombinator.com/)
* [Quora](http://quora.com) - Q&A site with lots of information about Data Science.
* [ThreeStoryBlog](http://blog.threestory.com/) - Design blog

### Data Science Conferences
* [Strata](http://strataconf.com/) - Conference and a lot of videos from previous conferences - great resource.
* [GraphLab](http://graphlab.com/events/conference14.html) - Another great conference.
* [PyData](http://pydata.org)

### Data Science Presentations
* [Strata Collection of Presentations](http://strataconf.com/strata2014/public/schedule/proceedings) - Most of their conference presentations available online.
* [KDD Keynotes](http://videolectures.net/kdd2014_newyork/) - collection of keynote presentations from the NYC conference
* [All of PyData Conference Talks](https://github.com/DataTau/datascience-anthology-pydata)  

### Relevant Business Processes
* [Lean Startup](http://theleanstartup.com/principles) - A method to develop product and businesses.
* [Agile Development](http://en.wikipedia.org/wiki/Agile_software_development) - group of software development methods to optimize for self-organizational and cross-functional teams.
* [Scrum](http://en.wikipedia.org/wiki/Scrum_(software_development)) - an iterative and incremental agile software development framework for managing product development.

### Start-Up Resources
* [How to Start a Start-up](http://startupclass.samaltman.com/) - Series of lectures from successful entrepreneurs (i.e. Y comb, SV angels, etc.) on how to start a start up.

##Open Source Data Science Resources
While the name might sound redundant this section represents other sites or repos that have aggregated information covering similar topics.  Tons of great content on these sites - definitely go check them out.

### Other Open Source Data Science Content
There are some really great resources linked within this section covering all of Data Science, the entire data pipeline, machine-learning, statistics, python, etc.  Go check them out.
* [Open Data Science Masters](http://datasciencemasters.org/) - Clare Corthell's Open Source online blog/github with lots of resources available for data science.
* [A Practical Intro to Data Science](http://www.zipfianacademy.com/blog/post/46864003608/a-practical-intro-to-data-science) - Zipfian Academy's collection of excellent resources available.
* [LearnDataScience](https://github.com/nborwankar/LearnDataScience) - Nitin Borwankar's collection of IpythonNotebooks for Linear Regression, Logistic Regression, Random Forests, K-Means Clustering
* [FreeDataScienceBooks](https://github.com/chaconnewu/free-data-science-books/blob/master/free-data-science-books.md) - Yu Wu's free open sourced online data science books.
* [Gallery of Ipython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks) - iPython's introduction to Python, Data Science, Economics, Comp Sci, Linguistics, and much more.
* [Data Science 45 Min Intros](https://github.com/DrSkippy/Data-Science-45min-Intros) - The team @ Gnip have a collection of repos to introduce data science topics in roughly 45 minutes per topic.
* [Awesome Data Science](https://github.com/okulbilisim/awesome-datascience) - Collection of bloggers, twitter accounts, facebook accounts, MOOC's, datasets, tools.
* [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) - Onur Akpolat's curated list of awesome big data frameworks, resources and papers.
* [Mining the Social Web](https://github.com/ptwobrussell/Mining-the-Social-Web-2nd-Edition) - Matthew Russell's repo related to his book that focuses on working with the Twitter, Facebook, etc.
* [Harvard CS109 Github Repo](https://github.com/cs109/)
* [Pete Warden's Data Science Toolkit](https://github.com/petewarden/dstk) - Collection of open data sets and open-source tools for data science in ruby but has python.
* [Course Materials for Data Science Specialization](https://github.com/DataScienceSpecialization/courses) - Coursera course materials.
* [iPython Cookbook Materials](https://github.com/ipython-books/cookbook-code) - Excellent resources for high performance scientific computing and data science in python.

### Auxiliary Content & Apps
* [Markable](http://markable.in/editor/) - Let's me visualize Markdown
  * [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)  - Self explanatory.
* [LightPaper](http://www.ashokgelal.com/lightpaper-for-mac/) - Markdown editor that I use.
* [iterm2](http://iterm2.com/) - Terminal application for Mac.
* [Oh My Zsh](http://ohmyz.sh/) - Framework for managing your ZSH config.  Awesome.
* [Sublime Text Editor](http://www.sublimetext.com/) - For all your scripting needs.

## ABOUT ME

I am currently working at an advanced energy start-up called Stem which works on a significant amount of time-series problems and other data science related challenges.  I acquired my data science skills through programming in an on-the-job environment and then taking three months off to learn to hone my data science skills @ Zipfian Academy (since acquired by Galvanize).  For me taking that time off to learn, run the daily/weekly sprints, and be in a collective learning environment at Zipfian was irreplaceable.  Even if all of Zipfian resources were open source, without taking the time off work and having the drive to learn all the necessary material would be next to impossible.  

I am always interested to hear what other data scientists are up to, new resources and tools, and any new project ideas. If you have some project ideas or other resources that would be great to add here - feel free to reach out on Twitter [@sf_oak](http://bit.ly/1FefepA), [LinkedIn](http://linkd.in/1vp57dk) or [AngelList](https://angel.co/jonathan-bower).  






[![Analytics](https://ga-beacon.appspot.com/UA-50532302-5/jonathan-bower/DataScienceResources?pixel)](https://github.com/igrigorik/ga-beacon)

