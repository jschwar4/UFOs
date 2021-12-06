# UFOs
1.	The purpose of this project is to build a filterable webpage for UFO sightings. The filters make a database of sightings searchable by date, city, state, country, and shape. Searching outputs the requested information in a dynamic table format to allow the user to see all data for a specific query.
2.	Searches are performed by entering the desired query into the corresponding search box and then clicking elsewhere on the page. 

a.	The search allows for single-criterion searching:
<img width="1082" alt="UFOs - Single Search Criterion" src="https://user-images.githubusercontent.com/90073490/144796153-18e934b7-3747-4d0f-8882-3c10300e893f.png">
b.	The search also allows for multiple search criteria, and displays all rows that match the whole query:
<img width="1356" alt="UFOs - Two Search Criteria" src="https://user-images.githubusercontent.com/90073490/144796192-5a063f2f-3da2-4876-b22c-8167a648a07d.png">
c.	The search also requires that the search term match the data exactly, such as the date below:
<img width="1054" alt="UFOs - Exact Date Match" src="https://user-images.githubusercontent.com/90073490/144796254-596fa18d-83b3-48b4-a975-77c5c5f4c57c.png">
3.	

a.	Drawback: 

i.	A major drawback of this webpage is that the search cannot match partial strings. For example, a search for “bent” in “city” will not return the row for “Benton.” 

b.	Further Development:

i.	The page could be improved such that the matching function searches each item for any matching partial string by parsing each string into a set of characters and looping through for a match, or by using regular expressions.

ii.	The page could also allow for searches along the Duration and Comments axes as well, a functionality that would be greatly improved by adding partial string searches as well.
