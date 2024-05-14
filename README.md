To set up the Project:

1. open a Terminal Window

2. navigate to 'backend/'

3. create virtual environment 

4. install requirements.txt 
```sh
python -m pip install -r requirements.txt
```

5. make initial migrations

```sh
python manage.py migrate
```

6. create superuser 
```sh
python manage.py createsuperuser
```

7. log in to 'localhost:8000' and create some initial users and blog-entries

8. run django server 
```sh
python manage.py runserver
```

9. in a new Terminal navigate to 'frontend/'

10. install frontend requirements 
```sh
npm install --include dev
```

11. run the vite dev server
```sh
npm run dev
```
12. now, when both servers are running, you can open 'localhost:5173'