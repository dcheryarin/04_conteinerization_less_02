FROM python:3.6.8

ADD requirements.txt .
RUN pip install -r requirements.txt

ADD . /python

ENTRYPOINT python /python/app.py localhost:8080
