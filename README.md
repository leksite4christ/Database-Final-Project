# Database-Final-Project
This Student Management System is design to revolutionize educational administration by centralizing data, automating processes, and enhancing communication, resulting in improved efficiency, accuracy, and engagement for all stakeholders.





The Student Management System built using Python and Django for the backend, with HTML, CSS, and JavaScript for the frontend. The system supports three distinct user roles: Admin, Teacher, and Student. Each role has its unique functionalities, providing a robust platform for managing student data, attendance, and fees.
 Project Overview The Student Management System aims to streamline the management of student-related information and administrative tasks. It includes features for user authentication, role-based access control, and data management for students, teachers, and admins.
 Key Features User Roles:
Admin Panel: Manage student and teacher accounts. Approve or disapprove student and teacher applications. View and manage student fees. Post notices accessible to teachers and students. Monitor attendance records.
Teacher Panel: View and manage student attendance. Post notices for students. Access and verify student fees.
Student Panel: Fill out the admission form. Create an account with username and password. View status of application (pending verification). Access notices posted by admin and teachers. View attendance and fee records once verified.
Authentication and Verification: Secure login system with separate panels for Admin, Teacher, and Student. Verification process for new student and teacher registrations by the admin.
Attendance Management: Teachers can mark and manage student attendance. Students and admins can view attendance records.
Fee Management: Admin and teachers can view and manage student fee records. Students can view their fee status.
Notice Board: Admin and teachers can post notices. Students can access notices relevant to them.
 Technologies Used Backend: Python, Django Frontend: HTML, CSS, JavaScript Database: PostgreSQL/MySQL (choose one or mention both if applicable) Tools: Git, VSCode
 Project Structure student_management/: Django project directory. settings.py: Configuration settings. urls.py: URL routing. wsgi.py: Web server gateway interface configuration. app_name/: Main application directory. models.py: Database models. views.py: Application logic and views. templates/: HTML templates. static/: Static files (CSS, JS). forms.py: Form definitions for user input.

