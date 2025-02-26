[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/4GNtqois)
# Hierarchical Data Project: Explore Data Using a JSON Dataset

## Assignment Summary 

Project 3 is a core component used to assess your learning of the course content in DA 210 / CS 181 and your ability to work together to build upon your existing skill sets. You must complete the project as a team of 2-3 students. (Partners/teams are your choice for this assignment.)

This project will ask you to interact with data in the JSON format, using some concepts that are new to you regarding the hierarchical data model, and it will build on what you have already learned and practiced all semester, including working with dictionaries and using pandas to manipulate data. You'll be asked to use your now well-developed collaboration skills and your knowledge of Python operations to explore a central topic or research question of your choosing.

## Assignment Purpose

This assignment asks students to fulfill the following learning goals:

- Show your ability to work with a real-world dataset
- Demonstrate knowledge and correct application of variable types, data structures, documentation, and readable code patterns
- Move beyond the "recipe following" mentality that comes with first learning a method
- Apply code that you have learned into the framework of the data analytics cycle, with a focus on data description and exploration
- Effectively communicate what was learned in a polished .html report document
- Use collaboration and version control to document and generate reproducible code

These learning goals are crucial to data analytics and computer science curriculum because hierarchical data is often a core component of external data pipelines, especially when accessing data via API. In our previous units, we learned tabular and relational data address complexities of one-to-one, one-to-many, and many-to-many relationships in different ways. Understanding how hierarchical data addresses these issues is equally crucial. 

## Assignment Details

The core tasks of this assignment are to choose a JSON data source, make your data tractable in Python, and compose a data story that mixes narrative elements with data exploration strategies. 

### 1. Choose a Data Source:

Beginning with the list of options below, look for a data source that speaks in some way to your interests or areas of familiarity:

1. Newspaper and text data: Chronicling America (https://chroniclingamerica.loc.gov/about/api) has excellent resources, and their data is available in json format. It includes a massive searchable archive of newspapers.
2. Reddit data: Small samples via Reddit's public API (https://www.reddit.com/dev/api/) or very large downloads via https://academictorrents.com/browse.php?search=reddit
3. NASA API data: https://api.nasa.gov/ 
4. Weather data: https://www.meteomatics.com/en/api/response/json/. 
5. City data: San Francisco and New York City Open Data both have extensive online and freely available datasets; some are available in json format. 
6. Star Wars character universe: https://swapi.dev/ 
7. Pokemon data: https://pokeapi.co/ 
8. Quandl financial data: https://data.nasdaq.com/tools/api 
9. Free APIs, many don’t require authentication: https://github.com/public-apis/public-apis
10. Find your own source, and get it approved with your professor!

__Notes:__ 

1. You may choose to include more data sources if you want to, but this is not required. 
2. If you have a different JSON format dataset in mind that is not from the list above, you may email the professor to seek approval. Datasets should be chosen with the goal of exploring a particular topic. It should be clear that you have permission to download and use the data, and all datasets should have some sort of metadata available or explanatory information you can find online. Please do not propose using a JSON dataset from Kaggle, as these are typically insufficient for the assignment. 

### 2. Make your Data Tractable in Python 

Write Python code, as needed, to import all data from JSON, convert to tabular formats, and subset/sample in ways that make sense for your project. For the most part, this assignment component will involve mixing standard Python and pandas code in ways that makes sense to your specific dataset. Since JSON data is hierarchical, converting it to tabular format will likely require generating more than one DataFrame/table. 

__Note:__ Unlike projects 1 and 2, there are specific technical requirements for this assignments other than using an appropriate JSON data source and writing Python/pandas code, as needed, to complete the assignment. 

### 3. Data Story

Your submission should synthesize storytelling elements (writing and visualizations) with the various data exporation strategies you employ. As with previous assignments, it should mix Python code and markdown text to tell a compelling story focused on a topic or question. You will create your data-driven stories using Jupyter Notebook files, and you will submit your work in both `.ipynb` and `.html` formats. Submissions should adhere to the following formatting guidelines: 

| Component        | Description                                                                                                                                                                                           |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Title            | Brief and informative, gives some idea of your core question or topic area.                                                                                                                           |
| Introduction     | Include core background information and ethical considerations relevant to initial data collection and contemporary use of the data. Articulate your core question or topic area.                     |
| Data Exploration | Use a blend of descriptive statistics and data visualizations to explore your core question or topic. Include code blocks. Discuss potential areas for deeper analysis based on the data.             |
| Uses of Python   | Take a step back and analyze your own use of code. Provide some rationale for choices you've made. Considerations may include performance, human readability, code dependencies, and reproducibility. |
| References       | List all works cited in the data guide. Use proper APA format.                                                                                                                                        |


## Assessment Criteria 

Submissions will be evaluated on technical execution; research and writing; and how well the submission comes together as a whole. The following descriptive rubric will be used when grading.

### Technical Content

- data files imported properly 
- attention is paid to the complexities of the source data (missing data, coded values, sample weighting, etc.)
- hierarchical data structures are used critically and support the data story effectively
- primary code and helper functions are used properly
- data visualizations are properly coded, sufficiently polished, and used effectively in support of the data story

### Research and Writing

- sufficient attention has been paid to proofreading
- external sources are used to enhance the submission, and sources are properly cited (APA style)
- the project is well organized, flows logically, and follows the all formatting guidelines
- the submission's use of language is appropriate for a well-informed, less technical reader

### Big Picture 

- all materials are turned in on time and in the right place
- assignment directions are followed, and all required components are included in the submission
- proper documentation and version control methods are used to facilitate collaboration and reproducibility
- the submission provides sufficient details or points to supplementary materials that make the research reproducible (e.g. detailed footnotes, appendices, links to GitHub, etc.)
- submitted materials build on multiple takeaways from the hierarchical data unit and synthesize them effectively

## Assignment Details

__Accessing Assignment Files:__ via Github Classroom (linked on Canvas site) and external resources (for JSON data)

__Teams:__ 2-3 students per team (chosen by students)

__Required Files:__ Jupyter Notebook (`.ipynb`) data story; `.html` version (using "Download as" feature); and any imported `.py` files

__How to Turn it in__: Upload html on Canvas and upload or push all `.py` and `.ipynb` files (not `.db` or `.csv` files) on Github

__Due Date:__ By midnight on Friday, December 13, 2024.
