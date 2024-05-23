FROM python:3

ENV PYTHONUNBUFFERED=1
ENV PYTHONDONTWRITEBYTECODE=1

WORKDIR /usr/src/app

COPY . /usr/src/app

RUN chmod +x entrypoint.sh
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

ENTRYPOINT [ "./entrypoint.sh" ]
