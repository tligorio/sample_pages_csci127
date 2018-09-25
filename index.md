**email:** tligorio@hunter.cuny.edu  / csci235.help@gmail.com 

**Office:** Hunter North 1000-C 

**Tel:** (212) 772-5213 (CS Department)

**Office Hours:** 

> Mondays 2:30 - 3:30

> Wednesday 2:30 - 3:30 

> **Room 1001-A** Hunter North **(note this is NOT my office)**

> or by appointment (I am usually available by appointment before clas at Silberman)

**UTA tutoring:**  
> Tuesday 2:00 - 4:00 Room C-06 (Silberman)

> Wednesday 1:00 - 5:30 Room 1001-B Hunter North (68th Street)

> Thursday 2:00 - 4:00 Room C-06 (Silberman)

# CSCI 235 - Software Analysis and Design II 
# Fall 2018


The primary focus of this course is the **design and analysis of algorithms and abstract data types**. To this end it introduces elementary data structures with related algorithms and their use in problem solving. The course also covers core computer science concepts such as abstraction, algorithm complexity, performance analysis and the tradeoffs between running time, storage size, clarity and extensibility that are at the core of software design. As a sequel to CSCI 135 it will also enhance your programming skills in C++ by introducing new tools such as Templates, Inheritance, Polymorphism, extend your understanding of pointers and dynamic memory allocation.







## [Syllabus](CSCI235_Fall2018_Syllabus.pdf)   **-- PLEASE READ THIS CAREFULLY --**






## [Programming Rules](CSCI235_Fall2018_ProgrammingRules.pdf) **-- PLEASE READ THIS CAREFULLY --**



# Announcements:

**9/25/2018 -- Google Information Session** 
![Google info flyer](GoogleEPHunter.png)

**9/19/2018 -- 30-MIN DISCUSSION SESSION ABOUT PROJECT 2 AFTER CLASS TOMORROW** I will stay 30 minutes after class to answer questions about Project 2. We will have a group discussion and I will answer any questions about Project 2, however this will not be a debugging session.

**9/17/2018 -- NO CLASSES AND NO TUTORING TUESDAY 9/18 AND WEDNESDAY 9/19** The Skirball Science Learning Center will also be closed. If you need tutoring help you may resume tutoring on 9/20, [here is their schedule](Computer Science Tutoring Schedule.pdf)

**9/13/2018** After lecture today some of you were still in doubt about the **correctness of remove()** for the last item in the array. Here is a bit of rationale as to why it works: Assume the last item is the kth item at position k-1. item_coutnt_ is k, so item_count_- - is now k-1. items_[located_index] = items_[item_count_] is items_[k-1] = items_[k-1], effectively copying the item onto itself. This is just a side effect of the loop to avoid an extra check (if statement), but it doesn't matter. What matters here is that we decrement item_count_, so now the array is of size k-1 with the last index being k-2. We have effectively removed the last (kth) item at position k-1 because we will no longer consider it being in the array, simply by decrementing item_count_. Hope this helps, please ask in lecture next time if you want me to go over it again.

**9/12/2018 -- NO OFFICE HOURS TODAY** Please also note the **change in office hours at the top of this page**. Keep in mind that, because I don't have an office and I must hold office hours in the conference room, these are subject to change. Please check here for announcements if you plan to see me during office hours. I am available by appointment to make up for these changes. Thank you!

**9/7/2018 -- Project 2 posted!** It is due on 9/25. There is no class on Tuesday 9/11. We will go over the Bag class in detail on Thursday 9/13. DO NOT WAIT until then to get started on Project 2. Read the instructions thoroughly and understand the full picture before you begin to code. I will post ArrayBag.h and ArrayBag.cpp on Blackboard under "Course Materials". You can start reading it and modifying it to obtain the Set class. If there are some methods you are not sure about, you can write stubs for them and still test some functionalities of Set. You can then go back and fill those in after we cover Bag in class on Thursday. **BE PROACTIVE, START EARLY!!!**

**9/5/2018 --** There is a typo in the comments of the main() function for Project 1: true (0) is a typo, it should be false (0).
Just go by the value in the parenthesis, so if it says (1) your output should be 1, if it says (0) your output should be 0. Sorry for the confusion!!!

**9/5/2018 -- REMINDER:** Today Hunter follows a Monday schedule, so the UTA's will not be in the lab for tutoring. HOWEVER, the [Skirball Science Learning Center](https://library.hunter.cuny.edu/skirball-science-learning-center) is open (Hunter East 7th floor). Please visit them and find out about their schedule for drop-in tutoring for CSCI 235.

