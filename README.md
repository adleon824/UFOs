# UFOs


Overview of UFO Analysis

The purpose of this analysis is to begin the journey of learning JavaScript by applying its technical capabilities we learned in this module to the field of data analytics and visualization. We assisted Dana with a project about an article she is writing about her hometown McMinnville, Oregon, which is apparently famous for its UFO sightings that date all the way back to the 1950s.  She used a JavaScript file she received to create a webpage for her story and make the data available for anyone who visits. We built a dynamic webpage by inserting Javascript into a HTML page.  I also used my knowledge of CSS and Bootstrap to build and style the page for consistent functionality, in addition to Chrome Dev Tools to test the code created for the webpage.

I created a table to organize the UFO data that is stored as a JavaScript array, or list.  This table will have the ability to filter data based on certain criteria.  The webpage displayed Dana's article and gave the visitors of the page the opportunity to interact with the data and search for UFO sightings based on how they filter the data.


Results

We will describe how someone might use the new webpage by walking through the process of using the search criteria.  First, look at the three images attached in the repository.  There are five criteria provided for the "Filter Search": date, city, state, country, and shape.  As well, there are potentially seven results for each search: date, city, state, country, shape, duration, and comments.  It will be necessary for the user to match one of the five criteria provided with data in our JavaScript file in order for a result to be returned. Next, in order to begin a search of the data, enter a word that describes one of the five search criterias.  For example, if you notice there are sample words that are nested in the search boxes.  You must type the appropriate information into one or more of the boxes and then click the enter button on your keyboard to intiate a search.  After that, it is not necessary to fill in each box in order for information to be returned.  You'll see in the first image that only the "Enter a City" box was chosen and information on every event in our data that occurred in that city is returned in the search.  The same is true for the second image that demonstrates what will happen when only a shape is known and nothing else.  The result is every event that matches the filter of "shape" is returned from the data linked to the webpage.  Finally, if someone has a specific event in mind and all five of the criteria are chosen, the results are very specific.


Summary

The webpage we created functions well and easy to use but there are some improvements that could be made to make it even better.  We are limited to searching only the data in the JavaScript file we received.  We could increase the users availablity to more data by linking the webpage we created with several other pages with similar goals that will have their data file to access, as well.  We can constantly update the webpage with new searchable data through a process called web scraping which allows us to share your data with other webpages and vice versa.  Another improvement we could add to the webpage is to give any user who visits the opportunity to share their own experiences with UFO sightings to help contribute to the available data on UFOs.  
