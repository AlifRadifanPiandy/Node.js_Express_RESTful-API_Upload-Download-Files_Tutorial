# Node.js Express File Upload/Download API

This is a simple Node.js Express server that provides RESTful API endpoints for uploading, downloading, and deleting files.

## Features

- File upload: Single file upload using Multer.
- File download: Download an uploaded file.
- File deletion: Delete an uploaded file.
- File listing: Get a list of all uploaded files.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- npm

### Installing

1. Clone the repository:

   ```sh
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```sh
   cd node-js-express-restful-api-upload-download-files-tutorial
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

### Running the Server

Start the server by running the following command:

```sh
npm start
```

The server will start on port 3000.

## API Endpoints

The following API endpoints are available:

- `POST /upload`: Upload a file.
- `GET /files`: Get a list of all uploaded files.
- `GET /files/:filename`: Download a file.
- `DELETE /files/:filename`: Delete a file.

## Built With

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Multer](https://www.npmjs.com/package/multer)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
