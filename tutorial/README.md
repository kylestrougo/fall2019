# Final Tutorial

Instead of a Final Exam in this course you will be responsible for generating a tutorial that will walk users through the entire data science pipeline: data curation, parsing, and management; exploratory data analysis; hypothesis testing and machine learning to provide analysis; and then the curation of a message or messages covering insights learned during the tutorial. Students may choose an application area and dataset(s) that are of interest to them; please feel free to be creative about this!

In the interest of building students' public portfolios, and in the spirit of "learning by doing", students will create a self-contained online tutorial to be posted publicly and a 7-10 minute presentation in class. This tutorial can be created individually or in a small group (max 2 people). This assignment will be a publicly-accessible website that provides an end-to-end walk-through of identifying and scraping a specific data source, performing some exploratory analysis, and providing some sort of managerial or operational insight from that data.  We will have several milestones associated with the final project including the following.  These are each discussed below in more detail.

1. **Milestone 1:** Identifying a dataset and establishing a GitHub.io Site. (\~25 points)
2. **Milestone 2:** Extraction, Transform, and Load (ETL) + Exploratory Data Analysis (EDA). (\~50 points)
3. **Deliverable 1:** A final, in class presentation. (\~50 points)
4. **Deliverable 2:** A final tutorial and website. (\~75 points)

----

## Milestone 1: Groups, Data, and Website - Oct. 15, 2019.

For Milestone 1 you should generate a roughly 1 page writeup (500 words) listing a partner (if any) and one to three datasets that you are considering working with and why.  This is just an outline to make sure you are thinking.  This will be published on your GitHub IO page so this also makes sure you’ve figured out how to get it uploaded!

### Possible Sources of Data

This list is just to give you some ideas.  Please feel free to scrape websites (legally!) or to find other sources of data that you may find important or interesting.

