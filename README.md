# React Firebase Authentication Project

This project is a basic React application that demonstrates how to implement user authentication using Firebase. It provides a boilerplate code for setting up user registration, login, and logout functionalities with Firebase's Authentication service.

## Getting Started

To get started with this project, follow the instructions below:

### Prerequisites

- Node.js (version 12 or higher)
- NPM (Node Package Manager) or Yarn

### Installation

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/UsamaSabir007/React-Auth.git
   ```

2. Navigate to the project directory:

   ```
   cd react-firebase-authentication
   ```

3. Install the dependencies by running one of the following commands, depending on the package manager you prefer:

   - Using NPM:

     ```
     npm install
     ```

   - Using Yarn:

     ```
     yarn install
     ```

### Configuration

To use Firebase authentication in your project, you need to set up a Firebase project and obtain the necessary configuration details. Follow the steps below to configure Firebase:

1. Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project (or use an existing one).

2. In the project overview page, click on the "Add app" button and select the "Web" option.

3. Register the app by providing a name for your application and click on "Register app".

4. Firebase will generate the configuration details (API keys, Firebase SDK scripts, etc.) for your app. Copy these details.

5. Rename the `.env.example` file in the project's root directory to `.env`.

6. Open the `.env` file and replace the placeholder values with your Firebase configuration details.

   ```
   REACT_APP_FIREBASE_API_KEY=YOUR_API_KEY
   REACT_APP_FIREBASE_AUTH_DOMAIN=YOUR_AUTH_DOMAIN
   REACT_APP_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
   REACT_APP_FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
   REACT_APP_FIREBASE_APP_ID=YOUR_APP_ID
   ```

### Usage

To start the development server and run the application, use one of the following commands:

- Using NPM:

  ```
  npm start
  ```

- Using Yarn:

  ```
  yarn start
  ```

The application should now be running on [http://localhost:3000](http://localhost:3000).
