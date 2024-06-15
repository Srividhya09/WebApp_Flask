# WebApp_Flask
# Flask Blog Application
This is a simple blog application built using Flask, a lightweight web framework for Python. The application allows users to create, edit, delete, and view blog posts. The blog posts are stored in an SQLite database using SQLAlchemy for ORM.

# Features
Create Post: Add a new blog post with a title, content, and author.
Edit Post: Update the details of an existing blog post.
Delete Post: Remove a blog post from the list.
View Posts: Display all blog posts in chronological order.

# Requirements
Python 3.12
Flask
Flask-SQLAlchemy

# Code Overview
Application Structure
app.py: The main application file that sets up the Flask app, routes, and database models.
templates: Directory containing HTML templates for rendering web pages.

# Templates
index.html: The home page template.
posts.html: Template to display all blog posts.
edit.html: Template for editing a blog post.
new_post.html: Template for creating a new blog post.

