# IMFS Data Science Competition - Summer 2019
### Last update: May 1st 2019

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
How to build a recommendation system of similar bonds within the trading universe of an investment portfolio or fund?  How to predict potentially rich and cheap bonds within a portfolio?

A portfolio manager (PM) manages multiple securities within a fund. Sometimes, she is not able to purchase all bonds in her trading universe. Otherwise, her preferred bonds may not be available.  In this project, the goal is to provide the PM with a toolkit to find similar bonds to the ones she originally wanted, as well as a list of bonds most likely to be rich or cheap. A bond is considered rich when it is trading at a price higher than its peers, or higher than historical norms.

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

   2. Review git commands. [Here](https://github.com/joshnh/Git-Commands) is a good refresher.

   3. Clone this repository locally

   4. Create a git branch where you will work on your own

   5. Use the dataset provided to train your model (good practice to split your dataset into training, testing and validation samples). Your model must take as an input a desired security "Security_desired" and return the following:
      1. In descending order, the top 10 similar securities to the "Security_desired", ranked in descending order from best to worst similarity
      2. A column that determines how cheap or rich each of the 10 recommended security is, against itself.
      3. A column that ranks, in descending order, the 10 recommended securities from richest to cheapest.
      4. See an example of expected output "***securityRecommendation.csv***"

   6. When you are ready to submit your work, run your model for each of the five test securities in the ["***testSecurities.csv***" dataset](../master/submissions/testSecurities.csv). Save the outputs for each recommendation per the template ["***securityRecommendation.csv***"](../master/templates/securityRecommendation.csv). Each recommendation should be saved as "***securityISIN_Recommendation.csv***" under your [team folder](../master/submissions). For example, your recommendation for security "US00037BAD47" would be saved as "US00037BAD47_Recommendation.csv"

   7. Submit your submission under your team's folder [here](../master/submissions).

   8. Confirm your submissions are present in the "submission" folder in the main repository by the deadline

   9. Post "Done with project - yourteamname" in the "**#ext-ds-competition**" Slack channel

3. Ground of truth and grading
IMFS holds a model built with the same data, in collaboration with the Spring 2019 cohort from the Columbia Data Science Institute. This model is used as ground of truth.
   1. You will get perfect score if your recommendations match the Columbia model perfectly. Otherwise, points will de deduced for each incorrect match.

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
