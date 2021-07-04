# My-Gallery
#
#### Author:[Ayuel Garang](https://github.com/ayuelgarang105)


## Description
My Gallery is an application developed using Django to display my photos. Other people can also see the photos when they visit the site, and the user can click on the image to view the details of the image.

my
## Figma Design

A link to my [figma design](https://www.figma.com/file/UNq2anH6uJd5N61DvW1J5M/Gallery?node-id=0%3A1)

## Setup and installations
* Clone Project to your machine
* Activate a virtual environment on terminal: `source virtual/bin/activate`
* Install all the requirements found in requirements.txt file.
* On your terminal run `python3.8 manage.py runserver`
* Access the live site using the local host provided



## Getting started

### Prerequisites
* python3.8
* virtual environment
* pip

#### Clone the Repo and rename it to suit your needs.
```bash
git clone https://github.com/ayuelgarang105/My-Gallary.git
```


#### Create and activate the virtual environment
```bash
python3.8 -m virtualenv virtual
```

```bash
source virtual/bin/activate
```

#### Setting up environment variables
Create a `.env` file and paste paste the following filling where appropriate:
```
SECRET_KEY='Generate one that suits you'
DEBUG=True
DB_NAME='photos'
DB_USER='<your database name>'
DB_PASSWORD='<password to your database>'
DB_HOST='127.0.0.1'
MODE='dev'
ALLOWED_HOSTS='*'
DISABLE_COLLECTSTATIC=1
```

#### Install dependancies
Install dependancies that will create an environment for the app to run
`pip install -r requirements.txt`

#### Make and run migrations
```bash
python3.8 manage.py check
python manage.py makemigrations gallery
python3.8 manage.py sqlmigrate news 0001
python3.8 manage.py migrate
```

#### Run the app
```bash
python3.8 manage.py runserver
```
Open [localhost:8000](http://127.0.0.1:8000/)

        
## Built With

* [Python3.6](https://docs.python.org/3/)
* Django 3.1.3
* Postgresql 
* Boostrap
* HTML

### License

* LICENSED UNDER  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](license/MIT)