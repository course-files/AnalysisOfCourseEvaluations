---
title: "Course Evaluation Results"
output:
  html_document: 
    toc: yes
    df_print: kable
    fig_width: 14
    fig_height: 10
    fig_caption: yes
    keep_md: yes
  html_notebook: default
  pdf_document: 
    toc: yes
    number_sections: yes
    fig_width: 12
    fig_height: 9
    fig_caption: yes
    keep_tex: yes
---

<style type="text/css">
table {
  border-collapse: collapse;
  table-layout: auto;
  margin: 0 auto;
}
th {
  border-bottom: 1px solid #000;
  padding: 8px;
  text-align: center;
  vertical-align: bottom;
}
td {
  border-bottom: 1px solid #000;
  padding: 8px;
  text-align: auto;
  vertical-align: middle;
}
</style>

+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| Key                                                                                     | Value                                                                   |
+=========================================================================================+=========================================================================+
| **Course**                                                                              | Business Intelligence II                                                |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Course Code**                                                                         | BBT4206                                                                 |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Class**                                                                               | BBIT 4.2                                                                |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Semester Duration**                                                                   | 21^st^ August 2023 to 28^th^ November 2023                              |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Date of Evaluation**                                                                  | 25^th^ September 2023 to 29^th^ September 2023\                         |
|                                                                                         | (Week 6/14)                                                             |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Total number of students who submitted the course evaluation**                        | 94                                                                      |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Total number of students registered in the AMS at the time of the course evaluation** | 115                                                                     |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Response rate**                                                                       | 81.73%                                                                  |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **e-Learning URL**                                                                      | <https://elearning.strathmore.edu/course/view.php?id=6599>              |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Data collection tool URL (for access to the raw data)**                               | <https://elearning.strathmore.edu/mod/questionnaire/view.php?id=221958> |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+
| **Lecturer**                                                                            | Dr Allan Omondi                                                         |
+-----------------------------------------------------------------------------------------+-------------------------------------------------------------------------+

------------------------------------------------------------------------











# Overall Course Evaluation Score

<table>
<caption>Overall Course Evaluation Score</caption>
 <thead>
  <tr>
   <th style="text-align:center;"> Mean Score </th>
   <th style="text-align:center;"> Percentage </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:center;"> 4.3839 </td>
   <td style="text-align:center;"> 87.6789 </td>
  </tr>
</tbody>
</table>
  Mean Score Percentage
1   4.383946   87.67892

------------------------------------------------------------------------







## Course Evaluation Scores per Group



The **"Average Course Evaluation Rating"** variable in the plot below indicates the score **per group** with a baseline of 4/5.

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/VisualizationsForCourseEvaluationResultsperClassGroup-1.png)<!-- -->

The **"Average Course Evaluation Rating"** variable in the plot below indicates the score **per gender** with a baseline of 4/5.

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/VisualizationsForCourseEvaluationResultsperGender-1.png)<!-- -->

The plot below presents a drill-down of the class group into **regular and exempt** students:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/VisualizationsForCourseEvaluationResultsperGroup-1.png)<!-- -->

# Correlations 

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

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/CorrelationMatrixWithoutFigures-1.png)<!-- -->

The specifc correlation values are presented below:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/CorrelationMatrixWithFigures-1.png)<!-- -->

## Interesting Correlations

The following are hypothetical statements given that "correlation does not imply causation".

-   **.73 correlation** between "I am developing my oral and writing skills" and "I am developing my reflective and critical reasoning skills": *Consider writing as formalized thinking.*

-   **.71 correlation** between "The assessment methods are assisting me to learn" and "I am developing my reflective and critical reasoning skills": *The more effort students put into the assessment, the more they develop their reflective and critical reasoning skills.*

-   **.68 correlation** between "I am enjoying the subject" and "I am developing my reflective and critical reasoning skills": *The more a student enjoys the subject, the more they consider their reflective and critical reasoning skills as developing.*

-   **.65 correlation** between "The assessment methods are assisting me to learn" and "I am enjoying the subject": *Students who value the assessments enjoy the subject more.*

-   **.64 correlation** between "Labs that require you to use Git to work in a team" and "Labs that require you to put in effort to make a submission related to the content of the lab": *The more students appreciate the use of Git for working in teams, the more they appreciate labs that require a submission to be made.*

-   **.61 correlation** between "The subject content is delivered according to the course outline and meets my expectations" and "The topics are clear and logically developed": *The more the course outline is followed, the clearer and more logically developed the topics are.*

-   **-.33 correlation** between "Concept 1 of 4 - Ensemble Methods for Predictive Analytics" and "Absenteeism": *Students who started the semester late (high absenteeism), had a harder time understanding concept 1 which was covered at the beginning of the semester.*

-   **-.36 correlation** between "I use the e-learning material posted" and "absenteeism": *The higher the number of classes missed, the lower the student's engagement with content posted on e-learning*

Below are the two most extreme (positive and negative) correlations:

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/DrillDownCorr1-1.png)<!-- -->

![](AnalysisOfCourseEvaluation-Notebook_files/figure-html/DrillDownCorr2-1.png)<!-- -->
