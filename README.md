# Tony Le Huynh and Johnson Wang T3A2

## Roids Fitness: MERN Full Stack Application

## Purpose

The purpose of this application is to serve as a calendar scheduling and booking system for a gym and its weekly classes. 

This application will allow gym patrons to view the weekly scheduled classes at the gym through an online calendar system, as well as make bookings for these classes. Along with this, gym staff and trainers will also be able to utilize the application to add additional classes to the calendar. 

It has been discussed with local gym business Roids Fitness to help transition their gym weekly classes system from paper to online. Developers working on this project are Johnson Wang and Tony Le Huynh. Before working with us, Roids Fitness only displayed their weekly classes on a whiteboard and sheets of paper at the gym. Gym patrons could only view the classes that were held by having to physically go to the gym to check, and could only book at the front office. By building this application, this will benefit both the gym patrons by making their customer experience much better as well as reducing workload for the staff as patrons can easily book classes online rather than having to see a staff member in person. 

Gym patrons will have their own user accounts where they can view the online gym class schedule, make bookings, as well as see a list of the classes they’ve booked for on their own dashboard. Gym staff and trainers will also have their own accounts where they can add classes as well as see a schedule of the specific classes that they’ll be hosting for the next week or fortnight. 

## Target Audience

The target audience for the application will be the patrons for the gym Roids Fitness. 

There are a wide range of demographics who attend the gym classes at Roids Fitness. According to employees, these include:

- Young teenagers between the ages 15-17
- Young adult men and women
- Middle-aged men and women
- Senior men and women

There are a variety of reasons patrons attend these classes including for health reasons as well as being a means to socialize. 

The application will need to be simple and intuitive to use so that it is easily accessible for all the gym patrons. 

## User Stories

__Core MVP features:__ 

1. As a gym patron, I want to see a clear calendar displaying the schedule of gym classes for the next few weeks, as I want to be able to make a quick decision on which class I want to attend. 
2. As a gym patron, I want to be able to easily book a class online so that I can attend this class. 
3. As a gym patron, an online dashboard showing a list of the classes I’ve booked would be really handy so that I can remember what classes I intend to attend. 
4. As a gym patron, I would like to create an account for myself and login, so that I can both book these classes as well as see a dashboard showing my details and lists of classes I’ve booked. 
5. As a gym staff member, I need to be able to add new classes to the calendar schedule so that the classes available remain up to date for our patrons to see. 


__Additional features:__


1. As a gym patron, I would like to see further details regarding the classes offered at my gym. This is so that I can make a decision on which classes I would like to attend and so that I also know if I need to bring any additional equipment (such as a yoga mat, shoes, towel etc.) to the class. 
2. As a gym patron, I would like to be able to filter the gym class schedule by types of classes and trainers. This is so that I can see specifically which classes I want to attend. 
3. As a gym staff member and trainer, I want to be able to see a roster of the specific classes that I’ll be taking for the week. This is so that I clearly know what classes I’ll be taking, and so that I can personally plan and prepare for these classes.


__After consultation with Roids Fitness__

After a second consultation with Roids Fitness regarding the plan for the features and development of the application, it was requested by the business to include additional admin/manager functionality to do things such as remove employees and classes. 

1. As a gym staff member, I want to also be able to edit or remove any classes from the schedule in case there are any changes such as a trainer no longer being available. 
2. As a gym staff member, I should be able to create my own account and login so that I can add/edit/remove classes to the schedule. 
3. As the manager and admin user, I want to be able to add and remove gym staff from the system so that the users that have access to the calendar application are up to date. 


__Further market research__

Upon some further market research of other applications and systems used by gym businesses, there were a few more aspects of functionality that could be added to the application. This would be dependent on project deadlines as well as budget. 


1. As a gym patron, I would like to be able to purchase individual PT sessions for myself as opposed to just attending classes so that I can have a one-on-one experience and guidance with my training. 
2. As a gym patron I would like to be able to update and see my details in my user account. This is so that I can keep these details up to date for my gym membership. 
3. As a gym patron, I would like to be able to purchase the products on offer at the gym online. This is so that I’m not limited to only being able to purchase these products at the gym. 
4. As a gym staff member, I want to be able to display and sell the gym’s products online. This is so that our patrons can see the fantastic products we have on offer such as supplements. 


## Functionality & Features

The core MVP features of the application will include:

1. Weekly calendar to display current available classes at the gym
2. Login + Signup account functionality for gym patrons
3. Display of a list of classes booked by the individual gym patrons, shown through a dashboard and their user account
Booking system for the classes to be utilized by gym patrons

All users will be required to be authenticated and to login via the same login page. From there, they will access their own user accounts with the functionality of gym staff and gym patrons being different. Gym patrons will be able to make bookings for classes as well as see a list of classes that they’ve currently booked, whilst gym staff will be able to create classes on the calendar schedule. 

Other additional features which can be implemented further along in the development/deployment process will include:

1. Login + Signup account functionality for admin users and gym staff
2. Adding classes to the weekly calendar (functionality available to only admin users/gym staff in the system). Classes should also be able to be edited and removed by gym staff/admin users. 
3. Booking system for gym patrons to schedule and purchase individual PT (personal training) sessions. 
4. Functionality to click on individual classes/slots in the calendar which will display further information about the class such as type of class, a short description, whether there is any required equipment to bring to class etc. This functionality can also be replaced by a dedicated section or page on the application/website which will provide a description of the classes on offer at the gym. 
5. Filtering option for the weekly calendar. Classes displayed can be filtered by aspects such as trainers, the type of class, level of difficulty etc. 

Depending on project deadlines as well as available resources and budget, these are some further features that could be implemented to add to the application:

- Section in the user dashboard to store details of the gym patron such as name, age, contact details, address, current gym membership etc. 
- Weekly roster functionality for gym staff/trainer accounts which will display the schedule of classes they are taking
- A further e-commerce section for the website for the gym to display and sell their products such as supplements and equipment

## Tech Stack

__Front-end:__ React.JS, HTML, CSS, JavaScript, Tailwind CSS

__Back-end:__ Node.js, Express.js

__Database:__ MongoDB, Mongoose

__3rd Party APIs:__ Cal.com

__Deployment:__ Netlify (Front-end), Heroku (Back-end)

__Testing:__ Jest, Mocha

__Project-management tools:__ Trello, Discord, Zoom

__Utilities:__ Draw.io, Figma

## Planning

At the start of the project, a scrum was conducted for the brainstorming of ideas and businesses to work with. During this time, a Trello board was also created where ideas would be commented on and stored on a card. Once the project idea was finalized, tasks were created and allocated on the Trello board. Each team member was responsible for completing and adding any new tasks, with the other checking each other’s work once a task was moved to the “Review” stage. 

Various stand up meetings were conducted via Discord and Zoom which served as check-ins for each team member's progress as well as an opportunity for questions. 

The order of priorities for features of the application, as well as the coding to be completed was settled on in a scrum meeting. This order of priorities to deploy the staging version of the application as soon as possible as a minimum viable product, would allow the team to have a clear vision of what to work on and in what priority. Through this, CI/CD can be followed where features will continuously be deployed to Heroku and Netlify. This will allow for consistent automatic and manual testing of the application as well as an opportunity to gain feedback from Roids Fitness for any changes to the features. 
