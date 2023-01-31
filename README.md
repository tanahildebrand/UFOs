# UFOs

## Overview
For this challenge, we were given an database of UFO sightings, including the city, state, country, description, date and shape of the UFO siting. We were asked to make a webpage to easily view the results. Included in the page was the ability to filter the sightings based on the criteria included in the results. The task was accomplished using JavaScript. 

## Results
The website can be easily used by those familiar with basic filtering on commonly designed websites. Using the left-hand side of the screen, the end user can manually enter one or many filter criteria using free-text entry, and click "Filter Table" to see the results that match the search. The results will appear on the right-hand side of the screen. Should the user wish to reset the search, they can click the website page header to revisit the standard search showing all results.

An example of a search performed for sightings in Ohio is below.

#### UFO Search for Ohio Sightings
![UFO Search](/images/UFOSearch.png)

## Summary
While the filter process is operational, it is not optimized. The process requires the user to know of the options to be able to search to return results. In addition, the user can only search for one date at a time, not see a span of sightings across many dates. To enhance this I recommend the following:
  1) Create graphs of the overall sightings by date (line graph), location (bubble chart overlaying a map) and shape (bar graph). This will allow the user to see the overall features of the data at first glance. The charts could also update dynamically based on the filter criteria.
  2) Remove the free-text entry in the search fields, replacing it with drop-down options that pull from the underlying data. For example, the shape field would show all options for the shapes.
  3) Adjust the date filter from a single response item to a two date response. Users can enter the from and to date to see all results within that range. This still allows the results to appear for a single date, while also allowing the results to span many dates.
