# UFO Sightings with JavaScript

### Overview of Analysis
The purpose of this analysis is to provide a more in depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. The following additional filters were added to the dynamic table; city, state, country and shape.

### Results
The UFO sightings data is auto-populated on the webpage. There are five search boxes on the left hand side where the user will enter text for specific search criteria. The user can filter one to five of search criteria, and the results will automatically update as a new search criteria is added. In the images below you will see the webpage update the results as a new search criteria is added. 

First, We will begin with no search criteria applied into the filters. 
<img width="1436" alt="filter_original" src="https://user-images.githubusercontent.com/91927712/149710206-d172d0f7-8f38-4d1f-95c5-d481d447d22c.png">

Then, we will add the first search criteria into the date filter.
<img width="1429" alt="filter_date" src="https://user-images.githubusercontent.com/91927712/149710248-51aed97f-5e4a-432d-9b0e-92f975d50703.png">

Finally, we will add search criteria into the city filter. 
<img width="1440" alt="filter_city" src="https://user-images.githubusercontent.com/91927712/149710295-3833e937-60e8-4828-b862-445bf2842b70.png">


### Summary
As search criteria was added into filters we saw the results narrow down, yielding more specific results. I recommend updating the code to accept characters regardless of letter case. As the code is written now, if search criteria is entered in all upper case letters where the data is recorded in lower case format, then the webpage yields no results. This can lead to missing data points and inacurate results. 
