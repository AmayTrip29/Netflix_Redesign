# Netflix Redesign Project

Welcome to the Netflix Redesign project! This project aims to redesign the Netflix homepage using HTML, CSS, and JavaScript. It includes both frontend and backend components for a complete user experience.

## Overview

The `netflix_redesign.js` file contains the combined JavaScript code for both frontend and backend functionalities. It includes:

- Frontend code for the Netflix-like homepage, including HTML structure, CSS styling, and JavaScript functionality.
- Backend code for user authentication, including user signup, login, and token generation.
- Integration with MongoDB for storing user data.

## Features

- **Frontend**:
  - Responsive design resembling Netflix's UI.
  - Dynamic content rendering for movie listings.
  - Integration with FMovies for streaming redirection.

- **Backend**:
  - User authentication using JWT (JSON Web Tokens).
  - Secure password hashing with bcrypt.
  - MongoDB integration for storing user data.

## Installation and Usage

1. Clone the repository to your local machine:

   Clone the repository using the following command:
   git clone <repository_url>

2. Navigate to the project directory:

   Change your current directory to the project directory using the command:
   cd netflix-redesign

3. Install dependencies: (bash)
   
   Run the following command to install project dependencies:
   npm install

4. Set up environment variables:
   
   Create a `.env` file in the root directory of the project and define the following environment variables:
   PORT=3000
   MONGODB_URI=mongodb://localhost/netflix-like
   JWT_SECRET=your_jwt_secret_key

5. Run the server:
   
   To start the server, execute the following command:
   node netflix_redesign.js

6. Open a web browser and navigate to http://localhost:3000 to access the Netflix-like homepage.

Contributing:

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

License:

This project is licensed under the MIT License.
