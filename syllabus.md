---
layout: single
title:  Syllabus
permalink: /syllabus
toc: true
toc_label: Outline
---

[Syllabus]: /syllabus
[Scala]: http://www.scala-lang.org
[Scala doc]: http://docs.scala-lang.org/
[SftI]: http://www.horstmann.com/scala/index.html
[SftIOberlin]: http://proquest.safaribooksonline.com/9780134540627?uicode=ohlink
[LIP]: https://pragprog.com/book/tpdsl/language-implementation-patterns
[DOET]: http://www.jnd.org/books/design-of-everyday-things-revised.html
[Schoology]: https://app.schoology.com/course/1448538421/updates
[Repo]: https://github.com/pioneer-dsl-2018
[Ben Wiedermann]: https://www.cs.hmc.edu/~benw
[Computer Science at Harvey Mudd College]: https://www.cs.hmc.edu

## About This Course

### Description

This course explores how to design a new programming language. In particular,
we’ll focus on "Domain-Specific Languages"—languages designed for people who
want to use a computer to perform a specialized task (e.g., to compose music, or
query a database, or make games). Through readings, discussions, and
programming, we'll investigate why and how you would create a domain-specific
language. The course also features a project that asks you to propose, design,
and implement your own domain-specific language.

We'll also investigate questions about how Computer Science and programming
languages relate to society, including:

   - What counts as programming?
   - What counts as a programming language?
   - Who gets to call themselves a programmer?
   - How (much) does language influence thought?
   - How do we make software that other people will find useful?

This course follows a "studio model", where all work-in-progress is made public,
and we rely on each other's critiques to improve our work. Sample solutions are
published at the beginning of the assignment, you'll often work in teams, you'll
have access to everyone else's work throughout the assignment, and every
assignment has a peer-review component. 

### Learning Objectives

This course has two broad aims, each with specific objectives:

**Aim 1:** To familiarize you with the purpose, design, implementation,
specification, and evaluation of domain-specific languages.

*Objectives:*

-   Compare and contrast the benefits and drawbacks of a domain-specific
    language versus a general-purpose language.
-   Analyze a domain and identify its semantic model(s) and linguistic
    abstractions.
-   Design language-based user interfaces.
-   Evaluate language design choices.

**Aim 2:** To give you the opportunity to explore a wide variety of
high-level language-implementation techniques.

*Objectives:*

-   Identify the properties of a general-purpose host language that make
    it (un)suitable for implementing a domain specific language.
-   Explore, compare, and contrast techniques for implementing an
    *internal* versus an *external* DSL.
-   Learn to program in Scala.

Because DSLs are a powerful and flexible programming tool, we will
explore the topic systematically and broadly, building up concepts
and code that should be useful to you in your end-of-course project
and in your future studies and careers.

### Instructor
My name is [Ben Wiedermann]. I'm a professor of [Computer Science at Harvey Mudd
College], in Claremont, California. I research the design and implementation of
programming languages.

### Style and Approach
One of the things I want to explore in this course is design and the design
process: how do we make something that other people find useful? To answer this
question for a programming language, we'll take a studio design approach. 

