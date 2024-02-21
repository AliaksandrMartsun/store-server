<h2 align="center">Store Server</h2>
<h2>The project for study Django.</h2>

**Stack:**
- Python

<h2>Local Developing</h2>
## All actions should be executed from the source directory of the project and only after installing all requirements.

##### 1.Firstly, create and activate a new virtual environment:

- python3.12 -m venv ../venv
- venv/bin/activate
##### 2.Install packages:

- pip install --upgrade pip
- pip install -r requirements.txt
##### 3.Run project dependencies, migrations, fill the database with the fixture data etc.:

- python manage.py migrate
- python manage.py loaddata <path_to_fixture_files>
- puthon manage.py runserver 

