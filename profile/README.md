## Welcome to Environmental Data Science - An Introduction (ESS 523A)!

This is a class at Colorado State University taught by Caitlin Mothes and Katie Willi

M-W-F 8:30am-9:50am, WCNR Building Room 243

## Goals

The broad goal of this course is to make your graduate or undergraduate research easier, more fun, less frustrating, more collaborative, and more supported, while also preparing you for a career that will include data science skills. The more specific goals of this course are to teach students to: 


  1)	Describe the basic code, file, and data management skills required to efficiently and effectively analyze environmental datasets of a range of sizes.

  2)	Apply various analysis techniques to reveal patterns in environmental data relevant to their field of study.
  
  3)	Actively distinguish and select appropriate levels of analysis and code complexity to answer the questions they have about their data.

  4)	Publicly share a code portfolio and participate in collaborative coding efforts.

## Preparation 

### REQUIRED to do before the class starts

#### 1) Set up Instructions and Tutorials

- You **must** install all necessary software to the computer you will be using in class before the course begins. From the online book [Happy Git and GitHub for the useR](https://happygitwithr.com/github-acct.html), complete **all** of Lessons 4 - 12 (skipping lesson 10, use HTTPS tokens and not SSH), and lessons 13 and/or 14 for troubleshooting if you have any issues. This book is a phenomenal resource for learning git, GitHub, and RStudio integration.

  *Even if you already have R/RStudio installed, please make sure to install the newest versions. At MINIMUM you must have R version 4.2 or greater*

### Suggested

If you are joining this class with minimal R experience, OR need a refresher on some of the fundamentals, we HIGHLY suggest working through some of these resources/tutorials:


- [RStudio Primers](https://github.com/rossyndicate/primers/blob/main/README.md) - Interactive
online coding. Really excellent base material and the most useful way to prepare for the course.

- [Posit Recipies](https://posit.cloud/learn/recipes). - Short coding tutorials for *many* different R tasks.

- [Stat 158](https://csu-r.github.io/Module1/) - Vectors, data frames, installing R, etc...

- [RStudio Materials](https://education.rstudio.com/learn/beginner/) - A series of
videos, books, and more to get you started in R.

- [R for Data Science](https://r4ds.had.co.nz/introduction.html) - Covers all of
the basic intro material, from a tidyverse perspective. As discussed, this is 
one way to find solutions in R, it happens to be my preferred way, but there are
lots of Base R ways that work just fine! This is a big book, and should be thought
of as a reference!

- [Stat 159](https://csu-r.github.io/Module2/) - A CSU specific course for an
intro to the tidyverse


#### Additional Core Introductory Material

- [R Markdown](https://bookdown.org/yihui/rmarkdown/#preface) - The primary 
book for learning more about R Markdown and all of its quirks.

- [Cheatsheets](https://www.rstudio.com/resources/cheatsheets/) - Short
clear documents that cover so much material from dplyr to shiny apps. Great
for quick references.


## Approach and Expectations

This class is flipped, meaning any lectures will be delivered via videos you will 
be expected to watch before class. 

So without lectures in class what do we do together? We code! This class has almost 6 hours of contact time per week, and such you will likely be able to finish your homework in the class period alloted. The flipped class allows for deeper discussion about the common pitfals of
[coding](https://ieeexplore.ieee.org/document/7344151).  

Generally we will do a quick live-code review of concepts from the videos, but often the majority of class time will be dedicated to you coding in class.

As such, coming to class is a vital part of how you can be successful and we fully expect you to be there everyday, except for the inevitable mitigating circumstances that we all know will arise. 

We also will actively encourage a collaborative coding environment where students help each other, discuss the best approach to solving various coding problems, and deeply engage in online coding help including AI code assistants like GitHub CoPilot or ChatGPT. We also hope that outside of class, you will use our Teams channel to discuss code issues!

Each week we will cover new topics, you will submit your code through GitHub, and you or your peers will grade your code based on a key we share. A full syllabus that we may occasionally update can be found on Canvas, with the course schedule below. 

We will always send announcements with assigments, video links, and other updates through Canvas. 

A final note. The data science field changes extremely quickly. We will teach you the best way we know how to do things, but these areas change very quickly and we may teach you things that are outdated. For example, over the long term, Quarto is replacing RMarkdown because it is more natively multi-lingual (able to use Python, Julia, etc...), but we are using RMarkdown. Why? Because Rmarkdown is currently more stable, but likely future versions of this class will use Quarto. The differences between these technologies is small, but not zero. A bigger shift we will discuss is how to code with AI assistants, another place where we are hoping to expose you to the cutting-edge resources so you start your career using the best tools available. 


| Week | Date (Monday) | Content                                                                                                                       | Assignment Due Date |
|------|---------------|-------------------------------------------------------------------------------------------------------------------------------|---------------------|
| 1    | 8/19          | Before class: Primers Basics and R Markdown; download R and RStudio<br> Introduction to R, RStudio, RMarkdown<br>  Assignment - None   | N/A                 |
| 2    | 8/26          | Before class: Work with Data<br>  Exploratory data analysis<br>  Assignment - Exploratory Data Analysis (20 points)                     | 9/3                 |
| 3    | 9/2           | **No Class Monday 9/2! Before class Wednesday: Visualize Data<br>  Data visualization<br>  Assignment - Bad Plots (20 points)             | 9/9                 |
| 4    | 9/9           | Before class: Tidy Your Data<br>  Introduction to statistical analysis - T-tests, ANOVA<br>  Assignment - T-Tests and ANOVA (20 points) | 9/16                |
| 5    | 9/16          | Before class: Iterate<br>  Simple Linear Regression<br>  Assignment - Simple regression (20 points)                                     | 9/23                |
| 6    | 9/23          | Before class: Write Functions<br>  Multiple Linear Regression<br>  Assignment - Interpreting multiple linear regression (20 points)     | 9/30                |
| 7    | 9/30          | Power in Statistical Analysis and R Skills Review<br>  Assignment - Power (20 points)                                              | 10/7                |
| 8    | 10/7          | *Before Class* R, Git and GitHub Setup Instructions<br> **Intro to Git and GitHub**<br>  Assignment - First Git Repo and Pull Request (20 points)                                              | 10/14               |
| 9    | 10/14         | **Debugging**<br>  Assignment - Debugging LLM Output (20 points)                                                                       | 10/21               |
| 10   | 10/21         | **Iteration, Functions, API call**<br> s Assignment - National Park Visitation (20 points)                                             | 10/28               |
| 11   | 10/28         | **Introduction to Working with Geospatial Data; Final Project Overview**                                                          | N/A                 |
| 12   | 11/4          | **Introduction to Working with Geospatial Data (cont.)** <br>  Assignment - Geospatial Workflows (20 points)                            | 11/11               |
| 13   | 11/11         | **Nested Modeling**<br>  Assignment - Water quality modeling (20 points)                                                               | 11/18               |
| 14   | 11/18         | **Introduction to Machine Learning**<br>  Assignment - Remote sensing of water quality (20 points)                                     | 12/02               |
| 15   | 11/25         | **No Classes - Fall Break**                                                                                                       |                     |
| 16   | 12/02         | **Final Projects - R Markdown, Bookdown, Quarto, Shiny**<br>  Assignment - Final Project (100 points)                                  | 12/11               |
