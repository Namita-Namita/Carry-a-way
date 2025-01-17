# CARRY-A-WAY
*A web-based luggage shipping and tracking application.*

## Contributors:
* Shriyans Nidhish 
* Namita 
* Siva Praneeth 
* Bhavana Nammi 

## Problem Statement:
The current process of traveling with bulky luggage/items and dealing with high charges imposed by airlines creates inconvenience and additional financial burden for travelers. There is a need for a cost-effective and user-friendly solution that allows travelers to easily track and ship their check-in luggage/items through their preferred courier service, ensuring a hassle-free travel experience.

## About:
Carry-A-way is a web application developed using **Go and Angular**, specifically designed to address the challenges faced by travelers when it comes to carrying and shipping their belongings. The application provides users with a convenient step-by-step tracking system, enabling them to select their desired courier service and have their luggage/items picked up and delivered directly to their origin or destination doorstep. By utilizing Carry-A-way, travelers can enjoy a seamless and worry-free travel experience, without the need to carry heavy items or incur hefty charges imposed by airlines.

This project was generated with **Angular CLI version 16.0.5**

## Key Features:
* **Scheduled the pick-up and delivery:** Users can easily schedule the pick-up and delivery of their luggage/items from their origin to the destination doorstep.
* **Choice of Courier Services:** Carry-A-way enables users to select their preferred courier service provider for shipping.
* **Cost-Effective Solution:** Users can avoid the heavy charges imposed by airlines for carrying bulky luggage.
* **Step-by-Step Tracking:** Provides real-time tracking of the shipped items, allowing users to monitor their progress.
* **Messaging Enabled:** Users can communicate directly with the courier service provider through the messaging feature, ensuring effective coordination and updates.

## Installation and Execution
### Installation
* Code file: Download the folder “Carry-a-way”
* Angular: Setup angular in your system by navigating to the project and running the below command in the terminal.

### Build
* Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.
```
ng build
```
### Backend execution command
```
go run signupauth.go
```
### Frontend execution command
```
ng serve
```
* Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
```
http://localhost:4200/
```

## Technology Stack:
* Backend: Go (Golang) for server-side development
* Frontend: Angular for building the user interface
* Database: MySql
* IDE : Microsoft Visual Studio Code
* Version Control : Github repository

## Backend unit test video
https://drive.google.com/file/d/1WF6RuD6OWyeMDitoBRbAr8Ip2n5I43jH/view?usp=sharing<br/>

## Project demo video link
https://drive.google.com/file/d/1nUXVa9W_sNc6zP6JJ9hQSCA_Vx6skMJZ/view?usp=sharing

## Cypress test video link
https://drive.google.com/file/d/1P-VP8WNh6CLGMf2LLEygWaJ1OAWmq44b/view?usp=sharing

## Project Milestones:
The project has been divided into 4 sprints to build the complete system. Each sprint is a 2 weeks long sprint and are dedicated to work on different user stories.

### Sprint 1
* Setup the environment. 
* Creation of the homepage.
* Configuring all navigation links in the homepage.
* Creation of a static page explaining the working of the website.
* Testing implemented items.

### Sprint 2
* Designing and implementation of the login and signup functionality.
* Designing and implementation of the pricing functionality.
* Testing implemented items.

### Sprint 3
* Designing and implementation of the luggage booking functionality.
* Designing and implementation of the bag calculator functionality.
* Testing implemented items.

### Sprint 4
* Implementation of the tracking status update functionality.
* Implementation of the payment functionality.
* Implementation of the messaging and chat functionality.
* Testing implemented items.
## Project Snapshots:
<p align="center"><img width="416" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/ef5503fd-7092-4ce4-9fef-697ee2720ac2" style="border:1px solid black">
<br><em>Fig 1.: Snapshot of home page.</em></p>
<p align="center"><img width="436" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/e57bebc1-d482-4610-bfb3-66ced14b3262" style="border:1px solid black">
<br><em>Fig 2.: Continued snapshot of home page.</em></p>
<p align="center"><img width="418" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/dcd8c817-ecde-4f6e-ad74-fdbe4511cc14" style="border:1px solid black">
<br><em>Fig 3.: Snapshot of how it works page.</em></p>
<p align="center"><img width="547" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/d90fbe1f-5648-4f91-8337-d5d0a23baba7" style="border:1px solid black">
<br><em>Fig 4.: Snapshot of Signup form.</em></p>
<p align="center"><img width="343" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/12917c2c-6c02-4c62-b7f9-e62bf320875c" style="border:1px solid black">
<br><em>Fig 5.: Snapshot of Sign in form.</em></p>
<p align="center"><img width="468" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/90f89df7-ba82-4f12-8fef-a3e3943b799b" style="border:1px solid black">
<br><em>Fig 6.: Snapshot of Booking.</em></p>
<p align="center"><img width="468" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/eb942cca-b26a-44e8-8983-f410e3934b77" style="border:1px solid black">
<br><em>Fig 7.: Continued snapshot of Booking.</em></p>
<p align="center"><img width="468" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/5a6acaa7-4522-4d29-98a1-379786dd054c" style="border:1px solid black">
<br><em>Fig 8.: Snapshot of confirmed book with reference.</em></p>
<p align="center"><img width="468" alt="image" src="https://github.com/Namita-Namita/Carry-a-way/assets/31967922/b1da844b-585a-4f99-9efb-11933a599092" style="border:1px solid black">
<br><em>Fig 9.: Snapshot of Bag calculator.</em></p>

## Project Flowchart:
![Home Page (1)](https://github.com/Namita-Namita/Carry-a-way/assets/31967922/e2d6d907-6baa-4ab4-9b59-256812a4ac3b)


## Future Enhancements:
* **Expedited Shipping Options:** To better accommodate the needs of last-minute travelers or situations that demand swift delivery, we are looking to integrate expedited shipping options into our platform. This enhancement will provide customers with a range of rapid shipping solutions, ensuring their luggage arrives promptly when they need it most.
* **AI-Powered Chatbot:** To improve our customer service offering and provide immediate, round-the-clock support, we are planning on deploying an AI-powered chatbot. This feature will help address customer queries instantly, guide users through our platform, and provide real-time troubleshooting, creating a seamless customer experience at all hours.
* **UI Upgrade:** We believe in delivering an exceptional user experience that is both functional and aesthetically pleasing. To this end, we are planning a comprehensive overhaul of our application's user interface. Our aim is to make it more intuitive, visually appealing, and user-friendly, enhancing overall user interaction with our platform.
* **Improved Order Completion Process:** To make the order completion process more efficient, we are working on an improved system for generating order numbers and barcodes. This feature will allow for more streamlined tracking and handling of shipments, providing customers with immediate and accurate updates about their luggage status.


