# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.


## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons)

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages (found in the design-files folder):

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions 
### (please edit this file and write your answer below each question. In addition, you may also review these questions with your mentor)

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

    Semantic HTML is markup language that describes the specific meaning of an element. Non-semantic HTML doesn't have this attendant meaning. For example, a div is not semantic HTML because a div is simply a container that can be used for many different case: a header section, a wrapper to contain an image, a wrapper to contain multiple blocks of text, a divider, blank space on the page, etc. Semantic HTML helps collaborators, browsers, and search engines to better understand what's going on in different places in your code. For example, instead of using a div for you header, your title section, and your footer, you can instead use the tags: <header>, <section>, and <footer>. Other examples of semantic HTML include paragraph's - <p>, header's - <h1>, ... , <h6>, images - <img>, and buttons - <button>. 

2. Name two big differences between ```display: block;``` and ```display: inline;```.

    Block elements take up a full line and send adjacent elements down the page whereas inline elements only take up as much space as their content necessitates and can sit next to one another on the same line. Another difference is that inline elements cannot receive a width whereas block elements can.

3. What are the 4 areas of the box model?

    Content, padding, border, margin.

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

    The cross-axis.

5. Explain why git is valuable to a team of developers.

    Git allows a team of developers to edit the same project simultaneously without overwriting one another's work or creating conflicting code that could break the application. By using branches, developers can work on a separate and local version of a repository without needing to worry about breaking the production code. When a developer is finished working on a branch, she can push her edits and create a pull request, which allows her manager to review the changes and to determine if there are any merge conflicts before merging the working branch into the production branch. This means that many developers can be working on many different versions of the same application without risking that they will break the live application or that they will write code that is non-compatible with other developers' code. Of course, there are times when multiple developers edit the same portion of code and both attempt to merge their code into production. Git will identify when two different versions of the same file are in conflict, which allows the team to determine which version of code to push to production. This process allows developers to work separately and asynchronously without needing to constantly communicate about the specific changes they are making. 

    Additionally, git provides version control, which is particularly helpful when an application has bugs. Git allows the application to get rolled back to a previous bug-free version while the team can identify the source of the bug in a recent commit before then re-committing.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [ x ] Create a forked copy of this project.
- [ x ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ x ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ x ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ x ] Push commits: git push -u origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ x ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**



## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [ x ] Build the HTML and CSS to create the missing navigation and header.
* [ x ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [ x ] box1: `teal`
* [ x ] box2: `gold`
* [ x ] box3: `cadetblue`
* [ x ] box4: `coral`
* [ x ] box5: `crimson`
* [ x ] box6: `forestgreen`
* [ x ] box7: `darkorchid`
* [ x ] box8: `hotpink`
* [ x ] box9: `indigo`
* [ x ] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [ x ] Copy and paste your home page navigation and header into the about page
* [ x ] Update the header image with the about page image
* [ x ] Link the `Home` navigation item back to the `index.html` page.
* [ x ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

Note: Please make sure you are using flexbox to layout your website. Floats, inline-block, tables, etc, should not be used for layout. 

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ x ] refactor your HTML, make sure it's indented properly, clean, readable, you have written appropriate comments where necessary and that all attributes (required and encouraged) are filled out correctly.  
* [ x ] Ensure your CSS is organized and readable, you've separated your code by section and that you are using descriptive class names and adding classes in your HTML where styles repeat rather than rewriting the same styles over again
* [ x ] Use a flex item property of your choice when laying out a section of your website, ensure you can explain how and why you've used this property 
