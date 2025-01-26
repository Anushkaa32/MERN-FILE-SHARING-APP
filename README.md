#File Sharing Application-MERN
A full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack that allows users to securely upload and share files. This application enables efficient and secure file-sharing through a generated download link.

Features
File Upload: Users can upload files to the server with size validation.
File Sharing: Generate shareable links for each uploaded file.
Secure Downloads: Download files securely using the shareable links.
Responsive Design: Optimized for both desktop and mobile use.
Technology Stack:
Frontend: React.js
Backend: Node.js with Express.js
Database: MongoDB
File Storage: Managed by local uploads or cloud integration (e.g., AWS S3).
Installation and Setup

Prerequisites
Ensure you have the following installed:
Node.js
MongoDB
Git
Steps to Run Locally

Clone the repository:
git clone https://github.com/Anushkaa32/MERN-FILE-SHARING-APP.git
cd MERN-FILE-SHARING-APP
Install dependencies:

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
Configure environment variables:

Create a .env file in the server directory and add the following:
MONGO_URI=your-mongodb-connection-string
PORT=5000
BASE_URL=http://localhost:5000
Replace your-mongodb-connection-string with your MongoDB URI.

Start the application:

# Start backend
cd server
npm start

# Start frontend
cd ../client
npm start

Open the app in your browser:
http://localhost:3000
Folder Structure

MERN-FILE-SHARING-APP
├── client                 # React.js frontend
│   ├── public             # Static files
│   └── src                # React components, CSS, services
├── server                 # Node.js backend
│   ├── controllers        # API business logic
│   ├── models             # MongoDB schemas
│   ├── routes             # API routes
│   ├── uploads            # Uploaded files directory
│   └── utils              # Utility functions


Features and Functionalities
File Upload:

Upload files through a simple and intuitive UI.
Supports multiple file types and sizes.
Shareable Links:

Generate a secure link for each uploaded file.
Users can share this link for downloading the file.
Download Tracking:

Tracks the number of times a file is downloaded.
Backend Services:

Built-in file validation.
Error handling and secure storage.
Frontend Experience:

User-friendly React interface.
Responsive design for different devices.
Future Enhancements
User Authentication: Add secure login and registration.
Cloud Integration: Use cloud storage for file uploads.
Expiry Links: Add expiry functionality for shareable links.
Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for discussion.

License
This project is licensed under the MIT License. See the LICENSE file for details.
