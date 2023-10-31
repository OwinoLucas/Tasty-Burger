##Tasty Burger
##########################

Tasty burger is an online web portal to allow users to register and order for a burger from 
tasty burger.

# Screenshots
## Home Page
![Screenshot from 2023-10-31 15-54-27](https://github.com/OwinoLucas/djangoAPIS/assets/60548928/2266017c-ee8b-420b-a5dc-0b46def1f0cc)

## Services
![Screenshot from 2023-10-31 15-54-48](https://github.com/OwinoLucas/djangoAPIS/assets/60548928/27d79fff-ddca-49e3-8a59-59caad65c00f)

## Blog
![Screenshot from 2023-10-31 15-55-04](https://github.com/OwinoLucas/djangoAPIS/assets/60548928/6728f135-53cf-4714-9e36-244c0d20e37e)


# Getting Started

1). Clone the application from the repo
	git clone [repo link]

2). Change the durectoy
	cd tasty_burger

3). Create a virtual enviroment
	python3.6 -m venv venv

4). Install the dependencies

	pip install -r requirements.txt

5). Make the migrations
	python manage.py makemigrations

	python manage.py migrate

6).Add the following to your enviroment 
	export SECRET_KEY='your_secret_key'

	export EMAIL_USERNAME='your_gmail_username'

	export EMAIL_PASSWORD='your_password' 
7). Create a superuser
	python manage.py createsuperuser 

9). Run the application

	python manage.py runserver


##For the heroku hosted one

https://tasty-burger-kenya.herokuapp.com/