# SimpleMOOC - Ensino a distância

## Do que se trata?
Plataforma simples de ensino a distância de cursos abertos utilizando embed videos, com base em um [curso de Djando](https://www.udemy.com/course/python-3-na-web-com-django-basico-intermediario/) do [Professor Gileno Filho](https://www.udemy.com/user/gilenofilho/), na [Udemy](https://www.udemy.com).

O projeto é basicamente um painel de controle da instituição onde pode ser cadastrado cursos e aulas em videos podendo ser do youtube ou outros que geram código embed e um painel do aluno para interagir com fórum e as aulas.

## Este projeto foi feito com:
- Python 3.8.2
- pip 20.1
- Django 3.0.6

## Como rodar o projeto?
1. Clone esse repositório.
    ```
    1. git clone https://github.com/RamonAlves1357/Simple_Mooc/
    2. cd Simple_Mooc
    ```
2. Crie um virtualenv com Python 3.
    ```
    3. python3 -m venv .venv
    ```
3. Ative o virtualenv.
    - No linux ou MacOS: 
        ```
        4. source .venv/bin/activate
        ```
    - No Windows:
        ```
        4. .venv\scripts\activate
        ```

4. Instale as dependências.
    ```
    5. pip install --upgrade pip
    6. pip install django
    7. pip install -r requirements.txt
    8. python contrib/env_gen.py
    ```

5. Rode as migrações.
    ```
    9. python manage.py migrate
    10. python manage.py createsuperuser
    11. python manage.py runserver
    ```
