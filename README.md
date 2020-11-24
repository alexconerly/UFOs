# UFOs

## Overview of the Project

The purpose of this project was to assist a client named Dana in utilizing HTML, CSS, and JavaScript to create a customized, dynamic webpage about UFO sightings.  This webpage featured a dynamic table of the UFO sighting data with corresponding input boxes, allowing users to input multiple criteria simultaneously to filter the associated table.  In order to create the dynamic webpage, JavaScript functions were created to add data to the htmal "tbody" tags and the script was implemented into an HTML page, while Bootstrap was employed to give it some aesthetic styling.  Additionally, a page header, article title, and article summary were included and the code was tested along the way using chrome devtools.  Ultimately, the webpage exhibited a nicely formatted, interactive user experience for filtering the data table according to date, location (city, state, and country) and/or the shape of the UFO object reported.

---------------------------------------------
## Resources:

Data Sources: data.js

Software: 

Chrome DevTools 86.0.4240.198, Visual Studio Code 1.49.2,
Bootstrap 3.3.7, HTML5, ES6, D3

---------------------------------------------

## Results

As a result of the webpage creation, filtering a search is as simple as inputting the desired criteria into one or more of the filter boxes and pressing "enter".  For example, upon visiting the webpage, the data table begins unfiltered.  You can also refresh the datatable by clicking "UFO Sightings" on the top left corner as shown below:

![](Resources/refresh_btn.png)


With the page refreshed, only "placeholder" values are given in the input boxes and the table will display all unfiltered dates, locations, and shape descriptions of the UFO sightings as shown here:

![](Resources/unfiltered.png)

In order to filter the data table, the user may choose to input selection criteria for any number of input boxes by using the format shown by the placeholder values.  Once the preferred input boxes are filled to taste, the user only needs to press enter and the table will filter accordingly.  For instance, here is a filtered search for UFO sightings reported in the United States within the state of Oregon.

![](Resources/Oregon_us.png)

Here is a convenient link to the actual website to test it out if desired:

https://alexconerly.github.io/UFOs/


## Summary

From this analysis, it is clear that by incorporating html, csss, and JavaScript, one can very quickly and effectively create an exciting and interactive dynamic website that is highly flexible.  However, there are indeed some drawbacks to this particular design.  For one thing, this dynamic webpage does not allow filters for all columns of the table.  In particular, it does not filter the column headers of "duration" or "comments" in any way.  

As such, one initial recommendation for further development would be to update the html list items to include these other columns as filter criteria.  Of course, filtering these columns could be more challenging than filtering the other columns because the currently filtered columns are already formatted consistently, making it easy for the user.  Therefore, as a second recommendation, it may be advantageous to manipulate specifically the "duration" column to make it user-friendly when filtering.  This could be done, possibly using python and regex, to organize the column into a format which may be more easily filtered.  For example, one could change all the values for the "duration" column to be in the format of "# minutes" and that would make filtering an input as simple as typing in the number of minutes followed by the word "minutes".

As a sidenote, the initial motivation for this project was to aid the client named "Dana" in discovering UFO sighting information about her hometown of McMinnville.  However, this dataset from the given JavaScript array did not include amy McMinnville data.  Nevertheless, the dynamic webpage may still help Dana to see how such a site may be useful for her if she were to create one herself.