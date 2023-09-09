# StudyNotion: Revolutionizing Education with Interactive Learning

#### [First Let's Take a Tour of the WebSite  <--- Click Here](https://study-notion-frontent-njnx4x2hz-pankaj25ic034-satienggin.vercel.app/)
---

Welcome to StudyNotion, your gateway to a dynamic and immersive educational experience. StudyNotion is a comprehensive ed-tech platform that empowers users to create, explore, and rate educational content. Harnessing the power of the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS), StudyNotion is dedicated to:

- **Enhancing Learning**: Providing an engaging and seamless learning journey for students, making education more accessible and enjoyable.

- **Empowering Instructors**: Offering instructors a platform to showcase their expertise and connect with a global community of learners.

  ## The Home Page

  ![Home page](https://github.com/Pankajk001/StudyNotion-An-Ed-tech-Platform/assets/121424516/ea5a050d-6430-48f9-98e9-1e41f108a597)

  ---

  

Let's dive into the technical details of StudyNotion:

## System Architecture

StudyNotion boasts a client-server architecture, consisting of three core components:

- **Front-end**: Built with ReactJS for dynamic and responsive user interfaces.
- **Back-end**: Developed using NodeJS and ExpressJS for robust server-side functionality.
- **Database**: Utilizing MongoDB, a flexible NoSQL database, to store course content, user data, and more.

Explore the architecture diagram 
![Architcture Diagram](https://github.com/Pankajk001/StudyNotion-An-Ed-tech-Platform/assets/121424516/c2fe000e-ad9d-494f-9589-9a81d3dcde5a)

---


## Front-end

The StudyNotion front-end, designed using Figma, offers a clean and minimalistic interface. Check out our Figma design [here](https://www.figma.com/file/Mikd0FjHKAofUlWQSi70nf/StudyNotion_shared).

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

StudyNotion adopts a monolithic architecture, with Node.js and Express.js powering the backend. MongoDB serves as the primary database, offering flexible data storage.

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

StudyNotion's RESTful API is built with Node.js and Express.js, using JSON for data exchange. Sample endpoints include user registration, login, course retrieval, and management.

Explore our API [here](insert-link-to-api-docs).

## Deployment

We deploy StudyNotion on cloud-based services to ensure scalability and reliability:

- Front-end: Vercel
- Back-end: Render or Railway
- Media files: Cloudinary
- Database: MongoDB Atlas

## Future Enhancements

To further enhance StudyNotion, we are considering:

1. **Gamification features**: Boost engagement with badges and leaderboards (medium priority).
2. **Personalized learning paths**: Customize learning journeys (high priority).
3. **Social learning features**: Promote interaction with discussions and projects (medium priority).
4. **Mobile app**: Enhance accessibility (high priority).
5. **Machine learning-powered recommendations**: Tailor courses for users (medium to high priority).
6. **Virtual reality/augmented reality integration**: Provide immersive learning experiences (low to medium priority).

## Conclusion

StudyNotion is on a mission to revolutionize education. Our MERN stack-powered platform offers interactive learning and empowers instructors. Stay tuned for updates as we continue to develop and improve StudyNotion. Join us on this exciting journey to transform education.

Thank you for being part of our educational revolution!
