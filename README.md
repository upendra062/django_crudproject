# Create Environment
```
python -m venv venv
```

# Activate Environment
```
source activate venv/bin/activate
```

# Create Super User
```
python manage.py createsuperuser
```

# mongodb and mysql database name
```
mysql database name = django_db
mongodb database name = curddjangoapplication
```

# Mysql Connection
```
pip install pymysql 
python manage.py makemigrations
python manage.py migrate
```

# Mongodb Connection
```
pip install pymongo[snappy,gssapi,srv,tls]

```

# some extra command if not working
```
pip install django
pip install --upgrade pip
pip install dnspython
pip install mongoengine
pip install pymongo
pip install djongo
python manage.py makemigrations
python manage.py migrate
```

# If connection with mongodb is not working use this version
pip install pymongo==3.12.3




# Deployment database Aws EDS 

# Deployment Elastic Beanstalk

# Deployment Dockerimage in AWS EC2 and ECR with CI & CD

# Deployment GCP

