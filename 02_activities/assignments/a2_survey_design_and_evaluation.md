# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the 
need(s) outlined in the prompt.

Scenario 1:

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:

```
write your answer here...
The purpose of the survey is to understand the reason behind the high turnover rate of entry- and lower-level positions across the departments of a large tech company, and to identify workplace factors that strongly predict turnover among them. This is to inform the HR department on changes needed to improve employee satisfaction and retnention.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
write your answer here...
target population: all current employees in entry- and lower-level positions (level 1-4) at the company exluding management, contractors and interns, across all departments.
sampling frame: employees in entry- and lower-level positions who registered on the HR system with contact information (email)
sampling unit: employee
overall sampling strategy: stratified random sampling, with department as the stratum. A simple random sample is drawn from each stratum with proportional allocation to ensure the same weight of the samples from each stratum which will simplify analysis. Probability sampling is chosen over convenient sampling (e.g. first 500 returned survey) since non-response bias will be a major concern for this study. The survey will have anonymity guaranteed to maximize response within the probability sample. Reminder emails will be sent to improve response rate.
```

Your 5-10 question survey:
```
1. What department do you work in?
[Engineering/ Marketing/ Sales/ Customer Suuport/ Product/ Operations/ others (specify)]
2. What is your current job level?
[Level 1 (Entry)/ Level 2 (Junoir)/ Level 3 (mid-level)/ Level 4 (Senior)/ Other]
3. How long have you been in the company?
[less than 6 months/ 6-12 months/ 1-2 years/ 2-5 years/ more than 5 years]
4. Overall, how satisfied are you with your current role at the company?
[Very dissatisfied / Dissatisfied / Neutral / Satisfied / Very satisfied]
5. To what extend do you agree with the following statements?
[each statement uses the same scale: strongly disagree/ disagree/ neutral/ agree/ strongly agree]
    a. My compensation is fair for the work I do.
    b. My manager gives me clear, regular feedback.
    c. I have meaningful opportunities to grow my career here.
    d. I feel respected by people I work with day-to-day.
    e. My workload is manageable on a typical week.
    f. The company supports my mental health and well-being.
6. How likely are you to still be working at this company 12 months from now?
[Very unlikely / Unlikely / Neutral / Likely / Very likely]
7. Have you actively looked for a job outside of the company in the past 6 months?
[Yes/ No/ Prefer not to say]
8. If you were to leave the company, what would be the single most important reason?
[compensation/ manager or leadship/ work-life balance/ growth opportunities/ lack of challenge or interest/ better opportunity elsewhere/ other (specify)]
9. (Optional) What is the ONE change the company could make that would most improve your experience here? (open response, <100 words)
```

## Part B - Survey Evaluation:

Identify and describe survey features:
```
write your answer here
1. Sample type: 
Cross-sectional two-staged stratified probability sampling. Each stratum is a province/census metropolitan area (CMA). First stage: groups of telephone numbers tied to the same address are sampled; second stage: one eligible member (aged 15+) is randomly selected per household. 
The ten provinces are divided into 27 strata. Major  Census Metropolitan Areas (St. John's, Halifax, Saint John, Montreal,  Quebec City, Toronto, Ottawa, Hamilton, Winnipeg, Regina, Saskatoon, Calgary, Edmonton, Vancouver, Victoria) are each individual strata; remaining CMAs in Quebec, Ontario, and British Columbia are grouped  into three additional strata; non-CMA areas of each province form ten more strata.
A sub-design 'rejective sampling' was chosen as part of the sample design. After a respondent is classified as a volunteer or not, sub-sampling is carried out for selected respondents who are not volunteers. All respondents who are volunteers do a long interview. Those who are NOT volunteers are randomly divided into two groups. One group does a long interview, while the other group does a short interview.

2. Sample size: 
A field sample of approximatively 50,000 units was used. Among them, about 40,000 invitation letters to the electronic questionnaire were sent to selected households across Canada. A target completion of 24,000 questionnaires was expected. At the end, the resopnse rate was approximately 41.9%, equating to 16760 completed responses in the public-use microdata file.

3. Target population: 
The target population for the GSS Giving, volunteering and participating includes all persons 15 years of age and older living in the ten provinces of Canada. It excludes residents of Yukon, Northwest Territories, and Nunavut and full-time (residing for more than six months) residents of institutions.

4. Sampling frame: 
A combined frame that integrates landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada's dwelling frame. Frame records are groups of one or several telephone numbers associated with the same address (or a single number when an address could not be linked).

5. Survey mode(s): 
All respondents in the ten provinces were interviewed by telephone or self-completed an electronic questionnaire.

6. Timeline: 
Data collection period: 2018-09-04 to 2018-12-28, once every 5 years; Reference period: Past 12 months preceding interview date.

7. Response rate: 
41.9%

8. Weights: 
WGHT_PER: This is the basic weighting factor for analysis at the person level, adjusted by rejective sampling, non-response (household & individual level), and coverage error.
Bootstrap weights are used for design-based variance estimation.

9. Data processing
Processing used Statistics Canada's Social Survey Processing Environment (SSPE), a generalized set of utilities for cleaning and transforming survey data.
10. Cleaning, imputation, etc
Almost all imputations were made using donor records selected through a score function.
Imputation was carried out in nine sequential steps:
   1. Personal income and family income
   2-4. Formal volunteering variables (master file)
   5-6. Informal volunteering variables (master file)
   7-9. Donation variables and solicitation methods

11. Sources of error
Sampling error — quantified via the bootstrap method using the 500 bootstrap weights; all reported differences in StatsCan publications are significant at the 95% confidence level.
Non-sampling errors:
  - Coverage error: households without telephone service, and those 
    with telephone services not covered by the integrated frame, are 
    excluded from the surveyed population. The bias from this 
    exclusion is expected to be small but not zero.
  - Nonresponse error: at two levels — household-level (no one in the 
    selected household replied) and individual-level (the selected 
    person did not complete the questionnaire). The 41.9% response 
    rate makes nonresponse the primary non-sampling error concern.
  - Response errors: respondents may misreport behaviors due to 
    recall difficulty (the survey asks about activities over the past 
    12 months) and social desirability bias (volunteering and 
    donating are socially valued, potentially inflating reports).
  - Processing errors: minimized by the SSPE workflow and head 
    office editing, but not eliminated.

12. Limitations, known biases, etc
Coverage gaps: the territories (Yukon, NWT, Nunavut), full-time institutional residents, and households without telephone service are excluded by design, biasing estimates away from rural, northern, elderly-institutionalized, and low-income populations.

Response-side biases: the 41.9% response rate creates substantial nonresponse risk (only partially corrected by admin-data-driven weight adjustments); 12-month recall of donations and volunteer hours introduces imprecision; and because giving/volunteering are socially valued behaviors, social desirability bias may inflate reported rates.

Design constraints: the cross-sectional design prevents tracking individual change over time; the 2018 shift to predominantly online self-completion may produce mode effects that complicate trend comparisons with earlier CATI-only cycles; and the rejective sub-sampling design means non-volunteers on the short-interview path have less detailed data, limiting some sub-analyses.

13. Link to documentation and any additional sources used
- Survey methodology page (full technical detail): https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
- Variable list for Cycle 33: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvVariableList&Id=796234

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
