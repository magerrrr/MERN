## Service for creating tiny links [Go to web-site](www.mager-link.ru)
This is an application that uses MERN Stack (MongoDB, Express.js, React, and Node.js).
![](https://github.com/IBM/pattern-utils/raw/master/mern-starter/architecture.png)

### Features

- Registration
- Authorization (jwt token)
- Shorter URLs
- Redirect
- Get private click stats (counts, create date)
- App deployed at VPS-hosting + available by mager-link.ru

### Flow

1. The user views the React web app with a browser.
2. The React front end communicates with the Express back end via RESTful APIs.
3. The back-end Express application uses the Mongo database for storing and retrieving data.
4. Back-end results are communicated back to the front end.
5. Front-end results are rendered in a human-readable format to the user.
