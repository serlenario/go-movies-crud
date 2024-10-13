# go-movies-crud

API Methods:
- GET /movies — Returns a list of all movies.
- GET /movies/{id} — Retrieves details of a movie by its ID.
- POST /movies — Creates a new movie. Expects JSON with isbn, title, and director.
- PUT /movies/{id} — Updates a movie with the specified ID. Expects updated data in JSON format.
- DELETE /movies/{id} — Deletes a movie by its ID.