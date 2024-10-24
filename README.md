Blog Website

This project is a dynamic blog website that allows users to create, edit, and delete blog posts. It also features a user authentication system and offers a smooth, user-friendly interface for blogging.
Table of Contents

Features [here](#features) 
Technologies
Installation
Usage
Screenshots
Contributing

Features

    User Authentication: Users can register, log in, and log out securely.
    Create Posts: Authenticated users can write blog posts.
    Edit and Delete Posts: Users can update or remove their own posts.
    Commenting System: Users can comment on posts.
    Responsive Design: The site is mobile-friendly and works well across various devices.
    Rich Text Editor: Posts can be created using a rich text editor to enhance content formatting.

#Technologies

    Backend: Python, Flask
    Frontend: HTML, CSS, Bootstrap
    Database: SQLite (Migrated to PostgreSQL for live website)
    Others: SQLAlchemy (for ORM)

Installation

To run this project locally, follow these steps:

  Clone the repository:

  bash
  
    git clone https://github.com/Infi-7/Blog-Website.git
    cd Blog-Website

  Set up a virtual environment (optional but recommended):

  bash

    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate

  Install the required dependencies:

  bash

    pip install -r requirements.txt

  Set up the database:

    While using any database make sure to create a database and configure your credentials in a .env file (or config file).

  bash

    flask db init  # Initialize the database
    flask db migrate
    flask db upgrade

Run the app:

bash

    flask run

    The website will be available at http://127.0.0.1:5000.

Usage

    Create an account:
        Navigate to the registration page, create a new account, and log in.

    Write a blog post:
        Once logged in, click the "New Post" button, fill out the form, and publish your post.

    Edit or delete posts:
        You can view, update, or delete posts through your dashboard.

Screenshots

    Home Page:
![homepage1](https://github.com/user-attachments/assets/dfd44837-96d7-43c2-aebb-a10658e72603)
![homepage2](https://github.com/user-attachments/assets/0ab9b07e-f117-40f1-bbd6-7a99e74017d2)
![homepage3](https://github.com/user-attachments/assets/33d33d1e-e343-4927-8629-5ec2fdf2611e)

    Create Blog Post:
![new_post1](https://github.com/user-attachments/assets/6afcff68-88da-4742-81e5-b682ca373d8e)
![new_post2](https://github.com/user-attachments/assets/71cdc3dc-c556-41c9-9435-f09627b00212)
![new_post3](https://github.com/user-attachments/assets/7f2c0aad-4b67-4246-afb2-7be4ecf05e4e)

    Blog Post View:
![post1](https://github.com/user-attachments/assets/884ba1b4-3065-46d9-be64-962c15bf7f9e)

Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.
Steps for Contributing:

    Fork the repository.
    Create a new branch for your feature.
    Submit a pull request explaining the feature or fix.
