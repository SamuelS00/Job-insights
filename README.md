![capa](.images/readme-capa.png)
### About

The implementation of this project aims to implement analysis from a set of data on jobs. Implementations will be embedded in a web application developed with Flask. Writing tests for implementing data analysis.

---

### Learnings

* Use Python's interactive terminal.
* Use conditional and repeating structures.
* Use built-in Python functions.
* Use exception handling.
* Perform file manipulation.
* Write functions.
* Write tests with `Pytest`.
* Write your own modules and import them into other code.

---

### Technologies Used

![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

---

### Usage

1. **Clone the repository**
   * Use the command: `git clone git@github.com:SamuelS00Job-insights.git.`
   * Enter the repository folder you just cloned: `cd Job-insights`
2. **Create the virtual environment for the project**
   `python3 -m venv .venv && source .venv/bin/activate`
3. **install the dependencies**
   `python3 -m pip install -r dev-requirements.txt`

##### Virtual environment

Python offers a resource called a virtual environment, where it allows your machine to run without conflicts, different types of projects with different versions of libraries.

1. **create the virtual environment**

```shell
$ python3 -m venv .venv
```

2. **activate the virtual environment**

```shell
$ source .venv/bin/activate
```

3. **install the dependencies in the virtual environment**

```shell
$ python3 -m pip install -r dev-requirements.txt$
```

With your active virtual environment, the dependencies will be installed in this environment. When you need to deactivate the virtual environment, run the **"**deactivate**"** command. Remember to turn it back on when you get back to working on the project.

The dev-requirements.txt file contains all the dependencies that will be used in the project.

##### Project structure

```
Legenda:
🔸Arquivos que não podem ser alterados
🔹Arquivos a serem alterados para realizar os requisitos.
.
├──🔸README.md
├──🔸Dockerfile
├──🔸docker-compose.yml
├──🔸dev-requirements.txt
├──🔸requirements.txt
├── src
│   ├──🔸app.py
│   ├──🔸brazilian_jobs.py
│   ├──🔸counter.py
│   ├──🔹insights.py
│   ├──🔸jobs.csv
│   ├──🔹jobs.py
│   ├──🔸more_insights.py
│   ├──🔹routes_and_views.py
│   ├──🔸sorting.py
│   └── templates
│       ├──🔸base.jinja2
│       ├── includes
│       │   └──🔸nav.jinja2
│       ├──🔸index.jinja2
│       ├──🔸job.jinja2
│       └──🔸list_jobs.jinja2
├── tests
│   ├──🔸init.py
│   ├──🔸conftest.py
│   ├──🔸marker.py
│   ├── brazilian
│   │   ├──🔸init.py
│   │   ├──🔸conftest.py
│   │   ├──🔸mocks.py
│   │   ├──🔹test_brazilian_jobs.py
│   ├── counter
│   │   ├──🔸init.py
│   │   ├──🔸conftest.py
│   │   ├──🔸mocks.py
│   │   ├──🔹test_counter.py
│   ├── mocks
│   │   ├──🔸job_1.html
│   │   ├──🔸jobs.csv
│   │   ├──🔸jobs_with_industries.csv
│   │   ├──🔸jobs_with_salaries.csv
│   │   └──🔸jobs_with_types.csv
│   ├── sorting
│   │   ├──🔸init.py
│   │   ├──🔸conftest.py
│   │   ├──🔸mocks.py
│   │   └──🔹test_sorting.py
│   ├──🔸test_flask_app.py
│   ├──🔸test_insights.py
│   ├──🔸test_jobs.py
│   ├──🔸test_more_insights.py
│   └──🔸test_routes_and_views.py
```

##### Linter

run ` python3 -m flake8`

---

### Tests

Run  `pyhton3 -m pytest`

---
