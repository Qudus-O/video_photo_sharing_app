# Qbyte Media
> **Seamless Media Sharing • Powered by FastAPI**

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://fastapi-media-centre-qudus.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-336791)
![Render](https://img.shields.io/badge/Render-Deployed-46E3B7)

## 🚀 Overview
**Qbyte Media** is a full-stack media sharing platform engineered to handle real-time image and video uploads. Unlike simple scripts, this application utilizes a **decoupled architecture**, separating the high-performance **FastAPI** backend from the interactive **Streamlit** frontend.

The system leverages asynchronous database operations and cloud-based object storage to ensure low latency and high scalability, even during concurrent user requests.

👉 **[Live Demo: Click here to open Qbyte Media](https://fastapi-media-centre-qudus.streamlit.app/)**

---

## 🛠 Tech Stack & Architecture

| Component | Technology | Role |
|-----------|------------|------|
| **Backend** | **FastAPI** (Python) | High-performance, asynchronous REST API handling logic and auth. |
| **Frontend** | **Streamlit** | Interactive UI for media gallery and upload management. |
| **Database** | **PostgreSQL** (Render) | Relational database for user data and media metadata. |
| **Storage** | **ImageKit.io** | Cloud-based media storage with real-time optimization. |
| **ORM** | **SQLModel / SQLAlchemy** | Async database interaction and schema validation. |
| **Deployment** | **Render & Streamlit Cloud** | Managed cloud infrastructure with CI/CD pipelines via GitHub. |

---

## ✨ Key Features
* **Secure Authentication:** JWT-based user login and registration system.
* **Cloud Media Management:** Direct integration with ImageKit for optimizing and serving assets.
* **Asynchronous Processing:** Utilizes `asyncpg` for non-blocking database queries to handle high concurrency.
* **Continuous Deployment:** Automated build pipelines on Render (Backend) and Streamlit Cloud (Frontend).

---

## 🔧 Local Installation

To run this project on your local machine:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/Qudus-O/video_photo_sharing_app.git](https://github.com/Qudus-O/video_photo_sharing_app/.git)
    cd YOUR_REPO_NAME
    ```

2.  **Set up the Backend**
    ```bash
    cd backend
    # Create virtual environment (optional but recommended)
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    
    # Install dependencies
    pip install -r requirements.txt
    
    # Run the server
    uvicorn main:app --reload
    ```

3.  **Set up the Frontend (New Terminal)**
    ```bash
    # Install dependencies
    pip install -r requirements.txt
    
    # Run the interface
    streamlit run frontend.py
    ```

---

## 🎓 Acknowledgements & Credits

This project was built as a capstone to demonstrate full-stack engineering capabilities. A special thank you to the following creators for their educational content that guided the architectural decisions:

* **Tim Ruscica - TechwithTim** - For the comprehensive guide on FastAPI Apps.
* **Raj Kapadia** - For the insights on deploying FastAPI apps on Render.

---

## 👨‍💻 Author

### Qudus
* *Data Scientist and a Machine Learning Engineer*
* [LinkedIn](https://linkedin.com/in/qudusoseni82)
  
