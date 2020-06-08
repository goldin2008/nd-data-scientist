# Capstone

## Build Your Data Science Project
In this capstone project, you will leverage what you’ve learned throughout the program to build a data science project of your choosing. Your project deliverables are:

1. A Github repository of your work.

2. A blog (or other medium for a write-up) post written for a technical audience, or a deployed web application powered by data.

You'll follow the steps of the data science process that we've discussed:

1. You will first :+1:**define** the problem you want to solve and investigate potential solutions.

2. Next, you will :+1:**analyze** the problem through visualizations and data exploration to have a better understanding of what algorithms and features are appropriate for solving it.

3. You will then :+1:**implement** the algorithms and metrics of your choice, documenting the preprocessing, refinement, and post-processing steps along the way.

4. Afterwards, you will collect :+1:**results** about your findings, visualize significant quantities, validate/justify your results, and make any concluding remarks about whether your implementation adequately solves the problem.

5. Finally, you will :+1:**construct** a blog post (or other medium for a write-up) to document all of the steps from start to finish of your project, or deploy your results into a web application.

### Setting Yourself Apart
An important part of landing a job or advancing your career as a data scientist is setting yourself apart through impressive data science projects. By now, you've completed several guided projects, and now's your chance to show off your skills and creativity. You'll receive a review of your project with feedback from a Udacity mentor, and they will focus on how your project demonstrates your skills as a well-rounded data scientist.

This project is designed to prepare you for delivering a polished, end-to-end solution report of a real-world problem in a field of interest. When developing new technology, or deriving adaptations of previous technology, properly documenting your process is critical for both validating and replicating your results.

Things you will learn by completing this project:

- How to research and investigate a real-world problem of interest.
- How to accurately apply specific data science algorithms and techniques.
- How to properly analyze and visualize your data and results for validity.
- How to document and write a report of your work.

### Software Requirements
Your project must be written in Python 3.x. Given the free-form nature of the data scientist capstone, the software and libraries you will need to successfully complete your work will vary depending on the chosen application area and problem definition. Because of this, it is imperative that all necessary software and libraries used in your capstone project are accessible to the reviewer and clearly documented. Information regarding the software and libraries that your project makes use of should be included in your README document in your GitHub repo, along with your submission. Please note that proprietary software, software that requires private licenses, or software behind a paywall or login account should be avoided.

### Data Requirements
Every data scientist capstone project will most certainly require some form of dataset or input data structure (input text files, images, etc.). Similar to the software requirements above, the data you use must either be publicly accessible or provided by you during the submission process, and private or proprietary data should not be used without expressed permission. Please take into consideration the file size of your data — while there is no strict upper limit, input files that are excessively large may require reviewers longer than an acceptable amount of time to acquire all of your project files and/or execute the provided development code. This can take away from the reviewer's time that could be put towards evaluating your submission. If the data you are working with fits the criteria of being too large, consider whether you can work with a subset of the data instead, or provide a representative sample of the data which the reviewer may use to verify the solution explored in the project.

### Ethics
Udacity's A/B Testing course has a segment that discusses the sensitivity of data (free course link) and the expectation of privacy from those whose information has been collected. While most data you find has been made available to the public will not have any ethical complications, it is extremely important that you are considering where the data you are using came from, and whether that data contains any sensitive information. For example, if you worked for a bank and wanted to use customers' bank statements as part of your project, this would most likely be an unethical choice of data and should be avoided.

### Note on Spark Project
Not all of these instructions regarding software and data requirements apply if you choose the Spark project option, which comes with its own separate set of software and data requirements. You can find more details on this in the Spark course content in the Extracurriculars section of your classroom.

## Starbuck's Capstone Challenge
Instructions for the project can be found in the Starbucks Project Workspace.

### Dataset overview
- The program used to create the data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers.
- Each person in the simulation has some hidden traits that influence their purchasing patterns and are associated with their observable traits. People produce various events, including receiving offers, opening offers, and making purchases.
- As a simplification, there are no explicit products to track. Only the amounts of each transaction or offer are recorded.
- There are three types of offers that can be sent: buy-one-get-one (BOGO), discount, and informational. In a BOGO offer, a user needs to spend a certain amount to get a reward equal to that threshold amount. In a discount, a user gains a reward equal to a fraction of the amount spent. In an informational offer, there is no reward, but neither is there a requisite amount that the user is expected to spend. Offers can be delivered via multiple channels.
- The basic task is to use the data to identify which groups of people are most responsive to each type of offer, and how best to present each type of offer.

### Data Dictionary
#### profile.json
Rewards program users (17000 users x 5 fields)
- gender: (categorical) M, F, O, or null
- age: (numeric) missing value encoded as 118
- id: (string/hash)
- became_member_on: (date) format YYYYMMDD
- income: (numeric)

#### portfolio.json
Offers sent during 30-day test period (10 offers x 6 fields)
- reward: (numeric) money awarded for the amount spent
- channels: (list) web, email, mobile, social
- difficulty: (numeric) money required to be spent to receive reward
- duration: (numeric) time for offer to be open, in days
- offer_type: (string) bogo, discount, informational
- id: (string/hash)

#### transcript.json
Event log (306648 events x 4 fields)
- person: (string/hash)
- event: (string) offer received, offer viewed, transaction, offer completed
- value: (dictionary) different values depending on event type
-- offer id: (string/hash) not associated with any "transaction"
*- amount: (numeric) money spent in "transaction"
*- reward: (numeric) money gained from "offer completed"
- time: (numeric) hours after start of test
