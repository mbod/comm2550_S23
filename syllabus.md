  
## COMM2550 Foundations in Data Science for Communication

### Spring 2023

#### Tuesday 5.15-8.15pm (Room: ASC 109)
	
#### Professor: Matt O'Donnell (he/him/his)
* Email: mbod@asc.upenn.edu
* Office Hours: via Zoom (see link in Canvas)
	* Specfic times TBA
		* But this may vary and I will always try and be available for appointments outside these times if you email with sufficient notice. 
 
 
----

## IMPORTANT NOTICE - <u>Masks are required in this class</u>
* Please make sure you are wearing a face mask fully covering both mouth and nose _before_ you enter the classroom and keep it in place _at all times_.

* Make sure you have a "properly-fitting, high-quality mask (preferably a surgical mask, KN95/KF94, N95, or [EHRS-recommended Aries mask](https://ehrs.upenn.edu/covid-19/universal-mask-and-cloth-face-covering-precautions) as opposed to a single layer cloth mask)." (UPenn Public Health Guidance).
<br/><br/>

----

## Course Description Goals and Objective

Acquiring and demonstrating data literacy, namely, the ability to find, appropriately handle, analyze and communicate insights from the rapidly growing spectrum of data in all aspects of modern life, is now a vital skill for virtually all workers and researchers. This course provides a foundation in the concepts, methods and applications of data science (including network science) to questions in Communication.

The course will:

* Build data literacy and help you start to develop skills working with large and complex datasets of relevance to communication behaviors in the digital world. 

* Help you become familiar with basic programming skills for data analysis using the R and Python programming languages, along with some of the common tools used for network and data analysis and visualization.

* Provide an introduction and overview of the key elements of applied data science, including the analysis of networks and machine learning (ML). 

* Consider the practical and ethical challenges of 'big data', unbiquitous data tracking and the increasing use of algorithmic (ML) decision systems.

The course serves as an introduction to and overview of courses within the Data and Network Science concentration for the Communication major. No prior programming or data analysis experience is required.



## Assessment
* Quizes (15%)
  * Most weeks there will be a short quiz related to the lecture and readings for the week. The quiz will be available in Canvas.

* Short paper [1500-2000 words] (15%)
  * A reflection/discussion paper focused on an data related issue. The paper should be written in Markdown.
  
* Lab Assignments (25%)
  * Building on the material covered in the weekly lab sessions, which focus on gaining some practical skills working with in Python and R, these assignments will contain questions designed to help you practice. The assignments will be available and submitted within JupyterHub.

* Quantified Self Assignment (15%)
  * Throughout the semester you will complete a quick daily rating task to build up a personal data set of your mood and relevant events.
  * You can choose to add in other data (e.g. location, movement or social media logs, etc).
  * You will analyze the data to observe patterns and trends and interpret any associations (e.g. with days of the week, a particular event, etc.)
  * You will then write a short blog post describing your findings.

* Data project (30%)
  * The project should make use of the techniques and theory covered in class to carry out a data analysis of a specific research question agreed upon with the instructor. 
  * The aim of the project is to work through the steps in a typical data science project. The steps include:
	* Develop a focused research question and some testable hypotheses
	* Acquire, clean and organize relevant data
	* Carry exploratory data analysis (and visualization)
	* Develop data analysis to answer research questions and hypotheses
	* Interpret patterns
	* Communicate findings in an engaging data story
	
  * More details of the kinds of projects that would be appropriate and manageable will be discussed as the class progresses.

## Textbooks and recommended readings

### Textbooks
 
* The two books by Ben Jones in _The Data Literacy Series_:
  1. _Data Literacy Fundamentals: Understanding the Power & Value of Data_(Abbreviated as `DLF` on schedule)
  2. _Learning to See Data: How to Interpret the Visual Language of Charts_(Abbreviates as `LSD` on schedule)

### References for Python and R coding

1. McGregor, S.E. (2021) *Practical Python Data Wrangling and Data Quality*. O'Reilly Media. (This text is available through the Penn library [](https://learning.oreilly.com/library/view/practical-python-data/9781492091493/))
   * We will use certain sections of this book in the lab sessions for learning how to work with data using Python. The whole book is a useful reference and introduction.
   * This book is referenced as `PPDW` in the schedule below.

