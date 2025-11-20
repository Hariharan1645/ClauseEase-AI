📘 ClauseEase AI – Contract Language Simplifier

ClauseEase AI is an AI-powered web application designed to simplify legal contracts, making them more understandable for students, businesses, and non-legal users.
It extracts key legal terms, detects clause types, highlights complex terminology, and produces simplified versions using multiple levels of explanation.

🚀 Features
✅ 1. Contract Upload & Text Extraction
Upload PDF, DOCX, or TXT files
Or directly paste contract text
Automatically extracts the content

✅ 2. AI-Powered Simplification
Choose simplification level:
Basic
Intermediate
Advanced
Generates easy-to-understand text using NLP & rule-based simplification.

✅ 3. Legal Term Detection
Uses a custom glossary database
Admin can add / edit / delete glossary terms
Automatically highlights legal jargon with definitions

✅ 4. Clause Detection (Legal-BERT Style)
Identifies clause types such as:
Indemnity
Confidentiality
Termination
Jurisdiction
Breach
Force Majeure
…and more.

✅ 5. Named Entity Recognition

Identifies:
Parties
Organizations
Dates
Locations
Monetary amounts

✅ 6. User System
Register / Login
Profile page
Upload history saved per user
Admin dashboard

✅ 7. Upload History & Downloads
Users can view past uploads
Preview simplified text
Download simplified files

✅ 8. Modern UI Enhancements
Glow cursor interaction
Loading overlay
Fake progress bar
Responsive layout (60/40 split display)

📁 Project Structure
ClauseEaseAI/
│
├── instance/
│   └── users.db
│
├── static/
│   ├── mouse-glow.js
│   └── style.css
│
├── templates/
│   ├── admin_glossary_add.html
│   ├── admin_glossary_edit.html
│   ├── admin_glossary.html
│   ├── admin.html
│   ├── base.html
│   ├── glossary.html
│   ├── home.html
│   ├── login.html
│   ├── profile.html
│   ├── register.html
│   ├── simplify.html
│   └── uploads.html
│
├── app.py
├── requirements.txt
├── Dockerfile
└── docker-compose.yml

🛠 Tech Stack

Backend
Flask
Flask-SQLAlchemy
Python (NLP processing)
transformers
spaCy
PyPDF2 / PyMuPDF
python-docx

Frontend
HTML5, CSS3
JavaScript
Custom UI components
DevOps
Docker
Docker Compose
Gunicorn

🐳 Running with Docker
1️⃣ Build Image
docker-compose build --no-cache

2️⃣ Run Container
docker-compose up

3️⃣ Access App
http://localhost:5000

⭐ Contribute

Pull requests are welcome!
If you find bugs or want new features, open an issue 😊

📄 License

MIT License – free to use and modify.
