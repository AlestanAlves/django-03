# Django

- **Rodar servidor em outra porta:** `python3 manage.py runserver 9000`
- **Criar um usuario do admin:** `python3 manage.py createsuperuser`
- **Importar todas as models de um app no admin.py:** `from website.models import *`
- **Em admin.py adicionar os dados no /admin:** `admin.site.register(Coach)`
- **Criar super usuario:** `python manage.py createsuperuser`
- **form:get:** `gera uma informação via URL`
- **form:post:** `gera informação via post`
- **form action:** `toda vez que criar um formulario no django tem que colocar isso {% csrf_token %}`
- **form action:** `action="/" para ir para algum lugar`
- **Criar na view o objeto de cadastro:** `


## CSRF TOKEN

<img src="https://www.digitalmunition.me/wp-content/uploads/2018/04/csrf-cross-site-request-forgery-620x350-c.png" />
