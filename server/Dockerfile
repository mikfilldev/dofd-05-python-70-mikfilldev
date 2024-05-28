FROM python:3.12.3-alpine3.20

ADD server.py /server/
ADD index.html /server/

WORKDIR /server/

CMD ["python", "./server.py"]

EXPOSE 8000