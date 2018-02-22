# sequelizeBurger

A Burger devouring application With Node.js/Express/MySQL/Handlebars/Materialize

## Description

This application demonstrates a simple full stack application with a front end implemented with HTML/CSS and elements from the Materialize framework and the backend implemented with Node.js and Express. HTML templating is done with the help of Handlebars.

The user may enter any burger name to add it to the menu. This also adds the new burger entry into the MySQL database. The initial burger entry is added as *available* on the menu and placed on the left side of the screen. The user may then eat any burger by clicking on it, which moves it into the adjacent column and updates its status accordingly in the database.

## Demo

The demo of the burger eating application can be found [here](https://burger-part-deux.herokuapp.com/).

## Installation

To run the application locally, first clone this repository with the following command.

	git clone git@github.com:xanimo/sequelizeBurger.git
	
Next, install the application dependencies.

	cd sequelizeBurger
	npm install
	
Finally, run the node server locally.

	node server
	
Now, open the local application on port 8080 at the URL: `http://localhost:8080/`.
