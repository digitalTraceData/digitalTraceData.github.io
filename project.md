---
layout: post
date: 2025-08-20
author: Javier Garcia-Bernardo, Laura Boeschoten, and Thijs Carrière
title: Group project guidelines
---

The group project is a central part of the course. The project is designed to give you hands-on experience with digital trace data, and to apply the knowledge you have gained in the course to a real-world problem. In the practical you will work in groups to collect text data, label it using Natural Language Processing models, discuss the errors and biases that you encounter in the data, and interpret the results in light of the errors.

The slides used in the first lab are available [here](https://raw.githubusercontent.com/digitalTraceData/digitalTraceData.github.io/main/materials/Lab_Project_info.pdf).

## Feedback moments during workshops

Feedback on the group project will take place during the regular workshop sessions. These moments combine peer review, short teacher check-ins, and time to continue working on the project.

During peer review, groups will present their progress to another group. Each peer-review round will take about 30 minutes. Come prepared to explain your research question, data collection strategy, expected representation and measurement errors, and the main decisions you still need feedback on.

Before the session, each group should prepare 2-3 specific questions they want feedback on. If there are problems with collaboration or task division, come early and talk to the teacher before the peer-review round starts.

After receiving feedback, each group will spend 15 minutes documenting:
- what feedback they received;
- how it relates to the questions they brought;
- what they will change or keep based on that feedback;
- who will take responsibility for the next tasks.

The rest of the workshop is project work. The teacher will circulate, ask questions, and help groups sharpen their research question, data collection plan, and error framework. When presenting to the teacher or another group, use the big screen where possible and sit together so the feedback can be discussed directly.


## Practical information
* The project consists of two assignments, each worth 30% of the final grade. 
* The groups will be formed in the first practical. If you miss the first practical, you will not be able to participate in the group project and will fail the course.
* Progress will be tracked through peer review and teacher check-ins during the regular workshop sessions. Attendance and active participation in these feedback moments are mandatory.
* Upload the written report and the presentation through the link on the [home page](./). Please name your file groupX_report.pdf, groupX_presentation.pdf.


## Assignment 1: Errors in data collection (30% of the grade)
In the first assignment you will develop a research question, collect text data using one of the methods explained in the lectures/labs (data donation, plug-ins, scraping, APIs), and identify and discuss the errors that you anticipate and encounter when collecting data to answer it.  

The outcome is a short report (<1,000 words excluding references and potential figures) that you will submit in week 5 (see weekly schedule). You will receive feedback from peers and lecturers during the workshop sessions (weeks 3 and 4).

Please find the template and the rubric of assignment 1 [here](https://raw.githubusercontent.com/digitalTraceData/digitalTraceData.github.io/main/materials/template_assignment1.docx).

Before you start, make sure your research question is broader than one platform, dataset, or source. For example, avoid framing the project only as "what happens in BBC comments?" and instead define the broader target population or phenomenon you want to study, then explain how your collected data approximates it.

In the report, explicitly distinguish representation errors from measurement errors. This distinction may look different depending on the data collection method: it is often more direct in data donation projects, while scraping projects require extra care in defining the target population, the observed population, and what each collected variable actually measures. For example, think carefully about whether deleted comments, missing users, platform moderation, or unavailable metadata create representation problems, measurement problems, or both.

Steps:
- During the final 20 minutes of the first lab meeting, discuss as a group how you envision working together. Discuss each person’s responsibilities and make agreements on how to collaborate. You can use the group contract for this, which can be found [here](https://docs.google.com/document/d/1VdUVTzQaxsFTXqVFKyJlNi9FZ_WlRKkHP-da_1MlPxI/edit?usp=sharing). 
- Decide on a specific research question and a target dataset. Since you will use the data in the second assignment, make sure that the data is suitable for the analysis you have in mind. In the second assignment, you will label the data using text classification models using a machine learning model. These models classify text, for example detecting the presence of hate speech, political leaning, personality traits or different emotions. We recommend you to use one of the proposed themes: political polarization, hate speech, personality traits, or mental health. Some of the research questions from previous years are:
  -  How does the Spotify listening behavior of Utrecht University students towards music change over the course of the academic year?  
  -  Do supporters of Donald Trump spread more hate speech on social media in the month after the July 13th assassination attempt compared to the month before the attempt?
  -  What attitudes towards the actions of radical climate activists are visible on Reddit?
- Take a quick look at the [PRIDE Questionnaire for approval Single Study](https://ferb.sites.uu.nl/wp-content/uploads/sites/432/2025/05/PRIDE-Questionnaire-for-approval-Single-Study.docx), which helps conduct the project in an ethically responsible manner and in accordance with legislation. You will only need to complete it for the second assignment, but it is a good idea to start thinking about the ethical implications of your project from the beginning.
- Start collecting the data using the methods explained in the lectures/labs: either data donation/plug-ins (lab 2), or scraping/APIs (lab 3). In the unlikely case that you are using participants, you will need to create an informed consent form. For that, talk with your project supervisor (either Thijs or Laura).
- Participate in the first peer-review workshop (week 3) to discuss your progress. Prepare a few (<5) slides with your progress which indicates on what topics each group member worked (each slide should contain the contributors). Bring already some of the collected data and 2-3 questions you want feedback on. The teacher may ask any group member the checkpoint questions below, and we expect everyone in the group to be able to answer them:
  - What broader phenomenon or target population are you studying, and what observed population or trace data do you actually have?
  - Why is this digital trace data a plausible proxy for your research question, and what does it fail to capture because of the platform, tool, or data source?
  - What exact collection route are you using (scraping, API, data donation, plug-in, or another method), and what are your inclusion rules, unit of analysis, and first signs of missing or distorted data?
- Finish collecting the data and discuss the errors (representation and measurement) that you anticipate when answering the research question with the proposed data.
- Participate in the second peer-review workshop (week 4) to discuss your progress. Prepare a few slides with your progress and 2-3 questions you want feedback on. The teacher may ask any group member the checkpoint questions below, and we expect everyone in the group to be able to answer them:
  - Can you draw the path from target phenomenon to final dataset and identify where representation errors enter, such as coverage, sampling or search terms, non-participation, deleted content, moderation, ranking, or unavailable data?
  - For each key variable, what concept do you want to measure, what proxy do you actually observe, and what measurement errors may enter through platform design, metadata limits, scraping or API extraction, preprocessing, bots, duplicates, or language choices?
  - Which two or three errors most threaten your answer to the research question, in what direction might they bias your findings, and what validation, comparison, or sensitivity check can you still do?
- Finish assessing the errors in the data, ideally by comparing the data with other sources of information (e.g. representative surveys).
- Submit a short report (<1,000 words excluding references and potential figures) in week 5 (see weekly schedule). The link for handing in the report can be found on the course’s homepage. 

Grading:
- Process: 30% (work, communication and preparation for feedback moments). This is an individual grade.
- Report: 70% This is a group grade.
- Error framework: Students should clearly separate representation and measurement errors, explain each step in the data collection process where these errors may enter, and apply the total error framework to their specific method rather than using it generically.


## Assignment 2: Errors in data labeling and moving past errors
In the second assignment you will further analyze the data collected in the first assignment to answer the RQ. For this you will use a Natural Language Processing model of your choice to label the data, which you will learn on week 5. These type of models can predict things from text. For example, they can predict if the text contains hate speech, polarized content, negative language, or specific personality traits. You will discuss the biases that you encounter in the labeling process, and how you will move past these errors in data collection and data labeling.

The outcome is a final presentation (12 minutes + 5 minutes of Q&A) that you will present in week 8 (see weekly schedule). Please submit the final presentation using the upload link before 23:59 in the day of the deadline (see weekly schedule). Name your slides `groupX_presentation.pdf/pptx`.

Please find the template and the rubric of assignment 2 [here](https://raw.githubusercontent.com/digitalTraceData/digitalTraceData.github.io/main/materials/template_assignment2.docx).


You will receive feedback from peers and lecturers during the workshop sessions (weeks 6 and 7).

Steps:
- Run a text classification model of your choice from [Hugging Face](https://huggingface.co/models) on the data collected in the first assignment. These models classify text, for example detecting the presence of hate speech, political leaning, personality traits or different emotions. The model should be appropriate to answer your research question. If you would like to use LLMs (e.g., GPT-5) for labeling, you can look at the materials [here](https://sodascience.github.io/workshop_llm_data_collection/). Please be aware that using LLMs costs money (for a typical project in the course, usually less than one euro).
- Reflect on the biases you expect during the labeling process, and the origin of those biases.
- Participate in the third peer-review workshop (week 6) to discuss your progress. Prepare a few slides with your progress, make sure the slides indicate who worked on what topics, and bring 2-3 questions you want feedback on. The teacher may ask any group member the checkpoint questions below, and we expect everyone in the group to be able to answer them:
  - What label or construct is your model trying to detect, what data was the model trained on, and how well does that match your own data, language, platform, and research question?
  - How will you check model quality and bias, for example with manual coding, false positives and false negatives, subgroup or platform differences, class imbalance, sarcasm, multimodal content, or preprocessing choices?
  - What are the main ethical and PRIDE issues in your project (consent, legal basis, sensitive data, vulnerable groups, re-identification, contextual integrity, data minimization, or possible harm), and what concrete decisions reduce those risks?
- Reflect on how you would expand the study to tackle these issues. What type of data would you need to collect?
- Complete the [PRIDE Questionnaire for approval Single Study](https://ferb.sites.uu.nl/wp-content/uploads/sites/432/2025/05/PRIDE-Questionnaire-for-approval-Single-Study.docx), which helps conduct the project in an ethically responsible manner and in accordance with legislation. 
- Reflect on the ethical principles discussed through the course. Is your project aligned with them?
- Draft the final presentation.
- Participate in the fourth peer-review workshop (week 7) to discuss your progress. Prepare a few slides with your progress and bring the completed PRIDE questionnaire. The teacher may ask any group member the checkpoint questions below, and we expect everyone in the group to be able to answer them:
  - What is your answer to the research question, and how do your representation errors, measurement errors, and model errors limit or qualify that answer?
  - If you redesigned or expanded the study, what would most improve it: another platform, data donation, survey linkage, designed big data, manual labels, better sampling, external benchmarks, or stronger model validation?
  - Does your final presentation make the whole logic visible: research question, target and observed population, collection method, error framework, model or analysis, findings, ethics and PRIDE, limitations, and next steps?
- **Submit the slides and the PRIDE form before the deadline (see weekly schedule)** through the link on the home page. Please name your file groupX_PRIDE.pdf, groupX_presentation.pdf. 
- Present the group project in week 8 (see weekly schedule). **Groups Cheetah, Pardus, Lynx and Tigris are present from 11:00 - 13:00. Groups Onca, Uncia, Leo, Puma and Caracal are present from 13:00 - 15:00. We expect all groups to actively engage with questions and discussion.**
- During the presentations, we require all other groups to active participate in the discussion and ask questions. 

Grading:
- Process: 30% (work, communication and preparation for feedback moments). This is an individual grade.
- Presentation: 70%. This is a group grade.
