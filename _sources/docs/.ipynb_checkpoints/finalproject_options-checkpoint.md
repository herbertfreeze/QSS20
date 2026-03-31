---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

(finalproject_options)=

# Project Options

You will select one of three options for your final project:


<!-- ## 1. Social Impact Practicum

With support from the [Dartmouth Center for Social Impact](https://students.dartmouth.edu/social-impact/), one option for your final project is to complete a [Social Impact Practicum](https://students.dartmouth.edu/social-impact/programs-initiatives/students/social-impact-practicums-sips) (SIP): a chance for you to use your data science skills to help a real-world organization. 

<!-- Your partner and data provider for the Social Impact Practicum will be the National Center for START Services (NCSS) at the Institute on Disability at University of New Hampshire (UNH). The START (Systemic, Therapeutic, Assessment, Resources, and Treatment) model advanced at UNH is a comprehensive model of service supporting the optimization of independence, treatment, and community living for individuals with IDD and mental health needs. You can find more information about the Center for Start Services [here](https://centerforstartservices.org/) and [here](https://iod.unh.edu/projects/center-start-services). To get a look at the START program in action, check out [this documentary (66 mins)](https://centerforstartservices.org/START-film).
 -->
<!-- If you choose this project option, you have two options. The first is to analyze the results of medical student training for prescribing to folks with Intellectual and Developmental Disabilities (IDD). The second is to study a large dataset on experiences and outcomes for START participants. -->
 -->
<!-- ### SIP Option: 21st Century Community Learning Centers

The 21st Century Community Learning Centers (21C) program for the Vermont Agency of Education has collected from about 90 sites offering 21C-supported afterschool and summer programs in Vermont. The dataset includes both quantitative data (for example, the % of students from low-income families and the number of students receiving different “doses” of afterschool/summer programs) and qualitative data (for example, descriptions of exemplary projects from each program). Students can use this data to evaluate the efficacy of afterschool and summer programs. -->

<!-- ### SIP Option 2: New Hampshire Academy of Science

In rural areas such as the Upper Valley, participants often claim to have learned of new initiatives by “word of mouth”. Unfortunately, while this may be an effective communication tool among affluent communities, research indicates that it does not necessarily reach those who are less financially secure. NHAS has secured a generous amount of financial aid to increase the socioeconomic representation in the scientific community but unless applicants from less affluent communities know about, and subsequently apply to, NHAS programs, these financial resources go unused.

To that end, NHAS is hoping Dartmouth students can work with data gathered by NHAS educational research surveys and registration data for NHAS patrons of current programs and camps to explore which communities in the Upper Valley are underrepresented in their program. This aligns with a broader goal of ensuring that the scientific community is accessible, regardless of socioeconomics, and truly representative of the broader community at large.

Part of this project should also include ideas about how to both collect the sensitive data that is likely to be yielded from the survey as well as how to evaluate and use the data gathered most effectively.-->


<!-- The data cuts to an important issue in public health: *How do medical professionals interact with patients with IDD, and how can medical student training improve this?* Here is more information from the project partner:

> As part of a strategic initiative to develop best practices for prescribers who work with patients with IDD and mental health concerns (IDD_MH), NCSS/UNH has begun piloting training content with medical students (residents, fellows and second/third year medical students) at the Geisel School of Medicine at Dartmouth, the medical school and the University of Puerto Rico, and Franklin Pierce University’s Physician Assistant Program.  This includes a 6 hours of trainings based on the recently published [Integrated Mental Health Treatment Guidelines for Prescribers in Intellectual and Developmental Disabilities](https://centerforstartservices.org/IDD-MH-Prescribing-Guidelines) as well as pre- and post-evaluation data.

> The START program at UNH would like students of QSS 20 to analyze this training evaluation data to assess strengths and growth points as well as recommend changes based on the data which could improve efficacy, retention, impact, or all of the above.  (For example, the training videos which include the lived experience of individuals are already scoring higher, so that is one already-identified place where small changes to the content delivery medium could improve results).

> At present (Fall 2023), there are 200+ evaluations of 40+ medical students, and by November we expect this number to grow to 300+ evaluations from 60+ distinct medical students. -->

<!-- The training was six hours in length, and students evaluated the program by answering multiple choice and open-ended questions. You can view the [program evaluation surveys here](https://drive.google.com/drive/folders/1csAgglJta0Nbriyl358LKBwecVgKlbwb?usp=sharing) or see the [general SIP proposal](https://docs.google.com/document/d/1zctCWNn5S3PaZGCyKkKo0lnMBxiYUiDv/edit?usp=sharing&ouid=106209867651452643666&rtpof=true&sd=true) for more info.

I will update with possibilities by the end of this week. Here are a few broad directions: -->

<!--  Here are a few broad questions you could investigate if choosing this option: 

_Is this working?_

* Changes in perspectives and depth of understanding toward IDD?
* Consider training outcomes from ranking questions (e.g., with regression) and free-form text (e.g., topic models)
* Connect with participant demographics

_What training components matter most?_

* Expert presentation & best practices
* Guest speakers with personal experience of IDD
* Other training elements suggested in open-ended questions


### SIP Option 2: START Information Reporting System (SIRS)

These data include about 13,000 START participants from 2013 to 2021. The more detailed files include only the cohort of participants from 2019 to 2020. These data include: 
* Encounters with law enforcement
* Emergency visits
* Physical restraint during crises
* Demographics
* Intake info

Here are a few broad questions you could investigate if choosing this option:--> 

<!-- **Over full SIRS data**: 

* What is the composition of START participants by race, gender, and living situation, and how do these correlate with disadvantage in terms of family background, crisis events, or aggressive behavior?
* How often do START participants encounter law enforcement or exhibit aggressive or self-harming behaviors, and how have these changed over time? 
* How did trends in START participation (e.g., hospital visits) change with the COVID pandemic compared with the previous, longer time scale (back to 2010)?

**Over 2019-2020 cohort**:
General question: *How have those with disabilities fared during COVID-19 and what racial inequalities do we see in its impact?*
* Did the COVID lockdowns increase suicidal ideation over time, e.g. through decreased access to mental health support or stress related to living situations?
* Did the COVID lockdowns introduce challenges due to encounters with law enforcement, who sometimes respond inappropriately to young adults with disabilities (e.g., they may refer them to Emergency Departments with excessive frequency)?
* What themes emerge in the Family Experiences with Severe Mental Illness Scale (FEIS) open responses (e.g., through topic modeling), such as desire for higher caregiver involvement and/or caregiver receptivity to this desire---and how do these themes vary with family demographics or other background factors?

You can view the [data dictionary here](https://docs.google.com/spreadsheets/d/1HV5kl3IOzWen91LkHBcFZi3so_angRf8/edit?usp=sharing&ouid=106209867651452643666&rtpof=true&sd=true).  -->

**These options require working in a group.**

## 1. Massive Social Media Data

The COVID-19 pandeimic impacted every country globally, with stay-at-home orders in most countries with outbreaks. The unprecendented amount of online activity also provided an opportunity to understand human behavior at a granular scale. Projects will analyze the largest COVID-19 Twitter dataset (n=4 billion) to investigate how COVID-19 interesect with student's particular interests. Examples from this dataset include [election misinformation](https://misinforeview.hks.harvard.edu/article/covid-19-misinformation-and-the-2020-u-s-presidential-election/), [liberal and conservative bots pushing misinformation](https://www.nytimes.com/2020/10/29/technology/twitter-bots-poised-to-spread-disinformation-before-election.html), and [KPop driving public health practices like mask wearking](https://arxiv.org/pdf/2110.04149.pdf).

Second, in recent years, text-based social media has given way to visual-based social media, and is now often the source of political organization and protest. The 2024 United States Presidential Election is a hotbed to test social scientific ideas, and as part of our efforts we have gathered 500,000 Instagram posts and 750,000 TikTok posts for analysis. This provides the opportunity to do timely analysis on the ongoing elections.


**This option requires working in a group.**


## 2. Use Senior Thesis/independent project 

If you're already pursuing a significant research project, you may use this course to advance an existing work in progress, covering parts and analysis you might not include otherwise. This is intended to build toward your thesis. If you are already enrolled in a thesis course, I will need to coordinate with your other professor. If in doubt, please ping me on Slack or email.

The project needs to align with the [evaluation criteria](https://github.com/herbertfreeze/QSS20_S25/blob/main/finalproj_guidelines/final_project_rubric.csv) — e.g., it must result in data you can share with us, a repo you can share, and a 10-page CS-style report.

Please choose this option with caution as you will be held to same grading standard as groups of 3-4. Moreover, unless you have already made substantial progress on an independent project, you probably won't be able to finish it in one short quarter.

**You can complete this option either individually or in a group** (i.e., by focusing on one person’s project and getting group help).