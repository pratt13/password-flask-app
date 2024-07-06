# README

A flask app that contains details on what a strong password might contain and some basic password tasks to try and crack a users password.

## Requirements
### Running the App
#### Replit
An example of this software is hosted publicly on Replit [here]().

#### Locally
The version of software this program is tested on is Python 3.8.10.
Other versions may or may not work.

#### Exercises
Some of the exercises can be done via the UI.
Some however, must be done either via a cURL command or some other programmatic way of posting to an application endpoint.
To facilitate this there are other [replit]()/[github repository]() that do this.

## Setup 
### Replit

### Locally

```sh
python3 -m venv flask-app
source flask-app/bin/activate
pip3 install -r requirements.txt
flask run --host=0.0.0.0
```

The app will be hosted on `localhost:5000/`.



## Tasks
Summary of tasks are below, but the flask app has far more information of you navigate to it.

### Task 1
#### Boyle's Task

Boyle has a web page with all his secrets, he has a password as a three digit pin. Can you guess it?

#### Terry's Task

Terry has a web page with all his secrets, he has a password that uses four common phrases, plus two extra characters.

## Task 2
Create a python function to generate a password of 8 characters.
It must have:
* A lowercase letter
* An uppercase letter
* A number
* A special character `£$?!_`
* No examples of `Qwerty, Password, Pa$$w0rd, yoghurt, cagney, lacey`
* No repeats within 100 tries
* Range of characters, not all the letter `a1a2a3a4`
* All characters are randomly and uniformly chosen.

To ensure that you haven't got one good solution only, the task also includes creating a 100 of these 'strong' passwords.

## Testing
This repository is only covered by some simple unit tests.
Code coverage admittedly is not that great.
### Unit tests

```sh
python3 -m unittest
```