* [Data.Gov](https://www.data.gov/): US-centric agriculture, climate, education, energy, finance, health, manufacturing data, and more.
* [BigQuery (Google Cloud)](https://cloud.google.com/bigquery/public-data/) public datasets (bikeshare, GitHub, Hacker News, NOAA,...) and many more.
* [Kaggle Competition Datasets](https://www.kaggle.com/datasets) Billboard Top 100 lyrics, credit card fraud, crime in Chicago, global terrorism, world happiness, etc...
* [Amazon AWS Public Data](https://aws.amazon.com/public-datasets/) AWS-hosted, various (NASA, a bunch of genome stuff, Google Books n-grams, Multimedia Commons, etc.)
* [Data is Plural](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0)Lots of interesting and strange datasets in a Google spreadsheet.
* [Corgies Datasets](https://think.cs.vt.edu/corgis/) Curated set of data from Virginia Tech.
* [GitHub Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) list of datasets that are open and public around the Internet.
* [Think Stats Datasets](https://docs.google.com/spreadsheets/d/e/2PACX-1vQlv2BpO7TsU2UAE7iQwCUxvxn9LTXEPPj5EnA0l9-DJSwCDZU0xg_IhWBItZ7bNvZ_BnznuOrYYy0i/pubhtml) list of interesting datasets from a class very much like this one.
* [Data.Nola.Gov](https://data.nola.gov/browse) list of open datasets from NOLA including lots of financial, voting, etc.

### Github Pages
GitHub provides a service called Pages <https://pages.github.com/> that provides website hosting functionality backed by a GitHub-based git repository. We would like you to host your final project on a GitHub Pages project site. To do this, you will need to:
1. Create a GitHub account (or use the one you already have from Project0) with your username `username`.
  * Note: If you want to make it a repository specific webpage instead of your userpage then please go ahead.
2. Create a git repository titled `username.github.io`; make sure `username` is the same as whatever you chose for your global GitHub account.
3. Create a project within this repository. This is where you’ll dump your iPython Notebook file and an HTML export of that Notebook file.

These instructions are also given directly on the front page of <https://pages.github.com/>; following those instructions should be fine!

In order to make your webpage open up the notebook and make sure everything is as you like it (cells and outputs are showing, no error messages, etc.).  Then go to `File >> Download As >>` and download the notebook as HTML.  This will save the HTML files to your disk.  You will then need to rename this to index.html and upload it into your github.io page.  Once this is done, navigate to `username.github.io` and make sure the notebook is displayed as you like!

### Submission

You should submit the notebook through [Canvas](https://tulane.instructure.com/).  The first cell of your notebook in the markdown **must be a clickable link to the webpage and the webpage must be live**.  That is: the first cell of your notebook must be a markdown cell with a hyperlink to the generated webpage up at `yourname.github.io`.  If this is not correct you will lose points.

*If you do this in a group, both students must submit the notebook through Canvas but it should be the same notebook.  Both students should have the same data uploaded to the site.*

### Scoring Rubric (25 Points)
* 10 Points: Website is up, link was submitted and is correct.  Notebook is professional and clean, the names of the group members, a title for the project, and other good practices as this is *publicly posted*.
* 15 Points: Project plan is in place, relevant data is identified and links are provided, there are draft questions or hypothesis that the student is going to explore.

----

## Milestone 2: Extraction, Transform, and Load (ETL) + Exploratory Data Analysis (EDA) - Nov. 12, 2019.

Your notebook from Part 1 but expanded to include the data being loaded and parsed into shape using the principles of tidy data discussed in class. This is to show that you have figured out how to get the data into your system.

In addition you should also have one or two graphs and summary statistics showing that you have started to investigate your data.  These graphs should be documented much as we did in Project 1 where you describe what the graph is showing and why.  Use of appropriate Markdown cells is essential.

### Submission

You should submit the notebook through [Canvas](https://tulane.instructure.com/).  The first cell of your notebook in the markdown **must be a clickable link to the webpage and the webpage must be live**.  That is: the first cell of your notebook must be a markdown cell with a hyperlink to the generated webpage up at `yourname.github.io`.  If this is not correct you will lose points.

*If you do this in a group, both students must submit the notebook through Canvas but it should be the same notebook.  Both students should have the same data uploaded to the site.*

**Note:** If the dataset you are using is not available from a website then it must also be uploaded to your GitHub site.  If I cannot download the data to verify the code you have submitted you will lose points.

### Scoring Rubric (50 Points)

* (10 Points) *Professionalism*: You have used both code comments and markdown cells to professionally and clearly document your work including having a clear and clean notebook; linking to resources and documents; and doing so with code that is reasonable and efficient.  Your notebook is correct and contains the required links.
* (20 Points) *Data Collection*: Data set(s) are loaded correctly using web scraping or other techniques.  The data is imported and tidy according to the principles discussed in class.  Dtypes are set properly, columns are appropriate, etc.
* (20 Points) *EDA:* Graphs are present in the notebook along with appropriate markdown cells explaining the meaning of the graphs and interpretations.

---

## Deliverable 1: Final Presentation - Dec. 3 & 5, 2019.

You (and your partner) will give a 5 minute presentation in class to your peers.  In this presentation you are role playing a bit -- your job is to convince the audience that the problem you investigated was interesting and meaningful.  An ideal talk will cover every step of the Data Lifecycle that we have discussed in class: (1) where you got your data, (2) how you loaded and preprocessed your data, (3) some exploratory analysis to show important features, (4) a hypothesis about the data and supporting evidence, (5) an important conclusion to draw from your data.

Some resources for giving a good talk:
1. Simon Peyton Jones, [How To Give a Great Research Talk](https://www.microsoft.com/en-us/research/academic-program/give-great-research-talk/)
2. Matt Might, [10 Tips for Academic Talks](http://matt.might.net/articles/academic-presentation-tips/)

### Scoring Rubric (50 Points)

* 10 Points: *Professionalism.* Are the slides well constructed?  Are the graphs labeled and clear?  Did you speak clearly and have a plan for the discussion?
* 10 Points: *Organization.* Was the talk clearly organized?  Did you explain where your data came from, why the question was important, and what the outcomes are?  You should address each stage of the DataScience LifeCycle in this talk.
* 10 Points: *Motivation.* Does the talk make the reader believe the topic is important (a) in general and (b) with respect to data science?
* 10 Points: *Science.* Did you clearly explain why you performed the analyses you chose?  Did you adequately defend any assumptions you made?
* 10 Points: *Peer Evaluation.* Were you present in class both days during presentations, did you provide feedback to the other students on their projects and ask questions.

### Schedule

**Note:** You must upload your slides through [Canvas]() before 10am on the day of your presentation.  Failure to do this will result in a minimum of 10 points lost for *professionalism*.  I will collate the slides on my laptop before class to make sure transitions go smoothly.

| **Tuesday Dec 3rd**  | Group       |           | Link                                                      |
|:----------------:|:-----------:|:---------:|:---------------------------------------------------------:|
| 11:00-11:05      | Gartenstein |           | https://jgartens.github.io/                               |
| 11:05-11:10      | Seidl       |           | https://ilanaseidl.github.io                              |
| 11:10-11:15      | Tucker      |           | https://briannatucker.github.io/                          |
| 11:15-11:20      | Catalano    | Mendels   | https://mcatalano26.github.io/Data-Science-Final-Project/ |
| 11:20-11:25      | Ngo         |           | https://dungngotan99.github.io/                           |
| 11:25-11:30      | O'Connor    |           | https://mroc170.github.io/                                |
| 11:30-11:35      | Urowsky     |           | https://github.com/urowskers/tutorial                     |
| 11:35-11:40      | Campbell    |           | https://christinacampbell98.github.io/                    |
| 11:40-11:45      | Pratt       |           | https://hpratt1.github.io/                                |
| 11:45-11:50      | Salter-Cid  |           | https://johnsaltercid.github.io/                          |
| 11:50-11:55      | Huang       | Stockwell | https://chas3stockwell.github.io/                         |
| 11:55-12:00      | Todorvic    |           | https://aleksatodorovic.github.io/                        |
| 12:00-12:05      | Nguyen      | Van Beek  | https://patches12306.github.io/patches12306/              |


| **Thursday Dec 5th**  | Group       |           | Link                                                      |
|:----------------:|:-----------:|:---------:|:---------------------------------------------------------:|
| 11:00-11:05      | Wang        | Zhuge     | https://zhengwangada.github.io/                           |
| 11:05-11:10      | Jasica      |           | https://ajasica.github.io/                                |
| 11:10-11:15      | Korrapati   |           | https://sri-korrapati.github.io/                          |
| 11:15-11:20      | Mills       |           | https://raemills97.github.io/                             |
| 11:20-11:25      | Kolbert     |           | https://jkolbert2.github.io/                              |
| 11:25-11:30      | Wu          | Wu        | https://wuslash0.github.io/                               |
| 11:30-11:35      | Malith      | Roginsky  | https://tjroginsky.github.io/CMPS-3660-Tutorial/          |
| 11:35-11:40      | Grimay      |           | https://tgirmay.github.io/                                |
| 11:40-11:45      | Hotsko      | Biren     | https://jhotsko.github.io/                                |
| 11:45-11:50      | Chahal      | Gavranic  | https://daveg99.github.io/                                |
| 11:50-11:55      | Westerfer   | Blavatt   | https://swesterfer.github.io/                             |
| 11:55-12:00      | Dorsey      |           | https://kdors.github.io/                                  |
| 12:00-12:05      | Lim         | Nguyen    | https://rjn-2b.github.io/DSLimNguyen/                     |
### Submission

You should submit your slides (PDF, Powerpoint, or Keynote only) through [Canvas](https://tulane.instructure.com/) before 10am on the day of your presentation.  Both students in groups should submit the same set of slides.  **If you do not sign in for class these days and engage with the discussion you will not receive points for the Peer Evaluation section.**

*If you do this in a group, both students must submit the set of slides through Canvas.*

---

## Deliverable 2: Final Tutorial - Dec. 8. 2019.

In general, the tutorial should contain at least 1500 words of prose and 150 lines of (nonpadded, legitimate) Python code, along with appropriate documentation, visualization, and
links to any external information that might help the reader.

Some example tutorials from a similar class at the University of Maryland are:
* Predicting a win in Rainbow Six: Siege: <https://jiglesia3.github.io/>
* Maryland and peer institutions’ faculty/student counts: https://krixly.github.io/
* Analysis of crime data in College Park: https://andresgogo.github.io/

### Scoring Rubric (75 Points)
* 10 Points: *Motivation*. Does the tutorial make the reader believe the topic is important (a) in general and (b) with respect to data science?
* 5 Points: *Further Resources.* Does the tutorial “call out” to other resources that would help the reader understand basic concepts, deep dive, related work, etc?
* 10 Points: *Prose and Professionalism.* Does the prose in the Markdown portion of the .ipynb add to the reader’s understanding of the tutorial?  Are the graphs labeled and clear? Is the writing clear and explained well.
* 15 Points: *Organization.* Was the notebook clearly organized?  Did you explain where your data came from, why the question was important, and what the outcomes are?  You should address each stage of the DataScience LifeCycle.
* 15 Points: *Code.* Does the code help solidify understanding, is it well documented, and does it include helpful examples?  Is the code correct?  Did you show that the results of intermediate steps are correct in the tutorial?  Is there enough code to be complex enough to require a tutorial?
* 10 Points: *Science.* Did you clearly explain why you performed the analyses you chose?  Did you adequately defend any assumptions you made?
* 5 Points: *Subjective Evaluation.* If somebody linked to this tutorial from Hacker News, would people actually read the whole thing?
* 5 Points: *Understanding.* After reading the tutorial, does the reader understand the topic?

### Submission

You should submit the notebook through [Canvas](https://tulane.instructure.com/).  The first cell of your notebook in the markdown **must be a clickable link to the webpage and the webpage must be live**.  That is: the first cell of your notebook must be a markdown cell with a hyperlink to the generated webpage up at `yourname.github.io`.  If this is not correct you will lose points.

*If you do this in a group, both students must submit the notebook through Canvas but it should be the same notebook.  Both students should have the same data uploaded to the site.*

**Note:** If the dataset you are using is not available from a website then it must also be uploaded to your GitHub site.  If I cannot download the data to verify the code you have submitted you will lose points.


