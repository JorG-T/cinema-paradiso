## Cinema Paradiso
```
Cinema Paradiso project build with a frontend built in React & Redux and a backend built in Django API.
```
## Live Demo
**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**
Check out [FRONTEND LIVE DEMO](https://jeorge-cinema.netlify.app) here!!
Check out [API LIVE DEMO](https://cinema-backend-shu3.onrender.com/) here!!

## Tech used
```
* Frontend : React & Redux
* Backend : Django
```
## How to Install
1. Git Clone
```
git clone https://github.com/Cinema-Paradise/Cinema-paradiso.git
```
2. Backend setting
```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/
# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```
3. Frontend setting
```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```







