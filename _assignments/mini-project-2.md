---
title: Mini-Project 2
date: 2017-02-10 00:00:00 -05:00
description: The second mini-project
due_date: 2017-02-26 19:00:00 -05:00
parts:
- name: Project Proposal
  due_date: 2017-02-12 19:00:00 -05:00
  tag: project-proposal
- name: Part 1
  due_date: 2017-02-21 19:00:00 -05:00
  tag: part-1
- name: Part 2
  due_date: 2017-02-26 19:00:00 -05:00
  tag: part-2
start_survey_url: https://goo.gl/forms/IVuPuA5de7OflI6m2
---

## Project Proposal

<i>Due {{ page.parts[1].due_date | date: '%a %b %-d' }}</i>

* Choose a *different* teammate(s) from the first mini-project.
* Jointly select a project based on a provocation from the [Course Book](/files/HtL_web-book-1.pdf). This should be a *different* project from one that you or your team mates worked on for Mini Project 1.
* Complete the [Mini-Project 2 Proposal Survey]({{ page.start_survey_url }}).


## Part 1

<i>Due {{ page.parts[1].due_date | date: '%a %b %-d' }}</i>

<i>Your total out-of-class time for the reading, lab, and mini-project is not required to exceed eight hours.</i>

* Demonstrable code in a GitHub repository.
* A five-minute project review presentation.

You may start from other otherwise incorporate code from MP1, so long as you are working on a different topic and
you attribute any contributions.


## Part 2

<i>Due {{ page.parts[2].due_date | date: '%a %b %-d' }}</i>

<i>Your total out-of-class time for the reading, lab, and mini-project is not required to exceed eight hours.
You may stop working on Part 2, regardless of state of completion, after eight hours of out-of-class effort, minus however long the lab work and readings took.
If your work is incomplete because you ran out of time, please make this known to me.</i>

What to deliver:

The repository README should answer the questions below, or link to documents that do.

* What is the vision?
* What does the software do? (Including screenshots.)
* How does the code work?
  * How it is organized
  * What is the data flow
  * How to run the code. Installation and usage instructions work on instructor machines. [You may assume Linux and Python 3.]
* Issues and enhancements
  * Known issues
  * Ideas for what to do next
  * Issues and enhancement may be delivered as a text file in your repo, or they can be [GitHub Issues](https://guides.github.com/features/issues/).

The big idea is that someone should be able to understand what your project does, and pick up where you left off. (“Someone” could be a future version of yourself.)
