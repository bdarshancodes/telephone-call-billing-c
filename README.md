# Telephone Call Billing System in C

This project is a **Telephone Call Billing System** written in C.  
It calculates the bill amount based on the **call arrival time** and **duration of the call**.  
It applies different **discounts** and **tax rates** depending on peak and off-peak hours.

---

## Features
- Takes **Call Arrival Time** (0–24 hrs).
- Takes **Call Duration** in minutes.
- Call charges:
  - Base rate = Rs. 0.40 per minute
- Discounts & taxes:
  - **Off-Peak Hours (18:00 to 8:00)**:
    - If call > 60 minutes → 15% discount, then 4% tax
    - If call ≤ 60 minutes → 50% discount, then 4% tax
  - **Peak Hours (8:00 to 18:00)**:
    - If call > 60 minutes → 15% discount, then 4% tax
    - If call ≤ 60 minutes → No discount, only 4% tax

---

## How to Run
1. Save the file as `call_billing.c`
2. Compile the program:
   ```bash
   gcc call_billing.c -o call_billing
bdarshancodes
MCA Student | Exploring C, C++, DSA, AI, and Algorithmic Trading
