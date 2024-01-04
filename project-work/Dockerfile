FROM python:3.12-slim
RUN apt update \
  && apt install libpq-dev gcc -y \
  && pip install Flask Psycopg2 ConfigParser \
ENTRYPOINT /srv/app/web.py
