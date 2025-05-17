# DevOps Projects: Docker Static Website Deployment 🚀

![Docker](https://img.shields.io/badge/Docker-Static%20Website-blue?style=for-the-badge&logo=docker)

Welcome to the **devops-projects_docker-static-website** repository! This project focuses on containerization and infrastructure, specifically deploying a static website using Docker. Whether you're a beginner or an experienced developer, this repository offers valuable insights and practical examples to enhance your DevOps skills.

## Table of Contents

1. [Overview](#overview)
2. [Getting Started](#getting-started)
3. [Project Structure](#project-structure)
4. [Deployment Steps](#deployment-steps)
5. [Technologies Used](#technologies-used)
6. [Key Features](#key-features)
7. [Usage](#usage)
8. [Contributing](#contributing)
9. [License](#license)
10. [Links](#links)

## Overview

This project aims to simplify the deployment of static websites using Docker. By leveraging containerization, you can ensure that your website runs consistently across different environments. This repository includes all the necessary files, configurations, and instructions to help you get started quickly.

## Getting Started

To get started with this project, you can download the necessary files from the [Releases section](https://github.com/keduzn/devops-projects_docker-static-website/releases). Make sure to execute the files as instructed in the documentation to set up your environment properly.

### Prerequisites

Before you begin, ensure you have the following installed:

- [Docker](https://www.docker.com/get-started)
- A text editor (like Visual Studio Code or Sublime Text)
- Basic knowledge of HTML, CSS, and JavaScript

## Project Structure

Here’s a brief overview of the project structure:

```
devops-projects_docker-static-website/
│
├── Dockerfile
├── docker-compose.yml
├── index.html
├── styles.css
└── script.js
```

- **Dockerfile**: This file contains instructions for building the Docker image.
- **docker-compose.yml**: This file defines the services, networks, and volumes for your application.
- **index.html**: The main HTML file for your static website.
- **styles.css**: The CSS file for styling your website.
- **script.js**: The JavaScript file for adding interactivity.

## Deployment Steps

Follow these steps to deploy your static website using Docker:

1. **Clone the Repository**

   Open your terminal and run the following command:

   ```bash
   git clone https://github.com/keduzn/devops-projects_docker-static-website.git
   ```

2. **Navigate to the Project Directory**

   Change to the project directory:

   ```bash
   cd devops-projects_docker-static-website
   ```

3. **Build the Docker Image**

   Use the following command to build the Docker image:

   ```bash
   docker build -t static-website .
   ```

4. **Run the Docker Container**

   After building the image, run the container with:

   ```bash
   docker run -d -p 8080:80 static-website
   ```

5. **Access Your Website**

   Open your web browser and navigate to `http://localhost:8080` to view your static website.

## Technologies Used

This project utilizes the following technologies:

- **Docker**: For containerization and deployment.
- **HTML**: For structuring the content of the website.
- **CSS**: For styling the website.
- **JavaScript**: For adding interactivity.

## Key Features

- **Easy Deployment**: Quickly deploy a static website using Docker.
- **Containerization**: Run your website in an isolated environment.
- **Cross-Platform**: Works on any system that supports Docker.
- **Version Control**: Use Git to manage changes to your code.

## Usage

You can customize the website by modifying the `index.html`, `styles.css`, and `script.js` files. After making changes, rebuild the Docker image and restart the container to see your updates.

### Example Modifications

- **Changing the Title**: Update the `<title>` tag in `index.html`.
- **Adding Styles**: Modify the `styles.css` file to change the appearance.
- **Adding Scripts**: Update `script.js` to add more functionality.

## Contributing

We welcome contributions to this project! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Links

For more information, visit the [Releases section](https://github.com/keduzn/devops-projects_docker-static-website/releases) to download and execute the necessary files. You can also explore the repository for additional resources and documentation.

Feel free to reach out with any questions or feedback!