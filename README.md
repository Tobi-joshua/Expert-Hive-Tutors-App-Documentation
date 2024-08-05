Note on Code Repository
IMPORTANT: The actual code for this project is stored in a private repository for security and copyright reasons. If you are interested in hiring me or need to see the code for verification purposes, please feel free to reach out. I will be happy to provide access to the code upon request. Thank you for understanding!


🚀 Expert-Hive-Tutors-App-Documentation
Cutting-edge web app for Expert Hive Freelance Services. Built with Python (Django) &amp; JavaScript, integrating SMS, Payment Gateway, and Recommendation System APIs.

![image](https://github.com/user-attachments/assets/cb07f33f-90d3-4075-bbd3-fe43d5fcf22d)

### Overview 

This documentation provides a detailed overview of the Expert Hive Tutors web application. The app serves as a platform for facilitating interaction between students seeking tutoring services and tutors offering their expertise. Its robust feature set includes functionalities such as posting questions, bidding for tutoring tasks, and integrating a payment gateway for secure transactions.

## 💻 Technologies Used

 - Python (Django framework): Leveraged for backend development, providing a solid foundation for the application's structure and logic.
 - JavaScript: Used for frontend development to create dynamic and interactive user interfaces.

## 🔌 APIs:

### SMS API (for notifications):
 - Implemented to send timely notifications to users regarding bid updates, payment status, and other relevant events.
### Payment Gateway API (Flutterwave): 
 - Integrated to enable seamless and secure transactions between students and tutors.
### Recommendation System API : 
 - Utilized to match tutors with relevant questions based on their expertise and past performance.
### Websockets: 
 - Employed for chat communication between students and tutors, optimizing interaction and reducing reliance on external services.

## 🌟 Features
### User Authentication: 

 - Users can register as either students or tutors and securely log in to access the platform's features.
  ![image](https://github.com/user-attachments/assets/a1ca2f26-86b7-4530-9ca6-a82535603982)
![image](https://github.com/user-attachments/assets/e2b07779-2369-42f1-862d-f0d60a6c41c1)
![image](https://github.com/user-attachments/assets/ba1eb129-1610-44d8-b6e1-3277e3df7806)


### Question Posting: 
 -- Students can post questions they need help with, providing details such as subject, level, and urgency.
 
 Student Dashboard:
 ![image](https://github.com/user-attachments/assets/673de0ea-6048-47aa-92ed-9249004f258a)
 ![image](https://github.com/user-attachments/assets/e56a8c2d-dfb4-414a-be17-c741baff1697)


Question Details Page:
On page Load:
![image](https://github.com/user-attachments/assets/971a7f29-3fc9-41e7-82ac-6f3f2c475993)

After Modal Clicked:
![image](https://github.com/user-attachments/assets/314cf66b-0078-42fa-880b-e6406cbcfc01)

![image](https://github.com/user-attachments/assets/1f195b33-1f48-4961-a730-736300d100fc)

![image](https://github.com/user-attachments/assets/5e647616-69d3-4e17-a0cb-767007bb9635)

![image](https://github.com/user-attachments/assets/c1b2dc43-41e2-4c7b-a3aa-f949476e3612)

Question List Page (This is added for student so that they can easily track the ongoing questions(paid or unassigned)
![image](https://github.com/user-attachments/assets/4ca312b0-bfd8-431f-a144-7d73d392517e)

![image](https://github.com/user-attachments/assets/b78092e6-b5c8-4134-be10-8dc09f5733d0)

After the question is posted, the student will be redirected to the Recommendation page:
![image](https://github.com/user-attachments/assets/33e885dd-2e08-40b1-97ed-d56347f9c5e8)

![image](https://github.com/user-attachments/assets/56427799-d3b7-4e21-be05-2a11d7c98766)

The received an instant recommendation once bids are received!:
![image](https://github.com/user-attachments/assets/4f38b064-17d8-4a08-b7c5-e21ffb9b215b)

They have the chance to chat with the tutor before selecting them:
![image](https://github.com/user-attachments/assets/8f50811a-e0fd-4e51-837d-08141c7dd09f)



### Bidding System: 
 - Tutors can view posted questions and bid for tutoring tasks by offering their services and proposing a price.
### Recommendation System: 
 - Utilizes a recommendation system to match tutors with relevant questions, enhancing efficiency and user experience.
### Payment Integration: 
 - The Flutterwave payment gateway is seamlessly integrated to enable secure and hassle-free transactions between students and tutors.
### Notification System: 
 - SMS notifications keep users informed about bid updates, payment status, and other relevant events, ensuring timely communication.
   -- ![image](https://github.com/Tobi-joshua/Expert-Hive-Tutors-App-Documentation/assets/62856830/46106e9d-fe41-4c90-8974-5328bfd12591)
   -- ![image](https://github.com/Tobi-joshua/Expert-Hive-Tutors-App-Documentation/assets/62856830/43f597ca-7f89-4850-8c08-962ea09a2fb9)

### Rating and Reviews: 
 - Students can rate tutors based on their tutoring experience, providing valuable feedback for continuous improvement.

## 🚀 Deployment
The application is deployed on Heroku, a cloud platform as a service (PaaS), ensuring scalability and reliability. Additionally, Daphne is utilized as the WebSocket protocol server, providing high-performance communication capabilities. The backend database is powered by PostgreSQL, offering robust data management, with Redis serving as the cache for optimizing performance.

## 📋 Usage
### 🎓 Students:
  - Register or log in to post questions, view bids from tutors, and proceed with payments for tutoring services.
    
###  Tutors:
  - Register or log in to browse available questions, place bids, and provide tutoring services to students.

## 🔮 Future Improvements
In addition to the existing features, potential future enhancements include:

### Chat Functionality: 
  - Further leveraging Websockets for enhanced real-time communication between students and tutors.
### Advanced Analytics: 
  - Implementing analytics features to provide insights into user behavior and performance metrics.
### Additional Payment Options: 
  - Integrating additional payment gateways to offer users more flexibility in payment methods.
