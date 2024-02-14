**# Django User Authentication and Profile Display**

**## Features**

- **User authentication (sign up, log in, log out)**
- **User profile display (email and username)**
- **Uses Django's built-in authentication system**
- **Simple Bootstrap-based UI for a pleasant user experience**

**## Setup Instructions**

**1. Clone the Repository**
Clone this repository to your local machine using Git:
git clone <repository_url>

**2. Enter into project's directory**
cd <project_directory>

**3. Set up virtual enviroment.**
python -m venv venv  

**4. activate virtual enviroment**
venv\scripts\activate  

**5. Install django in venv**
pip install django --upgrade  

**6. Set up project**
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser 

**7. Run the application**
python manage.py runserver  

