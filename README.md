# Hotel_Simulator

##  Features

-  **Check-In Form** with validation for:
  - Guest Name
  - Room Number
  - Stay Duration
-  **Room Availability Logic**: Prevents booking a room that’s already taken.
-  **Guest List** rendered dynamically in stylish cards.
-  **JavaScript Constructor Function** to manage guests.
-  **Beach Vibes UI** with Bootstrap + custom CSS for a sunny feel.

##  Technologies Used

- HTML5
- CSS3 + Bootstrap
- JavaScript (Vanilla)

##  How It Works

1. **Prepopulated Guests** are displayed when the page loads.
2. Users can **fill out the form** to check in new guests.
3. On submission, JavaScript:
   - Validates input
   - Checks if the room is available
   - Adds the guest if valid
   - Updates the guest list dynamically
   - Displays a message if the room is already booked
4. The form is cleared after each successful check-in.