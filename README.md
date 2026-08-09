# Spotify API Testing with Postman

API testing project using Spotify Web API and Postman.

## Tested Endpoints

- OAuth 2.0 Authorization
- Get Access Token
- Refresh Access Token
- Create Playlist
- Get Playlist
- Update Playlist

## Automated Tests

Post-response scripts are used to validate HTTP status codes.

Example:

```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
