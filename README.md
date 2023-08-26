# Data Vault 

A cloud-based file storage system, Data Vault offers functionalities akin to Google Drive, allowing users to register, log in, and manage their files. Each file can be paired with an optional caption. With Cloud Vault, users can upload, view, modify, and delete files. The system's storage backend is Amazon's S3 service.

## Technologies Used
- Language: JavaScript
- Authentication: AWS Cognito, AWS Amplify
- Frontend: React.js, Reactstrap
- Backend: Node.js, AWS S3, AWS RDS (MySQL)
- Routing and Additional Libraries: React-Router-Dom, Express.js, CORS, Body-Parser


1. Initiate by selecting create account, followed by entering the desired username, email, password, and contact number.

2. Upon providing valid credentials, users receive a unique verification code to validate their email.

3. Post account setup, users are prompted to log in, and their details are stored in AWS Cognito.

4. Once verified, users are navigated to the main dashboard displaying all uploaded files. Here, files can be downloaded, modified, or removed as per preference.

5. Navigating to drop file, users are presented with an interface that permits either dragging and dropping files or using the Choose File option for selections from their device.

- Note: The fields what should we call this? and what is this? are entirely optional.
