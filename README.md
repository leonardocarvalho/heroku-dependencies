# heroku-dependencies

Install pre-requisites to your project in order

## Funcitonality

Is suggested this buildpack to be used with https://github.com/projetoeureka/heroku-buildpack-multi to install
requirements.txt pre-requisites when its lines have depends on each other

## Usage:

Create a file pre-requirements.txt. Pip will be used to install dependecies just like requirements.txt, however but two consecutive lines black splits pip install commands.
