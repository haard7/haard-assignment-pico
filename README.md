
# Authentication App (Assignment)


### Research Internship - Web Development PICO recognition website Assignment

This is authentication app consisting of signup and login functionality.
I have used **NodeJS** language for this assignment. 



## How to run the code

type below command in your ommand line to run this project locally.  

**You Need to put your own mongo-atlas access key before running the project. 
refer [this](https://www.youtube.com/watch?v=tpz-6Trd1UI) link to learn about that key and how to use</br>**

As I am not using local database but I  use MongoDB cloud to store the data. 

```bash
  git clone https://github.com/haard7/haard-assignment-pico.git

  npm install
 
  nodemon app.js
```


## Hosted project  link  👇 
 
### [https://pico-auth-assignment.herokuapp.com/](https://pico-auth-assignment.herokuapp.com/)

## Here is video link of running this code on browser 👇

#### [https://youtu.be/iymfC3quwwg](https://youtu.be/iymfC3quwwg)

## Folder structure
```bash
.
│   .gitignore
│   app.js
│   config.env
│   package-lock.json
│   package.json
│   Procfile
│
├───controllers
│       authController.js
│
├───middleware
│       authMiddleware.js
│
├───models
│       User.js
│
├───public
│       logo.png
│       styles.css
│
├───routes
│       authRoutes.js
│
└───views
    │   home.ejs
    │   login.ejs
    │   pico.ejs
    │   signup.ejs
    │
    └───partials
            background.ejs
            footer.ejs
            header.ejs
```

