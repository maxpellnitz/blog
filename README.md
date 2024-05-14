To set up the Project:

1. Open a Terminal Window

2. Navigate to 'backend/'

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

    (log in to 'localhost:8000' and create some initial users and blog-entries)

7. run django server 
```sh
python manage.py runserver
```

8. In a new Terminal navigate to 'frontend/'

9. install frontend requirements 
```sh
npm install --include dev
```

10. run the vite dev server
```sh
npm run dev
```
