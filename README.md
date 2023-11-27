Azure-documentation
=======================

 ## Purpose

We were recently approached by a client; an owner of a freshly renovated aquatic centre, Azure Splash. Due to the high volume of patrons, the centre has had to implement mandatory reservations for each pool lane. There are currently two pools with a total of 6 lanes per pool. At the moment, the only way to reserve a lane is via phone or in-person as the facility does not have a website.This has led to multiple customers walking-in and unable to go for a swim, leaving them unsatisfied and resulting in customers visiting a competitor or worse yet, not continuing their patronage. Further, it was keeping staff tied to the phones in order to keep up with reservations, and preventing them from fulfilling their other duties.

The goal for this web application is to enable users to make a booking for available lanes in the allocated time slots. The slots are for half an hour, and each customer can reserve a maximum of two consecutive slots. This will allow customers to be guaranteed a lane, and for staff to be freed up with assisting customers in the venue. In the future, they would like to expand their services by adding a sauna. As such, a ‘coming soon’ booking space for this will be displayed on the web application. This will also enable the centre to introduce other services, such as swimming classes in the future.

The web application will also promote the business by showing off the brand new facilities, as well as the competitive prices. It will also encourage users to create an account, to view availability and make bookings as this will be unavailable to users without an account.The overarching goal is to ensure that the pool is always booked, hence guaranteeing customers a lane when they turn up for a swim. 




## Functionality & Features

 #### Browsing (non-member)
- The user will be able to:
- View all the services available at the centre
- Send enquiries with the ‘contact us’ form
- View opening hours and contact details
- View pricing
- Create an account

#### Browsing (logged-member - Customer)
- The user will be able to:
- View all the services available at the centre
- Send enquiries with the ‘contact us’ form
- View opening hours and all contact details
- View pricing
- View bookings page
- View lane availability
- Create/view/cancel their own bookings 
- View own profile

#### Browsing (logged in member - Workers)
- The user will be able to:
- View all the services available at the centre
- Send enquiries with the ‘contact us’ form
- View opening hours and contact details
- View pricing
- View bookings page
- View lane availability
- Create/view/cancel all bookings 
- View all profiles
- Create new Customer profiles

#### Browsing (logged in member- Admin)
- The user will be able to:
- View all the services available at the centre
- Send enquiries with the ‘contact us’  form
- View opening hours and contact details
- View/edit pricing
- View bookings page
- View/edit/delete lane availability
- Create/view/cancel all bookings 
- View all profiles
- Create new profiles(admin, worker, customer)
- Create/edit/delete services


### Target Audience

The application will be aimed at everyone that enjoys swimming of all experience levels, working or living in the local area. Further, there will be emphasis on future growth of the business and expansion of services that can be expected in the near future, such as swimming classes for all ages. 

The application will be designed with user experience in mind, as the pools are expected to be used by people of all ages. This will mean that the application will cater to both tech-savvy users and those less familiar with technology.




### Tech Stack

- **Frontend:** HTML5, CSS, REACT.JS, JavaScript
- **Backend:** Node, Express.JS
- **Database:** Mongo. Mongoose
- **Deployment:** Heroku (backend), Netlify (frontend)
- **Project Management Tools:** Discord, Trello
- **Utilities:** draw.io, Lucidchart, Figma
- **DevOps:** Github, VS Code

## Data Flow Diagram

## Application Architecture Diagram

The application architecture diagram displays the structure of the Azure Splash app, and the flow of data. The application is made up of three components: frontend, backend and database.

![Screenshot 2023-11-26 222905](https://github.com/Azure-Splash/Azure-documentation-/assets/126572960/0da3a3a7-3ba7-41f5-8a01-ec72bff17590)

## User Stories

### Admin 

As an admin, I want to be able to view all bookings so that I may be prepared and organised for current and upcoming bookings.

As an admin, I want to block lanes and time slots for maintenance to ensure that the facility is able to undergo any required upkeep with minimal disruptions.

As an admin, I want to create and manage the bookings for additional spaces, so that I may expand the services offered to customers online.

As an admin, I want to be able to create time slots and lanes to effectively manage the availability of the aquatic centre. 

### Customer

As a customer, I want to book a lane in a specific time slot to ensure that I am able to swim, regardless of the number of customers in the aquatic centre.

As a customer, I want to be able to view available times and lanes to ensure that there are no conflicts, whilst effectively choosing the best option. 

As a customer, I would like to edit or delete my own bookings  in the case of any changes in my schedule.


### Worker

As a worker, I want to delete and edit any booking to ensure that I’m able to assist customers with their requests.

As a worker, I would like to see available times and lanes to assist customers with their bookings.

As a worker, I would like to be able to see relevant information regarding maintenance so that I may provide warnings to customers and evacuate the areas if necessary. 


## Wireframes

Figma was used to create wireframes for this project. We decided to use image and full color instead of placeholder images. This will allow quicker approval from the client. After discussions with the owner of Azure Splash, we worked out that most of the users will be using a mobile device. With this in mind we decided to take a mobile first approach to the design. 

### Design Features

#### Color Scheme
![Website colors](/resources/color_scheme.png)

### Buttons

The buttons will be designed with a a slight rounded corner on a rectangle. The standard button will have Azure as a color with black text. Using OnHover the button will change to lighter color, text will be capitalized and white.

![Button examples](/resources/buttons.png)

### Nav Bar

The Nav Bar will be sticky at the top of the page making the menu accessible when scrolling the content on each page. The same color format then the buttons will be used on the Nav Bar. This will keep the site looking uniform and helping the user navigate the site easier.

![Navbar examples](/resources/navbar.png)

### Mobile Design

*** 

#### Home & About Us Pages

<img  alt="mobile wireframe"  height="500px" width="500px" src="./resources/mobile_home.png" />
<img  alt="mobile wireframe" height="500px" width="500px" src="./resources/mobile_about.png" />

#### Services & Contact Pages

<img  alt="mobile wireframe"  height="500px" width="500px" src="./resources/mobile_services.png" />
<img  alt="mobile wireframe" height="500px" width="500px" src="./resources/mobile_contact.png" />

#### Login & Register Pages

<img  alt="mobile wireframe"  height="500px" width="500px" src="./resources/mobile_login.png" />

#### Bookings Pages

<img  alt="mobile wireframe"  height="500px" width="500px" src="./resources/mobile_bookings.png" />
<img  alt="mobile wireframe"  height="500px" width="500px" src="./resources/mobile_bookings1.png" />

### Desktop & Tablet

***
#### Home & About Us Pages
#### Services & Contact Pages
#### Login & Register Pages
#### Bookings Pages












## Project Management


