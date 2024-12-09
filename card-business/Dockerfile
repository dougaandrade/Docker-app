FROM python:3.11

WORKDIR /app
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8080

ENV FOTO='https://www.metacritic.com/a/img/catalog/provider/2/13/2-e5de927f1b005a0409f86e82b9e53934.jpg'
ENV NOME='Nome'
ENV IDADE='Idade'
ENV EMAIL='E-mail'
ENV PROFISSAO='Profissao'
ENV SITE='Site'

COPY . .
CMD ["python3", "app.py"]
