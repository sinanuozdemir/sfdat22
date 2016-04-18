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
4/26: Time Series Data | 4/28: Working on a Data Problem || HW 2 Assigned (Th)
5/3: Clustering | 5/5: Natural Language Processing|| HW 2 Due (Th)
5/10: Naive Bayes | 5/12: Decision Trees | One Pager Due (Th)
5/17: Ensembling Techniques  | 5/19: Dimension Reduction<br>| Peer Review Due (Th) | HW 3 Assigned (Th)
5/24 Support Vector Machines | 5/26: Web Development with Flask || HW 3 Due (Th)
5/31/16: Recommendation Engines | 6/2: Neural Networks
6/7: Projects | 6/9: Projects | Git Er Done | Git Er Done


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
* Linear regression ([notebook](http://nbviewer.ipython.org/github/sinanuozdemir/sfdat22/blob/master/notebooks007_linear_regression.ipynb))
	* In depth slides [here](slides/07_linear_regression.pdf)

* LAB -- Yelp dataset [here](labs/07_yelp_reviews.md) with the [Yelp reviews data](data/yelp.csv). It is not required but your next homework will involve this dataset so it would be helpful to take a look now!

**Homework:**

* Watch these videos on [probability](https://www.youtube.com/watch?v=o4QmoNfW3bI) and [odds](https://www.youtube.com/watch?v=GxbXQjX7fC0) (8 minutes) if you're not familiar with either of those terms.
* Read these excellent articles from BetterExplained: [An Intuitive Guide To Exponential Functions & e](http://betterexplained.com/articles/an-intuitive-guide-to-exponential-functions-e/) and [Demystifying the Natural Logarithm (ln)](http://betterexplained.com/articles/demystifying-the-natural-logarithm-ln/).

**Resources:**

* [Correlation does not imply Causation](http://tylervigen.com/spurious-correlations)
* [P-values can't walsy be trusted](http://fivethirtyeight.com/features/science-isnt-broken/#part2)
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

