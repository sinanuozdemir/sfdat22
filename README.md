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
