# 🚗 Fleet Management App

> A custom web application for managing company vehicles, contracts, and driver assignments — built as a Bachelor's thesis project in Electrical & Computer Engineering.

![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
![Built With](https://img.shields.io/badge/Built%20With-Supabase%20%7C%20JavaScript%20%7C%20HTML%2FCSS-3ECF8E?style=flat-square)

---

## 📋 Overview

Most small and medium businesses still track their vehicle fleets in Excel — scattered files, no real-time visibility, manual updates. This app replaces that with a centralized, role-based web platform that automates the most tedious parts of fleet management.

Built as a capstone thesis project, it demonstrates full-stack development using modern cloud infrastructure.

---

## ✨ Features

- **Role-based access control** — separate views for Administrators and Drivers
- **Vehicle management** — register vehicles, track status and specs
- **Contract monitoring** — lease terms, mileage limits, expiration tracking
- **Automated mileage logging** — drivers log entries with built-in validation
- **Real-time alerts** — automatic warnings for contract expirations and mileage threshold breaches
- **Responsive design** — works seamlessly on desktop and mobile

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend / Database | [Supabase](https://supabase.com) (PostgreSQL + Auth + RLS) |
| Frontend | HTML, CSS, JavaScript |
| Authentication | Supabase Auth (email/password with role-based policies) |
| Security | Row Level Security (RLS) policies per user role |
| Hosting | Hostinger |
| Version Control | Git & GitHub |

---

## 🗄️ Database Schema

```
vehicles       — vehicle specs, registration, current status
drivers        — user accounts and driver info
contracts      — lease terms, mileage limits, expiry dates
mileage_logs   — timestamped mileage entries per vehicle/driver
alerts         — auto-generated warnings for limit breaches
```

---

## 🔮 Roadmap

- [ ] Advanced analytics dashboard with charts
- [ ] Email/SMS notifications for alerts
- [ ] Service history and maintenance scheduling
- [ ] Multi-company / multi-fleet support
- [ ] Export reports to PDF/Excel

---

## 👨‍💻 Author

**Dalibor Stanojlovic**
[dtcreativesolutions.com](https://dtcreativesolutions.com) · [LinkedIn](https://www.linkedin.com/in/dalibor-stanojlovic-0438a7133)
