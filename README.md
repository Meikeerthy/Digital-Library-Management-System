Digital Library Management System (DLMS)

Overview
The Digital Library Management System (DLMS) is a web-based platform that allows users to explore and manage digital books and resources efficiently. It provides functionalities for users to browse, reserve, and access books while also offering an **Admin Portal** for managing the system.

Features
User Features:
- User Registration & Login: Secure authentication for users.
- Browse & Search Books: Easily search for available books in the catalog.
- Book Reservation System: Reserve books and get notified when they become available.
- User Dashboard: Track borrowed books and reservations.
- Logout Functionality: Secure session management.

Admin Features:
- Admin Login: Secure access to the admin portal.
- Manage Books: Add, edit, and remove books from the catalog.
- User Management: View and manage registered users.
- Reservation Handling: Approve or deny book reservations.

Installation & Setup
Prerequisites:
- A web browser (Chrome, Firefox, Edge, etc.)
- Local web server (XAMPP, WAMP, or live web hosting)
- Basic knowledge of HTML, CSS, and JavaScript

Steps to Run Locally:
1. Download the Project
   - Clone the repository or download the project files.
   ```sh
   git clone https://github.com/your-repo/DLMS.git
   ```

2. Open in Browser
   - Navigate to the `index.html` file and open it in a browser.

3. Ensure Local Storage is Enabled
   - The project uses `localStorage` for authentication.

File Structure
```
DLMS/
│-- index.html           # Home page
│-- catalog.html         # Book catalog
│-- login.html           # User login page
│-- signup.html          # User registration page
│-- adminlogin.html      # Admin login page
│-- js/
│   ├── script.js        # JavaScript for authentication
│-- css/
│   ├── styles.css       # Main stylesheet
│-- images/              # Contains images
│-- README.md            # Documentation
```

Technologies Used
- Frontend: HTML, CSS, JavaScript, jQuery
- Data Storage: LocalStorage (for demo purposes, can be replaced with a database)

Usage
- Users must sign up and log in to access the catalog and reserve books.
- The "Click here for login" link disappears after login.
- Admins can manage books and users through the **Admin Portal**.

Future Improvements
- Implement a backend with a database for persistent storage.
- Add email notifications for book availability.
- Improve UI/UX design.

License
This project is licensed under the MIT License.

---
Author: Meikeerthy Lakshmanan  
Project Repository: [GitHub Link](https://github.com/your-repo/DLMS)

