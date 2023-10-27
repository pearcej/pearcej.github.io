# csc426: Open Source Software Engineering

## Berea College

- [Course Syllabus](https://docs.google.com/document/d/11O1P6yeYuWTDdGJzrgjw6xYm6N8mM_fhHf780vJtlqI/edit?usp=sharing)

---

## Day 18: Thursday, October 26, 2023

### Day 18: In class

- Still fixing problems with the dev environment set-up. This cannot continue. Students, you MUST seek help, so the class can move forward! Ypu are also EXPECTED to communicate!!
- ~~We are going to break up into interest teams in class today.~~
  ~~1. Runestone Set-up: Two of the teams will explore some alternative Runestone set-ups for Brad Miller.~~
  ~~- "I would like to hear what others think is the best way for a newcomer trying to set up the servers to build a book.  There are (at least) three different options that I can think of:~~
  ~~1. Install a production version of runestone from pypi~~
  ~~2. Initialize npm in bases/rsptx/interactives and use the dev version of runestone from the rs virtualenv.~~
  ~~3. Run docker compose run rsmanage rsmanage build bookname~~
~~Notes:~~
  ~~- You should not pip install things into the rs virtualenv so this would require a second virtualenv to swtich back and forth.~~
  ~~- This is what you need if you are actually going to do development on the components.   But it is the most effort to get set up.~~
  ~~- The rsmanage docker container has a production version of runestone installed.  Of all of them it should just work as long as you have an external or dockerized database running.  Also, for ptx books this has the benefit of copying things into the right places, processing the manifest, and updating the library page."~~

~~2. The rest of the teams will explore different aspects of how Runestone works. This could be explore one of the servers or it could be explore the instructor interface or the author interface.~~

~~All teams will be expected to report back to the class~~

### Day 17: Before next class

- Your **SOLE** homework is that you **MUST get a working development environment with a book that builds and deploys inside of it asap but at the latest BEFORE class on Tuesday, November 7.** You have ample resources. You have my office hours, which none of you have come to. You have Moise's lab hours. You have both class times next week (which you can attend virtually if you are at AfroTech.) You have our Slack channel, the Runestone Discord channel, and you have all of the following video drop in times:
- Friday 3pm-5pm Eastern (TODAY and a week from today)
- Tuesday 3pm-5pm Eastern
- Wednesday 12noon-1:45pm Eastern
- Thursday 2pm-4pm Eastern
- all of the above meet at the Zoom link: https://prose.runestone.academy/dropin/
If you REALLY cannot get your WSL set-up, you can set up a VM and run Ubuntu in it and set it up there.
But one way or another, I expect you to have a development environment fully set-up and fully working by BEFORE class on November 7.

## Day 17: Tuesday, October 24, 2023

### Day 17: In class

- Discussion on Docker vs VMs
- More debugging of the Runestone build

### Day 17: Before next class

- Homework: Try to get your build fully working and a book to build and deploy. If you are having trouble, please ask for help on our Slack channel, not in the Runestone Discord channel.

## Day 16: Thursday, October 19, 2023

### Day 16: In class

- Update your Windows by clicking the update from the web link. Note that this is important! Some of you ignored this before and it caused problems.
- Update your rs fork and update your local
- If on Windows and you haven't done this already, go to [Get started with Docker remote containers on WSL 2](https://learn.microsoft.com/en-us/windows/wsl/tutorials/wsl-containers)
  - The directions include installing Docker Desktop for Windows. Once you have done that, I recommend the tutorials inside of Docker Desktop.
  - If you have not done this already follow [Get started with databases on Windows Subsystem for Linux: Postgresql](https://learn.microsoft.com/en-us/windows/wsl/tutorials/wsl-database#install-postgresql)
- Report out on the Runestone setup and work-shopping set-up issues
- Strategizing about how to get unstuck
- If you get tired of all of the installation drugery, you can move on to learning about MVC and web2py:
  - Read [What Is a Web Application?](https://mikkegoes.com/what-is-a-web-application/)
  - Read [What Is the Model-View-Controller (MVC) Design Pattern?](https://mikkegoes.com/model-view-controller-mvc/)
  - Read [Web2py Tutorial](https://www.tutorialspoint.com/web2py/index.htm)

### Day 16: Before next class

- Complete See [Blog post description](b7-blog-docker.md) for more detail.

## Day 15: Tuesday, October 17, 2023

### Day 15: In class

- Reporting out on the Runestone setup and work-shopping set-up issues
- Strategizing about how to get unstuck

### Day 15: Before next class

- None - enjoy Mountain Day!

## Day 14: Thursday, October 12, 2023

### Day 14: In class

- Reporting out on the Runestone setup and work-shopping set-up issues
- Strategizing about how to get unstuck
- Possible work in **opensource** and **cppds**.

### Day 14: Before next class

- None - study for your other midterm exams!

## Day 13: Thursday, October 5, 2023

### Day 13: In class

- Discuss documentation and contribution
- Discuss responding to comments
- Discuss outstanding pull-requests
- Discuss homework
- Revisit issues in **opensource** and **cppds**.
- Finish the complete indexing of the Pretext version of **cppds** being sure to index one entire file per pull-request and follow best practices.

### Day 13: Before next class

- Carefully document your process on your blog as you very slowly and carefully follow the instructions to set up the development environment that begin at [https://github.com/RunestoneInteractive/rs](https://github.com/RunestoneInteractive/rs). For this you have a week, and I want you to demonstrate your understanding of the Runestone community by getting started on this early and seeking help appropriately in the appropriate Runestone communication channels. See [Blog post description](b6-blog-runestone-setup.md) for more detail.

## Day 12: Tuesday, October 3, 2023

### Day 12: In class

- Run `pip install pretext --upgrade`
- Discuss indexing in Pretext and Git workflow
- Revisit issues in **opensource** and **cppds**.
- Complete indexing of the Pretext version of **cppds** being sure to index one entire file per pull-request and follow best practices. 

### Day 12: Before next class

- Read [Chapters 6 & 7: Documentation & Contribution](https://moodle.berea.edu/mod/lti/view.php?id=642072) Be sure to do all activities for participation credit.

## Day 11: Thursday, September 28, 2023

### Day 11: In class

- Discuss open-source licensing
- Discuss indexing in Pretext and Git workflow
- Assigned expansion to other issues in specific sections of **opensource** and **cppds**.

### Day 11: Before next class

- Do the readings and the [blog post on motivation](b5-blog-motivation.md)

## Day 10: Tuesday, September 26, 2023

### Day 10: In class

- Discuss the readings and the [blog post on Agile](b4-blog-agile.md)
- Discuss strategies for figuring out how to create the index in a Pretext book
- Assigned expansion to other issues in specific sections of **opensource** and **cppds**.

### Day 10: Before next class

- Read [Chapter 5: Open Source Licensing](https://moodle.berea.edu/mod/lti/view.php?id=641368) Be sure to do all activities for participation credit.

## Day 9: Thursday, September 21, 2023

### Day 9: In class

- Git workflow. Update branches.
- Presentation by [Ala Qasem](https://www.linkedin.com/in/ala-qasem/)
- Discuss a strategy to figure out how to create the index in a Pretext book
- Assigned expansion to other issues in specific sections of **opensource**

### Day 9: Before next class

- Do the readings and the [blog post on Agile](b4-blog-agile.md)

## Day 8: Tuesday, September 19, 2023

### Day 8: In class

- Discuss PreTeXt and the PreTeXt community
- Complete [T03 Contributing and Accessibility](https://docs.google.com/document/d/1QsmaISKkOPAYRqZz7uCL04zNHpGK6UYppYzOcZr32bQ/edit?usp=sharing)

### Day : Before next class

- Complete [T03 Contributing and Accessibility](https://docs.google.com/document/d/1QsmaISKkOPAYRqZz7uCL04zNHpGK6UYppYzOcZr32bQ/edit?usp=sharing) if you didn't finish it in class.

## Day 7: Thursday, September 14, 2023

### Day 7: In class

- Discuss the feedback you got on your [Github Pages website](https://pearcej.github.io/csc426/websites-f23.html) and blog posts
- Overview of [PreTeXt](https://pretextbook.org/)
- Install the PreTeXt CLI as described in [Section 5.2 PreTeXt CLI](https://pretextbook.org/doc/guide/html/processing-CLI.html)
- Fork [the source code for this book](https://github.com/pearcej/opensource) then clone your fork to your WSL environment.
- Follow the instructions in [Sections 5.2.3 and 5.2.4](https://pretextbook.org/doc/guide/html/processing-CLI.html) to build and view the book.

### Day 7: Before next class

- Complete the explorations and [readings, explorations, and blog entry about Pretext that is described here](b3-blog-runestone-pretext.md).

## Day 6: Tuesday, September 12, 2023

### In class

- Discuss Dr. Miller's visit, Runestone, and Runestone communication
- **Top Priority** Complete the pull requests begun last time in [T02: Forking and Git Branches](https://docs.google.com/document/d/1H0hvucJYxOafntCageQ8V5SI2O--GcANHD9TEtSZyPw/edit?usp=sharing)
- After completing your pull request, spend the remainder of the period giving feedback to the next  ~~three~~ **two** Github Pages websites on the [2023 course listing of websites](https://pearcej.github.io/csc426/websites-f23.html) (ignoring mine), and also posting a *thoughtful* comment on one of each of their blog posts. This means that everyone in the class should receive feedback on their website from ~~three~~ **two** people as well as thougthful comments on their blog from ~~three~~ **two** people.

### Before next class

- Improve your Github Pages website based on feedback from classmates. (Can ypu also use AI to improve your website? Of course!)
- Respond to the comments received in your blog posts

## Day 5: Thursday, September 7, 2023

### In class

- Discuss readings
- Using best practices as described in [T02: Forking and Git Branches](https://docs.google.com/document/d/1H0hvucJYxOafntCageQ8V5SI2O--GcANHD9TEtSZyPw/edit?usp=sharing), contribute your link to our [2023 course listing of websites](https://pearcej.github.io/csc426/websites-f23.html) in order to make it look like [the 2019 course listing of websites](https://pearcej.github.io/csc426/websites-f19.html)
- Meet with [Dr. Brad Miller](https://www.linkedin.com/in/bnmnetp/)

### Before next class

- Complete the explorations and [blog entry about Runestone that is described here](b2-blog-runestone-communication.md).

## Day 4: Tuesday, September 5, 2023

### In class

- Discuss chapter reading assignment and WSL
- Debug the use of VS Code with WSL
- Show and tell with Github pages websites
- ~~Meet with [Dr. Brad Miller](https://www.linkedin.com/in/bnmnetp/)~~

### Before next class*

- Post your Github pages website if you have not already done so.
- Post to your blog based on these [prompts](b1-blog-runestone.md).

## Day 3: Thursday, August 31, 2023

### In class

- Discuss reading assignment and Runestone
- [CSC 426 Day 3 Slides](https://docs.google.com/presentation/d/1Afuvlnw3Sqcs2OBxNYcd6nWouGoA2XZMeHyqSOd_AAs/edit?usp=sharing)

### Before next class

- Read [Chapter 4: Version Control with Git](https://moodle.berea.edu/mod/lti/view.php?id=638827) Be sure to do all activities for participation credit.
- [Complete your website and submit T01: Git and Personal Github Pages website](https://docs.google.com/document/d/1hzN3_0RmjV4azRVsLsWE1PGlZwGBfnPUuquXlMVmP3g/edit?usp=sharing). Be sure that by next time, you have at least a minimal at least locally, but should use HTML and CSS. Also be sure your Github pages site is set up even if you are having difficulty pushing to it. We will debug your use of WSL in the next class.

## Day 2: Tuesday, August 29, 2023

### In class

- Discuss reading assignment, Runestone, and blog assignment
- [CSC 426 Day 2 Slides](https://docs.google.com/presentation/d/1bBqUgl_FXJB71cf9esMlIUv3mdgR1O4_1jXWpbetj5k/edit?usp=sharing)

**Before next class**:

- Complete the [R2: Read Chapters 2 and 3 (OSS Community and Communication and OSS Development Environment)](https://runestone.academy/assignment/student/doAssignment?assignment_id=150302) reading assignment
- Spend 30 minutes or so reading whatever interest you at the [Runestone Academy Blog](https://blog.runestone.academy/)

## Day 1: Thursday, August 24, 2023

### In class

- Welcome
- Discussion of course: content, texts, tools, syllabus, flow, etc
- Updating laptop in parallel with presentions
- Who is Dr. Jan Presentation
- Open Source Textbook: [Runestone Academy](http://runestone.academy) - sign up for bc_opensource_f23
- [CSC 426 Day 1 Slides](https://docs.google.com/presentation/d/1bBqUgl_FXJB71cf9esMlIUv3mdgR1O4_1jXWpbetj5k/edit?usp=sharing) which has many linked videos related to the course

### Before next class

- Complete the [R1: Chapter 1: Introduction to Open Source Software](https://runestone.academy/assignment/student/doAssignment?assignment_id=143046) reading assignment
- [Set-up a blog for this course](b0-blog-runestone.md) and write your first post.
- Submit link to blog in Moodle
- Post a big picture and a short bio to the [csberea.slack.com #csc426 slack channel](https://app.slack.com/client/T3RM3MK1D/C02AQ1WMM53)
- Be sure post your first post publicly and to ALSO copy post contents into Moodle

---

###### Copyright © 2023 | Licensed under a Creative Commons Attribution-Share Alike 3.0 United States License
