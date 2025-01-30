

# CRUD-NEXT-JS-FASTAPI-MYSQL

BACKEND

cd backend
pip install uvicorn - Install uvicorn
python -m venv venv - create virtual environment
pip install fastapi uvicorn sqlalchemy mysql-connector-python pydantic python-dotenv
pip freeze > requirements.txt

uvicorn app.main:app --reload
venv\Scripts\Activate - activate virtual environment
Set-ExecutionPolicy Unrestricted -Scope Process
venv\Scripts\activate.bat
pip install fastapi uvicorn
uvicorn app.main:app --reload -  run app



FRONTEND

cd frontend 
npm run dev - run app



DATABASE

Download XAMPP, launch apache server and the mysql
CREATE DATABASE crud_db;


GIT
git add .
git checkout -b fullstack-project - branch created
git push -u origin fullstack-project