2. Wickham, H. and Grolemund. G. (2017) *R for Data Science*. O'Reilly Media.
(Available online: https://r4ds.had.co.nz/index.html)
    * We will use parts of this book in the lab sessions for learning to use R. The book focuses on using `ggplot` for visualization and the `tidyverse` libraries for data analysis, just as we will.
    * There is more advanced material in the book that we won't be able to cover but it is well worth spending some time trying some of the exercises throughout the chapters.
    * This book is referenced as `RDS` in the schedule below.<br/><br/>


### Recommended

* Spiegelhalter, D. (2021) _The Art of Statistics: How to Learn from Data_. Basic Books

* Harford, T. (2021) _The Data Detective: Ten Easy Rules to Make Sense of Statistics_. Riverhead Books

* O'Neil, C. (2017). _Weapons of math destruction_. Penguin Books.

* Williams, S. (2020). _Data Action: Using Data for Public Good_. MIT Press.


## Note about learning programming

One of the aims of this class is to help students begin to develop data analysis and programming skills that they can use as a part of carrying out research. But like learning any new skill, such as a new spoken language, it takes time and can be frustrating at first. This course does not require students to have any programming background. Realistically it is not possible to become a fully proficient programmer in just one semester. However, the lab sessions and assignments are focused on helping you begin this process and to become comfortable with reading, understanding and modifying Python and R code examples that you can find on the web etc.


---


## Schedule

**NOTE: This is a tentative schedule that will change as the course gets started**

#### Class structure
* Usually each class session will be divided into two parts (with a short 15 minute break between):
  1. __Content and Discussion__ - This part of the class will introduce and review the key topics onlined in the schedule. It is important that you read the assigned material __BEFORE__ the class as you'll be expected to engage in discussion and other activities based on this content.
  2. __Lab session__ - The second part will be focused on pratical exercises to put into practice what we have been learning about thinking about, collecting, analyzing, interpreting and communicating data. This will include learning some basic steps using Python and R scripts and some other tools for data analysis and visualization.
  

#### Week 1: Course Introduction
* **Tue 01/17/23**
  - Content & Discussion
	* Course Overview
		- What is data?
		- What is data science?
  - Lab 
	* Setting up JupyterHub
		- Using Jupyter notebooks
		- Using Markdown
		- How assignments work

#### Week 2: What is data and the DISW hierarchy
* **Tue 01/24/23**

  - Content & Discussion
	* Reading: `DLF` Chs. 1 & 2
    * DIKW pyramid and systems of thinking

  - Lab Session
    - Python Basics Part 1
	  - Objects
	  - Named pointers
	  - Data types (`str`, `int` and `float` objects)
	  - Lists
		  - indexing
		  - list specific functions
			  - `count()`
			  - `index()`

* **Sat 01/28/23 11.59pm - Quiz 1 Due** - Submit in Canvas


#### Week 3: Domains of data and Data typology

* **Mon 01/30/23 11.59pm - Assignment 1 Due** - Submit in JupyterHub

* **Tue 01/31/23** 
  - Content & Discussion
	* Reading: `DLF` Chs. 3 & 4
	* Domains of Data
		- Private
		- Public
		- Personal
	* Data measurement and levels
		- Reliability and Validity
		- NOIR typology for data
			- Nominal
			- Ordinal
			- Interval
			- Ratio
	
  - Lab Session
	- Python basics Part 2
		- More on `list` objects
		- Conditional constructs
			- Tests and `if` constructs
			- `if` and `else` 
			- Walking through data using loops
			- `for` construct


* **Sat 02/04/23 11.59pm - Quiz 2 Due** - Submit in Canvas

#### Week 4: Forms of Data Analysis and Visualization

* **Tue 02/07/23**

  - Content & Discussion
	* Readings: `DLF` Ch. 5; `LSD` Introduction & Ch. 1
	* Types of data analysis
		1. Descriptive
		2. Inferential
		3. Diagnostic
		4. Predictive
		5. Prescriptive
	* Visualizing and discovering patterns in data
	* Basic typology for visualizing data
	
  - Lab Session
	- Python basics Part 3
		- Dictionaries (`dict` object)
		- Data structures
			- List-of-lists
			- List-of-dictionaries
			- JSON
			

#### Week 5: Representing and visualizing data

* **Tue 02/14/23** 

  - Content & Discussion
	* Reading: `DLF` Ch. 6; `LSD` Ch. 2
	1. Figures
	2. Tables 
	3. Statistics
	4. Visualizations
	5. Dashboards
	6. Data stories
	
  - Lab Session
		- Working with tabular data
		- Using `pandas` `DataFrame` object
		- Plotting with
			- `matplotlib`
			- `seaborn`
			- `plotly.express`
  
  
* **Tue 02/14/23 11.59pm - Quiz 3 Due** - Submit in Canvas
* **Wed 02/15/23 11.59pm - Assignment 2 Due** - Submit in JupyterHub			



#### Week 6: Working with tables, steps in data exploration and comparisons
* **Tue 02/21/23**


  - Content & Discussion
	* Reading: `DLF` Ch. 7; `LSD` Ch. 3
	
  - Lab Session
    - Using `pandas` for exploratory data analysis
    - Working with a CSV file in `pandas`
      - Loading data into a `DataFrame`
      - Examining shape
      	- ROWS - observation unit
	- COLUMNS - variables
      - Exploratory analysis of variables
        - Creating summaries
	   - Counts for categorical data
	   - Summary statistics for continuous data
        - Plots
           - Bar charts for categorical data
	   - Histograms for continuous data

* **Tue 02/21/23 11.59pm - Quiz 4 Due** - Submit in Canvas
* **Sun 02/26/23 11.59pm - Assignment 3 Due** - Submit in JupyterHub


#### Week 7: Public data - working with Open Data

* **Tue 02/28/23** 

  - Content & Discussion
    * Reading: `DLF` Ch. 8; `LSD` Ch. 4
    * More `oandas`
    * Reshaping and merging data frames
      - wide to long using `melt()`
      - using `.merge()` and column columns

  - Lab Session
    * Working with open data using `pandas`

* **NO QUIZ THIS WEEK**


#### SPRING BREAK  
* 03/04/23-03/12/23


#### Week 8: Examining change over time
     
* **Tue 03/14/23** 

  - Content & Discussion
	* Reading: `LSD` Ch.5
    - Patterns in data over time
      - Trends
      - Cycles
    	
  - Lab Session
    - Working with temporal data in `pandas`
      - `datetime` index
      - temporal grouping and aggregation
      


#### Week 9: Privacy, Data Storytelling and Web Scraping

* **Tue 03/21/23**

  - Content & Discussion
    * Reading: `LSD` Ch.6
    - Data story telling
    - Examples of investigating data
    - Privacy
    - Example of web scraping to check data

* **Tue 03/21/23 11.59pm - Quiz 5 Due** - Submit in Canvas


#### Week 10: Ways to use data in stories, geodata and mapping and R basics (Part 1) 


* **Tue 03/28/23** 

  - Content & Discussion
	* Reading: `LSD` Ch.7 and tidy chapter
	
  - Lab Session
    - Introduction to R using `tidyverse` and `ggplot`


#### Week 11: Dr Jake Pearl (Guest Lecturer) & R basics (Part 2)
* **Mon 03/27/23 11.59pm - Assignment 4 Due** - Submit in JupyterHub

* **Tue 04/04/23**

  - Content & Discussion
	* Reading:  `LSD` Ch. 8
	
  - Lab Session

* **Sun 04/09/23** - Quantified Self Assignment Due at 11.59pm (Submit through JupyterHub)

#### Week 12: More on networks and network data analysis

* **Tue 04/11/23**

  - Content & Discussion
	* Reading: 
	
  - Lab Session

#### Week 13: Machine Learning and Artificial Intelligence

* **Tue 04/18/23**

  - Content & Discussion
	* Reading: 
	
  - Lab Session

* **Sun 04/23/23** Short Paper Due (Submit in Canvas)

#### Week 14: Final Project Presentations

* **Tue 04/25/23** 


* **05/02/23** FINAL PROJECT DUE (TBC) * Submit in JupyterHub


  
