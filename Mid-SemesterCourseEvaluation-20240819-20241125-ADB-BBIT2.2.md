---
title: "Mid-Semester Course Evaluation Results"
# author: "Allan Omondi"
# date: "2024-09-29"
output:
  html_document: 
    toc: true
    df_print: kable
    fig_width: 8
    fig_height: 8
    fig_caption: true
    toc_depth: 4
    keep_md: true
    css: CSS_Chunk.css
  pdf_document:
    toc: yes
    number_sections: yes
    fig_width: 8
    fig_height: 8
    fig_caption: yes
    keep_tex: yes
  html_notebook: default
  always_allow_html: true
  word_document:
    toc: yes
---

|  |  |
|---------------------------------------|---------------------------------|
| **Course** | Advanced Database Systems |
| **Course Code** | BBT3104 |
| **Class** | BBIT 2.2 |
| **Semester Duration** | 19^th^ August 2024 to 25^th^ November 2024 |
| **Date of Evaluation** | 23^rd^ September 2024 to 29^th^ September 2024 (Week 6 of 14) |
| **Total number of students who submitted the course evaluation** | 171 |
| **Total number of students registered in the AMS at the time of the course evaluation** | 192 |
| **Response rate** | 89% |
| **e-Learning URL** | <https://classroom.google.com/c/NzAxMDA1ODc3MzU4?cjc=cqyoyyy> |
| **Data collection tool** | <https://docs.google.com/forms/d/e/1FAIpQLSd4By-juKjo3nB_ZEFWEdpUpWKBsTPeibqkYcoBKwZ0BOgXRg/viewform?usp=sf_link> |
| **Raw Data** | <https://docs.google.com/spreadsheets/d/1R7UcA0w7yNBO1e0FeC2SusxJt9u3GsVkC5mOZQ-bP4k/edit?usp=sharing> |
| **Lecturer** | Dr Allan Omondi \<aomondi\@strathmore.edu\> |

------------------------------------------------------------------------











# Course Evaluation Score

Mean Course Evaluation Score = 4.3769 / 5

Percentage Mean Course Evaluation Score = 87.54%

Median Course Evaluation Score = 4.4545 / 5

------------------------------------------------------------------------







\newpage

# Quantitative Data Analysis

## Course Evaluation Scores per Group



The **"Average Course Evaluation Rating"** variable in the plot below indicates the score **per gender** with a baseline of 4/5.

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/VisualizationsForCourseEvaluationResultsperGender-1.png)<!-- -->

\newpage

The **"Average Course Evaluation Rating"** variable in the plot below indicates the score **per class group** with a baseline of 4/5.

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/VisualizationsForCourseEvaluationResultsperGroup-1.png)<!-- -->

\newpage

## Correlations



The specific correlation values are presented below:

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/CorrelationMatrixWithFigures-1.png)<!-- -->

### Interesting Correlations

Correlations worth noting include:

-   **0.78 correlation** between "lectures slides" and "lecture notes on some of the lecture slides": *Having lecture notes to accompany some lecture slides improves the overall quality of the lecture slide*

-   **0.72 correlation** between "Supplementary videos to watch as an additional explanation of a topic" and "Supplementary content to read": *Students who find the supplementary videos useful with regad to their learning also find the supplementary notes useful*

-   **0.72 correlation** between "the quality of the lectures given (quality measured by the breadth (the full span of knowledge of a subject) and depth (the extent to which specific topics are focused upon, amplified, and explored) of learning - NOT quality measured by how fun, comical, or entertaining the lectures are)" and "the integration of practical labs in most classes even if it is not in a computer lab": *Mixing practicals with theory in the same class improves the overall quality of the lecture.*

-   **0.7 correlation** between "understood Concept 2 (Conceptual Data Modelling)" and "understood Concept 3 (Database Constraints)": *Students who do not understand Concept 2 also do not understand Concept 3. It is necessary to understand Concept 2 before moving on to Concept 3.*

