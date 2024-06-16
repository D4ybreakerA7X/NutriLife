<h1 align="center">
  SISTEMA WEB DE ANALISIS NUTRICIONAL PARA FAMILIAS MEXICANAS “NUTRILIFE”
</h1>
<p align="center">
  <a href="#tecnologias-e-práticas-utilizadas">Tecnologias e práticas utilizadas</a> •
  <a href="#funcionalidades">Funcionalidades</a> •
  <a href="#comandos">Comandos</a>
</p>

## Tecnologias  utilizadas
- Python 3.8
- Django 4.2
- SQLite
- Arquitetura MVT

## Funcionalidades
Aplicación web que funcione como una lista de compras de alimentos, permitiendo a los usuarios controlar sus compras y mantener un registro de lo que consumen. Además, la aplicación analizará estos datos junto con información proporcionada por el usuario, como el número de miembros del hogar y sus edades, para ofrecer recomendaciones nutricionales personalizadas y sugerencias de recetas equilibradas en base a los alimentos que sé tienen en casa. La aplicación busca promover hábitos alimenticios saludables al facilitar la planificación y preparación de comidas, así como ofrecer orientación nutricional basada en el análisis de datos.


###

![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/cadastre-se.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/logar.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/gerenciar_pacientes.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/novo_paciente.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/dados_dos_pacientes.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/dados_do_paciente.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/dados_do_paciente_detalhes.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/plano_alimentar_paciente.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/adicionar_refeicao.png)
![alt text](https://raw.githubusercontent.com/samuel-oldra/NutriLab/main/README_IMGS/adicionar_opcao.png)

## Comandos

### pip
```
pip list --outdate
pip install --upgrade pip setuptools Django ...
```

### virtualenv (windows)
```
python -m venv env
env\Scripts\activate.bat
env\Scripts\deactivate.bat
```

### Instalar bibliotecas, gravar/instalar requerimentos
```
(env) pip install Django
(env) pip install Pillow

(env) pip freeze > requirements.txt
(env) pip install -r requirements.txt
```

### Criar projeto
```
(env) django-admin startproject nutrilab .
```

### Criar super user (Django Administration)
```
(env) python manage.py createsuperuser (admin/admin)
```

### Criar apps
```
(env) python manage.py startapp autenticacao
(env) python manage.py startapp plataforma
```

### Migrations
```
(env) python manage.py makemigrations
(env) python manage.py migrate
```

### Executar projeto
```
(env) python manage.py runserver
```
