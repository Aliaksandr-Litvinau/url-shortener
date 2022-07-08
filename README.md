# url-shortener

# Getting Started
# 1. Using Docker  
Clone the repo:     
- git clone https://github.com/Aliaksandr-Litvinau/url-shortener  
Bring up the app:
- docker-compose up -d --build  
Perform the migration:
- docker-compose exec web python manage.py migrate

# 2. Manual Method
Create virtualenv and activate it:
- virtualenv -p python3.8 venv
- source venv/bin/activate  
Install the dependencies:
- pip install -r requirements.txt
