# Rwriter
Based on tutorial at http://blog.joanboixados.com/building-a-boilerplate-for-a-koa-redux-react-application-including-webpack-mocha-and-sass/

# RWriter concepts
In RWriter you can create projects.
## Project
A project contains the following data:
* A name
* An author (a plain string for now)
* A type (short story, novella or novel, might add more)
* A list of chapters
* A list of characters
* A list of locations
* Comments

## Chapter
A chapter has the following data :
* A title (optional)
* A number (created automatically)
* A list of scenes
* Comments

## Scene
* A title (optional)
* An order (created automatically)
* A contents (long string)
* A list of characters (refs to the project's characters)
* A list of locations (refs to the project's locations)
* Comments 

## Character
* A short name
* A full name
* A description
* A bio
* A weakness
* A need
* A desire (goal)

## Location
* A name
* A description
