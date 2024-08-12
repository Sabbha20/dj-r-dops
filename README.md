# dj-r-dops

### Initial Setup
**Create Workspace**
```
mkdir dj-r-dops
cd dj-r-dops
```

**Activate Virtual Environment**
```
python3 -m venv .djenv  
source .djenv/bin/activate
```
*For Windows*
```
.djenv/Scripts/activate
```

**Install Packages**
```
pip3 install -r requirements.txt
```

**Create Project**
```
django-admin startproject admin
```

**Run Project**
```
cd admin
python3 manage.py runserver
```

**Create Docker-File**
```
touch Dockerfile docker-compose.yaml
```

