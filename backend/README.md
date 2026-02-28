# ⚙️ AcadMate Backend

The backend of AcadMate is a high-performance **FastAPI** application that provides robust APIs, real-time communication via WebSockets, and secure data management using PostgreSQL.

## 🛠️ Tech Stack

- **Framework:** FastAPI
- **Database:** PostgreSQL (via SQLAlchemy)
- **Real-time:** Python-Socket.io
- **Auth:** JWT (JSON Web Tokens)

## 📦 Prerequisites

- Python 3.9+ installed
- A running instance of PostgreSQL

## 🚀 Setup & Installation

1. **Navigate to the backend folder:**

   ```bash
   cd backend
   ```

2. **Create and activate a virtual environment:**
   - **Mac/Linux:** `python -m venv venv && source venv/bin/activate`
   - **Windows:** `python -m venv venv && venv\Scripts\activate`

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Variables:**
   Create a `.env` file based on the provided `.env.example` file and configure your `DATABASE_URL` appropriately.

5. **Run the Server:**
   Launch the FastAPI and Socket app utilizing Uvicorn:

   ```bash
   uvicorn main:socket_app --reload
   ```

6. **Interactive APIs:**
   Once running, explore the automatic Swagger API documentation at: `http://localhost:8000/docs`.

## 📄 License

This module is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
