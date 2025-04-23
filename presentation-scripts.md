# University Magazine Portal Presentation Script

## 1. Introduction

Greetings, I'm Yan Wai Pan, and I'm here on behalf of our team - (group name) to present our group coursework project — the University Magazine Portal. It's a secure, responsive, and role-based web platform that streamlines the process of collecting, reviewing, and publishing student contributions for our university's annual magazine. We built this using agile scrum methodology, and I'll walk you through the key features and roles we implemented.

_Alternative Introduction:_

Greetings, my name is Yan Wai Pan. I'm representing our team to share our group coursework project which is the University Magazine Portal. It functions as a protected web system which offers users a convenient way to manage student submissions before magazine publication. The project was developed using agile scrum methodology and I will explain its essential features together with implemented roles.

## 2. Roles Overview

Our system supports five distinct roles:

- Student – who submits articles and images.
- Faculty Marketing Coordinator – who manages contribution within their faculty.
- University Marketing Manager – who can see all selected contributions.
- Administrator – who configures system settings such as submission deadlines and t&c.
- Guest Viewers – who can view selected contributions by faculty

Each role has its own access level, with permissions that match their tasks.

## 3. Features Demo with Screencast

### 3.1. Student Role

#### Login Page

- **Screen**: Login screen
- **Demo**: Form validation, login error message, actual login
- **Script**: Let's start with the student login. If incorrect details are entered, the system shows an error message. Once the correct email and password are provided, the student is successfully logged in.

#### All Contributions View

- **Screen**: All contribution
- **Demo**: Contributions view, contribution details view
- **Script**: Here, the student can view all the selected contributions of his faculty (mention faculty name). They can also click on each item to see more detailed information.

#### New Contribution Form

- **Screen**: New contribution
- **Demo**: Form validation, terms & condition, create contribution
- **Script**: To submit a new contribution, the student must first fill all the required fields. If any required field is left empty, the form shows a warning. After filling in everything correctly, the student must accept terms and conditions. Once submitted, the system automatically sends a notification email to the faculty's marketing coordinator.

#### My Contributions Page

- **Screen**: My contribution
- **Demo**: Contributions view, contribution details view, comment view, comment validation (student cannot start comment session), actual comment
- **Script**: On this page, students can view all their own submissions along with any comments from the coordinator. Students are not allowed to start the comment thread — if they try, the system prevents it. But once the coordinator adds a comment, the student can reply.

### 3.2. Marketing Coordinator Role

#### Login Interface

- **Screen**: Login screen
- **Demo**: Login
- **Script**: I'm logging in as a marketing coordinator, who can manages submitted contribution for his faculty.

#### Contributions Management

- **Screen**: All contribution
- **Demo**: Filters, pagination
- **Script**: The coordinator can see all submissions from students in their faculty. They can use filters and pagination to search or organize the list more easily.

#### Contribution Review

- **Screen**: Contribution details
- **Demo**: Comment, select, reject (and updated view)
- **Script**: On this page, the coordinator can read the article, leave a comment for the student, and either select the contribution for publication or reject it. The status updates immediately after taking action.

#### Analytics Dashboard

- **Screen**: Data insight
- **Demo**: Total Number of Contributions View, Total Number of Contributions View and Contributors in each Academic Year Chart View
- **Script**: In the Data Insight section, we can see statistics such as the total number of contributions, as well as visual charts showing contributions and contributors by academic year.

#### Reports Section

- **Screen**: Visual data reports
- **Demo**: View Contributions without a comment, Contributions without a comment after 14 days, filters, contribution details, download CSV
- **Script**: This page provides more advanced reports. For example, it shows which contributions don't have any comments, or which ones were not commented on within 14 days. Coordinators can filter the results, view submission details, and download the data as a CSV file.

#### Guest Management

- **Screen**: Guest reports 
- **Demo**: Login information view, filters, pagination
- **Script**: Coordinators can also view guest login records. These can be filtered and browsed using the same pagination system.

### 3.3. Marketing Manager

#### System Access

- **Screen**: Login
- **Demo**: Login
- **Script**: Now we'll log in as the University Marketing Manager, who can see all selected contributions.

