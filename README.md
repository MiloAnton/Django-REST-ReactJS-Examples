# Django-REST-ReactJS 

This is a repository that combines some first projects, tutorials, ways I learned to use the stack ReactJS - Pythaon Django REST Framework - MongoDB or SQLDB.

Each folder corresponds to a different URL : 
  - **"tutorial"** : https://www.django-rest-framework.org/tutorial/quickstart/#testing-our-api
  <br/>*Simple administrator project to GET and POST infos*
  - **"django-react"** : https://www.valentinog.com/blog/drf/
  <br/>*Simple Leads administrator and minimalist viewing client*

# Instructions for each project : 
  ## "tutorial"
  Run only python server using following commands : 
  ``` 
  cd tutorial 
  python -m venv env # Linux, macos
  env/Scripts/activate # Windows
  python manage.py runserver
  ```
  Then connect to http://127.0.0.1:8000/users/
  
  ## "django-react"
  You'll have to run python server and npm server. Here are the commands : 
  ``` 
  cd django-react
  python -m venv venv # Linux, macos
  venv/Scripts/activate # Windows
  python manage.py runserver
  ```
  ``` 
  cd django-react/frontend/
  python -m venv venv # Linux, macos
  venv/Scripts/activate # Windows
  npm run dev
  ```
 Then connect to http://127.0.0.1:8000/ for client side or http://127.0.0.1:8000/api/lead for admin side

Made with ❤️ by Milo ROCHE-VANDENBROUCQUE 