-   **-0.56 correlation** between "Absenteeism" and "Coursework Marks": *The higher the absenteeism, the lower the student's coursework marks*

-   **-0.29 correlation** between "Absenteeism" and "Understood Concept 1": *The more late students are to register for the course, the harder it is for them to understand concept 1*

\newpage

The negative correlation between "absenteeism" and "coursework marks" is stronger among the female students, i.e., the more classes a student misses, the worse their performance, especially for female students.

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/DrillDownCorr1-1.png)<!-- -->

\newpage

### Absenteeism Percentage

#### Absenteeism by Specific Class Group

Group C has the lowest absenteeism issues despite having a class on Friday afternoon.

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/AbsenteeismBoxandWhiskerSpecificGroup-1.png)<!-- -->

#### Absenteeism by Gender

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/AbsenteeismBoxandWhiskerGender-1.png)<!-- -->

\newpage

# Qualitative Data Analysis



## Sentiment Analysis (Lexicon-Based)



The "likes" refer to the answer to the question, "Write at least two things you like about the teaching and learning in this unit so far." The sentiments expressed through the "likes" are:



The "wishes" refer to the answer to the question, "Write at least one recommendation to improve the teaching and learning in this unit (for the remaining weeks in the semester)". The sentiments expressed through the "wishes" are:



\newpage

### Chord Diagram of Sentiments for Likes per Class Group

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/ChordDiagramLikesPerGroup-1.png)<!-- -->

\newpage

### Chord Diagram of Sentiments for Likes per Class Gender

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/ChordDiagramLikesPerGender-1.png)<!-- -->

The results are similar for both genders but the male students are more positive and trustworthy based on their choice of words for the "likes question".

\newpage

### Chord Diagram of Sentiments for Wishes per Class Group

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/ChordDiagramPerGroup_Wishes-1.png)<!-- -->

Group A and C express more negative sentiments with Group C also expressing fear based on their choice of words for the "wishes question".

\newpage

### Chord Diagram of Sentiments for Wishes per Gender

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/ChordDiagramPerGender_Wishes-1.png)<!-- -->

The sentiments for wishes are similar across both genders but female students express more fear than male students based on their choice of words.

\newpage

## Topic Modelling (Latent Dirichlet Allocation (LDA) based)

The goal of topic modelling is to identify latent (hidden) terms (topics) in the students' course evaluation textual feedback. In this case, a topic is a mixture of words and a student's textual feedback is a combination of one or more topics (mixed-membership model).





The 2 topics for the "likes" (as guided by the LDA model) are:

1.  Topic 1: Well-Explained Lectures

2.  Topic 2: Collaborative Environment

3.  Topic 3: Well-Taught for Ease of Understanding

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/visualizations_for_likes_topic_modelling-1.png)<!-- -->

\newpage

The 5 topics for the "wishes" (as guided by the LDA model) are:

1.  Topic 1: Reduce the Workload

2.  Topic 2: Reduce the Complexity of the Labs

3.  Topic 3: Application of Data Engineering

4.  Topic 4: Application of Python

![](Mid-SemesterCourseEvaluation-20240819-20241125-ADB-BBIT2.2_files/figure-html/visualizations_for_wishes_topic_modelling-1.png)<!-- -->

\newpage

# Appendices

## Appendix A: Full Name of Variables

The following variables have been renamed to fit the correlation plots:

