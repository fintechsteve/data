# IMFS Data Science Competition - Summer 2019
### Last update: July 1st 2019

## Welcome!
The Office of Investment Management Fintech Strategies (IMFS) is excited to announce the kick-off of our second annual data science collaborative and friendly competition. This collaborative effort brings together crew from across IMG and IMS that have an interest in learning about data science and getting some hands on experience. Beginning in late July, all interested crew members will be split up into teams to participate in a Data Science competition. The IMFS data science team has lined up an interesting problem to tackle and we hope that as many people that are interested in can join us.

## Overall Objective
Learn hands-on to solve a business problem using python and data science techniques. We are here to help you but you will get the most out of this competition by doing the work yourself.

## Timeline and Deadlines
* Monday June 24th 2019 - Registration email sent to IMG with a registration link + survey
* **DEADLINE** --> Wednesday July 3rd 2019 - Last day to register
* Monday July 8th - Welcome email + team and mentor identification
* Wednesday July 10th 2019 - Competition kicks off - Welcome webinar in Zoom (link). Video recording available [here](../master/recordings).
* **DEADLINE** --> Friday August 2nd 2019 - Last day to submit results
* Wednesday August 7th 2019 - Winning team announced, template presentation deck shared with winning team so they can prepare their slides for Demo Day
* **DEMO DAY** --> Wednesday August 14th 2019 - IMFS Open House : Winning team presents on their results then one IMFS mentor demoes the Recommender app (ground-of-truth) built with Columbia Data Science students.

## Time Commitment
Four hours a week, for four weeks (from July 8th to August 7th) + one hour during demo day.
If a winner, one or two additional hour(s) to prepare slides and demo on August 14th 2018.

## What (The Challenge)
How to build a recommendation system of similar bonds within the trading universe of an investment portfolio or fund? 

--Need Steve to complement the story--

A portfolio manager (PM) manages multiple securities within a fund. Sometimes, she is not able to purchase all bonds in her trading universe. Otherwise, her preferred bonds may not be available. In this project, the goal is to provide the PM with a toolkit to find similar bonds to the ones she originally wanted in the same day. In this challenge, you are to asked to predict top 10 similar bonds for each target bond in the test set in the same day; as long as the top 10 similar bonds contain the NearestISIN of the target, you successfully predict correct for this target. 

### The inspiration behind this challenge: Viktoriya Bondarenko and [this](../master/templates/JPM_ Identifying Rich Cheap bonds with Big Data.pdf) paper by JPM.

## The Data
One year of historical pricing and duration data for a portfolio of one thousand securities available [here](../master/dataset).
The data is proprietary to Vanguard so you must NOT share it publicly (outside of Vanguard networks).

## The Rules
1. **Participation**:
   1. You will work in small teams of two or three people max.
   2. IMFS data scientist mentors (DSMs) will be hosting "competition office hours" twice a week, where you can ask questions. The DSMs will NOT do the work for you.
   3. Your team will be assigned a DSM to help. She/he will check on you once a week to track your progress

2. **How to approach the problem**
Here’s a brief rundown of what you need to do:
   1. Join the competition on Slack at "**#ext-ds-competition**". You will receive an invitation to the competition's slack channel. Please say hello to confirm your participation.

   2. Run code in Kaggle Kernel(recommended way) or clone this repository locally and create a git branch where you will work on your own

   3. Use the dataset provided to train your model (good practice to split your dataset into training, testing and validation samples). Your model must take as an input a desired security "ISIN" and return the top 10 similar bonds of this bond.

   4. Save the result file in the format "Team_X.csv"(X represents team number) in Kaggle Kernel.

   5. Confirm your submissions are present in the "submission" folder in the main repository by the deadline

3. Ground of truth and grading
IMFS holds a model built with the same data, in collaboration with the Spring 2019 cohort from the Columbia Data Science Institute. This model is used as ground of truth.
   1. You will get perfect score if your recommendation contain the NearestISIN for each ISIN in 'test_set.pkl'. Otherwise, points will de deduced for each incorrect match.

   2. The winning team (with highest score) will be presented with a trophy and free Galley lunch passes. In case of a tie, we will provide an additional test set to determine a winner.

## Participants (Arranged in teams)
INSERT TABLE HERE

## Help Desk
### IMFS Data Science Blog for tips and tutorials
Access blog [HERE](http://vgimfs.com/blog)

### Mentorship
* Zoom link for all office hours: **LINK**
* Mentors (DSMs):
1. **YUHAN (FLORA) HUANG**
   1. LinkedIN: Connect HERE
   2. Office hours:
      1. Week 1:
      2. Week 2:
      3. Week 3:
      4. Week 4:
   3. Mentoring following team(s): xxx an yyy

2. **YUQIN (ALEXA) DAI**
   1. LinkedIN: Connect HERE
   2. Office hours:
      1. Week 1:
      2. Week 2:
      3. Week 3:
      4. Week 4:
   3. Mentoring following team(s): xxx an yyy

3. **MATTHEW VITHA**
   1. LinkedIN: Connect HERE
   2. Office hours:
      1. Week 1:
      2. Week 2:
      3. Week 3:
      4. Week 4:
   3. Mentoring following team(s): xxx an yyy### FAQs

4. **CHRISTOPHER H. STOCK**
   1. LinkedIN: Connect HERE
   2. Office hours:
      1. Week 1:
      2. Week 2:
      3. Week 3:
      4. Week 4:
   3. Mentoring following team(s): xxx an yyy

5. **SHADI FADEE**
   1. LinkedIN: Connect HERE
   2. Office hours:
      1. Week 1:
      2. Week 2:
      3. Week 3:
      4. Week 4:
   3. Mentoring following team(s): xxx an yyy

6. **SHIYU (SHERRY) LI**
   1. LinkedIN: Connect HERE
   2. Office hours:
      1. Week 1:
      2. Week 2:
      3. Week 3:
      4. Week 4:
   3. Mentoring following team(s): xxx an yyy

### FAQs
1.
