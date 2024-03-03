# Secure File Sharing App

This is a secure file sharing web application built using Node.js, Express, MongoDB, and EJS. It allows users to upload files with optional password protection and provides a password prompt for downloading protected files.

## Features

- Secure file upload with optional password protection.
- Password prompt for downloading protected files.
- Tracks the number of downloads for each file.

## Installation

1. Clone this repository to your local machine.
2. Install dependencies using npm:

    ```
    npm install
    ```

3. Set up environment variables:
   
   - Create a `.env` file in the root directory.
   - Add your MongoDB connection string as `MONGODB_URI`.
   - Optionally, set a custom port using `PORT`.

4. Start the application:

    ```
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

- Visit the homepage to upload files.
- Optionally set a password for the file.
- Share the generated link with others to download the file.
- For protected files, users need to enter the correct password to download.

## Dependencies

- Express.js: Web framework for Node.js.
- EJS: Embedded JavaScript templates for rendering HTML.
- Mongoose: MongoDB object modeling tool.
- Multer: Middleware for handling file uploads.
- Bcrypt: Library for hashing passwords.
