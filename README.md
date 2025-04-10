# Notes App 📝

A full-stack **MERN** (MongoDB, Express, React, Node.js) application for managing notes. This app allows users to create, view, edit, and delete notes with a clean and user-friendly interface.

---

## Features ✨

- **Frontend**: Built with React and styled for a modern look.
- **Backend**: RESTful API built with Express and MongoDB for data storage.
- **Kubernetes**: Deployment-ready with YAML configurations for frontend, backend, and database.
- **Docker**: Containerized for easy deployment.
- **CI/CD Ready**: Configured for seamless integration and deployment.

---

## Prerequisites 🛠️

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/)
- [Docker](https://www.docker.com/)
- [Kubernetes](https://kubernetes.io/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [nginx-ingress](https://kubernetes.github.io/ingress-nginx/)

---

## Installation 🚀

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/notes-app.git
cd notes-app
```

### 2. Backend Setup
1. Navigate to the server directory:
    ```bash
    cd server
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Create a `.env` file and configure the environment variables:
    ```plaintext
    MONGO_URI=your-mongodb-connection-string
    ```
4. Start the backend server:
    ```bash
    npm start
    ```

### 3. Frontend Setup
1. Navigate to the client directory:
    ```bash
    cd ../client
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the frontend development server:
    ```bash
    npm start
    ```

### 4. Docker Setup (Optional)
1. Build Docker images for the frontend and backend:
    ```bash
    docker-compose build
    ```
2. Start the containers:
    ```bash
    docker-compose up
    ```

### 5. Kubernetes Deployment (Optional)
1. Apply Kubernetes configurations:
    ```bash
    kubectl apply -f k8s/
    ```
2. Ensure all pods are running:
    ```bash
    kubectl get pods
    ```
3. Access the application via the configured ingress.

---

## Usage 📖

1. Open your browser and navigate to the application URL.
2. Create an account or log in.
3. Start creating, editing, and managing your notes!

---

## Contributing 🤝

Contributions are welcome! Please fork the repository and submit a pull request.

---

## License 📜

This project is licensed under the [MIT License](LICENSE).

---

## Contact 📬

For any inquiries or feedback, feel free to reach out at `tripathiiharsh02@gmail.com` .
