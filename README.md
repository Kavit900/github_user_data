# github_user_data
This repository contains a basic endpoint that fetches a github information about a user whose name we are entering.


## How it works

1. Clone the repository
2. cd into the directory
3. run this command - python manage.py runserver
4. And after that go to the url - localhost:8000/app/profile

Basically, I am making of https://api.github.com/users/:username, to fetch the username entered by the user and the respose returned to me is in form of json, so it's easy to manipulate it.