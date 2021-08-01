FROM python:3.9.6-slim
RUN pip install flask==2.0.1
WORKDIR /src
COPY ./src/server.py /src/
ENV PORT 80
ENTRYPOINT ["python", "-u", "server.py"]