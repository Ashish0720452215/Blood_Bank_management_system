# Blood Bank Management System

This is a web-based application developed using Django, a Python web framework, to manage the operations of a blood bank. The system facilitates the management of blood donors, blood recipients, inventory, and blood donation events.

## Features

- **Donor Management:** Add, edit, and delete donor information, including contact details and blood type.
- **Recipient Management:** Manage recipients' details, including their medical history and blood requirements.
- **Inventory Management:** Keep track of available blood units, expiration dates, and storage conditions.
- **Donation Events:** Schedule and manage blood donation events, including location, date, and volunteer coordination.
- **User Authentication:** Secure user authentication system for administrators, donors, and recipients.

## Installation

1. Clone the repository:

git clone https://github.com/your-username/blood-bank-management.git

css

2. Navigate to the project directory:

cd blood-bank-management

arduino

3. Install dependencies using pip:

pip install -r requirements.txt

4. Apply database migrations:

python manage.py migrate

5. Create a superuser account:

python manage.py createsuperuser

6. Start the development server:

python manage.py runserver

7. Access the application at `http://localhost:8000` in your web browser.

## Usage

1. Login to the system using the credentials of the superuser created in step 5.
2. Navigate to the appropriate sections (Donors, Recipients, Inventory, Events) to manage data.
3. Use the provided forms and interfaces to add, edit, or delete records.
4. Ensure to log out after completing tasks for security purposes.

## Contributing

Contributions are welcome! If you have ideas for new features, find bugs, or want to improve the codebase, feel free to submit pull requests or open issues.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
