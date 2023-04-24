# Telegram Bot 

This is a simple Telegram bot built with Node.js, Express.js, Multer, and MongoDB. It allows users to input data through a static webpage, which is then stored in a MongoDB database.

## Getting Started
To get started with this project, you'll need to do the following:

1. Clone the repository to your local machine.
2. Install the required dependencies by running the command npm install.
3. Set up a Telegram bot using Telegram BotFather and obtain an API token.
4. Set up a MongoDB database and obtain a connection URI.
5. Edit the config.js file and add the information for the Xerox shop, including their email address, phone number, and any other relevant details.
6. Start the server by running the command npm start.
7. Navigate to http://localhost:8000 in your browser to access the static webpage.

## Features
The Telegram bot has the following features:

`/start` command: Displays a welcome message and brief overview of the store.
`/help` command: Displays a list of available commands.
`/upload` command: Opens the static webpage where users can upload documents, such as PDFs or images, to purchase products.
`/details` command: Displays details about a specific product, such as its price, description, and available variants.
`/payments` command: Provides information about payment methods accepted by the store.
`/contact` command: Displays contact information for the store, such as email, phone number, or social media handles.

## Technologies Used
This project was built with the following technologies:

Node.js
Express.js
Multer
MongoDB
Telegram Bot API

