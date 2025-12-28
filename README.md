# Backend App

A basic Node.js backend application built with Express.js, created as a learning project. This application serves as an introduction to backend development with Node.js and demonstrates fundamental concepts such as routing, environment variables, and API endpoints.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Features

- Basic Express.js server setup
- Multiple API routes with different responses
- JSON response handling
- Environment variable configuration
- Clean and simple code structure

## Prerequisites

- Node.js (v14 or higher)
- npm (usually comes with Node.js)
- Git (for cloning the repository)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Backend-app
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your environment variables:
   ```
   PORT=4000
   ```

## Usage

1. Start the application:
   ```bash
   npm start
   ```

2. Open your browser or use an API client to access the endpoints.

## API Endpoints

The application provides the following endpoints:

- `GET /`
  - Returns a simple "Hello World!" message.
  - Example response: `Hello World!`

- `GET /login`
  - Returns an HTML message prompting the user to login.
  - Example response: `<h1>Please login at chai aur code</h1>`

- `GET /youtube`
  - Returns an HTML message related to "Chai aur code".
  - Example response: `<h1>Chai aur code</h1>`

- `GET /github`
  - Returns a JSON response with GitHub-related data.
  - Example response:
    ```json
    {
      "message": "Not Found",
      "documentation_url": "https://docs.github.com/rest",
      "status": "404"
    }
    ```

## Project Structure

```
Backend-app/
├── index.js          # Main application file containing server setup and routes
├── package.json      # Project metadata and dependencies
└── README.md         # This file
```

## Technologies Used

- [Node.js](https://nodejs.org/) - JavaScript runtime
- [Express.js](https://expressjs.com/) - Web application framework
- [dotenv](https://www.npmjs.com/package/dotenv) - Environment variable management

## Contributing

This is a learning project, but if you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License.

## Author

Atharva

## Acknowledgments

- This project was created as part of a learning journey with "Chai aur Code".
- Thanks to the Express.js team for providing an excellent framework.
