# StudyNotion - An Ed-Tech Platform

## Introduction
StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content. The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

## System Architecture
The StudyNotion ed-tech platform consists of three main components:
- **Front-end** (Client-side)
- **Back-end** (Server-side)
- **Database** (Data Storage)

### Front-end
The front end of StudyNotion is built using ReactJS, allowing for dynamic and responsive user interfaces. It communicates with the back end via RESTful API calls. The UI design is created using Figma.

#### Features:
**For Students:**
- **Homepage:** Introduction to the platform with links to course list and user details.
- **Course List:** Displays available courses with descriptions and ratings.
- **Wishlist:** Contains courses saved by the student.
- **Cart Checkout:** Enables course purchase.
- **Course Content:** Displays course videos and materials.
- **User Details:** Shows student's account information.
- **User Edit Details:** Allows editing of student account details.

**For Instructors:**
- **Dashboard:** Provides an overview of courses, ratings, and feedback.
- **Insights:** Shows analytics such as views, clicks, and other metrics.
- **Course Management Pages:** Enables course creation, updates, and deletions.
- **View/Edit Profile Details:** Allows instructors to update their account information.

### Back-end
The back end of StudyNotion follows a **monolithic architecture**, where all application modules are combined into a single codebase for better control, security, and performance. It is built using:
- **Node.js** (JavaScript runtime)
- **Express.js** (Web application framework)
- **MongoDB** (NoSQL database for flexible and scalable data storage)

#### Features:
- **User authentication and authorization:** Supports email/password login, OTP verification, and password reset functionality.
- **Course management:** Instructors can create, update, delete, and manage course content.
- **Payment Integration:** Students can purchase courses using Razorpay.
- **Cloud-based media management:** Uses Cloudinary for storing images, videos, and documents.
- **Markdown support:** Course documents are stored in Markdown format for better rendering.

### Database
MongoDB is used as the primary database, allowing for flexible and scalable data storage.

#### Data Models:
- **Student Schema:** Stores student details such as name, email, password, and enrolled courses.
- **Instructor Schema:** Stores instructor details including name, email, password, and their courses.
- **Course Schema:** Includes course name, description, instructor details, and media content.

## Technologies Used
- **Front-end:** ReactJS
- **Back-end:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token)
- **Security:** Bcrypt (for password hashing)
- **Media Management:** Cloudinary
- **Payment Gateway:** Razorpay

## Conclusion
StudyNotion is a robust and scalable ed-tech platform with a focus on security, reliability, and user experience. Built using modern web technologies, it provides a seamless learning environment for students and an efficient teaching platform for instructors.


