#Knappsack

###Collaborative project designed to integrate a personal travel itinerary/calendar with Yelp search results into a single-page application
built by [Steven Chow](https://github.com/enlightenone), [David Maupin](https://github.com/dmaupin) and [Greg Rock](https://github.com/grock006).

See online here: [Knappsack](http://knappsack-wdi.herokuapp.com)

##Technologies:

This project was built using [Ruby on Rails](http://rubyonrails.org/), [AngularJS](https://angularjs.org/) and PostgreSQL.

##Data Source:

Search results are pulled from [Yelp](https://www.yelp.com/developers/documentation) using a custom search and filtering system built with AngularJS
and Ruby on Rails.

###AngularJS:

AngularJS is a JavaScript model-view-controller framework that allows dynamic updating of webpage elements. It was utilized in the Knappsack Project in order to update search result filtering without page refreshes. It also allows search results to be added to [UI Calendar](http://angular-ui.github.io/ui-calendar/), a complete Angular Directive for the [Arshaw FullCalendar](http://fullcalendar.io/).

###APIs:

APIs were built for the application in order to consume the data for the visualization. These APIs return JSON-formatted data on:

* User Itinerary/Events
* Yelp Search Results, filtered by Restaurants, Arts & Entertainment and Music Venues


