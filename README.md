
# Kujali Finance Apllication

Introducing our financial budgeting application, the ultimate tool for managing your money and reaching your financial goals.

Our user-friendly interface makes it easy to track your income and expenses, set budgets, and monitor your spending in real-time. Automatic categorization of transactions ensures that your data is always accurate and up-to-date. The app also allows you to create customized budgeting categories and set savings goals, so you can stay on track and achieve your financial objectives.

With our budgeting application, you'll be able to:

```Track your income and expenses in real-time
1. Set budgets and monitor your spending
2. Create customized budgeting categories
3. Set savings goals and track your progress
4. Get alerts for overspending or when you're close to reaching your budget.
```
Our app also provides detailed reports and charts that give you a clear picture of your financial situation, including your net worth, cash flow, and spending by category. Plus, data can be export in CSV format for record keeping.

Whether you're looking to pay off debt, save for a down payment on a house, or just need to budget more effectively, our budgeting application is here to help you take control of your finances. Try it out today and see the difference it can make in your financial life!


## Tech Stack

Our application is built using Angular, a popular JavaScript framework for building web and mobile applications, and TypeScript, a superset of JavaScript that adds optional static typing and other features.

Here is a brief overview of how the application is structured:

```
1. Components: The building blocks of the application, responsible for displaying the UI and handling user interactions. Each component has its own template, styles, and logic, and can be nested inside other components.

2. Services: Classes that handle the business logic of the application, such as accessing an API or manipulating data. Services can be injected into components to share functionality across the application.

3. Routes: Define the different URLs of the application and which component should be displayed for each route.

4. Modules: Group related components, services, and routes together. Each module has its own set of imports, declarations, and exports, which define what should be available to other modules in the application.

5. TypeScript: The application uses TypeScript, a superset of JavaScript that adds optional static typing, classes, interfaces and other features. That makes the development more robust and reliable.

6. Interfaces: are used to define the types of the variables and objects in the application.

7. Decorators: are used to add metadata to classes, methods, and properties, which can be used by Angular to configure the application.

8. Observables: We use the RxJS library to handle asynchronous data streams, such as HTTP requests and user input. Components can subscribe to observables to receive updates and trigger changes in the UI.

```
Overall, The application is built with a modular structure, that makes it easy to understand, maintain, and scale. The use of TypeScript and Angular makes it robust and reliable. The application implements best practices for web development, such as separating concerns and using dependency injection, to make the code more maintainable.


## Getting Started

Follow the steps below to setup your project and get running

### Create a Firebase Project

Setting up a Firebase project is a simple process that can be completed in a few steps. Here is a step-by-step guide on how to do it:

```
1. Go to the [Firebase website](https://firebase.google.com) and sign in to your Google account.

2. Click on the "Go to console" button on the top right corner of the page.

3. Click on the "Create a project" button to create a new project.

4. Fill in the necessary information for the project, such as the name and ID.

5. Select the billing account and enable Google Analytics if you want to use it (Optional).

6. Click on the "Create project" button to create the project.
```

Once the project is created, you will be taken to the dashboard. From here you can add different features to your project, such as 
```
Authentication, Cloud Firestore, Realtime Database, and more.
```

To add a new feature, click on the hamburger icon on the top left corner of the page and select the feature you want to add.

Follow the instructions on the screen to set up the feature.


You can also access the project settings, by clicking on the settings icon on the top left corner of the project dashboard, you will access the settings to add collaborators, and configure the project.

That's it! You now have a Firebase project set up and ready to use. Keep in mind that you may need to configure some settings and add some dependencies to your application to make use of the Firebase features as you'll see in the (Installtion step).
### Add a Web Application to your project

Adding a web application to a Firebase project is a simple process that can be completed in a few steps. Here is a step-by-step guide on how to do it:

```
1. Go to the [Firebase Console](https://console.firebase.google.com) and select the project that you want to add the web application to.

2. Click on the "Develop" tab in the navigation menu on the left side of the page.

3. Select "Web App" from the options.

4. Click on the "Config" button to get your web app's Firebase configuration object. This object contains the necessary information to connect your web app to your Firebase project.

5. In your web application, create a new file (or add to an existing one) to hold the Firebase configuration object, usually a config.ts or config.js file.

6. Copy and paste the Firebase configuration object into this file and make sure it's available to the rest of your application.

```
Now you need to install the Firebase SDK, you can do it by running the command npm install firebase or yarn add firebase.

Import the Firebase library in your application by adding the following line to your code import * as firebase from 'firebase/app';

Initialize the Firebase app by adding the following code snippet in your main file usually index.ts or index.js
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file


`apiKey`: `YOUR_FIREBASE_API-KEY`

`authDomain`: `YOUR_AUTH_DOMAIN`

`projectId`: `YOUR_PROJECT_ID`

`storageBucket`: `YOUR_STORAGE_BUCKET`

`messagingSenderId`: `YOUR_MESSAGING_ID`

`appId`: `YOUR_APP_ID`


## Install and Run Locally

Clone the project

```bash
  git clone git@github.com:italanta/kujali.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the App & Emulators

```bash
  npm run start
```


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

