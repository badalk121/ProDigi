# ProDigi

ProDigi is a project designed to [briefly describe the purpose of your project]. This repository contains both the client and server sides of the application, structured to be easily set up and run locally.

## Prerequisites

Ensure you have the following installed:
- Node.js (version 16.20) or else nvm to set it to mentioned version.
- All the keys mentioned in the env.example file are important for this project to run.

## Installation

Follow these steps to set up and run the project on your local machine:

### 1. Clone the Repository

```shell
git clone https://github.com/badalk121/ProDigi.git
```

### 2. Install Dependencies

Navigate to the client and server directories and install the required dependencies:

```shell
# Install server dependencies
cd ProDigi
npm install
```

### 3. Environment Variables

Create a `.env` file in the `server` directory and add the required environment variables. I have provided a .env.example file for reference.

### 4. Run the Application

To run the application, you need to run the following command in the project directory:

```shell
# Start the server
npm run dev
```

### 5. Access the Application

Once both the client and server are running, you can access the application at `http://localhost:8080`.

## Docker Support

If you prefer to use Docker, a `dockercompose.yml` file is provided. To start the application using Docker, run:

```shell
docker-compose up
```

## License

This project is licensed under the MIT License.

## Contributing

Feel free to contrubute and send pull requests.
