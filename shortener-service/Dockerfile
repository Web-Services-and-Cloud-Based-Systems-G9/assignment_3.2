FROM python:3.8

ADD . /app
WORKDIR /app
RUN pip install -r requirements.txt

EXPOSE 8080

CMD ["python3", "./ShortyURL.py"]


