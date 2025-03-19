# EXPERIMENTATION REPORTING DOCUMENT<br/> INFORMATION ARCHITECTURE



## Purpose
The purpose of this document is to outline a proposed information architecture to assist with the accurate and detailed documentation of experimentation planning, design, deployment, analysis and decision-making. 

The document aims to highlight key focus areas for experiment design, execution and reporting that need to be addressed to facilitate a high-performance experimentation program, and perform repeatable, reliable and trustworthy experiments.

Data and insights from each detailed master experimentation report can be carved out for organisation communications, reporting, stakeholder presentations etc.

The experimentation reporting document is a live document, evolving and updated during the course of the experiment lifecycle.

Use this document as template to ensure that experiments are conducted in a systemmatic and structured manner.



## Why documenting experiments is important
Documenting your experiments is important for a number of reasons:

* Ensures a consistent and standardised approach to conducting all experiments in an organisation
* Provides a common language and terminology around experimentation
* There is an audit trail and traceability for all experiments
* Drives experimentation process efficiencies across the organisation - individual teams not creating cottage industries
* Experimentation documentation can be easily stored and shared across the organisation
* Engenders strong alignment around experiment hypothesis - hypothesis setting is a team sport
* All experiment metrics are declared and documented upfront
* Avoids mistakes during test Design and QA (and a need to re-run tests) - reduces the likelihood of human error
* Clear direction for post-experimentation analysis
* An educational tool to help teams understand all the components required to conduct a high-quality experiment



## Overview
The document outlines key considerations for the following focus areas:

1.	Experiment summary
2.	Experiment overview
3.	Experiment owners
4.	Research & evidence
5.	Learning objectives
6.	Hypothesis
7.	Metrics
8.	Statistical planning
9.	Experiment design
10.	Quality assurance
11.	Data analysis & results
12.	Key learnings & next actions



## 1. Experiment summary
A one-pager summary that provides a snapshot of key inputs into experiment design, outcomes and next steps.

Including:
* Customer research
* Problem identified
* Hypothesis
* Test outcomes
* Recommendation
* Images of test design (Control & Treatment)



## 2. Experiment overview
A high-level overview of the experiment.

* Experiment ID
* Test creation date
* Title - state the What, not the How (I.e., Improve CTR From Search Results)
* Description of test concept
* Behavioural heuristic - Clarity, Usability etc.
* Growth area - Retention, Acquisition etc.
* Audience - All visitors, Spain, Hosts, Drivers etc.
* Prioritisation ratings - ICE, PIE, something else etc.
* Opportunity size - what is the estimated business opportunity if the solution is successful?
* Test location - Checkout, Homepage, Landing Page etc.
* Components - Form, Image, Value Proposition etc.
* Metric - target primary metric
* Risk - Low, Medium, High
* Platform - Web, Mobile Android, Mobile iOS etc.
* Estimated test time - days / weeks
* Estimated design time - hours / days
* Estimated build time - hours / days
* Status - Idea, Build, Running etc.
* Test completion date
* Test outcome - Positive, Inconclusive, Negative



## 3. Experiment owners
Outline the key stakeholders involved in designing and executing the experiment. 

Experiment Owner:
* Experimentation
* Product
* Growth
* Marketing etc.

Experiment owners are responsible for end-to-end experiment lifecycle management, including sign-off, starting, stopping, monitoring and acting on any alerts.

Key stakeholders:
* Design / UX / UI
* Data Science
* Analytics
* Developers
* Engineering
* Research & Insights
* Legal etc. etc.



## 4. Research & evidence
Provide an overview of the key insights and customer research that have fed into the experiment.

* Summarise the key Qualitative and Quantitative insights that have informed the hypothesis
* External research
* Competitor intelligence
* Research sources – links to research / data sources
* Past results – are there any priors that inform the experiment (link: analysis, experiment results, research)
* Problem statement – This is a [_problem or opportunity_] because [_assumptions about value_]
* Proposed solution – We believe that [_description of testable solution_]
* Strategic business goals – how does this opportunity link to business strategy, goals and objectives

