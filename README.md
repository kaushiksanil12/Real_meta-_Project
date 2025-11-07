# 🖼️ RealMeta: Museumverse Experience

RealMeta is a multi-module web application designed to enhance the museum experience through intelligent analytics, interactive user engagement, and AI-powered painting recognition.

## 📦 Project Structure

This repository uses Git submodules to organize different components:

- `Admin_dashboard`: Analytics dashboard for museum administrators
- `Admin_backend`: Backend services for admin operations
- `Admin_frontend`: Frontend interface for admin users
- `User_frontend`: Interactive frontend for museum visitors
- `User_backend`: Backend services for user interactions
- `backend_02`, `dashboard`, `hackothsavawebapp`, `realmeta_backend_1`: Submodules linked to external repositories

---

## 🌐 Live Demos
## Note :Backend takes time to restart from sleep state it will take atleast 2 mins for the server to start

- **User Frontend**:https://hackothsavawebapp.onrender.com
  Interactive interface for museum visitors using Google Vision and Groq API.

- **Admin Dashboard**:https://dashboard-0o00.onrender.com/
  Analytics panel for administrators to manage paintings, view user data, and generate QR codes.

## 🧠 Features

### 🎛️ Admin Dashboard
- View detailed **user analytics** and interaction metrics
- Add new **paintings** to the database
- Generate **QR codes** for each painting to enable quick access
- Track **dwell time** for each artwork to measure visitor engagement

### 🖼️ User Frontend
- Uses **Google Vision API** to detect paintings or objects from camera input
- Sends detected image data to **Groq API** to retrieve rich descriptions of the artwork
- Offers interactive features like:
  - **Rating system**
  - **Feedback submission**
  - **Audio guide playback**

### 🔐 Backend Services
- Secure APIs for both admin and user modules
- Handles image processing, QR generation, and dwell time tracking

## 🛠️ Technologies Used

| Module            | Tech Stack                          |
|-------------------|-------------------------------------|
| Admin Dashboard   | React, Node.js, Express, MongoDB    |
| User Frontend     | HTML/CSS/JS, Google Vision API, Groq API |
| Backend Services  | Node.js, Express, MongoDB           |
| QR Code Generator | `qrcode` npm package                |

## 🚀 Getting Started

To clone this repository with submodules:
```bash
git clone --recurse-submodules https://github.com/<your-username>/Real_Meta.git
```

To initialize submodules after cloning:
```bash
git submodule update --init --recursive
```

## 📌 Notes

- Ensure you have API keys for **Google Vision** and **Groq** configured in your environment.
- QR codes are generated dynamically and can be printed or embedded in museum displays.
- Dwell time is tracked using timestamped user interactions.

---
