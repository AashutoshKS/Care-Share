# CareShare

## Overview

CareShare is a web-based food donation management system built with Django. It facilitates the connection between food donors and organizations helping people in need, making the process of food donation more efficient and accessible.

## Project Details

- **Duration**: November 2024 - December 2024
- **Institution**: GL Bajaj Institute of Technology and Management (GLBITM)


## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Useful Links](#useful-links)
- [Contact](#contact)

## Installation

1. Install all the dependencies
   ```sh
   npm install
   ```
2. Create a file named ".env" and enter the following credentials:
   ```js
   MONGO_URI = yourmongouri;
   ```
3. Run the web application
   ```sh
   npm start
   ```
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

- **Backend**: Node.js, Express.js
- **Frontend**: HTML, CSS, JavaScript, Bootstrap, EJS
- **Database**: MongoDB

## Contributing

We welcome contributions to improve CareShare. Please follow these steps:
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

- **Name**: Ashutosh Kumar Singh
- **Email**: aashutoshkumarsingh71@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/aashutosh-kumar-singh-61b492259/

---
© 2025 CareShare. All rights reserved.
