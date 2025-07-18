## 📘 Overview
The **Smart Parking System** is a responsive web-based application designed to streamline parking management in urban areas. Developed with frontend technologies, it enables real-time tracking of available slots, revenue monitoring, and vehicle entry/exit with duration-based billing.

---

## 🔧 Key Features

- 📊 **Dashboard Overview**
  - Available vs Occupied slots
  - Real-time revenue tracking
- 🅿️ **Vehicle Entry/Exit Form**
  - Enter vehicle number
  - Check-in and check-out with timestamp tracking
- ⏱ **Duration & Billing**
  - Calculates total time parked and generates bill (₹20/hr)
- 📋 **Live Vehicle Log**
  - Displays all checked-in/out vehicles with:
    - Time in/out
    - Duration parked
    - Total charge
- 📱 **Responsive Design**
  - Mobile and desktop friendly UI using Tailwind CSS



##  Tech Stack

- **HTML5**
- **Tailwind CSS** (via CDN)
- **Font Awesome** (Icons)
- **Google Fonts** – Roboto
- **Vanilla JavaScript** (No frameworks)

---

## How It Works

1. **Check-In**:
   - User enters vehicle number.
   - Vehicle is added to the system with check-in timestamp.
   - Slot count updates automatically.

2. **Check-Out**:
   - User enters the same vehicle number.
   - System calculates duration and applies the hourly rate.
   - Dashboard and revenue updates in real-time.

3. **Table Log**:
   - Vehicle history is shown in a table with check-in/out times and total charge.


## ✅ To Use

1. Open `spark.html` in any modern web browser.
2. Interact with the dashboard by entering vehicle numbers and using the "Check In" and "Check Out" buttons.
3. Watch the dashboard and vehicle logs update live.

---

## Possible Enhancements

* Back-end integration (Firebase, Node.js) for persistence
* Admin authentication
* QR code-based vehicle scanning
* SMS/Email alerts for billing


