FROM python:3.11.4

ENV APP_HOME /app

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

ENTRYPOINT ["python", "main.py"]
