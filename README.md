# Edu_Bond: Your Free Online Learning Companion

## Overview

Edu_Bond is an innovative e-learning platform designed to democratize education by making high-quality courses and learning materials accessible to everyone, completely free of cost. Unlike traditional e-learning platforms that offer pre-existing courses, Edu_Bond focuses on peer-to-peer learning, where students can connect with friends online, share knowledge, and collaborate on learning materials.

## Key Features

- **Peer-to-Peer Learning**: Connect with friends and share learning materials directly.
- **Free Access**: All learning materials and courses are available at no cost.
- **File Sharing**: Easily share files, notes, and links with your friends.
- **Chat Functionality**: Communicate and collaborate in real-time with your learning partners.

## Mission

The primary goal of Edu_Bond is to make education accessible to all, especially those who cannot afford expensive courses. By leveraging the power of peer-to-peer learning, we aim to create a community where knowledge is freely shared and everyone has the opportunity to learn and grow.

## Tech Stack

Edu_Bond is built using a combination of modern technologies to ensure a robust and scalable platform. Here are the key components of our tech stack:

### Frontend

- **React.js**: A JavaScript library for building user interfaces.
- **Redux**: A state management library for managing application state.
- **Material-UI**: A popular React UI framework for building beautiful interfaces.
- **Socket.io**: For real-time communication and chat functionality.

### Backend

- **Node.js**: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: A minimal and flexible Node.js web application framework.
- **Sequelize**: An ORM (Object-Relational Mapping) for Node.js to interact with the database.
- **JWT (JSON Web Tokens)**: For secure authentication and authorization.

### Database

- **PostgreSQL**: An open-source relational database management system.

### Deployment

- **Docker**: For containerization and consistent development environments.
- **GitHub Actions**: For continuous integration and deployment (CI/CD).

## Getting Started

### Prerequisites

- **Node.js**: Ensure you have Node.js installed. You can download it from [Node.js](https://nodejs.org/).
- **Git**: Ensure you have Git installed. You can download it from [Git](https://git-scm.com/).
- **PostgreSQL**: Ensure you have PostgreSQL installed and running.
- **Docker**: Ensure you have Docker installed. You can download it from [Docker](https://docker.com/).

### Cloning the Repository

1. Open your terminal or command prompt.
2. Clone the repository using the following command:

   ```bash
   git clone https://github.com/ManoharAI/Edu_Bond.git
   ```

3. Navigate to the project directory:

   ```bash
   cd Edu_Bond
   ```

### Setting Up the Project

1. **Install Dependencies**:
   - Navigate to the project directory if you haven't already.
   - Install the required dependencies using npm:

     ```bash
     npm install
     ```

2. **Environment Configuration**:
   - Create a `.env` file in the root directory of the project.
   - Add the necessary environment variables. Here is an example:

     ```env
     PORT=3000
     DB_HOST=localhost
     DB_USER=root
     DB_PASSWORD=yourpassword
     DB_NAME=edubond
     JWT_SECRET=your_jwt_secret
     ```

3. **Database Setup**:
   - Ensure your PostgreSQL database is running.
   - Run the database migrations to set up the necessary tables:

     ```bash
     npm run migrate
     ```

### Running the Project

1. **Start the Development Server**:
   - Run the following command to start the development server:

     ```bash
     npm start
     ```

   - The server will start on the port specified in your `.env` file (default is `3000`).

2. **Access the Application**:
   - Open your web browser and navigate to `http://localhost:3000` to access the application.

## Contribution

Edu_Bond is a team project, and we welcome contributions from developers, educators, and learners alike. If you are interested in contributing to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and commit them.
4. Open a pull request and describe your changes.

## Contact Us

For any questions or feedback, feel free to reach out to us at [contact@edubond.com](mailto:contact@edubond.com).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for your interest in Edu_Bond. Together, we can make education accessible to everyone, everywhere.
