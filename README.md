
# 🚀 Dockerized 2-Tier Flask Application on AWS 🐳☁️

This project demonstrates how to build and deploy a **2-tier Flask application** using Docker, with MySQL as the backend database. The entire setup runs seamlessly on an **AWS EC2 instance**, connected via a custom Docker bridge network.

---

## 🔧 Project Architecture

```
Client <--> Flask App Container <--> MySQL Container
```

### 🔹 Components:

- **Flask App Container** – Serves the frontend and backend logic, runs the Python Flask application
- **MySQL Container** – Hosts the database, set up using CLI inside the container
- **Custom Docker Network** – Enables full container-to-container communication

---

## ⚙️ Key Features

- 🔗 Custom **Docker Bridge Network** for secure inter-container communication  
- 💬 Flask app **interacts with MySQL** container to store and retrieve data  
- 💾 Data is stored **persistently** inside the MySQL container  
- 🐳 **Docker Compose** for easy multi-container orchestration  
- ☁️ Fully **deployed and tested on AWS EC2** instance

---

## 📚 What I Learned

- ✅ Writing a **Dockerfile** for a Python Flask application  
- ✅ Managing multi-container apps using the **Docker CLI**  
- ✅ Handling **networking and data persistence** between containers  
- ✅ Deploying containerized applications on **AWS EC2**

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-flask-docker-app.git
   cd your-flask-docker-app
   ```

2. **Start the application**:
   ```bash
   docker-compose up --build
   ```

3. **Access the Flask app**:
   ```
   http://<your-ec2-public-ip>:5000
   ```

---

## 📦 Tech Stack

- **Backend:** Flask (Python)
- **Database:** MySQL
- **Containerization:** Docker, Docker Compose
- **Deployment:** AWS EC2

---

## 🙌 Final Thoughts

This project was a great opportunity to learn real-world deployment using Docker and AWS. It helped me strengthen my knowledge of networking, container orchestration, and cloud infrastructure. Feel free to try it out or reach out with questions!

Happy building! 🎯
