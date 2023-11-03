Clone the repository using the command below :
'''code:
git clone https://github.com/dinaramashaeva/midterm.git

then move to directory where we have the project files : 
'''code:
cd blog
Create and install virtual environment :
'''code:
pip install virtualenv

'''code:virtualenv env
Install the requirements :
'''code:
pip install -r requirements.txt
'''code: set-executionpolicy unrestricted

Activate the virtual environment :
'''code:
env\scripts\activate
'''code:
pip install django

Run the App
'''code:
python manage.py runserver

Then, the server will be started at http://127.0.0.1:8000/
