FROM python:3.8.5-alpine3.12

WORKDIR /app

EXPOSE 80
ENV FLASK_APP=app.py

COPY ./src .
RUN pip3 install -r requirements.txt

ENTRYPOINT ["flask", "run"]

CMD ["--port=80"]