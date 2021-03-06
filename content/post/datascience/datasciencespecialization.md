---
title: "A Review of the Coursera Data Science Specialization"
date: 2015-09-10T06:29:12-06:00
tags: 
  - "data science"
  - "coursera"
---

# A Review of the Coursera Data Science Specialization

I recently completed the 10th and final course in the Data Science Specialization offered by Coursera in conjunction with Johns Hopkins University. My background is as a computer scientist and programmer looking to learn more about statistical analysis and machine learning — I have always had an interest in data analysis and machine learning but never actually studied it. I used the Data Science Specialization acted as a starting point to learn more about the field and become familiar with typical problems and solutions that data scientists encounter in the field. This article describes my experience with the specialization and answers the question of whether or not the it is worth the time.

## The Data Scientist's Toolbox

The specialization opens with The Data Scientist's Toolbox, providing a broad overview of the specialization itself and of the tools and technologies that will be covered throughout the course. You will learn the basics of Git, GitHub, Markdown and R. With tutorials on how to install RStudio and R packages. 

The Data Scientist's Toolbox is basic to the point of being remedial. A large portion of the course is spent reviewing what the upcoming courses will cover. It seems disingenuous to charge $50 for a course that explains what additional courses will cover. The concrete material in this course could easily be relegated to pre-requisites of other courses. If you complete a basic tutorial on Git and Markdown and know how to install software you will have completed all the requirements for this course.

###  Verdict

Skip. If you know absolutely nothing about software development this course may be useful. Otherwise, skip it.

##  R Programming

The R Programming course provides an overview of R as a programming language. It covers basic R syntax and data structures and offers an opportunity to practice writing basic R functions. 

Given background in other programming languages the R Programming course will not provide you with much benefit. I would recommend following some R programming introductory tutorials at your own pace. If, however, you do not have much programming experience this course will explain the fundamentals and teach you to think programmatically. This is one of the few courses that comes with a recommended textbook. Unfortunately, the textbook covers advanced R material and would only be useful after becoming familiar with R programming. The pace of the book does not match the expectations of the course.

### Verdict

Take.  There is enough R specific material to make this course worth while. Just don't expect revelations — you will not be an expert in R after this course. An additional textbook would be wonderful.

## Getting and Cleaning Data

Getting and Cleaning Data covers reading files into R from a variety of sources: CSV, MySQL, HDFS, among others. You will learn how to reshape data using R and how to generate summary statistics of your data.

While getting and cleaning data is a necessary process in data analysis, the material covered in this course is basic and disjointed. I would have vastly preferred covering how to load one or two different file types and spent more time on manipulating and preparing data with R.

### Verdict

Skip. This material can easily be learned when needed using specific Google searches on how to load a particular file with R. Consider taking this course if you need additional practice in R.

## Exploratory Data Analysis

The Exploratory Analysis course covers plotting in R using the base plotting system, the lattice package, and ggplot2. It then moves on to explain k-means, dimensionality reduction and principal components analysis.

The material on plotting is great. I only wish that the coverage of the lattice package were removed and more time dedicated to ggplot. I've yet to see any lattice plots in the real world — it seems like ggplot is the de facto standard in this area and should be covered more thoroughly. The course provides a cursory overview of k-means and principal components analysis as a way to summarize data. This material could have used a lot more explanation and motivation.

### Verdict

Take. ggplot is a must and this course will get you started on the right path to plotting. The statistical material on k-means and principal components analysis deserved more in-depth treatment and could almost be a course in itself. I wished for more material in these areas. 

## Reproducible Research

Reproducible research provides the motivation for making research reproducible. It then follows with coverage of R specific technologies that can aid in producing reproducible research: knitr, RPubs, and slidify.

I have mixed feelings about this course. It's great that coverage of reproducible research is included in the specialization but four weeks is too much for this particular topic. Most of the course seems like filler and following a quick tutorial on knitr would provide much the same benefit as taking this course. I also do not see the benefit in covering both RPubs and slidify when they do basically the same thing. I would much prefer seeing more in-depth coverage of one technology — anything learned in one technology could be easily applied to the other when it is needed.

### Verdict

Skip. The coverage of each technology is cursory at best. Reading the documentation of knitr would provide more detail for less time and effort than taking this course. Not recommended.

## Statistical Inference

The statistical inference course covers they key concepts of statistical inference: probability, confidence intervals, hypothesis testing and common statistical distributions. The course is math heavy, covering the theory behind each statistical method before providing R code for using the method in practice.

