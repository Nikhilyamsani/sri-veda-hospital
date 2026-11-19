# Sri Veda Multi Specialty Hospital - Web Application

A clean, responsive, and easy-to-understand web application portal for **Sri Veda Multi Specialty Hospital**, built using standard **HTML5, CSS3, JavaScript, and React 18**.

Designed with **simple, unbloated code** that can run immediately in any browser with **zero complex build steps** or dependencies.

---

## 🌟 Key Features

1. **🏥 Hospital Branding & Hero Section**
   - Highlights 24/7 Trauma & Emergency, 500+ hospital beds, 120+ senior doctors, and NABH/JCI accreditation.
   - Quick action buttons to book appointments or explore specialists.

2. **🩺 Clinical Specialties (Centres of Excellence)**
   - Cardiology, Neurology & Spine, Orthopedics, Pediatrics & NICU, Obstetrics & Gynecology, Oncology, Nephrology, and General Medicine.
   - One-click "Book Consultation" that auto-selects the specialty in the booking form.

3. **👨‍⚕️ Doctors Directory & Live Search**
   - Browse doctors by medical department or search by name/qualification.
   - Doctor cards with qualifications, years of experience, OPD consulting hours, and consultation fees.
   - One-click "Book Appointment" that pre-fills both doctor and department.

4. **📅 Interactive Appointment Booking System**
   - Real-time form with patient details, age, gender, contact number, doctor selection, date, time slot, and symptom details.
   - Generates a unique **Booking Token** (e.g. `SVEDA-1084`).
   - Confirmation modal with instant summary and automated persistence to `localStorage`.

5. **📋 Patient Portal & Diagnostic Records**
   - **My Appointments:** Real-time list of booked appointments with status badges (Confirmed/Cancelled) and option to cancel or print slips.
   - **Lab Test Reports:** Interactive viewer for diagnostic lab results (CBC, Lipid Profile, ECG/2D Echo, MRI Spine) with standard reference ranges and pathologist remarks.
   - **Live Bed Tracker:** Visual progress bars displaying current real-time occupancy across ICUs, Emergency, Deluxe Rooms, and General Wards.

6. **🚨 24x7 Emergency Ambulance SOS Dispatch**
   - Dedicated emergency hotline banner with blinking status beacon.
   - Interactive SOS form: enter pickup address and phone number for immediate ambulance dispatch confirmation with live unit ID and ETA.

---

## 🚀 How to Run the Application

You have two easy ways to run this application:

### Option 1: Direct in Browser (No Server Needed)
Simply **double-click `index.html`** in your file explorer to open it in Google Chrome, Microsoft Edge, Firefox, or Safari!

### Option 2: Run with Local Node Server (Recommended)
Open your terminal in this directory (`C:\Users\nikhi\.gemini\antigravity\scratch\sri-veda-hospital`) and run:

```bash
npm start
```
*(or run `node server.js`)*

Then open your browser and navigate to:
```
http://localhost:3000
```

---

## 📂 Project Structure

```
sri-veda-hospital/
│
├── index.html        # Main HTML file with React 18 & Babel Standalone integration
├── style.css         # Clean, responsive CSS with modern color palette & variables
├── app.jsx           # Clean, modular React component code
├── server.js         # Lightweight zero-dependency local Node.js static server
├── package.json      # Project definition and npm start command
└── README.md         # Documentation and guide
```

---

## 💡 Technologies Used

- **HTML5:** Semantic markup, accessible layout, responsive viewport.
- **CSS3:** Custom properties (CSS variables), Flexbox, CSS Grid, animations, and mobile breakpoints.
- **JavaScript (ES6+):** Clean state management, dynamic array filtering, template literals, and `localStorage` persistence.
- **React 18:** Functional components, React Hooks (`useState`, `useEffect`, `useMemo`), and declarative UI updates.
