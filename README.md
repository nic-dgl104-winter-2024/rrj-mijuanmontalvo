 # rrj-mijuanmontalvo

# App Development Foundation

## Assignment - Research and Reflection Journal between week 8 and week 14.

<br>

<br>

# Week - 8

<br>

## Research a new language - Processing

During the class on Monday, February 26, 2024, my work team investigated information about the "Processing" programming language, for which we answered the following questions related to "Processing"


**What is the language used for?**

Processing is a programming language used to create visual arts projects and interactive visualization projects with animations.

**Who uses the language?**

Processing is used mainly by artists and designers, however this language also is used by beginners in programming and by educators to teach concepts of programming within a visual context

**What are some useful resources?**

 https://processing.org/- The official Processing site offers comprehensive documentation, tutorials, and references that are ideal for beginners.
processing/processing-website: Repository for processing.org (github.com) - Processing repository on GitHub.
https://discourse.processing.org/ - Processing Forum

**Why are these specific resources useful?**

In these places it is possible to find information for those who want to learn this language: manuals, tutorials, general information, it is also possible to enter the forum to ask any questions about the language.

**Reflection**

Processing is a specialized language for visual arts projects. I did a quick search for information on the Processing programming language and found interesting information. I have learned that there are different languages for specific projects and that there is valuable information on the Internet.

<br>

## Write a user story

An application that I use regularly is MonTransit, below is my user story

**Main user story**

As a user of the MonTransit app I want to find the schedules of the Comox Valley bus routes.

**User story (1)**

As a MonTransit user, I can see that the application has a section about the total schedules of each bus route.

*Acceptance criteria:* there is a button for entering in each bus route and each stop bus.

**User story (2)**

As a MonTransit user, I can see that the application has a map where it indices the locations of stop bus.

*Acceptance criteria:* On each stop bus in map there is a tag with its address

<br>

## Choose a language for community code

I would like to focus on the PHP programming language. 

Last semester I took the course "Introduction to PHP", in this course I developed a small project, I do not have much experience in this programming language, however I liked the results that can be achieved with this language. 

I would like to learn more about this programming language because it works very well with HTML and with databases (free software) like MYSQL. I consider it to be a very good option for building web applications. I like to make queries in databases and I believe that this would be good practice.

<br>

## Star github topics and repositories of interest

In order to prepare for the Community Code project, I have visited the https://github.com/explore on this website and reviewed the following tabs:

- https://github.com/topics
- https://github.com/trending
- https://github.com/collections

On this website I applied several "PHP" filters to which I obtained many options of repositories related to PHP projects.

<br>

<br>

# Week 9

<br>

## Read the community code assignment

This assignment is composed of two parts. I will have to contribute to both parts, however I will only have to contribute code to one of them (other contributions include improving documentation, issue management and classification, bug reporting, site development, etc.)

In Part 2 I will also have to contribute to a true open source community. I will contribute to the DGL 104 pattern library repository to help produce a code resource for potential future DGL 104 students.

<br>

## Read “HOW TO CONTRIBUTE TO OPEN SOURCE”

Contributing to open source can be a rewarding way to learn, teach, and gain experience in virtually any skill you can imagine.

Here are some reasons why people contribute to open source:

- Improve software you rely on
- Improve existing skills
- Meet people who are interested in similar things
- Find mentors and teach others
- Build public artifacts that help you grow a reputation (and a career)
- Learn people skills
- It’s empowering to be able to make changes, even small ones

There are all kinds of ways to get involved in an open source project, and a few tips will help you get the most out of your experience. It is possible to contribute in several ways to a project not only in the code. Here are some ways to contribute to a project:

- Organize events that contribute to the project.
- Improvements to the project design.
- Write tutorials and documentation for the project.
- Organize project information.
- Contribute with user tests
- Review project code and recommend improvements.

In conclusion, it is possible to contribute to a project in various ways not only through the code, the important thing is to understand that the contribution will help the project, its readers and will also help the person contributing with practice and learning.

<br>

## Find potential projects to contribute to

Below are three PHP projects that I selected to review their information:

**Project 1:** phpDocumentor

URL Github: https://github.com/phpDocumentor/phpDocumentor

