# Pokedex with React
Taken from this blog post: [Let’s Build a Pokedex with React](https://blog.cloudboost.io/lets-build-a-pokedex-with-react-part-1-e1ba0b9387a7)

# To run this app
* Confirm your Node version > 6, otherwise you can use [nvm](https://github.com/nvm-sh/nvm) to install the latest version of node 
* Clone this repository
* Run `npm install` to install required dependencies
* Run `npm start` to start up the react app
* Visit http://localhost:3000/ to access the Pokedex

# Notes
I made changes to the DetailView.js file that is different than the tutorial where the `data-name` is used as a heading, followed by the type and ID of each pokemon. Additionally, I removed the CSS styling of the `data-char` className in DetailView.css to provide for more UI consistency.

# Next Steps
Things I would like to add or change in future iterations:
* Add a heading to the Pokedex itself
* Utilize other API calls or scraping to provide additional information about each Pokemon