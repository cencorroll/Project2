# project2 - SpaceX Website

This was a web app built using a space x RESTful API. It showed different launches and also an index of crews that could be linked back to the launches. It was created using React and a CSS library called React Bootstrap. It also included the use of axios and was hosted using netlify.

This project was paircoded.

# Technologies Used

  CSS
    - React Bootstrap
    - SASS
  
  React.JS
    - Routing (BrowserRouter)
    - useState and useEffect
    - .map functions
    - 

  Axios
    - GET Requests

# The Approach Taken

  Day 1

  We decided on the Space X website as we were looking for an API that would not limit us when coding. We wanted unlimited requests for any interval of time and one where there was at least more than two routes. This API had its documentation on github and seemed just right and as a result was chosen.

  We started off testing the routes and looking through the data that we recieved back using an API Client called Insomnia. This was used to see the routes we needed to access specific things such as youtube embed links and pictures. 

  We then started with trying to return all the launches and display them on the page in a grid using React Bootstrap. Once we achieved that we moved onto adding a route to show a specific launch. This would show data such as images, youtube links, launch date and time and if it was successful or not.

  We then took a look at the API and found a route for the crews where we could do the exact same thing as the launches. The objects within the crew data also provided us with a way to link back to the specific launches the crews were part of. We created a crew index page and a way to show individidual crew members. Within the individual crew member page we added a button to link to the launch they were a part of.

  Day 2

  We moved onto styling and used SASS to target specific things such as the navbar and the padding within the cards in both indexes. We finished our project and spent the last couple of hours in preparing for our presentation.


# Review
  Key Leanings

  - Using axios requests
  - Being able to use SASS with React Bootstrap
  - Ternary operator for loading of page

  Future Improvements
  
  - Map through images for gallery show
  - Add search bar or dropdown filter
  - Styling

