How to use:

1. Setup a virtual environment
2. Source to your virtual environment
3. mezzanine-project --template=https://github.com/pandabearcoder/launcher/archive/master.zip --extension=py,md,sample,conf,json {{ proj }}
4. Change directory to the created project on your computer
5. Create a copy of keys.json.sample to keys.json located inside config folder
6. Edit keys.json and change SECRET_KEY to your secret key
7. Create initial database using python manage.py createdb
8. Start your projects server python manage.py runserver 0.0.0.0:800x
