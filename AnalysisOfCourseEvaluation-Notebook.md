---
title: "Mid-Semester Course Evaluation Results"
# author: "Allan Omondi"
# date: "2023-11-27"
output:
  html_document: 
    toc: yes
    df_print: kable
    fig_width: 8
    fig_height: 8
    fig_caption: yes
    toc_depth: 4
    keep_md: yes
    css: CSS_Chunk.css
  html_notebook: default
  pdf_document:
    toc: yes
    number_sections: yes
    fig_width: 8
    fig_height: 8
    fig_caption: yes
    keep_tex: yes
  always_allow_html: true
  word_document:
    toc: yes
---

+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Course**                                                                              | Business Intelligence II                                                |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Course Code**                                                                         | BBT4206                                                                 |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Class**                                                                               | BBIT 4.2                                                                |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Semester Duration**                                                                   | 21^st^ August 2023 to 28^th^ November 2023                              |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Date of Evaluation**                                                                  | 25^th^ September 2023 to 4^th^ October 2023\                            |
|                                                                                         | (Week 6 & 7 of 14)                                                      |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Total number of students who submitted the course evaluation**                        | 102                                                                     |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Total number of students registered in the AMS at the time of the course evaluation** | 115                                                                     |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Response rate**                                                                       | 88.69%                                                                  |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **e-Learning URL**                                                                      | <https://elearning.strathmore.edu/course/view.php?id=6599>              |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Data collection tool URL\                                                             | <https://elearning.strathmore.edu/mod/questionnaire/view.php?id=221958> |
| (for access to the raw data)**                                                          |                                                                         |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Lecturer**                                                                            | Dr Allan Omondi \<aomondi\@strathmore.edu\>                             |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+

------------------------------------------------------------------------











# Course Evaluation Score

Mean Course Evaluation Score = 4.3770 / 5

Percentage Mean Course Evaluation Score = 87.54%

Median Course Evaluation Score = 4.3636 / 5

------------------------------------------------------------------------







\newpage

# Quantitative Data Analysis

## Course Evaluation Scores per Group



The **"Average Course Evaluation Rating"** variable in the plot below indicates the score **per group** with a baseline of 4/5.

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/VisualizationsForCourseEvaluationResultsperClassGroup-1.png)<!-- -->

\newpage

The **"Average Course Evaluation Rating"** variable in the plot below indicates the score **per gender** with a baseline of 4/5.

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/VisualizationsForCourseEvaluationResultsperGender-1.png)<!-- -->

\newpage

The plot below presents a drill-down of the class group into **regular and exempt** students:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/VisualizationsForCourseEvaluationResultsperGroup-1.png)<!-- -->

\newpage

## Correlations



The specific correlation values are presented below:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/CorrelationMatrixWithFigures-1.png)<!-- -->

### Interesting Correlations

The following are hypothetical statements given that "correlation does not imply causation".

-   **.73 correlation** between "I am developing my oral and writing skills" and "I am developing my reflective and critical reasoning skills": *Consider writing as formalized thinking.*

-   **.71 correlation** between "The assessment methods are assisting me to learn" and "I am developing my reflective and critical reasoning skills": *The more effort students put into the assessment, the more they develop their reflective and critical reasoning skills.*

-   **.67 correlation** between "I am enjoying the subject" and "I am developing my reflective and critical reasoning skills": *The more a student enjoys the subject, the more they consider their reflective and critical reasoning skills as developing.*

-   **.65 correlation** between "The assessment methods are assisting me to learn" and "I am enjoying the subject": *The more interesting/challenging the assessment methods, the more students enjoy the course.*

-   **.63 correlation** between "Labs that require you to use Git to work in a team" and "Labs that require you to put in effort to make a submission related to the content of the lab": *The more students appreciate the use of Git for working in teams, the more they appreciate labs that require a submission to be made.*

