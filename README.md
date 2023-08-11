# Microblog - ongoing project

Microblog is a web application built with Flask, following the esteemed "Flask Mega-Tutorial" by Miguel Grinberg. This project serves as a comprehensive exercise in web application development using Python and Flask.

## Overview

The Microblog platform allows users to:
- Register and manage their user profile.
- Publish text posts.
- Follow and unfollow other users.
- View a personalized feed with posts from users they follow.

## Technologies Used

- **Flask**: A lightweight web framework for Python.
- **SQLAlchemy**: An SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **Jinja2**: A templating engine for Python, used in conjunction with Flask.
- Additional Flask extensions for form handling, authentication, and more.

## Project Structure

- **app/**: The main application package.
    - **templates/**: HTML templates for rendering views.
    - **static/**: Static files like CSS and JS.
    - **routes.py**: Defines the routes that the application implements.
    - **models.py**: Defines the data models.
    - **forms.py**: Defines the form classes.
- **migrations/**: Folder for database migration scripts.
- **config.py**: Configuration settings.
- **microblog.py**: Main application script to start the server.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/microblog.git```
2. Navigate to the Project Directory and Set Up a Virtual Environment:
  `cd microblog`
  `python -m venv venv`
3. Activate the Virtual Environment:
   On macOS and Linux: `source venv/bin/activate`
   On Windows: `.\venv\Scripts\activate`
4. Install the Required Dependencies:
   `pip install -r requirements.txt`
5. Run the Application:
   `pip install -r requirements.txt`
7. Access the App in a Browser:
   Navigate to http://localhost:5000/.

## Future Enhancements

- Add image uploading functionality for user profiles.
- Implement post comments and likes.
- Integrate with third-party authentication providers like Google and Facebook.

## Credits

This project was developed following the [Flask Mega-Tutorial by Miguel Grinberg](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world).

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.

