# Test-Version1 (Version without lazy loading)

# Description

Test app is an application where Mock up service is used. It's a fake rest API that returns all the JSON data we need for this application. The features that are implemented: 
 - Display all the data,
 - Enable data search,
 - Delete data from the list,
 - Display loading spinner for any service call.

# Missing lazy loading

"Lazy lodging" is not implemented in this version because there was bug that happened when loading new data scroll is placed at the top of the list. When scrolling, new data was loaded but it did not look nice because the scroll is back to the beginning of the list. Version 2 of Test aplication where is implemented lazy loading is located on the following link: https://github.com/Budalic91/Test-Version2
 
 # Tehnical choices

 - HTML,
 - JQuery v2.1.1,
 - CSS,
 - Bootstrap(css, js).

JQuery is a Javascript library designed to ease the client-side scripting of HTML. JQuery comprising a modular set of platform agnostic methods for handling various requirements of the dynamic web, such as running calls on AJAX, traversing and selecting DOM elements, parsing animations and transition effects, manipulating page elements etc. It standardize the task of front-end development and user interaction elements. It is fast, concise and very flexible. There are various plugins available for jQuery too, but these are some of the more broad reasons to choose jQuery.

Bootstrap - The bootstrap css and js file is used because of the collapse panel. It's a very useful thing to quickly create and display collapse panels.

# Link to my public profile

http://linkedin.com/in/milos-budalic-321a6473
