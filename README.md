****Hotel** **Booking** **Application**

This project is a small Hotel Booking application that I built using a FastAPI (Python) backend and a React.js frontend.
Both parts of the project are containerized with Docker and can be deployed on Kubernetes (EKS).

**Project** **Structure**

project-root/
│
├── backend/        → FastAPI backend
│   ├── main.py
│   ├── requirements.txt
│   └── dockerfile
│
└── frontend/       → React frontend
    ├── package.json
    ├── dockerfile
    ├── public/
    │   └── index.html
    └── src/
        ├── App.js
        └── index.js
 **Backend** (**FastAPI**)       
- The backend is a simple FastAPI service that exposes a few endpoints for the booking application.

**How to run the backend locally
cd backend
pip install -r requirements.txt
uvicorn main:app 

**Running the backend with Docker
cd backend
docker build -t hotel-backend .
docker run -p 

****Frontend (React)
-  The frontend is built with React and communicates with the backend API.

**How to run the frontend locally
cd frontend
npm install
npm start
