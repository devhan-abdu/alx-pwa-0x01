# Movie App
### Api Overview
The movie api provides complete and updated data over 9 million titles in movies , serius and episodes and also data over 11 million actors 

### Api Version
we use V1 version

### Available Endpoints
  #### endpoint related to title
      - /titles/series/{seriesid}
      - /titles/x/upcoming
      - /titles/{id}/ratings
      - /titles
      - /tiles/seasons/{seriesid}
  #### enpoint used to search
      - /titles/search/akas/{aka}
      - /titles/search/keyword/{keyword}
      - /titles/search/title/{title}
 #### endpoint related to actors
     - /actors/random
     - /actors/{id}
     - /actors
## Request and Response Format
   a, Titles  - multple
       endpoint : /titles
       description: it return array of title according to filters /sorting query                              parameters provided
## Authentication

All requests to this API require authentication via RapidAPI headers.  
You must include the following headers in every request:

- `x-rapidapi-key`: **Your personal API key** (obtainable from your RapidAPI dashboard)
- `x-rapidapi-host`: `moviesdatabase.p.rapidapi.com`

## Error Handling

The API uses standard HTTP status codes to indicate success or failure of a request.  
Common responses include:

- **200 OK** – The request was successful.
- **400 Bad Request** – The request parameters are invalid or missing required fields.
- **401 Unauthorized** – Your API key is missing or invalid.
- **404 Not Found** – The requested resource could not be found.
- **429 Too Many Requests** – You have exceeded the allowed rate limit.
- **500 Internal Server Error** – A server-side error occurred.

## Usage Limits and best practices"
  - **Request** =  500, 000 /month
  - **Rate Limit** - 1000 requwest per hour
    
    
       