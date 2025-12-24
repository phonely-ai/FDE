# Forward Deployed Technical Exercise – Airline Voice Assistant (Phonely)

## Purpose
You will build a **voice assistant for an airline company** using **Phonely**. 
Then you will pitch the demo as if you're doing a live demo to a potential customer.

---

## Scenario
A customer calls an airline support line. The assistant should be able to help with:

- **Book a flight**

---

## Functional Expectations (High Level)

### 1) Resolve Airport Names
Callers will provide **city names** or **airport names** (e.g., “Los Angeles”, “JFK”, “San Francisco airport”).
The system should reliably interpret this as an **IATA airport code** (e.g., LAX, JFK, SFO).

---

### 2) Flight Lookup and Options
For booking flows, callers provide:
- **Departure location**
- **Destination location**
- **Date of travel**

The assistant should:
- Retrieve available flight options
- Present multiple options
- Help the caller choose an option

### 3) Booking Confirmation

After the caller selects a flight and provides details, the system should:
- Collect the following details:
  - **Full name**
  - **email**
- Confirm the booking
- Generate a **confirmation number**
- Store the booking in a simple “CRM” represented by the **CSV file**

The assistant should confirm critical details back to the caller before finalizing.
---

### 4) Send Confirmation to the Caller
Send a confirmation email containing:
- departure, arrival, airline, flight number, date/time, confirmation number

---

## Data & Storage
- Treat the airline “CRM” as a **CSV file**.
- It should store new bookings.
- see **bookings.csv** for flight bookings
- see **flights.csv** for available flights

Use whatever IDE you want, as much AI as you want. This is meant to see how you think and communicate
