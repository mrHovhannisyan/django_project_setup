# django_project_setup
The right way to start Django app 🙂️

### 0. Make sure you’ve got Python & pip
You can check this by simply running:
```
python --version
```
```
pip --version
```

### 1. Open the terminal and create project folder
```
mkdir <project_name>
```

### 2. Go to project folder
```
cd <project_name>
```

### 3. Make virtual environment*
```
virtualenv venv
```

_*You'll need `virtualenv` be installed on your system_   
```
pip install virtualenv
```   
_**You can also use the Python interpreter of your choice (like python2.7)._
```bash
virtualenv -p /usr/bin/python2.7 venv
```

### 4. To begin using the virtual environment, it needs to be activated
```bash
source venv/bin/activate
```

### 5. Now start installing Django using pip 
```
pip install Django
```
start a project:
```
django-admin startproject <project_name> .
```
and create a new app:
```
django-admin startapp <app_name>
```


