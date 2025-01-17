# Chess-Mono
Monorepo of our Chess mobile app project

## Contributors
| Name  | Links |
|--|--|
| Evan Giampaoli | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EvanG13) [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/evan-giampaoli-953460230/) |
| Cleveland Plonsey | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CleveyP) [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/clevelandplonsey/) |
| Arjun Radhakrishnan | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kysJune) [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arjun-radhakrishnan-9a3a441a8/) |
| Caimin Rybolt-O'Keefe | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CaiminRO) [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/caimin-r-o/) |

# Technologies Used
## Backend
- Java with Apache Maven
  - Purpose: Serves as the primary language and build tool for the backend services.
  - Details: Java provides a reliable and high-performance environment for developing server-side logic. Apache Maven is used for project management and dependency handling, ensuring consistent builds and simplifying the integration of various libraries and frameworks.
- OpenAPI
  - Purpose: Defines and documents the RESTful APIs.
  - Details: OpenAPI Specification (formerly Swagger) is used to design and describe the API endpoints. This facilitates clear communication between frontend and backend teams and enables automatic generation of client SDKs and API documentation.
- Terraform
  - Purpose: Infrastructure as Code (IaC) for managing AWS resources.
  - Details: Terraform automates the provisioning and management of cloud infrastructure, ensuring consistency across environments. It manages resources such as AWS Lambda functions, API Gateway configurations, S3 buckets, and more.

## Frontend
- React Native with Expo
  - Purpose: Builds the cross-platform mobile application.
  - Details: React Native allows for the development of native-like mobile apps using JavaScript and React. Expo enhances the development workflow by providing a set of tools and services that streamline the building, deploying, and testing processes.
- Android Studio
  - Purpose: Integrated development environment (IDE) for Android development.
  - Details: While React Native handles the cross-platform aspects, Android Studio is utilized for Android-specific development tasks, debugging, and testing, ensuring optimal performance and compatibility on Android devices.

## Deployment and Hosting
- AWS Lambda
  - Purpose: Serverless computing for backend functions.
  - Details: AWS Lambda enables the execution of backend code without managing servers. It scales automatically with demand, reducing operational overhead and costs.

- API Gateway (REST and WebSocket)
  - Purpose: Manages API requests and real-time communication.
  - Details: AWS API Gateway handles RESTful API requests, routing them to appropriate Lambda functions. Additionally, it supports WebSocket APIs for real-time features such as live game updates and chat functionalities.

- Amazon S3 Bucket
  - Purpose: Storage for static assets and user-generated content.
  - Details: S3 provides a scalable and secure solution for storing images, game data, and other static resources, ensuring quick retrieval and high availability.

- AWS CloudWatch
  - Purpose: Monitoring and logging.
  - Details: CloudWatch collects and tracks metrics, logs, and events from various AWS services. It provides insights into application performance, enabling proactive issue detection and resolution.

Database Management
- MongoDB
  - Purpose: Primary database for the application.
  - Details: MongoDB stores various types of data including user information, game states, and move histories. Its schema-less design allows for easy adaptation to evolving data requirements without significant downtime or restructuring.

- Liquibase
  - Purpose: Database schema version control.
  - Details: Liquibase ensures that all changes to the MongoDB schemas are tracked and managed systematically. It supports automated deployments and integrates seamlessly with the CI/CD pipeline, promoting consistency and reliability in database updates.
 
