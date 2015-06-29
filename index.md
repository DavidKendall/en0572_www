---
layout: default
title: Home
---

# Introduction

<p>
<img class="floatright"
     src="assets/images/en572_image.png" 
     alt="OS Image"
     width="400"/>

This module introduces the application and implementation of operating
systems and the use of concurrency in systems programming. It presents
fundamental concepts: processes, communication and synchronisation,
and illustrates their implementation using a simple, modern
OS. Students are given the opportunity to apply an OS in their own
programs to solve a variety of problems. Additional topics such as
memory management, file systems and security are required in the
implementation of a full-scale OS and are investigated in this module.
</p>

Lectures are the main vehicle for introducing fundamental concepts and
principles and for providing context and motivation. Students will be
expected to prepare for lecture topics and deepen their understanding
of course material by studying course texts and technical
literature. Seminars and laboratory sessions support the lecture
programme by providing students with opportunities to identify and
apply appropriate techniques for the application and implementation of
a variety of OS services.

Formative assessment will be provided in the form of small weekly
exercises, mainly practical in nature and involving
programming. Summative assessment is by way of a single piece of
coursework comprising a programming assignment and a short report.

# Module Team

|   |    |
|---|:---|
|Module Tutor &nbsp;  | [David Kendall](http://computing.northumbria.ac.uk/staff/cgdk2)|
|Lecturer      | [Michael Brockway](http://computing.northumbria.ac.uk/staff/cgmb3)|
|Lecturer      | [Alun Moon](http://computing.northumbria.ac.uk/staff/cgam1)|


# Teaching Arrangements

|   |    |
|---|:---|
**Lecture (Block A)** &nbsp;| Mon 16.00 - 17.00 EB A102B 
**Lecture (Block B)** | Mon 12.00 - 13.00 NB 348 
**Lab/Seminar**       | Tue 12.00 - 14.00 PB S2 
**Lab/Seminar**       | Tue 16.00 - 18.00 PB S2 
**Lab/Seminar**       | Thu 09.00 - 11.00 PB S2 
**Lab/Seminar**       | Thu 14.00 - 16.00 PB S2 

You should attend *both* lecture sessions and *one* of the
lab/seminar sessions every week. Refer to your personal timetable to identify
the lab session that you should attend.

# Synopsis


The aim of the module is to introduce operating system concepts and
the principles of concurrency, and to develop a practical
understanding of their implementation and application in modern
computing systems. Assessment is by course work.

On completion of this module, it is expected that students will be able to:



1. Describe the architecture of an operating system (OS) and its
services, and evaluate its use in a variety of scenarios.

2. Discuss the process model and the scheduling, IPC and
synchronisation services provided by an OS and reason informally about
the behaviour of a multitasking system under a variety of
scheduling algorithms.

3. Review the principal concepts and methods of memory management
and file system implementation.

4. Identify a variety of security threats and examine appropriate OS
mechanisms to protect against them.

5. Design, implement and evaluate solutions to problems of I/O
device handling, synchronisation, communication and timing for
multitasking systems, using appropriate OS services and concurrent
programming techniques.

# Teaching Plan

The following is a *provisional* guide to the organisation of
this part of the module for this year. These arrangements are subject to
change during the course of the module.



| Week   | W/c   | Lecture A   | Lecture B   | Practical   |
| :----: | :---: | :---------: | :---------: | :---------: |
**1** | 22-Sep &nbsp; | [Introduction and overview]({{site.raurl}}/A01.pdf) &nbsp; | [Introduction/review of development tools/environment. Device drivers]({{site.raurl}}/B01.pdf) &nbsp; | [C Programming]({{site.raurl}}/L01.pdf)
**2** | 29-Sep &nbsp; | [C programming for OS]({{site.raurl}}/A02.pdf) | [Interrupts and Interrupt Service Routines (ISR). Context switch]({{site.raurl}}/B02.pdf) &nbsp; | [Output device driver: LED]({{site.raurl}}/L02.pdf)
**3** | 06-Oct &nbsp; | [Process concept]({{site.raurl}}/A03.pdf) &nbsp; | [LPC2378: Interrupts, Vectored Interrupt Controller (VIC), ISR implementation, Timers]({{site.raurl}}/B03.pdf) &nbsp; | [Input device driver: Buttons and joystick]({{site.raurl}}/L03.pdf)
**4** | 13-Oct &nbsp; | [Process scheduling]({{site.raurl}}/A04.pdf) &nbsp; | [Introduction to uC/OS-II: tasks, delays, memory layout]({{site.raurl}}/B04.pdf) &nbsp; | [Installing an ISR and configuring a timer]({{site.raurl}}/L04.pdf)
**5** | 20-Oct &nbsp; | [Memory management&nbsp;1]({{site.raurl}}/A05.pdf) &nbsp; | [Shared variable IPC; interference; race conditions; mutual exclusion]({{site.raurl}}/B05.pdf) &nbsp; | [uC/OS-II task creation and delay]({{site.raurl}}/L05.pdf)
**6** | 27-Oct &nbsp; | [Memory management&nbsp;2]({{site.raurl}}/A06.pdf) &nbsp; | [Semaphores]({{site.raurl}}/B06.pdf) &nbsp; | [uC/OS-II task priorities, mutual exclusion - busy waiting]({{site.raurl}}/L06.pdf)
**7** | 03-Nov &nbsp; | [Storage management&nbsp;1]({{site.raurl}}/A07.pdf) &nbsp; | [Classical problems of synchronisation: producer/consumer, readers/writers]({{site.raurl}}/B07.pdf) &nbsp; | [mutual exclusion - semaphores]({{site.raurl}}/L07.pdf) <br/> Introduction to the assignment 
**8** | 10-Nov &nbsp; | [Storage management&nbsp;2]({{site.raurl}}/A08.pdf) &nbsp; | [Deadlock, Starvation]({{site.raurl}}/B08.pdf) &nbsp; | [Bounded buffer]({{site.raurl}}/L08.pdf)
**9** | 17-Nov &nbsp; | [Protection and security&nbsp;1]({{site.raurl}}/A09.pdf) &nbsp; | [Priority inversion, mutexes]({{site.raurl}}/B09.pdf) &nbsp; | [Deadlock and starvation]({{site.raurl}}/L09.pdf)
**10** | 24-Nov &nbsp; | [Protection and security&nbsp;2]({{site.raurl}}/A10.pdf) &nbsp; | [Monitors]({{site.raurl}}/B10.pdf) &nbsp; | Assignment reviews
**11** | 01-Dec &nbsp; | [Linux overview&nbsp;1]({{site.raurl}}/A11.pdf) &nbsp; | [Mailboxes, message queues. ISR -> task communication. Timer services]({{site.raurl}}/B11.pdf) &nbsp; | Assignment support
**12** | 08-Dec &nbsp; | [Linux overview&nbsp;2]({{site.raurl}}/A12.pdf) &nbsp; | [Memory management: implementation]({{site.raurl}}/B12.pdf) &nbsp; | Assignment demonstrations

<br/>
In addition to the taught sessions, you are expected to undertake
independent and directed learning. This is a 20-credit module, for
which the expected student workload is 200 hours. Over the course of a
15-week semester, you should be spending about 13 hours per week on
this module.


# Assessment

Summative assessment comprises:

* a single course work assignment undertaken in the last 4/5 weeks of
the module; students will be required to implement a simple embedded
application, making use of operating system services, and to report
on possible extensions to, and issues raised by, their work.

Formative assessment comprises a variety of theoretical and practical
exercises with opportunities for discussion with tutors and
colleagues.

Feedback on formative assessment will be given during the seminar and
laboratory sessions. Additionally the eLearning Portal will be used
for more formal feedback on summative assessment.

# Recommended Reading

There is no essential textbook for this module. [SGG14] is an
excellent introduction to operating systems in general. [LAB08] gives
full details of the uC/OS-II RTOS used in the module but is too
expensive to recommend for individual purchase. The other recommended
books and papers give useful information on parts of the syllabus
only.


* **Books**
  - **[SGG14]** Silberschatz, A., Galvin, P., and Gagne,
G., [Operating System Concepts Essentials](http://www.coursesmart.co.uk/9781118804926?__hdv=6.8&amp;__professorview=false&amp;__instructor=8439748&amp;__referringfirstname=David&amp;__referringlastname=Kendall&amp;__isreferringinstructor=true), John Wiley, 2nd edition, 2014, ISBN-13: 978-1-118-80492-6

  - **[DOW08]** Downey, A., [The Little Book of
Semaphores](http://www.greenteapress.com/semaphores/) ([Local copy]({{site.raurl}}/downey08semaphores.pdf)), Green Tea Press, 2002 <br/> A free text book by Allen Downey that introduces a variety of interesting synchronisation
problems and their solution using semaphores.


  - **[LAB02]** Labrosse, J., [MicroC/OS-II The Real-Time Kernel](http://www.amazon.co.uk/MicroC-OS-II-Real-Time-Kernel/dp/1578201039/ref=sr_1_1?ie=UTF8&amp;s=books&amp;qid=1285423255&amp;sr=8-1) (2nd edition), Newnes, 2002 <br/> A good textbook that gives a detailed account of (an earlier version of) the
real-time operating system used in this module. Too expensive to buy outright 
but it would be a good idea to have access to it. The library has nine copies.
It might cost about a tenner each between 3 or 4 of you to get hold of a copy.

  - **[WOL08]** Wolf, W., [Computers as Components: Principles of Embedded Computing System Design](http://www.amazon.co.uk/Computers-Components-Principles-Computing-Architecture/dp/0123743974/ref=sr_1_1?s=books&amp;ie=UTF8&amp;qid=1285439399&amp;sr=1-1), Morgan Kaufmann, 2008 <br/>
Nice overview of interrupts in Chapter 3 and of RTOS in Chapter 6.

* **Papers**
  - **[SR04]**Stankovic, J. and Rajkumar, R., [Real-Time Operating Systems]({{site.raurl}}/SR04.pdf), Journal of Real-Time Systems, 28, 237-253, 2004

# Resources

* **LPC4088**
  - [LPC408x/407x Product data sheet]({{site.raurl}}/LPC408X_7X.pdf)
  - [LPC407x/408x Errata sheet]({{site.raurl}}/ES_LPC407X_8X.pdf)
  - [LPC408x/407x User manual]({{site.raurl}}/UM10562.pdf)
  - [LPC4088 Quickstart Board](https://developer.mbed.org/users/embeddedartists/notebook/lpc4088-quickstart-board/)
  - [LPC4088 Quickstart Board Schematics RevB]({{site.raurl}}/LPC4088_QuickStart_Board_revB.pdf)
  - [LPC4088 Experiment Base Board Users' Guide]({{site.raurl}}/LPC4088_Experiment_BB_Users_Guide.pdf)
  - [LCD Board Users' Guide]({{site.raurl}}/LCD_Board_Users_Guide.pdf)


* **Programming in C**
  - **[KOC04]** Kochan, S., [Programming in C](http://www.amazon.co.uk/Programming-Developers-Library-Stephen-Kochan/dp/0672326663/ref=sr_1_5?ie=UTF8&amp;qid=1316089219&amp;sr=8-5), Sams, 2004 <br/>
A gentle introduction to programming in C. I think it's a better starting
point than the much-recommended Kernighan and Ritchie.

  - **[PRI02]** Prinz, P., [C Pocket Reference](http://www.amazon.co.uk/C-Pocket-Reference-Peter-Prinz/dp/0596004362/ref=sr_1_1?s=books&amp;ie=UTF8&amp;qid=1285570456&amp;sr=1-1), O'Reilly, 2002 <br/>
A concise C reference. Very cheap. Less than a fiver the last time I
looked. I suggest you buy a copy and read it from cover to cover.
  - [C Programming](http://www2.its.strath.ac.uk/courses/c/) <br/>
An online course on C Programming from the University of Strathclyde.
  - [Practical Programming in C](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-087-practical-programming-in-c-january-iap-2010/index.htm) <br/> A detailed introduction to C from the MIT Open Courseware catalogue. If you skip the material on data structures and concurrency, you're left
with a good basic introduction to C. The data structures and concurrency 
sections cover more advanced material. 

* **Miscellaneous**
  - [EE Times](http://www.eetimes.com/design/embedded) Embedded Design Centre for Electrical Engineers.
  - [Embedded Gurus](http://embeddedgurus.com/) A blog from
a variety of experts on embedded software.
  - [The Ganssle Group](http://www.ganssle.com/) Jack Ganssle's page has lots of useful embedded systems development information and links to other information sources.
  - [Sticky Bits](http://blog.feabhas.com/) Niall Cooling's blog
on developing software for real-time and embedded systems.


