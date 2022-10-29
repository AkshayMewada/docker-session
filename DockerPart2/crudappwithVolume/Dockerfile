FROM python:3.7.15-alpine3.16

WORKDIR /app

COPY ./requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY . /app

VOLUME /app

ENTRYPOINT [ "python" ]

CMD ["app.py" ]