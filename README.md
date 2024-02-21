<h2 align="center">Store Server</h2>
<h2>The project for study Django.</h2>

**Stack:**
- Python -> 3.12
- Django -> 3.2.13
- SQLite3

<h2>Local Developing</h2>
All actions should be executed from the source directory of the project and only after installing all requirements.

##### 1. Clone a repository

-git clone https://github.com/AliaksandrMartsun/store-server.git
##### 2.Firstly, create and activate a new virtual environment:

- python -m venv ../venv
- venv\bin\activate
##### 3.Install packages:

- pip install --upgrade pip
- pip install -r requirements.txt
##### 4.Run project dependencies, migrations, fill the database with the fixture data etc.:

- python manage.py migrate
- python manage.py loaddata <path_to_fixture_files>
- puthon manage.py runserver 