#### Selected Contributions

- **Screen**: All select contributions
- **Demo**: Contributions view, filters, contribution details view, Download Zip
- **Script**: The manager can browse through selected contributions across all faculties, apply filters, and open each one to view more details. However, they cannot make any changes to the contributions content.

#### File Management

- **Screen**: File manager
- **Demo**: Unzip the downloaded file, files views
- **Script**: The manager can download all selected contributions as a ZIP file and here is the downloaded files as we see.

#### Contribution Analytics

- **Screen**: Contributions report
- **Demo**: Contributions chart view
- **Script**: This chart shows the percent of selected contributions from each faculty over time.

#### Contributor Statistics

- **Screen**: Contributors report
- **Demo**: Contributors chart view
- **Script**: And this one displays how many individual students contributed each year in percent, grouped by faculty.

### 3.4. Admin

#### User Administration

- **Screen**: User management
- **Demo**: Filters, paginations, export csv
- **Script**: Now let's look at the admin dashboard. In the User Management page, admins can filter users, use pagination, and export the list as a CSV file.

#### User Registration

- **Screen**: New user registration
- **Demo**: Form validation, password generation, create new user, show updated view
- **Script**: Admins can add new users through this form. If something is missing, it shows a warning. We can also generate secured password here. Once complete, the new user appears in the list.

#### User Profile Management

- **Screen**: Edit user registration
- **Demo**: Edit user, show updated view
- **Script**: Admins can see the user information details or update user information. Changes are reflected immediately after saving.

#### Academic Year Control

- **Screen**: Academic year
- **Demo**: Filters, paginations, export csv
- **Script**: In the Academic Year section, they can manage records using filters and export tools, just like in user management.

#### Academic Year Setup

- **Screen**: New academic year registration
- **Demo**: Form validation, create new academic year, show updated view
- **Script**: Admins can register a new academic year. The form checks all fields before saving.

#### Academic Year Maintenance

- **Screen**: Edit academic year & academic year
- **Demo**: Edit new academic year, show updated view, delete academic year, show updated view
- **Script**: In this page, details of academic year can be viewd. Admin can also update or delete existing academic years. Any changes appear right away.

#### Faculty Administration

- **Screen**: Faculty management, new faculty year registration & edit faculty year
- **Demo**: Filters, pagination, export CSV, navigate to create page, form validation, create new faculty year, show updated view, navigate to edit page, edit new faculty year, show updated view
- **Script**: Similar features are available for managing faculties — including filtering, adding, viewing details, editing, and deleting entries.

#### Faculty Management

- **Screen**: Faculty management
- **Demo**: Delete faculty, show updated view
- **Script**: XXXX

#### Terms Management

- **Screen**: Edit Terms & Conditions
- **Demo**: Edit terms & conditions
- **Script**: Admins can also update the Terms and Conditions which all students must agree to before submitting.

#### System Analytics

- **Screen**: Reports
- **Demo**: Most viewed pages view, most active user view, most used browser chart view, filters
- **Script**: In this final section, we can see system analytics — such as the most visited pages, most active users, and most popular browsers used. Filters help customize the data shown.

### 3.5. Guest

#### Registration Process

- **Screen**: Registration
- **Demo**: Form validation, register
- **Script**: Guests can register to view selected contributions of their preferred faculty. During registration, the system checks the form for missing information. 

#### Authentication

- **Screen**: Login
- **Demo**: Login
- **Script**: After registration, guests can log in using their credentials.

#### Content Access

- **Screen**: Contributions
- **Demo**: Contributions view, contribution details view
- **Script**: Guests can browse published contributions and open each one to read it in detail.

### Notes

- Filters include academic filter in the header
- Too many form validations' demos (duplicated)
- Too many filters & paginations (duplicated)

### Not included features

- Emails
- Alert dialog when users navigate in forms filling page

## 4. Conclusion

Our team worked collaboratively using agile scrum, with defined sprints, user stories, and regular meetings. We maintained documentation which covered our testing phase and our design choices as well as our backlog items. The completed system provides device accessibility and role-based capabilities for large institutions to use.

Thank you for your time — we believe this system represents a worthy management solution for student publications that scales effectively.
