# My Fullstack App

This project is a fullstack application that consists of a React frontend and an Express backend connected to a MongoDB database.

## Project Structure

```
my-fullstack-app
├── client          # Frontend application
│   ├── src        # Source files for React app
│   ├── public     # Public assets
│   ├── package.json # Client dependencies and scripts
│   └── .env       # Environment variables for client
├── server          # Backend application
│   ├── src        # Source files for Express app
│   ├── package.json # Server dependencies and scripts
│   └── .env       # Environment variables for server
└── README.md      # Project documentation
```

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/my-fullstack-app.git
   cd my-fullstack-app
   ```

2. Set up the client:
   ```
   cd client
   npm install
   ```

3. Set up the server:
   ```
   cd server
   npm install
   ```

### Environment Variables

Create a `.env` file in both the `client` and `server` directories with the necessary environment variables.

#### Client `.env` example:
```
REACT_APP_API_URL=http://localhost:5000/api
```

#### Server `.env` example:
```
MONGODB_URI=mongodb://localhost:27017/mydatabase
PORT=5000
```

### Running the Application

1. Start the server:
   ```
   cd server
   npm start
   ```

2. Start the client:
   ```
   cd client
   npm start
   ```

### Usage

Visit `http://localhost:3000` in your browser to view the application.

### Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.

### License

This project is licensed under the MIT License.