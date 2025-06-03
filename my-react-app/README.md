# My React App

This project is a simple React application built with TypeScript. It serves as a template for creating React applications using Docker for containerization.

## Project Structure

```
my-react-app
├── src
│   ├── App.tsx          # Main component of the application
│   ├── index.tsx        # Entry point of the application
│   └── types
│       └── index.ts     # Type definitions used in the application
├── public
│   └── index.html       # HTML template for the application
├── package.json         # npm configuration file
├── tsconfig.json        # TypeScript configuration file
├── Dockerfile           # Docker image build configuration
├── .dockerignore        # Files and directories to ignore during Docker build
└── README.md            # Project documentation
```

## Getting Started

To get started with this project, follow the steps below:

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd my-react-app
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Run the application:**
   ```
   npm start
   ```

## Docker Setup

To run the application using Docker, follow these steps:

1. **Build the Docker image:**
   ```
   docker build -t my-react-app .
   ```

2. **Run the Docker container:**
   ```
   docker run -p 3000:3000 my-react-app
   ```

3. **Access the application:**
   Open your browser and navigate to `http://localhost:3000`.

## License

This project is licensed under the MIT License.