FROM python:3.9
LABEL maintainer="Ahmed Hussein"

COPY . /app
WORKDIR /app
RUN pip install -r ./solutions/python-helloworld/requirements.txt

# command to run on container start
CMD [ "python", "app.py" ]
