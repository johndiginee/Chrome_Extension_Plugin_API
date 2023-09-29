# Chrome Extension Plugin API

## Project Overview

The Chrome Extension Plugin API serves as the backend for a Chrome extension application. It allows users to upload and manage videos. Key features include video uploads.

## Installation Instructions

### Prerequisites

Before setting up the project locally, ensure you have the following prerequisites installed:

- [Python](https://www.python.org/downloads/) (>=3.11.4)
- [Django](https://www.djangoproject.com/download/)
- [Django Rest Framework](https://www.django-rest-framework.org/#installation)
- A Database System (e.g., PostgreSQL, MySQL, SQLite) - [Django Database Installation](https://www.djangoproject.com/download/#database-installation)

### Installation Steps

1. Clone the repository:

        git clone https://github.com/johndiginee/Chrome_Extension_Plugin_API.git


2. Change into the parent directory:

        cd Chrome_Extension_Plugin_API


3. Set up a virtual environment:

        python3 -m venv venv


4. Activate your virtual environment:

        source venv/bin/activate


5. Install the Python dependencies:

        pip install -r requirements.txt


6. Create a .env file and set SECRET_KEY='yourkeys'


7. Apply migrations to create the database schema:

        python3 manage.py makemigrations
        python3 manage.py migrate


8. Start the development server: 
 ```
 python3 manage.py runserver
 ```

The API should now be running locally at [http://localhost:8000/](http://localhost:8000/).

## Usage Instructions


#### Video Upload:

- /api/events/: Create, list, and search for events.
- /api/events/{event_id}/: Retrieve, update, or delete a specific event.
- /api/events/{event_id}/attendees/: Manage event attendees.

#### Group_Event Management:

- /api/groupevents/: Create, list, and search for events.
- /api/groupevents/{event_id}/: Retrieve, update, or delete a specific event.
- /api/groupevents/{event_id}/attendees/: Manage event attendees.

## Getting Started

To get started with the project, refer to the [Installation Instructions](#installation-instructions) and [Usage Instructions](#usage-instructions) sections. Familiarize yourself with the API endpoints by exploring the [API Documentation](documentation.md) provided.

## Configuration

Configuration details can be found in the project's `settings.py` file. Make sure to configure the required environment variables or configuration files as needed. Additionally, if any API keys or secrets are required, they should be mentioned in this section.

## Coding Standards

The project follows specific coding standards outlined in our [Coding Style Guide](#coding-standards). We use linting and code formatting tools to maintain code quality.

## API Documentation (if applicable)

You can access the API documentation [here](https://octopus-app-nax2o.ondigitalocean.app/) when the server is running. It provides comprehensive information on how to use the API endpoints.

## License Information

This project is open-source and is licensed under the [MIT License](LICENSE). For the full license text, please [click here](LICENSE).

## Contributors

We acknowledge and appreciate the contributions of the following individuals to this project:

- View the list of contributors in [Contributors.md](CONTRIBUTORS.md)

&copy; 2023 Team Panther Backend - HNG
