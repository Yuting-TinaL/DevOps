## Multi-Container Docker Application with CI/CD: Calculator App Project

#### Complete Project Instructions: [DevOps Foundations Course/Project](https://github.com/shiftkey-labs/DevOps-Foundations-Course/tree/master/Project)

#### Submission by - **<Yuting> <Liang>**

### Project Overview

- **Brief project description:** What is the purpose of your application?
<!-- To provide a web-based calculator that allows users to perform basic arithmetic and advanced mathematical operations. It consists of two parts:
(1)Frontend (React-based UI): A user-friendly interface for interacting with the calculator.
(2)Backend (Python API): Handles the logic for performing calculations, such as addition, subtraction, multiplication, division, square root, logarithm, and more advanced mathematical functions. -->

- **Which files are you implmenting? and why?:**
<!-- 
(1)Frontend:
React components: Responsible for rendering the UI and capturing user inputs.
App.js: The core file for routing and handling logic within the React app. It also communicates with the backend API to perform calculations.
index.html: The HTML template where meta information (e.g., title, icons) is defined.
(2)Backend:
API routes (Flask): The routes defined for various operations (e.g., /api/add, /api/subtract, etc.) provide endpoints that the frontend can call to perform the requested mathematical operations.
Dockerfile: For containerizing the backend application to ensure consistent deployment across environments. 
-->

- _**Any other explanations for personal note taking.**_

<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


### Docker Implementation

**Explain your Dockerfiles:**

- **Backend Dockerfile** (Python API):
    - Here please explain the `Dockerfile` created for the Python Backend API. 
    - This can be a simple explanation which serves as a reference guide, or revision to you when read back the readme in future. 

<!-- The Dockerfile ensures that the backend API runs in an isolated, consistent environment, making it easier to deploy the Python API regardless of the host system's configuration. -->

- **Frontend Dockerfile** (React App):
    - Similar to the above section, please explain the Dockerfile created for the React Frontend Web Application. 

<!-- Uses the official Node.js image () to create a container for the React application.Base Image: Uses the official Node.js image (node:18-slim) to create a container for the React application.
Installs the necessary dependencies Install Dependencies: Installs the necessary dependencies (npm install). -->

**Use this section to document your choices and steps for building the Docker images.**


### Docker Compose YAML Configuration

**Break down your `docker-compose.yml` file:**

- **Services:** List the services defined. What do they represent?
- **Networking:** How do the services communicate with each other?
- **Volumes:** Did you use any volume mounts for persistent data?
- **Environment Variables:** Did you define any environment variables for configuration? 

**Use this section to explain how your services interact and are configured within `docker-compose.yml`.**

<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


### CI/CD Pipeline (YAML Configuration)

**Explain your CI/CD pipeline:**

- What triggers the pipeline (e.g., push to main branch)?
- What are the different stages (build, test, deploy)?
- How are Docker images built and pushed to a registry (if applicable)?

**Use this section to document your automated build and deployment process.**

<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


### CI/CD Pipeline (YAML Configuration)

**Simply explain your CI/CD pipeline:**

- What triggers the pipeline (e.g., push to main branch)?
- What are the different stages (build, test, deploy)?
- How are Docker images built and pushed to a registry?

**Use this section to document your automated build, and docker process.**

<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


### Assumptions

- List any assumptions you made while creating the Dockerfiles, `docker-compose.yml`, or CI/CD pipeline. 

<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


### Lessons Learned

- What challenges did you encounter while working with Docker and CI/CD?
- What did you learn about containerization and automation?

**Use this section to reflect on your experience and learnings when implementing this project.**

<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->


### Future Improvements

- How could you improve your Dockerfiles, `docker-compose.yml`, or CI/CD pipeline? 
- (Optional-Just for personal reflection) Are there any additional functionalities you would like to consider for the calculator application to crate more stages in the CI/CD pipeline or add additional configuration in the Dockerfiles?

**Use this section to brainstorm ways to enhance your project.**

<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- Include explanation here -->
<!-- NOTE: It is not compulsory to include detailed explanations, writing succint concise points would also sufice. Make sure maintain readability and clarity. -->






<!-- BEST OF LUCK! -->