The course is a jarring departure from the rest of the specialization so far. Previous courses have covered practical considerations and mostly focussed on becoming proficient with R and the RStudio environment. The mathematical treatment of statistics and statistical models can be overwhelming at times and the videos are unevenly paced with complex topics being covered with only one or two slides. The course highlights one of the key failings of the specialization: lack of supplementary material. I would have loved a companion text and problem set to help work though the details.

### Verdict

Skip. The material in this course is fundamental. Unfortunately you will need a better source to learn it from. It's a shame that so much material is crammed into this four week course with no additional material to draw from. I would recommend picking up a basic statistics book rather than taking this course.

## Regression Models

Regression models continues the discussion of statistical methods, this time focussing on linear regression, log-linear regression and how to interpret the results of a regression model using residuals. 

The regression models course falls victim to the same shortcomings as the statistical inference course. Namely, the theoretical nature of the course without supplementary resources makes it difficult to fully dive into the technical details. One or two slides and a video as a format for learning complex material is unrealistic.

### Verdict

Skip. This course attempts to cover a very broad range of material in a short time frame. Unfortunately, not having a supplementary text to work from means that the coverage of the material is spotty and incomplete. 

## Practical Machine Learning

The practical machine learning course eases off from the theoretical underpinnings of prediction to introduce the caret package in R and walks through some typical machine learning algorithms. It starts with a discussion of what prediction is and how to measure if a prediction model is accurate or not, then dives in to linear regression, prediction trees, and random forests. 

The caret package is becoming the de facto standard interface for machine learning in R. As such, the course has some great material focusing on the practical aspects of the caret package. The course also provides a discussion of how to evaluate a prediction model for accuracy and how to compare models against one another. I wish there was more of this material as it seems like such a fundamental problem in machine learning. 

### Verdict

Take. This course provides a solid introduction to the caret package and should guide the student to further areas of study. You will not be an expert in machine learning after taking this course but it should give you a starting point to learn additional details whenever they are needed.

## Developing Data Products

This course focuses on using R to create presentations and web apps as a means of showcasing your models. This course covers Shiny, RStudio presenter and slidify, among other technologies. Each technology for presenting your work is introduced along with a minimal tutorial. Once that tutorial is complete, a new technology is introduced. 

I wish this course focussed more on one or two technologies and expanded more deeply on how they work and what can be accomplished with them. As it stands, it's hard to recommend a course that simply re-implements existing documentation for each technology that could easily be gotten in other, more complete, forms from the respective technologies websites. The course instructor even admits that most of the material is the exact examples from the technologies documentation.

### Verdict

Skip. Just read the tutorial for the technologies that interest you. 

## Data Science Capstone

The capstone project involves creating a Shiny web application that, given a sequence of input words, predicts the next word in the sentence. This project requires some understanding of NLP, data management, Shiny, and RPubs.

The project provided a good experience of what being a data scientist entails. It necessitated a lot of research, data mangling, and performance tuning that are common in the field. The end product is useful and the skills required to make it run well are novel and useful. My only issue with the project was that there was little use of statistical methods.

### Verdict

Take. The capstone brings together a lot of elements of the course and ties it all together. I feel like I learned a lot about data science simply by taking the capstone project.

## Summary

The individual reviews of the courses follow a definite trend: uneven coverage of material and technologies. That trend continues for the specialization as a whole. I don't think anyone doing actual data science would believe that a topic such as statistical inference should be given the same weight as a topic such as git. Although git is definitely something that is valuable for a data scientist, it is not essential to the field. As such, the course would be a great introduction to data science from the perspective of a statistician. It would teach the statistician basic programming techniques, version control, and how to deploy your code via a Shiny application. 

Another failing of the course is the lack of supplementary material. Not everyone learns best from watching videos and if you need to go back and review material at a later date then you need to either find the correct place in the video or look at only a few bullet points in a set of slides. The specialization begs for a text book for at least a few of the courses and could definitely use some supplementary material for almost every course. It seems that the instructors agree with this assessment as they are slowly publishing books through Leanpub that supplement the Coursera course. This is great news for new students going through the material.

As it stands, the specialization does provide a broad overview of the field of data science and I do feel like I can now dive in to particular areas of interest with more confidence. Overall, I'm glad that I took the entire specialization but looking back I believe I could have skipped a few of the courses and focussed more on my areas of interest from the beginning. If you wish to maximize the value for the time spent in this specialization, consider cherry-picking the particular courses that interest you rather than taking the entire specialization.
