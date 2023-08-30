# Developer-s-Challenge---Full-Stack
The Developer's Challenge - Full Stack is a comprehensive test designed to assess a developer's proficiency in both front-end and back-end development. This challenge presents a series of tasks that require creating a Single Page Application (SPA) with a user interface (UI) and a corresponding back-end infrastructure.

## Front-End (UI)

The front end of the application is built using Angular and Material Design.

### Setup

1. Install Node.js: Make sure you have Node.js and npm (Node Package Manager) installed on your machine.

2. Install Angular CLI: If you don't have Angular CLI installed, you can install it globally using the following command:
   
3. Install Dependencies: Navigate to the `ui` directory and install the project dependencies:


### Running the Front-End

Run the following command in the `ui` directory to start the front-end development server:

The application will be accessible at `http://localhost:4200/`.

## Back-End (Server)

The back-end of the application is built using Node.js and Express.js.

### Setup

1. Install Dependencies: In the root directory of the project, install the back-end dependencies:

2. Set Up Environment Variables: Create a `.env` file in the root directory and set the value for the secret key used for JWT:

### Running the Back-End

Run the following command to start the back-end server:

The server will be accessible at `http://localhost:3000/`.

## Running the Full Application

1. Make sure both the front-end and back-end are running.

2. Access the application in your web browser at `http://localhost:4200/`.

## Hosting

For deployment, you can follow these steps:

- Host the UI on a cloud hosting provider such as GitHub Pages, Cloudflare Pages, or Firebase Hosting.
- Host the back-end on a serverless environment like Cloudflare Workers or AWS Lambda.