**8/31/2018 --** I re-arranged the topics/reading in the schedule for lectures 5-9. Changes are also reflected in the syllabus, please get the updated version if you are referring to the syllabus for the schedule.

**8/30/2018 --** In C++, .h and .hpp extensions are the same (interchangable). Once you have named your interface file, however, you must use the exact file name and extension in your #include statements. **For Project 1, the files on Gradescope are named Customer.hpp and GeniusBar.hpp, so please use *#include "Customer.hpp"* and *#include "GeniusBar.hpp* in your submission.** Thank you!

**8/30/2018 --** My CUNYfirst account is locked and I cannot access Blackboard for now. Please keep an eye on these announcements regularly for important communications. Thank you!

**8/30/2018 --** **Postponed Project_1 due date to 9/6**, as well as all future projects accordingly

**8/30/2018 --** Email update: the alias (ligorio.tiziana) for my hunter email doesn't seem to be working. Please use tligorio@hunter.cuny.edu

**8/30/2018 --** I posted a flash intro to Object Oriented Programming along with Project 1 in the table below. Those of you who are confused about Project 1 and the basics of writing classes may find this helpful.



## TENTATIVE SCHEDULE:

LECTURE | DATE | TOPIC | READING | PROJECT | SLIDES
------- | ---- | ----- | -------- | --------- | ------- |
1 | T, 8/28 | Welcome / Intro | Syllabus, Programming Rules | [Project_1](Project1.html) [OOP_flash_intro](OOP_flash_intro.html)| [Lecture_1](Lecture 1.pdf)
2 | TH,  8/30 - **ROOM 115AB** | Abstraction / OOP | Chapter 1, Appendix B   | | [Lecture_2](Lecture 2.pdf)
3 | T, 9/4 | Abstract Data Types / Templates /Intro to Inheritance | C++ Interlude-1 | | [Lecture_3](Lecture3.pdf) 
4 | TH, 9/6 | Array-Based Implementation | Chapter 3  |**Project_1 DUE** / [Project_2](Project2.html) |  [Lecture_4](Lecture 4.pdf) 
x | T, 9/11 | **NO CLASS** | | |
5 | TH, 9/13 | Recursion| Chapter 2 |  | [Lecture_5](Lecture 5.pdf)
x | T, 9/18 | **NO CLASS**
6 | TH, 9/20 | Link-based Implementation | C++ Interlude 2 (Pointers), [pointers and references tutorial](http://www.ntu.edu.sg/home/ehchua/programming/cpp/cp4_pointerreference.html),  Chapter 4 |   |
7 | T, 9/25 | -//-|  |  **Project_2 DUE** / Project_3  |
8 | TH, 9/27 **ROOM 115AB** | Inheritance  & Polymorphism  | C++ Interlude 2 (Polymorphism)  |
9 | T, 10/2 | -//-  |  | |
10 | TH, 10/4 | Stacks | Chapters 6 |  |
11 | T, 10/9 | Stack Implementations | Chapter 7 | | 
12 | TH, 10/11 | Lists | Chapter 8 |  |  |
13 | T, 10/16 | List Implementation | Chapter 9 | **Project_3 DUE**  /Project_4 | |
14 | TH, 10/18 | -//- | | | | 
x | T, 10/23 | Midterm Review | |  |  |
x | TH, 10/25 | **Midterm** |  |  |  |
15 | T, 10/30 | Algorithm Efficiency | Chapter 10 | | |
16 | TH, 11/1 | Sorting Algorithms and their Efficiency | Chapter 11 |  |
17 | T, 11/6 | -//- |  | **Project_4 DUE** / Project_5 | 
18 | TH, 11/8 | Recursion as a Problem Solving Technique | Chapter 5 |  
19 | T, 11/13 | Queues and Priority Queues | Chapter 13 |
20 | TH, 11/15 | Queue Implementation | Chapter 14 | 
21 | T, 11/20 | -//- | 
x | TH, 11/22 | **NO CLASS** | |  | 
22 | T, 11/27 | Trees | Chapter 16 | **Project_5 DUE** / Project_6 | 
23 | TH, 11/29 | -//- | 
24 | T, 12/4 | Tree Implementation | Chapter 16 | 
25 | TH, 12/6 | -//- |
26 | T, 12/11 | Final Review | 
x | TH, 12/13 | **Reading Day,   NO CLASS** | | **Project_6 DUE** |
x | **TBA** | **FINAL** | 

