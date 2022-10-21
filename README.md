### Ninja’s Stack

### Motivation

Ninja's Stack was developed during Coding Dojo Software Development Immersive Full-Time Bootcamp.

Ninja's Stack is a website developed using Django framework. Frontend for Ninja's Stack was developed using the Bootstrap framework.

Our project covers all learned concepts: Restful Routing, Validations with Django, and Deployment.




### Description

The Ninjas Stack website is a platform for developers to communicate , cooperate, and grow !

Ninja's Stack is a community website for Ninja developers; Ninja developers can ask and answer each other and comment on other Ninjas' replies.




### Features

Manage Ninjas: Admins can add/delete Ninjas and update their information.
Direct Message and Comments: Ninjas can start a chat and answer inquiries.
Profile Edit: Each Ninja can edit his/her profile.

-  Register form requires email , first and last name, and password according to the validation instructions to ensure valid data.
- The login form requires an email address and a password.
 After logging in, we have :
- Users dashobard consist of a list of all registered users, their information, and their authority level, whether admin or normal.

- Clicking on the developer's name will take us to the developer page , where we can start a conversation in thread manner.

This allows us, as developers, to ask any question we have and get help from others .

- Each message is displayed with the sender's name and time .

- likes on the answers and unlike .

- Each message has a list of names of those who liked the message .

- Profile page , has all the user data where the user can update his/her password and all other data according to the validation instructions.

Now the Admin has all the previos featurs plus the following :

- Add new users .

- Edit existing users date and authority level.

- Remove existing users .

## Getting Started

### Installing Dependencies

#### Python 3

Follow instructions to install the latest version of python for your platform in the [python docs](https://docs.python.org/3/using/unix.html#getting-and-installing-the-latest-version-of-python)

#### Virtual Enviornment

We recommend working within a virtual environment whenever using Python for projects. This keeps your dependencies for each project separate and organaized. Instructions for setting up a virual enviornment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

#### PIP Dependencies

Once you have your virtual environment setup and running, install dependencies by naviging to the `NinjaStack` directory and running:

```bash
pip install -r requirements.txt
```

This will install all of the required packages within the `requirements.txt` file.

### Running the project

#### Start the project locally

From within the `NinjaStack` directory, first ensure you are working using your created virtual environment.

To run the server, execute:

```bash
python manage.py runserver
```

Then, for database migration, execute:

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

### Demo
[Ninjas Stack](https://www.youtube.com/watch?v=MkCSCvsetdo)

### Authors
- [Nada Alsogour](https://github.com/Nada-bit73)
- [Sarah Alsaedi](https://github.com/sarah-47)
- [Reem Allharbi](https://github.com/ReemAllharbi)
- [Amal Aldawsari](https://github.com/amalsaud)

### Acknowledgements

We want to convey our appreciation and gratitude to Coding Dojo and Saudi Digital Academy for this opportunity.
