# finalera

Projeto Django mínimo com app `blog`, modelo `Post` e registro no Django Admin.

## Requisitos
- Python 3.10+
- Pip

## Setup rápido

```bash
# (Opcional) criar e ativar venv
python -m venv .venv
.\.venv\Scripts\activate

# instalar dependências
pip install -r requirements.txt

# criar migrações e banco
python manage.py makemigrations
python manage.py migrate

# criar superusuário para acessar o admin
python manage.py createsuperuser

# rodar o servidor
python manage.py runserver
```

Acesse o Django Admin em: http://127.0.0.1:8000/admin/ e veja `Post`.
