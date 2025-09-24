JobHub
JobHub is a web-based job portal that offers two modes: User and Recruiter. Users can browse, filter, search, and apply for jobs, while recruiters can add, edit, and delete job listings. The platform features login functionality, job filtering, job descriptions, an applications history, and a responsive Bootstrap-based layout.

Features
Login System for Users and Recruiters (hardcoded credentials for recruiters)

Job Listing Dashboard with Bootstrap styling

Advanced Filters: Filter jobs by type, location, and experience level

Search Functionality for job title, company, or location

Job Application: Users can apply and see their application history

Recruiter Section: Add, edit, and delete jobs easily

Dynamic UI: All dashboard elements update live using JavaScript

Responsive Layout for desktops and mobile devices

Getting Started
Prerequisites
A modern web browser (Chrome, Firefox, Edge, etc.)

No server or backend is required (all data is stored in JavaScript variables)

Installation
Clone or download the repository.

Ensure both index.html (the HTML/JS code) and styles.css (the CSS code) are in the same directory.

Usage
Open index.html in your web browser.

Use the Login Page:

Select a role (User or Recruiter).

For Recruiter: use admin / admin as username/password.

For User: any credentials will work.

Explore the dashboard features:

Users can search, filter, see job details, and apply for jobs.

Recruiters can add, edit, or delete jobs with the provided forms.

All UI updates occur instantly; job and application data are session-based.

Code Structure
index.html: Contains HTML layout, UI structure, and embedded JavaScript.

Login page markup.

Dashboard with navbar, sidebar filters, job list, job detail view, and recruiter section.

All logic (login, filtering, CRUD for jobs, apply, render) is handled by JavaScript <script> block at the bottom.

styles.css: Handles custom styles for:

Job card appearance and hover effects.

Body background color and font.

Job details box styling.

Bootstrap is used via CDN for fast, responsive design and default theming.

Customization
Change or expand job filter options by editing checkbox/filter elements in HTML.

Add more jobs or extend job data by modifying the jobs array in JavaScript.

Adapt recruiter credentials or add persistent storage for real-world usage.

License
This project is provided for educational and demonstration purposes. Modify as needed for personal or academic projects.
