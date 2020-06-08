# nd-data-scientist
### Project: Write A Data Science Blog Post
**Introduction**

For this project, you will be creating a blog post and Github repository to begin building a data science portfolio of your own. You can gain some inspiration from Robert's posts here.
- Come up with three questions you are interested in answering.
- Extract the necessary data to answer these questions.
- Perform necessary cleaning, analysis, and modeling.
- Evaluate your results.
- Share your insights with stakeholders.

**Where to Start**

There are two components that are required for project completion.
- A Github repository for your code.
- A blog post of your findings.

Your Github repository must have the following contents:
- A README.md.
- Your code in a Jupyter notebook, with appropriate comments, analysis, and documentation.

You may also provide any other necessary documentation you find necessary. Your blog must provide the following:
- A clear and engaging title and image.
- Your questions of interest.
- Your findings for those questions with a supporting statistic(s), table, or visual.

The purpose of this project is for you to show off your technical skills, but more importantly for you to begin putting together a portfolio that shows your ability to effectively communicate technical results. Your technical skills will be built up as the program progresses, but for this project the main focus should be on communicating effectively the results of your analysis.

In this project follow the RUBRIC to assure you meet all of the necessary criteria for communicating your findings both as a developer and as a business professional.

**Data**

For this project, you will pick a dataset. Inspired by Robert, there are a few public datasets from AirBnB available below, but you may also choose a dataset similar to what was used in the lessons, or an entirely different dataset. Using your dataset, you will choose 3 questions you aspire to answer from the data.

**Stack Overflow Data - 2017 Survey**

You might have different questions about the 2017 StackOverflow survey data than I looked at earlier in the course. If you choose this dataset, you can not use the same questions that were analyzed earlier in the classroom.

Alternatively, if you felt pretty confident with the techniques in this lesson, you might be looking to push the envelope. In this case, you may choose to retrieve all of the Stack Overflow Survey - Multiple Years results. From this data, you could analyze trends over time. What languages were most popular in each year? What other changes can you observe over time?

**Seattle AirBNB Data**

The Seattle AirBnB homes data can be used at the above link. You might pair this with the Boston AirBnB data, which can be found at the link below.

**Boston AirBNB Data**

If you are looking to really challenge yourself, data from Seattle and Boston AirBNB homes can be used to understand how much AirBNB homes are earning in certain time frames and areas. You can compare rates between the two cities, or try to understand if there is anything about the properties that helps you predict price. Can you find negative and positive reviews based on text? This dataset requires a number of skills beyond those shown thus far in the course, but if you would like a challenge, this will certainly test your ability to work with messy, real world data.

You can find additional AirBnB data at the link here.

**Choose A Dataset of Your Own**

You are welcome to use Kaggle or another platform (or your own data) to create a blog and Github post instead of using the datasets discussed above.

**Key Steps for Project**

Feel free to be creative with your solutions, but do follow the CRISP-DM process in finding your solutions.

1) Pick a dataset.

2) Pose at least three questions related to business or real-world applications of how the data could be used.

3) Create a Jupyter Notebook, using any associated packages you'd like, to:

**Prepare data:**
- Gather necessary data to answer your questions
- Handle categorical and missing data
- Provide insight into the methods you chose and why you chose them

**Analyze, Model, and Visualize**
- Provide a clear connection between your business questions and how the data answers them.

4) Communicate your business insights:
- Create a Github repository to share your code and data wrangling/modeling techniques, with a technical audience in mind
- Create a blog post to share your questions and insights with a non-technical audience

Your deliverables will be a Github repo and a blog post. Use the rubric here to assist in successfully completing this project!


# Write-a-Data-Science-Blog-Post
A Udacity Data Scientist Nanodegree Project

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Black Friday Dataset from Kaggle to better understand:

Question 1: Which User spent most during black Friday, list the top 20 spending users

Question 2: How about the User Distribution by Age Group? And also consider Gender

Question 3: Which products are most popular during Black Friday, list the top 20

Question 4: Look at the users again, this time focus on group by Occupation in different city

Question 5: Correlation between Gender, Age, Occupation, City_Category, Stay_In_Current_City_Years, Marital_Status, Product_Category_x vs Purchase

## File Descriptions <a name="files"></a>

There are 1 notebooks available here to showcase work related to the above questions. The notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title. Markdown cells & comments were used to assist in walking through the thought process for individual steps.

BlackFriday.csv       - This file contains 550,000 observations about the black Friday in a retail store, it contains different kinds of variables either numerical or categorical. It contains missing values.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@goldin20082011/write-a-data-science-blog-post-f0209fcd188c).