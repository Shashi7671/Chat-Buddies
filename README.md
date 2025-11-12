# 💬 Chat-Buddies

A comprehensive, real-time online chatting application designed to connect users instantly across the globe. This project features a robust backend for handling user authentication and data, and a dynamic frontend for a seamless chat experience.

---

## ✨ Features

* **Real-Time Messaging:** Instant message delivery using WebSockets (likely Socket.IO).
* **User Authentication:** Secure registration and login functionalities.
* **User Status:** Display of online/offline status for connected users.
* **One-on-One Chat:** Ability to send private messages to other online users.
* **Responsive Design:** Accessible and usable across various devices.

---

## 🛠️ Technologies Used

This project is built using a modern JavaScript stack split into a backend server and a frontend client.

### Backend (Server)
| Technology | Purpose |
| :--- | :--- |
| **Node.js** | JavaScript runtime environment for the server. |
| **Express.js** | Web application framework for API and routing. |
| **Socket.IO** | Library for real-time, bidirectional communication (WebSockets). |
| **MongoDB** | NoSQL database for storing user accounts and chat history. |
| **Mongoose** | MongoDB object data modeling (ODM) for Node.js. |
| **JWT** | JSON Web Tokens for secure user authentication. |

### Frontend (Client)
| Technology | Purpose |
| :--- | :--- |
| **React** (or similar framework) | Library for building the user interface. |
| **Socket.IO Client** | Client-side library to connect to the WebSocket server. |
| **CSS Modules / Tailwind CSS** | Styling and responsive design. |

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

You need the following software installed on your machine:
* [Node.js](https://nodejs.org/) (which includes npm or yarn)
* [MongoDB](https://www.mongodb.com/try/download/community) (running locally or a cloud service like Atlas)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Shashi7671/Chat-Buddies.git](https://github.com/Shashi7671/Chat-Buddies.git)
    cd Chat-Buddies
    ```

2.  **Configure Environment Variables:**
    Create a file named `.env` in the root of the **`server`** directory with the following content (replace placeholders with your actual values):

    ```env
    # .env in the /server folder
    PORT=5000 
    MONGO_URI=mongodb+srv://<user>:<password>@<cluster-name>/chat-db?retryWrites=true&w=majority 
    JWT_SECRET=<a_long_secret_key_for_tokens> 
    ```

### Running the Backend (Server)

1.  Navigate into the server directory:
    ```bash
    cd server
    ```
2.  Install dependencies:
    ```bash
    npm install
    # or yarn install
    ```
3.  Start the server:
    ```bash
    npm start 
    # The server will run on http://localhost:5000
    ```

### Running the Frontend (Client)

1.  Open a **new terminal window** and navigate to the client directory:
    ```bash
    cd ../client
    ```
2.  Install dependencies:
    ```bash
    npm install
    # or yarn install
    ```
3.  Start the client application:
    ```bash
    npm run dev 
    # or npm start
    # The client will open in your browser (usually http://localhost:3000)
    ```

---

## 📝 Usage

Once both the server and client are running:

1.  **Register:** Create a new account using the sign-up form.
2.  **Login:** Log in with your new credentials.
3.  **Chat:** You will see a list of other online users. Click on a user's name to open a private chat window and start a real-time conversation.

---

## 🧑‍💻 Contributing

If you wish to contribute, please follow these steps:
1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE.md` for more information (if applicable).

---

## 📧 Contact

Shashi7671 - [Your Email/GitHub Profile Link]

Project Link: [https://github.com/Shashi7671/Chat-Buddies](https://github.com/Shashi7671/Chat-Buddies)
