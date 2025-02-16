
# DoggoHub

## Description

DoggoHub is a full-stack web application designed to facilitate global interactions among dog enthusiasts. By leveraging modern web technologies, the platform offers a responsive and user-friendly interface, enabling users to connect, share experiences, and build a community centered around their canine companions.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up the DoggoHub project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NidhiRai1/Dogebook.git
   cd Dogebook
   ```

2. **Install server dependencies:**
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies:**
   ```bash
   cd ../client
   npm install
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the `server` directory with the following content:
     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
   - Replace `your_mongodb_connection_string` and `your_jwt_secret` with your actual MongoDB URI and a secret key for JWT authentication.

5. **Start the development server:**
   - In the `server` directory, run:
     ```bash
     npm start
     ```
   - In the `client` directory, run:
     ```bash
     npm start
     ```

   The server will run on `http://localhost:5000` and the client on `http://localhost:3000`.

## Usage

Once the application is running, users can register and log in to access the platform's features. The intuitive interface allows users to create profiles, post content, and interact with other members of the DoggoHub community.

## Features

- **User Authentication:** Secure registration and login using JSON Web Tokens (JWT).
- **Profile Management:** Users can create and customize their profiles.
- **Post Creation:** Share text and images with the community.
- **Interactive Feed:** View and engage with posts from other users.
- **Responsive Design:** Optimized for various devices, ensuring a seamless user experience.

## Technologies Used

- **Frontend:**
  - React.js: For building the user interface.
  - Formik and Yup: Handling form validation and management.

- **Backend:**
  - Node.js and Express.js: Setting up the server and API endpoints.
  - MongoDB with Mongoose: Database management and modeling.
  - Multer: Handling file uploads.
  - JSON Web Token (JWT): Implementing secure authentication.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

