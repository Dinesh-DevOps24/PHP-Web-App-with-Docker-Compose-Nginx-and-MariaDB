# PHP-Web-App-with-Docker-Compose-Nginx-and-MariaDB

A complete containerized PHP web application setup using **Docker Compose**, **Nginx**, and **MariaDB**. This project demonstrates modern DevOps practices for deploying and managing PHP applications in isolated containers.

---

## 🚀 Tech Stack

* **PHP**
* **Nginx**
* **MariaDB**
* **Docker**
* **Docker Compose**

---

## 📁 Project Structure

```bash
PHP-Web-App-with-Docker-Compose-Nginx-and-MariaDB/
│
├── app/                 # PHP application files
├── nginx/
│   └── default.conf     # Nginx configuration
├── docker-compose.yml   # Docker Compose configuration
├── Dockerfile           # PHP container configuration
└── README.md
```

---

## ⚙️ Features

* Multi-container Docker environment
* Nginx as reverse proxy server
* MariaDB database integration
* Easy local development setup
* Portable and scalable architecture
* Beginner-friendly DevOps project

---

## 🐳 Prerequisites

Make sure the following tools are installed:

* Docker
* Docker Compose
* Git

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Dinesh-DevOps24/PHP-Web-App-with-Docker-Compose-Nginx-and-MariaDB.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd PHP-Web-App-with-Docker-Compose-Nginx-and-MariaDB
```

### 3️⃣ Start Containers

```bash
docker-compose up -d --build
```

---

## 🌐 Access the Application

Open your browser and visit:

```bash
http://localhost
```

---

## 🗄️ Database Configuration

| Service  | Value   |
| -------- | ------- |
| Database | MariaDB |
| Host     | db      |
| Port     | 3306    |

Update your PHP database connection settings accordingly.

---

## 📦 Docker Services

| Service | Description                |
| ------- | -------------------------- |
| php     | PHP application container  |
| nginx   | Web server container       |
| db      | MariaDB database container |

---

## 🛠 Useful Commands

### Stop Containers

```bash
docker-compose down
```

### View Running Containers

```bash
docker ps
```

### View Logs

```bash
docker-compose logs -f
```

---

## 📚 Learning Objectives

This project helps you understand:

* Docker containerization
* Multi-container applications
* Nginx configuration
* Database container integration
* DevOps deployment workflow

---

## 🤝 Contributing

Pull requests are welcome. Feel free to fork this repository and improve the project.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Dinesh Kumar**

GitHub:
https://github.com/Dinesh-DevOps24
