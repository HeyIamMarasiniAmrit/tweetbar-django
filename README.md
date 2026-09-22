# TweetBar 🐦

A clean and simple Twitter-style microblogging application built with **Django 5**.

Users can register, log in, create tweets with optional photos, edit or delete their own tweets, and view a feed of all posts.

---

## Features

- User registration & authentication
- Create, read, update & delete tweets
- Photo upload support
- Only the tweet owner can edit/delete their tweets
- Responsive Bootstrap 5 UI
- Media files handling

---

## Tech Stack

- Django 5.2
- SQLite (default)
- Bootstrap 5
- Pillow (for image handling)

---

## Project Structure
chaihq/
├── chaihq/               # Project settings
├── tweet/                # Main app
│   ├── models.py         # Tweet model
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── templates/
├── templates/            # Base layout
├── media/                # Uploaded photos
└── manage.py

## Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/tweetbar-django.git
cd tweetbar-django

