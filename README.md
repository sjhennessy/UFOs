# UFOs

## Overview of Analysis
The purpose of the challenge is to analyze the UFO sightings data and allow users to filter for one to five criteria. The criteria for searching the UFO dataset is the 1) date, 2) city, 3) state, 4) country, and 5) shape of the UFO sightings. The index.html file contains the code for the layout of the UFO webpage. The app.js file contains the javascript code that saves the element, value, and id of the filters that were changed. There is also an event listener in the app.js file to detect changes to each filter. Finally, a function was created in the app.js file to loop through all of the filters and keep any data that matches the filter values. The UFO webpage is a user-friendly site that correctly filters the original table based on user input. 

## Results
The webpage is intuitive and users have 5 choices for filtering UFO data. For example, in the png file titled "Jan 12 Oregon" in the UFO file, two of the five filters were used. The first filter was the date of 1/12/2010 and the other input was the state of Oregon. The remaining three filters (city, country, and shape) were left untouched by the user. The resulting table had two rows with one of the sightings in Eugene, OR and the other in Springfield, OR on January 12, 2010.

Another example of the utilization of the webpage is in the png file titled "Jan 10 El Cajon triangle" in the UFO file. The user inputed values for all five of the fields. The date of 1/1/2010 was entered along with the city of El Cajon, the state of CA, the country of US, and the shape of a triangle. The resulting table showed two rows that meet the criteria inputed by the user.

## Summary
### A drawback of the UFO webpage
One of the drawbacks to the UFO analysis is the small sample size of the UFO sightings. The list is relatively short compared to other datasets analyzed in the class, and I recommend adding more UFO sightings from other states to get a broader view of the frequency of sightings.

### Two additional recommendations for further development
#### Source Information 
The webpage also doesn't contain information about the source of the data, and I wondered about the qualifications of the sources. Did the data come from people that lived in the towns or trained scientists in the area of UFOs? The credibility could be increased if source information was included. One more column with the source should be added to the data and a webpage user would be able to filter for "citizen", "amateur ufologist", or "scientist", for example.

#### Expansion of Dataset
Another recommendation for further development is to add additional dates to the dataset. The current dataset has a very short range of January 1, 2010 to January 13, 2010. A broader range of at least 6-12 months would give webpage users a more comprehensive view of the UFO sightings.
