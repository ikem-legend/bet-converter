# Bet Converter - A Django powered app for converting bets between multiple bet sites

Bettors have always had their preferred betting sites and yet are always willing to try other sites based on the benefits available. 
Other times they come across bet slips online but for different betting sites than theirs so they have to manually recreate the bets.
This app aims to solve these problems by automatically converting bet slips between multiple sites.

## Requirements
* Python 3.7+
* Django 3.2+ and other dependencies in the Pipfile
* PostgreSQL

## Installation
After cloning the project, create a virtual environment using pipenv and run the following command:
```bash
pipenv install
```

Rename the .env.example file to .env and update the environment variables.

To create an admin user:
```bash
python manage.py createsuperuser
```
Create the database and start the server with the following commands:
```bash
python manage.py migrate

python manage.py runserver
```

## License

This project is [MIT licensed](LICENSE).