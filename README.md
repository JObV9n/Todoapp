
# Todo App

This project is a Django-React Todo App that allows you to manage tasks and to-dos.

## Installation

Follow these steps to set up the project on your local machine.



## Run Locally

Clone the project

```bash
  git clone https://github.com/JObV9n/intern.git project_name
```
 Navigate to the `project` directory:


### Backend Setup (Django)
   ```bash
   pip install pipenv
   pipenv intall django
   ```    
create django Backend
   ```bash
   django-admin startproject backend
   ```
Goto backend folder
```bash
  cd backend
```
```bash
python manage.py startapp todo
```

make migrations
```bash
python manage.py migrate 

python manage.py makemigrations todo

python manage.py migrate todo
```
Create SuperUser
```bash
python manage.py createsuperuser
```
Setup the API's to backend
```bash
pipenv install djangorestframework django-cors-headers
```

Run the Django server
```bash
python manage.py runserver
```
### Frontend Setup (React)

##Download and Install NodeJs

Navigate to base project_name folder
```bash
cd ..
```

create a React app 
```bash
npm create-react-app frontend
```
Install all dependencies 
```bash
npm install reactstrap bootstrap axios
```

###Running the project

1.Start the Django Backend 
```bash
cd ../../backend
python manage.py runserver
```

2. Start the React frontend

```bash
cd ../frontend
npm start
```

## Accessing the Project
#### Open your web browser and visit http://localhost:3000 to access the React frontend.
 #### To access the Django admin panel, visit http://localhost:8000/admin and log in with the superuser account you created.

 

 
![Logo](https://res.cloudinary.com/practicaldev/image/fetch/s--Xd0KNnXc--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/m1iv6bl1w5o9i4ppoh3i.png)