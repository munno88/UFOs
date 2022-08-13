# UFOs Sightings - a JavaScript Assignment

Using JavaScript to build dynamic webpages and other customization tools that include Bootstrap, HTML, and CSS.
  
## Project Overview

The purpose of this project was to learn how to take data that is stored as a JavaScript array or list and create a table to organize the information that will       visually adjust as "events" change (i.e. filtering). In order to react when an element is changed, we use Javascript functions to loop through the data to build the table and create a customized dashboard. The customizations include filters with event listeners that will record the information when an element has changed and develop an interactive webpage. Filters can be applied in many ways. In this exercise, we reviewed how to display default data in the table, listen for a button click or trigger the table to update based on the user's input with a select criteria. Finally, we use HTML, Bootstrap and CSS to read the Javascript code and create a webpage that is easy to view, includes filters, images, and a synopsis of the topic.

##  Topic

Are we alone in this universe? UFO sightings have been an obsession among many for centuries. Are they real or some government conspiracy? We have been tasked to help Dana with building a webpage in which others can access information of reported sightings and see for themselves. This webpage should include:

•	A description or summary of the topic
•	A table to display all of the information from the data source
•	Search filters that will allow for visitors to update the table based on the search criteria they enter.

![ufo](https://user-images.githubusercontent.com/103727169/184516226-ca3fd97c-2dac-4500-8a57-2c116d14192b.png)



##  Results

The webpage UFO Sightings - The Truth is Out There has been created. Upon entering, visitors embarking on their "first encounter" will see:

![first_encounter](https://user-images.githubusercontent.com/103727169/184516243-c73ff4b9-237e-44a3-8ce4-45cbbf3bf8c4.png)

You will notice that a "Filter Search" section has been added.


![filter_search](https://user-images.githubusercontent.com/103727169/184516311-9a02ad5a-7ee8-4972-9765-f33c4848ee57.png)

You can filter by one or all of the search criteria shown. For example, if you search by "City", you will see that the table updated to show the reported sightings that was recorded for that specific city.

![city_search](https://user-images.githubusercontent.com/103727169/184516319-5147b395-d6f0-4749-9554-c91b3f898036.png)

If you add a shape, the table will update filtering further to only display the information containing that shape.

![city_shape_search](https://user-images.githubusercontent.com/103727169/184516327-3ebe4e0e-819c-4940-9618-9daa2e1d4349.png)

Or if you delete your previous entries and enter "State" and "Shape", the table will update using your new criteria.

![state_shape_search](https://user-images.githubusercontent.com/103727169/184516336-f6fea6ac-2da1-468c-b378-e968a9212717.png)


# Summary

##  Drawbacks:

##  Unfortunately, the page has several drawbacks. They include:

1.  The search field is "case-sensitive". The table will not update if you do not enter exactly how the data is stored and does not allow for partial entries. This is an issue because it does not intuitively tell the user how the information should be entered other than the "default" example shown.

2.  There is no button to click, wording or action that tells the user that the table will update after you hit "enter".

3.  The data is limited and outdated since it is not linked to a "live" source.

##  Recommendations for further development:

With the following enhancements, it can greatly improve the user's experience.
1.  Add additional customizations, such as click-buttons, dropdown list, and/or auto-fill that can help "guide" the user and make the page more interactive.
2.  Add functionality to pull the data from a live source that includes current and archived data not limited to only the United States, but globally.
3.	Add a "Latest News" section that will highlight an article showing the most recent reported sighting.
4.	The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases. 

    ![space_txt](https://user-images.githubusercontent.com/103727169/184516633-a099d6b9-f3f8-4183-9dcb-ee23ac731ceb.png)


5.	A filter on a date range might be preferable than a singular date. Typing 1/2010 did not bring up all the dates from January as hoped. Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month. It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings.

    ![month_search](https://user-images.githubusercontent.com/103727169/184516646-d8743cb5-11d3-4189-84b7-d2f3e452b603.png)

 

