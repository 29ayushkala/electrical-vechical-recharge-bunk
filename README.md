# 🚗⚡ Electric Vehicle Charging Slot Booking System

### **By Ayush Kala**

The **Electric Vehicle (EV) Charging Slot Booking System** is a web-based solution designed to help EV users easily locate nearby charging stations, check real-time slot availability, and book charging slots through an intuitive interface.
This system reduces long queues at EV charging stations and enhances the smart city EV infrastructure.

---

## 📌 Problem Statement

Future smart cities depend heavily on transportation electrification.
To support this, charging stations must be easily discoverable and efficiently managed.

However, EV owners often face challenges such as:

* Long waiting queues
* Uncertainty about slot availability
* Difficulty locating nearby EV bunk stations

This project solves these issues by providing:

* Nearby charging station discovery
* Slot availability checking
* Real-time booking
* Google map location access
* Admin-controlled station management

---

# 🚀 Features

## 👨‍💼 **EV Admin Module**

* Admin Login
* Create EV Bunk (Charging Station) Details
* Manage / Update / Delete Bunk Details
* Add Location, Address, Mobile Number, Google Map Link
* Manage Charging Slots (Create / Update / Availability)

---

## 👤 **User Module**

* User Registration & Login
* Search Nearby EV Bunks
* View Bunk Details & Slot Vacancy
* Book Charging Slots
* View station’s address, mobile number, map location

---

# 🛠️ Technologies Used

* **HTML** – Frontend UI
* **CSS** – Styling and responsiveness
* **JavaScript** – Logic, validation, user interaction
* **Firebase Authentication** – Login & registration
* **Firebase Firestore Database** – Store bunk details, slots, users
* **Firebase Hosting (optional)** – Deployment
* **JavaScript Logging** – Log user/admin actions

---

# 📦 System Requirements (Coding Standards)

This project is built to be:

✔ **Modular** – Code split into manageable modules
✔ **Safe** – Input validation & Firebase rules
✔ **Testable** – Each module independently testable
✔ **Maintainable** – Clean folder structure
✔ **Portable** – Works on all operating systems
✔ **Optimized** – Efficient queries, reduced redundancy

---

# 📂 Module Overview

### **Authentication**

* Firebase-based secure login & registration
* Logging for login/logout attempts

### **EV Bunk Management (Admin)**

* Store bunk name, address, map link, mobile number
* Create/manage multiple time slots

### **Slot Booking (User)**

* View available slots
* Book real-time
* Prevent double bookings
* Firebase updates reflect instantly

### **Search**

* Search nearby EV charging stations
* Based on location, name, or area

---

# ▶️ How to Run the Project

1. Clone the repository:

   ```
   git clone https://github.com/your-username/EV-Charging-Slot-Booking.git
   ```
2. Open the folder in VS Code.
3. Add Firebase config in `firebase.js`.
4. Open `index.html` in the browser.
5. Start using:

   * **Admin:** Create/Manage EV Bunks
   * **User:** Search & Book Charging Slots

---

# 🧪 Test Cases (Sample)

| Test Case                 | Input                | Expected Result            |
| ------------------------- | -------------------- | -------------------------- |
| User Login                | Valid credentials    | Redirect to user dashboard |
| Booking Slot              | Valid slot selection | Booking confirmed          |
| Admin Adds Bunk           | Valid details        | Bunk added to Firestore    |
| Search EV Bunk            | Location name        | Relevant bunk list shown   |
| Empty Registration Fields | Missing info         | Show error popup           |

---

# ☁️ Deployment

You may host using:

* Firebase Hosting
* GitHub Pages
* Local server

---

# 📄 Submission Requirements

* GitHub Public Repository
* README with workflow & setup steps
* Detailed Project Report
* Optimized code structure
* Firebase configuration included

---

# ✅ Conclusion

The **Electric Vehicle Charging Slot Booking System** improves EV accessibility by helping users find charging stations easily and book available slots without waiting in long queues.
Built with Firebase and modern web technologies, this project is scalable, secure, and future-ready.

---

Created with ❤️ by **Ayush Kala**
