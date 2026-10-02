# HW1-Movie-Kiosk
A self-service movie ticket booking application that allows customers to browse available movies, select showtimes, choose seats, and purchase tickets. The system provides booking confirmations and prevents duplicate seat reservations, ensuring a smooth and convenient ticket-booking experience.
## Purchase Ticket

**Primary Actor:** Customer

**Precondition:**  
The customer has selected a movie, showtime, and an available seat.

**Main Steps:**
1. The customer selects a movie showtime.
2. The kiosk displays available seats.
3. The customer selects an available seat.
4. The system checks that the selected seat is still available.
5. The customer proceeds with the ticket purchase.
6. The payment is processed.
7. The system marks the selected seat as sold.
8. The kiosk displays a purchase confirmation.

**Postcondition:**  
The ticket purchase is completed, the selected seat is reserved for the customer, and a confirmation is displayed.
