# UOG HelpDesk

During the summer of 2025, I was granted the opportunity to work on the development team for the Helpdesk application, created by [Stefan C. Kremer](https://www.uoguelph.ca/computing/people/stefan-kremer). I was the sole developer who worked on improving the Helpdesk codebase, with a goal of improving the developer experience. As this application is used by students and teaching staff at the University of Guelph, the codebase will not be available to the public. This README.MD file will showcase the functionalities of this web-based application. 

## What is Helpdesk?

Helpdesk is an application designed to enable students to interact with professors and teaching staff for their respective courses. Using their University of Guelph credentials, students can sign into Helpdesk to gain access to their enrolled courses. Helpdesk grants students the ability to ask questions via ticket submissions, sign up for demo appointments, and request regrades. Professors and teaching staff can use Helpdesk to answer student inquiries, view class lists, and more. This web application seeks to improve the student experience by allowing for quick access to resources and tools to aid their educational needs. 

## Technology/Tools Used
The following were used to build the Helpdesk application...

<p align="center">
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white" alt="Apache" />
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white">
</p>


## Features

The following are a list of features that have been built for use by various types of users (Students, GTA, UTA, etc.). Some features will be excluded from this documentation due to it's data sensitive nature. 

### Users

The Users feature showcases all users currently enrolled in the course, essentially a class list. This feature allows you to mimic a user's experience by replicating what the Helpdesk application looks like to them based on their user permissions. 

<img width="1440" height="674" alt="Screenshot 2025-08-06 at 9 12 36 AM" src="https://github.com/user-attachments/assets/53f8db62-bbfc-4ebd-8c27-69673d1847d9" />

### Tickets

The Tickets feature displays all currently open tickets submitted by a student. A ticket is an inquiry made by a student regarding some aspect of the course. This feature was made for teaching staff to be able to answer student questions.

<img width="1440" height="739" alt="Screenshot 2025-08-06 at 9 19 59 AM" src="https://github.com/user-attachments/assets/16e953f6-fbce-4ede-8a05-8ea3838b634b" />

### Overview

The Overview feature displays all tickets of any status for a set assignment. Teaching staff can view current and past inquiries made by students grouped by assignments. 

<img width="1440" height="672" alt="Screenshot 2025-08-06 at 9 22 21 AM" src="https://github.com/user-attachments/assets/0efa0261-e596-4109-a214-634bd0ced15c" />

<img width="1440" height="670" alt="Screenshot 2025-08-06 at 9 22 29 AM" src="https://github.com/user-attachments/assets/4547064b-b5e0-4aa9-a826-7109cd82f63f" />

### Upload

The Upload feature initializes all users within a class when given a .csv file with student data. 

<img width="1440" height="659" alt="Screenshot 2025-08-06 at 9 22 37 AM" src="https://github.com/user-attachments/assets/614378e9-ac74-4cf9-b2d9-db5a8ae67215" />

### Demos

The Demo feature displays all the available time slots for a given teaching staff. Students are able to enroll in a time slot, with their name replacing the 'TBA' text.

<img width="1440" height="660" alt="Screenshot 2025-08-06 at 9 24 09 AM" src="https://github.com/user-attachments/assets/0f3be57e-90f4-47de-8f22-abfbf8ebb1f3" />





