# 🩺 ArogyaSakhi – Digital Health & Wellness Platform 🌿

ArogyaSakhi is a modern, full-stack healthcare platform that bridges the gap between patients, doctors, and healthcare services. It enables users to access online consultations, manage appointments, monitor health records, and access verified health education — all from one secure and user-friendly interface.

---

## 📜 Description

In today’s digital age, healthcare accessibility and management remain major challenges, especially in semi-urban and rural areas. Patients often struggle to connect with verified doctors, maintain medical history, and get timely guidance.  
ArogyaSakhi provides an innovative digital solution by creating a **connected ecosystem for patients and healthcare providers**, promoting preventive care and continuous health monitoring.

---

## 🎯 Main Goal of the Project

The primary goal of **ArogyaSakhi** is to:
- Provide a **digital health companion** that connects patients with doctors online.  
- Offer a **centralized health dashboard** to track health records, prescriptions, and wellness activities.  
- Enable **secure and scalable telemedicine** for remote consultations and healthcare management.  
- Promote **health awareness and education** through an integrated learning module.  

---

## 💡 What Makes It Unique

- **Inclusive Healthcare Access:** Connects rural and urban populations to verified doctors.  
- **Smart Health Tracking:** Monitors patient vitals and progress with interactive dashboards.  
- **AI-Based Recommendations:** (Future Scope) Personalized health insights based on user data.  
- **Community Wellness Support:** Health awareness blogs and educational content.  
- **Doctor & Patient Portals:** Dual-role system for efficient interaction and management.

---

## 🧑‍🤝‍🧑 Target Audience

- **Patients & General Users:** Individuals seeking digital healthcare access.  
- **Doctors & Clinics:** Healthcare professionals offering remote consultations.  
- **Health Organizations:** NGOs or startups focused on digital health initiatives.  
- **Students & Researchers:** Those interested in telemedicine and health informatics systems.

---

## ✨ Key Features and 🖼️ Screenshots

* **User Authentication:** Secure registration and login for both doctors and patients.  
* **Appointment Scheduling:** Book, manage, and cancel online consultations.  
* **Health Dashboard:** Track medical history, prescriptions, and doctor feedback.  
* **Health Education Module:** Access verified articles and preventive health tips.  
* **Doctor Management:** View, approve, and manage doctor profiles and availability.  
* **Responsive UI:** Optimized for desktop, tablet, and mobile devices.  
* **Secure Data Handling:** All health data stored safely with authentication and encryption.


---

## 🛠️ Tech Stack

* **Frontend:** React.js (TypeScript), Tailwind CSS, Axios  
* **Backend:** Node.js, Express.js  
* **Database:** Neon db 
* **Authentication:** JWT-based secure login system  
* **APIs:** RESTful API integration  
* **Version Control:** Git & GitHub  

---

## 🚀 Getting Started

Follow these steps to set up **ArogyaSakhi** locally.

### 🧩 Prerequisites

Make sure you have the following installed:
* Node.js (v18 or later)  
* MongoDB (running locally or MongoDB Atlas)  
* Git  

---

### ⚙️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/SURAJ1430sv/ArogyaSakhi.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ArogyaSakhi
    ```

3. Install dependencies for both client and server:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

4. Set up your environment variables:
    Create a `.env` file inside the **server** folder and add:
    ```
    DATADB_URI=your_db_connection_string
    JWT_SECRET=your_secret_key
    PORT=5000
    ```

5. Start the development servers:
    ```bash
    # Backend
    cd server
    npm start

    # Frontend
    cd ../client
    npm run dev
    ```

6. Open your browser and visit:
    ```
    http://localhost:5173
    ```

---

## 📂 Project Structure

