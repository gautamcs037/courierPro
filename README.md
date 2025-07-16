Courier Pro
===========

Courier Pro is a modern, full-stack courier and logistics management application designed to make shipment handling simple and efficient.

This project includes a FastAPI backend and a React frontend, with role-based access for suppliers, importers, and exporters. It offers a dashboard to manage users, addresses, shipments, and real-time shipment tracking.

Project Structure
-----------------

```
courier-pro/
├── front_end_courier/     React app (Vite + Tailwind CSS)
├── courier_new/      FastAPI backend service
└── README.md
```

Getting Started
---------------

Prerequisites:

- Node.js and npm (for the frontend)
- Python 3.10+ (for the backend)
- Git

Running the Frontend:

```
cd frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5174`.

Running the Backend:

```
cd backend
python -m venv venv
venv\Scripts\activate  # or 'source venv/bin/activate' on Mac/Linux
pip install -r requirements.txt
uvicorn main:app --reload
```

The backend will be available at `http://localhost:8000`.

Features
--------

- Secure login with role-based access control
- Inline editing and management of multiple addresses
- Create, accept, reject, or cancel shipments
- Real-time shipment status tracking
- Clean and responsive dashboard interface

Technology Stack
----------------

| Layer     | Tech                     |
|-----------|--------------------------|
| Frontend  | React, Vite, Tailwind CSS|
| Backend   | FastAPI, SQLAlchemy      |
| Auth      | JWT                      |
| Database  | PostgreSQL     |


