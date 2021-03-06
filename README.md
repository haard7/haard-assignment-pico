
# Authentication App (Assignment)


### Research Internship - Web Development PICO recognition website Assignment

This is authentication app consisting of signup and login functionality.
I have used **NodeJS** language for this assignment. 



## How to run the code

type below command in your ommand line to run this project locally.  

**You Need to put your own mongo-atlas access key in config.env file before running the project. 
refer [this](https://www.youtube.com/watch?v=tpz-6Trd1UI) link to learn about that key and how to use</br>**

As I am not using local database but I  use MongoDB cloud to store the data. 

```bash
  git clone https://github.com/haard7/haard-assignment-pico.git

  npm install
 
  nodemon app.js
```


## Hosted project  link  π 
 
### [https://login-app-pico.herokuapp.com/](https://login-app-pico.herokuapp.com/)

## Here is video link of running this code on browser π

#### [https://youtu.be/iymfC3quwwg](https://youtu.be/iymfC3quwwg)


## Tech Stack used

- HTML, CSS, JS (For Frontend)
- NodeJS (For server side programming)
- MongoDB cloud (as Database)
- Packages (Express, mongoose, ejs, cookie-parser, jasonwebtoken (JWT), Validator)



## Folder structure
```bash
.
β   .gitignore
β   app.js
β   config.env
β   package-lock.json
β   package.json
β   Procfile
β
ββββcontrollers
β       authController.js
β
ββββmiddleware
β       authMiddleware.js
β
ββββmodels
β       User.js
β
ββββpublic
β       logo.png
β       styles.css
β
ββββroutes
β       authRoutes.js
β
ββββviews
    β   home.ejs
    β   login.ejs
    β   pico.ejs
    β   signup.ejs
    β
    ββββpartials
            background.ejs
            footer.ejs
            header.ejs
```


## π Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haard-patel-73b001196)