-   **.62 correlation** between "The subject content is delivered according to the course outline and meets my expectations" and "The topics are clear and logically developed": *The more the course outline is followed, the clearer and more logically developed the topics are.*

-   **-.32 correlation** between "Concept 1 of 4 - Ensemble Methods for Predictive Analytics" and "Absenteeism": *Students who started the semester late (high absenteeism), had a harder time understanding concept 1 which was covered at the beginning of the semester.*

-   **-.36 correlation** between "I use the e-learning material posted" and "absenteeism": *The higher the number of classes missed, the lower the student's engagement with content posted on e-learning*

(1) A **.73 correlation** between "I am developing my oral and writing skills" and "I am developing my reflective and critical reasoning skills":

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/DrillDownCorr1-1.png)<!-- -->

(2) A **.71 correlation** between "The assessment methods are assisting me to learn" and "I am developing my reflective and critical reasoning skills":

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/DrillDownCorr2-1.png)<!-- -->

\newpage

### Absenteeism Percentage

The lower the absenteeism, the more a student makes use of the e-learning materials posted. And the more a student makes use of the e-learning materials posted, the higher their overall grade in the course.

With this in mind, a further investigation of the **absenteeism percentage** is presented below.

#### Absenteeism by General Class Group

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/AbsenteeismBoxandWhiskerGroup-1.png)<!-- -->

#### Absenteeism by Specific Class Group

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/AbsenteeismBoxandWhiskerSpecificGroup-1.png)<!-- -->

#### Absenteeism by Gender

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/AbsenteeismBoxandWhiskerGender-1.png)<!-- -->

\newpage

# Qualitative Data Analysis























## Sentiment Analysis (Lexicon-Based)



The "likes" refer to the answer to the question, "Write two things you like about the teaching and learning in this unit so far." The sentiments expressed through the "likes" are:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/OverallSentimentForLikes-1.png)<!-- -->

The "wishes" refer to the answer to the question, "Write at least one recommendation to improve the teaching and learning in this unit (for the remaining weeks in the semester)." The sentiments expressed through the "wishes" are:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/OverallSentimentForWishes-1.png)<!-- -->

\newpage

Chord Diagram of Likes per Class Group:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/ChordDiagramLikesPerGroup-1.png)<!-- -->

\newpage

Chord Diagram of Likes per Class Gender:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/ChordDiagramLikesPerGender-1.png)<!-- -->

\newpage

Chord Diagram of Wishes per Class Group:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/ChordDiagramPerGroup_Wishes-1.png)<!-- -->

\newpage

Chord Diagram of Wishes per Gender:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/ChordDiagramPerGender_Wishes-1.png)<!-- -->

\newpage

## Topic Modelling (Latent Dirichlet Allocation (LDA) based)

The goal of topic modelling is to identify latent (hidden) terms (topics) in the students' course evaluation textual feedback. In this case, a topic is a mixture of words and a student's textual feedback is a combination of one or more topics (mixed-membership model).





The 2 topics for the "likes" (as guided by the LDA model) are:

1.  Topic 1: Well-Explained Lectures

2.  Topic 2: Interactive and Practical Labs

3.  Topic 3: Learning Practical Skills

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/visualizations_for_likes_topic_modelling-1.png)<!-- -->

\newpage

The 5 topics for the "wishes" (as guided by the LDA model) are:

1.  Topic 1: Reduce the Amount of Content

2.  Topic 2: Allocate More Time for the Labs

3.  Topic 3: Lenient Deadlines

4.  Topic 4: Recommend Professional Certifications

5.  Topic 5: Help when Stuck in Technical Labs

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/visualizations_for_wishes_topic_modelling-1.png)<!-- -->

\newpage

# Appendices

## Appendix A: Full Names of Variables

The following variables have been renamed to fit the correlation plots:

