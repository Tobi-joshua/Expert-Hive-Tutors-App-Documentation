# Expert Hive Tutors App Documentation 📚🚀

![image](https://github.com/user-attachments/assets/b771f89b-9b69-4f97-8761-cd8a3d357bc7)

Welcome to the **Expert Hive Tutors App** documentation! This cutting-edge web application facilitates interactions between students seeking tutoring services and tutors offering their expertise. It integrates SMS notifications, a payment gateway, and a recommendation system to provide a seamless experience.

## IMPORTANT ⚠️

The actual code for this project is stored in a private repository for security and copyright reasons. If you are interested in hiring me or need to see the code for verification purposes, please feel free to reach out. I will be happy to provide access to the code upon request. Thank you for understanding!

## Overview 🌟

This documentation provides a detailed overview of the Expert Hive Tutors web application. The app includes functionalities such as posting questions, bidding for tutoring tasks, and integrating a payment gateway for secure transactions.

## 💻 Technologies Used

- **Python (Django)**: Framework for backend development.
  ![Django](https://img.shields.io/badge/Django-%23092E20?style=flat&logo=django&logoColor=white)
- **JavaScript**: Used for frontend development.
- **Swagger/OpenAPI**: For API documentation.
  ![Swagger](https://img.shields.io/badge/Swagger-%2300D1C1?style=flat&logo=swagger&logoColor=white)

## 🔌 APIs

### SMS API 📱
- **Description**: Sends timely notifications to users about bid updates, payment status, and other relevant events.

### Payment Gateway API 💳 (Flutterwave)
- **Description**: Enables seamless and secure transactions between students and tutors.

### Recommendation System API 🧠
- **Description**: Matches tutors with relevant questions based on their expertise and past performance.

### Websockets 💬
- **Description**: Facilitates real-time chat communication between students and tutors, optimizing interaction.

## 🌟 Features

### User Authentication 🔐
- Users can register as either students or tutors and securely log in to access the platform's features.
  ![image](https://github.com/user-attachments/assets/a1ca2f26-86b7-4530-9ca6-a82535603982)
  ![image](https://github.com/user-attachments/assets/e2b07779-2369-42f1-862d-f0d60a6c41c1)
  ![image](https://github.com/user-attachments/assets/ba1eb129-1610-44d8-b6e1-3277e3df7806)

### Question Posting 📝
- Students can post questions with details such as subject, level, and urgency.
  - **Student Dashboard**:
    ![image](https://github.com/user-attachments/assets/673de0ea-6048-47aa-92ed-9249004f258a)
    ![image](https://github.com/user-attachments/assets/e56a8c2d-dfb4-414a-be17-c741baff1697)
  - **Question Details Page**:
    - On page load:
      ![image](https://github.com/user-attachments/assets/971a7f29-3fc9-41e7-82ac-6f3f2c475993)
    - After modal clicked:
      ![image](https://github.com/user-attachments/assets/314cf66b-0078-42fa-880b-e6406cbcfc01)
      ![image](https://github.com/user-attachments/assets/1f195b33-1f48-4961-a730-736300d100fc)
      ![image](https://github.com/user-attachments/assets/5e647616-69d3-4e17-a0cb-767007bb9635)
      ![image](https://github.com/user-attachments/assets/c1b2dc43-41e2-4c7b-a3aa-f949476e3612)
  - **Question List Page**:
    ![image](https://github.com/user-attachments/assets/4ca312b0-bfd8-431f-a144-7d73d392517e)
    ![image](https://github.com/user-attachments/assets/b78092e6-b5c8-4134-be10-8dc09f5733d0)
  - **Recommendation Page**:
    ![image](https://github.com/user-attachments/assets/33e885dd-2e08-40b1-97ed-d56347f9c5e8)
    ![image](https://github.com/user-attachments/assets/c91167cd-bd56-4d95-acdc-c739aaac0b95)
  - **Instant Recommendations**:
    ![image](https://github.com/user-attachments/assets/4f38b064-17d8-4a08-b7c5-e21ffb9b215b)
  - **Chat with Tutor**:
    ![image](https://github.com/user-attachments/assets/8f50811a-e0fd-4e51-837d-08141c7dd09f)

### Bidding System 💬
- Tutors can view posted questions and bid for tutoring tasks by offering their services and proposing a price.
  ![image](https://github.com/user-attachments/assets/f86cc121-fb51-445b-9529-a4ba271984a1)
  ![image](https://github.com/user-attachments/assets/c3ad4de3-ceca-4c0a-b4c3-2d2f33992d69)

### Recommendation System 🧠
- Matches tutors with relevant questions to enhance efficiency and user experience.

### Payment Integration 💳
- The Flutterwave payment gateway is integrated for secure and hassle-free transactions.

### Notification System 📲
- SMS notifications keep users informed about bid updates, payment status, and other relevant events.

### Rating and Reviews ⭐
- Students can rate tutors based on their experience, providing valuable feedback for improvement.

## 🚀 Deployment

The application is deployed on **Heroku**, ensuring scalability and reliability. **Daphne** is used as the WebSocket protocol server for high-performance communication. The backend database is powered by **PostgreSQL**, with **Redis** serving as the cache for optimized performance.

## 📋 Usage

### 🎓 Students
- Register or log in to post questions, view bids from tutors, and proceed with payments for tutoring services.

### 👩‍🏫 Tutors
- Register or log in to browse available questions, place bids, and provide tutoring services.

## 🔮 Future Improvements

### Chat Functionality 💬
- Enhance real-time communication between students and tutors using Websockets.

### Advanced Analytics 📊
- Implement analytics features to provide insights into user behavior and performance metrics.

### Additional Payment Options 💵
- Integrate additional payment gateways to offer more flexibility in payment methods.

## Repository 🔗

Explore the repository and contribute to the project: [GitHub Repository Link](#)
