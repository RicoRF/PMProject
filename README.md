# PMProject - Student Engagement Platform

## Project Overview

The PMProject is a web-based application designed to enhance student engagement and foster connections among students and staff. The platform was developed as part of the "PROJ1029 Project Management" course at NBCC Fredericton Campus. This initiative addresses post-pandemic challenges by creating opportunities for interaction through events, resources, and shared interests.

This project was also an exercise in learning how a project is planned, executed, and managed from start to finish. Students applied project management techniques to develop and deliver the platform while gaining practical experience in teamwork and structured workflows.

---

## Features

1. **User Registration and Login**:
   - Secure sign-up and login functionality with user profiles.

2. **Student Engagement Tools**:
   - Browse and participate in student events.
   - Discover resources and services tailored to student needs.

3. **Interactive Features**:
   - Connect with peers based on shared hobbies, languages, and interests.

4. **Database-Driven Design**:
   - Centralized data storage for managing profiles, events, and interactions.

5. **Comprehensive Design**:
   - Focused on accessibility and ease of use for students and staff.

---

## Project Management Practices

The development of this project adhered to the principles and practices taught in the "PROJ1029 Project Management" course, including:

1. **Project Charter**:
   - Defined the scope, objectives, and stakeholders for the project.

2. **Project Plan**:
   - Created a comprehensive plan with the following components:
     - Work Breakdown Structure (WBS)
     - Project Schedule using Gantt Charts
     - Project Resources documented in a RACI Chart
     - Risk Management Plan
     - Communication Management Plan

3. **Project Execution**:
   - Regular status updates using Kanban boards.

4. **Lessons Learned Report**:
   - Documented insights and areas for improvement from the project.

5. **Team Member Evaluations**:
   - Assessed contributions and teamwork at the conclusion of the project.

---

## Technical Details

- **Programming Languages**: HTML, CSS
- **Database**: SQL (script included in `database.sql`)
- **Project Structure**:
  - **HTML Pages**:
    - `index.html`: Main landing page
    - `login.html`: Login page
    - `sign-up.html`: Registration page
    - `events.html`: Events page
    - `resources.html`: Resources and tools
    - `privacy.html` and `terms.html`: Legal information
  - **CSS**: `styles.css` for unified styling across pages
  - **Images and Fonts**: Assets to enhance user experience

---

## Database Design

The database schema is designed to manage student profiles, interests, hobbies, languages, and events efficiently. The ERD (Entity Relationship Diagram) outlines the relationships between tables:

- **`profile`**: Stores user information (ID, first/last name, email, password, etc.)
- **`hobbies`, `hobby`**: Links users to their hobbies
- **`interests`, `interest`**: Links users to their interests
- **`languages`, `language`**: Links users to their spoken languages
- **`events`**: Details of events hosted on the platform
- **`country`, `campus`, `school`, `major`**: Hierarchical data for organizing users and events

![Database Diagram](Database%20Diagram.png)

---

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/RicoRF/PMProject.git
   ```

2. **Set up the database**:
   - Import the `database.sql` file into your SQL server to initialize the database.

3. **Open the application**:
   - Launch `index.html` in a modern web browser to access the platform.

4. **Navigate the platform**:
   - Register and log in to explore events and resources.

---

## Lessons Learned

1. **Project Management**:
   - Gained practical experience in creating a project charter, WBS, Gantt charts, and risk management plans.

2. **Team Collaboration**:
   - Developed effective communication plans and evaluated teamwork dynamics.

3. **Database Design**:
   - Designed a normalized database schema to support dynamic content.

4. **Web Development**:
   - Applied front-end development skills to build an engaging platform.

---

## Future Enhancements

- Add interactive dashboards for event management.
- Implement personalized recommendations based on user profiles.
- Integrate social media sharing for events.
- Extend functionality for staff to manage and approve events.

---

## Project Deliverables

This project adheres to the deliverables outlined in the course, including:

1. Project Charter
2. Project Plan (WBS, Gantt Chart, RACI Chart, Risk Management Plan, Communication Plan)
3. Project Execution and Status Reports
4. Lessons Learned Report
5. Team Member Evaluations


