# API Testing Project

## Overview
This project contains automated API test collections created using Postman.

The collection validates:
- Authentication endpoints
- CRUD operations
- Response status codes
- Response time validation
- Negative test scenarios
- Schema validation

## Tools Used
- Postman
- Newman (CLI runner)
- GitHub Actions (CI Integration)

## How to Run Tests Locally

Install Newman:
npm install -g newman

Run collection:
newman run API-Testing-Project.postman_collection.json

## CI Integration
Tests automatically execute using GitHub Actions on every push.
