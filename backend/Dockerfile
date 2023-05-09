FROM python:3.11-slim

ENV PYTHONBUFFERED 1
ENV PYTHONDONTWRITEBYCODE 1

WORKDIR /app/backend

COPY requirements.txt /app/backend/

COPY . /app/backend/

CMD ["python", "manage.py", "runserver", "0.0.0.0:8011"]