-   \`A. Enjoying Subject\` = \`B - 1. I am enjoying the course\`,

-   \`B. Classes Start-End\` = \`B - 2. Classes start and end on time\`,

-   \`C. Learning Environment\` = \`B - 3. The learning environment is participative, involves learning by doing, and is group-based\`,

-   \`D. Content Delivery\` = \`B - 4. The subject content is delivered according to the course outline and meets my expectations\`,

-   \`E. Clear Topics\` = \`B - 5. The topics are clear and logically developed\`,

-   \`F. Oral and Writing\` = \`B - 6. I am developing my oral and writing skills\`,

-   \`G. Critical Thinking\` = \`B - 7. I am developing my reflective and critical reasoning skills\`,

-   \`H. Assessment Methods\` = \`B - 8. The assessment methods are assisting me to learn\`,

-   \`I. Relevant Feedback\` = \`B - 9. I receive relevant feedback\`,

-   \`J. Read Recommendations\` = \`B - 10. I read the recommended readings and notes\`,

-   \`L. eLearning Material\` = \`B - 11. I use the eLearning material posted\`,

-   \`Understood Concept 1\` = \`C - 1. Concept 1 of 6: Business Processes\`,

-   \`Understood Concept 2\` = \`C - 2. Concept 2 of 6: Conceptual Data Modelling\`,

-   \`Understood Concept 3\` = \`C - 3. Concept 3 of 6: Database Constraints\`,

-   \`Understood BI1 Concept 4\` = \`Q03_Level of Learning Achieved-\>B - 4. - BI1 - Concept 4 of 4: Dashboarding for Business-Facing and Customer-Facing Analytics\`,

-   \`Understood BI2 Concept 1\` = \`Q03_Level of Learning Achieved-\>B - 1. - BI2 - Concept 1 of 4: Ensemble Methods for Predictive Analytics\`,

-   \`Understood BI2 Concept 2\` = \`Q03_Level of Learning Achieved-\>B - 2. - BI2 - Concept 2 of 4: Predictive Modelling Using R\`,

-   \`Understood BI2 Concept 3\` = \`Q03_Level of Learning Achieved-\>B - 3. - BI2 - Concept 3 of 4: Data Warehousing and BI Strategy Implementation\`,

-   \`Understood BI2 Concept 4\` = \`Q03_Level of Learning Achieved-\>B - 4. - BI2 - Concept 4 of 4: Data Engineering\`,

-   \`Acquired Skill 1\` = \`Q04_Competency for Technologies-\>D - 1. ChartJS\`,

-   \`Acquired Skill 2\` = \`Q04_Competency for Technologies-\>D - 2. R (includes R markdown and R plumber)\`,

-   \`Acquired Skill 3\` = \`Q04_Competency for Technologies-\>D - 3. MySQL\`,

-   \`Acquired Skill 4\` = \`Q04_Competency for Technologies-\>D - 4. Kafka\`,

-   \`Acquired Skill 5\` = \`Q04_Competency for Technologies-\>D - 5. ksqlDB\`,

-   \`Acquired Skill 6\` = \`Q04_Competency for Technologies-\>D - 6. ClickHouse\`,

-   \`Acquired Skill 7\` = \`Q04_Competency for Technologies-\>D - 7. Linear and Non-Linear ML Algorithms in the caret package\`,

-   \`Group Project\` = \`D - 1. The group project\`,

-   \`Labs Manuals\` = \`D - 2. Quizzes at the end of each concept\`,

-   \`Lab Submissions\` = \`D - 3. Lab manuals that outline the steps to follow during the labs\`,

-   \`Supplementary Videos/Audio\` = \`D - 4. Required lab work submissions at the end of each lab manual that outline the activity to be done on your own\`,

-   \`Lecture Slides\` = \`D - 5. Labs that require you to use Git to work in a team\`,

-   \`Lecture Notes\` = \`D - 6. Labs that require you to work alone\`,

-   \`Quality of Lectures\` = \`D - 7. Supplementary videos to watch as an additional explanation of a topic\`,

-   \`Online for Theory\` = \`D - 8. Supplementary content to read\`,

-   \`Recording of Online\` = \`D - 9. Lectures slides\`, \`D - 10. Lecture notes on some of the lecture slides\`, \`D - 11. The quality of the lectures given (quality measured by the breadth (the full span of knowledge of a subject) and depth (the extent to which specific topics are focused upon, amplified, and explored) of learning - NOT quality measured by how fun, comical, or entertaining the lectures are)\`, \`D - 12. The integration of practical labs in most classes even if it is not in a computer lab\`

\newpage

## Appendix B: Raw Qualitative Data

### Likes

The raw data of the likes is as follows:

<table class="table" style="margin-left: auto; margin-right: auto;">
<caption>Write two things you like about the teaching and learning in this unit so far</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Comment (Likes) </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Class punctuality
Community feedback on Slack </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I love that we have labs that enable me to engage with the content and get some experience of what I would be needed to do in the work environment. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The content delivery is well done </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> - </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the learning pace and the content with the labs is executable </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The topics 
Labs and group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The delivery
The content </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The quizzes, how we learned to use new software i.e. Slack </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Inclusive learning
relevant feedback is given </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Coding in vs and applying it in GitHub </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> n/a </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Null </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like how we are given a quiz after each concept in this unit.
In this unit, I also like the way we already have all the content online for the whole semester. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The learning is very enjoyable and interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the concept of doing the short quizzes on google classroom </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Triggers 
and also capabilities and constraints </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lessons are interesting and push us to get more knowledge and to do better </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is Fun. It is interactive </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. I enjoy how organized the results are so I am able to track my performance from the start to the finish 
2. I like how detailed the lab manuals are because I am able to fully understand what is happening </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> its interesting. its relevant </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like that it is much more practical as performing activities is much more beneficial that just sitting an having the information exposited, I also like that the steps for the practicals are detailed and give explanations on their functions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like that the lecturer gives feedback regarding the projects and labs and that the classes start on time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer has great delivery method and tries to be at per with his class
The lecturer  takes his work seriously and gives his students clear expectations </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The class is quite interactive and teamwork is also shown in class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the quizes  given
the way the content is delivered </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like how informative the unit is.
I like how there is time allocated to work with my peers, it allows me to understand  the concepts more. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer explains things well,the lec goes with a good pace </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> configuration of a database transaction
event scheduling </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Its interactive </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> interactiveness and time keeping </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Assistance when someone has issues during labworks
The step by step procedures to do the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Broading my knowledge and unnderstanding </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1.The quizzes
2.The project </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The timely response on slack
The quizzes after each concept </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The delivery of the content,the lecturer's commitment on assisting a peson individually </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> #NAME? </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> #NAME? </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the topics are taught well , One is guided and what and how they are supposed to do the exercises </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> OK </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. The lecturer takes his time to explain concepts 
2. The lab manuals are well laid out </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The quiz
The project </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> topic one and two </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The group work makes it fun and engaging
The lecturer manages time well, classes end in good time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The group project
The way everything is organized </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Its good that you keep pushing us .... Thats what amazes me in this unit </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Content delivery
Quizes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is very organized, the assignments, labs and group work
The concepts are understandable </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Explaining being explained in steps by the lecturer. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Learning new things.
We do most of the work ourselves so we learn while practicing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lecturer explains everything to the tea </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> . </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer is always punctual
The learning is efficient </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lecturer </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Fun </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. I like it 
2.Good lectures </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is very interactive and fun 
I get to learn new skills based on different perspectives </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1.Very well explained
2.Interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is very practical
Feedback is relevant and on time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The practicals
The teamwork </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the detailed explained slides and the time taken to make sure everyone understands </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The unit is really involving which is good 
The unit is interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The clear outline of the work
The practical examples </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The applicability of the unit in modern world </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the labs and quizzes which check on our progress </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like how the lecturer explains the concepts clearly and logically
I like the fact that the lec is always ready to explain unclear and ambiguous concepts </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Well Organised, Interactive </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer and what is being taught </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Use of real world examples. 
And Use of structured design and logical thinking </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Learning new skills
Learning problem solving </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Practice is very important for the long run, Database is very broad </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The explanation is simple and easy for me to understand.
The class is involving by asking questions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> it is mostly practical </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the lab exercises are engaging if one is committed to them.

the extensive use of the GitHub repositories and the other database tools are equipping with practical database experiences </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Simple </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> - </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i.) Classes start and end on time
ii.) Lab practiclals are interractive and are fun to do </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The topics are well explained and to one's understanding and learning the topics are interesting as compared to labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the clarity that is offered and the avaliability of the lecturer </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> He is very organised
He is patient when it comes to explaining </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> simplified mode of teaching
proper organization of content </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. Well organized work plan
2. Good amount of work load given </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is very practical and well detailed </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the quizzes that are given out after each concept are really helpful </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Everything is well outlined and oranised
he explains the concepts in a good way </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> How the lecturer organises his work so its easy to find the material that you need </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The practical interaction with the content
The methods of checking content retention </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The organisation of the lecturers materials 
The feedback given and the ability to track progress </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is giving me more ideas and knowledge 
It is helping in my oral skills </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The way the concept is taught with like the examples that are understandable </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The quizes offered really help in summarising the topic 
The lab work manual is simple and easy to follow </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The group work given by the lecturer helps in my understanding of the concept better
The quizzes done after every concept which helps me in reminding myself on the concept </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. The lecturer is very organized and teaches the content well.
2. Resources and materials required to take on this unit are readily available. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The group gave me idea on how to apply the concepts in real life </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The hands-on practicals.
The lab manuals. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the lecturere...He is wonderful and fair </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the practical aspect of the unit 
I like how we explore different aspects of the database </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. I enjoy the content and lectures in general
2. I like the labs and the manuals are helpful for understanding </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the ability to engage in critical thinking and group participation </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> group work and the quizes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The teacher know how to explain the theory parts </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the amount of group work that we're given because during the undertaking of the work, I get to learn new concepts.
Watching supplementary videos online. Some of the videos explain the content in a simpler way. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Topics well developed
Able to ask questions freely </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer's teaching style is interactive </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is well explained 
Lecture tutors well </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> We are first taught then we do practically which is really helpful 
The lecturer responds to those who have not understood.He takes time to teach certain concepts </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It’s engaging and the lab works make it much more interesting. In the few past weeks, I’ve learned a lot more than I learned in the past semester. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Helps in thinking critically about data management. Additionally the collaborative projects foster teamwork and problem solving skills. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the organization </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Mode of delivery, </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It's good </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It's engaging 
It is practical hence keeping you on your toes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I am able to solve real world problems
I am able to logically think </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> #NAME? </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer ensures that he has expounded on the topic of the day
The lecturer asks questions that engage the class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer explains the concepts in detail before the lab exercises.
The lecturer is ready to help whenever a challenge arises when doing the lab manuals in class. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The group work concept
The lecture is always ready to explain a concept you’ve not understood </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. The teaching methods the lecture always make sure that every student has understood.2. The learning environment . </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I'm enjoying the unit so far </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lab works are educative and creates innovativion </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> how it is interactive 
the group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is very practical so it really helps with hands on skills
Content is clearly broken down and understandable </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the topics are well detailed, explanation is well given </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is mostly practical. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It requires me to be more active and keen </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lec
The content </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> very interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Many quizzes help understand </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The notes are comprehensive and the methods of evaluation are effective </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> practically done </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1: It has group based activities.
2: Some business concepts are involved. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Teaching methods
Venue </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Classes start and end on time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Well organized, clear explanations </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1.Good lectures
2.Friendly lecturer </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The Lecturer is considerate(available for consultation and what not) </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer involves students in answering questions during lectures which keeps them attentive 
The lectures are light and easy to understand making them enjoyable </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The quizzes at the end of each concept help me to remember things 
The group work is really helpful </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. It is easy to understand.
2. It enables me to earn more marks in coursework. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> course delivery materials and the lecturer is organized </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like how time is kept </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Good feedback 
Step by step guidelines </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Punctuality of the lecturer </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> interactive learning experience
notes are clear </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Use of groups 
Use of quizes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The concept </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is interactive and knowledge based </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The concept of containerization and using of docker and Dbeaver </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> ive learnt how to run diffrent containers on dbeaver as well on my vscode ranging from python, php e.t.c </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Time management,  punctuality </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Quiz after every concept </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the way that like deliver the contents and gives us a lot of labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The hands-on approach in this unit, especially with using tools like MySQL and Docker, has been really beneficial.
 I appreciate the collaborative aspect of this unit, especially through GitHub and other group assignments. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the involving labwork
I like how groupwork enables me to learn from my friends </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is more practical than theoretical 
The fact that we have all the topics before class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The content </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The quiz after every major topic </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Notes are provided and the quizes are helpful </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like how we have quizzes at the end of each session and also the way the teacher is always available </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The group work on github and also class and the quizzes after class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the mode of teaching the lecturer offers, he is well organized and orderly in the way he presents his materials and notes in class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> fun </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like that the lecturer is on point and brief and the group based assignments </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The teacher is very intentional. The knowledge acquired is very deep. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Time management and reading materials </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer is easy to reach
The lecturer is willing to help </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> containerization concept </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i like the method of teaching
the lecturere is good and calm </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The teacher is very responsive
The unit is delivered at the students pace </td>
  </tr>
</tbody>
</table>

\newpage

### Wishes

The raw data of the wishes is as follows:

<table class="table" style="margin-left: auto; margin-right: auto;">
<caption>Write at least one recommendation to improve the teaching and learning in this unit (for the remaining weeks in the semester)</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Comment (Wishes) </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Extend deadlines for labs. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More code explanation </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lab manuals are nit straight forward </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To allow quizzes to be done outside class time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Introduce breaks in between the lessons </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Be a bit flexible on the lab submissions to enable catching up </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> In addition to the quizzes we have, more quizzes that don't have an impact on coursework </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More group related working </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> recommend you slow down the pace of teaching and please be more engaging with the class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Null </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer should share with us more online resources, mostly videos, to help us easily and quickly internalize some of the complex concepts. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To repeat what we have learnt previously </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Easier labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> more deadline on lab submissions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> After every topic we hope to get at least  a summary of if </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Added time to do lab work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> teaching more theory </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I wish the balance between group and individual work was better as there is way more group work than individual and i personally learn best myself </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer could introduce breaks in the middle of the class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> reduced group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Requesting the lecturer to be sending us like reference videos which we can use to like expand froma what he has taught or like a video that can help one understnd more on what he has taught </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> to slow down abit </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To reduce the speed at which some of the concepts are covered. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> making sure everyone is not left behind </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I would recommend that you show us why and how they are applied in real-life by giving out   real based examples or one of your projects as an example just to help us know how they are implemented. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More quizes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More time on labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Having reasonable submission time, given the hefty timetable this semester. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Be clear on the topics being tested and consider we have other units other than this one so we have enough time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1.Group work should be marked according to the work done by each member seeing as there some members don't participate in group work
2. Could we also have a break mid lesson </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More labs to emphasize in the different concepts </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More time should be allocated to finish up the quizes and the projects </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lecturer to go at a moderate speed </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> #NAME? </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Keep updating  the knowledge </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Give us breaks. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Adequate time for lab submissions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More quiz </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the lab lecture slides </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I am content </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Review of quizzes and labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Yes pushing us is good but it would be better if we go a bit slowly </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More quizzes
A deeper explanation on lab manuals </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> more revisions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Increasing deadlines for submitting the lab works. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Explain things in an easier way to understand </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More fun engagement </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Allocate more time for the lab assignments </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Everything is okay </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Less work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> clear notes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> more time for submission </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> We should engage more with the lecturer </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Extended duration of time for lab manuals group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The unit is fine for me. I am content with everything the lecturer has done so far to make our life studying this unit easier </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Class participation </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I recommend maybe re evaluating the quizzes as already it's a lot to handle with labs we do and the documentation, considering we also have other units it proves difficult to always be at par with you. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The class should be made more lively </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> . </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lab time submittion should be extended </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i think its going okay </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> A little bit more time on labs deadline </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More time added to submission time for work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Peer review </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Remind us the relevant concepts of Database 1 and not assume that we know </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> some more time for the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> emphasis on ensuring students are clear about the course outline and the amount of commitment it requires before hand </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Timing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> - </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To carry out lab practicals with students during class so we can easily identify errors together and move as one unit. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Explain the  lab processes much better and slower for one to understand </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More group presentations </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturers tone. To project his voice abit more. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer should add us more time to work on the projects and labs since there is a lot to be covered but the time is too short
 The lecturer should not assume that we know certain things mostly during the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More individual exercises </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I would request that the labs be doen if possible at a slower pace </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> time allocated for the project should be increased </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Extending the lab submission times
Better elaboration on the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> As he marks the labs, he should include comments on what about your work is outstanding or missing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Grading criteria sharing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More recaps on some concepts of the database 1
Recaps on the material where we did by ourselves to understand the reasoning behind the grade </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Give us time to finish the lab works </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Explain better how the lab work and the projects are intergrated it's a bit confusing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> give us more time to finish the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The engagement of the lecturer </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Find a way to make sure each group member participates and not just get carried by other group members as well as measures to ensure each student is on board with what is happening and not lost. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To give us more time for the lab work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Reduced group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> A better way for helping those left behind with the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Some of the steps in the Lab rarely execute correctly. Can you kindly once in a while go through the lab step by step </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I would prefer if we could do the labs individually since working in groups is a little stressful and one person mostly does the work (in my experience) however I understand if that would not be possible </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> engagement in group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> more group presentations </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> A better follow up on the lab manuals </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More recommendations on the youtube videos </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Moving at a moderate pace rather than fast pace </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Extended time frame to submit project and labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lecturer explain better on lab works </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Kindly give us enough time to do the group work .. not teaching on Friday and work is due the next day </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I wish we learn more about transactions. And also how to deployments of databases/containers. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Allow us to be able to correct our labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Same time as the other groups to complete our work. We usually get less time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Not to rush to finish the syllabus take time to make sure we (the students)we understand </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Increase of assessment deadlines </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Give atleast 3-4 days for the lab work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To go slow on the labs since one can easily be left behind </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Maybe adding case studies to the learning process </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I have no recommendations. The learning and teaching methods are satisfactory </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More topical quizzes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Kindly extend the deadlines for lab submissions. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The submission time should be increased </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To improve the lab’s explanation </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> class interaction </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer needs to be audible enough </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> longer work extensions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> none </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> more practical examples during teaching </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Basing the quizzes on Advanced database systems unit </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Notes on each topic </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> NONE </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Nothing lol </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Try and influence students to participate on their own </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> . </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More jokes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Kindly place the deadline for labs at night cause during the day we busy </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Longer time before labwork submissions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More submission time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> idk </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lectures should have creative ways of teaching the students </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To have a more active class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Reduce the workload. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> . </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I recommend the time for lab works to be longer </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The group lab submissions should have adequate time to enable each student to understand the content well </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Increase time for quizes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> incorporate examples that apply to concepts being taught </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer should select group members instead of student selecting themselves </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Increase submission time for lab work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More time for labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Avoid skipping most of the steps in lab work it makes following hard and also easily lost </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> one on one regular checkups since some of us may be stuck but we are kind of shy to speak up but are willing to ask for help </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Increase time in completing quizzes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Teach concept twice before we do the lab </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> making sure that  everyone are able to do labs and assignments </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> To host guest lectures or webinars featuring industry professionals who specialize in advanced database management. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> submission leniency </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Have breaks at the middle of the class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lecturer should make the group for us </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The teaching is excellent </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> You can try being audible </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Deadline for submission </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None, he is perfect so is the class </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> clear notes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I have no recommendation to give at the moment </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More explanation of concepts </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> yes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> A document compilation of all the quizzes and answers </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lab steps have difficult errors to debugg i need help </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i request hte lecturer to give deeper understanding of the unit itself coz i enjoyed during the first 2 weeks and now i just feel lost. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Make it as understandable as possible </td>
  </tr>
</tbody>
</table>
