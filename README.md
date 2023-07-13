# Human natural laguage to SQL converter using OpenAI

This is a full stack app that converts natural language English to SQL queries using OpenAI's GPT-3.5/davinci architecture. The app has a client and a server, each with its own npm packages.

This is an exploratory project to explore Open AI apis. I have followed the following tutorial to learn how to setup these APIs: https://youtu.be/kjUSOa_KOts

## Getting Started

To get started, clone the repository to your local machine and navigate to the root directory. There are two folders in the root directory: client and server. Each folder has its own package.json file and node_modules folder.

### Installing Dependencies

To install the dependencies for the client, navigate to the client folder and run the following command:

```bash
npm install
```

To install the dependencies for the server, navigate to the server folder and run the following command:

```
npm install
```

## Running the Client

To run the client, navigate to the client folder and run the following command:

```
npm run dev
```

## Running the Server

To run the server, navigate to the server folder then set up your OpenAI API Key in a .env file and run the following command:

```
npm start
```

## Technologies

The front end is built with React, and the back end is built with Node.js and Express.