
# Holiday booking 

If you're looking to book a holiday online, there are several options available to you. Here are the steps you can follow to book your holiday online:
Decide on your destination and dates of travel. 
Holiday Booking platform that includes a time-off tracking system for employees. It allows you to request vacation time, view your remaining balance, and see who else on your team has scheduled time off.


# 375 x 1180
![375x1180](https://github.com/ocimar84/holidays/assets/79640465/d8d3814d-b5eb-4534-a8cb-b1ce760cdfc9)
# 768 x 1180
![768x1180](https://github.com/ocimar84/holidays/assets/79640465/4e0bd822-223a-4a64-8fc4-13e6b842679a)
# 1024 x 1180
![1024x1180](https://github.com/ocimar84/holidays/assets/79640465/72adf66e-0045-44b5-8308-7112915980f4)
# 1440 x 1180
![1440x1180](https://github.com/ocimar84/holidays/assets/79640465/69aab250-57fd-423f-873b-058f5a960394)



# Live Site

[Holidays](http://holidays-ocimar.herokuapp.com/)

# Content

* [Business Goals](#business-goals)

* [User experience](#user-experience)
    * [User stories](#user-stories)
    * [Agile Methodology](#agile-methodology)
    * [Crud Functionality](#crud-functionality)
    * [Wireframes](#wireframes)

* [Feautres](#features)
    * [Header](#header)
    * [Hero image](#hero-image)
    * [Login](#Login)
    * [Add time off](#Add-time-off)
    * [Add Department](#Add-Department)
    * [Reason](#Reason)
    * [Start and end date](#Start-and-end-date)
    * [The start date is invalid](#The-start-date-is-invalid)
    * [ADMIN](#ADMIN)
    * [Accounts](#Accounts)
    * [User](#User)
    * [Departmens](#Departmens)
    * [Time offs](#Time-offs)
    * [Change time off](#Change-time-off)
    * [Status](#Status)
    * [Disapproval](#Disapproval)
    * [Future features](#future-features)

* [Testing](#testing)
    * [Lighthouse](#lighthouse)
    * [HTML Validator](#html-validator)
    * [CSS Validator](#css-validator)
    * [Python Validator](#python-validator)
    * [JSON Validation](#json-validation)
    * [Manual](#manual)

* [Security Features](#security-features)


* [Credits](#credits)
    * [Code](#code) 
    * [Images](#images)
    * [Technology used](#technology-used)

* [Deployment](#deployment)
    * [Local deployment](#local-deployment)
    * [Production Deployment](#production-deployment) 
        * [Create heroku app](#create-heroku-app)
        * [Connect Postgres database](#connect-postgres-database)
        * [Deploy app on heroku](#deploy-app-on-heroku)
        * [PostgreSql](#postgresql)

* [Acknowledgements](#acknowledgements)

# Business goals

The objective of a holiday booking company in this context would be to provide an exceptional service that meets the needs of employees and companies, leading to a positive experience for the corporate group. This can help build long-term relationships. In addition, it can help the company to organize itself better with the help of this site.

# User experience

As an unauthorized user:
* Ability to access all the features and functions available to an authorized user, such as booking holidays, changing or canceling bookings, and viewing personal information.
* A user-friendly interface that makes it easy to navigate the site and find the desired information or features.
* Clear and concise instructions on how to use the site's features and functions, including any necessary steps for booking or modifying a holiday.
* A reliable and secure system for booking holidays, changing bookings, and canceling bookings.
* Prompt and effective customer support, including email or phone support, for any questions or issues that may arise during the booking process or during the holiday itself.

As an authorized user:
* Navigate the site easily and efficiently to view all the content you need.
* Create an account with a simple and easy process.
* Book a holiday for a specific time and date, choosing from available options and making payment through the site's secure payment gateway.
* Receive a confirmation email once the booking is complete, which includes all the relevant details about the holiday.
* Change the day of your holiday to a different date or time, if the website offers this feature. This may be subject to availability and may require additional payment if the new dates are more expensive than the original booking.
* Cancel your holiday, if the website offers this feature. The cancellation policy would typically be outlined in the terms and conditions.

As an administrator, I can:
* Viewing all available holidays and managing the booking system to ensure that the website's inventory is up-to-date and accurate.
* Reviewing and authorizing holiday requests from users, based on criteria such as availability, employee schedule, and other factors.
* Creating new user accounts if necessary, in order to provide access to the site's features and functions for new employees or customers.
* Managing user accounts and permissions, including setting access levels, resetting passwords, and monitoring activity on the site.
* Troubleshooting technical issues and providing support to users, including responding to inquiries and resolving any problems that arise.

## User stories
* Provide a registration option for users to create an account and access the booking features.
* Offer a clear option to opt out of sharing personal information for those who value their privacy.
* Be designed with easy navigation and user-friendly interface to make it easy for users to find information and take actions.
* Send a confirmation email after booking to ensure that users have a record of their reservation information.
* Allow users to cancel their reservation to provide flexibility in their travel plans.
* Display users' booking information clearly for easy reference.
* Have a secure login system to ensure the privacy and security of user information and booking details.
* Provide a prominent "book" button on the homepage to make it easy for users to initiate the booking process.
* Implement appropriate security measures to ensure that only authorized users can make updates to their reservations.
* By meeting these user requirements, a holiday booking site can offer a positive user experience that is easy to use, secure, and meets the needs of its customers.


## Admin stories
* User Account Approval:
As an administrator, you may receive a notification that a new user has registered on the site. You would then review the user's account details, such as name, email, and other information, to verify that they are a legitimate user. You would also check that their account has been created with the appropriate level of access and permissions, based on their role and responsibilities. Once you have confirmed that the user's account is valid and complete, you would approve their account and notify them that they can now log in to the site.

* Holiday Request Approval:
As an administrator, you would receive notifications when a user has requested a holiday booking. You would review the request details, such as the dates and location of the holiday, and check that the requested dates are available and that the user has sufficient vacation time or other permissions to take the holiday. You would also check that the user's account is in good standing, with no outstanding balances or other issues that would prevent them from booking a holiday. If the request is valid and meets all the necessary criteria, you would approve the holiday request and notify the user that their booking has been confirmed.

* Holiday Inventory Management:
As an administrator, you would have access to the site's inventory management system, which allows you to view all available holidays and make updates as necessary. You would check that all the holidays listed on the site are up-to-date and accurate, with correct pricing, availability, and other details. You would also monitor the inventory levels to ensure that there are enough holidays available to meet user demand, and make adjustments as necessary to avoid overbooking or underbooking. If there are any issues or discrepancies with the inventory, you would investigate and resolve them promptly, to ensure that users have a positive experience when using the site.

## Agile Methodology

Using Github projects to track user stories and organize tasks based on their level of importance is a key aspect of Agile methodology. By breaking down development into smaller, more manageable tasks, and prioritizing them based on user needs and feedback, developers can ensure that the app meets user expectations and delivers value in a timely and efficient manner. The use of Agile methodology can also help developers to adapt to changes in user requirements or market conditions, and to continuously improve the app over time based on user feedback and usage data.

* MUST HAVE
* SHOULD HAVE

By using AGILE methodology in this project I was able to deliver a site which had all required functionality and was able to give even more extra detail when going through the project.

I used GitHub projects board to create the user stories and keep track of my tasks. Here is the link to my board - [Project board](https://github.com/users/ocimar84/projects/2/views/1))

Here is also a screenshot overview

![Project](https://github.com/ocimar84/holidays/assets/79640465/e403d30a-45cc-434d-b9bd-42cfbe726837)


## CRUD functionality

Holiday Booking data with full CRUD Functionality:

**Create** - Users can create a new account and make a booking for their specific requirements. This involves creating a new record in the database that contains information about the user and their booking details, such as the date and time of the booking, the number of people in the group, and any special requests or requirements.

**Read** - Users can view their booking details in the "Manage Booking" section of the app. This involves querying the database for the relevant record(s) based on the user's login credentials or booking ID, and displaying the information in a user-friendly format.

**Update** - Users can update their booking by changing any of the details within the booking form. This involves updating the relevant record(s) in the database with the new information, and notifying the user that their changes have been saved.

**Delete** - Users can delete their booking from the database. This involves removing the relevant record(s) from the database and notifying the user that their booking has been cancelled.


## Wireframes

It's great that you're considering responsive design for smaller devices like tablets and mobile phones. Adapting the layout to stack the columns, providing a single-column navigation menu, and using a dropdown for smaller screens are all good practices for mobile responsiveness.

![image-2](https://github.com/ocimar84/holidays/assets/79640465/10a27f6a-8cdc-4cc1-97e8-8da64d8ea8e6)


![image-1](https://github.com/ocimar84/holidays/assets/79640465/179d51e4-81b5-4732-a585-f19746aedbb6)

![image](https://github.com/ocimar84/holidays/assets/79640465/b132d905-1cac-4ffb-bdfe-151b52c7fd4e)

![9f033a7b-b0c9-4aeb-bed8-921036e5b8b1](https://github.com/ocimar84/holidays/assets/79640465/0b419123-40db-4fa8-b114-0919d53f683a)

![image-4](https://github.com/ocimar84/holidays/assets/79640465/09c30b90-d7e6-4cd3-97c4-9c2b590ec7b2)

![image-3](https://github.com/ocimar84/holidays/assets/79640465/dee33e82-f441-41d7-9487-8581d03483c3)


# Features

## Header
Header based on login and sign Up and dark mode.
Login to enter your email and password.
Sign Up to register.

![image](https://github.com/ocimar84/holidays/assets/79640465/7c0d46de-bdcb-4755-8076-81d1389b4d1f)

## Hero image
A hero image, also known as a banner image or header image, refers to a large, prominent image displayed at the top of a webpage. It typically spans the full width of the page and is designed to grab the user's attention and convey the main message or theme of the website.

![image](https://github.com/ocimar84/holidays/assets/79640465/9d64a815-cb15-4e68-a8fb-3b7f674a795c)

## Login
A login tool, also known as a login form or login module, is a user interface component on a website or application that allows users to authenticate themselves and access restricted or personalized content. It typically consists of fields for entering a username or email and a password, along with a "Login" button. 

![image](https://github.com/ocimar84/holidays/assets/79640465/8ff7c958-199c-407e-a45a-eccc9cf4caf3)

## Add time off
Adding a time off booking feature to a holiday website can provide users with a convenient way to request and manage their vacation time. Here are some key considerations for implementing a time off booking feature on a holiday website:

![image](https://github.com/ocimar84/holidays/assets/79640465/c28c2200-6ccd-4fe5-8711-d02ee4bdc2f5)

## Add Department
It will add department right after the reason with the start date and end date.

![image](https://github.com/ocimar84/holidays/assets/79640465/5ec04b02-d9d3-4495-bbe1-bad43fe4f410)

## Reason
Determine the reason for requesting the holiday.

![image](https://github.com/ocimar84/holidays/assets/79640465/45d36a95-5355-4578-b0cc-1107ec306aa4)

## Start and end date
Determines the start and end date of the holiday, you cannot put the dates retroactively, before today.

![image](https://github.com/ocimar84/holidays/assets/79640465/37dd77a0-7fb3-4a13-8c35-f61db3ae8844)

## The start date is invalid
When the user enters the retroactive date he receives a message saying that it is not possible to create.

![image](https://github.com/ocimar84/holidays/assets/79640465/f89fdbd0-972c-4e0d-a3dc-41003b85092b)

## ADMIN
Django admin can manage 5 parameters User: ocimar / Pass: admin

![image](https://github.com/ocimar84/holidays/assets/79640465/d60829fc-0118-469b-87fd-6825909e7138)

## Accounts
Where the super user can delete registered emails

![image](https://github.com/ocimar84/holidays/assets/79640465/1e1789d2-c349-46ea-acfa-8cddede04cf2)

## User
Where it displays user name and email information.

![user](https://github.com/ocimar84/holidays/assets/79640465/f68bb808-2e81-49f6-aa97-eb154e2dd68a)


## Departmens
Here is where the super user can create the departments that are used in the company.

![image](https://github.com/ocimar84/holidays/assets/79640465/99d580d3-c2fc-4a52-b971-3c91d752c95a)

## Time offs
Where it shows the movement of requests created by users.

![image](https://github.com/ocimar84/holidays/assets/79640465/08829025-cd54-4c84-9a40-e5ea1f8233c3)

## Change time off
On this page there is all the information about the user's request:
* User - User name;
* Department - Which department the applicant works in;
* Holiday Start - Start date;
* Holiday end - End date;
* Hours - Amount of hours the user will spend on their holiday;
* Reason - What is the reason for requesting the holiday.

![image](https://github.com/ocimar84/holidays/assets/79640465/e19936d8-eabc-4fbd-83bf-6d514919ff1f)

## Status
To approve the basque holiday write something in the status the holiday will be approved.

![image](https://github.com/ocimar84/holidays/assets/79640465/43d7ff9a-7347-46b5-a617-b49bf4ea3177)

## Disapproval
To disapprove the holiday request, the super user just delete the request, so it will disappear from the history, For the future thinking about developing some other tool

![image](https://github.com/ocimar84/holidays/assets/79640465/398a7a73-e895-4e21-a436-3ef4fe50ee12)

![image](https://github.com/ocimar84/holidays/assets/79640465/bde72c00-0f12-4044-9bfb-475c59fbb62c)

## Future Features

* Add a button for the user to edit the holiday date.
* Allow the user to see why their request was denied.
* Improve the user experience on the website.
* Add a form if the user forgets the email receives a link with a temporary password.


# Testing

## Lighthouse
The application has been tested with Chrome Dev Tools Lighthouse Testing which tests the application for:

* Performance
* Accessibility
* Best Practices
* SEO

### Home Page
![image](https://github.com/ocimar84/holidays/assets/79640465/844af648-0374-4a63-873d-83f93d441743)

### Booking Page
![image](https://github.com/ocimar84/holidays/assets/79640465/23dd805b-efd8-4e07-bf07-bcf576984b3f)

### Adm Page
![image](https://github.com/ocimar84/holidays/assets/79640465/dbba2512-4eef-4a29-9674-b71626fd0f7f)

## HTML Validator

When running my HTML code through the [HTML Validation service](https://validator.w3.org/), I encountered a few minor errors that have now all be corrected.

This is the home page -

![HTML test ](https://github.com/ocimar84/holidays/assets/79640465/6e63ddfd-2e64-404b-8fc9-23f9cc4f50f3)

This is the main page where the user makes the request, there is an error being used in my HTML that is impossible to correct.

![image](https://github.com/ocimar84/holidays/assets/79640465/685bb775-741a-4d59-9e59-32c5d988cb97)



## CSS Validator
When running my CSS code through the [CSS Validation service](https://jigsaw.w3.org/css-validator/).

I used django-crispy-forms to improve all my layouts, I did my best to remove the error but every time I changed something it didn't work.

<img width="1408" alt="CSS test " src="https://github.com/ocimar84/holidays/assets/79640465/4f43e1a0-52eb-4ce3-8582-f8115d2bdf3b">

## JSON Validation
Valid JSON

![image](https://github.com/ocimar84/holidays/assets/79640465/c90c857a-e3ee-4c10-95b4-102656de846b)


## Python Vaildator
When running my code through the [CI Python Linter Validation](https://pep8ci.herokuapp.com/) 

![Python test ](https://github.com/ocimar84/holidays/assets/79640465/9da1371c-f96e-42ba-ad96-90b54f8528fa)

## Manual

Verify that the website loads properly without any errors.
Check that the navigation menu is displayed correctly.
Ensure that the homepage content is visible and properly formatted.
Verify that any images or media on the homepage are displayed correctly.
Search Functionality

https://docs.google.com/spreadsheets/d/14IOgHDqhm2oafJCocH2HDPnnSyy-PY2jPVagz_ujWP0/edit?usp=sharing

![image](https://github.com/ocimar84/holidays/assets/79640465/c207eeea-ed23-465b-82b2-7ec00c89c374)


# Security Features

* If a logged-in user attempts to deduce the delete URL for others' bookings, they receive a warning message. This serves as a reminder that they can only delete their own bookings and discourages unauthorized actions.
* Message failure occurs when a user tries to update a booking for a time that is already booked. This prevents double booking and ensures that each time slot is reserved for only one user.
* Users who do not own a particular booking receive a message failure when attempting to update it. This ensures that only the rightful owner can modify their bookings.
* The custom 500 error page is activated for various reasons, including when a user tries to delete a booking they do not own or when they attempt to access a non-existent booking. 
* If a user is not logged in and tries to deduce the delete URL to delete someone else's bookings, they are redirected to a custom 500 error page. This indicates that the action is not allowed and prevents unauthorized deletion of bookings.


# Credits

## Code 

* I used [this website](https://timepicker.co/?fbclid=IwAR2OiqEuDfKTM7438Gk72GFZjP0l4ze-A7aRiBSfE4FAJeH0Q8jIjk_-EcY) to make the datetime picker.
* I used [this website](https://opensource.com/article/22/12/django-send-emails-smtp) to send emails to the users.
* I used [this website](https://developers.google.com/maps/documentation/embed/get-api-key) to help me create the google maps API.
* I used [this website](https://docs.djangoproject.com/en/3.2/ref/templates/builtins/#for-empty) to help me with for loops on my_booking.html

## Images

I used the following website to get my free stock images from -

* [Pexels](https://www.pexels.com/)
* [Unsplash](https://unsplash.com/)

## Technology used

* [Django](https://www.djangoproject.com/) - Django is a popular Python-based web framework used for building web applications. It follows the Model-View-Template (MVT) architectural pattern and provides a robust set of tools and features for rapid development.
* [Bootstrap](https://getbootstrap.com/) - Bootstrap is a widely used CSS framework that provides a responsive grid system and pre-designed CSS components. It helps in creating a visually appealing and consistent user interface across different devices and screen sizes.
* [HTML5](https://en.wikipedia.org/wiki/HTML) - HTML5 is the latest version of the Hypertext Markup Language, which is used to structure the content of web pages.
* [CSS3](https://en.wikipedia.org/wiki/CSS) - CSS3 is the latest version of Cascading Style Sheets, used for styling the visual presentation of web pages.
* [JavaScript](https://www.javascript.com/) - JavaScript is a programming language that allows for interactive and dynamic elements on web pages. It is used to enhance the user experience and add functionality to the website.
* [Python](https://www.python.org/) - Python is a versatile programming language used for backend development in the Locksmith Booking system. It is the primary language used by Django.
* [Gitpod](https://www.gitpod.io/) - Gitpod is an online integrated development environment (IDE) that allows developers to write, edit, and collaborate on code in a browser-based environment.
* [GitHub](https://github.com/) - GitHub is a web-based hosting service for version control using Git. It is commonly used for hosting and managing code repositories.
* [Heroku](https://id.heroku.com/login) - Heroku is a cloud platform that allows developers to deploy, manage, and scale web applications. It is used to host the deployed version of the Locksmith Booking system.
* [CI Python Linter](https://pep8ci.herokuapp.com/) - CI Python Linter is a tool used to validate Python code and ensure code quality and adherence to coding standards.
* [HTML Validation](https://validator.w3.org/) - HTML Validation is a process of checking HTML code against standard HTML rules and specifications to ensure that it is well-formed and valid.
* [CSS Validation](https://jigsaw.w3.org/css-validator/) - CSS Validation is the process of checking CSS code for errors, syntax issues, and adherence to CSS standards.
* [JSHint Validation](https://jshint.com/) - JSHint is a tool used to validate JavaScript code and detect potential errors and code quality issues.

# Deployment

## Local deployment
To test the app locally, the terminal within VScode was used. The steps to run this:

* Start from installing the chrome extension then clicking the green gitpod button in YOUR forked repository
* Include the pip3 install -r requirements.txt
* Creating env.py
    * EMAIL_HOST_PASSWORD=<YOUR_VALUE>
    * DEFAULT_FROM_EMAIL=<YOUR_VALUE>
    * EMAIL_USERNAME=<YOUR_VALUE>
    * SECRET_KEY=<YOUR_VALUE>
    * CLOUDINARY_URL=<YOUR_VALUE>
    * DEV=TRUE
* Migrate so the database starts up python3 manage.py migrate
* Create a super user so you can make the rooms in the admin and other things  python3 manage.py createsuperuser
* Start the server python3 manage.py runserver
* Use the website as usual.

A local database was used for most of the local deployment usage, since it was necessary for the automated tests to run. However, the switch to using the production database could be easily made, in case migrations needed to be performed or otherwise. Furthermore, in the development version, DEBUG was set to False, so error messages would show.

## Create a Fork

* On GitHub.com, navigate to the repository.
* In the top-right corner of the page, click Fork.
* Select an owner for the forked repository.
* By default, forks are named the same as their upstream repositories. You can change the name of the fork to distinguish it further.
* Optionally, add a description of your fork.
* Choose whether to copy only the default branch or all branches to the new fork. For many forking scenarios, such as contributing to open-source projects, you only need to copy the default branch. By default, only the default branch is copied.
* Click Create fork.

## Production delpoyment 
Escape room is deployed to Heroku, using an ElephantSQL Postgres database. To duplicate deployment to Heroku, follow these steps:

After you have forked the project for your own, continue these steps as follows -

* You will need a Cloudinary account to host user images and static files.
* Login to [Cloudinary](https://cloudinary.com/).
* Select the 'dashboard' option.
* Copy the value of the 'API Environment variable' from the part starting cloudinary:// to the end. You may need to select the eye icon to view the full environment variable.Paste this value somewhere for safe keeping as you will need it shortly (but destroy after deployment).
* Log in to [Heroku](https://id.heroku.com/login).
* Select 'Create new app' from the 'New' menu at the top right.
* Enter a name for the app and select the appropriate region.
* Select 'Create app'.
* Select 'Settings' from the menu at the top.
* Login to [ElephantSQL](https://www.elephantsql.com/).
* Click 'Create new instance' on the dashboard.
* Name the 'plan' and select the 'Tiny Turtle (free)' plan.
* Select 'select region'.
* Choose the nearest data centre to your location.
* Click 'Review'.
* Go to the ElephantSQL dashboard and click on the 'database instance name' for this project.
* Copy the ElephantSQL database URL to your clipboard (this starts with postgres://).
* Return to the Heroku dashboard.
* Select the 'settings' tab.
* Locate the 'reveal config vars' link and select.
* Enter the following config var names and values:
* CLOUDINARY_URL: your cloudinary URL as obtained above
* DATABASE_URL: your ElephantSQL postgres database URL as obtained above
* PORT: 8000
* SECRET_KEY: your secret key
* Select the 'Deploy' tab at the top.
* Select 'GitHub' and confirm you wish to deploy using GitHub. You may be asked to enter your GitHub password.
* Find the 'Connect to GitHub' section and use the search box to locate your repo.
* Select 'Connect' when found.
* Optionally choose the main branch under 'Automatic Deploys' and select 'Enable Automatic Deploys' if you wish your deployed site to be automatically redeployed every time you push changes to GitHub.
* Find the 'Manual Deploy' section, choose 'main' as the branch to deploy and select 'Deploy Branch'.
* Your site will shortly be deployed and you will be given a link to the deployed site when the process is complete.

# Acknowledgements

A huge thanks to my mentor Malia for going through my project and helping me with any issues I had to deal with.
