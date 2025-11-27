# 🌿 EcoRewards
### *Turn Your E-Waste Into Rewards*

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JS-yellow?style=flat-square">
  <img src="https://img.shields.io/badge/Backend-Node.js%20%7C%20Express-orange?style=flat-square">
</p>

EcoRewards is a web platform designed to promote **responsible e-waste recycling**.  
Users can submit e-waste, schedule pickups, earn reward points, and redeem them — all through a simple, eco-themed interface.

---

## 📑 Table of Contents

- Features  
- Project Structure  
- Tech Stack  
- Setup Instructions  
- API Overview  
- Contributing  
- License  

---

## ✨ Features

### 🔐 User Features
- Signup, Login & Authentication  
- Profile with Base64 image upload  
- Points Dashboard  
- Redeem rewards instantly  
- Smooth green-themed UI  

### 🚚 E-Waste Management
- Submit disposal / drop-off requests  
- Schedule pickup requests  
- Track pickup & disposal history  
- View nearby recycling centres  

### 🛠 Backend Features
- JSON-based storage (`users.json`, `centres.json`, `pickups.json`)  
- Reward redemption tracking  
- Express-based secure routing  

---

## 📁 Project Structure



    EcoRewards/
    │── index.html
    │── loginpage.html
    │── signuppage.html
    │── profilepage.html
    │── education.html
    │── otp.html
    │── rewards.html
    │── pickups.html
    │── centres.html
    │
    ├── css/
    │ ├── style.css
    │ ├── loginpage.css
    │ ├── profilepage.css
    │ ├── education.css
    │ └── rewards.css
    │
    ├── js/
    │ ├── script.js
    │ ├── profilepage.js
    │ └── server.js
    │
    ├── users.json
    ├── centres.json
    ├── pickups.json
    └── images/


---

## ⚙️ Tech Stack

### Frontend  
- HTML5  
- CSS3  
- JavaScript  

### Backend  
- Node.js  
- Express.js  
- JSON-based storage (extendable to DB)

---

## 🚀 Setup Instructions

### 1️⃣ Clone the repository
    ```bash
    git clone https://github.com/Rohan200511/EcoRewards.git
    cd EcoRewards
    
    2️⃣ Install dependencies
    npm install
    
    3️⃣ Start the server
    node server.js
    
    4️⃣ Visit the app
    http://localhost:3000

🔌 API Overview

    Method	Endpoint	Description
    POST	/signup	Register new user
    POST	/login	Authenticate user
    POST	/updateProfile	Update user info & profile picture
    POST	/redeem	Redeem reward points
    GET	/centres	Get recycling centres
    POST	/pickup	Schedule pickup
🤝 Contributing

Contributions, issues, and feature requests are welcome.
Feel free to fork the repo and submit a pull request.

📄 License

Released under the MIT License.
