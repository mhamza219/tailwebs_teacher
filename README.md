
# Teacher Portal

A robust teacher portal built with Ruby on Rails, HTML, and JavaScript. The portal includes a login screen and a home screen for teachers, which serves as the student listing screen. Additionally, it features functionality to manage student listings and add new students.

## Features

- **Login Functionality**:
  - Secure login screen where teachers can input their credentials.
  - User authentication by verifying with a database.
  - Error handling and appropriate feedback for authentication errors.

- **Teacher Portal Home & Student Listing Screen**:
  - Redirects to the home screen after successful login, which serves as the student listing screen.
  - Displays a list of students with their Names, Subject Names, and Marks.
  - Options to edit and delete student details.
  - Inline editing of student details and updates the state accordingly.

- **New Student Entry**:
  - Feature for adding details of a new student using a popup/modal.
  - Checks for existing student with the same name and subject combination.
  - Updates marks for existing students or creates a new student record if no matching record is found.

## Getting Started

### Prerequisites

- Ruby 3.0.0 or higher
- Rails 7.0.0 or higher
- Use nvm 21.6.1
- Sqlite3

### Installation

1. Clone the repository:
   ```sh

   git clone https://github.com/mhamza219/tailwebs_teacher.git
   bundle install
   rails s

   on browser run  "http://localhost:3000/"
