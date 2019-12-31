## Service for creating tiny links [Go to mager-link.ru](http://mager-link.ru)
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

### ScreenShots

1. Open main page and create new profile (skip if you already have profile) 
![](https://github.com/magerrrr/MERN/raw/img/img/create-user.png) 

2. Input your Email and Password, click "Войти"
![](https://github.com/magerrrr/MERN/raw/img/img/login.png)  

3. When you successfully log-in you will be immediately on the page for creating a short link (but you can 
click "Создать" on navigation bar)
![](https://github.com/magerrrr/MERN/raw/img/img/create-link.png)  

4. Press ENTER on keyboard for creating tiny link

5. If you click "Ссылки" on navigation bar you will see all yours links
![](https://github.com/magerrrr/MERN/raw/img/img/links.png)

6. Click to "Открыть" for getting private click stats (like counts of opens, create date of link)
![](https://github.com/magerrrr/MERN/raw/img/img/link-details.png)

