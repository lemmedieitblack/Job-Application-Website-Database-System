Project Overview
This project implements a comprehensive job portal database system using PostgreSQL and PL/pgSQL. The system facilitates interactions between job seekers, recruiters, and administrators, providing functionalities for user registration, job posting, application management, interview scheduling, notifications, and reporting.

Key Features
User Management (Q1)
Job Seekers can:

Register and create profiles with personal details, skills, and CVs

View, update, or delete their profiles (with cascading deletions)

Manage skill proficiencies (beginner, intermediate, advanced, expert)

Recruiters can:

Register company profiles with detailed information

View and update company details

Admins can:

Manage job listings (approve, suspend, or delete)

Job Listings (Q2)
Recruiters can post, update, and manage job listings

System automatically closes expired job postings

Job seekers can search and filter jobs by multiple criteria

Bookmark functionality for saving interesting jobs

Applications & Interviews (Q3)
Job seekers can:

Submit, view status of, and withdraw applications

Recruiters can:

Filter applications by skills and experience

Schedule interviews

Update application statuses (hired/rejected)

Notifications (Q4)
Automated notifications for:

Interview invitations

Application status changes

Job posting updates

Reporting (Q5)
Top applicant identification by:

Total experience

Number of skills

Prior hiring success

Most in-demand skills analysis

Time-based reporting (weekly, monthly, quarterly) on:

Job postings

Hires

Job seeker application tracking

Data Consistency (Q6)
Cascading deletions for related data

Notification system for job updates


Technical Implementation
PostgreSQL with PL/pgSQL for stored procedures and triggers

Normalized database schema with proper foreign key relationships

Dynamic search and filtering capabilities

Automated notification system using triggers

Comprehensive reporting functions with DATE_TRUNC for time-based grouping


Database Schema (ERD)
Note: The ERD diagram was not provided in the uploaded files, but the system includes tables for:

Users (Job_Seeker, Company/Recruiter)

Skills and skill associations

Job listings

Applications

Interviews

Notifications

Bookmarks

Work history


Setup Instructions
Create a PostgreSQL database

Execute the schema creation scripts (not provided in these files)

Load the provided SQL functions and triggers (q1.sql through q6.sql)

Populate with test data as needed


Team Learnings
As noted in Report.pdf, this project provided valuable experience in:

PostgreSQL function and trigger creation

Database schema design and normalization

Implementing complex business logic in SQL

Building automated notification systems

Developing dynamic search functionalities

The team gained practical skills in database management and applied classroom knowledge to a real-world scenario.
