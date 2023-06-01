FROM python:3

RUN apt-get update -y && \
    apt-get install python3-pip python3-dev -y
    
WORKDIR /app

RUN pip3 install Flask

RUN pip3 install requests

COPY . /app

EXPOSE 5000

CMD ["python3", "./app.py"]

