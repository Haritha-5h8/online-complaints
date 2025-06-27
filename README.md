ResolveNow: Your Platform for Online Complaints Overview

ResolveNow is an online complaint registration and management system designed to streamline how users raise concerns and how organizations respond. It provides a centralized digital platform for complaint tracking, automated resolution processes, and improved transparency and customer satisfaction.

Features

 User Registration & Login
Secure sign-up and login system with role-based access for Users and Admins.

Complaint Submission
Users can easily lodge complaints with detailed information and optional file attachments.

 Complaint Dashboard
Track the status of your complaints in real-time with filtering and search options.

Automated Assignment
Admins can auto-assign or manually delegate complaints to relevant departments or officers.

 Email Notifications
Status updates and responses are communicated via automated emails.

Complaint History & Analytics
Comprehensive reports and visual charts for complaint trends and performance tracking.


Tech Stack

Frontend:

React.js

Tailwind CSS / Bootstrap

Axios


Backend:

Node.js

Express.js

JWT (Authentication)


Database:

MongoDB (Mongoose ORM)


Other:

Nodemailer (Email service)

Cloudinary / Multer (File uploads)

Dashboard | 📑 Complaint Form |  Admin Panel

Setup Instructions

1. Clone the Repository

git clone https://github.com/yourusername/resolve-now.git
cd resolve-now


2. Install Backend Dependencies

cd backend
npm install


3. Install Frontend Dependencies

cd ../frontend
npm install


4. Set up .env Files

Create a .env file in the backend directory with the following:

PORT=5000
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password


5. Run the Application

In two terminals:

# Terminal 1 - Backend
cd backend
npm run dev

# Terminal 2 - Frontend
cd frontend
npm start


6. Access
Visit http://localhost:3000 in your browser.



Roles

User: Can register, file complaints, and track resolution.

Admin: Can view, assign, and respond to complaints.


Future Enhancements

AI-powered complaint classification and prioritization.

Chatbot integration for instant support.

Mobile app (React Native).

Multi-language support.


Contributing

1. Fork the repo.


2. Create your feature branch (git checkout -b feature/YourFeature)


3. Commit your changes (git commit -m 'Add some feature')


4. Push to the branch (git push origin feature/YourFeature)


5. Open a Pull Request.



📄 License

This project is licensed under the MIT License.



