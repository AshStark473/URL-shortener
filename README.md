# URL-shortener
Web App to shorten a URL

This Node.js application utilizes Express and MongoDB to create a simple short URL generator. Here's a brief summary of the key functionalities:

Features:
Database Connection:

Connects to a MongoDB database on the local server.
Create Short URL:

Generates a unique short URL ID for a given long URL.
Inserts the long URL and its corresponding short URL ID into the database.
Retrieve All Short URLs:

Retrieves all entries from the "links" table in the database.
Redirect Short URL:

Redirects to the original long URL when a valid short URL is accessed.
Updates the access count in the database.
