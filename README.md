# DATSC101: Introduction to Data Science
Welcome to *Data Science 101*. Consider this the homepage for the course; all of the course content can be found here. Below you will find administrative information, all of which can also be found in the formal [course outline]([https://outline.uwaterloo.ca/](https://outline.uwaterloo.ca/viewer/view/nn8472)). The many folders in this repository also contain the materials you'll need for lectures, tutorials, assignments, and more.

## Course Information ℹ️
**Lectures:** Tuesdays and Thursdays, 11:30AM - 12:50PM in [RCH](https://uwaterloo.ca/accessibility/getting-around/building-accessibility/jr-coutts-engineering-lecture-hall-rch) 112\
**Tutorials:** Fridays, 9:30AM - 10:30AM in [MC](https://uwaterloo.ca/accessibility/getting-around/building-accessibility/mathematics-and-computer-mc) 2054\
**Office Hours:** Wednesdays, 9:00AM - 11:00AM in [M3](https://uwaterloo.ca/accessibility/getting-around/building-accessibility/mathematics-3-m3) 3143\
**Instructor:** [Nathaniel Stevens](https://uwaterloo.ca/statistics-and-actuarial-science/profile/nstevens) (he/him/his)\
**Email:** <nstevens@uwaterloo.ca>

## Course Description 📋 
This introductory data science course provides a comprehensive foundation in statistical reasoning, computational thinking, and mathematical modelling as it relates to data-driven decision-making. Students will learn to acquire, manage, analyze, and interpret diverse types of data using modern programming tools. Through hands-on projects involving real-world datasets from a variety of domains, students will develop skills in data wrangling, visualization, pattern discovery, and predictive modelling. Emphasis is placed on reproducible workflows, ethical considerations like privacy, and effective communication of data-driven insights. Designed for beginners, the course equips students to address complex, modern problems using the tools and concepts of data science.

## Course Learning Outcomes 📝
By the end of this course, students will be able to:

*Knowledge & Understanding*
1. Explain what data science is and describe its role across disciplines.
2. Differentiate between types of data (categorical, numerical, structured, unstructured).
3. Describe the data science workflow: formulating questions, collecting, cleaning, analyzing, modeling, and communicating results.
4. Understand basic concepts of probability and statistics (randomness, distributions, sampling, confidence intervals, hypothesis testing).
5. Recognize common ethical issues in data science, including bias, privacy, and fairness.

*Practical Skills*

6. Obtain, clean, and prepare real-world datasets using basic programming tools.
7. Summarize data using descriptive statistics and exploratory data analysis techniques.
8. Create clear and effective data visualizations that highlight patterns and communicate insights accurately.
9. Apply simple statistical/ mathematical/ machine learning models and interpret their outputs.
10.	Evaluate model adequacy and performance using metrics such as goodness of fit and predictive accuracy.
11.	Use computational tools for reproducibility.
12.	Communicate data-driven insights through written reports, visualizations, and oral presentations.

*Attitudes & Professional Skills*

13.	Develop critical thinking about data sources, quality, and limitations.
14.	Recognize the importance of ethical and responsible data practices in professional and societal contexts.
15.	Collaborate effectively in teams on data analysis projects.
16.	Gain confidence working with data despite not having prior coding or statistics background.

## Course Topics and (Tentative) Schedule 🗓️

Course content will be delivered via two in-person lectures (Tuesdays and Thursdays) and one in-person tutorial (Fridays) each week. Lectures and tutorials will consist of me (Nathaniel) teaching via a combination of slides, jupyter notebooks, and other media. You (the students) are expected to actively engage with this, especially in the tutorials which will have dedicated activities where participation is required.

The table below lists the topics we'll be covering each lecture. The topics are set, but the schedule is tentative; we may progress slower (or faster) than originally planned. All relevant lecture and tutorial materials for a given week will be posted on both [LEARN](https://learn.uwaterloo.ca/) and here on Github by the Monday of that week.

<div align="center">
   
|  | Tuesday | Thursday | Friday |
|------|-------|----------|--------|
| **Week 1**<br>Sept 7 - Sept 11 | No Lecture| Introduction   | Tutorial 1  |
| **Week 2**<br>Sept 14 - Sept 18 | PPDAC & Data Science Workflow  | Exploratory Data Analysis | Tutorial 2  |
| **Week 3**<br>Sept 21 - Sept 25 | Exploratory Data Analysis | Exploratory Data Analysis | Tutorial 3   |
| **Week 4**<br>Sept 28 - Oct 2  | Data Visualization | Data Visualization | Tutorial 4  |
| **Week 5**<br>Oct 5 - Oct 9   | Data Visualization   | Bonus  | Test 1 |
| **Reading Week**<br>Oct 12 - Oct 16  | No Lecture     | No Lecture  | No Tutorial |
| **Week 6**<br>Oct 19 - Oct 23 | Estimation & Inference | Estimation & Inference  | Tutorial 5|   
| **Week 7**<br>Oct 26 - Oct 30  | Randomness & Probability  | Randomness & Probability   | Tutorial 6  |
| **Week 8**<br>Nov 2 - Nov 6   | Confidence Intervals   | Confidence Intervals  | Tutorial 7  |
| **Week 9**<br>Nov 9 - Nov 13   | Hypothesis Testing  | Hypothesis Testing     | Test   2                |
| **Week 10**<br>Nov 16 - Nov 20  | Predictive Modeling: Numerical Prediction | Simple Linear Regression  | Tutorial 8   |
| **Week 11**<br>Nov 23 - Nov 27  | Predictive Modeling: Classification      | Simple Logistic Regression   | Tutorial 9  |
| **Week 12**<br>Nov 30 - Dec 4  | Cross Validation    | Unsupervised Learning   | Tutorial 10  |
| **Week 13**<br>Dec 7 - Dec 11  | Data & AI Ethics | No Lecture | No Tutorial |                                                                    

</div>
   
## Textbook 📚
There is no formal textbook assigned for this course; you'll be able to get by using the provided lecture and tutorial material. That said, when creating this content, I drew on material from several sources, the primary ones listed below. Most of these are not textbooks in the traditional sense; all of them are "open educational resources", with the operative word being "open" (i.e., *free*). While you will not strictly *need* them, you may wish to consult them for additional exposure to various topics. Supplemental (optional) readings will be assigned from some of these sources.

* [*Data Science: A First Introduction with Python*](https://python.datasciencebook.ca/) by Tiffany Timbers, Trevor Campbell, Melissa Lee, Joel Ostblom, Lindsey Heagy 
* [*Computational and Inferential Thinking: The Foundations of Data Science*](http://inferentialthinking.com/) by Ani Adhikari, John DeNero, David Wagner
* [*Computer Age Statistical Inference: Algorithms, Evidence and Data Science*](https://hastie.su.domains/CASI/) by Bradley Efron and Trevor Hastie
* [*An Introduction to Statistical Learning with Python*](https://www.statlearning.com/) by Gareth James, Daniela Witten, Trevor Hastie, Rob Tibshirani, Jonathan Taylor

## Python 🐍
Data science is not done by pencil and paper; it's done on a computer with computer programs. The most common programming language used today in data science is Python, so that's what we'll be using. In particular, we'll write our Python code in *jupyter notebooks* accessed through a browser via [JupyterHub](https://jupyter.math.uwaterloo.ca/hub/login). You (and we) may also make use of collaborative jupyter notebooks via [Google Colab](https://colab.research.google.com/). These services can be accessed by any device connected to the internet. While access in-class is encouraged, it's not not required. However, access outside of class *is* required. So, if you don't have a tablet, laptop, or personal computer, please make use of the various computer labs on campus. For instance: 🧡[Arts](https://uwaterloo.ca/arts-computing/facilities-and-labs/our-labs), 💜[Engineering](https://uwaterloo.ca/engineering-computing/computer-labs), 💚[Environment](https://uwaterloo.ca/environment-technology-instructional-support/etis-computer-labs), 💙[Science](https://uwaterloo.ca/science-computing/services/science-computer-labs), and 🩷[Math](https://uwaterloo.ca/math-faculty-computing-facility/services/mfcf-computer-labs) all have dedicated computer labs.

## Assessment 🔍

<div align="center">

| Assessment Type | Weight | 
|------|:-----:|
| Case Studies | 15% |
| Tests | 30% |
| Tutorials | 15% |
| Final Exam | 40% |

</div>

**Case Studies (15%)**

* There will be three (3) case studies, each worth 5% of your final grade. Think of these as homework assignments, done outside of class. They will involve data analysis, interpretation, communication, and other facets of the data science workflow.
* You will have two weeks to complete each case study – their release dates will be two weeks ahead of the due dates shown below. You will submit your work electronically via Crowdmark by 5:00PM on the stated due dates. Late submissions will not be accepted.
    * Case Study 1 Due: **Tuesday October 6**
    * Case Study 2 Due: **Tuesday November 10**
    * Case Study 3 Due: **Tuesday December 8**
* Data Science is a collaborative discipline, so I encourage working together with your peers on these Case Studies. However, what you submit must be your own work; blatant cheating and plagiarism will not be tolerated. Please refer to the "Academic Integrity" section in the Course Outline and familiarize yourself with [Policy 71, Student Discipline](https://uwaterloo.ca/secretariat/policies-procedures-guidelines/policy-71) to ensure you are not committing academic misconduct.
* The use of Generative AI tools (like ChatGPT, DALL-E, Gemini, Claude, CoPilot) **is permitted** on Case Studies. Please refer to the "Generative AI" section in the Course Outline for additional guidance on this point. The Case Studies themselves will also provide detailed instructions on the appropriate use of GenAI.

**Tests (30%)**

* There will be two (2) closed-book tests, each worth 15% of your final grade, held on **Friday October 9** and **Friday November 13**.
* Each test is 50 minutes in duration, running between 9:30AM - 10:20AM during that week’s Tutorial time slot. Seating will be assigned with specific locations communicated closer to the tests.
* The tests will evaluate your comprehension of the course material and will consist of a combination of multiple choice questions, small calculations, short answer written responses, python code interpretation, and analysis output interpretation.

**Tutorials (15%)**

* In every Tutorial session not devoted to a test, we will have in-person activities. Participation in each of these ten (10) Tutorials will earn you 1.5% each.

**Final Exam (40%)**

* There will be a 2.5-hour, closed-book, cumulative Final Exam during the Fall 2026 Final Examination Period: **December 10 – December 23**. Please refrain from booking end-of-term travel before the actual exam date is scheduled.
* The format of the Final Exam will mimic that of the two Tests. Specifically, multiple choice questions, small calculations, short answer written responses, python code interpretation, and analysis output interpretation can all be expected.

**Remark Policy:**

* If you have a dispute with your grade on a Case Study or Test, you may request a remark within 1 week of the assessment being returned to you. Bear in mind that the entire assessment is then subject to be remarked. Remark requests must be directed to our course’s Teaching Assistant.
* If you would like to review your Final Exam once final grades have been released, you can schedule an appointment with me by emailing [nstevens@uwaterloo.ca](nstevens@uwaterloo.ca).

## Absence Accommodation 🤝

Throughout the term, you may encounter situations such as significant illnesses, ongoing medical conditions, or other circumstances that prevent you from meeting academic obligations. In such cases, you may choose to declare an absence and may seek accommodation. Permissible absences include:

* _Short-term absence_ - two (2) days, no documentation required, 1 per lecture period, declared within 48 hours of missed assessment 
* _Religious or creed-related absence_ - no documentation required, during lecture period, declared within the first two weeks of class
* _Verification of Condition_ - documentation required, will be reviewed prior to approval, declared within 48 hours of missed assessment
* _Extenuating circumstances_ - documentation required, will be reviewed prior to approval, declared within 48 hours of missed assessment

All such absences must declared in the [Absence Database](https://uwaterloo.ca/math/submitting-absence-declaration). It is your responsibility to refer to the Faculty of Mathematics [Absence Declarations webpage](https://uwaterloo.ca/math/absence-declarations) to ensure you comply with the declaration requirements.

**Accommodation for Missed Case Studies**

* If you have declared a short-term absence in the Absence Database that spans the Case Study deadline, a 48-hour extension will be provided.
* If you have declared any other type of absence in the Absence Database that spans the Case Study deadline, the weight from that Case Study will be shifted to the Final Exam.
* If you have not declared an absence in the Absence Database, you will receive a zero for your missed Case Study.

**Accommodation for Missed Tests**

* If you have declared any absence in the Absence Database that spans the Test date, the weight from that Test will be shifted to the Final Exam.
* If you have not declared an absence in the Absence Database, you will receive a zero for your missed Test.

**Accommodation for Missed Tutorials**

* There will be no accommodation for missed Tutorials. For any missed Tutorial, you will not receive the associated 1.5%.

**Accommodation for Missed Final Exam**

* If you miss the Final Exam with a verified absence in the Absence Database, you may be assigned a final grade of “incomplete” ([INC](https://uwaterloo.ca/academic-calendar/undergraduate-studies/catalog#/policy/rkrb6r5V6?bc=true&bcCurrent=Grading%20Systems%20and%20Processes&bcGroup=Academic%20Regulations&bcItemType=policies)), and your Final Exam deferred to a later date, if:
    * it is mathematically possible for you to pass the course, had you written the Final Exam, AND
    * you demonstrated _meaningful engagement_ with the course, defined here to mean: your grade going into the Final Exam is more than 0%.
* If you miss the Final Exam and your absence is not approved, you will be assigned a final grade of “did not write” ([DNW](https://uwaterloo.ca/academic-calendar/undergraduate-studies/catalog#/policy/rkrb6r5V6?bc=true&bcCurrent=Grading%20Systems%20and%20Processes&bcGroup=Academic%20Regulations&bcItemType=policies)), which counts as a final grade of 32 in transcript averages.
