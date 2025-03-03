# Booking Site
Welcome to the Booking Site project! This application allows users to search for and book flights, providing a seamless experience for managing travel plans.

### Features
- **Flight Search**: Users can search for available flights based on their travel preferences.
- **User Authentication**: Secure user registration and login functionalities to manage bookings.
- **Booking Management**: Users can view and manage their flight bookings.
  
### Technologies Used
- **Backend**: Python with Django framework.
- **Frontend**: HTML for templating.
- **Database**: SQLite for data storage.
  
### Installation
To set up the project locally, follow these steps:

Clone the repository:
```bash
git clone https://github.com/IVON1010/booking-site.git
```

Navigate to the project directory:

```bash
cd booking-site
```
Install dependencies:
Ensure you have Pipenv installed. Then, run:

```bash
pipenv install
```

Apply migrations:

```bash
pipenv run python manage.py migrate
```

Run the development server:

```bash
pipenv run python manage.py runserver
```

The application will be accessible at http://127.0.0.1:8000/.

### Usage
- **Flight Search**: Use the search functionality on the homepage to find flights.
- **User Registration/Login**: Register a new account or log in to manage your bookings.
- **Booking Management**: After logging in, navigate to the "My Bookings" section to view or cancel your reservations.
  
### Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests.

### License
This project is licensed under the MIT License. See the LICENSE file for more details.
