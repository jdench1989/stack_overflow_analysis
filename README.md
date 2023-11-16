# stack_overflow_analysis

## Dependencies

python-dotenv, psycopg, psycopg2, pandas, matplotlib, seaborn, ipywidgets, sqlalchemy, voila

## Learning objectives

For this project, your learning objectives are:

- Learn to use SQL to analyse and summarise data from a large application
  database
- Learn to apply a commonly used framework for designing meaningful user
  experience metrics
- Learn to build accurate and useful analytics dashboards
- Learn to identify gaps in datasets
- Learn to formulate and propose a data collection strategy

<!-- OMITTED -->

## The scenario

You work as a data analyst at Stack Overflow.

Stack Overflow is a question and answer website for professional and enthusiast
programmers.

Stack Overflow's revenue comes from providing companies the opportunity to run
job postings on its site, as well as by providing space for advertisers who are
interested in advertising to programmers.

Yetunde, a Product Manager in the Questions & Answers team, would like you to
build a dashboard that can be used to track metrics that measure the quality of
the Questions & Answers user experience (UX).

After some research, Yetunde has concluded that the best way to measure the
overall success of the Questions & Answers product is using a user experience
methodology called HEART.

HEART stands for **H**appiness, **E**ngagement, **A**doption, **R**etention and
**T**ask Success, and describes a common approach for designing user-centered
metrics that can be used to gauge the quality of a software product's UX.

## The data

You have access to a database containing a subset of tables from the Stack
Overflow web application database:
- user profiles
- posts (questions and answers)
- comments
- tags
- votes

## Your goal

You have two goals on this project:

1. **Build a Jupyter notebook-based dashboard that allows Yetunde and other business stakeholders to explore the Stack Overflow HEART metrics over time.**  
   This will require you to explore the dataset, deepen your understanding of
   the domain you're analysing (i.e. the Stack Overflow product), familiarise
   yourself with the HEART method and decide on how best to apply it to this
   particular product. You'll want to be able to give clearly reasoned answers
   to questions like "What does engagement mean for Stack Overflow Questions &
   Answers?" or "What do we count as a retained Stack Overflow user?" There is
   more than one valid answer to these questions! The key is to have reasonable
   arguments for why you chose to measure things in a certain way. 
2. **Feed back to Yetunde what data is missing to complete your analysis**   
   Formulate an actionable proposal for what additional pieces data should be
   collected and how this could be done. 