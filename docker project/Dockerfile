# FROM python:3.9

FROM python:3.11-alpine

WORKDIR /app

COPY . .
RUN pip install flask redis

COPY . .
 
EXPOSE 5000

CMD ["python", "app.py"]