I chose this project because it is a project that has 157 contributors, 154 issues and records recent updates. phpDocumentor stands as the de-facto documentation tool for PHP projects, offering a robust solution for generating comprehensive documentation effortlessly. By analyzing your PHP source code and DocBlock comments, phpDocumentor generates a complete set of API documentation, making it an indispensable tool for developers striving for clear and well-documented codebases.tool for developers striving for clear and well-documented codebases.
![Checklist-phpDocumentor](https://github.com/nic-dgl104-winter-2024/rrj-mijuanmontalvo/assets/122574675/3e528648-ea0e-4dce-af57-4f769655ff5c)



**Project 2:** Ushahidi

URL Github: https://github.com/ushahidi/platform

I chose this project because it is a project that has 66 contributors, 666 issues and records recent updates. Ushahidi Platform is an open source web application for information collection, visualization and interactive mapping. It helps you to collect info from: SMS, Twitter, RSS feeds, Email. It helps you to process that information, categorize it, geo-locate it and publish it on a map.
![Checklist-ushahidi](https://github.com/nic-dgl104-winter-2024/rrj-mijuanmontalvo/assets/122574675/048f23b9-bd5d-44f7-89c5-debb7b1f6981)



**Project 3:** SolidInvoice

URL Github: https://github.com/SolidInvoice/SolidInvoice

I chose this project because it is a project that has 15 contributors, 35 issues and records recent updates. SolidInvoice is a sophisticated open-source invoicing application designed to assist small businesses and freelancers in efficiently managing their daily billing operations. With its comprehensive range of features, this elegant online platform ensures that you receive timely payments.
![Checklist-SolidInvoice](https://github.com/nic-dgl104-winter-2024/rrj-mijuanmontalvo/assets/122574675/26309fcf-a6b6-4082-8cc3-0262fa8606c2)

<br>

## Identify issues to support

Below are some problems detected that I could contribute to.

**To Project phpDocumentor:**

Improve search UX in the default template #3411

URL: https://github.com/phpDocumentor/phpDocumentor/issues/3411

Detail of the issues and the suggested recommendation

The current search input opens a box with the results while typing with no control, and totally hide the page including the search input.

Mutiple UX/ergonomy/accessibility issues in consequence:

- We do not have all the same ability and speed to type on a keyboard. While some of geeks can type a complete long word before the box opens, many other humans will only type few characters.
- Once the box is open, impossible to continue to read what we was typing, so impossible to continue to type for most of humans. (as @jaapio was saying in the issue - Default template search is broken #3092: "Apart from the failing test I think we should have the search field in the search results dialog, as it is unexpected for the user to be able to type in a hidden field.")
- There is no way to access the results page/box from another method (for ex direct access to a search in our dev softwares like selecting a word and "search into…"), because of lack of URL/query dynamic change, and no use of the URL after page load. It's always in best practices to provide direct URL access to such an important feature as the search.

Suggested improvements:

- The search input must never be hidden, always accessible when displaying the results. The results must include the same search input, pre-fill with the same content we typed in the page, and with focus inside to continue/change. When we close the results, the focus must return to the input in the page.
- At the same time the system detects that it can display the results or change the current results (if changes in the input box), the URL must be dynamically changed in accordance, with a query added like "?search=my_input_content".
- When we close the results, the query in the URL must be removed.
- During the loading of a page, IF the JS detects this same query param in the URL, then the system: 1) pre-fill the search input with the content of the query param + 2) displays the results for this request, in the same way as it does when we directly type.
With that, searching will be waaay more accessible for many kind of persons and usages. :)

**To Project  ushahidi:**

[Outreachy Task Submission] Grammatical Error and Capitalization Error in the error message when adding a new post #4794

URL: https://github.com/ushahidi/platform/issues/4794

Issue details:

the error message when adding a new post is "Failed to create a post. please recheck the your input"
Grammatical error: "please recheck the your input." The word "the" before "your input" is redundant and should be removed for correct grammar. The correct form should be: "please recheck your input."
Capitalization error: The please in the statement should start in capital letter 'P'.

**To Project SolidInvoice:**

Unable to install - get 404 message from server. #970

URL: https://github.com/SolidInvoice/SolidInvoice/issues/970

Issue details:

Hello
I have tried installation several times, but get a 404 error from the server when I call the folder with the SolidInvoice files.
I have done the following:
Uploaded 2.2.5 as tar and zip, extracted on server.
2.2.5 zip extracted on MacBook client, and uploaded via FTP
2.2.0 uploaded as tar file and unpacked on server.
Client: MacBook
Browser:
Safari, Firefox, Google Chrome
Same result in all cases.

<br>

## Summary for slack

One of the projects that I have reviewed and could contribute to is Ushahidi Platform.

Ushahidi Platform is an open source web application for information collection, visualization and interactive mapping. It helps you to collect info from: SMS, Twitter, RSS feeds, Email. It helps you to process that information, categorize it, geo-locate it and publish it on a map.

One of the issues found for this application is the following (URL: https://github.com/ushahidi/platform/issues/4794):

the error message when adding a new post is "Failed to create a post. Please recheck your input"
Grammatical error: "please recheck your input." The word "the" before "your input" is redundant and should be removed for correct grammar. The correct form should be: "please recheck your input."
Capitalization error: The please in the statement should start in capital letter 'P'.

I consider that since I do not have great knowledge of PHP coding, I could contribute to the review of the interface in search of other grammatical errors and suggest improvement changes to the application text.

<br>

<br>

# Week 10

<br>

## ASSESS EXTERNAL COMMUNITY CONTRIBUTION GUIDELINES

I have proceeded to review the information related to the contribution, in the Ushahidi project I found the file Contributing.md in which they indicate the following:
  "There are many ways to get involved with Ushahidi projects, and some of them are great even for first time contributors. If you never contributed to Open Source Software before, or need more guidance doing it, please jump in our gitter channel with a clear description of what you are trying to do, and someone in there will try to help you."

As indicated in the previous paragraph, the project is very open to external contributions, for which they have a gitter channel where new contributors can ask or ask questions about their contributions.

**Contributing.md of Ushahidi project URL :** [CONTRIBUTING.md](https://github.com/mijuanmontalvo/platform/blob/develop/CONTRIBUTING.md)

**Gitter channel of Ushahidi project URL:** [gitter](https://app.gitter.im/#/room/#ushahidi_Community:gitter.im)

<br>

## WRITE A SUMMARY ON SLACK

On Sunday, March 17, I sent a message in Slack about my summary of the Contributing.md file, in the message I included the url of the file and a url of a gitter channel for new contributors to the Ushahidi project

<br>

## CONTRIBUTE TO EXTERNAL COMMUNITY

To start my contribution to the Ushahidi project I have taken the following actions:

- I have forked the usahhidi project on my personal account ([usahhidi fork](https://github.com/mijuanmontalvo/platform/tree/Contribution1))

- I have made a clone of the fork on my local computer.

- I have created a branch with the name Contribution1, in this branch I will make the changes that are necessary for the fork of the initial repository

I would like to work in the next issue: [Outreachy Task Submission] Grammatical Error and Capitalization Error in the error message when adding a new post #4794

Below is the text that describes the issue:

**URL Issue:** https://github.com/ushahidi/platform/issues/4794

**Author:** Gbolahan Oladeji

**Issue description:**

the error message when adding a new post is "Failed to create a post. please recheck the your input"

Grammatical error: "please recheck the your input." The word "the" before "your input" is redundant and should be removed for correct grammar. The correct form should be: "please recheck your input."
Capitalization error: The please in the statement should start in capital letter 'P'.

I would like to review this issue and search a possible solution.

<br>

## CONTRIBUTE TO PATTERN-LIBRARY

To start my contribution to the pattern-library project I have taken the following actions:

- I have forked the pattern-library repository on my personal account ([pattern-library fork](https://github.com/mijuanmontalvo/pattern-library))

- I have made a clone of the fork on my local computer.

- I have created a branch with the name Contribution1, in this branch I will make the changes that are necessary for the fork of the initial repository

I would like to work in the issue: "Write definition of Observer pattern in README.md #23" because I am new in design patterns and I would like to start learning with the definitions firt

<br>

## FOLLOW-UP QUESTIONS AND REFLECTIONS

**What is the hardest/most challenging thing you had to do this week for DGL 104? How did you overcome this challenge?**

The most difficult thing was finding a issue in the external and internal repositories that I could support with my level of knowledge, taking into account that I have never performed tasks similar to these. The way to overcome this problem was to review as much information as possible related to the issues.

<br>

<br>

# Week 11
<br>

## CONNECT WITH YOUR EXTERNAL COMMUNITY

In the ushahidi/Community [gitter](https://app.gitter.im/#/room/#ushahidi_Community:gitter.im) channel I sent a message with the following text:

"Hello everyone, I am Juan from Ecuador, I good like to know more about Ushahidi, I neve have made a contribution in a project, please could anyone tell me if there is any document where I can see the instructions for contributing in the documentation of this project, thank you very much". 

<br>

## READ THROUGH PATTERN LIBRARY ISSUES

- I checked the issues of the "pattern-library" repository

- I made comments to [issue #23 "Write definition of Observer pattern in README.md #23"](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/23).

- I made comments to [issue #26 "Identify a potential short list of additional design patterns"](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/26) and I requested to work on issue #26 about it (issue #26 was assigned to me)

- I visited the pull requests tab of the pattern library and read the open pull requests.

<br>

## CONTINUE CONTRIBUTIONS TO EXTERNAL COMMUNITY

I created an issue #4846 in (real) Ushahidi Platform repository to report a problem with the link that is in the README.md file at the root of the repository.

**Issue number:** #4846

**Title:** The "Installation guides" link is not enabled in README.md

**Issue text:** 

Good morning everyone, I am interested in knowing more about the Ushahidi project, however, I was reading the README.md file and I tried to enter the "Installation guides" link in the Useful Links section and I got the following message "Page not found Sorry".

Issue URL: https://github.com/ushahidi/platform (README.md)

Impact: Users who cannot find this file may feel misplaced and lost when trying to install Ushahidi

Possible solution: I consider that the file associated with "Installation guides" is not correctly located or was deleted, perhaps it is necessary to load that file again.

**URL Issue:** [https://github.com/ushahidi/platform/issues/4846](https://github.com/ushahidi/platform/issues/4846)

**Author:** mijuanmontalvo

**Actions done (external):**

I checked the pull request list in [repository of Ushahidi Platform](https://github.com/ushahidi/platform/pull/4849) and currently there is a open pull request (#4849) that is related to my issue #4846:

![image](https://github.com/nic-dgl104-winter-2024/rrj-mijuanmontalvo/assets/122574675/024b034c-d925-416e-bb7a-83e8b8cb6eb7)

[Here](https://github.com/ushahidi/platform/pull/4849) it is possible to see more detail about pull request #4849

![image](https://github.com/nic-dgl104-winter-2024/rrj-mijuanmontalvo/assets/122574675/91e749ec-ef24-47ce-a1ea-8931794b55f2)

On the next screen it is possible to see the lines of code that have been changed in the pull request #4849

![image](https://github.com/nic-dgl104-winter-2024/rrj-mijuanmontalvo/assets/122574675/2fc867f8-d6c0-48f1-8cab-13e65f7ada10)

I understand the pull request #4849 will be reviewed by the maintainers of Ushahidi Platform.

**Actions done (internal):** 

In order to contribute to my issue #4846, within the [Contribution1 branch](https://github.com/mijuanmontalvo/platform/tree/Contribution1?tab=readme-ov-file) I modified the code of the README.md file, corrected the link of the text "Installation guides", below how the edited text looked:

- "[Installation guides](https://docs.ushahidi.com/platform-developer-documentation/v/"

Replicate the modifications made in Contribution1 branch to the main [develop branch](https://github.com/mijuanmontalvo/platform/tree/develop?tab=readme-ov-file) of my clone.

[Here](https://github.com/mijuanmontalvo/platform/commit/67b1f90396be3ecfcd8e1a282cf9fb7c1874fb10) is the link where it is possible to see my Commit in my clone of Ushahidi Platform repository

![image](https://github.com/nic-dgl104-winter-2024/rrj-mijuanmontalvo/assets/122574675/3d39e6f2-e021-4794-9866-10e37baabcf3)

I updated the CONTRIBUTING.md file with all the progress of the contribution for the EXTERNAL COMMUNITY

<br>

## CONTRIBUTE TO PATTERN-LIBRARY

I create the [Pull Request #76](https://github.com/nic-dgl104-winter-2024/pattern-library/pull/76) ("Add Prototype patters and contribute with issue #26"), which consists of the following:

- In the "1. Creational Patterns" section table of the README.md file in the "patterns" folder add a link to the word Prototype, so that when users click, it will take them to the "Prototype" pattern folder

- Inside the "patterns" folder I created a folder called "Prototype" (the folder indicated in the previous paragraph).

- Inside the "Prototype" folder I created two files "README.md" and "Prototype.js".

- In the "README.md" file I have placed a definition of the prototype pattern and an explanation of an example of this type of pattern for javascrip.

- In the "Prototype.js" file add the example code of the prototype pattern for javascrip

Currently the Pull Request #76 is open

Within [issue #26](https://github.com/nic-dgl104-winter-2024/pattern-library/issues/26) make a comment in which I reported on the loading of pull request #76

## FOLLOW-UP QUESTIONS AND REFLECTIONS

The language I chose is PHP, this is an object-oriented language. Starting with version 5, PHP has built in strong object-oriented features, allowing developers to write more modular, reusable, and structured code. OOP in PHP includes concepts such as classes, objects, inheritance, encapsulation, polymorphism, among others.

PHP es bastante compatible con la programación orientada a objetos y proporciona muchas de las características fundamentales necesarias para escribir código orientado a objetos eficiente y modular.

PHP in its beginnings was better known for its procedural programming style, but over time it has adopted more features and practices of object-oriented programming, so it can be considered that PHP is a partially object-oriented language since in its start

PHP is also compatible with other programming paradigms. In addition to object-oriented programming, PHP also supports procedural programming and can also be used to implement other paradigms, such as: 

- Functional programming

- Event-based programming

- Imperative programming
