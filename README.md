# Apna.co Clone – Job Portal Web Application

## 📝 Overview
This project is a working clone of the [Apna.co](https://apna.co) job portal, created as part of an internship assignment. It replicates core features like user login, profile creation, contact form submission, and backend integration using **HTML**, **CSS**, **JavaScript**, **PHP**, and **MySQL**. The frontend design closely follows the UI of Apna.co, ensuring a smooth and intuitive user experience.

---

## 📦 Modules & Features

### 1. 🔐 Login Module
- **Files:** `index.html`, `index.php`, `Emp_login.html`
- **Description:** Allows users to input their mobile number for login.
- **Features:**
  - OTP-style UI input (simulated).
  - Client-side form validation.
  - Redirect to the profile page upon successful login.

### 2. 👤 Profile Module
- **File:** `profile.php`
- **Description:** Captures user’s basic profile details.
- **Features:**
  - Input fields: Name, Date of Birth, Gender, Email.
  - Optional checkbox for WhatsApp job updates.
  - Saves data to the `basic_details` table in MySQL.
  - Displays a popup message and redirects to the homepage on success.

### 3. 📨 Contact Module
- **Files:** `contactUs.html`, `contact.php`
- **Description:** Handles employer inquiries through a contact form.
- **Features:**
  - Input fields: Full Name, Work Email, Mobile Number, Role, Company Name, Company Size.
  - Form submits data to `contact.php` and stores it in `contact_details`.
  - Displays a success alert via JavaScript.

### 4. 🗃️ Database Module
- **File:** `project.sql`
- **Tables:**
  - `basic_details`: Stores jobseeker profiles.
  - `contact_page`: Duplicate table for testing/demo.
  - `contact_details`: Stores contact form submissions.
- **Functionality:** Tables use `AUTO_INCREMENT` for ID and `TIMESTAMP` for logging.

### 5. 🧑‍💼 Employee Login (Dummy UI)
- **File:** `Emp_login.html`
- **Description:** Static login page for employees.
- **Note:** UI only, no backend functionality.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML**   | Web page structure |
| **CSS**    | Styling and layout |
| **JavaScript** | Client-side interactivity, alerts, redirects |
| **PHP**    | Server-side form processing |
| **MySQL**  | Backend database management |
| **XAMPP**  | Local development stack (Apache, MySQL, PHP) |

---

## 💻 Running the Project Locally

1. Start **Apache** and **MySQL** using **XAMPP**.
2. Place the `internship` folder inside the `htdocs` directory.
3. Import the `project.sql` file into **phpMyAdmin** under a new database called `assignment`.
4. Open your browser and navigate to: http://localhost/internship/assignment_of_apna.co_clone/index.html


---

## 🎨 UI Highlights

- Pixel-perfect layout modeled after Apna.co's interface.
- Responsive design elements.
- Clean and user-friendly input forms.

---

## 🚀 Future Scope & Improvements

- Implement **real OTP verification** for secure login.
- Add **user authentication** and session management.
- Develop an **admin dashboard** to view all submissions.
- Enhance responsiveness and add mobile-first UI optimizations.

---

## 📁 Folder Structure (Overview)

internship/ 
├── index.html 
├── index.php 
├── Emp_login.html 
├── profile.php 
├── contactUs.html 
├── contact.php 
├── images/ 
├── css/ 
├── js/ 
└── project.sql

---

## 📌 Note
- The PHP scripts are designed to run on **localhost** only.
- Make sure all form inputs have `name` attributes for successful data processing in PHP.
