Getting Started
1. To get a local copy up and running follow these simple example steps.

2. To get started, fork this repository to your GitHub account.

3. Clone the repo : 

" git clone https://github.com/aasis2002/E-Commerce.git
 
(optional) Create and activate a virtualenv (you may want to use virtualenvwrapper).

4. Install dependencies:

 " pip install -r requirements.txt "
 
5. Create a development database:

  " python manage.py migrate "
If everything is alright, you should be able to start the Django development server:

 6. " python manage.py runserver "
Open your browser and go to http://127.0.0.1:8000, you will be greeted with a welcome page.

Generate fake data
Make use of management command python manage.py createdata to generate fake categories and products automatically.
