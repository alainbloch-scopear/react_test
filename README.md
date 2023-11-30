## React Technical Interview

The objective of this technical interview is to develop a movie browsing page.

The data for the app is in `db/db.json`.

We've added a small server that you will need to run in order to interact with these endpoints. We've also added a script in your package.json file to run the server `"start-api-server": "json-server --watch db/db.json"`

Please make sure to clone this repo. When you are finished please provide a link to the repo so we can take a look.

To get started  
- Run `bin/setup` to install dependencies
- Run `yarn start`

In total that means you'll need 3 termimals. 

Next are the requirements. It will be helpful to read all the requirements before beginning.

1. Create a screen that displays a list of genres. The endpoint http://localhost/genres is already provided for you. You can style the list any way that you like. You will need to make sure that each list item has some kind of icon that will later be used to navigate to another screen. Users should be able to scroll through the genres. Another thing to note is that the Genres will NEVER change. 


2. Next we want to see all of the movies for any given genre when a user clicks on the icon to the right of the  Unfortunately there isn’t an endpoint that lets you filter the data you get back from an endpoint. This means you’ll have to filter the results yourself each time. Just like before you can style the list any way that you like. And just as before you will need to make sure that each list item has some kind of icon that will later be used to navigate to another screen.The user should be able to navigate back to the list of genres from this screen.

3. Last we want to view the details of a specific movie from the previous screen. For example if they choose Beetlejuice above they should see the details for Beetlejuice. Please take notice of each component of the screen. The user should be able to navigate back to the list of movies from this screen.

  




