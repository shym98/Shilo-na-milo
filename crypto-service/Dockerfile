FROM python:3.6
RUN apt-get update
RUN mkdir /app
WORKDIR /app
COPY . /app
RUN pip3 install --no-cache-dir -r requirements.txt
ENV FLASK_ENV="docker"
ENV FLASK_APP="app"
EXPOSE 5000
CMD python3 -m flask run --host=0.0.0.0 --port=5000
