# UFO Sightings

## Overview 
This UFO Sightings project is to help our client, Dana, build a webpage and a dynamic table with the ability to provide the end user to filter a dataset of UFO sighting in the world by multiple criteria such as date, city, state, country and shape of the sighting.  

### Purpose
The purpose of this project is to build an HTML webpage using Javascript, practicing skills that include built-in Javascript functions, arrow functions, forEach loops, and filters. 

## Results
The UFO Sightings Webpage is very user friendly. Below is the what the webpage looks like when a user pulls up the webpage. 

![Screen Shot 2022-01-09 at 10 18 52 AM](https://user-images.githubusercontent.com/92831268/148696885-325d3377-9d81-43a9-bb12-279d06b85ee1.png)

The User will go to the "Filter Search" section of the page. A user can search for a sigting based on only one criteria, as shown below. The below search is for sightings only in the city of El Cajon. 

<img width="1414" alt="Screen Shot 2022-01-09 at 11 08 20 AM" src="https://user-images.githubusercontent.com/92831268/148696991-3d5c7a9e-9e3c-422a-aa8c-1e6320f21858.png">

A User is also able to search based on multiple criteria. The below search is for sightings that occur in Florida and have a Sphere Shape. 

<img width="1412" alt="Screen Shot 2022-01-09 at 11 12 03 AM" src="https://user-images.githubusercontent.com/92831268/148697078-dd3e5769-5035-4b0e-8214-6f9dbb86633c.png">


## Summary 

# Date Ranges
One drawback to the search filters is for the dates. The user would have to know the exact data of a UFO sighting in order to search for a specific sighting. If a user were trying to do research on a date range, for example all of the sightings in a certain location for the month of June in 2007, they would be unable to do so because the criteria needs a month/day/year specific input. One recommendation I would have is to be able to finter by a range of dates instead of one spefici day. 

<img width="1416" alt="Screen Shot 2022-01-09 at 11 20 55 AM" src="https://user-images.githubusercontent.com/92831268/148697459-c8ad2018-4675-4abd-95e2-a9aa9e2a68d1.png">


# Exact Matches
In order to use the filters, the search inputs ahve to be exact matches for the filters to work properly. For example, if the used wanted to search for all of the sightings in Grants Pass, the user would have to input in the search criteria "grants pass" because that is how the city is written in the data.js file and we have filtered for an exact match. If the user were to input "Grants Pass" using capitol letter, the output would appear as below with no data entries. If the user did not have knowledge of the data.js file (or the search filter on the beginning of the page did not show 'grants pass' as one of the first entries), the user would likely think that there were no UFP sightings in Grants Pass. A recommendation would be to have the search filter loosely equal to the search, rather than an exact match. 

<img width="1418" alt="Screen Shot 2022-01-09 at 11 24 04 AM" src="https://user-images.githubusercontent.com/92831268/148697500-e7cd6fc9-723e-4a3e-a402-5a549108ec2a.png">



