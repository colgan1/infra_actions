FROM python:3.7-slim
WORKDIR /app/infra_project/
COPY . ../
RUN pip install -r ../requirements.txt
CMD python manage.py runserver 0:5000
