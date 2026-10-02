# Movie Theater Ticket Kiosk

This repository contains artifacts for a simple movie theater self-service ticket kiosk. Customers can view available movies and showtimes, select an available seat, purchase a ticket, and receive confirmation.

The system also ensures that the same seat cannot be sold to multiple customers.

## Expanded Use Case: Purchase Ticket

**Primary Actor:** Customer

**Precondition:**  
The customer has selected a movie, showtime, and an available seat.

### Main Steps

1. The customer selects a movie and showtime.
2. The system displays available seats.
3. The customer selects an available seat.
4. The system verifies that the seat is still available.
5. The customer provides payment information.
6. The system processes the payment.
7. The system creates the ticket.
8. The system displays a purchase confirmation.

**Postcondition:**  
The ticket is successfully purchased, the selected seat is marked unavailable, and a confirmation is provided to the customer.
