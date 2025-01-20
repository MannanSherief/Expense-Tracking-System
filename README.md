🚀 Expense Management System 💸
Welcome to the Expense Management System — a simple yet powerful application to track and manage your personal or business expenses efficiently! This system combines the intuitive power of Streamlit for the frontend and the high-performance capabilities of FastAPI for the backend, creating a seamless and user-friendly experience. 


🏗️ Project Structure
This project is structured to ensure clear separation between the frontend, backend, and testing components:

frontend/: The code for the Streamlit app — providing a responsive and easy-to-navigate UI.
backend/: The FastAPI backend server — handles data processing, storage, and retrieval.
tests/: Unit and integration tests for both the frontend and backend, ensuring that the system remains stable and bug-free.
requirements.txt: Lists all the necessary Python dependencies for the project.
README.md: This file, containing all the details about the project


⚙️ Setup Instructions
Get the Expense Management System running on your local machine with these easy steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
