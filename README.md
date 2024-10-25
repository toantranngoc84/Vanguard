<<<<<<< HEAD
# Project 2

## Technologies:


## Context:
You are a newly employed data analyst in the Customer Experience (CX) team at Vanguard, the US-based investment management company. You’ve been thrown straight into the deep end with your first task. Before your arrival, the team launched an exciting digital experiment, and now, they’re eagerly waiting to uncover the results and need your help!

## The Digital Challenge:
The digital world is evolving, and so are Vanguard’s clients. Vanguard believed that a more intuitive and modern User Interface (UI), coupled with timely in-context prompts (cues, messages, hints, or instructions provided to users directly within the context of their current task or action), could make the online process smoother for clients. The critical question was: Would these changes encourage more clients to complete the process?

## The Experiment Conducted:
An A/B test was set into motion from 3/15/2017 to 6/20/2017 by the team.
Control Group: Clients interacted with Vanguard’s traditional online process.
Test Group: Clients experienced the new, spruced-up digital interface.
Both groups navigated through an identical process sequence: an initial page, three subsequent steps, and finally, a confirmation page signaling process completion.
The goal is to see if the new design leads to a better user experience and higher process completion rates.

## Roadmap:
00 Vanguard
01 Problem Statement
02 Data Overview
03 Exploratory Data Analysis
04 KPI / Hypothesis
05 Analysis
06 Summary
07 Conclusion / Recommendation
=======
# Vanguard A/B Testing 

## Context
Welcome to the Customer Experience (CX) team's project at Vanguard, the US-based investment management company. As a newly employed data analyst, I have been tasked with analyzing the results of a recent digital experiment. The team has launched a modern User Interface (UI) with timely in-context prompts to enhance the online process for clients. Our critical question is: *Will these changes encourage more clients to complete the online process?*

## The Digital Challenge
The digital landscape is continuously evolving, along with the expectations of Vanguard’s clients. We hypothesize that an intuitive and modern UI, combined with helpful prompts, will improve user experience and increase the completion rates of online processes.

## A/B Testing Overview
A/B testing, or split testing, is a method of comparing two versions of content (A and B) to identify which performs better in terms of specific objectives such as conversion rates and user engagement.

### Why A/B Testing is Important
- **Data-Driven Decisions:** Enables businesses to make informed choices based on real data.
- **Optimizing User Experience:** Helps to understand user preferences and enhance their experience.
- **Improving Conversions:** Allows optimization of pages or processes to drive desired actions, such as purchases or sign-ups.

## Dataset
The analysis utilizes three key datasets available at the following links:

1. **Client Profiles:** [Client Profiles Dataset](https://github.com/data-bootcamp-v4/lessons/tree/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_demo.csv) - Contains demographics such as age, gender, and account details.
2. **Digital Footprints:** [Digital Footprints Dataset](https://github.com/data-bootcamp-v4/lessons/tree/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_web_data.csv) - A detailed trace of client interactions online, split into two parts (pt_1 and pt_2). Merging these files is recommended for comprehensive analysis.
3. **Experiment Roster:** [Experiment Roster Dataset](https://github.com/data-bootcamp-v4/lessons/tree/main/5_6_eda_inf_stats_tableau/project/files_for_project/df_final_experiment_clients.csv) - Identifies which clients participated in the experiment.

## Steps for Analysis

1. **Exploratory Data Analysis (EDA) & Data Cleaning**
   - Conduct dataset exploration to prepare for analysis.

2. **Client Behavior Analysis**
   - Analyze who the primary clients using this online process are (age, new vs. long-standing clients).

3. **Performance Metrics**
   - Define success indicators such as:
     - **Completion Rate:** Proportion of users reaching the final ‘confirm’ step.
     - **Time Spent on Each Step:** Average duration users spend on each step.
     - **Error Rates:** Frequency of users returning to previous steps, indicating confusion.
     - **Redesign Outcome:** Compare the performance of the new design against the old one.

4. **Data Visualization with Tableau**
   - Visualize results to highlight key findings.
   

## Metadata
The following fields will guide the analysis:

- `client_id`: Unique ID for each client.
- `variation`: Indicates if a client was part of the experiment.
- `visitor_id`: Unique ID for each client-device combination.
- `visit_id`: Unique ID for each web visit/session.
- `process_step`: Marks each step in the digital process.
- `date_time`: Timestamp of each web activity.
- `clnt_tenure_yr`: Tenure with Vanguard in years.
- `clnt_tenure_mnth`: Tenure with Vanguard in months.
- `clnt_age`: Age of the client.
- `gendr`: Gender of the client.
- `num_accts`: Number of accounts held by the client.
- `bal`: Total balance across all accounts.
- `calls_6_mnth`: Number of times the client called in the past six months.
- `logons_6_mnth`: Frequency of logins to Vanguard’s platform in the last six months.

## Client Behavior Analysis
### Interaction Patterns
- Compare navigation between the old and new digital processes to identify patterns and divergence points.
- Investigate the number of actions (steps) taken by users between the Test and Control groups.

### Statistical Analysis
- Calculate effect sizes and post-hoc power for tests conducted on completion rates, error rates, time spent, and visit rates, using Z-tests and T-tests as appropriate.

### KPI/Hypothesis Results
- **Completion Rate:** New UI led to a 5% increase; Hypothesis rejected.
- **Error Rate:** Remained almost the same; Hypothesis rejected.
- **Time Rate:** No significant change; Hypothesis rejected.
- **Visit Rate:** Nearly identical between UIs; Hypothesis rejected.

## Installation Instructions

1. **Clone the Repository**
   To clone the repository to your local machine, run the following command:
   ```bash
   git clone https://github.com/toantranngoc84/Vanguard.git
   
   
2. **Navigate into the project directory:**
   ```bash
   cd Vanguard
   
3. **Install the required dependencies: Install the dependencies listed in the requirements.txt file:**:
   ```bash
   pip install -r requirements.txt
   
4. **Run the Jupyter Notebook: After installing the dependencies, open the Jupyter notebook by running:**:
   ```bash
   jupyter notebook Vanguard.ipynb
   
5. **Clone the repository**:
   ```bash
   git clone https://github.com/toantranngoc84/Vanguard.git
   
>>>>>>> 3f5975c4 (update README)
