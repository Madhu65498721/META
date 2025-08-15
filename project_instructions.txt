Hello, Reviewers!

To execute the available unit tests, open the VS terminal and run:
python manage.py test tests/

Please ensure you have activated the virtual environment and navigated to the 'littlelemon' directory before running the unit test command.

# Path to verify that the application delivers static HTML content along with images and styles:
/restaurant

You may use the API endpoints listed below for testing via Insomnia, Postman, or directly in your web browser.

# JDOSER endpoint to send a POST request and create a new user:
/auth/users/

# Endpoint to obtain an authentication token upon login:
/api-token-auth/

# JDOSER endpoint alternative login path:
/auth/token/login

# Menu items listing and details:
/restaurant/menu/
/restaurant/menu/{menuItemId}

# Table booking system:
/restaurant/booking/tables/
/restaurant/booking/tables/{bookingId}
