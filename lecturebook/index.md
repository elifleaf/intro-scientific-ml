# Course Information 

Welcome to the class website. Here you will find all course related information, and links to all course-related content. 

## Credit and Acknowledgements 

The course content draws extensively from the following: 

+ "Introduction to Scientific Machine Learning" by [Prof. Ilias Bilionis](https://engineering.purdue.edu/ME/People/ptProfile?resource_id=113500), Dept. of Mechanical Engineering, Purdue University. A big BIG thank you to Prof. Bilionis for making his lecture book and homework assignments available. Please see the original repo at [https://predictivesciencelab.github.io/data-analytics-se/index.html](https://predictivesciencelab.github.io/data-analytics-se/index.html).
+ Educational content available on youtube by [Prof. Ryan P. Adams](https://www.cs.princeton.edu/~rpa/), Dept. of Computer Science, Princeton University

## License 

This material is available under the GNU General Public License. You may reuse it as you wish, once you include the same License and cite the original repo linked above.  You may as well just use the original (Purdue) repo linked above.  

## Course and Instructor Information 

CRNs:
+ 60823: Section EN1 - in-person lecture, MW 9-11am, 2045 LUMEB.
+ 62822: Section EON - online/asynchronous for remote students.
+ 62823: Section ENC - online/asynchronous for on-campus students. 

Instructor: Elif Ertekin, Prof. of Mechanical Science and Engineering, University of Illinois, Urbana-Champaign. 
email: ertekin [at] illinois [dot] edu 
web: [https://oasis.mechse.illinois.edu](https://oasis.mechse.illinois.edu)

## Course Blurb  

This is an introductory but graduate level course for students who are interested in data science/machine learning methods as applied to problems in Engineering and the Physical Sciences.  Largely because of my own background in stochastic methods and applied math, we will introduce the concepts from the perspective of probabilistic modeling and highlight the principles behind the methods. Course content will be split approximately evenly between theory and applications. 

Topics to be covered: 
+ intro and review of probability theory (6 lectures - predictive modeling, basics, discrete and continuous random variables, collections of random variables, random vectors)
+ uncertainty propagation (4 lectures - sampling, Monte Carlo, Monte Carlo estimators, quantifying uncertainty)
+ Bayesian inference (2 lectures - selection of priors, some analytic examples)
+ supervised learning (4 lectures - linear and least squares regression, bayesian linear regression, classification)
+ unsupervised learning (2 lectures - clustering, density estimation, dimensionality reduction)
+ state space models (2 lectures)
+ Gaussian process regression (3 lectures - priors, conditioning, Bayesian global optimization)
+ neural networks (3 lectures - function approximation, deep, physics-informed)
+ sampling methods and variational inference (2 lectures) 

Expected outcomes: at the end of the course, you will be able to represent uncertainty in parameters in models, propagate uncertainty through physical models, solve basic supervised tasks (regression, classification, filtering), solve basic unsupervised tasks (clustering, dimensionality reduction, density estimation), design new models that by design include physical information and causal assumptions.  You will also gain skills in Python coding, loading and visualizing data in Jupyter notebooks, and use/recognize common Python libraries (pandas, scikit-learn) and software (PyTorch, TensorFlow, JAX).   

## Course Links 

+ Online lecturebook (here) :  https://elifleaf.github.io/intro-scientific-ml/ 
+ Public access repo : 
+ Slack : tam598scientificml.slack.com 
+ Canvas (only used for uploading HW pdfs and for recording grades) : 



## Prerequistes/Suggested Prior Background - What to Expect 

## Office Hours and Course-Related Communication 

In-person office hours will be held ... 

I can be reached using the course slack at most other times, and will respond to questions as soon as I am able.  Please note that questions related to course content, homework, etc should be posted and shared with everyone as this is a small class and many of us will benefit from the discussion. 

## Required Texts and Computer Tools 

## Grading 

## Disclaimer 

This is the first time I have taught this course.  Topics and schedule subject to change as I get a sense for timing. 




(intro)=
# Preface

These are the lecture notes for ME 539 Introduction to Scientific Machine Learning.
Please note that these notes are a companion to the class lectures.
They are not a self-contained, textbook-like exposition of the topic of scientific machine learning.
They are supposed to be complementary to the course lectures.

(course-description)=
## Course description

This course introduces data science for engineers who just started on their scientific machine-learning journey. We begin with an extensive review of probability theory as the language of uncertainty, discuss Monte Carlo sampling for uncertainty propagation, and cover the basics of supervised, unsupervised learning and state space models. The course also introduces physics-informed deep learning and its potential for revolutionizing engineering practice. We end with automated Bayesian inference using probabilistic programming, giving practical examples of research-grade problems. Throughout the course, the instructor follows a probabilistic perspective highlighting the first principles behind the presented method, aiming to teach students how to create and fit their models. 

(course-learning-outcomes)=
## Course learning outcomes
After completing this course, you will be able to: 
+ Represent uncertainty in parameters in engineering or scientific models using probability theory.
+ Propagate uncertainty through physical models to quantify the induced uncertainty in quantities of interest.
+ Solve basic supervised learning tasks like regression, classification, and filtering.
+ Solve basic unsupervised learning tasks, such as clustering, dimensionality reduction, and density estimation.
+ Create new models that encode physical information and other causal assumptions.
+ Calibrate arbitrary models using data.
+ Apply various Python coding skills.
+ Load and visualize data sets in Jupyter Notebooks.
+ Visualize uncertainty in Jupyter notebooks.
+ Recognize basic Python software (e.g., Pandas, numpy, scipy, sci-kit-learn) and advanced Python software (e.g., PyTorch, pyro, jax, pymc3) commonly used in modern data science.

(prerequisites)=
## Prerequisites
+ Working knowledge of multivariate calculus and basic linear algebra.
+ Basic Python knowledge.
+ Knowledge of probability and numerical methods for engineers would be helpful but optional.

(gaps)=
## What if I need to become more familiar with Python?
If you have no prior experience with Python, go over Lectures 1 to 6 of my undergraduate course on [data science for mechanical engineers](https://purduemechanicalengineering.github.io/me-297-intro-to-data-science/index.html).
These lectures include a very gentle introduction to the same basic Python concepts.
It should take you about a week to cover these seven lectures.
