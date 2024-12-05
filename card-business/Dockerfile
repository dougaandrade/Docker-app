FROM ubuntu:22.04

RUN apt-get update && apt-get install -y python3.13 apt-get install -y python3.13-dev apt-get install -y python3-pip

WORKDIR /app
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8080

ENV LOGOMARCA='Doug'
ENV FOTO='AAAAAA'
ENV NOME='DouG'
ENV IDADE='22'
ENV EMAIL='@VALUE.COM'
ENV PROFISSAO='Programador'
ENV SITE='https://github.com'


CMD ["python3", "app.py"]
