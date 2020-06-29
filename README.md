# Module 1 Final Project

## Introduction

This project focused on three particular sets of data collected from multiple files to answer specific questions about movies and movie studios in order to help a new studio understand the market. The new studio needed information on what the most popular movies are and the finacial analysis of other studios to determine their decision making. 

### Methods Used

*Python Libraries
*Pandas Dataframe Cleaning
*Pandas Dataframe Joining
*Data Visualization

### Technologies

*Python
*Pandas
*Numpy
*Matplotlib
*Jupyter

## Project Description

    The project consisted of three major questions to help a new movie studio on what to focus their attention on when creating movies. The first question raised was: 'What are the top 25 ranked movies in the IMDB and TMDB datasets and how do they compare to each other?'. A data set for each website was compiled to build a dataframe containing the top 25 movies from each website. Since each website does not limit the voting for any movie in their database, movies that did not receive enough votes was not considered valid for the top 25 list. Bar plots were used to visualize the data collected and answer the first question.
    The second question was: 'What are the top five highest earning movie studios and how do their earnings compare to one another over the years?'. The Box Office Mojo website contained the information required for answering the second question. This data was initially cleaned to replace null values and convert the necessary columns to numeric data types in order for the information to be plotted. The data was then grouped and sorted to produce a top 5 earning movie studios dataframe than could be plotted as a line plot. The plot allowed for a better grasp of the information required to answer the second question.
    The third, and last question was: 'Does the production budget of a movie have any influence on the worldwide earnigs of movies, or do the two not impact each other?'. The tn.movie_budgets file contained the information required to answer the question. The data was extracted and placed into a pandas dataframe. All of the budget information had to be converted into numerical data types in order to plot the information. Once converted to float64, the data was plotted on a scatter plot to view how the production budget of a film related to the worldwide earnings of that film. The trend from the plot showed that increasing the production budget of tends to result in increased worldwide earnings from the movie, thus answering the third question.

## Getting Started

1. Fork and clone the repository
2. The data used for the project is found in the zippedData folder ('zippedData/file.csv')
3. Open the student.ipynb file to view the code http://localhost:8888/notebooks/student.ipynb

## Featured Analysis

*Presentation (http://localhost:8888/files/presentation.pdf)
*Blog (https://wblakedalton.github.io/module_1_final_project)

## Contributing Member

**Blake Dalton (https://github.com/wblakedalton)(@wblakedalton)