#2019 IMFS Data Science Competition - Netflix for Bonds#

Week 0 - Setting Up
Welcome to the 2019 IMFS Competition!

What (The Challenge)

Your challenge is to build a recommendation system that matches similar bond based on the revealed preferences of an expert trader.

Backstory: In an alternative universe, Vanguard employs several robotic crewmembers (manufactured by the Tyrell corporation) to perform certain parts of the investment lifecycle. One of the best robots, TRACE_Y, is very good at picking complementary bonds for various portfolios with an inexplicable knack for predicting which bonds will perform best in a diversified portfolio. Nobody has been able to replicate her work. Unfortunately, not only is TRACE_Y very good at picking bonds, she is also very good at picking the winning lottery numbers and just retired to a beach shack in Key West, where she plans to go off grid. This leaves you, the portfolio manager, with no way to pick bonds unless you can recreate the mind of the robot! All you have is a historical set of bonds that TRACE_Y looked at and her assessment of the ISIN of the nearest bond. Not every bond is labelled and the characteristics of the bond change from one day to the next. You have no idea what bond characteristics TRACE_Y weighed most heavily, but know it must be one or more of the fields presented in the attached files. Thankfully, you took Coursera classes on machine learning and think you might have what it takes to replicate her mind. You need to act fast – you have been given until July 31st to come up with an algorithm that can predict the nearest ISIN for several bonds. If you correctly predict the “nearest” bond (or even identify a bond in the top 10), you are confident that you will be able to continue to operate.

A slightly more serious explanation of the problem: We’ve taken several months of data on various bonds and created a secret algorithm that ranks bonds by their similarity. It is based on knowledge of characteristics of the bonds and somewhat resembles decisions made by true portfolio managers. However, this ground truth is artificial, intentionally made up to provide a positive Kaggle experience. So while some knowledge of bonds and their characteristics may help you, a deep knowledge of fixed income markets will not help. You are not predicting the true nearest bond (if you believe you know what that is), but the nearest bond as predicted by our algorithm, which remains secret.

Getting Started

You must join Microsoft Teams to stay up-to-date with the latest announcements for this competition.

Please ensure that you have joined the Teams channel (refer to welcome email from Steve Lawrence).

If located in Australia, where Teams has not been deployed yet in the Vanguard networks, make sure you sign up to the IMFS slack channel for this competition (refer to welcome email from Steve Lawrence).

You will be working out of Kaggle, a platform for data science related competitions, to build and run your recommendation models. Therefore, you must create a Kaggle account and share your Kaggle handle with us (via Teams or Slack).

While you will do all the work in Kaggle, we also provide the Github repository if you want to work on your own mahine, GitHub hosts the main repository for this competition with all materials you will be using in this challenge.

Please remember you can always work in Kaggle and you do not need to clone the github repository locally.

Your teammates



Your timeline

Week 0 (starting July 1st) – Setting Up/Onboarding + Meet your IMFS mentor
Week 1 (Starting July 8th) – Understand the challenge + Tutorial on exploring your dataset in your Kaggle Kernel
Week 2 (starting July 15th) – Tutorial on preprocessing dataset
Week 3 (starting July 22nd) – Tutorial on building classification models and tuning the parameters
Week 4 (Starting July 29th) – Tutorial on submitting your results for grading
Wednesday July 31st – Last date for submission of competition results
Friday August 2nd – Award ceremony and announcement of winning teams

The Dataset

One year of historical pricing and duration data for a portfolio of securities.

The Rules

Participation:

You will work in small teams of four to five people.
IMFS data scientist mentors will be hosting "competition office hours" where you can ask questions. The mentors will NOT do the work for you.
Your team will be assigned a mentor to help. She/he will check on you once a week to track on your progress
How to approach the problem
Here’s a brief rundown of what you need to do:

Join the competition on Microsoft Teams HERE. We are using Microsoft TEAMS as it is widely available at Vanguard (US and Malvern). For our participants in Australia, communicate via Slack using the IMFS slack channel for this competition (refer to Steve Lawrence’s welcome email). Please remember to submit your GitHub and Kaggle account handles.
Use the dataset provided to train your model. Your model must take as an input a ISIN and return the top 10 similar securities to the "ISIN" in the test set.
Follow along the tutorial in your assigned competition kernel in Kaggle. A Kaggle kernel is a cloud computational environment that enables reproducible and collaborative analysis. For this competition, the kernels are setup as Jupyter notebooks. Jupyter notebooks consist of a sequence of cells, where each cell is formatted in either Markdown (for writing text) or in a programming language of your choice (for writing code). For more details on kernels, read this article by Kaggle.
When you are ready to submit your work, run your model for each of the 1000 test securities in the ["test_set.csv" dataset].
At the end of your notebook, save your recommendations for each security, see the function generate_output below.
Post "Done with project - yourteamname" in the competition's "#Microsoft Teams" channel or the Slack channel if in Australia.
Ground of truth and grading
The ground truth consists of a set of bonds and their characteristics and labels for the ISIN of the nearest bond. Information on the characteristics of this nearest bond are provided in the training file. As mentioned in the backstory, this ground truth is artificially generated to provide for an interesting competition and may not reflect the truly optimal bond for a particular situation. A good algorithm will correctly predict the ISIN of the nearest bond as labelled in the training dataset.

We will grade your result in the following way: for each target ISIN in the test set, as long as your top 10 predictions contain the NearestISIN of the target ISIN, you successfully recommend it, otherwise you don't.

You will get perfect score if your recommendations match the model perfectly. Otherwise, will you will not get the score, so your score will be the number of NearestISIN you predict correct/1000.
The winning teams will be determined based on:
First Place (Performance based)
Best coded (as judged by Chuqi Yang)
Most innovative solution (As judged by IMFS team)
Most engaged (As judged by IMFS interns)
