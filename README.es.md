Español| [English](README.md)

# Star Wars REST API (Flask)

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-000000?logo=sqlalchemy&logoColor=white)](https://www.sqlalchemy.org/)

<br>

> **⚠️ Nota:** Este es un proyecto de aprendizaje antiguo (legacy) desarrollado durante mi formación como Full Stack Developer en **4Geeks Academy**. Se centra en el diseño de APIs RESTful, modelado de bases de datos relacionales y lógica de servidor con Python.

<br>

Backend construido con **Python** y **Flask** para gestionar la base de datos de un blog de Star Wars. Maneja usuarios, personajes, planetas y un sistema de favoritos personalizado mediante una arquitectura relacional y el ORM SQLAlchemy.

<br>

## Implementación Backend

La base de datos está estructurada en torno a **Usuarios**, **Personajes**, **Planetas** y **Favoritos**, utilizando una lógica de relación Many-to-Many. A continuación, se muestra un fragmento de los modelos relacionales y la lógica de serialización:

![Backend Code Snippet](./assets/preview-code.png)

<br>

## Tecnologías y Herramientas

- Python
- Flask 
- Flask-SQLAlchemy 
- Pipenv

<br>

## Instalación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Antonio-Borrero/starwars-rest-api.git
   ```
2. Instalar dependencias:
   ```bash
   pipenv install
   ```
3. Inicializar la Base de Datos y Migraciones:
    ```bash
   pipenv run init
   pipenv run migrate
   pipenv run upgrade
   ```
4. Ejecuta el servidor:
   ```bash
   pipenv run start
   ```

<br>

## Resultados de Aprendizaje

- **Diseño de Bases de Datos Relacionales:** Creación de modelos de Entidad-Relación y manejo de relaciones (One-to-Many/Many-to-Many).
- **Flujo de Trabajo Backend:** Aprendizaje del ciclo de actualización de modelos, migraciones y pruebas de endpoints con Postman.
