# Reservations API Checklist

## Get Reservation IDs

- [ ] Get all reservation IDs without filters
- [ ] Filter reservations by first name and last name
- [ ] Filter reservations by first name only
- [ ] Filter reservations by last name only
- [ ] Filter reservations by check-in date
- [ ] Filter reservations by check-out date
- [ ] Reject invalid check-in date format with HTTP 400 Bad Request
- [ ] Get reservation by valid ID
- [ ] Return HTTP 404 Not Found for a non-existing reservation ID
- [ ] Handle invalid reservation ID correctly
- [ ] Return reservation data in XML format when requested
