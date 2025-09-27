
# 🏥 Medical System

## 📌 Overview
A **Medical Management System** designed to manage patients, doctors, and appointments.  
The platform provides separate roles for **Patients** and **Doctors** with appointment booking, medical records, and scheduling.

---

## ✨ Features

### Patients
- Register & manage personal profile (medical history, contact info).  
- Book appointments with doctors.  
- View upcoming and past appointments.  
- Cancel appointments if needed.  

### Doctors
- Register & update specialization & availability.  
- Manage patient appointments.  
- Approve or cancel bookings.  
- View patient medical history.  

---

## 🛠️ Tech Stack
- **Frontend:** React, Tailwind CSS, Axios  
- **Backend:** Django, Django REST Framework (DRF), JWT Authentication  
- **Database:** PostgreSQL  
- **Other:** GitHub, Agile/Scrum  

---

## 📂 Database Design
- `Users` → patients & doctors (roles).  
- `Patients` → medical history, phone, address.  
- `Doctors` → specialization, available slots.  
- `Appointments` → links patients & doctors (status: booked/canceled).  

---

## 🚀 Installation & Run

### Backend (Django)
```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
