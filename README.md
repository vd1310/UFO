# UFO
## Overview of Project
#### Provide analysis of UFO sightings by allowing users to filter for multiple criteria at the same time and populating the results on the webpage as per the selected criteria. 
#### Purpose
##### The purpose of this project is to allow users to select data as per following filters:
###### 1. Date
###### 2. City
###### 3. State
###### 4. Country 
###### 5. Shape


#### Results: The webpage allows users to enter the multiple filters based on date, city, state, country or shape and then display the results in the UFO table as per the selected filters. When the user enters the filters, the JS code will save the input values in the test box along with the element ids in the JS object. The event listeners in the code will detect the change in the text box values and trigger the filter function to update the table as per the selected criteria. Below are the results based on the input criteria or filters:

###### 1. Single criteria / one filter: Let’s say user enters only one filter which is shape = 'triangle' and press enters. The table on the page will display the rows which have the shape of 'triangle'
![image](https://github.com/vd1310/UFO/blob/main/image(shape).png)

###### 2. Multiple criteria / filters: Let’s say user enters date = '1/4/2010', state = 'ca' and shape = ' light', the table will display only two results as shown below. This was user can narrow down the search to more specific criteria: 
![image](https://github.com/vd1310/UFO/blob/main/image(multiple).PNG)


## Summary
##### 1. Drawback: The source data is static / limited to a specific year. The input elements (text box) don’t provide information of the possible values that can be selected as filters.
##### 2. Recommendations:
###### 2a. Use web scrapping to update source data
###### 2b. Instead of text box as input elements, use drop downs with placeholders’ values to provide information to users about the possible input filters.

