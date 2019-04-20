# todo-list

This project is used to learn TDD and python project development

## Code Structure
```
todo-list
├── .editorconfig
├── .flake8
├── .github
│   └── PULL_REQUEST_TEMPLATE.md
├── .gitignore
├── README.md
├── VERSION
├── functional_tests.py
├── requirements-dev.txt
└── superlists
    ├── db.sqlite3
    ├── lists
    │   ├── __init__.py
    │   ├── admin.py
    │   ├── apps.py
    │   ├── migrations
    │   │   ├── __init__.py
    │   ├── models.py
    │   ├── tests.py
    │   └── views.py
    ├── manage.py
    └── superlists
        ├── __init__.py
        ├── settings.py
        ├── urls.py
        └── wsgi.py
```

## How to Build

### Build Environment Requirements
- OS
	- Linux or maxOS
- Tools

### Build Instructions
- Clone repository or fetch new commits

  ```sh
  # TODO
  ```
- Install dependencies
	
	```sh
	pip3 install -r requirements-dev.txt
	```

- Test

  ```sh
  python3 functional_tests.py
  ```	 

## How to Run
- Start Django server

	```sh
	cd superlists
	python3 manage.py runserver

	```

## Reference

[1] Harry J.W. Percival (2016) Test-Driven Development with Python. O'reilly