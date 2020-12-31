FROM python:3.8
ENV PYTHONUNBUFFERED 1

ADD /src /src/
ADD requirements.txt /src/
WORKDIR /src

RUN pip install --upgrade pip
RUN pip install wheel
RUN pip install -r requirements.txt
