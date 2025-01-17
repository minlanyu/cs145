# CS 145, Spring 2025: Networking at Scale


## Overview

This course studies computer network topics including Layer 2/Layer 3 topology, routing, transport protocols, traffic engineering, network functions, programmable switches, and software-defined networking. Modern networks have grown to large scale (connecting millions of servers) and high speed (Terabits per second) to meet the needs of cloud applications in business and society. Thus, in addition to learning the conventional concepts in networking, we will also discuss how to adapt these concepts to large-scale networks. These discussions will hopefully help deepen our understanding of networking technologies. This course includes lectures and system programming projects. 

- Instructor: Minlan Yu 
- Lecture time: T/TH 11:15-12:30am
- Lecture location: SEC 1.402
- Section time: Fridays 2:15-3:15 pm every other week (available on demand for extension students). Please see the syllabus below for the actual dates for sections.
- Section location: SEC 1.402
- Minlan Office hours: Tue 10-11, SEC 4.415
- TF and office hours:
  * Howard Huang: howardhuang@college.harvard.edu
  * Raj Joshi: rajjoshi@g.harvard.edu
  * Xiao Yao: yaoxiao@g.harvard.edu
- Prerequisites: There are no official prerequisites. Recommended prep: system programming at the level of CS 61.

## Textbook
- This course covers both basic networking concepts and advanced cloud networking concepts.
- For basic networking concepts, you can refer to the textbook (K&R): Computer Networking: A Top-Down Approach, by Jim Kurose and Keith Ross. The latest edition is the 8th edition. Earlier editions are fine. The numbers in the syllabus are based on the 7th edition.
- An alternative book is Computer Networks: A Systems Approach, by Larry Peterson and Bruce Davie. You can find an online version [here](https://book.systemsapproach.org/).
- For advanced topics of networking, please check out lecture notes and class slides.
   
## Coursework
- Class and biweekly section participation is mandatory. (Extension school: Classes and sections can be attended via live stream or on demand.)
- Programming projects: 60%
  - You will build data center networks and network protocols on your laptop, which include topology, routing, load balancing, failure recovery, measurement, and congestion control.
- Homework: 18%
- Midterm exam: 17%
- In-class and Ed participation 5% (Extension school: Ed participation and online questions in class)
- Please refer to the first lecture slides for details.
- All assignments will be due at 11:59 pm ET on the deadline date.

## Syllabus

**Every week, there will be one or two homework questions which are released on Thursday or Friday and due in a week.**

### Prework

* [Infrastructure notes](infra.md) 

* Project 0
You are required to finish [Project 0](https://classroom.github.com/a/E8YYO96_) before the class or in the first week of the class. Project 0 will not be graded. This is just a project for you to check if you are comfortable with the level of programming in this class and to set up infrastructure for future projects.

### Week 1 
* Jan 28 Tue class: Course Overview 
   - Supplemental: [UMass Professor Explains the Internet in 5 Levels of Difficulty](https://www.youtube.com/watch?v=0EqKnvzo3no&t=1216s) by Jim Kurose 
* Jan 30 Thu class: Network topology (K&R 6.6)
* Jan 30 Thu: `Project 1 (Topology) released`
* Jan 31 Fri section: Mininet tutorial
* Feb 2 Sun: `Project 0 check-in`

### Week 2 
* Feb 4 Tue class: Network topology (K&R 6.6)
* Feb 6 Thu class: Link layer: Ethernet (K&R 6.1-6.4)

### Week 3 
* Feb 11 Tue class: Link layer: Ethernet (K&R 6.1-6.4)
* Feb 13 Thu class: Network layer: data plane: packet switching vs circuit switching (K&R 1.3); Network layer: Control plane: Link state and distance vector (K&R 5.2, 5.3)
* Feb 13 Thu: `Project 2 (intradomain routing) released`
* Feb 14 Fri section: Q&A on project 1
* Feb 16 Sun: `Project 1 due`

### Week 4 
* Feb 18 Tue class: Network layer: Control plane: Link state and distance vector (K&R 5.2, 5.3) 
* Feb 20 Thu class: Network layer: Data plane: IP forwarding (K&R 4.1-4.3, 6.4)  
* Feb 21 Fri section: Routing protocols

### Week 5 
* Feb 25 Tue class: Discovery service
* Feb 27 Thu class: Network layer: data center routing (K&R 5.4);  
* Feb 28 Fri: `Project 3 (ECMP) Released`
* Feb 28 Fri section: Project 3 ECMP tutorial
* Mar 2 Sun: `Project 1 grading out`

### Week 6 
* Mar 4 Tue class: BGP; 
* Mar 4 Tue: `Project 2 Due` 
* Mar 6 Thu class: BGP in data centers;

### Week 7 
* Mar 11 Tue class: Transport layer: TCP basics (K&R 3.1-3.5) 
* Mar 13 Thu class: Transport layer: Congestion control (K&R 3.6)  
* Mar 13 Thu: `Project 4 (reliable transport) released`
* Mar 14 Fri section: Transport tutorial 
* Mar 16 Sun: `Project 3 Due`
* Mar 16 Sun: `Project 2 grading out`

### Week 8  Spring recess. No class

### Week 9 
* Mar 25 Tue class: Transport layer: Congestion control (K&R 3.6); 
* Mar 27 Thu class: course review. 
* Mar 30 Sun: `Project 3 grading out`

### Week 10 
* Apr 1 Tue class: **Exam**
   * Extension school students will take the exam on Canvas on Apr 1-2. The exam will be available starting at 9:45 AM ET and will be available for 24 hours. You must finish the exam within 1 hour and 15 minutes of starting the exam.
* Apr 3 Thu class: Data center TCP; Data center load balancing 
* Apr 3 Thu: `Project 5 (traffic balancing) released`
* Apr 4 Fri section: Data center load balancing tutorial 
* Apr 6 Sun: `Project 4 due`

### Week 11 
* Apr 8 Tue class: Data center TCP; TCP fairness (K&R 3.7.1); SDN in the control plane (K&R 4.4, 5.5); 
  - Supplemental: [The Future of Networking, and the Past of Protocols](https://www.youtube.com/watch?v=YHeyuD89n1Y) by Scott Shenker
* Apr 10 Thu class: SDN in the data plane; Wide area: Traffic engineering; Application: Internet application HTTP and DNS; 
* Apr 13 Sun: `Project 4 grading out`

### Week 12 
* Apr 15 Tue class: Ethics (Minlan travel)
* Apr 17 Thu class: Application: Data center applications
* Apr 17 Thu: `Project 6 released`
* Apr 18 Fri section: Final project suggestions 
* Apr 20 Sun: `Project 5 due`

### Week 13 
* Apr 22 Tue class: Application: Data center applications
* Apr 24 Thu class: Reseaerch topics presented by PhD students (Minlan travel)
* Apr 27 Sun: `Project 5 grading out`

### Week 14 
* Apr 29 Tue class: Course summary

### Week 15
* May 13 Tue: `Project 6 due`

## Project

### Objectives

This course project runs throughout the semester. Through this project, you will reach two objectives:

* Build a full stack data center network on your own laptop ranging from topology, and routing, to applications.
* You will get hands-on experiences with the major concepts learnt in lectures and understand the tradeoffs of different design decisions

### Late policy
You should submit your work on an assignment (electronically) before its due time. All assignments will be due at `11:59 pm ET` on the deadline date. 

If you submit your work late, we will award you a fraction of the score you would have earned on the assignments had it been turned in on time, according to this sliding scale:

* 90% for work submitted up to 24 hours late
* 80% for work submitted up to 2 days late
* 70% for work submitted up to 3 days late
* 60% for work submitted up to 5 days late
* 50% for work submitted after 5 days late

For example, if you should have earned 8/10 points but submitted 36 hours late, you will instead earn 6.4 points.

That said, you are allowed **SIX free late days** during the semester. The final project is due based on the final grade submission date and cannot be turned in late. You do not need to tell us that you are applying your *late day* -- we'll remove the late penalty at the end of the semester from the assignment(s) that benefits you the most.

Please plan your work on the assignments so that travel, interviews, athletics, touring, student clubs, extracurricular activities, religious holidays, etc. do not cause you to submit it late. None of the above reasons nor a heavy academic workload constitute an extraordinary circumstance.

Several projects depend on earlier projects. *So even if you miss a deadline of a previous project, it is still important to finish it so you can build future projects on top of it.* Here are the project dependencies:

```
  Project 0 (Setup) --> Project 1 (Topology) --> Project 3 (ECMP) --> Project 5 (Traffic balancing)
  Project 2 (Intradomain routing)
  Project 4 (Reliable transport)
```

### Collaboration policy
Programming, like composition, is an individual creative process. Individuals must reach their understanding of the problem and discover a path to its solution. During this time, you are encouraged to discuss your project with other students at the conceptual level. However, when the time comes to write the code that solves the problem, the program must be your own work.

Do not, under any circumstances, copy another person's program, comments, README/Report description, or any part of the submitted assignment. This includes character-by-character transliteration of other works (whether inspected visually or copied digitally), but it also includes derivative works (i.e., by renaming variable names or subtly shifting around statements to try to hide that copying has occurred). You are also not allowed to use other people's code, comments, or results. This includes work done by other students this or past semesters, as well as any other code you find online.

You are also responsible for ensuring that the code you write for the assignments is not readable by others, which includes sharing with students in future years or posting publicly on websites like GitHub.

You may reuse functions from libraries, but you must check any packages/libraries that you plan to use with the TFs. You should also mark all the places where you reuse functions/libraries from other places. 

All programs will be subject to automated checking for similarity. Any cases of plagiarism will result in an F for the entire course. If you have any questions about policies about academic integrity, please talk to the professor.

### Policy on ChatGPT and generative AI
We expect that all work students submit for this course will be their own. We specifically forbid the use of ChatGPT or any other generative artificial intelligence (AI) tools at all stages of homework and projects, including preliminary ones. Violations of this policy will be considered academic misconduct. We draw your attention to the fact that different classes at Harvard could implement different AI policies, and it is the student’s responsibility to conform to expectations for each course.  There are also [Harvard guidelines for GAI tools](https://provost.harvard.edu/guidelines-using-chatgpt-and-other-generative-ai-tools-harvard). 

## Diversity and Inclusion
I would like to create a learning environment in our class that supports a diversity of thoughts, perspectives and experiences, and honors your identities (including race, gender, class, sexuality, socioeconomic status, religion, ability, etc.). I (like many people) am still in the process of learning about diverse perspectives and identities. If something was said in class (by anyone) that made you feel uncomfortable, please talk to me about it. If you feel like your performance in the class is being impacted by your experiences outside of class, please don’t hesitate to come and talk with me. As a participant in course discussions, you should also strive to honor the diversity of your classmates. (Statement extracted from one by Dr. Monica Linden at Brown University.)

## Accommodations for Disabilities
If you have a health condition that affects your learning or classroom experience, please let me know as soon as possible. I will, of course, provide all the accommodations listed in your AEO letter (if you have one), but sometimes we can do even better if a student helps me understand what really matters to them. (Statement adapted from one by Prof. Krzysztof Gajos.)

## Policies for Extension School Students

### Academic Integrity Policy
You are responsible for understanding Harvard Extension School policies on [Academic Integrity](https://extension.harvard.edu/for-students/student-policies-conduct/academic-integrity/) and how to use sources responsibly. Violations of academic integrity are taken very seriously. Visit [Using Sources Effectively and Responsibly](https://extension.harvard.edu/for-students/support-and-services/using-sources-effectively-and-responsibly/) and the [Harvard Guide to Using Sources](https://usingsources.fas.harvard.edu/) to review important information on academic citation rules. 

### Accessibility Services Policy
The Division of Continuing Education (DCE) is committed to providing an accessible academic community. The [Accessibility Services Office (ASO)](https://extension.harvard.edu/for-students/support-and-services/accessibility-services/) is responsible for providing accommodations to students with disabilities. Students must request accommodations or adjustments through the ASO. Instructors cannot grant accommodation requests without prior ASO approval. It is imperative to be in touch with the ASO as soon as possible to avoid delays in the provision of accommodation. 
DCE takes student privacy seriously. Any medical documentation should be provided directly to the ASO if a substantial accommodation is required. If you miss class due to a short-term illness, notify your instructor and/or TA but do not include a doctor's note. Course staff will not request, accept, or review doctor's notes or other medical documentation. For more information, email accessibility@extension.harvard.edu. 

### Publishing or Distributing Course Materials Policy
Students may not post, publish, sell, or otherwise publicly distribute course materials without the written permission of the course instructor. Such materials include, but are not limited to, the following: lecture notes, lecture slides, video, or audio recordings, assignments, problem sets, examinations, other students’ work, and answer keys. Students who sell, post, publish, or distribute course materials without written permission, whether to solicit answers or otherwise, may be subject to disciplinary action, up to and including the requirement to withdraw. Further, students may not make video or audio recordings of class sessions for their use without written permission from the instructor. 
