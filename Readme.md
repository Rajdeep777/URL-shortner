# Node.js URL Shortener

This is a simple URL shortener application built using Node.js, Express.js, and MongoDB. It allows you to create short URLs for long links, making it easier to share and manage links.

## Features

- Shorten long URLs to a custom short link.
- Retrieve the original URL by visiting the short link.
- View statistics for each short link, including the number of clicks.

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js
- MongoDB

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Rajdeep777/URL-shortener.git
   ```

2. Change into the project directory:

   ```bash
   cd url-shortener
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Configure your MongoDB connection in the `config.js` file.

5. Start the application:

   ```bash
   npm start
   ```

   The application will be running at `http://localhost:3000`.