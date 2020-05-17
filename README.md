#  Todoey

This app was created as a part of a [Udemy course](https://www.udemy.com/share/101WsWAEMScldUQn8F/) I am taking (May 2020). 

The goal: to create a To Do List app to keep track of your tasks. We went over several methods to persist data, but the final project utilizes Realm. Flat colors come from [Chameleon Framework](https://github.com/wowansm/Chameleon/tree/swift5) and “Swipe to Delete” functionality uses [SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit)

During the lesson module, I noticed a small bug in which cities with multi-word names (e.g., "New York" or "Salt Lake City") would throw an error, because the url string was not converting the whitespace character to "%20". This fix has been incorporated into my final code.

## Lesson Objectives
* How to use UserDefaults and plists 
* How to use the Codable Protocol to save to file 
* How to use Core Data for relational data management 
* How to use Realm as a modern database solution
>This is a companion project to The App Brewery's Complete App Development Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)

## Final Result
![](TodoeyDemo.gif)
