# Date-with-Destiny (revised)

Created with Ruby on Rails, SQLite3, and uses data from the Foursquare API.

A date-making app that is designed to help users make decisions on three date locations- an Activity, a Restaurant, and a Nightlife spot.

The app randomly generates these locations based on an user-inputted address which is translated to latitude and longitude by the Geocoder gem.
The latitude and longitude are then provided to the Foursquare api along with a relevant activity category to find a small sample of venues in the area, which are randomly sampled to provide a full plan for the user.

The user can then choose to save, edit, or delete their plans as they see fit.

Each user has their own account, managed with the browser Sessions object, which they can log in and out of and access their persisted plans with full CRUD (Create, Read, Update, and Destroy) functionality.

This app uses RESTful Routing patterns for Sessions, Users, Plans, and show pages for Nightlives, Activities, and Restaurants.

To run, fork and clone this repository, open 'date-with-destiny/mod2-project/' in your console and start your rails server (type 'rails s' into your console). Navigate to the webpage your server specifies (often this will be localhost:3000), create an account, and start making dates!
