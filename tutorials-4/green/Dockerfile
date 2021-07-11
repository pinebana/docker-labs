FROM python:3.8-slim-buster
RUN mkdir /green && mkdir /green/templates
RUN pip install flask
COPY ./green.py                /green/green.py
COPY ./templates/index.html    /green/templates/index.html
EXPOSE 5000
WORKDIR /green
ENTRYPOINT [ "python3","green.py" ]