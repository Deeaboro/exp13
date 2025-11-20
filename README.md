This project implements a basic user login system using HTML and PHP.
It authenticates users by checking their credentials against the database using secure password verification.

This experiment includes:

✔ HTML login form

✔ PHP script to verify login details

✔ Password validation using password_verify()

✔ Basic session creation to maintain login state

✔ Works with hashed passwords stored during registration

📁 Project Structure
/experiment-3-login/
│
├── login.html           # Login form
├── login.php            # Backend verification script
├── dashboard.php        # Protected page (session required)
├── logout.php           # Destroy session & logout
└── README.md            # Documentation
