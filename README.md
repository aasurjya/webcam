Directories of the projects

video_streaming/
├── videostream/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── consumers.py
│   ├── models.py
│   ├── routing.py
│   ├── tests.py
│   └── views.py
├── static/
│   └── js/
│       └── videostream.js
├── templates/
│   └── videostream.html
├── db.sqlite3
├── manage.py
└── video_streaming/
    ├── __init__.py
    ├── asgi.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py


* videostream/: This is the Django app directory for the video streaming application.
* migrations/: This directory contains database migration files.
* __init__.py: This file makes the directory a Python package.
* admin.py: This file registers models with the Django admin site.
* apps.py: This file defines the app configuration.
* consumers.py: This file contains the WebSocket consumer class.
* models.py: This file defines the app's database models.
* routing.py: This file defines the WebSocket routing.
* tests.py: This file contains the app's test cases.
* views.py: This file contains the app's views.
* static/: This directory contains static files like CSS and JavaScript.
* js/: This directory contains the videostream.js file that handles the client-side JavaScript code.
* templates/: This directory contains the videostream.html file that defines the HTML template for the app.
* db.sqlite3: This is the SQLite database file for the app.
* manage.py: This is the Django management script.
* video_streaming/: This is the project directory.
* __init__.py: This file makes the directory a Python package.
* asgi.py: This file contains the ASGI configuration.
* settings.py: This file contains the app's settings.
* urls.py: This file contains the app's URL configuration.
* wsgi.py: This file contains the WSGI configuration.