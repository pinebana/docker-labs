FROM python:3.8-slim-buster
RUN useradd -U -u 5000 -ms /bin/bash yoteri
COPY --chown=yoteri:yoteri ./sleep.py /home/yoteri/sleep.py
USER yoteri
WORKDIR /home/yoteri
ENTRYPOINT [ "python3","./sleep.py" ]
