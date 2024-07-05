# Fresko-63431
Fresko 63431 Java Full Stack Developer - Spring Boot - #Mini-Project - Java_Fullstack_Developer - Spring Boot

In this project, you will develop the backend for a healthcare management system application using the Spring framework.


HealthCare Service - SpringBoot
Backend
Create an API for Healthcare Service.
API Endpoints
register: (HTTP METHOD-POST)
﻿﻿Should register a user.
﻿﻿On successful registration, the response should be (message=""Registration successful"'].
﻿﻿On registration failure, the response should be {message="Password or username polic y failed"}.
signin: (HTTP METHOD-POST)
• A user should be able to sign in through this endpoint by providing their email and password.

﻿﻿On successful login, the response should be: message = "Authentication successful!", token = JWTtoken, id=user.ld};
﻿﻿On login failure, the response should be {message="Username or Password is Incorrect."}

"viewprofile/{userld}":(HTTP METHOD-
GET)
Should return the details of all users.
"editprofile/{userld}":(HTTP METHOD-
GET)
Should allow you to edit a user's profile.
"patients/register": (HTTP METHOD-POST)

﻿﻿A user should be able to register a patient through this API.
﻿﻿On successful registration, the response should be {message="Registration successful"}.
﻿﻿On registration failure, the response should be {message="Registration failure"}.
"patients/list/": (HTTP METHOD-GET)
Should return the list of all patients.
"patients/view/{ld}": (HTTP METHOD-GET)
Should return details of a specified patient ID.
"patients/delete/{ld}": (HTTP METHOD-DELETE
Should delete a specified patient ID.
"appointment/register" : (HTTP METHOD-POST)

﻿﻿Should book an appointment.
﻿﻿On successful booking, the response should be {message="Booking successful"}.
﻿﻿On booking failure, the response should be {message="Booking failure"}.
"appointment/list" : (HTTP METHOD-GET)
Should return the list of all appointments.
"/appointment/view/
{appointmentld}":(HTTP METHOD-GET)
Should return details of a specified appointment ID.
"/appointment/list/{patientid)" : (HTTP METHOD-GET)
Should return the list of all the appointments of a specified patient ID.
"/appointment/delete/
{appointmentld}": (HTTP METHOD-DELETE)

Should return the list of all the appointments of a specified patient ID.
"/appointment/delete/
{appointmentld}": (HTTP METHOD-DELETE)
Should delete a specified appointment ID.
Middleware:
Create a Middleware to validate the API calls using JSON web token (JWT).
﻿﻿'Sign in' and 'Register API' endpoints do not require Middleware.
﻿﻿If the login details are validated, send a response with the JWT as token parameter.
Steps:
﻿﻿﻿Install dependencies (project > install)
﻿﻿﻿Run application (project > run)
﻿﻿﻿Test application (Run tests)