Checkpoint: Do we need to test this opportunity with an experiment? If no, what other forms of evidence can inform a path forward for decision-making.



## 5. Hypothesis
Define and declare your hypothesis upfront – the hypothesis should be precise, testable and falsifiable.


* Hypothesis - BASED ON [_research insight_], WE BELIEVE THAT [_change X_], WILL CAUSE [_impact Y_]

* Prediction – If we [_proposed change_] to [_independent variable/s_], then [_expected impact_] on [_dependent variable/s_]



## 6. Learning objectives
What do you hope to learn from performing the experiment? What are your learning objectives?

* We want to understand how reframing the Value Proposition on the homepage will impact lead generation
* We want to understand which customer segments find the incentive scheme most compelling
* We want to understand how adding a new pricing tier impacts conversions to existing plans for new users

Think about the following:
* Impacts to customer experience
* Impacts to business performance
* Unintended consequences or downstream/upstream impacts
* How learnings will inform your future work



## 7. Metrics
Declare and register the key metrics that you will measure for the experiment across the key metrics categories.

Metric categories:
* Primary (# of hours viewed)
* Secondary (# of previews watched)
* Guardrail (# of subscriber cancellations)
* Data quality (data loss)

Pre-register your decision criteria prior to performing the experiment to yield higher quality decisions, faster decisions and to save time on data analysis.

If [_insert change_] improves [_insert key metric_] and has positive or null effects on [_all other metric categories_] then [_release the change to 100% of users_].



## 8. Statistical planning
Outline and document the key statistical parameters that inform experiment design and execution.

|             Category             |          Example             |
|              :---                |           :---:              |
| Metric baseline                  | 15%                          |
| Minimal Detectable Effect (MDE)  | 5%                           |
| Statistcal Power                 | 80%                          |
| Significance Level               | 5%                           |
| Required sample size             | 8,376 per variant            |
| Target runtime                   | 3 weeks                      |
| Standard business cycle          | 1 week                       |


* Baseline traffic volumes on target pages to ascertain if there is a sufficient volume of traffic to warrant performing an A/B test in the first instance. Ideally, this analysis will be conducted prior to commencing detailed experiment design to avoid wasted time and effort.



## 9. Experiment design
Define and document all the parameters for design and execution of the experiment.


For example:
* Audience – target audience / cohorts / allocations
* Audience size - how big are the cohorts
* Eligibility criteria – New user, Returning user, Language etc.
* Platform – web or mobile etc.
* Device – Android or iOS etc.
* Geo-targeting – Country, State, Location etc.
* Duration – the test will run for X Days / X Weeks from DD/MM/YYYY to DD/MM/YYYY (to detect a smaller lift will require a longer runtime)
* Experiment dates – Start Date / Finish Date
* Start rules – Anytime / After test X ends
* Stop rules – Fixed duration / Fixed sample / Sequential
* Experiment type – A/B Test, Multivariate Test, A/A Test etc.
* Replication – is the test a replication run?
* Test type – Superiority / Inferiority 
* Traffic split – 50/50
* Unit of randomisation (E.g., User ID, Device ID, Email recipient)
* Assignment criteria - what point a User/Device is bucketed into a Control/Treatment group
* Metrics -  existing metrics / build new metrics
* Experiment design – wireframes / designs / copy (footnote and link to relevant materials)
* Variants – Control / Variant description
* Interaction check – does the test interact with any other Planned / In-Flight tests?
* Risks - identify and mitigate risks (could the experiment have adverse effects we're not measuring?)



## 10. Quality assurance
This Quality Assurance (QA) testing plan outlines the process to ensure accurate and reliable deployment of an experiment. The goal is to validate experiment setup, mitigate risks, and ensure a seamless user experience while maintaining data integrity. Experiment QA will vary between organisations and the number of resources availalbe for QA activities.

### _Experiment setup_
* Check audience targeting
* Check experiment duration settings
* Check traffic split (50/50)
* Check that feature flagging is correctly implemented (if applicable)
* Check traffic allocation to Control & Variant groups – correct randomisation and user assignment

### _Functional testing_
* Check all variants for design and functionality
* Code changes tested for correctness
* Test experiment for required user states (New user, Logged in user)
* Check cross-browser
* Check cross-device

### _Performance testing_
* Measure page load speeds for variants – identify any latencies
* Check for excessive network / API calls

### _Data & analytics validation_
* Metrics are available and can be collected
* Event tracking is correctly setup for Control and Variants
* Validate data flows into analytics tools – metrics are firing correctly

### _Security & compliance_
* Verify compliance with privacy and data regulations

### _Issue tracking & resolution_
* Log and track all identified issues and bugs
* Implement fixes and retest before full deployment

### _Sign-off & approvals_
* QA team signs-off on test results
* Experiment owner approves deployment of the test

### _Deployment strategy & rollout_
* Gradual rollout – 10%, 50%, 100% (progressive ramp up)
* Monitoring and alerting criteria defined
* Monitor key metrics and user engagement to identify any anomalies
* Have a contingency plan to Rollback / Stop the test (if required)



## 11. Data analysis & results
Conduct post-hoc analysis of relevant experiment data and results to understand key learnings and insights from the test.

Compute:
* Data quality metrics
* Statistical markers – Power, Significance
* Sample Ratio Mismatch (SRM)
* Evaluation and analysis of experiment Metrics set – Primary, Secondary, Guardrail
* Deep-dive Segmentation analysis to detect heterogeneous effects
* Outliers and skewed data are identified and addressed (if required)



* Visualisation of results - Include relevant screenshots, graphs and tables from post-experiment analysis.

Key questions:
1. What changes were observed across the metrics set?
2. What is your interpretation of the results?
3. Were there any issues encountered that may have impacted the experimentation results?
4. Were there any unintended consequences of performing this experiment? (Upstream or downstream)
5. If the Null Hypothesis was accepted, what data do you have to support this claim?
6. If the Null Hypothesis was rejected, and you accepted the Alternate Hypothesis, what data do you have to support this claim?



## 12. Key learnings & next actions
Summarise the learnings and insights from the experiment, outlining key decisions and next business actions.

We learned that:
* What was our hypothesis?
* What was the experiment that we performed?
* What did we think was going to happen?
* What actually happened?
* Why do we think this happened?
* Who shares a different perspective? Why?
* What are our key learnings?
* How does our hypothesis need to be refined and adjusted?

Based on the experiment results, the next actions that we will take are:
* How will we apply the learnings from the experiment?
* Does the experiment need to be replicated?
* What additional experiments are required? How will we iterate? 
* How is our strategy impacted?
* What decisions are required?
* Why are our decisions correct?



Insights and learnings from the experiment are stored in a centralised knowledge repository and shared with key stakeholders.



## Referenced
[Make Decisions Before Experimenting](https://www.geteppo.com/blog/make-decisions-before-experimenting)<br/>
[Three Key Checklists And Remedies For Trustworthy Analysis of Online Controlled Experiments at Scale](https://exp-platform.com/Documents/2019%20FabijanDmitrievOlssonBoschVermeerLewis_Three-Key-Checklists_ICSE_SEIP.pdf)<br/>
[Design For Impact: Your Guide to Designing Effective Product Experiments](https://erindoesthings.com/design-for-impact/)<br/>
[The Better Experiment Checklist](https://docs.google.com/document/d/1pBosyUXOXu4xB4jRQhjt14KSvOhzneYnLGArxQYodjE/edit?tab=t.0#heading=h.qfq157e10f87)<br/>



## Contributors
Gavin Bryant












