# 17 Computer Science for JavaScript: Regex Tutorial

## Table of Contents

1. [DEPLOYED GIST](#deployed-gist)
2. [Task](#task)
3. [User Story](#user-story)
4. [Acceptance Criteria](#acceptance-criteria)
5. [What Is a Regex?](#what-is-a-regex?)
6. [Getting Started](#getting-started)
7. [Resources](#resources)
8. [Author and Acknowledgements](#author-and-acknowledgements)

## DEPLOYED GIST

<a href="https://gist.github.com/AngelChloe/8f08e3a36f7ec1079f7052c383acdf44"> Link to the deployed Gist </a>

## Task

Developers write code, but they also *write about code*. Take a moment to search the web for tutorials about any of the subjects you’ve learned so far in this course. You’re likely to find thousands of tutorials written by developers of all skill levels, including junior developers&mdash;like yourself!

Assignment this week is to create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does. 

## User Story

As a web development student, I want a tutorial explaining a specific regex.  This is so that I can understand the search pattern the regex defines.

## Acceptance Criteria

```md
* When given regex tutorial, I open the tutorial

* I see a descriptive title and introductory paragraph explaining the purpose of the tutorial:
** A summary describing the regex featured in the tutorial
** A table of contents linking to different sections that break down each component of the regex and explain what it does
** A section about the author with a link to the author’s GitHub profile

* I click on the links in the table of contents
* I am then taken to the corresponding sections of the tutorial
* I read through each section of the tutorial
* I find a detailed explanation of what a specific component of the regex does
* I reach the end of the tutorial and I find a section about the author and a link to the author’s GitHub profile
```

## What Is a Regex?

A **regex**, which is short for **regular expression**, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input. 

For example, the following regular expression can be used to verify that user input is a valid email address:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.

Before you get started, watch this [introduction to regular expressions video](https://youtu.be/7DG3kCDx53c) and read [Regex Tutorial: Matching a Username](https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial) to learn how to identify the different components that make up a regex. If you need any additional help, there are many resources on the web. Feel free to do your own research to find one that can help you complete this assignment.

Once you have a better understanding of what these different parts of a regular expression do, you’ll need to explain what they do for a specific regex.

You can choose one of the following regular expressions or you can choose one that you found on your own (with the exception of the one that is covered in the [Regex Tutorial: Matching a Username](https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial):

* Matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

* Matching an Email: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

* Matching a URL: `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

* Matching an HTML Tag: `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s


## Getting Started

Instead of creating a repository, you’ll publish a GitHub gist. GitHub describes a **gist** as a simple way to share code snippets with others. It’s also an ideal way to demonstrate a technique, teach a principle, or show off a solution. It functions just like a repository, and you’ll use Markdown to create it, just as you do with your READMEs. Gists can include code, images, links, and anything else you can include in a README.

After you’ve downloaded the starter code, learn [how to create a gist](https://help.github.com/en/github/writing-on-github/creating-gists). You can also watch this [video on how to use gists](https://www.youtube.com/watch?v=wc2NlcWjQHw).

> **Note**: Make sure to create a **public** gist.

The starter code is a template with a title, introductory paragraph, summary, and table of contents. The table of contents should link to sections of the tutorial that describe the functionality of each component in the regex. Be sure to rename the template to a unique name that describes your tutorial.

> **Note**: The regular expression that you choose might not include all of the components outlined in the starter code. After you’ve finished your walkthrough, you can remove any sections that you didn’t use.

Each section that describes a component should include more than just one sentence explaining what it does. It should also include a code snippet of that particular component and some examples that meet the requirements of that component.

> **Important**: Make revisions to your gist in the GitHub gist UI. This will create a revision history that graders can use to verify that the tutorial content is yours.


## Resources

- [Repository](https://github.com/AngelChloe/17-Computer-Science-for-JavaScript/edit/main/README.md)


## Author and Acknowledgements

Created by University of Utah University of Utah Coding Bootcamp Student, Cindy Chynoweth
