
# Educational Platform for Studying Abroad

## Description
This project is an **educational platform** designed to help students apply for bachelor's degree programs in various foreign countries. The platform provides comprehensive guides and courses for the application process, offering step-by-step instructions for students who wish to study abroad.

## User Roles

- **Admin User**: Users with an `id = 1` are designated as admin users. Admins have full access to the platform's **CRUD (Create, Read, Update, Delete)** capabilities, allowing them to manage courses, universities, and other content. Admin users can see additional buttons for editing or deleting courses and other resources that regular users cannot access.

- **Regular User**: Regular users can register, browse courses, and access the content they have purchased. They do not have access to admin features.

## Accessing Courses with a Course Code

Each course on the platform is associated with a unique course code. For example, if a user enters the course code `240290`, they will be directed to one of the courses available on the platform. This system helps users easily navigate to the correct course by entering the code associated with it. 

### How to Use the Course Code:
1. Log in with your credentials.
2. Enter the course code (e.g., `240290`) to access the corresponding course page.


### Key Features
- **Country-Specific Guides**: Detailed guides explaining the application process for different countries (e.g., Poland).
- **Course Registration & Payment**: Users can purchase courses/guides and register to access the information.
- **User Login**: Secure login system where users can sign in using their name, email, and course code.
- **Mentor Support**: Students can seek assistance from mentors when needed.
- **Admin Control**: Admin users have full CRUD (Create, Read, Update, Delete) capabilities to manage universities, courses, and content.

### Technologies Used
- **Backend**: Flask, Flask-SQLAlchemy, Flask-Login (Python)
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Forms**: Flask-WTF, WTForms
- **Database**: SQLAlchemy
- **Text Editor**: Flask-CKEditor
- **Security**: Werkzeug for password hashing
- **Web Scraping/Validation**: Bleach and MarkupSaf

### Installation
Ensure you have **Python** installed on your system.

### Requirement
To install the dependencies listed in the requirements.txt file, use the following command: 
`pip install -r requirements.txt`

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/project-name.git
   cd project-name

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the app:
   ```bash
   flask --app main run
   
4. Create a .env file and add the following environment variables:
   ```bash
   SECRET_KEY=your_secret_key
   DATABASE_URL=your_database_url








