# Full-Stack-Letter-Editor-with-Google-Drive-Integration
A web application that allows users to authenticate via Google OAuth, create &amp; edit letters, and save them to Google Drive in Google Docs format. Built with React, Flask, MySQL, Firebase Auth, and Google Drive API. Features include draft saving, editing, and retrieval from Google Drive. Fully deployed on Netlify/Vercel &amp; Render/Heroku
Project Overview
This project is a full-stack web application that allows users to:
✅ Sign up & log in using Google OAuth authentication.
✅ Create and edit text-based letters using a rich text editor.
✅ Save drafts in a MySQL database before uploading to Google Drive.
✅ Upload letters to Google Drive in Google Docs format.
✅ Retrieve and view saved letters from Google Drive.

Tech Stack
Frontend: React, React Router, Tailwind CSS

Backend: Flask, Flask-RESTful, Flask-CORS, Flask-JWT-Extended

Database: MySQL (SQLAlchemy ORM)

Authentication: Firebase Auth (Google Sign-In)

Storage API: Google Drive API

Deployment: Frontend on Netlify/Vercel, Backend on Render/Heroku

Installation & Setup
Frontend Setup
sh
Copy
Edit
cd frontend
npm install
npm start
Backend Setup
sh
Copy
Edit
cd backend
pip install -r requirements.txt
python app.py
Environment Variables
Set up a .env file in both frontend and backend directories:

Backend (.env)
ini
Copy
Edit
DATABASE_URL=mysql://username:password@localhost/db_name
SECRET_KEY=your_jwt_secret
FIREBASE_CONFIG=your_firebase_config
GOOGLE_DRIVE_API_KEY=your_google_drive_api_key
Frontend (.env)
ini
Copy
Edit
REACT_APP_FIREBASE_CONFIG=your_firebase_config
REACT_APP_BACKEND_URL=http://localhost:5000
API Endpoints
✅ POST /login - Google OAuth Login
✅ POST /letters - Save draft letter
✅ PUT /letters/:id - Edit letter
✅ GET /letters - Fetch all letters
✅ GET /letters/:id - Fetch a single letter
✅ POST /letters/upload - Upload letter to Google Drive
✅ DELETE /letters/:id - Delete a letter

Deployment
1️⃣ Deploy backend to Render/Heroku
2️⃣ Deploy frontend to Netlify/Vercel
3️⃣ Configure Firebase authentication
4️⃣ Enable Google Drive API & set OAuth permissions
5️⃣ Ensure production .env configurations are set

Future Enhancements
🔹 Add real-time collaborative editing
🔹 Support PDF export for letters
🔹 Improve text formatting options
🔹 Implement user roles & permissions

📌 Contributions & Feedback
Feel free to fork this repository and submit pull requests. Suggestions & feedback are always welcome! 

This description is detailed, structured, and professional, making it easier for others to understand your project. Let me know if you want any modifications! 🚀🔥
Full-Stack Letter Editor with Google Drive Integration
A web application that allows users to authenticate via Google OAuth, create & edit letters, and save them to Google Drive in Google Docs format. Built with React, Flask, MySQL, Firebase Auth, and Google Drive API. Features include draft saving, editing, and retrieval from Google Drive. Fully deployed on Netlify/Vercel & Render/Heroku
