I will assume you have XAMPP or another program of the same type installed (LAMPP etc).

Unzip this file into your htdocs folder of your XAMPP installation as we had to do for kevins AJAX labs.

You will need to then have your XAMPP running and input http://localhost/G00341279_G00329882_G00341284/www/ into your browser to run the html to view the project working.

Currently I have the project set up with html templates, controllers, services, routing between pages and the basic http request working. 

In the services.js I have a service called getDataService, this is called from the mainCtrl which is the controller for the main page. 
This returns data from a http request to the nasa website for the APOD data using an api-key i have signed up for us.
The main controller then outputs this data to the main page template.

The http request currently only sends back the data for the current day.

The settings page is set up with radio toggles for today, 7 days and 14 days. They currently do nothing. There is an empty settings controller set up.