In our studio, **all work in progress is made public** 
[[John Seely Brown](http://www.fastcodesign.com/1665654/4-lessons-the-classroom-can-learn-from-the-design-studio)].
Assignments, critiques, grading, and projects will be viewable by everyone in 
the class, all the time. Much of our work will be to comment on, critique,
improve upon, and be improved by one another.

## Resources

### Communication
All communication outside of meeting-times will be conducted on the Pioneer LMS
(Learning Management System), [Schoology]. As per the student agreement, use of
email to communicate with the professor mentor during the program is strictly
prohibited. If you have problems using the Pioneer LMS, contact your designated
Pioneer program manager.

Feedback is an important part of any learning. During this course I will
be asking you to give me feedback on your learning in implicit ways
(e.g., exercises and assignments) as well as explicit ways (e.g., "How's
the class going for you?"). This is *your* class, and I want to make
sure you get the most out of it. Please let me know right away when
something we discuss is not clear. If you don't understand something,
chances are that other people feel the same way. You are
always free to interrupt me — don't let me get away with glossing over
any topic. I also welcome any feedback about the structure, tone, and
nature of this course. I ask that you give me this kind of feedback
outside of class, via a message on [Schoology]. If you would
like to give me anonymous feedback, you can send [anonymous
email](https://www.wikihow.com/Send-An-Anonymous-Email).

### Materials

**Forum:** We'll use [Schoology's discussion forum][Schoology] to ask questions
about the course. I'll also post announcements there. You're required to keep up
with announcements on the forum. 

**GitHub repository:** All the assignments will live on [GitHub][Repo], where
we'll also comment on and critique each other's work.

**Scala:** During the part of the course, we'll be programming in [Scala]. We'll
    cover key parts of the language in meetings and assignments, and there are
    also lots of good online resources for [learning Scala][Scala doc].

**Books:** There is one recommended (but not required) book for the course. 

   - _[Scala for the Impatient][SftI]_ by Cay Horstmann. This book is a good
     reference for the Scala programming language, which we'll be using a lot
     during the first half of the course. I'll point out parts of the book that
     might be useful for particular assignments. It is available in the 
     [Oberlin online library][SftIOberlin].

## Collaboration

This course is highly collaborative: we'll discuss things as a group, and all
work-in-progress is public. Although everyone else's work (and often, the
solution) will be available at all times, you _must_ do your own work. You can
be inspired by others, but you should look at someone else's work only after
doing your own work. If you are inspired by someone else's solution, you can
_incorporate_ into your own, with attribution. Use your good judgement here. If
you have any questions about what's acceptable, please talk with me about it.

## Coursework and Grading

Your work in this course will be a combination of:

### Assignments (20%) 

We will have five assignments during the first part of the course (after that,
you'll be working on your project). The assignments will have reading, writing,
and programming components. Additionally, each assignment will have a "critique"
component, where you help evaluate someone else's work. Assignments will
typically be given out after a group meeting, with the submission due four days
before our next group meeting and the critique the day before the next meeting.

### Project (80%)

You will complete one large project that asks you to design, implement, and
evaluate your own domain-specific language. Though the project will be due at
the end of the course, I will provide milestones and guidelines throughout the
course, to help you stay on track. Each milestone is graded separately. More
details about each milestone and their due dates will become available when we
start working on the projects. For now, here is a brief description of each
milestone, roughly when it will be due, and how much each milestone contributes
to your project grade:

  - *Design notebook entries (10%):* You'll keep a notebook where you write and
    reflect on how your project is going. At least one entry will be required
    before each individual meeting.
  - *Critiques (10%):* You will write critiques of your classmate's work,
    throughout the project. At least one critique will be required before each
    individual meeting.
  - *Motivation for DSLs (10%):* A relatively brief paper about DSLs and why
    they are useful. This paper will be original, written by you, cite existing
    sources, and be based on the material we learn during the first part of the
    course. This paper will be due before our first individual meeting.
  - *Project description and plan (5%) + video-conference peer review (2.5%):*
    Your description of the project and your schedule for completing it. This
    milestone will be due before our second individual meeting. You will also
    meet with all the students in the class to discuss your projects and plans.
  - *Language design and implementation overview (10%):* A snapshot of your
    evolving design for your DSL and your strategy for implementing it. This
    milestone will be due before our third individual meeting.
  - *Prototype (10%) + video-conference peer review (2.5%):* A version of your
    DSL that others can use. This milestone will be due before our fourth
    individual meeting. You will also meet with all the students in the class to
    discuss your prototypes.
  - *Preliminary evaluation (10%):* Your assessment of how well your DSL matches
    its design goals. This milestone will be due before our fifth individual
    meeting.
  - *Final product (15%):* The last version of your DSL, for this course. This
    milestone will be due by the end of the course.
  - *Final paper (15%):* A document that describes and reflects on your project.
    It will incorporate, with modifications, many of your previous milestones.
    This milestone will be due by the end of the course.

Additionally, you'll be required to work with Pioneer Academic's writing center
throughout your project.

## Attendance / participation

This class—and your design process—thrive on open discussion and critique.
You're expected to attend all the required sessions and to participate by asking
questions, offering your thoughts, and participating in discussions. Much of
this work is built into the course and its grading (e.g., via the critiques);
however, grading penalties will apply if you consistently miss or do not
participate in sessions.

## Notices

### Rescheduling sessions
Group sessions cannot be rescheduled once confirmed by the student in writing.
If a student misses a group session, Pioneer will endeavor to make a recording
of the session available to the student. However, Pioneer cannot guarantee a
recording will be available due to occasional technical issues.

During the one-on-one sessions, a student can request up to two sessions be
rescheduled if he or she provides a written request to both Pioneer and his or
her professor with more than 48 hours notice before the meeting time. Cases of
student illness or other emergencies will also be considered with less than 48
hours notice. Once a student has altered two meeting times, he or she may not
alter other agreed-upon meeting times in advance of the meetings, regardless of
whether he or she continues to provide notice. 

### Technical support
For any technical issues relating to program software, the Pioneer LMS or the
Oberlin College library system that are not urgent, students should contact
their designated program manager. For all issues that require immediate
attention, message Pioneer Academics on WeChat. A Pioneer staff member will
respond to help resolve any problem quickly.

{% include research-resources.md %}
