# Introduction 
**Business Context.** Online peer-to-peer (P2P) lending has made the practice of borrowing and lending easy. In this form of lending, there is no in-person interview and a borrower can simply fill out an online form and get a loan approved. The information provided solely by a borrower is prone to exaggeration and distortion, especially when it comes to income. Every P2P lending company relies on a well-designed procedure that rejects borrowers with a high chance of not paying off their debts.

Rejecting anyone without a verified source of income is a relevant policy that lending platforms can roll out to help reduce the rate of bad loans. It is natural to suspect that if a person's income source cannot be verified, then they might default on the loan. However, from the perspective of a borrower, the verification process can be cumbersome and time-consuming and they may just switch to another platform due to this inconvenience. 

**Business Problem.** As a data scientist at an emerging P2P lending company, you must answer the following question: **"Should the company verify the income source of an online loan applicant before approving their loan?"**

**Analytical Context.** The data is downloaded from [LendingClub (LC) Statistics](https://www.lendingclub.com/info/download-data.action) and it contains all loans issued from 2007 - 2012 along with their current loan status (fully paid or charged off). There are ~50 variables that describe the borrowers and the loans; for the sake of reducing complexity, the company has already performed a pre-screening of these variables based on existing analyses from LendingClub to select nine relevant variables, such as annual income, LendingClub credit grade, home ownership, etc. We will use a **logistic regression**, to answer our question at hand.


 # Key Learnings
1. Performing EDA on a binary outcome using cross tables
2. Performing statstical tests to generate hypotheses
3. Codifying and testing these hypotheses with larger models using logistic regressions
4. Assessing classifier performance using AUC
