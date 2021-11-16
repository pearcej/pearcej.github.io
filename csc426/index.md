## csc426: Open Source Software Engineering
#### Berea College

  - [Course Syllabus](https://docs.google.com/document/d/1h3_tJQsIA-POB-ronkaHWczbyGybvheo3-KnNljuDpU/edit?usp=sharing)

---
## Day 25: Tuesday, November 16, 2021
 - **In class**:
   - See some presentations
   - work on project
 - **Before next class**:
   - Your homework is to spend spend 2 or more hours working on your Runestone issue, making changes and seeing the results, keeping track of your time in. If you missed class, or were late back to class after the break, you must also make up this missed work time. Be sure to note that you did this. [Complete SR5: Scrum Report 5](https://docs.google.com/document/d/1L8E74FH802iRdE77sY_EXwxTHw5LK7RXFB9LyrR-lwo/edit?usp=sharing). Be sure that you read the linked Google Doc before beginning this part.  Be sure to convert to edit access. Note that due to the nature of this report, it will NOT be accepted late.

## Day 24: Thursday, November 11, 2021
 - **In class**:
   - Discuss scrum reports
   - See some presentations
   - work on project
 - **Before next class**:
   - Your homework is to spend spend 4 or more hours working on your Runestone issue, making changes and seeing the results, keeping track of your time in. If you missed class, or were late back to class after the break, you must also make up this missed work time. Be sure to note that you did this. [Complete SR4: Scrum Report 4](https://docs.google.com/document/d/1L8E74FH802iRdE77sY_EXwxTHw5LK7RXFB9LyrR-lwo/edit?usp=sharing). Be sure that you read the linked Google Doc before beginning this part.  Be sure to convert to edit access. Note that due to the nature of this report, it will NOT be accepted late.

## Day 23: Tuesday, November 9, 2021
 - **In class**:
   - Discuss scrum reports
   - see some presentations
   - work on project
 - **Before next class**:
   - Your homework is to spend spend 2 or more hours working on your Runestone issue, making changes and seeing the results, keeping track of your time in. If you missed class, or were late back to class after the break, you must also make up this missed work time. Be sure to note that you did this. [Complete SR3: Scrum Report 3](https://docs.google.com/document/d/1L8E74FH802iRdE77sY_EXwxTHw5LK7RXFB9LyrR-lwo/edit?usp=sharing). Be sure that you read the linked Google Doc before beginning this part.  Be sure to convert to edit access. Note that due to the nature of this report, it will NOT be accepted late.

## Day 22: Thursday, November 4, 2021
 - **In class**:
   - Discuss scrum reports
   - work on project
 - **Before next class**:
   - Your homework is to spend spend 4 or more hours working on your Runestone issue, making changes and seeing the results, keeping track of your time in. If you missed class, you must also make up this missed work time. Be sure to note that you did this. [Complete SR2: Scrum Report 2](https://docs.google.com/document/d/1L8E74FH802iRdE77sY_EXwxTHw5LK7RXFB9LyrR-lwo/edit?usp=sharing). Be sure that you read the linked Google Doc before beginning this part.  Be sure to convert to edit access. Note that due to the nature of this report, it will NOT be accepted late.


## Day 21: Tuesday, November 2, 2021
 - **In class**:
   - Discuss scrum reports
   - work on project
 - **Before next class**:
   - Your homework is to spend spend 2 or more hours working on your Runestone issue, making changes and seeing the results, keeping track of your time in. If you missed class, you must also make up this missed work time. Be sure to note that you did this. [Complete SR1: Scrum Report 1](https://docs.google.com/document/d/1L8E74FH802iRdE77sY_EXwxTHw5LK7RXFB9LyrR-lwo/edit?usp=sharing). Be sure that you read the linked Google Doc before beginning this part.  Be sure to convert to edit access. Note that due to the nature of this report, it will NOT be accepted late.
   
 ## Day 20: Thursday, October 28, 2021
 - **In class**:
   - try to fix build
 - **Before next class**:
   - Your homework is (again) to get a working build, but we have a couple of paths that will work if you follow one of the following sets of instructions.
   - If you still have your older droplet made from YOUR repos that work or used to work, return to it, and run the following commands:

      docker-compose stop

      docker-compose rm

      cd into RunestoneServer and issue the following command:

      git checkout -b pre-bookserver-<your-issue#> 8a198173ffe43da5b60914135598eaeed7699dc0

      This will check your branch on a branch of Runestone before all of the major structural changes. 

      Next pick-up the old install direction beginning with docker build -t runestone/server . 

      which are located at [Digital Ocean Environment Set-up](]https://docs.google.com/document/d/1ny3caEiPnYwsFn803241RO_ZkbvvFA7X268A0mUq5Q4/edit?usp=sharing)

      pick this up below at 4d in [Digital Ocean Environment Set-up](]https://docs.google.com/document/d/1ny3caEiPnYwsFn803241RO_ZkbvvFA7X268A0mUq5Q4/edit?usp=sharing)
   - If you deleted your older droplet, then make a new one following the directives located at [Digital Ocean Environment Set-up](]https://docs.google.com/document/d/1ny3caEiPnYwsFn803241RO_ZkbvvFA7X268A0mUq5Q4/edit?usp=sharing)usp=sharing
  
## Day 19: Tuesday, October 26, 2021
 - **In class**:
   - disussion of midterm and work on projects
 - **Before next class**:
   - Try to fix build

## Day 18: Thursday, October 21, 2021
 - **In class**:
   - Midterm exam
 - **Before next class**:
   - Make sure your local droplet build is both current with the upstream branches. Then make sure it is working and you are able to edit and push your changes. This MUST be done BEFORE the next part, and the time spent on updating and fixing droplet does not count in the next part. 
   - Next, spend spend 4 or more hours working on your Runestone issue, making changes and seeing the results, keeping track of your time in [SR1: Scrum Report 1](https://docs.google.com/document/d/1L8E74FH802iRdE77sY_EXwxTHw5LK7RXFB9LyrR-lwo/edit?usp=sharing). Be sure that you read the linked Google Doc before beginning this part. **Note that due to the nature of this Scrum Report, it will NOT be accepted late.**
   - *Failure to have an up-to-date working droplet environment in our next class will negatively impact your participation grade.*

## Day 17: Tuesday, October 19, 2021
 - **In class**:
   - Peerwise Jeopardy Game
   - **Announcement:** The Midterm will take place in our next class.
 - **Before next class**:
   - Study for Midterm using [Peerwise course 24005](https://peerwise.cs.auckland.ac.nz/course/main.php?course_id=24005) and other class materials.

## Day 16: Thursday, October 14, 2021
 - **In class**:
   - Review, revise, resubmit, and post questions from [TRM: Peerwise Review for Midterm](https://docs.google.com/document/d/1IE_3hm9a41kcbjBKt3zileZ-OpSDeulUPBT5kd3vd-M/edit?usp=sharing) to [Peerwise course 24005](https://peerwise.cs.auckland.ac.nz/course/main.php?course_id=24005). This is due by the end of class today.
   - Scrum reports in teams
   - Issue work in teams
   - **Announcement:** The Midterm will take place in class on Thursday, October 21, one week from today.
 - **Before next class**:
   - Answer and rate **all** of the questions in [Peerwise course 24005](https://peerwise.cs.auckland.ac.nz/course/main.php?course_id=24005) before class on Tuesday.
   - Come to class with questions.
   - Come to class having updated your Runestone Server and rebuilt it following the directions here: [Docker Deployment](https://runestoneserver.readthedocs.io/en/stable/docker/README.html). 

## Day 15: Tuesday, October 12, 2021
 - **In clas[Peerwise course 24005](https://peerwise.cs.auckland.ac.nz/course/main.php?course_id=24005)s**:
   - Scrum reports in teams
   - Issue work in teams
   - Building a Midterm exam review sheet
   - **Announcement:** The Midterm will take place in class on Thursday, October 21.
 - **Before next class**:
   - Complete the Goodle Doc part of [TRM: Peerwise Review for MidtermAssignment](https://docs.google.com/document/d/1IE_3hm9a41kcbjBKt3zileZ-OpSDeulUPBT5kd3vd-M/edit?usp=sharing) which is due before our next class and WILL NOT Be accepted late.
   - Note that we will review these questions next time before adding to Peerwise. Poor questions will not earn credit, so be sure to take this seriously.
    
## Day 14: Thursday, October 7, 2021
 - **In class**:
   - Debrief on experience with the Runestone open source community
   - Scrum reports in teams
   - Issue work in teams
 - **Before next class**:
    - Complete [A09: Working with Databases](https://docs.google.com/document/d/1uhKqf-3g4sk5Ca0yNxf9Y1C1fDCQexYNzxCbwLFk5r8/edit?usp=sharing)

## No class: Tuesday, October 5 - Enjoy your Reading Day!

## Day 13: Thursday, September 30, 2021
 - **In class**:
   - Meet with Dr. Brad Miller to hear about desired features and potential projects.
   - Choose an issue from Runestone Server or Runestone Components
 - **Before next class**:
    - Complete [A08: MVC and Runestone](https://docs.google.com/document/d/1U5U5jcTitm_QhKB95WzbrPONIXhC04aCdmOMEI8Jhy4/edit?usp=sharing) due Thursday, October 7, 2021

## Day 12: Tuesday, September 28, 2021
 - **In class**:
   - Usability testing of a new Peer Instruction feature that is under development led by Dr. Barbara Erickson and Dr. Brad Miller
   - Discuss what you learned about the usability of Runestone's Instructor's interface 
   - Continue contributions to Runestone
 - **Before next class**:
    - Complete [A07: Exploring or Diving into JavaScript](https://docs.google.com/document/d/1ax5AEHQB_oxshhqHwVwS7jsnfVt3PErfLYHZvof_74g/edit?usp=sharing) which is due before the next class.


## Day 11: Thursday, September 23, 2021
 - **In class**:
   - Discussion of readings, ReStructured text
   - Discussion of [A05: ReStructured Text](https://docs.google.com/document/d/1UOyoX2sBVadey0Co7LeQ0NaHuTlgGthF93RR-mnmKjo/edit?usp=sharing)
   - Complete [T03: More Issues & Connection Building](https://docs.google.com/document/d/1w1mTpPNFVGQ5JlUeJdzThZWADbA8rwPzEH6nt5nS7sw/edit?usp=sharing).
 - **Before next class**:
    - Complete [A06: Contributing to Runestone](https://docs.google.com/document/d/1Vf0x9Id4ljyF4dR9YFvnfym9VJop4PhjgwGDVdeI3l4/edit?usp=sharing) which is due before the next class.

 ## Day 10: Tuesday, September 21, 2021
 - **In class**:
   - Discussion of readings and blog post
   - Fast-tracked scrum reports
   - Work on [T03: More Issues & Connection Building](https://docs.google.com/document/d/1w1mTpPNFVGQ5JlUeJdzThZWADbA8rwPzEH6nt5nS7sw/edit?usp=sharing).
 - **Before next class**:
    - Complete [A05: ReStructured Text](https://docs.google.com/document/d/1UOyoX2sBVadey0Co7LeQ0NaHuTlgGthF93RR-mnmKjo/edit?usp=sharing)
 
 ## Day 9: Thursday, September 16, 2021
 - **In class**:
   - Discussion of reading and blog post
   - [Facilitating Scrum](https://docs.google.com/document/d/1L8E74FH802iRdE77sY_EXwxTHw5LK7RXFB9LyrR-lwo/edit?usp=sharing) - For your reference and time keeping.
   - Work on [T03: More Issues & Connection Building](https://docs.google.com/document/d/1w1mTpPNFVGQ5JlUeJdzThZWADbA8rwPzEH6nt5nS7sw/edit?usp=sharing).
 - **Before next class**:
    - Complete and submit [Blog post 5](b4-blog-runestone.md).
    - Come to class able to build the books you need to build.

## Day 8: Tuesday, September 14, 2021
 - **In class**:
   - Introduction to Scrum
   - Join the [Runestone Slack channel](https://runestoneteam.slack.com)
   - Work on [T03: More Issues & Connection Building](https://docs.google.com/document/d/1w1mTpPNFVGQ5JlUeJdzThZWADbA8rwPzEH6nt5nS7sw/edit?usp=sharing).
 - **Before next class**:
    - Complete and submit [Blog post 4](b3-blog-runestone.md).

## Day 7: Thursday, September 9, 2021
 - **In class**:
   - Demos of [T02: Git and Website](https://docs.google.com/document/d/1Xg3hjSlw9XJIapK8HTdJLJRgEcBa2nM6JsqdhIogI5U/edit?usp=sharing). Keep making improvements!
   - Discussion of useful extensions in VSCode
   - Complete and submit [T01: Engaging with Runestone](https://docs.google.com/document/d/1BUVDwjYnbYlpV6rVykNbPZq-mcIeY925Ees5I2lkERI/edit?usp=sharing), which  includes getting your pull-request pre-approved by myself or one of our TAs.
 - **Before next class**:
   - If you have not done so already, debug and complete your set-up. Then complete and submit [A04: CSC 426 Digital Ocean Set-up](https://docs.google.com/document/d/1gZrOndNf_WP8CVmThPssePumMTeQpHNv20ZYOYBntC8/edit?usp=sharing).
   - Complete and submit [T01: Engaging with Runestone](https://docs.google.com/document/d/1BUVDwjYnbYlpV6rVykNbPZq-mcIeY925Ees5I2lkERI/edit?usp=sharing), which  includes getting your pull-request pre-approved by myself or one of our TAs.
    - Complete and submit [Blog post 3](b2-blog-runestone.md).


## Day 6: Tuesday, September 7, 2021
 - **In class**:
    - Discussion and debugging of [A04: CSC 426 Digital Ocean Set-up](https://docs.google.com/document/d/1gZrOndNf_WP8CVmThPssePumMTeQpHNv20ZYOYBntC8/edit?usp=sharing)
   - Begin [T02: Git and Website](https://docs.google.com/document/d/1Xg3hjSlw9XJIapK8HTdJLJRgEcBa2nM6JsqdhIogI5U/edit?usp=sharing)
 - **Before next class**:
   - Complete something for [T02: Git and Website](https://docs.google.com/document/d/1Xg3hjSlw9XJIapK8HTdJLJRgEcBa2nM6JsqdhIogI5U/edit?usp=sharing). Be sure to submit to Moodle
    - Debug and complete your set-up. Then complete and submit [A04: CSC 426 Digital Ocean Set-up](https://docs.google.com/document/d/1gZrOndNf_WP8CVmThPssePumMTeQpHNv20ZYOYBntC8/edit?usp=sharing). Be sure to submit to Moodle.

## Day 5: Thursday, September 2, 2021
 - **In class**:
    - Presentations by Ala, Bryar, and Micho
    - Questions for Ala, Bryar, and Micho
    - Homework announcement
 - **Before next class**:
   - Make a sincere attempt at completing [A04: CSC 426 Digital Ocean Set-up](https://docs.google.com/document/d/1gZrOndNf_WP8CVmThPssePumMTeQpHNv20ZYOYBntC8/edit?usp=sharing). Be sure to submit to Moodle.

## Day 4: Tuesday, August 31, 2021
 - **In class**:
    - Discussion/Presentation on Git Workflow in a large project
    - Continue [T01: Engaging with Runestone](https://docs.google.com/document/d/1BUVDwjYnbYlpV6rVykNbPZq-mcIeY925Ees5I2lkERI/edit?usp=sharing).
 - **Before next class**:
   - Complete and submit [Blog post 2](b1-blog-runestone.md).

## Day 3: Thursday, August 26, 2021
 - **In class**:
   - Remember that we are meeting in Zoom today so we can have a visit from Brad Miller, Founder, CEO, and Lead Developer, of Runestone Academy. (The Zoom link is in the [Moodle site](https://moodle.berea.edu/mod/url/view.php?id=479234)) and also posted in the course Slack channel.
 - **Before next class**:
   - Complete [A03: Learning Basic Web Development](https://docs.google.com/document/d/1rk7GA5UAaV8y5u_qDrmGiqmskODCIbudwYqo19Zau4o/edit?usp=sharing) before the next class.

## Day 2: Tuesday, August 24, 2021
  - **In class**:
    - Complete [T00: Exploring Runestone](https://docs.google.com/document/d/1_ogEpyQ8l4J_SGwTBgnC3Wh70g3TxV8f9Xpz2g8aRxI/edit?usp=sharing). Complete and submit a link to your copy in Moodle.
    - Begin [T01: Engaging with Runestone](https://docs.google.com/document/d/1BUVDwjYnbYlpV6rVykNbPZq-mcIeY925Ees5I2lkERI/edit?usp=sharing).
  - **Before next class**:
    - Complete [A02: Searching Issues](https://docs.google.com/document/d/1gha9rwu5mhDYQ3IJ25r-vC2i32HMa1jcG-W041j4EEk/edit?usp=sharing) before the next class.

## Day 1: Thursday, August 19, 2021
  - **In class**:
    - Welcome
    - Discussion of course: content, texts, tools, syllabus, flow, etc
    - Read and discuss [Advice to future CSC 426 students from 2019 students](https://docs.google.com/document/d/1Y_WOZfFfDB1pSxxN5EMrL0h9ZqVRVfOfjWOwIsLUNC0/edit?usp=sharing)
    - Brainstorming of skills and characteristics of good open source software developers
    - Begin [T00: Exploring Runestone](https://docs.google.com/document/d/1_ogEpyQ8l4J_SGwTBgnC3Wh70g3TxV8f9Xpz2g8aRxI/edit?usp=sharing). Make a copy, complete and submit a link to your copy in Moodle.
    - Set up some of the tools needed for the course
    - Install (or update) [git](https://git-scm.com/downloads)
    - Install [Git for Windows](https://github.com/git-for-windows/git/releases/download/v2.33.0.windows.1/Git-2.33.0-64-bit.exe)
    - Install [Visual Studio Code](https://code.visualstudio.com/download)
    - Complete [A01: Git Starter](https://classroom.github.com/a/9m32H6Db). Complete this before our next class if you do not complete it in class. Submit your repo link to Moodle.
  - **Before next class**:
    - Read [GitHub vs Resume: Why Bother With a Resume in the Age of GitHub?](https://blog.kickresume.com/2017/09/11/github-vs-resume/)
    - [Set-up a blog for this course](b0-blog-runestone.md) and write your first post.
    - Submit link to blog in Moodle
    - Post a big picture and a short bio to the [csberea.slack.com #csc426 slack channel](https://app.slack.com/client/T3RM3MK1D/C02AQ1WMM53)
    - Be sure post your first post publicly and to ALSO copy post contents into Moodle

---
###### Copyright © 2021 | Licensed under a Creative Commons Attribution-Share Alike 3.0 United States License
