---
layout: single
title:  Syllabus
permalink: /syllabus
toc: true
toc_label: Outline
---

[Syllabus]: /syllabus
[honor code]: https://www.hmc.edu/student-life/student-handbook/standards-of-student-conduct-honor-code/
[Scala]: http://www.scala-lang.org
[Scala doc]: http://docs.scala-lang.org/
[SftI]: http://www.horstmann.com/scala/index.html
[SftIOberlin]: http://proquest.safaribooksonline.com/9780134540627?uicode=ohlink
[LIP]: https://pragprog.com/book/tpdsl/language-implementation-patterns
[DOET]: http://www.jnd.org/books/design-of-everyday-things-revised.html
[Schoology]: https://app.schoology.com/course/1448538421/updates
[Repo]: https://github.com/pioneer-dsl-2018

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

## Style and Approach
One of the things I want to explore in this course is design and the design
process: how do we make something that other people find useful? To answer this
question for a programming language, we'll take a studio design approach. 

In our studio, **all work in progress is made public** 
[[John Seely Brown](http://www.fastcodesign.com/1665654/4-lessons-the-classroom-can-learn-from-the-design-studio)].
Assignments, critiques, grading, and projects will be viewable by everyone in 
the class, all the time. Much of our work will be to comment on, critique,
improve upon, and be improved by one another.

## Resources

**Scala:** During the part of the course, we'll be programming in [Scala]. We'll
    cover lots of topics in meetings and assignments, and there are also lots of
    good online resources for [learning Scala][Scala doc].

**Books:** There is one recommended (but not required) book for the course. 

   - _[Scala for the Impatient][SftI]_ by Cay Horstmann. This book is a good
     reference for the Scala programming language, which we'll be using a lot
     during the first half of the course. I'll point out parts of the book that
     might be useful for particular assignments. It is available in the 
     [Oberlin online library][SftIOberlin].

**Forum:** We'll use [Schoology's discussion forum][Schoology] to ask questions
about the course. I'll also post announcements there. You're required to keep up
with announcements on the forum. 

**GitHub repository:** All the assignments will live on [GitHub][Repo], where
we'll also comment on and critique each other's work.

## Feedback

Feedback is an important part of any learning. During this course I will
be asking you to give me feedback on your learning in implicit ways
(e.g., exercises and assignments) as well as explicit ways (e.g., "How's
the class going for you?"). This is *your* class, and I want to make
sure you get the most out of it. Please let me know right away when
something we discuss is not clear. If you don't understand something,
chances are that several other students feel the same way. You are
always free to interrupt me — don't let me get away with glossing over
any topic. I also welcome any feedback about the structure, tone, and
nature of this course. I ask that you give me this kind of feedback
outside of class, via a message on Schoology. If you would
like to give me anonymous feedback, you can send [anonymous
email](https://www.wikihow.com/Send-An-Anonymous-Email).


## Collaboration and the Honor Code

This course is highly collaborative: we'll discuss things as a group, and all
work-in-progress is public. Although everyone else's work (and often, the
solution) will be available at all times, you _must_ do your own work. You can
be inspired by others, but you should look at someone else's work only after
doing your own work. If you are inspired by someone else's solution, you can
_incorporate_ into your own, with attribution. Use your good judgement here. If
you have any questions about what's acceptable, please talk with me about it.

## Coursework and Grading

Your grade in this course will be a combination of:

-   **Assignments (40%).** There will be roughly one assignment per week for 
the first six weeks (after that, you'll be working on your projects). The 
assignments will be reading+writing or programming. Some assignments you will 
complete on your own; some you may do in a team.
_Every_ assignment will have a "critique" component, where you help evaluate
someone else's work. Assignments will typically be given out on Wednesday, with
the submission due the subsequent Sunday and the critique due on Tuesday.
-   **Project (40%).** You will complete one large project that asks you
    to design, implement, and evaluate your own domain-specific
    language. Though the project is due at the end of the course, I
    will provide milestones and guidelines throughout the course, to
    help you stay on track. I'll be handing out *lots* more details —
    including expectations, grading criteria, and project suggestions —
    when the time comes, about three weeks into the course.
-   **Participation (20%).** A course like this one benefits from lively debate
    and from our diversity of experience and interests. There often is no right
    answer to a problem, so I expect that you will contribute your opinions and
    reasoning both in and out of class, especially through critiques. I also
    expect that you will share your interests: Do you know of an interesting
    domain or have you found a cool DSL? Let us know! During class, I will set
    aside times for us to discuss these things. You can also post them to the
    class forum. Participation is a naturally subjective quality, though it can
    be measured. I will measure your participation in part by assigning small
    thinking/writing exercises during class, asking for feedback on assignments,
    and observing your interactions with classmates. Half-way through the
    course, I will ask you to assess your level of participation. I will
    compare my assessment to yours, and if there is a discrepancy, we will work
    it out. Rest assured, I want you to succeed. If you are concerned about your
    level of participation or how I might perceive it, please visit with me.

## Notices
