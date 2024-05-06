# UrbanMED
Projeto de agendamento de consultas online para o workspace Urban.

## Requisitos
Certifique-se de que você tenha os seguintes requisitos instalados em seu sistema:

- Python (versão recomendada: 3.7 ou superior)
- Django (instalado automaticamente ao seguir as instruções abaixo)
- Outras dependências listadas no arquivo `requirements.txt`

## Instalação das Dependências
Com o ambiente virtual ativado, instale as dependências do projeto usando o comando:

    pip install -r requirements.txt

## Rodar o projeto
Após instalar as dependências, aplique as migrations no banco de dados com o comando:

    python manage.py migrate

Agora o projeto já pode ser inicializado com o comando:

    python manage.py runserver

Após isso, o sistema estará pronto para ser acessado em: http://localhost:8000
