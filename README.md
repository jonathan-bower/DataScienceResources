##Data Science Resources

This repo is here to provide some free and available resources from the internet.  It is intended to be an aid to practicing and/or aspiring Data Scientists.  Mostly it is a repo so that I can keep track of resources that were helpful to me at a given time along this journey of acquiring new skills.  It doesn't delve deeply into any of the theory - for that I would look to some of the online courses, books or bootcamps.    

The original plan is to break down resources in terms of skills necessary in each element of the data pipeline (Acquistion-Cleaning/Preprocessing-Modeling-Validation/Evaluation-Visualization).  

I figure it also makes sense to have some articles to provide some context and/or thought about elements of data science that haven't been overly talked about (use cases, career trajectories, feature engineering, product & data science, etc.).

I will include some links to other relevant topcis - such as a design/data visualization / aggregation sites for data science resources as I recognize that I am certainly not the only person doing this and there are a lot of good resources currently available. 

Personally, I acquired my skills through programming in an on-the-job environment and then taking three months off to learn and put into practice my data science skills @ Zipfian Academy.  For me taking that time off to learn, run the daily sprints, and be in a collective learning environment was irreplaceable.  Even if Zipfian resources were open source (which they aren't) taking the time off work and having the drive to push through all that material would be next to impossible. 

That being said - here is the collection of open source resources -- if you have anything to add or want to be a contributor - let me know.  I have taken the liberty to link to people's blogs - if anyone has any issues with that please let me know.  


#Table Of Contents
**update table of contents  
1.  [Scripting Languages](#Scripting-Languages)    
 * [Python](#Python)  
 * [Stats/Engineering Libraries](#Stats/Engineering-Libraries)  
 * [Databases/Frameworks](#Databases/Frameworks)  
 * [Data Acquisition](#Data-Acquisition)  
 * [Processing & EDA](#Processing-&-Exploratory-Data-Analysis)
 * [Feature Engineering](#Feature-Engineering)
 * [Machine Learning](#Machine-Learning)
 * [Other](#Other)
 * [Data @ Scale](#Data-@-Scale)
 * [Data Visualization](#Data-Visualization)
 * [Courses](#Courses)
 * [ipython Notebook Tutorials](#ipython-Notebook-Tutorials)
 * [Data Sources](#data-sources)

Section of the data pipeline & resources:

### Theory
Data Pipeline 
PlaceHolder for More Content **
![alt text](http://machinelearningmastery.com/wp-content/uploads/2014/05/Overview-of-the-Applied-Machine-Learning-Process.png) - Detailed overview of data pipeline from MachineLearningMastery.com



###Scripting Languages:
As I use predominantly python - I will keep this as the language of choice for this repo. I like python as it has applicability to work with other environments and problems outside from data analysis and it has many useful libraries.  There are many other languages that could be useful but are not covered here: Julia, R, Cython, Pig, Scala, Java, etc.

####Python 
[Python @ Codecademy](http://www.codecademy.com/en/tracks/python) - If you have never used Python, right this way..  
[The Python Wiki](https://wiki.python.org/moin/FrontPage)  
[Python for Data Science Tutorial - Kaggle](https://www.kaggle.com/wiki/GettingStartedWithPythonForDataScience) - Stepping into Data Science with Kaggle and installing some libraries   
There are many resources avaible to learn python elsewhere.  
[Introduction to Data Processing with Python](http://opentechschool.github.io/python-data-intro/) - Just as the name says - some introductory level information and exercises.

[Python Data Structures]  
[Object Oriented Programming]  
####Version Control
[Git tutorial](https://try.github.io/levels/1/challenges/1) - Simple tutorial for Git from Github.

####Stats/Engineering Libraries
[Pandas](http://pandas.pydata.org/) Pandas for EDA on small to medium sized data sets when you don't want to put the infrastructure for SQL or when it isn't necessary  
[Numpy/Pandas/Scipy Cheatsheet](https://s3.amazonaws.com/quandl-static-content/Documents/Quandl+-+Pandas,+SciPy,+NumPy+Cheat+Sheet.pdf)  
[SciPy](http://www.scipy.org/) - Open-source software for mathematics, science and engineering.  
[NumPy](http://www.numpy.org/) - Fundamental package for scientific computing with Python.  
[StatsModels](http://statsmodels.sourceforge.net/) - Module that allows users to explore data, estimate statistical models and perform statistical tests.  
[PyMC](https://pypi.python.org/pypi/pymc) - Bayesian estimation useful for Markov chain Monte Carlo analysis (among other things)
[Probalistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Github Repo all about the namesake.  

###Databases/Frameworks:
[SQL](http://www.postgresql.org/) -- SQL Database - I linked to Postgres since that is the version I use. 
[Psycopg](http://initd.org/psycopg/) -- Pyton <> Postgres.  Able to adapt PostgreSQL for the python environment   
[SQL Cheet Sheet](http://www.sql-tutorial.net/sql-cheat-sheet.pdf)   
[SQLZoo](http://sqlzoo.net/wiki/Main_Page) - Develop your skills
[SQLSchool](http://sqlschool.modeanalytics.com/) - Develop your skills  
[MongoDB](http://www.mongodb.org/) - NoSQL database
[PyMongo](http://api.mongodb.org/python/current/tutorial.html) - Python Mongo Driver.
[MongoDB - cheatsheet](https://blog.codecentric.de/files/2012/12/MongoDB-CheatSheet-v1_0.pdf) - Cheatsheet for MongoDB  
[Apache Hive](https://hive.apache.org/) - Uses Hiave Query Language (HQL) - similar to SQL for data at scale.     
[Hive - cheatsheet](http://hortonworks.com/wp-content/uploads/downloads/2013/08/Hortonworks.CheatSheet.SQLtoHive.pdf)  
[ElasticSearch](http://www.elasticsearch.org/) - For scalable, fast text search/analysis
[neo4j](http://www.neo4j.org/) - Leading graph database  
[redis](http://redis.io/) - Key-value open source data structure server  
[redshift](http://aws.amazon.com/redshift/) - AWS petabyte-scale data warehouse solution.  
[Hadoop - the definitive guide](http://ce.sysu.edu.cn/hope/UploadFiles/Education/2011/10/201110221516245419.pdf) - Hadoop ecosystem.
[Spark](https://spark.apache.org/) - Lightening fast cluser computing.

###Data Acquisition:
[BeautifulSoup](http://www.crummy.com/software/BeautifulSoup/) - a python library to make web-scraping HTML easier  
[Beautiful Soup Cheat Sheet](http://youkilljohnny.blogspot.com/2014/03/beautifulsoup-cheat-sheet-parse-html-by.html)  
[Requests](http://docs.python-requests.org/en/latest/) - HTTP for Humans - python library that makes working with http and api's more effortless  

###Processing & Exploratory Data Analysis:
[Unix for Processing](http://www.theunixschool.com/p/awk-sed.html) - sed & awk for data processing  
[Pandas](http://pandas.pydata.org/) - Already mentioned is great for data processing - cleaning, filtering and getting rid of nan's, normalizing, scaling, replacing values, etc  
[SciKit Learn for Preprocessing](http://scikit-learn.org/stable/modules/preprocessing.html#preprocessing)  
[Regular Expressions](http://www.zytrax.com/tech/web/regex.htm) - Regex explained.

###Feature Engineering:
** One of the critical elements of Data Science but also least talked about..  
[Ipyhon Notebook for Feature engineering](http://nbviewer.ipython.org/urls/raw2.github.com/yhat/DataGotham2013/master/notebooks/7%20-%20Feature%20Engineering.ipynb?create=1)
[CS Princeton Course](http://www.cs.princeton.edu/courses/archive/spring10/cos424/slides/18-feat.pdf)    
[Blog Post about Feature Engineering / Data Exploration](http://deblivingdata.net/machine-learning-tricks/)  

###Machine Learning:
There is a lot of information on the internet about the theory, mathematics, tuning, etc for this discipline - I am not trying to cover it in that depth, at least not at this current time.  These are just some high level toolkits to work with.  
[SciKit-Learn](http://scikit-learn.org/stable/) - Simple and efficient machine learning tools for data mining and data analysis    
[NLTK](9http://www.nltk.org/) - Natural Language Toolkit to work with human languages data.  
[Tour of Machine Learning Algorithms](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/) - Blog Post  
[Coursera Machine Learning Course](https://www.coursera.org/course/ml)  
[VIDEO - How to get started w/mL](https://www.youtube.com/watch?v=uBorfxosVYs) - Melanie Warrick @ PyCon 2014
![alt text](http://nyghtowlblog.files.wordpress.com/2014/04/ml_algorithms.png?w=535&h=311) - Classification for some sample ML algorithms
[SciKit-image](http://scikit-image.org/) - Algorithms for image processing

Model Selection:
[SciKit Learn Flow Chart for Model Selection](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html) - helpful for a starting point selecting SKlearn algorithms.

Model Evaluation:
[Evaluatin ML Algorithms](http://machinelearningmastery.com/how-to-evaluate-machine-learning-algorithms/) - Blog Post from MachineLearningMastery

### Other Skills:
[A/B Testing](http://conversionxl.com/how-to-build-a-strong-ab-testing-plan-that-gets-results/#.) Blog about A/B testing
[A/B Testing](http://unbounce.com/a-b-testing/5-ways-youre-screwing-up-your-a-b-testing/) And how you are screwing it up.  
[Bloom Filters](http://nbviewer.ipython.org/github/ctb/2013-pycon-awesome-big-data-algorithms/blob/master/04-bloom-filters.ipynb)  - Python notebook about bloom filters
[Bloom filters](http://billmill.org/bloomfilter-tutorial/)  
[Reservoir Sampling](http://blog.cloudera.com/blog/2013/04/hadoop-stratified-randosampling-algorithm/) - A primer on Reservoir Sampling  
[Reservoir Sampling Again](http://www.geeksforgeeks.org/reservoir-sampling/)  
[Monte Carlo for the Monty Hall Problem](http://slantedwindows.com/monty-hall-meet-mr-monte-carlo/) - Hyon puts on a good explaination.  
[Markov Chain Monte Carlo](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter3_MCMC/IntroMCMC.ipynb)  Opening the black box of MCMC.
[Multitreading and Queues](http://pymotw.com/2/Queue/)  
[Basics of Multithreading and queses](http://www.troyfawkes.com/learn-python-multithreading-queues-basics/)  
[Hash Tables]()


###Data @ Scale/Cloud Services:
[Amazon Web Services](http://aws.amazon.com/) - solid commercial resources for cloud services especially for start-ups.  

### Data Visualization
[ggplot](http://ggplot.yhathq.com/) -- ggplot for python ported by the team at yhat  
[matplotlib](http://matplotlib.org/) -- awesome plotting library for python.  
[d3](http://d3js.org/) - de facto gold standard for polished visualization - in js, steep learning curve.  
[bokeh](http://bokeh.pydata.org/) - interactive visualization library.  
[d3py](https://github.com/mikedewar/d3py) --  
[vincent](http://vincent.readthedocs.org/en/latest/)  --  
[seaborn](http://web.stanford.edu/~mwaskom/software/seaborn/) - clean statistical data visualization library.  
Design Theory -- The importance of design theory in data visualization and presentations could not be understated though many people pay no heed (probably through a lack of understanding than anything else).  I will try and find some good resources to fill this.


###Ipython Notebook Tutorials:
[Pandas Tutorial](http://nbviewer.ipython.org/github/twiecki/financial-analysis-python-tutorial/blob/master/1.%20Pandas%20Basics.ipynb) - Basic intro to Pandas in notebook form.  
[Scipy Tutorial](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-3-Scipy.ipynb)    
[Numpy Tutorial](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-2-Numpy.ipynb)  
[Multiple Regressions using Statsmodels](http://nbviewer.ipython.org/urls/s3.amazonaws.com/datarobotblog/notebooks/multiple_regression_in_python.ipynb)  
[Intro to PyMC](http://nbviewer.ipython.org/github/fonnesbeck/Bios366/blob/master/notebooks/Section4_3-Introduction-to-PyMC.ipynb)  
[More on PyMC](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter2_MorePyMC/MorePyMC.ipynb)  
[Kaggle Titanic Comp Tutorial](http://nbviewer.ipython.org/github/agconti/kaggle-titanic/blob/master/Titanic.ipynb)
[Psycopg2 tutorial in Python](https://wiki.postgresql.org/wiki/Psycopg2_Tutorial)   
[SQL in iPython](http://nbviewer.ipython.org/gist/catherinedevlin/6588378)  
[Mongo in Python](http://api.mongodb.org/python/current/tutorial.html)  
[Beautiful Soup Tutorial](http://nbviewer.ipython.org/github/kcranston/2013-08-ku/blob/master/beautifulsoup/notebooks/00-BeautifulSoup.ipynb)  
[Sci-Kit Learn Basics](http://nbviewer.ipython.org/urls/raw2.github.com/yhat/DataGotham2013/master/notebooks/4%20-%20scikit-learn%20basics.ipynb?create=1)  
[MatPlotLib](http://nbviewer.ipython.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-4-Matplotlib.ipynb)  
[Choosing the right priors - Bayesian](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Chapter6_Priorities/Priors.ipynb)  
[Some Basic Data Analysis in Python](http://nbviewer.ipython.org/github/jvns/talks/blob/master/pyconca2013/pistes-cyclables.ipynb)  
[Crash Course in Python for Scientists](http://nbviewer.ipython.org/gist/rpmuller/5920182) - Ipython Notebook  
[Regular Expressions](http://nbviewer.ipython.org/gist/rjweiss/7577022) - Regex to match patterns in strings - very powerful.  
[MapReduce](http://nbviewer.ipython.org/github/cs109/content/blob/master/labs/lab8/lab8_mapreduce.ipynb) - Classes, inheritance and mapreduce exercises.  
[Recursion](http://nbviewer.ipython.org/github/gumption/Motivating_and_Visualizing_Recursion_in_Python/blob/master/Motivating_and_Visualizing_Recursion_in_Python.ipynb)  Notebook visualization recursion "The single most powerful idea in algorithms"  
[Recursion](http://anandology.com/python-practice-book/functional-programming.html) More about Recursion and Functional Programming  


### Data Sources:
- Will include good data sources to practise.

### Data Science Career Path:
- Will find a blog post to discuss career trajectory


### Data Science Courses:
[Coursera](https://www.coursera.org/specialization/jhudatascience/1) - Data Science Specialization at Coursera - many other courses avialble as well.   
[Udacity](https://www.udacity.com/courses#!/data-science) - Online MOOCs these are the Data Science related courses      
[Data Science Bootcamps](http://yet-another-data-blog.blogspot.com/2014/04/data-science-bootcamp-landscape-full.html) - List of all bootcamps currently on the market as of April 5, 2014  
[Coursera Machine Learning Course](https://www.coursera.org/course/ml)  
[Edx](https://www.edx.org/course/mitx/mitx-6-00-2x-introduction-computational-2836#.VEANx9TF-tw)

### Types of Data Scientists:
[Kind's of Data Scientist](http://radar.oreilly.com/2013/06/theres-more-than-one-kind-of-data-scientist.html) - O'reilly's classification of 4 different data scientists.
[Data Science For Startups](http://tomtunguz.com/data-science-types/) Which of the Five Types of DS does your startup need?  Different classification from O'reilly.
[My own blog post about DS Types]
[Post about types of data team integration]

### Data Science Applications/Use Cases:
[Kaggle Data Science Use Cases](https://www.kaggle.com/wiki/DataScienceUseCases) - Helpful to generate ideas for new uses in different industries
[Big Data Analytics News - use Cases](http://bigdataanalyticsnews.com/big-data-use-cases/) - for Big Data but that's almost synonomous with Data Science.

### New Data Tools:
[BigML](https://bigml.com/) - machine learning for the everyday user. 
[GraphLab](http://graphlab.com/) - graph-based, high performance, distributed computation framework.  
[ModeAnalytics](https://modeanalytics.com/) - platform to share analysis/data science  

### Data Science Websites/Books:
[CrossValidated](http://stats.stackexchange.com/) - a question and answer site for people interested in statistics, machine learning, data analysis, data mining, and data visualization.    
[StackOverflow](stackoverflow.com) - language-independent collaboratively edited question and answer site for programmers.   
[Kaggle](http://www.kaggle.com) - Model building competition and great resources for training and data.  
[O'Reilly Media](http://shop.oreilly.com/category/get/data-science-kit.do) -They have a lot of content rich books available for Data Science and using the tools for excellent data science.    
[Quora](http://www.quora.com/) - Question and Answer site - lots of Data Science Content.  

### Data Science Meetups in the Bay Area
A great way to meet other Data Scientist and keep up to date with best practices.  
[SF Data Science](http://www.meetup.com/SF-Data-Science/)  
[Data Science for Sustainability](http://www.meetup.com/Data-Science-for-Sustainability/)  
[Python Meetup Group](http://www.meetup.com/sfpython/)  
[USF Seminar Series in Analytics](http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/http://www.meetup.com/USF-Seminar-Series-in-Analytics/)  
[DataKindSF](http://www.meetup.com/DataKind-SF-Bay-Area/)  
[SF Bayarea Machine Learning](http://www.meetup.com/SF-Bayarea-Machine-Learning/)  
[AirBnB Tech Talks](http://nerds.airbnb.com/tech-talks/)     


### Data Science Blogs:
[FastML](http://fastml.com/)  
[FiveThirtyEight Blog](http://fivethirtyeight.com/) - Nate Silver's blog  
[Simply Statistics Blog](http://simplystatistics.org/)  
[All The Things Tech](http://nyghtowl.io/)  
[Musings in Data Science](http://deblivingdata.net/)  
[Zipfian Data Science Blog](http://www.zipfianacademy.com/blog/)  
[Machine Learning Mastery](http://machinelearningmastery.com/)  

### Design Blogs:
[ThreeStoryBlog](http://blog.threestory.com/)


### Data Science Conferences:
[Strata](http://strataconf.com/) - Conference and a TON of old videos from previous conferences - great resource.  
[GraphLab](http://graphlab.com/events/conference14.html) - Another solid conference.  


### Relevent Business Processes:
[Lean Startup](http://theleanstartup.com/principles)  
[Agile Development](http://en.wikipedia.org/wiki/Agile_software_development)  
[Scrum](http://en.wikipedia.org/wiki/Scrum_(software_development))  

### Additional Git Hub Open Source Content:
[Open Data Science Masters](http://datasciencemasters.org/) - Open Source online blog with lots of resources avialable for data science.  
[A Practical Intro to Data Science](http://www.zipfianacademy.com/blog/post/46864003608/a-practical-intro-to-data-science) - List of excellent resources available  
[LearnDataScience](https://github.com/nborwankar/LearnDataScience) - IpythonNotebooks for Linear Regression, Logistic Regresison, Random Forests, K-Means Clustering  
[FreeDataScienceBooks](https://github.com/chaconnewu/free-data-science-books/blob/master/free-data-science-books.md) - Free open sourced online data science books.  
[Gallery of Ipython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks) -- 

### Other stuff:
[Markable](http://markable.in/editor/) - Let's me visualize my Markdown 
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
