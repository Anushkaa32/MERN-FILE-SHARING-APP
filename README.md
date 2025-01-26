# MERN File Sharing Application

This is a secure file-sharing application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to upload files and generate shareable links for efficient and secure file sharing.

---

## Features

- **File Upload**: Upload files securely through an intuitive user interface.
- **Download Tracking**: Track the number of times files are downloaded.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.

---

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

---

## Installation and Setup

### Clone the Repository

```bash
git clone https://github.com/Anushkaa32/MERN-FILE-SHARING-APP.git
cd MERN-FILE-SHARING-APP
```
### Install Server Dependencies
```bash
cd server
npm install
```
### Install Client Dependencies
```bash
cd ../client
npm install
```

### Configure Environment Variables
Create a .env file in the server directory and add the following:
```bash
MONGO_URI=your-mongodb-connection-string
PORT=5000
BASE_URL=http://localhost:5000
```
Replace your-mongodb-connection-string with your MongoDB URI.

---

## Running the Application

### Start the Backend
```bash
cd server
npm start
```

### Start the Frontend
```bash
cd ../client
npm start
```
Open the application in your browser at http://localhost:3000.

---

## Folder Structure
MERN-FILE-SHARING-APP
├── client                 # React.js frontend <br/>
│   ├── public             # Static files <br/>
│   └── src                # React components, CSS, services <br/>
├── server                 # Node.js backend <br/>
│   ├── controllers        # API business logic <br/>
│   ├── models             # MongoDB schemas <br/>
│   ├── routes             # API routes <br/>
│   ├── uploads            # Uploaded files directory <br/>
│   └── utils              # Utility functions <br/>

---

## Future Enhancements
- **Authentication**: Add user login and registration.
- **Cloud Storage**: Integrate cloud services like AWS S3 for file storage.
- **Link Expiry**: Add expiry functionality for shareable links.

---

## Contributing
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


