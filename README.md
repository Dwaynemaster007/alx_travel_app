# 🌍 alx_travel_app: Your Gateway to Seamless Travel Listings 🚀

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green)
![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-57A60F?style=for-the-badge&logo=django&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## ✨ Project Overview

Welcome to the **alx_travel_app**! This project is a robust, real-world Django application designed to be the foundation for a powerful travel listing platform. Our mission is to build a scalable and secure backend that sets the standard for modern web development.

This repository represents the crucial first milestone, where we've focused on creating a production-ready setup from the ground up.

## 🌟 Key Features

* **Django-Powered Backend:** Built on the reliable and feature-rich Django framework.
* **RESTful API:** Developed with Django REST Framework for clean, well-structured API endpoints.
* **MySQL Database:** Utilizes a robust relational database for secure and efficient data management.
* **API Documentation:** Integrated with **Swagger UI** (`drf-yasg`) for automatic, interactive, and beautifully documented API endpoints. 
* **Secure Configuration:** Employs `django-environ` to handle sensitive data via `.env` files, ensuring secrets are never committed to the repository.
* **CORS Headers:** Configured with `django-cors-headers` for seamless cross-origin resource sharing.

## 🚀 Getting Started

Follow these simple steps to get the project up and running on your local machine.

### Prerequisites

Make sure you have the following installed:
* Python 3.x
* MySQL Server
* Git

### Installation

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Dwaynemaster007/alx_travel_app.git](https://github.com/Dwaynemaster007/alx_travel_app.git)
    cd alx_travel_app
    ```
2.  **Set Up the Virtual Environment**
    ```bash
    python3 -m venv venv
    source venv/Scripts/activate  # On Windows using Git Bash
    ```
3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Database Configuration**
    Create a `.env` file in the root directory of the project and add your MySQL credentials.
    ```env
    DB_NAME=your_database_name
    DB_USER=your_username
    DB_PASSWORD=your_password
    DB_HOST=127.0.0.1
    DB_PORT=3306
    SECRET_KEY=your_secret_key
    DEBUG=True
    ```
5.  **Run Migrations**
    ```bash
    python manage.py migrate
    ```
6.  **Start the Server**
    ```bash
    python manage.py runserver
    ```

Your API will now be running at `http://127.0.0.1:8000/`.

## 📚 API Documentation

Explore all available API endpoints directly from your browser!

* **Swagger UI:** [http://127.0.0.1:8000/swagger/](http://127.0.0.1:8000/swagger/)
* **ReDoc:** [http://127.0.0.1:8000/redoc/](http://127.0.0.1:8000/redoc/)

## 🤝 Contribution

This project is a continuous journey. We welcome contributions, bug reports, and feature requests. Feel free to open an issue or submit a pull request!

## 📜 License

This project is licensed under the BSD License. See the `LICENSE` file for details.

---

Made with ❤️ by [Dwayne Master 007](https://github.com/Dwaynemaster007)
