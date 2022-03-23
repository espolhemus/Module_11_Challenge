# Module_11_Challenge
Module 11 - UFO Sightings DB

## Overview of Project
This project involves using HTML, CSS, JavaScript, and D3.js to create an interactive webpage to display data related to purported UFO sightings. 

### Purpose
The purpose of this challenge is to take a JavaScript data file containing records of claimed UFO sightings and use HTML, CSS, JavaScript and D3.js to create an interactive webpage to display both the underlying data and an article that was written discussing the topic, and to enable visitors to the site to filter the data based on their own criteria.  

## Results
The results of efforts are as follows:

### Page on Initial Load

- On initial load, the resulting page appears as follows:

![Page on Load](/Images/page_on_load.png)
 
### Filtering by User Specified Criteria

- In order to filter the dataset based on user-specified criteria, the user can enter values into one or more than one of the following fields:

![Filter Criteria](/Images/filter_criteria.png)

- In order to apply the user-specified criteria, the user simply enters a value into the text box, and then applies the criteria by pressing Enter, Tab, or by using their mouse to click within a different field.  The user can enter multiple filter criteria - however, in order to remove the filters which have been applied, the user must reload the HTML page.

### Results of User-Specified Search

- The results of a user-specified search appear as follows:
 
![Post Filter](/Images/post_filter.png)

## Summary of Analysis
 
### Drawbacks

- The simplistic approach that was taken in developing this solution has resulted in a number of significant drawbacks - in particular, the search criteria is case-sensitive, which is a significant limitation and impediment impacting the utility of the solution, and the fact that the user must reload the page in order to clear any previously-applied filter criteria is likely to result in significant user frustration, and a negative perception of the site. 

### Recommendations for Further Development

There are a number of recommendations for further development, including:

- Adding the ability to sort the resulting table based on the column headings.

- Adding a button to enable the user to clear existing filters and restore the entire corpus of data without having to reload the page.

- Adding functionality to enable searches to be executed regardless of the case of the input values and the values within the dataset.

- Converting certain of the text boxes (e.g. "Country", "Shape") into dropdown menus containing a list of the values that are actually present in the dataset.

- Enabling date-based searches to be performed for periods of time other than a single day (e.g. for an entire month).
