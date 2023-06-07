# WikiDB - RESTful API

This is a simple RESTful API for a hypothetical wiki website. The application is built with Node.js, Express, and MongoDB. This API allows to perform CRUD operations on articles in a MongoDB database.

## Installation

Before starting, make sure you have Node.js and MongoDB installed on your system.

```bash
# Clone the repository
git clone https://github.com/Bonus1337/WikiDB_RESTful_API.git

# Go to the project directory
cd WikiDB_RESTful_API

# Install dependencies
npm install
```

## Usage

Start the server.

```bash
node app.js
```

The server is now running on `http://localhost:3000`.

## Endpoints

Here are the available API endpoints:

### `/articles`

- **GET**: Fetches all articles from the database.
- **POST**: Adds a new article to the database. The title and content should be provided in the request body.
- **DELETE**: Deletes all articles from the database.

### `/articles/:articleTitle`

- **GET**: Fetches a specific article from the database using the article title.
- **PUT**: Updates a specific article. The new title and content should be provided in the request body. This operation overwrites the entire article.
- **PATCH**: Updates one or more properties of a specific article. The properties to be updated should be provided in the request body.
- **DELETE**: Deletes a specific article using the article title.

## Dependencies

- [express](https://www.npmjs.com/package/express)
- [body-parser](https://www.npmjs.com/package/body-parser)
- [ejs](https://www.npmjs.com/package/ejs)
- [mongoose](https://www.npmjs.com/package/mongoose)

## License

This project is licensed under the MIT License.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

**Note**: Replace 'yourusername' and 'your-repository' with your actual GitHub username and repository name in the above instructions.
