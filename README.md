# codetice_taskno.1
# URL Link Shortener

This is a simple URL link shortener web application developed as a task for Codetice Company by Arisetty Sai Ganesh.

## Overview

This web application allows users to shorten long URLs, making them more convenient to share. It is built using Python and Flask for the backend, and it uses SQLAlchemy to store the original and shortened URLs in a SQLite database. The frontend is created using HTML templates, and Bootstrap is used for styling.

## Features

- Shorten long URLs to more manageable links.
- Access shortened URLs to be redirected to the original link.
- Store shortened URLs in a SQLite database.
- Simple and intuitive user interface.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python (3.6+)
- Flask
- Flask-SQLAlchemy
- ShortUUID

You can install these dependencies using `pip`:

```bash
pip install Flask Flask-SQLAlchemy shortuuid
