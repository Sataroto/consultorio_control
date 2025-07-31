# Sistema de Gestión de Citas para Consultorio

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)

Este proyecto es una API RESTful diseñada para gestionar el agendamiento de citas en un consultorio médico. El objetivo es proporcionar una plataforma eficiente para que los pacientes puedan registrarse y reservar citas, y a futuro, permitir la administración por parte del personal del consultorio.

## 🎯 Objetivo del Proyecto (Fase 1)

El enfoque principal de la primera fase es entregar un Producto Mínimo Viable (MVP) que valide la funcionalidad central del sistema. El objetivo es permitir que un paciente pueda registrarse en la plataforma, autenticarse y agendar una nueva cita de forma autónoma.

## ✨ Características Actuales (Fase 1)

* **Autenticación de Pacientes:** Registro y login de usuarios de tipo "Paciente".
* **Gestión de Perfil:** Los pacientes pueden tener un perfil con su información básica.
* **Creación de Citas:** Los pacientes autenticados pueden crear nuevas citas en horarios disponibles.
* **Visualización de Citas:** (A futuro) Los pacientes podrán ver sus citas agendadas.

## 🛠️ Tecnologías Utilizadas

* **Backend:** Python, Django, Django REST Framework
* **Base de Datos:** SQLite (para desarrollo)

## 🚀 Puesta en Marcha

Para ejecutar este proyecto localmente, sigue estos pasos:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/Sataroto/consultorio_control.git](https://github.com/Sataroto/consultorio_control.git)
    cd consultorio_control
    ```
2.  **Crea y activa un entorno virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    cd consultorio
    ```
3.  **Instala las dependencias:**
    ```bash
    pip install -r requirements.txt 
    ```

4.  **Aplica las migraciones:**
    ```bash
    python manage.py migrate
    ```

5.  **Ejecuta el servidor de desarrollo:**
    ```bash
    python manage.py runserver
    ```# Sistema de Gestión de Citas para Consultorio
