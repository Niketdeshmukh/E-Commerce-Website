# E-Commerce Application
# Frontend
## An e-commerce app built on MERN stack (MongoDB, Express, React and Node) with Stripe Checkout to handle payments.
__Features present in the app :-__
1. Authentication using JSON Web Tokens (JWT).
2. Option to add, edit, view and delete all the items in our store.
3. Option to add items or remove items from the cart for the user.
4. Display the total bill of the cart and update it as soon as the cart is updated by the user.
5. Using Local Storage to store the JWT so that we only allow logged-in users to buy items.
6. Option to pay using Stripe Checkout and thus creating a new order and emptying the cart after payment is successful.
7. Option to view all your past orders along with the bill amount for each.
---


# Backend

1.  **Configure default configs**. In `config/default.json`, set your variables.

	1. `dbUrl`: It can be set as `mongodb://localhost/MernECommerce`.
NOTE: This is very basic, one without any username and password. This can be configured as per your requirement.
  2. `jwtsecret`: This is the key used sign jwt tokens. It can be set as `dummySecret`.
  3. `StripeAPIKey`: Create your account here [register](https://dashboard.stripe.com/register).
2. Install dependencies with `npm i`.
3. Server will start running on [port 4000](http://localhost:4000).

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

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
..
../
./
