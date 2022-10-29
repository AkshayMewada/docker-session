FROM python:3.7.15-alpine3.16

WORKDIR /app

RUN pip install flask

COPY . /app

ENTRYPOINT [ "python" ]

CMD ["app.py" ]