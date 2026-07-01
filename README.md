# JSONPlaceholder API Testing

## Overview
This project contains API test cases created with Postman for the JSONPlaceholder REST API.

## API Under Test
https://jsonplaceholder.typicode.com/posts

## Tools
- Postman
- JSONPlaceholder

## Test Scenario
**GET /posts**

## Test Cases
- Verify status code is 200
- Verify response is an array
- Verify response contains 100 posts
- Verify required fields exist (userId, id, title, body)
- Verify data types are correct
- Verify response time is less than 1000 ms
- Verify title is not empty
- Verify body is not empty

## Files
- JSONPlaceholder API Testing.postman_collection.json

## Expected Result
All test cases should pass successfully.
