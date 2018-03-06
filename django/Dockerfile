FROM python:alpine
RUN apk update \
  && apk add --virtual build-deps gcc python3-dev musl-dev \
  && apk add postgresql-dev \
  && pip install circus django-bulk-update psycopg2 Django PyMySQL SQLAlchemy Django-crontab numpy pandas patsy webencodings wheel statsmodels \
  && apk del build-deps

