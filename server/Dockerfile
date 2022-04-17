FROM python:3.9

EXPOSE 5000

WORKDIR /usr/src/app

COPY hello.py .

COPY requirements.txt requirements.txt 

RUN pip3 install -r requirements.txt

ENV FLASK_APP=hello

CMD flask run --host=0.0.0.0