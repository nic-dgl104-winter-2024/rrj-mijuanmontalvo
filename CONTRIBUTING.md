


# CONTRIBUTE TO EXTERNAL COMMUNITY


### Find potential projects to contribute to

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


I decided to contribute to the repository [ushahidi/platform](https://github.com/ushahidi/platform)

# About CONTRIBUTING.md file of repository ushahidi/platform

**URL:** https://github.com/mijuanmontalvo/platform/blob/develop/CONTRIBUTING.md


## Summary of what you learned about the Contributing.md file

In the Ushahidi project there is a file Contributing.md in which they indicate the following:
  "There are many ways to get involved with Ushahidi projects, and some of them are great even for first time contributors. If you never contributed to Open Source Software before, or need more guidance doing it, please jump in our gitter channel with a clear description of what you are trying to do, and someone in there will try to help you."

As seen in the file, the Ushahidi project is very open to external contributions and they even have a Gitter channel where they can guide how to contribute even if a person has never made a contribution.

On the other hand, in the Contributing.md file they indicate that it is possible to contribute in many ways, for example with documentation, Report a bug, Fix a bug, New features, Security issues, etc.

Additionally, in this project there is a code of conduct that describes the way in which people should make their comments, contributions, etc. The code of conduct also refers to conflicts of interest when carrying out an evaluation on someone who breached the code of conduct.

In general, I find this type of document very appropriate and very necessary for the contributors and collaborators of the project to read this type of document before starting to get involved in the project. This will help maintain a good collaborative environment in the project.

I consider that even though the text of the Contributing.md file is small, it is also very concise and makes it very clear that the project is very open to receiving external contributions.


# Ushahidi Platform

Ushahidi Platform is an open source web application for information collection, visualization and interactive mapping. It helps you to collect info from: SMS, Twitter, RSS feeds, Email. It helps you to process that information, categorize it, geo-locate it and publish it on a map.

To start my contribution to the Ushahidi project I have taken the following actions:

- I have forked the usahhidi project on my personal account ([usahhidi fork](https://github.com/mijuanmontalvo/platform/tree/Contribution1))

- I have made a clone of the fork on my local computer.

- I have created a branch with the name Contribution1, in this branch I will make the changes that are necessary for the fork of the initial repository



### Issue #4794 of Ushahidi Platform

I checked the [issue #4794](https://github.com/ushahidi/platform/issues/4794), which has the following detail:

**Issue number:** #4794

**Title:** [Outreachy Task Submission] Grammatical Error and Capitalization Error in the error message when adding a new post

**Issue text:** 

the error message when adding a new post is "Failed to create a post. please recheck the your input"  

Grammatical error: "please recheck the your input." The word "the" before "your input" is redundant and should be removed for correct grammar. The correct form should be: "please recheck your input."
Capitalization error: The please in the statement should start in capital letter 'P'.

**URL Issue:** [https://github.com/ushahidi/platform/issues/4794](https://github.com/ushahidi/platform/issues/4794)

**Author:** Gbolahan Oladeji

**Actions done:** 

When I was reviewing the repository documentation to try to resolve issue #4794, I tried to access the **Installation guides** link which is within the [REAADME.md](https://github.com/ushahidi/platform) file located at the root of the repository, however when I click on this link it takes me to a page that has a message that the page was not found "Page not found The page you are looking for doesn't exist." [link](https://docs.ushahidi.com/platform-developer-documentation/development-and-code/setup_alternatives)

Since I found the problem detailed in the previous paragraph, I decided to try to contribute by reporting the problem of this link. So I created an issue in the (real) Ushahidi Platform repository, below is a detail of the issue that I uploaded:



### Issue #4846 of Ushahidi Platform (Issue created by me)

I created an [issue #4846](https://github.com/ushahidi/platform/issues/4846) in (real) Ushahidi Platform repository to report a problem with the link that is in the README.md file at the root of the repository.

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

## Reflection on success

I consider that the problem detected (failure in the installation guides link) was reported through issue #4846 and that this issue was addressed through a pull request (#4849). As of the date of updating this document, the pull request is still open but I believe that once it is attended to, issue #4846 will be resolved.

Initially, it was a problem for me to understand how issues and pull requests work, but when I investigated them I managed to understand them. It was also difficult to understand a project that was totally new to me.

## Discussion of next steps

I consider that the last step to follow to solve the detected problem is to verify that the pull request #4849 is accepted, which was created to address my issue #4846

