# Edu_Bond: Peer-to-Peer Learning Platform

## Overview

Edu_Bond is an innovative e-learning platform that democratizes education by providing free access to high-quality courses and learning materials. Unlike traditional platforms that offer pre-existing courses, Edu_Bond focuses on peer-to-peer learning, enabling students to connect with friends online, share knowledge, and collaborate on learning materials. Additionally, Edu_Bond ensures secure access through email verification via OTP during the login process.

## Key Features

- **Peer-to-Peer Learning**: Connect with friends and share learning materials directly.
- **Free Access**: All learning materials and courses are available at no cost.
- **File Sharing**: Easily share files, notes, and links with your friends.
- **Chat Functionality**: Communicate and collaborate in real-time with your learning partners.
- **Email Verification**: Secure login process with OTP-based email verification.

## Tech Stack

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
     EMAIL_SERVICE=your_email_service
     EMAIL_USER=your_email_user
     EMAIL_PASS=your_email_password
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
