# Hotel Booking API — QA Testing

## Overview

Manual API testing project completed as part of a QA home task.

The project focuses on functional testing of a REST API for a hotel booking system using Postman.

## Source Repository

The API used for testing was provided as part of the original QA home task:

[Hotel Booking API — Original Repository](https://github.com/Zunft-Inc/qa-home-task)

The source repository contains the API implementation and task requirements.
This repository contains my QA testing artifacts and documentation.

## Testing Scope

- REST API testing
- Functional testing
- Positive and negative testing
- Authentication and authorization
- HTTP status code validation
- Request and response validation
- JSON request/response testing
- Query parameter testing
- Error handling

## Tools

- Postman
- Jira
- Qase
- GitHub

## Test Coverage

### Authentication

- Login with valid and invalid credentials
- Empty and missing fields
- Case sensitivity
- Partial password validation
- Authentication response validation

## Test Artifacts

- Test cases
- Bug reports
- Postman collection

## Defects Found

During testing, several defects were identified, including:

- Incorrect HTTP status code returned for invalid login credentials
- Authentication bypass caused by acceptance of a partial password
