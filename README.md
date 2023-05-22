# BubbleCha
Bubble Tea Locator Web Application

# Overview
BubbleCha is a mobile app that lets a user search nearby shops that serve bubble tea beverages, allowing them to see the distance the shop/vendor is from them, what the contents of the beverage are, ratings of the beverage, sugar adjustment content, calorie content, and allergy information. The app opens up to a search bar and the user will be able to type in either type in location of city with state, location with zip code, or a certain type of drink beverage. The search will return results most accurate to what matches the user input.

If the user starts with a location, the app will return nearby bubble tea shops with the current distance from the location and the contact information for the shop. The user also has an option to view the drink menu if they select a particular shop. Then the user can select certain drinks and will be provided with the information concerning that drink. However if the user inputs a certain drink, then the app will list certain shops that have that drink with their respective location and contact information for the shop. From this, if the user selects a certain shop for that drink, then the app will return the ratings of the beverage, the contents, sugar adjustment contents, calorie contents, and allergy information. When the user is satisfied with their browsing, they can contact the shop to place the order, either through calling or utilizing the shops’ respective online order applications.

If you are craving bubble tea and want to make an informed decision to try something new and nearby, search it up in BubbleCha!

Imagine it is a hot summer day and you are parched! You are looking for a beverage that has a variety of fruits and toppings, with a hint of caffeine in the form of tea, but you aren’t sure where the closest bubble tea shop is nor do you know what they will have on their menu.

BubbleCha will narrow down the time it takes you to search for new and exciting beverages while helping you navigate to a nearby vendor who sells your favorite classic bubble tea drink. You might even find a new bubble tea shop down the street from you!

# Architecture
BubbleCha follows the Model-View-Controller (MVC) architecture pattern. The Model layer consists of a MySQL database, which stores various bubble tea data. The View layer is built using HTML, CSS, and REACT JavaScript, and is responsible for rendering the user interface. The Controller layer is implemented using the Spring and Java, and provides the application's business logic and RESTful API endpoints.

# Database Schema
The MySQL database consists of tables: bubble_drinks, bubble_vendors, and bubble_users. The bubble_drinks table stores information about each bubble tea drink, including the vendors that offer that drink. The bubble_users table stores information about each user account, including the users's ID, username, encrypted password, and email address. A many-to-many relationship is maintained between the bubble_vendors and bubble_drinks tables using a junction table named bubble_vendors_drinks.

# Look No Further!
If you are craving bubble tea and want to make an informed decision to try something new and nearby, search it up in BubbleCha!

Imagine it is a hot summer day and you are parched! You are looking for a beverage that has a variety of fruits and toppings, with a hint of caffeine in the form of tea, but you aren’t sure where the closest bubble tea shop is nor do you know what they will have on their menu.

BubbleCha will narrow down the time it takes you to search for new and exciting beverages while helping you navigate to a nearby vendor who sells your favorite classic bubble tea drink. You might even find a new bubble tea shop down the street from you!
