# Як запустити проект Flask:

pip install -r requirements.txt
python app.py
docker build -t flask-app .
docker run -p 5005:5005 flask-app