https://github.com/ArtOfEngineer/DjangoReactJs

# Back-end

~~~sh

source myenv/bin/activate

cd DjangoAPI 
python manage.py runserver

# for new location
pip install django 
pip install django-cors-headers
pip install djangorestframework
~~~



~~~sh

virtualenv myenv

pip install django #pip install django==3.0.1
python -m django --version
django-admin startproject DjangoAPI 

pip install django-cors-headers
pip install djangorestframework



python manage.py startapp  EmployeeApp
#update settings.py, models.py
python manage.py makemigrations EmployeeApp
python manage.py migrate EmployeeApp
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

#for new location
npm install
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

# Deploy

~~~sh
npm run build
将build目录的内容全部cp到django的templates/react目录里，再将templates/react/static目录放到django的static目录里

source myenv/bin/activate

cd DjangoAPI 
python manage.py createsuperuser
python manage.py runserver




$ # Get the code
$ git clone https://github.com/xxx/xx.git
$ cd xx
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ # Install modules - SQLite Storage
$ pip3 install -r requirements.txt
$
$ # Create tables
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
$
$ # Start the app - custom port
$ # python manage.py runserver 0.0.0.0:<your_port>
$
$ # Access the web app in browser: http://127.0.0.1:8000/
~~~

