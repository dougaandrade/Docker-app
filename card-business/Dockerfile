FROM ubuntu:22.04

RUN apt-get update &&  apt-get install -y python3.11 --no-install-recommends python3.11-dev python3-pip
WORKDIR /app
COPY . .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8080

ENV FOTO='https://www.metacritic.com/a/img/catalog/provider/2/13/2-e5de927f1b005a0409f86e82b9e53934.jpg'
ENV NOME='DouG'
ENV IDADE='22'
ENV EMAIL='vaue@gmail.com'
ENV PROFISSAO='Developer'
ENV SITE='https://github.com/dougaandrade'

CMD ["python3", "app.py"]
