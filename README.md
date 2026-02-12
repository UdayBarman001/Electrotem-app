# Electrotem App

## Overview
The Electrotem App is a project developed using Spring Boot and follows the MVC architecture pattern. It integrates AI technologies to generate product descriptions and images, providing users with an enhanced shopping experience.

## Features
- **Spring Boot MVC Architecture**: A robust structure that separates the application into three main components: Model, View, and Controller.
- **Spring AI Integration**: Harnessing the power of artificial intelligence, the application can automatically generate descriptions and images for products, reducing manual input and improving consistency in presentation.
- **AI Assistant Chatting Capabilities**: Engage users in real-time conversations, offering assistance and answering queries regarding products and services.

## Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone https://github.com/UdayBarman001/Electrotem-App.git
   cd Electrotem-App
   ```

2. **Install Dependencies**
   Make sure you have Java and Maven installed. Use the following command to install dependencies:
   ```bash
   mvn install
   ```

3. **Configure Application Properties**
   Update the `application.properties` file with your configuration details such as database parameters, API keys for AI services, etc.

4. **Run the Application**
   You can run the application using:
   ```bash
   mvn spring-boot:run
   ```
   This will start the embedded server, and you can access the application at `http://localhost:8080`.

## Contribution Guidelines
Feel free to make contributions to improve the Electrotem App. Please ensure that you follow coding standards and create meaningful commits.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.