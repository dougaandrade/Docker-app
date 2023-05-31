# Projetos do curso 'Docker Essencial: Primeiros Passos'
Repositório destinado a todos os projetos que competem ao curso 'Docker Essencial: Primeiros Passos'.

## Projeto: Cartão de Visitas (card-business) - Python/Flask
### 1 - O que é?
Cartão de visitas web desenvolvido em Python com Flask com intuito educacional.

### 2 - Pré-requisitos
- Python (versão 3)
- Pip
- Flask

**2.1 - Instalação dos pré-requisitos (Exemplo: GNU/Linux Debian 11)**
1. Atualize os repositórios com `sudo apt update` 
2. Instale os pacotes `sudo apt install python3.9 python3.9-dev python3.9-venv python3-pip -y`
3. Atualize o pip com `sudo pip3 install --upgrade pip`

### 3 - Configurando variáveis de ambiente
O projeto trabalha com algumas variáveis de ambientes para definir valores presentes no cartão web, são elas:
- LOGOMARCA
- FOTO
- NOME
- IDADE
- EMAIL
- PROFISSAO
- SITE
Exporte-as para aplicar seus valores.
Você pode defini-las em algum local de sua preferência de modo que sejam carregadas no sistema.

**3.1 - Exportando Variáveis de Ambiente**
Adicione o trecho abaixo ao `/etc/profile`, por exemplo:
```bash
export LOGOMARCA='DEFINA O SEU VALOR: LINK PARA LOGOMARCA'
export FOTO='DEFINA O SEU VALOR: LINK PARA FOTO DO PERFIL'
export NOME='DEFINA SEU VALOR: SEU NOME'
export IDADE='DEFINA SEU VALOR: SUA IDADE'
export EMAIL='DEFINA SEU VALOR: SEU EMAIL'
export PROFISSAO='DEFINA SEU VALOR: SUA PROFISSAO'
export SITE='DEFINA SEU VALOR: SEU SITE'
```
E aplique suas configurações com `source /etc/profile`

### 4 - Como executar (Exemplo: GNU/Linux Debian 11)?
1. Crie um ambiente virtual (opcional)
  1.1. Entre no diretório do projeto e execute `python3 -m venv venv`
  1.2. Ative o ambiente virtual com `source venv/bin/activate`
  1.3. Instale as dependências com `pip install --no-cache-dir -r requirements.txt`
2. Execute o projeto com `python app.py`

### 5 - Como Acessar?
Com a aplicação em execução abra o navegador em `localhost:8080`
