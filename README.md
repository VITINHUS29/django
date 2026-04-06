#  Projeto Django - Times de Futebol

Aplicação web desenvolvida com Django para cadastro e visualização de times de futebol.

---

##  Funcionalidades

* Cadastro de times pelo painel administrativo
* Visualização de todos os times em uma página web
* Estrutura baseada no padrão MVT (Model-View-Template)

---

## Tecnologias utilizadas

* Python
* Django
* SQLite (banco de dados padrão do Django)
* HTML

---

## 📁 Estrutura do Projeto

```
DJANGO/
│
├── futebol/        # Configurações do projeto
├── times/          # Aplicação principal
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   └── times/
│   │       └── lista_times.html
│
├── manage.py
├── requirements.txt
└── .gitignore
```

---

## Como executar o projeto

###  Clonar o repositório

```
git clone https://github.com/VITINHUS29/django.git
cd django
```

---

###  Criar e ativar ambiente virtual

```
python -m venv venv
venv\Scripts\activate
```

---

## Instalar dependências

```
pip install -r requirements.txt
```

---

###  Aplicar migrações

```
python manage.py makemigrations
python manage.py migrate
```

---

###  Criar superusuário

```
python manage.py createsuperuser
```

---

###  Executar o servidor

```
python manage.py runserver
```

---

##  Acessos

* Página principal: http://127.0.0.1:8000/
* Admin: http://127.0.0.1:8000/admin/

---

## Como usar

1. Acesse o painel administrativo
2. Faça login com o superusuário criado
3. Cadastre novos times
4. Visualize os times na página inicial

---

##  Modelo de Dados

### Time

* nome (CharField)
* cidade (CharField)
* fundacao (IntegerField)

---

##  Possíveis melhorias

* Implementar edição e exclusão de times na interface
* Adicionar sistema de busca
* Melhorar o layout com Bootstrap
* Criar API REST com Django REST Framework
* Deploy em plataformas como Render ou Heroku

---

##  Autor

Desenvolvido por **VITINHUS29**

---

##  Licença

Este projeto é apenas para fins educacionais.
