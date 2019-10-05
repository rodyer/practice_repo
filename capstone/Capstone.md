# Proposal Template

## Business Problem

Describe your project, what business will it support?  What is problem you are trying to solve?  What has been the existing work to try to solve this problem?

- Business supported: Frontier
- Problem to solve: To identify ways to customize the return visitor experience in order to drive the user to convert on an earlier visit. 
- Description: ~30% of overall visits on Frontier are coming from return visitors, with these return visitors converting the highest on their 3rd-5th visit to Frontier. Additionally, we know return visitors (agnostic of the visit return count) convert 83% higher and engage 28% higher than a new visitor to the site. 
- Existing Work: Verizon tested changing a headline and content on the landing page to recognize the user has visited before (E.g. "Welcome back!" header) and saw a +6% increase to Total VC. HughesNet tested something similar and saw large gains, but tested more than just the return visior changes, so results are hard to attribute to return visitor changes only. Frontier will be testing a modal to pop upon landing to expedite the user's buyflow. 

## Data

What data will be required to solve this problem?  What types of features will be available to you?  What databases, tables contain the data you are concerned about?  Are there experts at RV that can help to describe the data you are concerned about?

- Data required: Visit count on conversion, marketing channel (PS, SEO, etc.) and on what visit (meaning do these start on SEO and come back through PS), market (copper/fiber), device (experiences are often very different),  VRC options, previous engagement option (do they switch purchase method), serviceable results by visit, and last page seen before leaving the site.

- Tables with data: frontier.v_websessionfct, frontier.v_cartsessionfct

- Concerns: It might be tricky to assign each of the features to a specific visit for the user, but I can work with Tab/Matt/Mike on the data ops team to make sure I am pulling the data correctly to gain confidence in the data. As for data experts on the business, I have been on FTR for over a year and feel confident on where to find the data needed to complete this exercise.


## Approach

How to do you plan to collect the data?  How will you visualize the information?  What will you be looking for?  

- Collection Plan: I plan to look at data for the past year. 
- Visualization | What to look for: I will be looking for common trends of users who return and over time (customer pathing of those that convert on an earlier visit). Additionally for features that stick out as an opportunity to customize the user experience. 

## Deliverables

What are your intended deliverables?  Who is your intended audience?  What action to you expect them to take?
- Intended audience is my business team and we hope as a team to be able to find new ways to customize the experience from this analysis. We plan to focus a lot of our attention on return visitors in Q4 and our hope is we find new information from this analysis to act on in the coming weeks. 

*All projects should include a Jupyter notebook, 1-2 page final paper, 5 slide deck, and 5 minute presentation. NO MORE THAN ANY OF THIS!*

## Impact and Evaluation

How will you know if your project is successful or not?  What metrics or change in behavior might you use to evaluate your impact?
- I will know this project is successful if we are able to decrease the return visitor count on the Frontier business. 
