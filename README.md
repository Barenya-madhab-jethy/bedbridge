🏥 BedBridge – README (Short Version)
📋 Project Overview
BedBridge is a real-time hospital bed availability system that helps patients find ICU, oxygen, ventilator, and general beds instantly during emergencies.

🚀 Quick Start
Prerequisites
Python 3.9+

Web browser

Installation (2 Minutes)
bash
# 1. Clone or download project
git clone https://github.com/yourusername/bedbridge.git
cd bedbridge

# 2. Install Python dependencies
pip install flask flask-cors flask-sqlalchemy

# 3. Run backend
cd backend
python app.py

# 4. Open index.html in browser
# That's it! 🎉
Demo Credentials
text
Hospital Login: city123 / pass123
Emergency Mode: Click red button
✨ Key Features
Feature	Description
🚨 Emergency Mode	One-tap find nearest ICU
🏥 Live Bed Tracking	Real-time availability updates
📍 Smart Navigation	Direct hospital routing
📊 Admin Dashboard	Easy bed management
📱 Mobile Ready	Works on all devices
🛠️ Tech Stack
text
Frontend: HTML5, CSS3, JavaScript, Font Awesome
Backend: Python, Flask, SQLAlchemy
Database: SQLite/MySQL/PostgreSQL
APIs: Google Maps, Twilio (optional)
📁 Project Structure
bedbridge/
│
├── index.html                    # Main landing page
├── emergency.html                # Emergency quick access mode
├── search.html                   # Hospital search results page
│
├── css/
│   ├── style.css                 # Main stylesheet
│   ├── animations.css            # CSS animations library
│   └── responsive.css            # Mobile responsiveness
│
├── js/
│   ├── main.js                   # Core JavaScript functionality
│   ├── emergency.js              # Emergency mode logic
│   └── animations.js             # Animation controllers
│
├── assets/
│   ├── logo.svg                   # BedBridge logo
│   └── icons/                     # UI icons set
│
├── admin/
│   ├── login.html                 # Hospital admin login
│   └── dashboard.html             # Bed management dashboard
│
└── backend/                        # Python/SQL backend
    ├── app.py                      # Flask/FastAPI main app
    └── database.sql                # SQL database schema

🎯 How to Use
For Patients:
Open website

Enter location

Find nearest hospital with beds

Click "Emergency" for instant help

For Hospitals:
Login at /admin/login.html

Update bed availability

Changes go live instantly

🌐 API Endpoints
text
GET    /api/hospitals           # List all hospitals
GET    /api/hospitals/nearby    # Find nearby hospitals
PUT    /api/hospitals/:id/beds  # Update bed count
POST   /api/emergency           # Emergency request
🤝 Contributing
Fork project

Create branch (git checkout -b feature/AmazingFeature)

Commit (git commit -m 'Add feature')

Push (git push origin feature/AmazingFeature)

Open Pull Request

📄 License
MIT License - Free for personal and commercial use

📞 Support
Email: support@bedbridge.com

Demo: city123 / pass123

Docs: See code comments
