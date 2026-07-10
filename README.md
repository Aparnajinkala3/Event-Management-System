# 🎉 Event Management System

A full-stack **Event Management System** built using **Python Flask** and **MySQL** that simplifies event organization, ticket booking, customer management, and administrator operations through a secure web interface.

---

## 📌 Features

### 👤 User Module
- User Registration and Login
- Secure Authentication
- Forgot Password with Email OTP
- Browse Available Events
- Book Event Tickets
- Hall Booking
- View Notifications
- User Dashboard

### 👨‍💼 Admin Module
- Admin Login
- Manage Events
- Manage Customers
- View Bookings
- Send Notifications to Users
- Control Room Dashboard
- Event Status Management

### 🎫 Ticket Management
- Ticket Booking
- Ticket Class Selection
- Payment Details Collection
- Booking Confirmation

### 🏢 Hall Management
- Hall Reservation
- Food Preferences
- Audio/Video Requirements
- Seating Arrangement
- Parking Selection

### 📧 Email Services
- Password Reset via OTP
- Email Notifications
- Reminder Emails

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Backend |
| Flask | Web Framework |
| MySQL | Database |
| PyMySQL | Database Connectivity |
| HTML5 | Frontend |
| CSS3 | Styling |
| JavaScript | Client-side Interaction |
| Bootstrap | Responsive UI |
| Flask-Mail | Email Services |
| dotenv | Environment Variables |

---

## 📂 Project Structure

```
EventManagement/
│
├── templates/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── app.py
├── requirements.txt
├── .env.example
├── README.md
└── database.sql
```

---

## 🚀 Installation

### 1. Clone Repository

```bash
git clone https://github.com/Aparnajinkala3/Event-Management-System.git
```

### 2. Navigate to Project

```bash
cd Event-Management-System
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure Environment Variables

Create a `.env` file:

```env
DB_HOST=your_database_host
DB_PORT=3306
DB_USER=your_username
DB_PASSWORD=your_password
DB_NAME=event_management

MAIL_USERNAME=your_email@gmail.com
MAIL_PASSWORD=your_gmail_app_password
```

### 7. Run the Application

```bash
python app.py
```

Visit:

```
http://127.0.0.1:5000
```

---

## 📊 Database

The project uses **MySQL** with the following primary tables:

- Users
- Customers
- Events
- Tickets
- Notifications
- Halls

---

## 🔒 Security Features

- Environment Variables (.env)
- Session Management
- Email OTP Verification
- Password Recovery
- Secure Database Connection
- Form Validation

---

## 📷 Screenshots

You can add screenshots here:

- Home Page
- Login Page
- Registration Page
- User Dashboard
- Admin Dashboard
- Event Booking
- Hall Booking
- Notifications

---

## 📈 Future Enhancements

- Online Payment Gateway Integration
- QR Code Based Ticket Verification
- Event Analytics Dashboard
- Mobile Application
- SMS Notifications
- Role-Based Access Control
- Cloud Deployment
- AI-based Event Recommendations

---

## 👩‍💻 Author

**Aparna Jinkala**

- GitHub: https://github.com/Aparnajinkala3


---

## 📄 License

This project is developed for **learning and educational purposes**.

