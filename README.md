# Expert-Hive-Tutors-App-Documentation
Cutting-edge web app for Expert Hive Freelance Services. Built with Python (Django) &amp; JavaScript, integrating SMS, Payment Gateway, and Recommendation System APIs.

![image](https://github.com/Tobi-joshua/Expert-Hive-Tutors-App-Documentation/assets/62856830/a5fc97d6-5f7f-47b9-9956-e716a46bc9f5)
![image](https://github.com/Tobi-joshua/Expert-Hive-Tutors-App-Documentation/assets/62856830/89926f0b-6c50-49e0-b0ad-f754a382953b)
![image](https://github.com/Tobi-joshua/Expert-Hive-Tutors-App-Documentation/assets/62856830/51707a74-5c34-4b4c-987f-50ba65c9bbef)

### Overview 
This documentation provides a detailed overview of the Expert Hive Tutors web application. The app serves as a platform for facilitating interaction between students seeking tutoring services and tutors offering their expertise. Its robust feature set includes functionalities such as posting questions, bidding for tutoring tasks, and integrating a payment gateway for secure transactions.

## Technologies Used
Python (Django framework): Leveraged for backend development, providing a solid foundation for the application's structure and logic.
JavaScript: Used for frontend development to create dynamic and interactive user interfaces.

## APIs:

### SMS API (for notifications): Implemented to send timely notifications to users regarding bid updates, payment status, and other relevant events.
### Payment Gateway API (Flutterwave): Integrated to enable seamless and secure transactions between students and tutors.
### Recommendation System API (if applicable): Utilized to match tutors with relevant questions based on their expertise and past performance.
### Websockets: Employed for chat communication between students and tutors, optimizing interaction and reducing reliance on external services.

## Features
### User Authentication: Users can register as either students or tutors and securely log in to access the platform's features.
### Question Posting: Students can post questions they need help with, providing details such as subject, level, and urgency.
### Bidding System: Tutors can view posted questions and bid for tutoring tasks by offering their services and proposing a price.
### Recommendation System: Utilizes a recommendation system to match tutors with relevant questions, enhancing efficiency and user experience.
### Payment Integration: The Flutterwave payment gateway is seamlessly integrated to enable secure and hassle-free transactions between students and tutors.
### Notification System: SMS notifications keep users informed about bid updates, payment status, and other relevant events, ensuring timely communication.
### Rating and Reviews: Students can rate tutors based on their tutoring experience, providing valuable feedback for continuous improvement.

## Deployment
The application is deployed on Heroku, a cloud platform as a service (PaaS), ensuring scalability and reliability. Additionally, Daphne is utilized as the WebSocket protocol server, providing high-performance communication capabilities. The backend database is powered by PostgreSQL, offering robust data management, with Redis serving as the cache for optimizing performance.

## Usage
### Students:
Register or log in to post questions, view bids from tutors, and proceed with payments for tutoring services.

### Tutors:
Register or log in to browse available questions, place bids, and provide tutoring services to students.

## Future Improvements
In addition to the existing features, potential future enhancements include:

### Chat Functionality: Further leveraging Websockets for enhanced real-time communication between students and tutors.
### Advanced Analytics: Implementing analytics features to provide insights into user behavior and performance metrics.
### Additional Payment Options: Integrating additional payment gateways to offer users more flexibility in payment methods.
