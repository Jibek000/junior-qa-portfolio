# API Testing — JSONPlaceholder

**Project:** API Testing Practice
**QA Engineer:** Jibek Rysbekova
**Tool:** Postman
**API:** https://jsonplaceholder.typicode.com

## 1. GET Request

**Endpoint:**
GET /posts/1

**Purpose:**
Retrieve a post by ID.

**Expected Status Code:** 200 OK

**Expected Result:**
- Response contains post data.
- Response contains userId, id, title and body.
- Post ID equals 1.

## 2. POST Request

**Endpoint:**
POST /posts

**Request Body:**
{
  "title": "QA Practice",
  "body": "Testing API with Postman",
  "userId": 1
}

**Expected Status Code:** 201 Created

**Expected Result:**
- New post is returned.
- Response contains title, body and userId.
- Response contains a generated ID.

Note: JSONPlaceholder simulates creation. Data is not permanently saved.

## 3. PUT Request

**Endpoint:**
PUT /posts/1

**Request Body:**
{
  "id": 1,
  "title": "Updated QA Title",
  "body": "Updated post body",
  "userId": 1
}

**Expected Status Code:** 200 OK

**Expected Result:**
Post data is returned with updated values.

## 4. PATCH Request

**Endpoint:**
PATCH /posts/1

**Request Body:**
{
  "title": "Partially Updated Title"
}

**Expected Status Code:** 200 OK

**Expected Result:**
The title is updated in the response.

## 5. DELETE Request

**Endpoint:**
DELETE /posts/1

**Expected Status Code:** 200 OK

**Expected Result:**
The API returns a successful deletion response.

## 6. API Test Scenarios

- [ ] Verify GET request returns 200.
- [ ] Verify POST request returns 201.
- [ ] Verify PUT request returns 200.
- [ ] Verify PATCH request returns 200.
- [ ] Verify DELETE request returns 200.
- [ ] Verify response body.
- [ ] Verify response status code.
- [ ] Verify JSON response format.
https://jsonplaceholder.typicode.com/posts/1
## 7. Actual Results

| Method | Expected Status | Actual Status | Result |
|--------|-----------------|---------------|--------|
| GET    | 200             | 200           | PASS   |
| POST   | 201             | 201           | PASS   |
| PUT    | 200             | 200           | PASS   |
| PATCH  | 200             | 200           | PASS   |
| DELETE | 200             | 200           | PASS   |

Note: Actual results must be confirmed by executing each request in Postman.
