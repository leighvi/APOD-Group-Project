Currently I have the project set up with html templates, controllers, services, routing between pages and the http request working. 

In the services.js I have a service called getDataService, this is called from the mainCtrl which is the controller for the main page. 
This returns data from a http request to the nasa website for the APOD data using an api-key I have signed up for us.
The main controller then outputs this data to the main page template.

The http request currently sends back the data for as many days as are chosen in the settings page.

The settings page is set up with radio toggles for today, 7 days and 14 days. They currently do nothing. There is an empty settings controller set up.