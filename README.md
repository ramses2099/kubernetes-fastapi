# kubernetes-fastapi
Deployment fastapi in microk8s

# Create virtual environment
python -m env venv

# Activate virtual
.\venv\Scripts\Activate.ps1

# Update pip 
python.exe -m pip install --upgrade pip

# Install FastAPI
pip install "fastapi[standard]"

# Requirements
pip freeze > requirements.txt

# Run 
fastapi run

# Docker
docker compose up --build

# Running
http://127.0.0.1:8001/