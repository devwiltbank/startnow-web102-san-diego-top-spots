**********************************
San Diego Top Spots

This little app has names and descriptions of fun things to do in San Diego, with a link to show it in google maps.

Need to include the index.html, data.json, jquery.js and main.js files.

Tasks
Using the command prompt open the project folder in VS Code: code ~/oca/startnow-web102-san-diego-top-spots.md
Run: npm install
Write your code in the index.html file and a corresponding main.js file.
Add a title to the page with 'San Diego Top Spots' as the text.
Add an H1 with 'San Diego Top Spots' as the text.
Create an HTML table structure with the headers you see in the image above.
Also make sure you reference your main.js before the </body> tag.
Write the following JavaScript in your main.js file:
Use the $.getJSON method to download the contents of the data.json file.
Iterate through the top spots and create a table row for each spot.
Create a link to the location using the longitude and latitude provided. (Example https://www.google.com/maps?q=33.09745,-116.99572)
To start/test your application in your browser - Run static . to start a web server that you can access by going to http://localhost:8080. You MUST follow this step and use a static web server in order to read in the contents of a file on your local file system as required in this project.
Bonus
Once you have completed the tasks and your tests have been submitted, push yourself farther by attempting the following bonus items:
Display a map, and using the google api, place a pin in the location of each top spot
When a users hoovers over the pin display a tool tip with the description
Using the current location, get directions for the user to get to the location
Display the distance to each location from users current location on the row in the table
Sort the top spots based on distance from users current location
