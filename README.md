# README - About Me

## Introduction
Hello! I'm a passionate **Full Stack Developer** currently studying at **YouCode** in **Nador, Morocco**. I'm in my **fourth month** of the program and actively working on multiple projects to enhance my skills.

## Skills & Interests
- **Programming Languages**: PHP (Laravel, OOP, PDO), JavaScript, HTML, CSS, SQL
- **Frontend Frameworks**: React
- **Database Management**: MySQL (secure database handling, queries, optimization)
- **Software Development Concepts**: MVC Architecture, Object-Oriented Programming (OOP)
- **UI/UX Research** (Under the supervision of Hamza Bouchikhi)
- **Mobile Development & Professional Communication** (Veille on both topics)

## Projects & Experience
### 1. **TaskFlow**
   - A task management web application
   - Focused on learning the basics of OOP

### 2. **BlogPress**
   - A blogging platform built with PHP
   - Features include article publishing, performance tracking, user authentication, and statistics visualization

### 3. **Video Game Collection Management Platform**
   - Developed as a **junior backend developer**
   - Built with PHP8 OOP & PDO
   - Worked with **Ahmed** as a teammate
   - SQL Table for games:
     ```sql
     CREATE TABLE Games (
         id INT AUTO_INCREMENT PRIMARY KEY,
         title VARCHAR(100) NOT NULL,
         release_date DATE,
         genre VARCHAR(50),
         description TEXT,
         score FLOAT,
         created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
     );
     ```

### 4. **Trip Planning Platform (Fil Rouge Project)**
   - Parses trip materials and suggests optimal routes
   - Includes hotel booking & social features for travelers

### 5. **Commercial Website for Couple Bracelets**
   - E-commerce platform selling love-themed products

### 6. **Course Enrollment Platform**
   - Built a **Course Enrollment System** with the following SQL schema:
     ```sql
     CREATE TABLE Course_Enrollments (
         id INT AUTO_INCREMENT PRIMARY KEY,
         course_id INT NOT NULL,
         student_id INT NOT NULL,
         FOREIGN KEY (course_id) REFERENCES Courses(id),
         FOREIGN KEY (student_id) REFERENCES Users(id)
     );
     ```

## Other Activities & Contributions
- **Member of the YouCode BDE**
  - Preparing a report on clubs, budgets, and equipment
  - Organized a 10-minute meeting about club regulations
  - Running for a position in the BDE to enhance collaboration between YouCode's Nador, Safi, and Youssoufia campuses
- **Visited Tessi Oujda as part of a YouCode activity**
- **Started working on Fiverr**

## Design & Preferences
- **UI/UX Preferences**:
  - Enhanced console designs with **formatted printf output**
  - Aesthetic menus for better user experience
- **Preferred Colors**: `#80ff00` (green) and `#a8a8a8` (gray)
- **Logo Design**: Created a logo for **GymBro**
- **Illustration**: Working on an artistic minimalist design of a couple in love, featuring a simple background with red, black, and white accents

## Looking for an Internship
I'm actively searching for a **Full Stack Developer internship** to further develop my skills and gain real-world experience in web development.

---
## Contact & Socials
- **Location**: Nador, Morocco
- **Languages**: Prefers explanations in Arabic but technical terms in English
- **Preferred Communication**: English
