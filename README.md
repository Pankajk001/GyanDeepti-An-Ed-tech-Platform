# GyanDeepti: Revolutionizing Education with Interactive Learning

#### [First Let's Take a Tour of the WebSite  <--- Click Here](https://study-notion-frontent-njnx4x2hz-pankaj25ic034-satienggin.vercel.app/)
---

Welcome to GyanDeepti, your gateway to a dynamic and immersive educational experience. GyanDeepti is a comprehensive ed-tech platform that empowers users to create, explore, and rate educational content. Harnessing the power of the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS), GyanDeepti is dedicated to:

- **Enhancing Learning**: Providing an engaging and seamless learning journey for students, making education more accessible and enjoyable.

- **Empowering Instructors**: Offering instructors a platform to showcase their expertise and connect with a global community of learners.

  ## The Home Page

 ![React   Tailwind CSS Starter Pack - Google Chrome 03-05-2024 22_58_07](https://github.com/Pankajk001/GyanDeepti-An-Ed-tech-Platform/assets/121424516/ae83ba5c-1313-479a-a0de-992f87ea43ed)

)

---

  

Let's dive into the technical details of GyanDeepti:

## System Architecture

GyanDeepti boasts a client-server architecture, consisting of three core components:

- **Front-end**: Built with ReactJS for dynamic and responsive user interfaces.
- **Back-end**: Developed using NodeJS and ExpressJS for robust server-side functionality.
- **Database**: Utilizing MongoDB, a flexible NoSQL database, to store course content, user data, and more.

Explore the architecture diagram 
![Architcture Diagram](https://github.com/Pankajk001/StudyNotion-An-Ed-tech-Platform/assets/121424516/c2fe000e-ad9d-494f-9589-9a81d3dcde5a)

---


## Front-end

The GyanDeepti front-end, designed using Figma, offers a clean and minimalistic interface. Check out our Figma design [here](https://www.figma.com/file/Mikd0FjHKAofUlWQSi70nf/StudyNotion_shared).

Key Pages:

For Students:
- **Homepage**: Introduction to the platform, course list, and user details.
- **Course List**: Browse courses with descriptions and ratings.
- **Wishlist**: View saved courses.
- **Cart Checkout**: Complete course purchases.
- **Course Content**: Access course materials.
- **User Details**: Manage your account.
- **User Edit Details**: Edit account information.

For Instructors:
- **Dashboard**: Monitor courses and ratings.
- **Insights**: Gain detailed course metrics.
- **Course Management**: Create, update, and delete courses.
- **View and Edit Profile Details**: Manage your account.

For Admin (future scope):
- **Dashboard**: Overview of platform data.
- **Insights**: Detailed platform metrics.
- **Instructor Management**: Administer instructor accounts and courses.

Frameworks and libraries used:
- ReactJS
- CSS and Tailwind
- Redux for state management

---

## Back-end

GyanDeepti adopts a monolithic architecture, with Node.js and Express.js powering the backend. MongoDB serves as the primary database, offering flexible data storage.

Features and Functionalities:
1. **User authentication and authorization**: Secure login and OTP verification.
2. **Course management**: Instructors create, manage, and students rate courses.
3. **Payment Integration**: Razorpay handles course purchases.
4. **Cloud-based media management**: Cloudinary stores media content.
5. **Markdown formatting**: Markdown simplifies content display.

Frameworks, Libraries, and Tools:
- Node.js
- MongoDB
- Express.js
- JWT for authentication
- Bcrypt for password hashing
- Mongoose for ODM

Data Models and Database Schema:
- Student schema
- Instructor schema
- Course schema

  ![Modals](https://github.com/Pankajk001/StudyNotion-An-Ed-tech-Platform/assets/121424516/63446260-2903-48da-a745-308d10a6b224)

---


## API Design

GyanDeepti's RESTful API is built with Node.js and Express.js, using JSON for data exchange. Sample endpoints include user registration, login, course retrieval, and management.

#### Sample list of API endpoints and their functionalities:
1.	/api/auth/signup (POST) - Create a new user (student or instructor) account.
2.	/api/auth/login (POST) – Log in using existing credentials and generate a JWT token.
3.	/api/auth/verify-otp (POST) - Verify the OTP sent to the user's registered email.
4.	/api/auth/forgot-password (POST) - Send an email with a password reset link to the registered email.
5.	/api/courses (GET) - Get a list of all available courses.
6.	/api/courses/:id (GET) - Get details of a specific course by ID.
7.	/api/courses (POST) - Create a new course.
8.	/api/courses/:id (PUT) - Update an existing course by ID.
9.	/api/courses/:id (DELETE) - Delete a course by ID.
10.	/api/courses/:id/rate (POST) - Add a rating (out of 5) to a course.

    
#### Sample API requests and responses:
1.	GET /api/courses: Get all courses
●	Response: A list of all courses in the database
2.	GET /api/courses/:id: Get a single course by ID
●	Response: The course with the specified ID
3.	POST /api/courses: Create a new course
●	Request: The course details in the request body
●	Response: The newly created course
4.	PUT /api/courses/:id: Update an existing course by ID
●	Request: The updated course details in the request body
●	Response: The updated course
5.	DELETE /api/courses/:id: Delete a course by ID
●	Response: A success message indicating that the course has been deleted.

---

## Deployment

We deploy GyanDeepti on cloud-based services to ensure scalability and reliability:

- Front-end: Vercel
- Back-end: Render or Railway
- Media files: Cloudinary
- Database: MongoDB Atlas

---

## Future Enhancements

To further enhance GyanDeepti, we are considering:

1. **Gamification features**: Boost engagement with badges and leaderboards (medium priority).
2. **Personalized learning paths**: Customize learning journeys (high priority).
3. **Social learning features**: Promote interaction with discussions and projects (medium priority).
4. **Mobile app**: Enhance accessibility (high priority).
5. **Machine learning-powered recommendations**: Tailor courses for users (medium to high priority).
6. **Virtual reality/augmented reality integration**: Provide immersive learning experiences (low to medium priority).

---

## Conclusion

GyanDeepti is on a mission to revolutionize education. Our MERN stack-powered platform offers interactive learning and empowers instructors. Stay tuned for updates as we continue to develop and improve GyanDeepti. Join us on this exciting journey to transform education.

Thank you for being part of our educational revolution!
