FROM python:3.7-alpine

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY src /src
WORKDIR /src
EXPOSE 5000

CMD python3 app.py


