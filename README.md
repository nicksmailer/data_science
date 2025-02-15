# Data Science Projects
Data Science projects I worked on during my post graduate education, as well as personal projects undertaken out of curiosity for the subject matter. I will be continuously adding my work as projects are completed.
Below are brief summaries of each:

Election Contributions: For this project, I analyzed election contributions from Alaska, Hawaii, Oregon, and Pennsylvania during fiscal quarters 2 - 4 for the 2020 election cycle, focusing on Joe Biden, Donald Trump, and Bernie Sanders. I first sourced the data, then created a relational data warehouse in PostgreSQL to store the data after cleaning. Following cleaning, I loaded the data by quarter and analyzed. I then repeated the process using the distributed file system, Apache Hadoop working with both Apache Pig and Apache Hive. The document within the folder outlines my process, findings, and comparison between the relational approach and the distributed approach. 

Increasing Department Enrollement: The goal of this project was to both reduce the course offerenings and create course groupings for an arts department at a fictitious university. First, the course list had to be refined to include only existing courses, then I guaged the popular and unpopular courses by calculating enrollement history. From there, I used KNIME to determine frequent itemsets in order to group courses together in the most logical fashion. 

Literary Discussions: This folder contains discussions and thoughts of mine regarding things I have read both as required and out of personal interest. Currently, only one paper is stored here, an evaluation of the current works using deep learning to identify tumors on magnetic resonance imaging (MRI) brain scans.  

NBA Playoff Predictions: The NBA Playoff Predictions project was my capstone project for my graduate program. I sought to answer a variety of research questions, but most importantly, which teams will make the NBA playoffs during a given season, and what if any key indicators are there? Upon sourcing and cleaning the data (a quite involved process) I conducted thorough analysis using R. My best predictions were reached using the Random Forest algorithm working with team data, so I used R markdown to create a basic application that can be used by anyone. To run the app, refer to the README within the zipped folder.

Restaurant RDBMS: The Restaurant Relational Database project was designed to satisfy business requirments prodivided by the fictional restaurant. In order to meet their needs, the database required plenty of intricate capabilities requiring outside of the box thinking. While it was not for a real business, data had to be entered and queries written in order to ensure the project met the specifications. This database was created in Oracle. 
