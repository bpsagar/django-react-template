FROM python:3.6

ENV PYTHONBUFFERED 1

# Install pip requirements
COPY ./requirements/base.txt /requirements/base.txt
COPY ./requirements/local.txt /requirements/local.txt
RUN pip install -r /requirements/local.txt

# Copy the code
COPY . /app
WORKDIR /app

EXPOSE 8000
