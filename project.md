---
layout: post
date: 2024-09-01
author: Javier Garcia-Bernardo and Laura Boeschoten
title: Group project guidelines
---

The group project is a central part of the course. The project is designed to give you hands-on experience with digital trace data, and to apply the knowledge you have gained in the course to a real-world problem. In the practical you will work in groups to collect text data, label it using Natural Language Processing models, discuss the errors and biases that you encounter in the data, and interpret the results in light of the errors.

The slides used in the first lab are available [here](https://surfdrive.surf.nl/files/index.php/s/eC188WPkihnWC2I).

## Timeslots for the Wednesday feedback moments (see dates and location on MyTimetable)

- Location: BOL - 2.115 (please double check on MyTimetable)
- Come prepared: Bring and hand in a list of 10+ concrete tasks and who completed those tasks. Make sure that the list is signed by all group members.
- Ideally bring 1-2 slides with your progress so far and your proposed next steps.


| Group   | Timeslot            | Instructors             |
|:--------|:--------------------|:------------------------|
| Uncia   | 13:15-13:30         | Thijs + Javier          |
| Tigris  | 13:35-13:50         | Thijs + Javier          |
| Lynx    | 13:55-14:10         | Thijs + Javier          |
| Onca    | 14:15-14:30         | Thijs + Javier          |
| Pardus  | 14:45-15:00         | Thijs + Laura           |
| Cheetah | 15:05-15:20         | Thijs + Laura           |
| Caracal | 15:25-15:40         | Thijs + Laura           |
| Leo     | 15:45-16:00         | Thijs + Laura           |


## Practical information
* The project consists of two assignments, each worth 30% of the final grade. 
* The groups will be formed in the first practical. If you miss the first practical, you will not be able to participate in the group project and will fail the course.
* The progress will be tracked in four feedback sessions, a 15 minute meeting with the lectures to discuss the progress of the project. The feedback sessions are mandatory.
* Upload the group contract, the written report and the presentation through [this link](https://surfdrive.surf.nl/files/index.php/s/HgeNKHK8K9JS4jW). Please name your file contract_groupX.pdf, report_groupX.pdf, presentation_groupX.pdf. 


## Assignment 1: Errors in data collection (30% of the grade)
In the first assignment you will develop a research question, collect text data using one of the methods explained in the lectures/labs (data donation, plug-ins, scraping, APIs), and identify and discuss the errors that you anticipate and encounter when collecting data to answer it.  

The outcome is a short report (<1,000 words excluding references and potential figures) that you will submit in week 5 (see weekly schedule). You will receive feedback from the lecturers during the feedback sessions (weeks 3 and 4).

Please find the template and the rubric of assignment 1 [here](https://digitaltracedata.github.io/materials/template_assignment1.docx).

Steps:
- Write a group contract: a short signed group agreement stating each person's responsibilities and the consequences of violating the agreement (e.g., getting kicked out of the group). You can find a template [here](https://docs.google.com/document/d/1VdUVTzQaxsFTXqVFKyJlNi9FZ_WlRKkHP-da_1MlPxI/edit?usp=sharing)
- Decide on a specific research question and a target dataset. Since you will use the data in the second assignment, make sure that the data is suitable for the analysis you have in mind. In the second assignment, you will label the data using text classification models using a machine learning model. These models classify text, for example detecting the presence of hate speech, political leaning, personality traits or different emotions. We recommend you to use one of the proposed themes: political polarization, hate speech, personality traits or mental health. 
- Fill the [PRIDE Questionnaire for approval Single Study](https://ferb.sites.uu.nl/wp-content/uploads/sites/432/2020/12/PRIDE-Questionnaire-for-approval-Single-Study.docx), which helps conduct the project in an ethically responsible manner and in accordance with legislation. 
- Start collecting the data using the methods explained in the lectures/labs: either data donation/plug-ins (lab 2), or scraping/APIs (lab 3).
- Attend _Feedback session I_ (week 3) to discuss your progress. Ideally prepare a couple slides with your progress. Bring the completed PRIDE questionnaire for discussion. Bring and hand in a list of 10+ concrete tasks and who completed those tasks. Make sure that the list is signed by all group members.
- Finish collecting the data and discuss the errors (representation and measurement) that you anticipate when answering the research question with the proposed data.
- Attend _Feedback session II_ (week 4) to discuss your progress. Ideally prepare a couple slides with your progress. Bring and hand in a list of 10+ concrete tasks and who completed those tasks. Make sure that the list is signed by all group members.
- Finish assessing the errors in the data, ideally by comparing the data with other sources of information (e.g. representative surveys).
- Submit the PRIDE questionnaire and a short report (<1,000 words excluding references and potential figures) in week 5 (see weekly schedule).

Grading:
- Process: 30% (communication and preparation for feedback sessions). This is an individual grade.
- Report: 70%. This is a group grade.


## Assignment 2: Errors in data labeling and moving past errors
In the second assignment you will further analyze the data collected in the first assignment to answer the RQ. For this you will use a Natural Language Processing model of your choice to label the data, which you will learn on week 5. These type of models can predict things from text. For example, they can predict if the text contains hate speech, polarized content, negative language, or specific personality traits. You will discuss the biases that you encounter in the labeling process, and how you will move past these errors in data collection and data labeling.

The outcome is a final presentation (10-15 minutes + 5-10 minutes of Q&A) that you will present in week 8 (see weekly schedule). Please submit the final presentation using the upload link on October 24th (before 23:59). Name your slides `presentation_groupX.pdf/pptx`.

Please find the template and the rubric of assignment 2 [here](https://digitaltracedata.github.io/materials/template_assignment2.docx).


You will receive feedback from the lecturers during the feedback sessions (weeks 7 and 8).

Steps:
- Run a text classification model of your choice from [Hugging Face](https://huggingface.co/models) on the data collected in the first assignment. These models classify text, for example detecting the presence of hate speech, political leaning, personality traits or different emotions. The model should be appropriate to answer your research question.
- Reflect on the biases you expect during the labeling process, and the origin of those biases.
- Attend _Feedback session III_ (week 7) to discuss your progress. Ideally prepare a couple slides with your progress. Bring and hand in a list of 10+ concrete tasks and who completed those tasks. Make sure that the list is signed by all group members.
- Reflect on how you would expand the study to tackle these issues. What type of data would you need to collect?
- Reflect on the ethical principles discussed through the course. Is your project aligned with them?
- Draft the final presentation.
- Attend _Feedback session IV_ (week 8) to discuss your progress. Ideally prepare a couple slides with your progress. Bring and hand in a list of 10+ concrete tasks and who completed those tasks. Make sure that the list is signed by all group members.
- Present the group project in week 8 (see weekly schedule)

Grading:
- Process: 30% (communication and preparation for feedback sessions). This is an individual grade.
- Presentation: 70%. This is a group grade.