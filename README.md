# Rancid Tomatillos

## Table of Contents
- [About the Project](#about-the-project)
- [Technologies Used](#technologies-used)
- [Contributors](#contributors)
- [Learning Goals](#learning-goals)
- [Project Evolution](#project-evolution)
- [Project Reflections](#project-reflections)
- [Extensions](#extensions)
- [Future Goals](#future-goals)
- [Organizational Resources](#organizational-resources)
- [Set Up](#set-up)
- [Application in Action](#application-in-action)
- [Testing](#testing)

## About the Project
Rancid Tomatillos is a React-based web application that offers users the ability to browse movies, view detailed information, and search by title or genre. It features an autoplay trailer for an immersive experience when a user selects a movie to explore further.

For project specifications, visit the [project spec](https://frontend.turing.edu/projects/module-3/rancid-tomatillos-v3.html).

## Application in Action

**View Movie Details**
![View Movie Details](./assets/movie-details.gif)

**Search by Genre**
![Search by Genre](./assets/genre-search.gif)

## Technologies Used

### Languages
- JavaScript

### Frontend
- React
  - react-dom
  - react-router-dom

### Testing
- @testing-library/react
- @testing-library/jest-dom
- @testing-library/user-event
- Cypress
- Web Vitals

### Build Tools
- react-scripts

### Others
- ESLint
- Browserslist

## Contributors
- [Eli Davidson](https://github.com/elleshadow)
- [Nathan Hodnett](https://github.com/nhodnett)

### Project Manager
- [Kayla Gordon](https://github.com/)

## Learning Goals
- React component lifecycles and state management.
- End-to-end testing with Cypress.
- Asynchronous functions and API calls.
- Dynamic and conditional rendering in React.

## Project Evolution
The concept of genre carousels was initially considered but moved to future development goals to maintain the scope for MVP. Component structures evolved throughout the project to optimize functionality.

## Project Reflections
Challenges were faced with React's rendering based on state and timing within Cypress tests, which required strategic waits and state checks.

## Extensions
"More React Functionality" was chosen, adding search and filtering capabilities to the movie selection process.

## Future Goals
- Implement genre-based carousels.
- Improve error handling for unavailable YouTube videos.
- Add favorites feature and user personalization.
- Deploy with Heroku and enhance responsive design for movie cards.

## Organizational Resources
- [Project board on GitHub](https://github.com/nhodnett/rancid-tomatillos/projects/1) for task management.
- [Figma wireframes](https://www.figma.com/file/B5YF2KSCHALrpK1mAkaCVu/Component-architecture?node-id=0%3A1) for design planning.

## Set Up
To set up the project locally:
1. Fork and clone the repository.
2. Navigate to the directory and run `npm install` to install dependencies.
3. Start the application with `npm start`.

## Testing
Cypress is used for end-to-end testing. Run `npm test` to execute the test suites.
