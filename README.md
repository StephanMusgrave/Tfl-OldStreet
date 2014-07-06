TFL - Old Street Arrivals 
===
We created an app that checks the arrivals at Old Street Underground Station, London from the Traffic for London live data stream. It updates itself every 10 seconds, however the TFL API is slower most of the time.

![](public/oldstreetarrivalapp.png)

Heroku
----
[App on Heroku]

Objectives of exercise
----
Learning to implement apps using a novel API in a Javascript environment.

## Technologies used
|Technology                 |Used for                        |
|---------------------------|--------------------------------|
| Javascript |programming alanguage for websites|
| Jquery |a cross-platform JavaScript library designed to simplify the client-side scripting of HTML
 |
| Mustache.js |a simple web template system |
| Underscore.js |a JavaScript library which provides utility functions for common programming tasks |
| HTML5 |HyperText Markup Language: the standard markup language used to create web pages |
| CSS3 |Cascading Style Sheets: a style sheet language used for describing the look and formatting of a document written in a markup language |
| [TFL API] |Transport for London's application programming interface , enabling a query from an application to receive a bespoke response, depending on the parameters supplied |


How to run it
----
```sh
git clone git@github.com:StephanMusgrave/Tfl-OldStreet.git
cd Tfl-OldStreet
open tfl_oldstreet.html
```

Pairing Partners
----
[Steve Musgrave],[Nico Saueressig]

[Steve Musgrave]:https://github.com/StephanMusgrave
[Nico Saueressig]:https://github.com/NicoSa
[TFL API]:http://api.tfl.gov.uk/
[App on Heroku]:http://tfl-oldstreet.herokuapp.com/
