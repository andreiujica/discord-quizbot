
<h4 align="center">A <a href="https://discord.com/" target="_blank">Discord</a> bot for simple quizzes.</h4>

<p align="center">
 <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
 <img src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"/>
 <img src="https://img.shields.io/badge/%3CServer%3E-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white"/>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#license">License</a>
</p>

![discord bot](https://user-images.githubusercontent.com/46849514/189495907-97bcc7c0-dd0c-4c73-8de2-af545aacafdd.png)

## Key Features

* Get a random question everytime you type the command "$question"
  - Answer Timeout
  - Points system
* Django REST Framework API 
  - Connect your database of choice
* Discord.py for interacting with the Discord API
* Asyncio for asynchronous programming

## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Poetry](https://python-poetry.org/docs/). From your command line:

```bash
# Clone this repository
$ git clone https://github.com/andreiujica/discord-quizbot

# Go into the repository
$ cd discord-quizbot

# Install dependencies
$ poetry install

# Setup Django Application
$ poetry run python manage.py createsuperuser
$ poetry run python manage.py migrate

# Run the API
$ poetry run python manage.py runserver

# Run the Discord bot
$ poetry run python bot.py
```

## License

MIT

