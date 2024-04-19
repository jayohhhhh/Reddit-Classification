# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Web APIs & NLP

### Description

In week four we learned about a few different classifiers. In week five we're learning about webscraping, APIs, and Natural Language Processing (NLP). This project will put those skills to the test.

For project 3, your goal is two-fold:
1. Using [PRAW](https://praw.readthedocs.io/en/stable/index.html), you'll collect posts from two subreddits of your choosing.
2. You'll then use NLP to train a classifier on which subreddit a given post came from. This is a binary classification problem.


#### About the API

For this project, you will be using [PRAW](https://praw.readthedocs.io/en/stable/index.html) to collect posts from two different subreddits. 

To help you get started, we have a [notebook](./Reddit-PRAW-tutorial.ipynb) detailing the process of creating an app and obtaining your API credentials.

Note: Rather than working in this template notebook, make a brand new "scraping" notebook (or script), with your own unique work and comments, so you can use this project in a portfolio!

---

### Requirements

- Gather and prepare your data using PRAW. DONE
- **Create and compare two models**. Any two classifiers at least of your choosing: random forest, logistic regression, KNN, SVM, etc. DONE
- A Jupyter Notebook with your analysis for a peer audience of data scientists. DONE
- An executive summary of your results.
- A short presentation outlining your process and findings for a semi-technical audience.

**Pro Tip:** You can find a good example executive summary [here](https://www.proposify.biz/blog/executive-summary).

---

### Necessary Deliverables / Submission

- Code must be in at least one clearly commented Jupyter Notebook.
- A readme/executive summary in markdown.
- You must submit your slide deck as a PDF.
- Materials must be submitted by **10:00 AM (EST) on Monday, 3/4**.

---

## Rubric
Your instructors will evaluate your project (for the most part) using the following criteria.  You should make sure that you consider and/or follow most if not all of the considerations/recommendations outlined below **while** working through your project.

For Project 3 the evaluation categories are as follows:<br>
**The Data Science Process**
- Problem Statement DONE
- Data Collection DONE
- Data Cleaning & EDA DONE
- Preprocessing & Modeling DONE
- Evaluation and Conceptual Understanding DONE
- Conclusion and Recommendations DONE

**Organization and Professionalism**
- Organization
- Visualizations
- Python Syntax and Control Flow
- Presentation

**Scores will be out of 30 points based on the 10 categories in the rubric.** <br>
*3 points per section*<br>

| Score | Interpretation |
| --- | --- |
| **0** | *Project fails to meet the minimum requirements for this item.* |
| **1** | *Project meets the minimum requirements for this item, but falls significantly short of portfolio-ready expectations.* |
| **2** | *Project exceeds the minimum requirements for this item, but falls short of portfolio-ready expectations.* |
| **3** | *Project meets or exceeds portfolio-ready expectations; demonstrates a thorough understanding of every outlined consideration.* |


### The Data Science Process

**Problem Statement**
- Is it clear what the goal of the project is? YES
- What type of model will be developed? YES
- How will success be evaluated? YES
- Is the scope of the project appropriate? YES
- Is it clear who cares about this or why this is important to investigate? YES
- Does the student consider the audience and the primary and secondary stakeholders? YES

**Data Collection**
- Was enough data gathered to generate a significant result? (At least 1000 posts per subreddit) YES
- Was data collected that was useful and relevant to the project? YES
- Was data collection and storage optimized through custom functions, pipelines, and/or automation? YES
- Was thought given to the server receiving the requests such as considering number of requests per second? YES

**Data Cleaning and EDA**
- Are missing values imputed/handled appropriately? YES
- Are distributions examined and described? YES
- Are outliers identified and addressed? YES
- Are appropriate summary statistics provided? YES
- Are steps taken during data cleaning and EDA framed appropriately? YES
- Does the student address whether or not they are likely to be able to answer their problem statement with the provided data given what they've discovered during EDA? YES

**Preprocessing and Modeling**
- Is text data successfully converted to a matrix representation? YES
- Are methods such as stop words, stemming, and lemmatization explored? YES
- Does the student properly split and/or sample the data for validation/training purposes? YES
- Does the student test and evaluate a variety of models to identify a production algorithm (**AT MINIMUM:** two models)? YES
- Does the student defend their choice of production model relevant to the data at hand and the problem? YES
- Does the student explain how the model works and evaluate its performance successes/downfalls? YES

**Evaluation and Conceptual Understanding**
- Does the student accurately identify and explain the baseline score? YES
- Does the student select and use metrics relevant to the problem objective? YES
- Does the student interpret the results of their model for purposes of inference? YES
- Is domain knowledge demonstrated when interpreting results? YES
- Does the student provide appropriate interpretation with regards to descriptive and inferential statistics? YES

**Conclusion and Recommendations**
- Does the student provide appropriate context to connect individual steps back to the overall project? YES
- Is it clear how the final recommendations were reached? YES
- Are the conclusions/recommendations clearly stated? YES
- Does the conclusion answer the original problem statement? YES
- Does the student address how findings of this research can be applied for the benefit of stakeholders? YES
- Are future steps to move the project forward identified? YES


### Organization and Professionalism

**Project Organization**
- Are modules imported correctly (using appropriate aliases)? YES
- Are data imported/saved using relative paths? YES
- Does the README provide a good executive summary of the project? YES
- Is markdown formatting used appropriately to structure notebooks? YES
- Are there an appropriate amount of comments to support the code? YES
- Are files & directories organized correctly? YES
- Are there unnecessary files included? NO
- Do files and directories have well-structured, appropriate, consistent names? YES

**Visualizations**
- Are sufficient visualizations provided? YES
- Do plots accurately demonstrate valid relationships? YES
- Are plots labeled properly? YES
- Are plots interpreted appropriately? YES
- Are plots formatted and scaled appropriately for inclusion in a notebook-based technical report? YES

**Python Syntax and Control Flow**
- Is care taken to write human readable code? YES
- Is the code syntactically correct (no runtime errors)? YES
- Does the code generate desired results (logically correct)? YES
- Does the code follows general best practices and style guidelines? YES
- Are Pandas functions used appropriately? YES
- Are `sklearn` and `NLTK` methods used appropriately? YES

**Presentation**
- Is the problem statement clearly presented? YES
- Does a strong narrative run through the presentation building toward a final conclusion? YES
- Are the conclusions/recommendations clearly stated? YES
- Is the level of technicality appropriate for the intended audience? YES
- Is the student substantially over or under time? GOOD
- Does the student appropriately pace their presentation? GOOD
- Does the student deliver their message with clarity and volume? GOOD
- Are appropriate visualizations generated for the intended audience? YES
- Are visualizations necessary and useful for supporting conclusions/explaining findings? YES


---

### Why did we choose this project for you?
This project covers three of the biggest concepts we cover in the class: Classification Modeling, Natural Language Processing and Data Wrangling/Acquisition.

Part 1 of the project focuses on **Data wrangling/gathering/acquisition**. This is a very important skill as not all the data you will need will be in clean CSVs or a single table in SQL.  There is a good chance that wherever you land you will have to gather some data from some unstructured/semi-structured sources; when possible, requesting information from an API, but sometimes scraping it because they don't have an API (or it's terribly documented).

Part 2 of the project focuses on **Natural Language Processing** and converting standard text data (like Titles and Comments) into a format that allows us to analyze it and use it in modeling.

Part 3 of the project focuses on **Classification Modeling**.  Given that project 2 was a regression focused problem, we needed to give you a classification focused problem to practice the various models, means of assessment and preprocessing associated with classification.   
