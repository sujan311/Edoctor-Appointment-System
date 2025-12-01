Edoctor-Appointment-System

A simple web-based Doctor Appointment Booking System built with PHP, MySQL, HTML/CSS — supporting three user roles (Admin, Doctor, Patient) to manage appointment scheduling, user accounts and doctor-patient interactions.

🎯 Purpose & Overview

Edoctor-Appointment-System allows:

Patients to browse doctors, create accounts, and book appointments online.

Doctors to view their scheduled appointments and manage their profile/account.

Admin to manage doctors (add/edit/delete), manage doctor availability/sessions, and view patient booking data.

The system helps clinics/hospitals manage appointments digitally — reducing manual scheduling, improving organization, and providing convenient booking for patients. This approach reflects what typical doctor-appointment web systems aim to provide. 
SourceCodester
+2
GitHub
+2

✅ Features

User roles: Admin, Doctor, Patient.

User authentication & account management (login, signup, logout, profile settings).

Doctor management (Admin): Add/edit/delete doctors with specialty, contact, credentials.

Doctor availability scheduling (Admin): Create sessions/slots for doctors; remove or modify sessions.

Patient functionality: Sign up / login; browse doctors; view available sessions; book appointments.

Doctor functionality: View upcoming appointments, patient details, account settings.

Admin functionality: View all patients, bookings, doctor schedules; manage doctor database and sessions.

🗂️ Project Structure
/
├── admin/             # Admin-side pages
├── doctor/            # Doctor-side pages
├── patient/           # Patient-side pages
├── css/               # Stylesheets
├── img/               # Images / assets
├── connection.php     # DB connection setup
├── create-account.php # User registration
├── login.php          # Login page
├── logout.php         # Logout logic
├── signup.php         # Signup logic
├── SQL_Database_edoc.sql  # Database schema / seed data
└── ...                # Other PHP files for functionality

📥 Installation & Setup (Local)

Make sure you have a local web server setup (e.g. XAMPP, WAMP) with PHP and MySQL support.

Clone this repository:

git clone https://github.com/sujan311/Edoctor-Appointment-System.git


Copy the project folder into your server’s document root (e.g. htdocs for XAMPP).

Open your web-server’s control panel (start Apache + MySQL).

Open phpMyAdmin and create a new database (e.g. edoc).

Import the SQL_Database_edoc.sql file to set up the necessary tables & sample data.

Access the application via browser (e.g. http://localhost/your-folder-name/).

Use the signup/login pages to start as Admin / Doctor / Patient.

🧑‍💻 How to Use

As Admin: log in → manage doctors (add/edit/delete), manage doctor sessions, view bookings & patient details.

As Doctor: log in → view your scheduled appointments, patient info, adjust your profile/account.

As Patient: sign up → browse doctors → check their availability → book appointment → view bookings / history.

⚠️ Notes & Limitations

This is a basic appointment system, without advanced features like notifications, email reminders, or payment integration.

Security and validation are minimal — for production use, you’d need to add input sanitization, session-handling, secure authentication, and possibly HTTPS support.

There is no support for rescheduling or cancelling appointments (unless you add those flows manually).

The UI and layout are minimal — you may want to improve styling for better UX.

💡 Potential Future Enhancements

Add appointment notifications / email reminders.

Enable appointment cancellation / rescheduling by patients and doctors.

Add search/filter doctors by specialty, availability, location etc.

Improve UI/UX (responsive design, better CSS, maybe a frontend framework).

Add role-based access control, more robust authentication & security.

Add audit logs, appointment history, doctor/patient profile pages with more data.