-   \`A. Enjoying Subject\` = \`Q02_General Questions-\>A - 1. I am enjoying the subject\`,

-   \`B. Classes Start-End\` = \`Q02_General Questions-\>A - 2. Classes start and end on time\`,

-   \`C. Learning Environment\` = \`Q02_General Questions-\>A - 3. The learning environment is participative, involves learning by doing and is group-based\`,

-   \`D. Content Delivery\` = \`Q02_General Questions-\>A - 4. The subject content is delivered according to the course outline and meets my expectations\`,

-   \`E. Clear Topics\` = \`Q02_General Questions-\>A - 5. The topics are clear and logically developed\`,

-   \`F. Oral and Writing\` = \`Q02_General Questions-\>A - 6. I am developing my oral and writing skills\`,

-   \`G. Critical Thinking\` = \`Q02_General Questions-\>A - 7. I am developing my reflective and critical reasoning skills\`,

-   \`H. Assessment Methods\` = \`Q02_General Questions-\>A - 8. The assessment methods are assisting me to learn\`,

-   \`I. Relevant Feedback\` = \`Q02_General Questions-\>A - 9. I receive relevant feedback\`,

-   \`J. Read Recommendations\` = \`Q02_General Questions-\>A - 10. I read the recommended readings and notes\`,

-   \`L. eLearning Material\` = \`Q02_General Questions-\>A - 11. I use the eLearning material posted\`,

-   \`Understood Concept 1\` = \`Q03_Level of Learning Achieved-\>B - 1. Concept 1 of 4 - Ensemble Methods for Predictive Analytics\`,

-   \`Understood Concept 2\` = \`Q03_Level of Learning Achieved-\>B - 2. Concept 2 of 4 - Predictive Modelling Using R\`,

-   \`Teaching - Labs\` = \`Q04_Quality of Teaching Strategies-\>C - 1. Labs with comments that describe each step to be followed\`,

-   \`Labs with Submission\` = \`Q04_Quality of Teaching Strategies-\>C - 2. Labs that require you to put in effort to make a submission related to the content of the lab\`,

-   \`Git in Teams\` =\`Q04_Quality of Teaching Strategies-\>C - 3. Labs that require you to use Git to work in a team\`,

-   \`Solo Labs\` = \`Q04_Quality of Teaching Strategies-\>C - 4. Labs that require you to work alone\`,

-   \`Quality of Lectures\` = \`Q04_Quality of Teaching Strategies-\>C - 5. The quality of the lectures given (quality measured by the breadth (the full span of knowledge of a subject) and depth (the extent to which specific topics are focused upon, amplified, and explored) of learning - NOT quality measured by how fun/comical/lively the lectures are)\`,

-   \`Recordings of Classes\` = \`Q04_Quality of Teaching Strategies-\>C - 6. The recordings of online classes\`,

-   \`Online Classes\` = \`Q04_Quality of Teaching Strategies-\>C - 7. Online classes in general\`,

-   \`Physical Classes\` = \`Q04_Quality of Teaching Strategies-\>C - 8. Face-to-Face classes in general\`

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
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is interesting and helps improve coding skills </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> it is very detailed hence of great helpIt is interactive both in the unit and in regards to other units such as IS project II </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;">  Ensemble Methods for Predictive Analytics   Predictive Modelling Using R  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Interactive </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The concepts are well explained  Communication is effective  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is a bit more practical due to the use of python and r  The instructor is well organized and the teaching methods are useful </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is practical and based on modern concepts  The labs are interesting and thought provoking </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like that the labs are practical  I like being given enough time to do the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Everything is good </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is interesting and interactive since we get to use different tools in our sessions. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> So far its been a hard unit and fortunately the teaching style for the lecture is helping as he guides us along  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lecturer is efficient  classes start and end on time </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Increase submission deadline  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The practical labs are engaging hence skill development   the teaching method and lectures  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. It is comprehensive  2. It is interesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is step by step    </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> - The content is really engaging and intense and shows that learning is there.  - Also additional hands on skills like using GitHub and collaborations which plays a huge role in the personal development goals in the digital space.  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Interactivity and applicability of the unit </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The online classes  The Labs that require submissions help me to dig deeper. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The practical examples and labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The unit is very practical which helps me in the long run.  The lecturer does not leave anyone behind, ensures everyone has understood the concept </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Work is clearly and easily broken down  The lecturer is very available for consultation </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The teaching for this unit has been very comprehensive so far and engaging with the lecturer.  The learning implements group works. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Learning to use GIT  Being taught practically and through walk-throughs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The step by step explanation of the concepts is very helpful  The time to complete the labs is sufficient  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lec takes his time to teach the concept </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Detailed Explanations.  Quick feedback by lecturer. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The labs are guided and help to learn  The lecturer is willing to repeat explaining areas of less understanding </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer is readily available to help when one is stuck  The unit is well structured and organized </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Very in depth  Very practical </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Its practical and has interactive learning  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is interactive   It is engaging </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer does everything in his power to ensure we are comfortable with content being taught and make sure we are following along together. The e-learning site is also very well organized and categorized for this unit </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Answers the questions asked  Explains well </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Patience and flow </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> mode of delivery  Information </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The mode of delivery   The assistance of reference links put on elearning for easy reference  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer ensures everyone understandsThe labs are fun </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer ensures everyone has understood.  It is practical. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The explanations to the various concepts are well explained  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the labs sessions are nice </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i like the group labs  i like the topics </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I find it current industry oriented </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer provides adequate feedback on the questions asked.  The lab work clearly elaborates on the work taught. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer explains the content really well. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Takes time to organize his work, I appreciate the effort </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> So far so good  The lecturer is very clear </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is comprehensive  It is easy to follow </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Labs that describe each step to be followed are engaging and learning enables me to follow through the lab properly  It is very engaging and interactive. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer asks questions  The lectures are clear  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Interactive  Interesting  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The content is very well delivered. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The assistance by the lecturer, the practicality </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lab work  Class sessions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;">  It is very participative and lecturer gives room for questions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> feedback is quickLecturer is willing to help </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Working as a team </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the fact that we get to do the lab work in groups   the interactive online and on campus classes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like how the Lecturer explains the concepts and takes us through the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The concept are explained very well  A chance to learn R I have wanting to interact with R and data </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> very interactive and hands on </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> on hand Practice  Good delivery </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It’s interactive and very logical. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The technical aspect of the unit.  The attentiveness to detail when it comes to the labs and concepts are clearly explained. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i like the templates that come with the labs   i like the fact that we draw references from real world scenarios  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Wide scope of content  Practicability </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Once you follow the steps for the lab you will be okay.  The lecturer helps in one on one for the labs if one has an issue </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The attention to detail when explaining the code. It makes it easier to understand  Having practical labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the way the topics are broken down very logical and easy to understand.  I like that we are constantly able to ask questions and be answered regardless of the nature of the question. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lectures </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Its Good </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the lecturer  the lectures </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lecturer, Teaching method </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like this ui=nit because it prompts me to think actually think and connect the dots  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Well explained content </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Gaining R skills </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Use of realistic  code  group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> practicality  Engagement </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Group Labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> its straight forward and simple to understand  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like the practicality of R and learning github in depth through the group work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Group workPractical Exercises </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The learning of this unit is good in terms of the detailed and step by step practicals shown by the lecturer for each lab.The recordings. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The teaching is very thorough and labs have well explained instructions. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I like that it challenges me to apply everything practically. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The practical aspect.  The group work is good. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Labs activities, Quizzes help a lot on learning during the semester </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> clear and direct to the point   step by step teaching works for me </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The lecturer explains everything in detail and caters for both ides that is vscode and rstudio </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Systematic  Modular </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> How to use and implement R as a language for data analysis </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I am learning to use new language, R language, and how to use it together with the available libraries for predictive analytics.    </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Its practical  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> none </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is very practical and a good example of a prospective career path for many. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. The lecturer makes the content easy to understand </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the teaching method  the recording being online is also helpful  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The practicals </td>
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
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> none </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i would like if the concepts were divided where we learn the functions first online then do the practicals of it in person </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Flexibility </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I don't have any  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Leniency with regards to lab work submission and future project work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More tutorials based on the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Use of less complex datasets </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i have no recommendations </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> A guide to help us counter different problems like installation of packages during labs. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I would like lab exercises to be done more in class so as to easily understand  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lecturer might be a bit fast at times </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Step by step materials/videos on how to do the lab works  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> student involvement   </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> 1. Nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Go easy on us abit, it is te last semester </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> - To give us insights or recommendations about certifications that we can as well do, related to this unit which will boost our C.Vs for the interested students.  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> A bit more tutorials on technical errors such as ones on knitting and rendering the markdown files </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> If the concept requires many practicals, the classes should be more online. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> For the physical class to be moved to a lab </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Being more lenient with lab work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Everything is okay so far. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Sticking to a specific application to be used </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> No recommendation at the moment </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The content is too broad and covers a lot i.e new softwares which make the unit overwhelming. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More teamwork collaboration in labs. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It would be better if the physical classes were being recorded because at times one might be behind or missed an important lab step    </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> No recommendations </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Make the course work less bulky and complex </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> no comment </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> n/a </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Too much content to deal with </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> time liniency </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> That the labs should be given more time to them  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Breaks in between classes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Nothing. I am enjoying and understanding the course. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> increase more labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> the labs are quite hefty so it really makes the work easier to do in a group </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More engagement </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More time to be allocated in the lab work assignments. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I am content </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Reduce content  Reduce labwork </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> . </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Proper detailed explanation of the labs, rather than rushing through them quickly.
More time is needed for lab completion and progressive follow-up so the lecturer knows where you are stuck. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More time for labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> So far none </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> - </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Reduce the workload, its honestly too much </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More reference material  Breaks during classes at least 5 mins    </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None....The unit met my expectation and was delivered perfectly </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Avoid online classes </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Deadlines to be extended abit </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i am enjoying the unit as it is </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Since we are about to finish our 8.4.4 system. To give us more recommendation on certificates
and what the job market expects from us </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> better communication of activities btwn the students and the lec  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> . </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Ensure that the code work can work with any dataset and not fixated on provided dataset </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I would like there be more simpler labs with easier datasets to understands the concepts first then move on to more complex data handling and manipulation. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> i wish that that the lab assignments could be allocated more time, that they are marked towards the end of the semester     </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None so far </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Kindly share more reading materials and past papers. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Having more practical labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> I recommend that the deadlines on the labs be more flexible as there are many subject and projects running concurrently. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The labs are long, they are individually basically the same size as an entire same project </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> No recomendation </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> so far so good </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Greater in depth exploration into labs to ensure we're actually understanding what is going on. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> The content is so hard to understand and the lec solving other people's issues only bring more confusion to some of us.
I wish he would go through the content first then afterwards focus on individual problems </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> He is doing a good job </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Personally I use linux and its kinda hard for me   You can add some YouTube materials  </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Lab submissions still very confusing </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More online sessions </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> so far so good </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Adequate time for completing the labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> More group work, less individual work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;">  No recommendations there is good delivery. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Generally just slow down the amount of work we have to submit considering the IS project we need to work on </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> One recommendation may be to explain how these concepts can relate to and apply to our IS Project 2. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> It is okay. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> - Slide are very long (too much content) lecture can improve on that- </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> nothing really </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> There are many labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> Further work on ease of following the lab work </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> No comment, everything is fine </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> None </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> nothing all is well </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> reduce the workloads on the labs kindly </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> n/a. </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> so far I have been struggling a little with the Lab a bit but i'm hoping it will get better as we continue with the other labs </td>
  </tr>
  <tr>
   <td style="text-align:left;width: 35em; border-bottom: 1px solid;"> N/A </td>
  </tr>
</tbody>
</table>
