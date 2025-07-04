# 📌**Placement Management System**
#
An online Placement Portal developed specifically for BVRIT students and the Placement Cell, aimed at efficiently managing and analyzing student placement data.
#

### 📌 Project Features

- 👤 Student Registration & Login
- 📝 Profile Creation and Resume Generation
- 📊 Placement Data Analysis (e.g., CSE, IT)
- 📤 Internship & Job Tracking
- 🧾 Request Forms for Opportunities
- 🏢 Company Listings and Updates
- 📈 Admin & Student Views
- 🎨 Responsive UI with CSS and JavaScript

---

### 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL (XAMPP)
- **Server**: Apache (XAMPP)

---

### 📷 Images

 🧑‍🎓 Create Account

<img src="https://github.com/SANDIRIAMULYA/placementmanagement-website/blob/e46d08cf69b871f9d1be3c61dbfeaf5bca604b27/Screenshot%202024-06-12%20214803.png?raw=true" width="500"/>

---

 🏠 Home Page

<img src="https://github.com/SANDIRIAMULYA/placementmanagement-website/blob/e46d08cf69b871f9d1be3c61dbfeaf5bca604b27/Screenshot%202024-06-12%20215924.png?raw=true" width="500"/>

---

 📊 Placement Analysis

<img src="https://github.com/SANDIRIAMULYA/placementmanagement-website/blob/e46d08cf69b871f9d1be3c61dbfeaf5bca604b27/Screenshot%202024-06-12%20220204.png?raw=true" width="500"/>

---



### 📁 Folder Structure (Main Files)

* wadproject/
* │
* ├── Ahome.php # Admin home page
* ├── Alogin.php # Admin login page
* ├── Analysis.php # Placement analysis (graphical view)
* ├── Analysis.js # Chart logic for placement graphs
* ├── Arequest.php # Admin interface to view student requests
* ├── Aresult.php # Admin result view
* ├── Asubmit.php # Admin form submission handler
* ├── backgrd.jpeg # Background image
* ├── company.php # Company details (admin)
* ├── Scompany.php # Company details (student)
* ├── generate-resume.php # Resume generator
* ├── home.php # Student home page
* ├── login.php # Student login page
* ├── register.php # Student registration page
* ├── resume.php # Resume view or editing
* ├── resume_builder.php # Resume building functionality
* ├── select.php # Course/option selector
* ├── sprofile.php # Student profile page
* ├── submit.php # Student submission page
* ├── request.php # Student request form
* ├── submit_request.php # Handles student request submission
* ├── test.php # Test functionality
* ├── update.php # Update handler
* ├── update1.php # Alternative update handler
* ├── update_request.php # Admin request update handler
* ├── view_image.php # View uploaded images
* ├── welcome.php # Welcome/landing page


---

### 🧑‍💻 How to Run

1. **Install XAMPP**  
   Download and install [XAMPP](https://www.apachefriends.org/).

2. **Move Project Folder**  
   Copy `wadproject` into xampp->htdocs

3. **Start Apache and MySQL**  
Launch XAMPP Control Panel → Start both **Apache** and **MySQL**.

4. **Create the Database**
- Visit: `http://localhost/phpmyadmin/`
- Create a new database (e.g., `placement_db`)
- Import your `.sql` file with tables and data (you can export from your original database if needed).

5. **Run the Application**
Open your browser and go to `http://localhost/welcome.php/`

