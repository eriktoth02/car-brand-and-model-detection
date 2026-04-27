# Car Brand & Model Detection WebApp

Web application for automatic car brand and model detection from images using AI.

---

## 🏗️ Architecture

| Component | Service               | Technology          |
| --------- | --------------------- | ------------------- |
| Frontend  | Azure Static Web Apps | React, Vite         |
| Backend   | Azure App Service     | FastAPI, Python     |
| Database  | Azure PostgreSQL      | PostgreSQL          |
| AI Model  | AWS SageMaker         | Deep Learning Model |

---

## ⚙️ Features

* Upload car image
* Detect car brand and model using AI
* Store results in database
* Display results in web interface

---

## ☁️ Cloud Architecture

* Main hosting on Microsoft Azure
* AI service hosted on AWS (SageMaker)
* Cross-cloud communication via REST API

---

## 🚀 Local Development

### Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔐 Environment Variables

Copy `.env.example` to `.env` and configure:

* DATABASE_URL
* AWS_ACCESS_KEY_ID
* AWS_SECRET_ACCESS_KEY
* AWS_REGION
* SAGEMAKER_ENDPOINT
* FRONTEND_URL

---

## 📦 Tech Stack

* Frontend: React, Vite
* Backend: FastAPI (Python)
* Database: PostgreSQL (Azure)
* AI: AWS SageMaker
* Cloud: Azure + AWS

---

## 📄 License

MIT
