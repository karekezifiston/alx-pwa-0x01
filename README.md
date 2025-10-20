## API Overview
The MoviesDatabase API allows developers to fetch movie information. You can filter movies by year, genre, and paginate results. The API provides details such as movie title, release year, and poster images.

## Version
v1.0

## Available Endpoints
- `/titles`: Fetch movie data
  - Supports filtering by year and genre
  - Supports pagination

## Request and Response Format
- **Request Example:**
```json
POST /titles
{
  "year": 2024,
  "genre": "Action",
  "page": 1
}
