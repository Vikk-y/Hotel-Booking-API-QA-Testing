# Hotel Booking API — QA Testing

## Overview

Manual API testing completed as part of a QA home task.

The project focuses on functional testing of a REST API for a hotel booking system using Postman.

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

**Test cases:** 15  
**Bug reports:** 2  
**Checklist:** Login API checklist

### Reservations

- Get all reservation IDs
- Filter reservations by first name and last name
- Filter reservations by first name or last name
- Filter reservations by check-in and check-out dates
- Invalid check-in date format validation
- Get reservation by valid ID
- Handle non-existing and invalid reservation IDs
- Get reservation in XML format

**Test cases:** 11  
**Bug reports:** 4  
**Checklist:** Reservations API checklist

## Test Artifacts

- Checklists
- Test cases
- Bug reports

## Defects Found

During testing, 6 defects were identified, including:

### Authentication

- Incorrect HTTP status code returned for invalid login credentials
- Authentication bypass caused by acceptance of a partial password

### Reservations

- Last name filter returns an empty result
- First name and last name filter returns an empty result
- Check-out date filter excludes reservations matching the specified date
- Invalid check-in date format is accepted instead of returning HTTP 400

## Project Summary

**Total test cases:** 26  
**Total bug reports:** 6  
**Checklists:** 2
