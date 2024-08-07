# CHAT APP - USING MERN TECHNOLOGIES

Welcome to the CHAT APP repository! It is a full-stack web application built using the MERN stack. It serves as a platform for real time chatting, providing users with the ability to authenticate and chat conviniently.

# Installation

1. Clone the repository to your local machine:
   ### `git clone https://github.com/neerajkumar4/chatAppMERN.git`
2. Navigate to the project directory:
   ### `cd .\chatAppMERN\`
3. Navigate to the api directory:
   ### `cd .\backend\`
4. Install server-side dependencies:
   ### `npm i`
5. Navigate back to the project root directory:
   ### `cd ..`
6. Navigate to the client directory:
   ### `cd .\frontend\`
7. Install client-side dependencies:
   ### `npm i`

# Configuration

Before running the application, you need to set up the environment variables.

1. Create a .env file in the backend directory and specify the following variables:
   ```
    PORT=your server_port
    MONGO_URI=your_mongodb_url
    JWT_SECRET_KEY=your_secret_key
   ```
   Replace `your_mongodb_url` with your MongoDB connection string, `your_secret_key` with a secret key for JWT token generation and `server_port` with port numnber(8000).

# Usage

To start the application, you have to start front-end and back-end in separate terminal simultaneously:

1. open a terminal and navigate to backend directory then run the following command:
   ### `npm start`
2. open another terminal and navigate to frontend directory then run the following command:
   ### `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
