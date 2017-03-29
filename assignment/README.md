# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas.

## Problem / Question

Applications are ultimately just tools. What problem or question does
your application attempt to resolve or grapple with? How does your
application speak to this problem/question?

-The City of Philadelphia recently committed to Vision Zero (reducing traffic fatalities to zero). I’d like to make a map that allows users to view and learn about the patterns and types of crashes that have occurred in Philadelphia. This map would allow the user to scroll around, click on the crash to get information in a pop up or graph on the sidebar, and have tabs or a drop down menu to filter by each mode type.


## The data

Geospatial applications are all about working with data. What datasets
would you plan/like to use? If the data you'll be working with isn't
already stored in a way that you can use, how will you be storing your data?

Using crash data from Open Data Philly. This is the same data set I used for my midterm, but expanded with car modes as well.


## Technologies used

Which technologies covered in class (or discovered on your own!) do you
plan to use? How do you anticipate using each of these technologies?

Review the APIs/online examples of leaflet, turf, jQuery, underscore (or
any library not explicitly covered in class) for functions/uses which
you'd like to explore. Briefly describe how you might use them.

- underscore - filter (by safety issue type)
- jquery - .done for ajax; .filter by safety issue type
- leaflet - popup with information about the crash
- mapbox - potentially using custom marker icons

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users?
- What do they gain from your application' use?
- Are there any website/application examples in the wild to which you can compare your final?


- Users: Transportation enthusiasts, city officials, and residents
- Gain: An understanding of some of the safety problem areas on the road in Philadelphia
- Examples: Portland crash map. http://pdx.maps.arcgis.com/apps/MapSeries/index.html?appid=cf122cd3b4ef46f0ac496b2d61d554e9


#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

- I think I'll stick with the sidebar, which will include a brief description of the map, a legend for any icons, and maybe charts analyzing some of the data.

## Anticipated difficulties

Thinking about weaknesses can be useful. What do you anticipate being
most difficult about this project? How will you attempt to cope with
these difficulties? For example, asynchronous behavior (ajax, events)
are hard to use and think about. Global variables are a strategy for
coping with that difficulty by breaking data out of the asynchronous
context.


- working with ajax calls to the geojson data.
- formatting the popups so the information is clear
- creating different tabs to filter by each mode type
- creating a legible symbology


## Missing pieces

We've only managed to scratch the surface of the available technologies
by which you could construct an application. What use-cases haven't we covered
that you think would be useful? What technologies not covered seem exciting to
you (you don't necessarily have to fully understand what they're for,
this is a chance for you to get our help interpreting a technology's
purpose/usage).

- not yet sure how to create different tabs/pages
