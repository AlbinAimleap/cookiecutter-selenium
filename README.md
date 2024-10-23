
# Cookiecutter SELENIUM

A Cookiecutter template for creating Selenium applications with best practices.


## Usage

First, make sure you have cookiecutter installed:

```bash
pip install cookiecutter
```

Then generate your project:
```bash
cookiecutter https://github.com/AlbinAimleap/cookiecutter-selenium
```

You'll be prompted for basic info about your project:

- project_name: Your project name
- project_slug: The name used in setup.py and other files
- project_description: A brief description of your project
- author_name: Your name
- author_email: Your email
- version: Initial version of your project

## Project Structure
```
project/
    ├── README.md
    ├── requirements.txt
    ├── main.py
    ├── schema.py
    ├── selenium_base/
        ├── __init__.py
        ├── core/
            ├── __init__.py
            ├── base.py
            ├── schema.py
            └── logger.py
```

## Happy Coding ;)


