FROM python:3

#WORKDIR /src

ADD src/index.html src/index.html
ADD src/web_server.py src/web_server.py

EXPOSE 8000
ENTRYPOINT ["python3", "src/web_server.py"]