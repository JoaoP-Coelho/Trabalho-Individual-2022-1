FROM python:3.8

ENV PYTHONUNBUFFERED=1

RUN mkdir /app
WORKDIR /app
#COPY . /app

COPY requirements.txt /app/

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

COPY . /app/

#COPY library_back/dependencies.sh .
#CMD ["sh", "dependencies.sh"]

