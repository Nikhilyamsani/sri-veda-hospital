# Sri Veda Multi Specialty Hospital - Web Application

A clean, simple, and beginner-friendly web application for **Sri Veda Multi Specialty Hospital** built using standard **HTML, CSS, JavaScript, and React**.

Designed with **simple, human-readable code** that is easy to understand, modify, and run.

---

## 🌟 Key Features

1. **🏥 Hospital Overview & Home Page**
   - Clean navigation bar and 24/7 emergency hotline.
   - Hospital key statistics (24/7 emergency, 25+ specialist doctors, 100+ beds, 15,000+ patients).
   - Quick action buttons to book an appointment or browse doctors.

2. **🩺 Medical Departments**
   - Cardiology, Neurology, Orthopedics, Pediatrics, and General Medicine.
   - Quick "Book Appointment" button on each specialty card.

3. **👨‍⚕️ Specialist Doctors**
   - View doctors with their qualification, experience, OPD timings, and consultation fee.
   - One-click booking with the selected doctor.

4. **📅 Appointment Booking Form**
   - Simple form to book an appointment with Patient Name, Mobile Number, Department, Doctor, Date, and Time Slot.
   - Generates a unique Token ID (e.g. `SV-102`).
   - Automatically saved to your browser's `localStorage`.

5. **📋 My Bookings**
   - View your booked appointments list.
   - Status badge ("Confirmed" or "Cancelled").
   - Option to cancel any appointment.

6. **📞 Contact & Emergency**
   - 24/7 emergency helpline number.
   - General hospital reception and email contacts.

---

## 🚀 How to Run the Project

### Option 1: Direct in Browser (No Server Needed)
Simply **double-click `index.html`** in your file explorer to open it in Google Chrome, Microsoft Edge, or Firefox.

### Option 2: Using VS Code
1. Open this folder in VS Code (`File` > `Open Folder...`).
2. Open terminal in VS Code (`Ctrl + ~`) and type:
   ```bash
   npm start
   ```
3. Open your browser at: `http://localhost:3000`

---

## 📂 Project Structure

```
sri-veda-hospital/
│
├── index.html        # Clean HTML file with React & Babel
├── style.css         # Simple and clean CSS stylesheet
├── app.jsx           # Simple React component code
├── server.js         # Basic Node.js server (optional)
├── package.json      # Project info
└── README.md         # Documentation
```
