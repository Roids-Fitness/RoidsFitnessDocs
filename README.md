# Tony Le Huynh and Johnson Wang T3A2

[Github repo link](https://github.com/Roids-Fitness/RoidsFitnessDocs)

## *Roids Fitness: MERN Full Stack Application*

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

## Project Management Tools
Kanban is a project management tool used to visualise progress and encourages steady output. It is a board where tasks are listed on cards and moved along the board until it reaches the “Done” column.

The project would follow an Agile framework where work is outputted in weekly cycles of planning, implementation, review and retrospectives. Within each week, a meeting is held with the stakeholders to discuss the project progress and the Kanban board is re-populated with new tasks that need to be completed for the week. Ideally at the end of each week, all the tasks specified for that week would be in the “Done” section.

The Kanban board would be created in Trello in the following [link](https://trello.com/invite/b/7ynXsY0G/ATTIad1612a188a0b08b5e2f737cda51edb54F40A231/trello-board). This platform would be used to delegate, provide updates and give feedback on a particular task. On top of that, daily stand up meetings were conducted via Discord and Zoom which served as check-ins for each team member's progress as well as an opportunity for questions..

At the start of the project, a scrum was conducted for the brainstorming of ideas and businesses to work with. During this time, a Trello board was also created where ideas would be commented on and stored on a card. Once the project idea was finalized, tasks were created and allocated on the Trello board. Each team member was responsible for completing and adding any new tasks, with the other checking each other’s work once a task was moved to the “Review” stage.

__Trello Board at project start:__
![Trello Board 1](docs/Trello%20Board%20(1)%20.png)

__Trello Board at project part A end:__
![Trello Board 2](docs/Trello%20Board%20(2).png)

Below is a close look at a card that has utilised quite a few functionality on Trello (highlighted with numbers):
1. Clearly defined title of the task
2. The assigned members to the card
3. Label specifying the type of task in relation to the project
4. The expected completion date for the card
5. Brief description or information related to the task
6. Checklist to help with completion of the task
7. Comment section where updates and feedback are provided

![Trello Card](docs/Trello%20Card.png)

## Dataflow Diagram

Below diagram shows the flow of data within the application related to user processes.

![Dataflow Diagram](docs/Dataflow%20Diagram.png)

## Application Architecture Diagram 

Below diagram shows the tech stack related to this application and how they interact to serve client's browser.

![Application Architecture Diagram](docs/Application%20Architecture%20Diagram.png)

This diagram is a more detailed look at what data is served on each web page of the application along with navigation at the frontend.

![Application Architecture Diagram1](docs/Application%20Architecture%20Diagram1.png)

## Wireframes

__Homepage__

This is the homepage of the application. There is an image slideshow that show various exercises and classes available in the gym.

Desktop:
![Homepage Desktop](docs/Home%20Page%20(Desktop).png)

Mobile:

![Homepage Phone](docs/Home%20Page%20(Phone).png)

__Login Page__

Simple form component for users to sign in.

Desktop:
![Login Page Desktop](docs/Login%20Page%20(Desktop).png)

Mobile:

![Login Page Phone](docs/Login%20Page%20(Phone).png)

__Register Page__

Simple form component for users to register a new account.

Desktop:
![Register Page Desktop](docs/Register%20Page%20(Desktop).png)

Mobile:

![Register Page Phone](docs/Register%20Page%20(Phone).png)

__Calendar Page__

Page with calendar functionality showing the class schedule for the gym. Users do not have to login to view this page except there are filter options dor "All" and "My Classes" for logged in users. Classes that are in the past, would not be able to be signed up.

Desktop:
![Calendar Page Desktop](docs/Calendar%20Page%20(Desktop).png)

Mobile:

![Calendar Page Phone](docs/Calendar%20Page%20(Phone).png)

__Class Details Page__

Page that will open up when user clicks on a class. It will display the details of the class as well as an option to book to attend the class.

Desktop:
![Class Details Page Desktop](docs/Class%20Details%20Page%20(Desktop).png)

Mobile:

![Class Details Page Phone](docs/Class%20Details%20Page%20(Phone).png)

__Confirmation Page__

Page that will display confirmation of the user's booking for the class.

Desktop:
![Confirmation Page Desktop](docs/Confirmation%20Page%20(Desktop).png)

Mobile:

![Confirmation Page Phone](docs/Confirmation%20Page%20(Phone).png) 

__Add Class Page__

Feature available only to admin users/gym employees where they will be able to add new classes which will be displayed on the gym class schedule calendar.

Desktop:
![Add Class Page Desktop](docs/Add%20Class%20Page%20(Desktop).png)

Mobile:

![Add Class Page Phone](docs/Add%20Class%20Page%20(Phone).png)

## Tech Stack

__Front-end:__ React.JS, HTML, CSS, JavaScript, Tailwind CSS

__Back-end:__ Node.js, Express.js

__Database:__ MongoDB, Mongoose

__3rd Party APIs:__ Cal.com

__Deployment:__ Netlify (Front-end), Heroku (Back-end)

__Testing:__ Jest, Mocha

__Project-management tools:__ Trello, Discord, Zoom

__Utilities:__ Draw.io, Figma