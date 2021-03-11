FROM python:3.6.7

RUN mkdir -p /home/project/flask
WORKDIR /home/project/flask
COPY requirements.txt /home/project/flask
RUN pip install --no-cache-dir -r requirements.txt

COPY . /home/project/flask

