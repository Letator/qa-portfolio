# API Testing

This section contains examples of API testing performed using Postman.

## API

The tests use the Postman Echo API for demonstration purposes.

## Tested Requests

### GET — Echo Response

**Endpoint:**

`GET https://postman-echo.com/get`

**Purpose:**

Verify that the API successfully returns a response to a GET request.

**Expected result:**

- HTTP status code is 200 OK.
- Response is returned in JSON format.
- Request information is present in the response.

---

### POST — Create Resource

**Endpoint:**

`POST https://postman-echo.com/post`

**Request body:**

```json
{
  "name": "Andrii",
  "role": "QA Engineer",
  "project": "QA Portfolio"
}
**Purpose:**

Verify that the API accepts POST requests and returns the submitted data.

**Expected result:**

- HTTP status code is 200 OK.
- Response is returned in JSON format.
- Submitted request data is returned in the response.

---

### GET — Non-existent Resource

**Purpose:**

Verify API behavior when requesting a non-existent resource.

**Expected result:**

- The API returns an appropriate HTTP error status.
- The response contains a valid error message.

---

## Testing Performed

- GET requests
- POST requests
- HTTP status code verification
- Response body verification
- JSON response validation
- Request data verification

## Tools

- Postman
- Postman Echo API

## Collection

The Postman collection is available in this repository:

`qa-portfolio-api-testing.postman_collection.json`
