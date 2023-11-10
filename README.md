# URL Shortener

A simple URL shortening web application built with Node.js, Express, and MongoDB.

## Features

- Shorten long URLs to concise and shareable short links.
- Copy short URLs to the clipboard with a click.
- Toggle visibility of the footer for a cleaner user interface.

## Getting Started

### Prerequisites

- Node.js installed
- MongoDB installed and running

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ApiError/Url-Shortener.git
   ```

2. Navigate to the project directory:

   ```bash
   cd url-shortener
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Open file named `config.json` in the project root:

   ```json
   {
     "website_url": "http://localhost:3000" // Replace with your website URL
   }
   ```

### Usage

1. Start the application:

   ```bash
   npm start
   ```

2. Open your browser and visit [http://localhost:3000](http://localhost:3000).

3. Enter a long URL in the input box and click "Shorten URL."

4. Copy the generated short URL and share it!

### Configuration

You can customize the website URL by modifying the `config.json` file.

## Contributors

- [ApiError](https://github.com/ApiError/Url-Shortener)
