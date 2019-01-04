# FriendFinder

To use our web service, simply go to our homepage and take our state-of-the-art survey. Immediately after submitting the survey, your perfect best friend will pop up. We also have an API you can access to the network's users and their personalized information. For research purposes.

## Explain
- Our server.js file sets up the Express server, specifying our port number, the npm packages that need to be loaded, and also the routes, which we have externalized

- There are 2 separate HTML files (home.html and survey.html) that serve as the front-end portion of our code; they determine what the user sees (the homepage and the survey, which will also show the resulting best match)

- Our 2 routing files (htmlRoutes.js and apiRoutes.js) determine the back-end logic (based on the request being made, the response that gets sent to the browser); the HTML routes display the survey and the homepage based on the URL that is accessed, and the API routes send back existing content in our server-side data or add new friends

- Best match is calculated by finding the friend with the minimal difference in scores and then sending that friend to the browser as a JSON object

- A modal is then toggled, displaying the the best match to the person who just took the survey

- In essense, this will also be a form of notes that you may later reference weeks later


