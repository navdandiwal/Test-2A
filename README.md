# Dinner Booking Web Form

##Overview

This is a responsive HTML + JavaScript web form designed for booking dinner reservations. It collects the user's name, phone number, preferred dining time, and selected extras (such as Starters or Drinks). The form includes **real-time input validation** and generates a **summary output** upon successful submission.

## File

This file contains:

- All HTML elements for form inputs, labels, buttons, and output.
- Embedded JavaScript for validation and logic.
- Inline CSS for basic styling.

---

## Features Implemented

1. **Name Validation**
- Requires the user to enter **both first and last names** (minimum two words).
- Displays an error message if input is invalid.
- Turns input border red on error.

2. **Phone Number Validation**
- Must be exactly **8 numeric characters**.
- Starts with a number only.
- Displays an error message if invalid.

3. **Time Selection**
- The user selects a time using **radio buttons**.
- Default selection is `05:00`.

4. **Extras Selection**
- Multiple options (checkboxes): Starters, Main Course, Desserts, Drinks.
- Optional, can choose any number (including none).

5. **Submit Button**
- **Disabled by default**.
- Enabled only when both **name and phone number are valid**.

##Author

**Navdeep Singh** 
