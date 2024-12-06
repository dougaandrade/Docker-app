FROM ubuntu:22.04

RUN apt-get update &&  apt-get install -y python3.11 --no-install-recommends python3.11-dev python3-pip

WORKDIR /app
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8080

ENV LOGOMARCA='none'
ENV FOTO='none'
ENV NOME='DouG'
ENV IDADE='22'
ENV EMAIL='vaue@gmail.com'
ENV PROFISSAO='Developer'
ENV SITE='https://github.com'


CMD ["python3", "app.py"]
