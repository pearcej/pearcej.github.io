## CSC 493: r02d: Project Concept Proposal

Your project repo should have both README.md and concept.md with the sections detailed below. Be sure to keep these up-to-date as your project progresses.

Your new work will involve adding two new sections of the README.md which are related to one another, **Vision** and **Scope**. You will also start a new document, the Preliminary Software Requirements Specification (SRS) which you will put into a file called requirements.md.

README.md
- Project name
- Project proposal (including purpose)
- **Vision**
- **Scope**
- Prerequisites
- Built With
- Author name
- Acknowledgments
- link to concept.md
    - Goals
    - Context
    - Novelty
    - Functionality
    - Audience
    - Challenges
    - Measures
    - Motivation
    - Future Extensions
    - *Other (Optional)*
  - link to requirements.md
    - formal list of requirements

# Summary of the new sections and file

We have a very constrained time-frame in this course to complete a sizeable project. This means that
scaling the scope of your project is very important. In English, the word “scope” means the range, size,
or extent of something. In software development, one creates a Vision and Scope Document or a Scope
Document to clearly define the scope of the project, i.e. to clearly specify what the software developers
understand to be their tasks. This means that “out of scope” tasks are what the software developers
assume are NOT their responsibilities. Note that even though it is called a Scope Document, it is
typically just a small section of the larger design document, as it will be in our case. In the business world, clarifying the scope and limitations helps to establish realistic expectations of the stakeholders and
provides a reference frame against which proposed features and requirements changes can be evaluated.

It has been long recognized that the hardest part of building a software system is deciding precisely what
to build. Thus, no other part of the work is as difficult as establishing the detailed technical
requirements. The iterative development model of software engineering employs the construction of
very small components which are tested and then built upon with additional small components. Iterative
process models are often used by commercial developers because they are models which allow
flexibility in achieving design goals of a customer who does not know how to explicitly describe what
they need.

The specific iterative software engineering model recommended in this course is an agile model called a Joint Application Development (JAD) model which is a methodology of evolutionary prototyping that
assumes project requirements are not completely fixed when the project begins but may emerge more
fully and even change as the project develops; up until the time they must be finalized in order to
complete the project.

A Software Requirements Specification (SRS) is a written understanding of system requirements prior
to any actual design or implementation work. The SRS document states in precise and explicit language
those functions and capabilities a software system must provide, and any required constraints which the
system must follow. An SRS contains functional and nonfunctional requirements only, rather than
design ideas. Functional requirements describe the functionality or capability that the software is to
have. Example functional requirement: "Software must update and remember the highest score earned
by all users." Non-functional requirements are qualities or constraints that the software must have or
comply with, but which are not operations that will be automated.

Example non-functional requirement:
  - "Software must run on Windows XP".

Requirements are typically prioritized on as well as numbered so
that they can be tracked as the project moves forward.

# Application Development

## Vision
This section be no more than a paragraph.
It should present a concise vision statement which summarizes the purpose and intent of the project and describes what the world will be like
when the project is completed. This vision statement may be somewhat idealistic, but it still should be grounded in the realities of time and resource limitations.

## Scope
This section should also be no more than one paragraph. It should very clearly specify both the scope of the project
as what will considered “out of scope”. Be sure to describe the intended major features that
will be included in the project. Also, identify any product features or characteristics that a
stakeholder might anticipate, but which are not planned to be included in the project.

## Preliminary Software Requirements Specifications

Create a new file called requirements.md.
Using your stated Scope as a guide, precisely and explicitly describe the primary software requirements using the following template for each specific requirement:

  - **Number**: (List unique requirement number.)
  - **Statement**: (Precisely state the requirement.)
  - **Evaluation Method**: (How can you tell if the completed software satisfies this requirement?)
  - **Dependency**: (List each other requirement on which satisfaction of this requirement depends or write "None")
  - **Priority**: (Assign a priority to this requirement: essential, high, middle, low, or if time permits.)
  - **Requirement revision history**: (when, what, and why)

Be sure that you list each requirement separately rather than combining two or more.

You may want to use [MarkDown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) and [MarkDown Live Demo](http://www.markdown-here.com/livedemo.html).

Add a relative link to requirements.md from README.md. (A relative link uses just the file name and not http://...) Test this link and make sure it works.

---
### Submission Deadline:
- *Before next class:* Completed Scope and Vision paragraphs. At least one requirement in requirement.md. All submitted to your linked Github repo.
