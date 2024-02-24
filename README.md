# Cloud Computing End-Semester Project: Microservices-based Photo Gallery Application

This repository contains the implementation of a comprehensive end-semester project for the Cloud Computing course. The project involves developing a microservices-based photo gallery application using the MERN stack (MongoDB, Express.js, React.js, Node.js) and deploying it on Google Cloud Platform (GCP) with Kubernetes.

## Project Description

The goal of the project is to create a scalable and efficient photo gallery application with the following features:

1. **User Accounts Management**: Implement user authentication and authorization using relational databases or NoSQL. This includes identity management as a separate microservice named UserAccMgmtServ.

2. **Storage Management**: Allocate 10MB of cloud storage to each user for storing photos. Implement a microservice named StorageMgmtServ to track user storage usage and generate alerts when storage reaches a certain threshold.

3. **Usage Monitoring**: Monitor user activity and track data volume usage. Alert users when they exceed specific usage limits (e.g., 25MB per day). Develop a microservice named UsageMntrServ for usage monitoring.

4. **View Generation**: Create an intuitive and visually appealing user interface (UI) to display photos. Implement a microservice named ViewGeneratorServ to interact with other microservices and generate the UI.

5. **Additional Microservices**: Develop additional microservices such as Controller and Model microservices to facilitate the proper functioning of the application.

6. **Load Testing**: Perform load testing to determine the application's scalability and performance under various load conditions. Utilize automated load testing tools to simulate concurrent user access and monitor system behavior.

7. **Logging**: Implement logging functionality to monitor user activities and system events. Store logs centrally using an appropriate logging microservice.

## Technologies Used

- **Frontend**: React.js, HTML, CSS, JavaScript, client/server-side libraries 
- **Backend**: Node.js, Express.js
- **Database**: MongoDB 
- **Cloud Storage**: Cloudinary 
- **Deployment**: Google Cloud Platform (GCP), Kubernetes
- **Additional Libraries**: Redux Toolkit, React Router, Axios, React Toastify

## Project Setup

1. **Clone Repository**: Clone this repository to your local machine.
   ```bash
   git clone https://github.com/Hassaan-Qaisar/Photo-Gallery
   ```

2. **Install Dependencies**: Install dependencies for both frontend and backend.
   ```bash
   cd frontend
   npm install

   cd ../microservices
   npm install
   ```

3. **Configuration**: Configure environment variables, database connections, and cloud storage settings as per the provided instructions.

4. **Run Application**: Start the frontend and backend servers.
   ```bash
   # Start frontend server
   cd frontend
   npm start

   # Start backend server
   cd ../microservices
   npm run dev
   ```

5. **Access Application**: Access the photo gallery application via the provided URL. Register/login to explore the features and functionalities.

## Contributors

- Hassaan Qaisar
- Yasir Ghaffar
- AbuBakr Javed
- Rana Mahad

## Acknowledgements

Special thanks to Sir Qaisar Riaz for providing the project requirements and guidance throughout the development process.
