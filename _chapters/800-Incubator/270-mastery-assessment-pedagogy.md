---
title: Mastery Assessment Pedagogy
slug: mastery_assessment_pedagogy
---
## Intent
Elegantly combine backward design with mastery learning for skill-based courses.



## Problem
Students will perform better and study more effectively if there is a crystal clear connection between the learning objectives and the assessments and if they are given a generous number of times to demonstrate full mastery for each objective.



## Solution
The key idea is to clearly specify about 40 learning objectives in enough detail that their mastery can be tested by a single challenging open response answer. We call these skills to emphasize that they are very specific and assessible learning objectives. 

Then each week give a comprehensive in-person proctored paper exam with one question for each skill that has been covered. The student answers are graded pass/fail with minimal feedback. If the student demonstrates mastery of a skill, then they no longer have to answer questions for that skill. If they don't then they can answer a different question for that skill the next week, and the next, and the next until the end of the semester. Students typically fail on their first attempt at a skill more than half of the time.

The instructor needs to 
* create the fine-grained list of learning objectives (called skills)
* create a problem bank with at least 3-12 problems for each skill (depending on how late it is introduced in the 13 week semester)
* create an exam each week with one new question for each skill that has been covered so far
* print out personalized exams for each student with their name and only the problems for skills they haven't mastered
* grade the problems with binary grading where they pass only if they have demonstrated full mastery (up to the level expected in the course) for that skill. This usually takes 2 hours with 1 grader for each 15 students.
* update the mastery table which shows which skills each student has mastered
* inform the students of their current level of mastery
* Assign final grades as a monotone function of the number of skills they have mastered.

For faculty just starting out they could give just 2 or 3 exams (similar to midterms and a final)
but with each exam containing a makeup for questions misssed on previous exams. By gradually increasing
the number of exams (and decreasing the number of new questions on each exam), the course can transition
over a few years into a fully implemented model with weekly exams.


## Applicability
This play works well when there are a clear set of skills that the course is designed to teach.

It also works best with a premade skill list and problem bank for that skill list, or with a teaching team
that is able to work collaboratively to build that skill list and problem bank.

It also requires that students have a 2 hour scheduled proctored exam each week, even though most students will stay under an hour and many for just a few minutes.

_Every play involves tradeoffs, and this is the spot to describe them and
explain when this play is a good idea or works, and when it might not
be applicable or might be harder to use. Answer the question of: "In what
contexts should we use this play?"_


## How to Implement

These steps can all be done by hand and we have done this by hand for a few courses. It requires keeping a list of skills and a folder for each skill containing the problems for that skill. 

The standard practice is then to create a folder for each quiz containing problems for each skill introduced so far, and removing those skills from their original buckets so they aren't duplicated on future exams. We currently write the skills in LaTeX.

One then needs a script that takes an excel sheet showing the skill mastery of each student and the folder of skill-based problems, and generates a personalized pdf exam for each student in the class. 

Next one needs a way to grade these with binary grading, tools like Gradescope or Pensieve could be used, and the result is used to update the skill mastery excel sheet for the class. 

It is much easier to do all of this with an app. We have developed the [Mastery Learning App (MLA)](https://github.com/tjhickey724/MasteryLearningApp) to handle all of the bookkeeping needed to teach this kind of course. It also has a cloud implementation that allows faculty to share skills and skill lists, and to share skill-based problems. 

Given a comprehensive skill list and problem bank, each weekly exam can be created and sent to the printer in 15-20 minutes and the exam can be graded in about 2 hours with 1 grader for every 15 students.

The app allows instructors to share skills and share problem libraries, so this incentivizes collaboration among
faculty to build these artifacts.


## See Also

_List any other related plays here as a bullet list of chapter links.
Then remove this text._


## Source

Source: ["M.A.P. — Mastery Assessment Pedagogy for Learning Computer Science"](https://www.proquest.com/openview/908ec01bbc9600eb77f75795e9966bd5/1.pdf?pq-origsite=gscholar&cbl=18750&diss=y)
Computer Science PhD Dissertation by Ella Tuson, Brandeis University August 2024.

Described by: Tim Hickey and Ella Tuson



## References

* The Mastery Learning App,
Timothy Hickey & Ella Tuson
SIGCSE 2025
https://doi.org/10.1145/3641555.3705053
* Grading for Equity in a Hyflex Compiler Design Course,
Fatima Abu Deeb & Ella Tuson & Timothy Hickey
SIGCSE 2025
https://doi.org/10.1145/3641554.3701835
* Mastery Learning with Specs Grading for Programming Courses
Ella Tuson and Tim Hickey
SIGCSE 2023
https://doi.org/10.1145/3545945.3569853
* Mastery Learning and Specs Grading in Discrete Math.
Ella Tuson and Tim Hickey
ITiCSE '22. https://doi.org/10.1145/3502718.3524766



## Community Discussion

Community members are free to comment on, ask questions about, share
experiences, or otherwise contribute to knowledge about this play by
posting comments below.
See {% include chapter-link.html slug="join-discussions" %} for details.

* Insert a comment here.
