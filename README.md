# ANYWHERE FITNESS APP 📱

Anywhere Fitness is a React web application that allows fitness classes to be held anywhere - a park 🌳, an unfinished basement or a garage 🏠 - not just your traditional gym 💪🏽.

https://anywhere-fitness-club.vercel.app/

### [Link to Code on GitHub](https://github.com/Build-Week-Anytime-Fitness) 💻

# FRONT END

## App Organization & Structure

    - Home / video element
    - sign-up
      (checkbox for instructor)
    - log-in
      (checkbox for instructor, conditional render)
      password? / instructor code?
      User Object
      isInstructor: boolean;
    - log-out

    Client (protectedRoute) /classes
      - classes page

    Instructor (protectedRoute) /instructors
      - classes page for instructors (that has edit form component on top enabling full CRUD operations)

## Components

- Home.js
- Header.js
- Footer.js
- Nav.js

- Classes.js
- Class.js
- Instructors.js

- SignUpForm.js
- LogInForm.js
- Logout.js
- ClassForm.js


## SAMPLE LOGINS

> Link to backend Github https://github.com/Build-Week-Anytime-Fitness/back-end/blob/main/README.md

        Client # 1
        email: th@marvel.org
        password: password

        Instructor# 2
        email: bp@marvel.org
        password: password

## Dependencies

- React Dom
    - [ ] npm install react react-dom

- Axios
    - [ ] npm install axios
    - [ ] import axios from 'axios';

- Yup
    - [ ] npm install -S yup
    - [ ] import \* as yup from 'yup';

- React Router
    - [ ] npm install --save react-router
    - [ ] import { Router, Route, Switch } from "react-router";

- Material UI
    - [ ] npm install @material-ui/core
    - [ ] npm install @material-ui/icons

- Bootstrap
    - [ ] npm install react-bootstrap bootstrap@4.6.0
    - The following line can be included in your src/index.js or App.js file
    - [ ] import 'bootstrap/dist/css/bootstrap.min.css';

- GSAP
    - [ ] npm install gsap
    - [ ] import { gsap } from "gsap";

## Dev Dependencies

- Cypress
    - [ ] npm install cypress --save-dev
    - [ ] npx cypress open
    - [ ] add to cypress.json folder

> ADD:

        {
        "viewportWidth": 600,
        "viewportHeight": 600,
        "baseUrl": "http://localhost:5000",
        "integrationFolder": "cypress/integration"
        }

- React Testing Library
    - [ ] npm install --save-dev @testing-library/react

## Tools

[Tiny JPEG](https://tinyjpg.com/)

- to compress images to optimize performance

## Data Structures

> User Data Structure:

{ "id": "1", "personName": "Pete", "email": "petel@email.com", "isOverEighteen": true, "password": abc123, "isInstructor": false }

> Class Data Structure:

{ "id": "1", "className": "oldie but goodie", "classType": "jazzersize", "classDate": "Monday", "startTime": 9:00am, "duration": 1, "intensity": "high", "location": "anywhere", "numberOfStudents": 10, "maxClassSize": 10 }

## Responsiveness Media Queries

<!-- mobile -->

@media only screen and (min-width: 480px) {
}

<!-- tablet -->

@media only screen and (min-width: 768px) {
}

<!-- desktop -->

@media only screen and (min-width: 992px) {
}

<!-- wide-screen -->

@media only screen and (min-width: 1280px) {
}
