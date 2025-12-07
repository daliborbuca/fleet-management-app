# fleet-management-app
Custom fleet management web application built using Supabase + AI Builder.
# 🚗 Fleet Management Web Application

A custom web application built to organize company vehicle data, automate mileage tracking and improve visibility of contracts and fleet operations.

---

## 📌 Features  

- Role-based access (Admin / Driver)  
- Vehicle list with key details (model, registration, user, status)  
- Contract tracking with start/end dates and mileage limits  
- Mileage input with validation and alerts for exceeded limits  
- Service / registration / contract-expiry reminders  
- Dashboard with real-time overview of vehicles and alerts  
- Supabase backend with RLS policies  
- Responsive UI for desktop and mobile  

---

## 🛠 Tech Stack  

- **Supabase** – database, authentication, RLS  
- **JavaScript**  
- **HTML / CSS**  
- **Hostinger AI Website Builder / AI tools**  
- **Git & GitHub**  

---

## 🧩 Database Structure (Supabase)  

Main tables:  

- `vehicles` – basic info (brand, model, plate, VIN, cost center…)  
- `drivers` – driver/user data  
- `contracts` – leasing details, mileage limits, start/end dates  
- `mileage_logs` – user-entered mileage over time  
- `alerts` – generated warnings (contract expiry, mileage threshold, etc.)

Each table is protected with **Row Level Security (RLS)** and policies for Admin and Driver roles.

---

## 🎯 Purpose  

This project was created as part of my **Bachelor thesis in Electrical & Computer Engineering**.  
The goal is to replace manual Excel tracking and emails with a central digital system for fleet management, reducing errors and saving time for administrators and drivers.

---

## 📸 Screenshots  

_Screenshots of the dashboard, forms and alerts will be added here._  

---

## 🚀 Future Improvements  

- Advanced analytics dashboard (costs, mileage per vehicle/driver)  
- Email notifications for upcoming deadlines  
- Service history tracking  
- Multi-company support  
