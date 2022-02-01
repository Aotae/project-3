FROM python:3.8
LABEL maintainer="Nathan Pang nathan.ao.pang@gmail.com"
RUN apt-get update -y
COPY . /app
WORKDIR /app
RUN python -m pip install -U pip
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]
