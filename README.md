This is an old personal website [repository](https://github.com/krmannix/personal-website)

I want to convert these static files to one with a nodejs backend

<h3>DBs</h3>

#Table set up:

	 ___________________ ___________________________ _________________________ _______________________ _____________
	|         		    |		                    |					      |						  |			    |
	| title (VARCHAR 50)| description (VARCHAR 700) | image_src (VARCHAR 200) | link_to (VARCHAR 200) | date (DATE) |
	|___________________|___________________________|_________________________|_______________________|_____________|


<h3>To Dos</h3>
* Create local img folder with all files
* Populate Postgres DBs
	* Create tables ~~projects~~, hobbies, experience, events
* Create routes to return all rows in each table
* Ensure routes return proper JSON
* Markup 1 HTML & CSS with fake data
* Plug into calls to back-end node server
