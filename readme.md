# Tweet App

A web application built with Django that allows users to post, edit, and manage their tweets.

## Features

- User authentication and registration
- Create and publish tweets
- Edit existing tweets
- Upload images with tweets
- Delete tweets
- Responsive design using Bootstrap

## Technologies Used

- Python
- Django
- Bootstrap
- HTML/CSS
- SQLite (default Django database)

## Installation

1. Clone the repository:
```
git clone https://github.com/bindalsourabh1/blog-app.git
cd blog-app
```

2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```
pip install -r requirements.txt
```

4. Run migrations:
```
python manage.py migrate
```

5. Start the development server:
```
python manage.py runserver
```

6. Open your browser and navigate to `http://127.0.0.1:8000/`

## Usage

- Register a new account or login to an existing account
- Create tweets from your dashboard
- View all tweets on the home page
- Edit or delete your own tweets
- Upload images to enhance your tweets

## License
This project is licensed under the MIT License - see the LICENSE file for details.
