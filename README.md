## SF DAT 22 Course Repository

Course materials for General Assembly's Data Science course in San Francisco, CA (3/29/16 - 6/9/16).

**Instructors:** [Sinan Ozdemir](https://www.linkedin.com/in/sinan-ozdemir-10568534) 
**Teaching Assistants:**
[Mars Williams](https://www.linkedin.com/in/marswilliams) / [Imeh Williams](https://www.linkedin.com/in/imehw)

**Office hours:** 

W: 5:30pm - 7:30pm

Sa: 12pm-2pm

Su: 12pm-2pm

All will be held in the student center at GA, 225 Bush Street

**[Course Project Information](project.md)**

**[Course Project Examples](project-examples.md)**


Tuesday | Thursday | Project Milestone | HW
--- | --- | --- | ---
3/29: Introduction / Expectations / Intro to Data Science | 3/31: Introduction to Git / Pandas
4/5: Pandas | 4/7: APIs / Web Scraping 101 | | HW 1 Assigned (Th)
4/12: Intro to Machine Learning / KNN | 4/14: Scikit-learn / Model Evaluation| Question and Data Set (Th) | HW 1 Due (Th)
4/19: Linear Regression | 4/21: Logistic Regression
4/26: Time Series Data | 4/28: Review (SF Crime Data Lab) || 
5/3: Clustering | 5/5: Natural Language Processing|| HW 2 Assigned (Th)
5/10: Naive Bayes | 5/12: Decision Trees / Ensembling Techniques | |HW 2 Due (Th)
5/17: Dimension Reduction  | 5/19: Web Development with Flask | One Pager Due (Th) | 
5/24: Recommendation Engines (**peer reviews due!!!!!!**) | 5/26: Support Vector Machines / Neural Networks | Peer Review Due (Tues)
5/31: Projects | 6/2: Projects | Git Er Done | Git Er Done


### Installation and Setup
* Install the [Anaconda distribution](http://continuum.io/downloads) of Python 2.7x.
* Install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and create a [GitHub](https://github.com/) account.
* Once you receive an email invitation from [Slack](https://slack.com/), join our "SF\_DAT\_17 team" and add your photo!

### Resources
* [PEP 8 - Style Guide for Python](http://www.python.org/dev/peps/pep-0008)
* [Learn How to Think Like a Computer Scientist](http://interactivepython.org/runestone/static/thinkcspy/toc.html#t-o-c)

### Class 1: Introduction / Expectations / Intro to Data Science / Python Exercises

####Agenda

* Introduction to General Assembly [slides](slides/01_DAT_intro_deck.pdf)
* Course overview: our philosophy and expectations ([slides](slides/01_course_overview.pdf))
* Intro to Data Science: [slides](slides/01_intro_to_data_science.pdf)

Break -- [**Command Line Tutorial**](http://generalassembly.github.io/prework/cl)

* Introduction on how to read and write iPython notebooks [tutorial](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/intro_to_ipython_notebooks.ipynb)
* Python pre-work [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/01_python_exercies.ipynb)
* Next class we will go over proper use of git and ipython notebooks in more depth



####Homework
* Make sure you have everything installed as specified above in "Installation and Setup" by Thursday
* Read this awesome intro to Git [here](http://www.dataschool.io/tag/git/)
* Read this intro to the iPython notebook [here](http://www.randalolson.com/2012/05/12/a-short-demo-on-how-to-use-ipython-notebook-as-a-research-notebook/)



--

### Class 2: Introduction to Git / Pandas

####Agenda

* Introduction to [Git](slides/02_git.pdf)
* Intro to Pandas walkthrough [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/02_pandas.ipynb)
	* Pandas is an excellent tool for exploratory data analysis
	* It allows us to easily manipulate, graph, and visualize basic statistics and elements of our data
	* [Pandas Lab!](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/labs/02_lab_pandas.ipynb)

####Homework
* Go through the python file and finish any exercise you weren't able to in class
* Make sure you have all of the repos cloned and ready to go
	* You should have both "sfdat22" and "sfdat22_work"
* Read Greg Reda's [Intro to Pandas](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/)
* Take a look at Kaggle's [Titanic competition](https://www.kaggle.com/c/titanic)

#### Resources:
* Another Git turorial [here](try.github.io)
* In depth Git/Github tutorial series made by a GA_DC  Data Science Instructor [here](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD)
* [Another Intro to Pandas](http://nbviewer.ipython.org/gist/wesm/4757075/PandasTour.ipynb) (Written by Wes McKinney and is adapted from his book)
	* [Here](https://vimeo.com/59324550) is a video of Wes McKinney going through his ipython notebook!

--

### Class 3: Pandas

####Agenda

* Don't forget to `git pull` in the sfdat22 repo in your command line
* Intro to Pandas walkthrough [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/02_pandas.ipynb) (same as last Thursdays)
	* [Pandas Lab 1](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/labs/02_lab_pandas.ipynb) (same as last Thursday)
* Extended Intro to Pandas walkthrough [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/03_pandas.ipynb) (new)
	* [Pandas Lab 2](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/labs/03_lab_pandas.ipynb) (new)

####Homework
* Finish any lab questions that you did not finish in class
	* Make sure everything is pushed to sfdat22_work if you'd like us to take a look
* make sure both requests and beautifulsoup are installed
	* To check, try `import requests` and `import bs4` both work without error while running python!
* Read this [intro to APIs](https://www.dataquest.io/blog/api-introduction/)
* Check out the National UFO Reporting Center [here](http://www.nuforc.org/) it will be one of the topics of the lab on Thursday

#### Resources:
   
* Examples of [joins in Pandas](http://www.gregreda.com/2013/10/26/working-with-pandas-dataframes/#joining)
* For more on Pandas plotting, read the [visualization page](http://pandas.pydata.org/pandas-docs/stable/visualization.html) from the official Pandas documentation.

--

### Class 4: APIs / Web Scraping 101

####Agenda

* I will also be using a module called `tweepy` today. 
	* To install please type into your console `conda install tweepy` 
		* OR if that does not work, `pip install tweepy`
* Slides on Getting Data [here](slides/04_getting_data.pdf)
* Intro to Regular Expressions [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/04_regex_example.ipynb)
* Getting Data from the open web [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/04_getting_data_from_web.ipynb)
* Getting Data from an API [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/04_getting_data_from_api.ipynb)
* LAB on getting data [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/labs/04_lab_getting_data.ipynb)

####Homework
* The first homework will be assigned by tomorrow morning (in a homework folder) and it is due NEXT Thursday (4/14)
	* It is a combo of pandas question with a bit of API/scraping
	* Please push your completed work to your sfdat22_work repo for grading

####Resources:

* [Mashape](https://www.mashape.com/) allows you to explore tons of different APIs. Alternatively, a Python API wrapper is available for many popular APIs.
* [The Data Science Toolkit](http://www.datasciencetoolkit.org/) is a collection of location-based and text-related APIs.
* [API Integration in Python](https://realpython.com/blog/python/api-integration-in-python/) provides a very readable introduction to REST APIs.
* [Microsoft's Face Detection API](https://www.microsoft.com/cognitive-services/en-us/face-api#detection), which powers [How-Old.net](https://how-old.net/), is a great example of how a machine learning API can be leveraged to produce a compelling web application.
Web Scraping Resources:
* For a much longer web scraping tutorial covering Beautiful Soup, lxml, XPath, and Selenium, watch [Web Scraping with Python](https://www.youtube.com/watch?v=p1iX0uxM1w8) (3 hours 23 minutes) from PyCon 2014. The slides and code are also available.
* [import.io](https://www.import.io/) and [Kimono](https://www.kimonolabs.com/) claim to allow you to scrape websites without writing any code. Its alrighhhtttttt
* [How a Math Genius Hacked OkCupid](http://www.wired.com/2014/01/how-to-hack-okcupid/all/) to Find True Love and [How Netflix Reverse Engineered](http://www.theatlantic.com/technology/archive/2014/01/how-netflix-reverse-engineered-hollywood/282679/?single_page=true) Hollywood are two fun examples of how web scraping has been used to build interesting datasets.

--
### Class 5: Intro to Machine Learning / KNN

####Agenda

* Iris pre-work [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/05_iris_prework.ipynb)
	* Using numpy to investigate the iris dataset further
	* Understanding how humans learn so that we can teach the machine!
* Intro to numpy [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/05_numpy_ref.ipynb)
	* Numerical Python, code adapted from tutorial [here](http://www.engr.ucsb.edu/~shell/che210d/numpy.pdf)
	* Special attention to the idea of the np.array

* Intro to Machine Learning and KNN [slides](slides/05_ml_knn.pdf)
	* Supervised vs Unsupervised Learning
	* Regression vs. Classification

* [Lab](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/labs/05_lab_knn.ipynb) to create our own KNN model


####Homework
* The one page project milestone as well as the pandas homework! [See requirements here](project.md)
* Read this excellent article, [Understanding the Bias-Variance Tradeoff](http://scott.fortmann-roe.com/docs/BiasVariance.html), and be prepared to discuss it in class on Wednesday. (You can ignore sections 4.2 and 4.3.) Here are some questions to think about while you read:
    * In the Party Registration example, what are the features? What is the response? Is this a regression or classification problem?
    * In the interactive visualization, try using different values for K across different sets of training data. What value of K do you think is "best"? How do you define "best"?
    * In the visualization, what do the lighter colors versus the darker colors mean? How is the darkness calculated?
    * How does the choice of K affect model bias? How about variance?
    * As you experiment with K and generate new training data, how can you "see" high versus low variance? How can you "see" high versus low bias?
    * Why should we care about variance at all? Shouldn't we just minimize bias and ignore variance?
    * Does a high value for K cause over-fitting or under-fitting?

    
**Resources:**

* For a more in-depth look at machine learning, read section 2.1 (14 pages) of Hastie and Tibshirani's excellent book, [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/). (It's a free PDF download!)

--


### Class 6: scikit-learn, Model Evaluation Procedures
* Introduction to scikit-learn with iris data ([code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/06_sklearn_knn.ipynb))
* Exploring the scikit-learn documentation: [user guide](http://scikit-learn.org/stable/modules/neighbors.html), [module reference](http://scikit-learn.org/stable/modules/classes.html#module-sklearn.neighbors), [class documentation](http://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
* Discuss the [article](http://scott.fortmann-roe.com/docs/BiasVariance.html) on the bias-variance tradeoff
* Look as some [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/06_bias_variance_tradeoff.ipynb) on the bias variace tradeoff
	* To run this, I use a module called "seaborn" 
	* To install to anywhere in your terminal (git bash) and type in `sudo pip install seaborn`
* Model evaluation procedures ([slides](slides/06_model_evaluation_procedures.pdf), [code](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/06_model_evaluation.ipynb))
* Glass Identification Lab [here](http://nbviewer.jupyter.org/github/sinanuozdemir/sfdat22/blob/master/labs/06_lab_glass.ipynb)

**Homework:**

* Keep working on your project. Your [data exploration and analysis plan](project.md) is due in three weeks!

**Optional:**

* Practice what we learned in class today! Finish up the Glass data lab

**Resources:**

* Here's a great [30-second explanation of overfitting](http://www.quora.com/What-is-an-intuitive-explanation-of-overfitting/answer/Jessica-Su).
* For more on today's topics, these videos from Hastie and Tibshirani are useful: [overfitting and train/test split](https://www.youtube.com/watch?v=_2ij6eaaSl0) (14 minutes), [cross-validation](https://www.youtube.com/watch?v=nZAM5OXrktY) (14 minutes). (Note that they use the terminology "validation set" instead of "test set".)
    * Alternatively, read section 5.1 (12 pages) of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), which covers the same content as the videos.
* This video from Caltech's machine learning course presents an [excellent, simple example of the bias-variance tradeoff](http://work.caltech.edu/library/081.html) (15 minutes) that may help you to visualize bias and variance.

--
### Class 7: Linear Regression
* Linear regression ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/07_linear_regression.ipynb))
	* In depth slides [here](slides/07_linear_regression.pdf)

* LAB -- Yelp dataset [here](labs/07_yelp_reviews.md) with the [Yelp reviews data](data/yelp.csv). It is not required but your next homework will involve this dataset so it would be helpful to take a look now!

**Homework:**

* Watch these videos on [probability](https://www.youtube.com/watch?v=o4QmoNfW3bI) and [odds](https://www.youtube.com/watch?v=GxbXQjX7fC0) (8 minutes) if you're not familiar with either of those terms.
* Read these excellent articles from BetterExplained: [An Intuitive Guide To Exponential Functions & e](http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/) and [Demystifying the Natural Logarithm (ln)](http://betterexplained.com/articles/demystifying-the-natural-logarithm-ln/).

**Resources:**

* [Correlation does not imply Causation](http://tylervigen.com/spurious-correlations)
* [P-values can't always be trusted](http://fivethirtyeight.com/features/science-isnt-broken/#part2)
* Setosa has an excellent [interactive visualization](http://setosa.io/ev/ordinary-least-squares-regression/) of linear regression.
* To go much more in-depth on linear regression, read Chapter 3 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), from which this lesson was adapted. Alternatively, watch the [related videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) or read my [quick reference guide](http://www.dataschool.io/applying-and-interpreting-linear-regression/) to the key points in that chapter.
* To learn more about Statsmodels and how to interpret the output, DataRobot has some decent posts on [simple linear regression](http://www.datarobot.com/blog/ordinary-least-squares-in-python/) and [multiple linear regression](http://www.datarobot.com/blog/multiple-regression-using-statsmodels/).
* This [introduction to linear regression](http://people.duke.edu/~rnau/regintro.htm) is much more detailed and mathematically thorough, and includes lots of good advice.
* This is a relatively quick post on the [assumptions of linear regression](http://pareonline.net/getvn.asp?n=2&v=8).
* John Rauser's talk on [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) (12 minutes) gives a great explanation of how the null hypothesis is rejected.
* A major scientific journal recently banned the use of p-values:
    * Scientific American has a nice [summary](http://www.scientificamerican.com/article/scientists-perturbed-by-loss-of-stat-tools-to-sift-research-fudge-from-fact/) of the ban.
    * This [response](http://www.nature.com/news/statistics-p-values-are-just-the-tip-of-the-iceberg-1.17412) to the ban in Nature argues that "decisions that are made earlier in data analysis have a much greater impact on results".
    * Andrew Gelman has a readable [paper](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf) in which he argues that "it's easy to find a p < .05 comparison even if nothing is going on, if you look hard enough".
* An article on ["P Hacking"](http://www.dailydot.com/geek/data-manipulation-tool-science-p-hacking/) the idea that you can alter data in order to achieve good p values

--

### Class 8: Logistic Regression
* Logistic regression ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/08_logistic_regression.ipynb))
	* BONUS slides [here](slides/08_logistic_regression.pdf) (These slides go a bit deeper into the math)
* Confusion matrix ([slides](slides/08_confusion_matrix.pdf))
* LAB -- Exercise with Titanic data [instructions](labs/08_titanic.md)

**Homework:**

* If you aren't yet comfortable with all of the confusion matrix terminology, watch Rahul Patwari's videos on [Intuitive sensitivity and specificity](https://www.youtube.com/watch?v=U4_3fditnWg) (9 minutes) and [The tradeoff between sensitivity and specificity](https://www.youtube.com/watch?v=vtYDyGGeQyo) (13 minutes).

**Resources:**

* To go deeper into logistic regression, read the first three sections of Chapter 4 of [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/), or watch the [first three videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/) (30 minutes) from that chapter.
* For a math-ier explanation of logistic regression, watch the first seven videos (71 minutes) from week 3 of Andrew Ng's [machine learning course](https://www.coursera.org/learn/machine-learning/home/info), or read the [related lecture notes](http://www.holehouse.org/mlclass/06_Logistic_Regression.html) compiled by a student.
* For more on interpreting logistic regression coefficients, read this excellent [guide](http://www.ats.ucla.edu/stat/mult_pkg/faq/general/odds_ratio.htm) by UCLA's IDRE and these [lecture notes](http://www.unm.edu/~schrader/biostat/bio2/Spr06/lec11.pdf) from the University of New Mexico.
* The scikit-learn documentation has a nice [explanation](http://scikit-learn.org/stable/modules/calibration.html) of what it means for a predicted probability to be calibrated.
* [Supervised learning superstitions cheat sheet](http://ryancompton.net/assets/ml_cheat_sheet/supervised_learning.html) is a very nice comparison of four classifiers we cover in the course (logistic regression, decision trees, KNN, Naive Bayes) and one classifier we do not cover (Support Vector Machines).
* This [simple guide to confusion matrix terminology](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) may be useful to you as a reference.

--

### Class 9: Time Series Data
* Time Series ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/09_time_series.ipynb))
	* slides [here](slides/09_time_series.pdf)
* LAB -- Walmart Sales Forecasting [instructions](labs/09_lab_time_series.ipynb)


**Resources:**

* Some more practice with time series [here](http://earthpy.org/pandas-basics.html)
	* And [here](http://chrisalbon.com/python/pandas_time_series_basics.html)
* More practice with [Autocorrelation](http://pandasplotting.blogspot.com/2012/06/autocorrelation-plot.html)
* Extensive blog on time series and [ARIMA](http://www.analyticsvidhya.com/blog/2016/02/time-series-forecasting-codes-python/)


--

### Class 10: Review (crime doesn't pay)
* Review on the board
* Review part deux ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat22/blob/master/notebooks/10_review.ipynb))
* LAB -- Kaggle competition [instructions](https://www.kaggle.com/c/sf-crime)

### Class 11: Clustering
* Clustering ([slides](slides/11_clustering.pdf), [notebook](notebooks/11_clustering.ipynb))
    * K-means: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html), [visualization 1](http://tech.nitoyon.com/en/blog/2013/11/07/k-means/), [visualization 2](http://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
    * DBSCAN: [documentation](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html), [visualization](http://www.naftaliharris.com/blog/visualizing-dbscan-clustering/)
    * LAB -- Pandora [notebook](labs/11_lab_pandora.ipynb)

**Homework:**

* **Homework 2 is due in one week!**
* **Project Milestone 2 is due in two weeks!**
* Download all of the NLTK collections.
   * In Python, use the following commands to bring up the download menu.
   * ```import nltk```
   * ```nltk.download()```
   * Choose "all".
   * Alternatively, just type ```nltk.download('all')```
* Install two new packages:  ```textblob``` and ```lda```.
   * Open a terminal or command prompt.
   * Type ```pip install textblob``` and ```pip install lda```.
 



**Resources:**

* For a very thorough introduction to clustering, read chapter 8 (69 pages) of [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php) (available as a free download), or browse through the chapter 8 slides.
* scikit-learn's user guide compares many different [types of clustering](http://scikit-learn.org/stable/modules/clustering.html).
* This [PowerPoint presentation](http://www2.research.att.com/~volinsky/DataMining/Columbia2011/Slides/Topic6-Clustering.ppt) from Columbia's Data Mining class provides a good introduction to clustering, including hierarchical clustering and alternative distance metrics.
* An Introduction to Statistical Learning has useful videos on [K-means clustering](https://www.youtube.com/watch?v=aIybuNt9ps4&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (17 minutes) and [hierarchical clustering](https://www.youtube.com/watch?v=Tuuc9Y06tAc&list=PL5-da3qGB5IBC-MneTc9oBZz0C6kNJ-f2) (15 minutes).
* This is an excellent interactive visualization of [hierarchical clustering](https://joyofdata.shinyapps.io/hclust-shiny/).
* This is a nice animated explanation of [mean shift clustering](http://spin.atomicobject.com/2015/05/26/mean-shift-clustering/).
* The [K-modes algorithm](http://www.cs.ust.hk/~qyang/Teaching/537/Papers/huang98extensions.pdf) can be used for clustering datasets of categorical features without converting them to numerical values. Here is a [Python implementation](https://github.com/nicodv/kmodes).
* Here are some fun examples of clustering: [A Statistical Analysis of the Work of Bob Ross](http://fivethirtyeight.com/features/a-statistical-analysis-of-the-work-of-bob-ross/) (with [data and Python code](https://github.com/fivethirtyeight/data/tree/master/bob-ross)), [How a Math Genius Hacked OkCupid to Find True Love](http://www.wired.com/2014/01/how-to-hack-okcupid/all/), and [characteristics of your zip code](http://www.esri.com/landing-pages/tapestry/).

--

##Class 12: Natural Language Processing

**Agenda**

* Naural Language Processing is the science of turning words and sentences into data and numbers. Today we will be exploring techniques into this field
* [code](notebooks/12_nlp.ipynb) showing topics in NLP
* [lab](labs/12_lab_nlp.ipynb) analyzing tweets about the stock market


**Homework:**

* HW2 is assigned in the hw folder
* Read Paul Graham's [A Plan for Spam](http://www.paulgraham.com/spam.html) and be prepared to **discuss it in class on Wednesday**. Here are some questions to think about while you read:
    * Should a spam filter optimize for sensitivity or specificity, in Paul's opinion?
    * Before he tried the "statistical approach" to spam filtering, what was his approach?
    * How exactly does his statistical filtering system work?
    * What did Paul say were some of the benefits of the statistical approach?
    * How good was his prediction of the "spam of the future"?
* Below are the foundational topics upon which Wednesday's class will depend. Please review these materials before class:
    * **Confusion matrix:** [a good guide](http://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/) roughly mirrors the lecture from class 10.
    * **Sensitivity and specificity:** Rahul Patwari has an [excellent video](https://www.youtube.com/watch?v=U4_3fditnWg&list=PL41ckbAGB5S2PavLIXUETzAmi5reIod23) (9 minutes).
    * **Basics of probability:** These [introductory slides](https://docs.google.com/presentation/d/1cM2dVbJgTWMkHoVNmYlB9df6P2H8BrjaqAcZTaLe9dA/edit#slide=id.gfc3caad2_00) (from the [OpenIntro Statistics textbook](https://www.openintro.org/stat/textbook.php)) are quite good and include integrated quizzes. Pay specific attention to these terms: probability, sample space, mutually exclusive, independent.
* You should definitely be working on your project! First draft is due Monday!!

--

##Class 13: Naive Bayes Classifier

Today we are going over advanced metrics for classification models and learning a brand new classification model called naive bayes!

**Agenda**

* Are you smart enough to work at [Facebook?](https://www.glassdoor.com/Interview/You-re-about-to-get-on-a-plane-to-Seattle-You-want-to-know-if-you-should-bring-an-umbrella-You-call-3-random-friends-of-y-QTN_519262.htm)
* Learn about Naive Bayes and ROC/AUC curves 
	* 	Slides [here](slides/13_naive_bayes_roc_auc.pdf)
	* 	Code [here](notebooks/13_naive_bayes_roc_auc.ipynb)
	* In the code file above we will create our own spam classifier!
* Work on Homework / previous labs


**Resources**

* Bayes Theorem as applied to Monty Hall [here](https://www.quora.com/How-do-I-solve-the-Monty-Hall-Problem-using-Bayes-Theorem) and [here](http://angrystatistician.blogspot.com/2012/06/bayes-solution-to-monty-hall.html)
* Video on [ROC Curves](https://www.youtube.com/watch?v=21Igj5Pr6u4&list=PL41ckbAGB5S2PavLIXUETzAmi5reIod23) (12 minutes).
* My good buddy's [blog post about the ROC video](http://www.dataschool.io/roc-curves-and-auc-explained/) includes the complete transcript and screenshots, in case you learn better by reading instead of watching.
* Accuracy vs AUC discussions [here](http://stats.stackexchange.com/questions/32139/roc-vs-accuracy) and [here](http://datascience.stackexchange.com/questions/806/advantages-of-auc-vs-standard-accuracy)

--

### Class 14: Decision Trees / Ensembling
* Decision trees ([notebook](notebooks/14_decision_trees.ipynb))
* Ensembling ([notebook](notebooks/14_ensembling.ipynb))
    * [Major League Baseball player data](data/hitters.csv) from 1986-87
    * [Data dictionary](https://cran.r-project.org/web/packages/ISLR/ISLR.pdf) (page 7)


**Decision Tree Resources:**

* scikit-learn's documentation on [decision trees](http://scikit-learn.org/stable/modules/tree.html) includes a nice overview of trees as well as tips for proper usage.
* For a more thorough introduction to decision trees, read section 4.3 (23 pages) of [Introduction to Data Mining](http://www-users.cs.umn.edu/~kumar/dmbook/index.php). (Chapter 4 is available as a free download.)
* If you want to go deep into the different decision tree algorithms, this slide deck contains [A Brief History of Classification and Regression Trees](https://drive.google.com/file/d/0B-BKohKl-jUYQ3RpMEF0OGRUU3RHVGpHY203NFd3Z19Nc1ZF/view).
* [The Science of Singing Along](http://www.doc.gold.ac.uk/~mas03dm/papers/PawleyMullensiefen_Singalong_2012.pdf) contains a neat regression tree (page 136) for predicting the percentage of an audience at a music venue that will sing along to a pop song.
* Decision trees are common in the medical field for differential diagnosis, such as this classification tree for [identifying psychosis](http://www.psychcongress.com/sites/naccme.com/files/images/pcn/saundras/psychosis_decision_tree.pdf).

**Ensembling Resources:**

* scikit-learn's documentation on [ensemble methods](http://scikit-learn.org/stable/modules/ensemble.html) covers both "averaging methods" (such as bagging and Random Forests) as well as "boosting methods" (such as AdaBoost and Gradient Tree Boosting).
* MLWave's [Kaggle Ensembling Guide](http://mlwave.com/kaggle-ensembling-guide/) is very thorough and shows the many different ways that ensembling can take place.
* Browse the excellent [solution paper](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/ChenglongChen/Kaggle_CrowdFlower/master/Doc/Kaggle_CrowdFlower_ChenglongChen.pdf) from the winner of Kaggle's [CrowdFlower competition](https://www.kaggle.com/c/crowdflower-search-relevance) for an example of the work and insight required to win a Kaggle competition.
* [Interpretable vs Powerful Predictive Models: Why We Need Them Both](https://medium.com/@chris_bour/interpretable-vs-powerful-predictive-models-why-we-need-them-both-990340074979) is a short post on how the tactics useful in a Kaggle competition are not always useful in the real world.
* [Not Even the People Who Write Algorithms Really Know How They Work](http://www.theatlantic.com/technology/archive/2015/09/not-even-the-people-who-write-algorithms-really-know-how-they-work/406099/) argues that the decreased interpretability of state-of-the-art machine learning models has a negative impact on society.
* For an intuitive explanation of Random Forests, read Edwin Chen's answer to [How do random forests work in layman's terms?](http://www.quora.com/Random-Forests/How-do-random-forests-work-in-laymans-terms/answer/Edwin-Chen-1)
* [Large Scale Decision Forests: Lessons Learned](http://blog.siftscience.com/blog/2015/large-scale-decision-forests-lessons-learned) is an excellent post from Sift Science about their custom implementation of Random Forests.
* [Unboxing the Random Forest Classifier](http://nerds.airbnb.com/unboxing-the-random-forest-classifier/) describes a way to interpret the inner workings of Random Forests beyond just feature importances.
* [Understanding Random Forests: From Theory to Practice](http://arxiv.org/pdf/1407.7502v3.pdf) is an in-depth academic analysis of Random Forests, including details of its implementation in scikit-learn.

--

### Class 15: Dimension Reduction

* Finish up Ensembling ([notebook](notebooks/14_ensembling.ipynb))
    * [Major League Baseball player data](data/hitters.csv) from 1986-87
    * [Data dictionary](https://cran.r-project.org/web/packages/ISLR/ISLR.pdf) (page 7)
* PCA
	* [Explained visually](http://setosa.io/ev/principal-component-analysis/)
    * [Slides](slides/15_dimension_reduction.pdf)
    * Code: [PCA](notebooks/15_pca.ipynb)


**Resources**

* Some hardcore math in python [here](code/15_pca_svd_class.py)
* PCA using the iris data set [here](http://scikit-learn.org/0.11/auto_examples/decomposition/plot_pca_iris.html) and with 2 components [here](http://scikit-learn.org/stable/auto_examples/decomposition/plot_pca_vs_lda.html)
* PCA step by step [here](http://sebastianraschka.com/Articles/2014_pca_step_by_step.html)
* Check out [Pyxley](http://multithreaded.stitchfix.com/blog/2015/07/16/pyxley/)

--

### Class 17: Web Development with Flask and Heroku

**Objectives**

* To launch your own machine learning powered website

**Agenda**

* Sign up for Project times NEXT WEEK
* Slides [here](slides/17_web_development.pdf)

**Homework**

* Work on your project!!
* Work on your project!!
* Work on your project!!
* Work on your project!!
* please
* Work on your project!!

--

### Class 18: Neural Networks and SVM

**Agenda**

* Sign up for a project slot [here](https://docs.google.com/spreadsheets/d/1Nc9ettfPvVNV23nAqLMdaL37WiQ6kIFKXGlHy5VgD2I/edit#gid=0)
* slides [here](slides/18_nn_svm.pdf)
* SVM notebook [here](notebooks/18_svm.ipynb)
* Neural Network notebook [here](notebooks/18_nn.ipynb)
* We will need a new package [Pybrain](http://pybrain.org/)!!   `sudo pip install pybrain`


### Office Hours this weekend are Saturday from 9am-5pm and Sunday from 12pm-2pm
#### Project questions ONLY 



**Resources**


* An intro to Neural Networks [here](http://natureofcode.com/book/chapter-10-neural-networks/)
* An intro to [SVM](http://www.cs.columbia.edu/~kathy/cs4701/documents/jason_svm_tutorial.pdf)
* SVM Margins Example [here](http://scikit-learn.org/stable/auto_examples/svm/plot_svm_margin.html)
* SVM digits was adapted from [here](http://pythonprogramming.net/support-vector-machine-svm-example-tutorial-scikit-learn-python/)
* [Google Deep Dream: why does it always see dogs?!](http://www.fastcodesign.com/3048941/why-googles-deep-dream-ai-hallucinates-in-dog-faces)
* [Deep Dream Generator](http://deepdreamgenerator.com/)
* Most used non-sklearn ANN [PyBrain](http://pybrain.org/)
* Step by Step back propagation [here](http://home.agh.edu.pl/~vlsi/AI/backp_t_en/backprop.html)
* Code adapted from [here](http://iamtrask.github.io/2015/07/12/basic-python-network/) and [here](http://corpocrat.com/2014/10/10/tutorial-pybrain-neural-network-for-classifying-olivetti-faces/)
* Calculus adapted from [here](http://math.stackexchange.com/questions/78575/derivative-of-sigmoid-function-sigma-x-frac11e-x)
* Sklearn will come out with their own supervised neural network soon! [here](http://scikit-learn.org/dev/modules/neural_networks_supervised.html)

