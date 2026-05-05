# Emerald Airlines - Flight Management System

Desktop application for booking and managing flight reservations.

## What It Does

- **User Authentication**: Secure login system for employees
- **Flight Booking**: Search and book flights with origin/destination selection, one-way or round-trip options
- **Passenger Management**: Handle adult and child passengers with seat selection
- **Flight Cancellation**: Cancel existing reservations
- **Dynamic Pricing**: Class-based and passenger-type pricing

## Tech Stack

- **Frontend**: Tkinter (Python GUI)
- **Backend**: Python 3
- **Database**: MySQL
- **Libraries**: PIL (Image processing), tkcalendar (Date selection)

## How to Run

```bash
# Install dependencies
pip install pillow tkcalendar mysql-connector-python

# Start the application
python Login.py
```

## Project Structure

- `Login.py` — Employee authentication
- `main.py` — Main flight booking interface
- `Try.py` — Flight search and booking engine
- `Register.py` — Employee registration
- `Cancel.py` — Flight cancellation workflow

---

Built as a high school final project demonstrating GUI development, database integration, and booking system design.
