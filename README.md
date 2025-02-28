### Express-Blog-Assignment

The application is designed to serve as a foundational structure for more complex projects and provides clear examples of how to handle routes and controllers in an Express environment.

## Features

- **Create Blog**: Add a new blog entry.
- **Read Blog**: Retrieve a list of all blog entries.
- **Update Blog**: Modify an existing blog entry.
- **Delete Blog**: Remove a blog entry.

## Technologies Used

- **Node.js**: JavaScript runtime for server-side programming.
- **Express.js**: Web application framework for Node.js.
- **JSON**: Data format used for sending and receiving data.

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd express-blog-project

   ```

2. Install the dependencies:

   ```bash
   npm install

   ```

3. Start the server:

   ```bash
   node app.js

   ```

4. The server will run on http://localhost:3000.

### API Endpoints

# POST /api/blogs/createBlog - Create a new blog entry

Response: Blog created successfully

# GET /api/blogs/readBlog - Retrieve blog entries

Response: Blog read successfully

# PUT /api/blogs/updateBlog - Update a blog entry

Response: Blog update successfully

# DELETE /api/blogs/deleteBlog - Delete a blog entry

Response: Blog delete successfully

## Usage

You can use tools like Postman or cURL to test the API endpoints. Make sure to set the request method and URL as specified in the API endpoints section.
