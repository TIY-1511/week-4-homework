# week-4-homework

## Add Restuarants to Explore

Add Restaurants to Explore

Note: these restaurants should not be linked to the hotels in anyway at this  stage

Within the explore application, start the Rails server

Open the site in the browser and enter the following URL: 

localhost:3000/restaurants


Check that the page has a routing error.

Add a "named" route that specifies a `restaurants` controller and an `index` view.


Add the `restaurants` controller and the index action (method).

Make sure that that a `missing template error` is now visible in the browser.


Add the `index.html.erb` template in the folder `app/views/restaurants`. 


Put some static data in this file which shows some restaurants.


Create a `restaurant` model (singular) with fields and run the migration - `rake db:migrate`


Create restaurants from the Rails console. 


Use this data in the application, so that these restaurants are shown on the view.


### Bonus: files

Read through this repo and try out the code:

https://github.com/TIY-1511/files
