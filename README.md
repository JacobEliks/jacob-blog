## My Blog Website
This is a responsive blog website built with Flask and Bootstrap.

# Features

- User Registration: Users can create an account to access additional features.
- User Authentication: Secure user authentication with hashed and salted passwords.
- View Blog Posts: Users can read blog posts on various topics.
- Leave Comments: Users can leave comments on blog posts to engage with the content.
- Contact Form: Users can send messages to the website owner via a contact form.
- Responsive Design: The website is designed to be mobile-friendly and responsive across different devices.

# Installation

1. Clone the repository:
```bash
  git clone https://github.com/JacobEliks/jacob-blog
```
2. Navigate to the project directory:
```bash
  cd blog-website
```
3. Create and activate a virtual environment (optional, but recommended):
```bash
  python3 -m venv venv
  source venv/bin/activate
```
4. Install the required dependencies:
```bash
  pip install -r requirements.txt
```
5. Configure the Database:
Create a SQL database and update the database configuration in the config.py file.
Make sure to set the appropriate values for the database URL, username, password, etc.
6. Run the application:
```bash
  python app.py
```
7. Access the website:
Open your web browser and navigate to http://localhost:5000 to access the blog website.

# Usage
- Create a new account by clicking on the "Register" link on the navigation bar.
- Sign in using your registered credentials.
- Explore the blog posts and leave comments on the ones you find interesting.
- Use the contact form to send messages to the website owner.

# Technologies Used
- Flask: Python web framework used for developing the application.
- Bootstrap: Front-end framework for responsive design and styling.
- SQL Database: The application uses a SQL database for storing user credentials and blog post data.

# Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.
