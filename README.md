https://github.com/ArtOfEngineer/DjangoReactJs

# Back-end

~~~sh
cd myenv 
source bin/activate
python manage.py runserver
cd DjangoAPI 
~~~





~~~sh

virtualenv myenv

pip install django #pip install django==3.0.1
python -m django --version
django-admin startproject DjangoAPI 

pip install django-cors-headers




python manage.py startapp  EmployeeApp
#update settings.py, models.py
python manage.py makemigrations EmployeeApp
python manage.py makemigrations EmployeeApp
#verify the db.sqlite3
#creat serializers.py under EmployeeApp
#views.py, urls.py
#urls.py uder DjangoAPI
#postman test the API(PUT/POST/DELETE)

#creat media floder
#setting.py
#views.py, urls.py under EmployeeApp

~~~

# Front-end

~~~sh
cd my-app
npm start
~~~





~~~sh
npx create-react-app my-app


npm install react-bootstrap bootstrap


#App.js
#index.html
#https://react-bootstrap.github.io/getting-started/introduction/
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
  integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
  crossorigin="anonymous"
/>

#Home.js
#Department.js, Employee.js, Navigation.js
#App.js

npm install --save react-router-dom

#.env, .gitignore
#Department.js
#AddDepModal.js
#EditDepModal.js
#Department.js
#Add/Edit employee in the same way

~~~

