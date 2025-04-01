# Frontend React Project

This project is a simple frontend application built using React and set up with Vite. It demonstrates essential React functionalities and routing using `react-router-dom`.

## Project Initialization

The project was initialized using Vite with the following settings:

- **Framework**: React
- **Variant**: JavaScript

## Installation and Setup

Follow the steps below to run the project locally:

### Clone the Repository

Clone or download the repository to your local machine and navigate to the project directory.

git clone https://github.com/VaishnaviGayke/Movie-App.git

### Install NodeJS
Make sure NodeJS is installed on your machine. You can download it from NodeJS Official Website (https://nodejs.org/en/download/package-manager/).

### Install Dependencies
Install the project dependencies using npm:
npm install

This command will install all necessary packages listed in the package.json file.

### Additional Dependencies
The project uses React Router for client-side routing. Install it separately if needed:
npm install react-router-dom

### Running the Project
To run the project locally, execute the following command:
npm run dev

Your application will be available at:
http://localhost:5173

## API Key
This project uses data from The Movie Database (TMDB). Register and obtain your API key from their official website:

- **Get your API key:** https://www.themoviedb.org/

## Project Structure
The main structure of your React application is as follows:

frontend/
├── node_modules/
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   ├── components/
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── package.json
├── package-lock.json
└── vite.config.js

- **src/:** Contains all source code.

- **components/:** Contains reusable components.

- **assets/:** Stores static files like images or icons.

- **App.jsx:** Main React component.

- **main.jsx:** Entry point to render the React application.

## Dependencies
Major dependencies include:

- React

- React DOM

- React Router DOM

- Vite

## Scripts
The following scripts are available in your project:

- **npm run dev:** Starts the development server.

- **npm run build:** Builds the project for production.

- **npm run preview:** Previews the built version of your app.
