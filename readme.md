CareShare

## Overview

CareShare is a web-based food donation management system built with Django. It facilitates the connection between food donors and organizations helping people in need, making the process of food donation more efficient and accessible.

## Project Details

- *Live Link*: https://care-share.onrender.com/
- *Duration*: November 2024 - February 2025
- *Institution*: GL Bajaj Institute of Technology and Management (GLBITM)

## Installation

1. Install all the dependencies
   npm install
   
2. Create a file named ".env" and enter the following credentials:
   MONGO_URI = yourmongouri;
   
3. Run the web application
   npm start
   
4. Open http://localhost:5000
5. You need to first signup and then login to run the application.

## Features

- User-friendly interface for donors and recipient organizations
- Secure authentication system
- Efficient food donation management
- Real-time tracking of donations
- Community engagement features

### Donor Features

- Donors make the donation request for food with basic details.
- Donors' donation requests can be accepted or rejected and the status can be easily tracked by them.
- Donors can view their current incomplete donations (if any).
- Donors can also view all their past donations.
- Donors can update their profile.

### Admin Features

- Admins receive all the requests made by donors.
- Admins can accept or reject the donation requests depending upon the details provided by a donor.
- If accepted, admins can assign an agent to a donation for collecting donation from the donor's home.
- Admins can view all the pending donations along with status.
- Admins can view all the donations that they have received.
- Admins can also view all the agents in the application.
- Admins can update their profile.

### Agent Features

- Agents will receive notifications from admins to collect food from donor's homes.
- Agents can mark their collection upon collection of food from donor's home.
- Agents can also view all those food donations which have been collected by them previously.
- Agents can update their profile.

## Technologies Used

- *Backend*: Node.js, Express.js
- *Frontend*: HTML, CSS, JavaScript, Bootstrap, EJS
- *Database*: MongoDB

## Contact

- *Name*: Akshay Gupta
- *Email*: akshay.gupta.1018@gmail.com
