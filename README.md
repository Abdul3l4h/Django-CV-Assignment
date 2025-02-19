# Django CV Assignment
 Individual assignment: Convert your CV to HTML using Django template

Django Project

Setup and Run Instructions (macOS & VSCode)

Prerequisites

Ensure you have the following installed:

Python 3.x (Check with python3 --version)

pip (Check with pip --version)

VSCode (Download Here)

Python Extension for VSCode (Install from Extensions Marketplace)

1. Clone the Repository

git clone <repository_url>
cd <project_name>

2. Set Up Virtual Environment

python3 -m venv venv
source venv/bin/activate

3. Install Dependencies

pip install -r requirements.txt

4. Apply Migrations

python manage.py migrate

5. Create a Superuser (Optional, for Admin Panel Access)

python manage.py createsuperuser

Follow the prompts to set up a username and password.

6. Run the Server

python manage.py runserver

Open http://127.0.0.1:8000/ in a browser.

7. (Optional) Running in VSCode Debug Mode

Open the project in VSCode (code . from Terminal).

Go to Run > Start Debugging or press F5.

Select Django if prompted.

Troubleshooting

If venv is not activated, try:

source venv/bin/activate

If dependencies are missing, ensure requirements.txt is correctly set up.

For permission issues, try using python3 instead of python where necessary.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Author

Your NameYour Contact Information
