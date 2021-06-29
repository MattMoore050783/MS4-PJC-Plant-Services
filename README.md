![responsiveimage](Documentation/ResponsiveImage.png)

PJC Plant Services - E-Commerce Site - MS4
---
## Table of Contents

- [**About**](#About)
- [**UX**](#UX)
  - [Goals](#Goals)
  - [User Stories](#User-Stories)
  - [Styling](#Styling)
  - [Wireframes](#Wireframes)
- [**Features**](#Features)
  - [Existing Features](#Existing-Features)
  - [Features Left To Implement](#Features-Left-To-Implement)
- [**Technologies Used**](#Technologies-Used)
  - [Version Control](#Version-Control)
- [**Testing**](#Testing)
  - [Testing User Stories](#Testing-User-Stories)
  - [Responsive Testing](#Responsive-Testing)
  - [Additional Testing](#Additional-Testing)
  - [Code Validation](#Code-Validation)
- [**Deployment**](#Deployment)
  - [Live Website Link](#Live-App-Link)
  - [Repository Link](#Repository-Link)
  - [Running Code Locally](#Running-Code-Locally)
- [**Credits**](#Credits)
  - [Content](#Content)
  - [Media](#Media)
  - [Acknowledgements](#Acknowledgements)
  
---

## About

PJC Plant Services are a Hire and Consumables supplier to the construction Industry based in Leicester.

During Lockdown a lot of business was lost due to construction sites being closed. The mission for the business was to advertise and sell via a e-commerce store online to increase revenues and the customer base of the business as well as how they current supply via orders from the telephone and people visiting the store.

The online store needed the mirror the  products in the store and be easy for customers to find and buy the products they needed.

The online store also needed to be designed with the PJC Plant Services colour scheme and logo.

___

## UX

#### Goals

The goals of the website were:-
- Sell all products on the website that are currently sold from the warehouse.
- Hold secure information for all current customers and new customers so they can login to place orders.
- The website theme and colours must tie in with the company logo and profile
- The website must be accessible and show correctly on all devices from PC/Laptops to Tablets and mobile phones.
- Products on the website must be easily be able to be modified and added.
- Payments via the website must be secure.

---

#### User Stories

From the Designers Perspective:-
- The site must be easy to use and navigate and easy to find products.
- The site must show correct and east to view on all devices.
- The sites colour scheme must work with the PJC Plant Services logo colour scheme and font
- The Menus must be clear and concise so users can navigate around the site easily.
- Products must be able to be easily modified and added to the database
- Images for each product must be clear on all devices to the user.
- The shopping Bag must be clear of what products are being brought and how much the total cost is including delivery.
- Login and Registration to the site must be secure but easy for the user to do.
- Details about the company location and other social media formats must be shown.
- Products can be searched easily and also ordered easily by Price, Rasting etc.
- The checkout page must be secure and easy to understand so the user can complete the purchase easily and quickly.

From the users perspective:-
- I need to find the product I want to buy easily.
- My personal details held on the site need to be secure and access needs to be secure.
- I need to be able to see the product clearly before purchasing.
- I need to be able to see how much my total order is going to cost including delivery.
- I need to be able to modify products and add products to the database.
- I need to be able to place the order easily and securely through the website.
- I need to be able to register for a new account easily so I can buy products.
- I need the system to store my details so I dont have to fill this out everytime I place a order.

---

### Styling

The site must be easy to view on all devices with menus clear and concise, the colours must integrate with the colour scheme of the PJC Plant Services Logo.

The below colour scheme was used for the menus and text.

![ColourScheme](Documentation/ColourScheme.png)

The font chosed was Montserrat because it was clear and concise. The backup font if google fonts didnt load is Sans-Serif.

The background image used for the site was a picture of the head office to shot customers when entering the site they was dealing with a reputable and professional company for all construction supply needs..

---

### Wireframes

Wireframes/Database Tables Link - [Wireframes](Documentation/Wireframes/Wireframes.pdf)

**Design Changes to Wireframes**
- Colour changes added to menu when hovering with a mouse
- Menu Structure was changed and shortened for a better user experience.
- Has sizes taken out on the products, individual products for each size will be added to the site instead.

---

## Features

### Existing Features

- The navigation menu shows at the top but shrinks to a burger on smaller devices and shows on the left side of the screen with a company logo shrinking to give the user access back to the homepage.
- Users can login and register to the system which will be stored on the system for delivery information to be automatically stored for future orders.
- Admin access must be given by the system administrator with access to Django Admin.
- Different menu options show between admin and standard user, admin users can add and modify products and have access to the product management pages.
- Standard users have access to only buy products and update there profile information.
- Purchases at the checkout are made via Stripe for secure purchases via card.
- Users details of the shopping cart are stored until the browser is closed.
- The footer is pinned to the bottom of all pages.
- Webhooks are generated when a purchase is made in case any issues wth the site craching or user error, the order and payments still go through to stripe and to the database via the webhook.
- The search function searches all products and matches the product name and description of anything added in the search critera.
- Boostrap classes are used on all pages so it shows on mobile devices as well as large devices, pictures used are clear and concise for each product the give the user the best experience.


### Features Left To Implement

- Product Quantities to be linked the the purchasing/stock system so stocks can be checked before placing orders.
- More products to be added to match the total catalogue for the company.

---

## Technologies Used

- Bootstrap4
  - Bootstrap4 was used for page structures and features like the menu system.

- HTML  
  - HTML was used for the main structure of the website.

- JQuery/Javascript
  - JQuery was used for boostrap features that needed some javascript function - Return to top button.

- CSS
  - CSS was used to style and change sizes and positions of different items where boostrap couldn't be used.

- Python 
  - Python was used for creating the apps, models for each section.

- Django
  - Django was used for the framework for the website alongside Python.

- Google Chrome
  - Google Chrome Inspect and Developer tools was used for examining the website on different devices.

- Google Fonts
  - Google fonts was used for the font of the website.

- Font Awesome
  - Font Awesome was used for the icons on the forms.

- Django Crispy Forms 
  - Used for forms on the site.

- Django Allauth 
  - Used for user authentication on the site.

- Stripe 
  - Used to handle payments on the website.

- VS Code 
  - VS Code was used as the development tool to create all pages. Different add-ons were used in VS Code to aid my developement. These add-ons included were:-
    - Auto Close and Rename Tag - to end tags automatically.
    - Beauty - To help Beautify my coding.
    - Color Highlight - Shows the colours in your coding.
    - CSS Peek - Allows you to show the CSS Next to your HTML Code, rather than going between the two files.
    - Live Server - Allows you to see the live webpage as you code
    - Markdown Preview Enhancer - Allows you to see your markdown file as you type.
    - Prettier - Allows you to Beautify your CSS.

- Balsamiq was used to create the wireframes

### Version Control

- VS Code
  - VS Code linked to the repositry in Github was used to do regular Commits from my changes and additions to the website.

- Github
  - Github was used to store the repositry online. All Adds/Commits go to this file online. 

- Heroku
  - Heroku was used to store and run the application, heroku was linked to github to auto update.

- AWS
  - Amazon web services was used to store the static files for the site.

- Postrgres SQL
  - PostgresSQL was used to store the datafor orders, customers etc migrated from the SQL Lite in the development environment.

---

## Testing

### Testing User Stories

| Story  |  Test | Extra Coding Required  |
|---|---|---|
|I need to find the product I want to buy easily|Tested the different menus, search function to find products|All working ok|
|My personal details held on the site need to be secure and access needs to be secure|Tested the secure login to Django and the site and Heroku once deployed|All secure|
|I need to be able to see the product clearly before purchasing|Tested viewing the produucts on different devices|Some products showed too small on mobile devices so I made them bigger using a 12 Column instead of 2 6 Columns|
|I need to be able to see how much my total order is going to cost including delivery|Tested the order in the bag and at checkout and the bag total updating when more products are added|All working ok|
|I need to be able to modify products and add products to the database|Tested logging in as Admin and using the Product Management, Edit and Delete Functions|All worked ok|
|I need to be able to place the order easily and securely through the website.|Tested the bag and checkout pages, was an issue with the country field|Changed the country to a dropdown menu to avoid issues with stripe and countires, used django-countries to do this|
|I need to be able to register for a new account easily so I can buy products.|Tested regsitering an account and getting the email confirmation|The e-mail didnt initially work so i created a new gmail account and used gmail as the base to send emails to customers, once this worked, registration was easy|
|I need the system to store my details so I dont have to fill this out everytime I place a order.|When users checkout, made sure address details are auto populated if a customer has already registered|Added the option at checkout to save delivery details if they have changed, apart from that all working ok|

### Responsive Testing

To check how the site ran on different devices I used Am-I-Responsive and Inspect in Google Chrome Developer Tools. I also pushed out the site regular to the live area and accessed the link on my IPhone, Ipad and Macbook. While doing these tests I did the following:-

|  Test | Result  |  Extra Coding Required |
|---|---|---|
|Tested the home page on Mobile/Tablet and Large Screen devices|Was working ok apart from the shop now button was aligned to the right side on smaller devices|reduced the padding on the button on smaller devices|
|Tested the menu between large and small devices|When the mobile menu shrunk down, there wasn't any link to get back to the home page|Added the company logo as a link to get back to home on the mobile view|
|Tested the products menu when searching and adding to bag|product details and buttons wasn't showing correctly on smaller devices|reduced the size of buttons and text on smaller devices|
|Tested the Search/My Account/Bag on smaller devices|On smaller devices the links was going over to two rows|Made the links smaller on smaller devices so they stayed on one row|
|Tested the Sort by and catergories links on small devices|Shrunk down and shown correctly by stacking on top|N/A|
|Tested the footer on all devices|Links were too small originally but everything else worked and staked ok|Made links bigger and changed colour when hovered to give the user a better experience|
|Tested all menu links on all devices|All links worked but the user didn't know which link he was definitely hovering over|Changed the background colour to greay when the user hovered over menu links to give them a better user experience|

### Additional Testing

I also carried the following addtional testing:-
|  Test | Result  |  Extra Coding Required |
|Flake8 - Ran flake8 on all my python code|correct the main error like fields not being used|N/A|
|Tested move from SQLite to PostGresSQL|Checked the export file before moving accross to the database on Heroku|N/A|
|Ran tests on AWS when the static files were moved over|Base.css wasn't moved over correctly|Created in the relevant folder and the site showed correctly|


### Code Validation

- W3C Markup Validation Service for HTML.
- W3C CSS Validation Service was used for validating the code.
- http://pep8online.com/ - For Validation Python Code.
- Slack - Peer Code Review Forum.

 ---

## Deployment

### Live Website Link

https://pjc-plant-services-ms4.herokuapp.com/

### Repository Link

https://github.com/MattMoore050783/MS4-PJC-Plant-Services

### Running Code Locally

To deploy the project the following is required:-

- Github account
- Heroku Account
- AWS Account

To create a clone follow the below steps:- 

Github
1. Login to github and find the repository.
2. Click Code and open with Github Desktop.
3. Follow the prompts in the GitHub Desktop Application.

Heroku Deployment with AWS

1. Install gunicorn, psycopg2-binary and dj-database-url using the PIP Install command.
2. Freeze all the requirements for the project into a requirements.txt file using the pip3 freeze > requirements.txt command.
3. Create a procfile, with the following inside it: web: gunicorn pjc_plant_services_ms4.wsgi:application
4. Push these changes to GitHub, using git add . git commit -m and git push commands.
5. Navigate to [Heroku](https://www.heroku.com/), and login or create an account.
6. Once logged in, click on 'resources'.
7. From the add-ons search bar, add the Heroku Postgres DB, select the free account, and then submit order form to add it to the project.
8. From the app's dashboard, click on 'settings', and then 'reveal config vars' in order to set the necessary configuration variables for the project. 
It should look like this: 

| Key                   | Value                      |
|-----------------------|----------------------------|
| AWS_ACCESS_KEY_ID     | Your AWS Access Key        |
| AWS_SECRET_ACCESS_KEY | Your AWS Secret Access Key |
| DATABASE_URL          | Your Database URL          |
| EMAIL_HOST_PASS       | Your Email Password        |
| EMAIL_HOST_USER       | Your Email Address         |
| SECRET_KEY            | Your Secret Key            |
| STRIPE_PUBLIC_KEY     | Your Stripe Public Key     |
| STRIPE_SECRET_KEY     | Your Stripe Secret Key     |
| STRIPE_WH_SECRET      | Your Stripe WH Key         |
| USE_AWS               | TRUE                       |

9. Back on the main dashboard, click on 'deploy', and then under the 'Deployment' method section, select GitHub and 'Automatic Deploys'.

10. Ensure that in settings.py, the following code is commented out:

Database
 https://docs.djangoproject.com/en/3.1/ref/settings/#databases

and the following code is added:

DATABASES = {
        'default': dj_database_url.parse(os.environ.get('DATABASE_URL'))
    }
11. Make migrations using the following command:
python3 manage.py makemigrations
and migrate the database models to the Postgres database using the following command:
python3 manage.py migrate

12. Load the fixtures from the 'product_types.json' file and then from the 'products.json' file - which are contained in the 'fixtures' folder into the database. 
This is done by using the following command:
```
python3 manage.py loaddata <file name>
```
13. Create a new superuser with the following command:
python3 manage.py createsuperuser
and then enter chosen email, username and password.

14. In settings.py, contain the previously entered database setting in an if statement, and add an else condition, so that different databases are 
used depending on the environment.

if 'DATABASE_URL' in os.environ:
    DATABASES = {
        'default': dj_database_url.parse(os.environ.get('DATABASE_URL'))
    }
else:
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.sqlite3',
            'NAME': BASE_DIR / 'db.sqlite3',
        }
    }

15. Disable 'COLLECTSTATIC' with the fillowing code: heroku config:set DISABLE_COLLECTSTATIC=1
so that Heroku doesn't attempt to collect the static files.
16. Add ALLOWED_HOSTS = ['pjc-plant-services-ms4.herokuapp.com', 'localhost', '127.0.0.1'] to settings.py.
17. Add Stripe environment variables to settings.py.
18. Push to Heroku using the following command:
    git push heroku master

Amazon Web Services:

All Static and media files for the deployed version of the site are hosted in a Amazon Web Services(AWS) S3 bucket. 
In order to create your own bucket, please follow the instructions on the AWS website 
[Here](https://docs.aws.amazon.com/AmazonS3/latest/userguide/creating-bucket.html)

1. In the gitpod terminal, install boto3 and django-storages using the following commands:
   pip3 install boto3 and pip3 install django-storages
2. Freeze the new requirements into the 'requirements.txt' file using the pip3 freeze > requirements.txt command
3. Add 'storages' to INSTALLED_APPS in settings.py.
4. Add the following code to settings.py in order to link the AWS bucket to the website:

if 'USE_AWS' in os.environ:
    # Cache control
    AWS_S3_OBJECT_PARAMETERS = {
        'Expires': 'Thu, 31 Dec 2099 20:00:00 GMT',
        'CacheControl': 'max-age=94608000',
    }

    # Bucket Config
    AWS_STORAGE_BUCKET_NAME = 'downham-and-finch'
    AWS_S3_REGION_NAME = 'eu-west-2'
    AWS_ACCESS_KEY_ID = os.environ.get('AWS_ACCESS_KEY_ID')
    AWS_SECRET_ACCESS_KEY = os.environ.get('AWS_SECRET_ACCESS_KEY')
    AWS_S3_CUSTOM_DOMAIN = f'{AWS_STORAGE_BUCKET_NAME}.s3.amazonaws.com'

    # Static and media files
    STATICFILES_STORAGE = 'custom_storages.StaticStorage'
    STATICFILES_LOCATION = 'static'
    DEFAULT_FILE_STORAGE = 'custom_storages.MediaStorage'
    MEDIAFILES_LOCATION = 'media'

    # Override static and media URLs in production
    STATIC_URL = f'https://{AWS_S3_CUSTOM_DOMAIN}/{STATICFILES_LOCATION}/'
    MEDIA_URL = f'https://{AWS_S3_CUSTOM_DOMAIN}/{MEDIAFILES_LOCATION}/'

5. Create a custom_storages.py file in the root level of the project. Inside it, include the locations of the Static Storage and Media Storage.
6. Delete DISABLE_COLLECTSTATIC from the Heroku Config Variables.
7. Finally, push to GitHub, and all changes should be automatically pushed to Heroku too.

Making a Local Clone:
In order to make a local clone of the PJC Plant Services website, enter git clone https://github.com/MattMoore050783/MS4-PJC-Plant-Services into the terminal. 

Next, create an .env.py file in the root directory of the project, and add it to the .gitignore file. 
The following code needs to be added to the .env.py file:

import os  
os.environ["DEVELOPMENT"] = "True"    
os.environ["SECRET_KEY"] = "<Your Secret Key>"
os.environ["STRIPE_PUBLIC_KEY"] = "<Your Stripe Public Key>"    
os.environ["STRIPE_SECRET_KEY"] = "<Your Stripe Secret Key>"    
os.environ["STRIPE_WH_SECRET"] = "<Your Stripe WH Secret Key>"   

Then make sure that the required packages are installed by running the following command: 
pip install -r requirements.txt

Make migrations and then migrate in order to create a database, by running the following commands:
python3 manage.py makemigrations and python3 manage.py migrate.

New products can be entered via the Django Admin panel or the SQLLite Database can be imported by using the following command
python3 manage.py loaddata

Create a superuser with the following command: python3 manage.py runserver and entering your email, username and password.

Run the app by entering the following command:
python3 manage.py runserver

---

## Credits

### Code

I used the following links to help my coding:-
- Code Institue task project for setup and linking to AWS.
- https://stackoverflow.com/ - for various issues when writing queries in Python.
- https://www.w3schools.com/python/default.asp - for extra help and tuition with Python.
- https://miniwebtool.com/django-secret-key-generator/ - for generating the secret key
- https://getbootstrap.com/docs/5.0/getting-started/introduction/ - For help with bootstrap classes
- http://ami.responsivedesign.is/ - For help with how the site looked on different devices
- https://dashboard.stripe.com/test/dashboard - For stripe JS Code for my project and webhooks testing


### Content

All content for the site was based on what would be required by PJC Plant Services if this app was to be live.

### Media

All pictures used from other builder merchants websites like Screwfix, etc.

### Acknowledgements

Many Thanks to the below for the help and guidances throughout my project:- 
- My Mentor Maranatha
- Code Institues support team for increasing my hand in date and being supportive.
- The slack community for feedback on my website. 
- Code Institute and the learning programme Python and the Boutique-Ado Project
