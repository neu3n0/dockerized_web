FROM python:3

ENV PYTHONUNBUFFERED=1
WORKDIR /usr/src/app

COPY . /usr/src/app
RUN pip install django

ENTRYPOINT [ "./entrypoint.sh" ]
