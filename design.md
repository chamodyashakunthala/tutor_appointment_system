Subsystem Design

The system is divided into several subsystems to ensure modularity and ease of maintenance.

🧩 1. User Management Subsystem

Handles student and tutor registration, authentication, and profile management.

Key operations:

Register new users

Login / Logout

Update profile information

View tutor/student details

🧩 2. Tutor Management Subsystem

Manages tutor information such as subjects taught, qualifications, and availability.

Key operations:

Add or update tutor details

Set available time slots
Manage feedback and ratings
3. Appointment Scheduling Subsystem

Handles the entire booking process between students and tutors.

Key operations:

Search tutors by subject or availability

Book, reschedule, or cancel appointments

Notify users of confirmed or changed sessions

🧩 4. Payment Subsystem (optional)

Manages session payments and generates receipts.

Key operations:

Process payments

Generate transaction history

🧩 5. Notification Subsystem

Sends reminders and updates for upcoming sessions or changes.

Key operations:

Email or message notifications for session updates

Workflow Design (System Logic)
🧭 Appointment Booking Flow

Student logs in.

Student searches for a tutor by subject or rating.

System displays a list of available tutors.

Student selects a tutor and available time slot.

System confirms the appointment and updates both dashboards.

Notification subsystem sends confirmation to both tutor and student.

🧭 Tutor Availability Update Flow

Tutor logs in.

Tutor navigates to “Manage Schedule.”

Tutor updates available dates and time slots.

System updates availability table and reflects in student search results.

