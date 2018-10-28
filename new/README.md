# FreeCodeCamp - Backend Challenges
## API Projet: URL Shortener Microservice
### User stories:
1. I can pass a URL as a parameter and I will receive a shortened URL in the JSON response.
2. If I pass an invalid URL that doesn't follow the valid http://www.example.com format, the JSON response will contain an error instead.
3. When I visit that shortened URL, it will redirect me to my original link.
## Example usage:
```url
https://fcc-api-3.glitch.me/new/https://www.google.com
https://fcc-api-3.glitch.me/new/http://foo.com:80
```
## Example output:
```json
{ "original_url":"http://foo.com:80", "short_url":"https://fcc-api-3.glitch.me/8170" }
```
