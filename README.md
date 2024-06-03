# Gmail Clone README

## Introduction
Welcome to the Gmail Clone project! This application is designed to replicate the basic functionalities of Gmail, including sending, receiving, and organizing emails. This project is a great way to understand the fundamentals of email management systems, and it serves as an excellent practice for full-stack development.

## Features
- **User Authentication:** Secure sign-up and login functionality.
- **Compose Email:** Ability to compose and send emails.
- **Inbox:** View received emails.
- **Sent Items:** View sent emails.
- **Drafts:** Save emails as drafts.
- **Search:** Search emails by subject or sender.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## Technologies Used
- **Frontend:**
  - HTML, CSS, JavaScript
  - React.js
- **Backend:**
  - Node.js
  - Express.js
- **Database:**
  - MongoDB
- **Authentication:**
  - JWT (JSON Web Tokens)
- **Other Tools:**
  - Redux for state management
  - Axios for HTTP requests

## Getting Started

### Prerequisites
Ensure you have the following installed on your machine:
- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/gmail-clone.git
    cd gmail-clone
    ```

2. **Install frontend dependencies:**
    ```bash
    cd frontend
    npm install
    ```

3. **Install backend dependencies:**
    ```bash
    cd ../backend
    npm install
    ```

4. **Set up environment variables:**
   Create a `.env` file in the `backend` directory and add the following:
    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```

### Running the Application

1. **Start the MongoDB server:**
    ```bash
    mongod
    ```

2. **Start the backend server:**
    ```bash
    cd backend
    npm start
    ```

3. **Start the frontend server:**
    ```bash
    cd ../frontend
    npm start
    ```

   The application will be available at `http://localhost:3000`.

## Folder Structure
gmail-clone/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ └── app.js
│ └── server.js
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── redux/
│ │ ├── App.js
│ │ └── index.js
├── README.md



## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any improvements, bug fixes, or new features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
If you have any questions or suggestions, feel free to reach out at [mayank221602@gmail.com](mailto:mayank221602@gmail.com).

Thank you for using Gmail Clone! We hope this project helps you in your development journey.
