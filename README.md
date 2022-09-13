# UFOs

## Overview of analysis
An in-depth analysis of UFO sightings and allowing users to filter for multiple criterias at the same time.

## Technologies
  * Javascript
  * HTML
  * VS Code

### Deliverable: Filter UFO sightings on multiple criteria

  * The list element that creates the button is removed, and there are five list elements for filtering in the index.html file.
  * The event listener is modified to detect changes to each filter in the app.js file.
  * The updateFilters() function saves the element, value, and the id of the filter that was changed.
  * The filterTable() function loops through all of the filters and keeps any data that matches the filter values.
  * The webpage filters the table correctly based on user input.

## Results
The user is given 5 search functions. You can manually input the date, search by city,
<img src="Resources/by%20city.png" width="75%" height="75%"><br>
country<br>
<img src="Resources/by%20country.png" width="75%" height="75%">,<br>
state and even the shape.
This allows the users a more refined search. 

## Summary
One drawback i found is that the search info typed needs to be exact. Upper and lower case also need to be specific.
I recommend refactoring the code to where if someone were to type "spring" for instance, you'd get a hit for "spring valley".
I'd also recommend fixing the upper and lowercase issue. That could easily lead to a bad experience.
