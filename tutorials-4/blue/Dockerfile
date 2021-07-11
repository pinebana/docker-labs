FROM python:3.8-slim-buster
RUN mkdir /blue && mkdir /blue/templates
RUN pip install flask
COPY ./blue.py                /blue/blue.py
COPY ./templates/index.html   /blue/templates/index.html
EXPOSE 5000
WORKDIR /blue
CMD ["python3","blue.py"]