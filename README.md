# Ravenous
Click on the link to view the outcome.
<https://faysoserious.github.io/react-class-components-project/>

Used CORS anywhere to enables cross-origin requests to anywhere. So before searching, need to open [this page](https://cors-anywhere.herokuapp.com/), to allow this service.

## Introduction

This is a Yelp-like website. 

### Understand user needs

- As a user, I should be able to search for restaurants
- As a user, I should be able to view a list of restaurants returned by the Yelp API
- As a user, I should be able to sort through restaurants using a filter

### Implementation Process

Developed through the following process:

1. Creating Static Components
   1. Business
   2. BusinessList
   3. SearchBar
2. Passing information to Components
   1. Moved business information to the container component (App)
   2. Passed information from parent components (App) to child components (BusinessList, Business)
3. Setting the State of Ravenous Components
   1. Setting state and handling state changes of SearchBar component.
      - Add a SearchBar Constructor
      - Get a Sort Option's Class
      - Handle a Change in Sort Option
      - Set the Class Name of a Sort Option
4. Connect with the Yelp API, fetch the search result.
5. Hide the API key before push to github. Refer to [this page](https://stackoverflow.com/questions/48699820/how-do-i-hide-api-key-in-create-react-app). According to the question on stackoverflow, it is not the best solution to hide API key using method like this. **Nothing is secure on the client-side.**

## Current issues

1. When Resturant name is too long, then it will enlarge the description element, so the line was broken. 
2. The location has to be precise city names, otherwise will not show result. 



## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
