# Django_v1
Primer Proyecto Django


Proyecto Básico en Django
Este proyecto tiene como objetivo levantar un proyecto Django básico para visualizar la página de bienvenida de Django. Este es el primer paso para familiarizarse con el framework.

Índice
Requisitos Previos
Configuración del Entorno
Creación del Proyecto
Iniciar el Servidor de Desarrollo
Probar la Página Inicial
1. Requisitos Previos
Antes de comenzar, asegúrate de tener:

Python 3.8 o superior instalado en tu máquina.
pip (el gestor de paquetes de Python) instalado.
Un editor de texto (opcional, pero recomendado: Visual Studio Code).
2. Configuración del Entorno
Crear un Entorno Virtual
Abre tu terminal o línea de comandos.
Crea un entorno virtual:
python -m venv venv
Activa el entorno virtual:
En Windows:
venv\Scripts\activate
En macOS/Linux:
source venv/bin/activate
Instalar Django
Con el entorno virtual activado, instala Django:

pip install django
3. Creación del Proyecto
Crea un nuevo proyecto Django llamado my_project:
django-admin startproject my_project
Navega a la carpeta del proyecto:
cd my_project
4. Iniciar el Servidor de Desarrollo
Con el proyecto creado, inicia el servidor de desarrollo ejecutando:

python manage.py runserver
5. Probar la Página Inicial
Abre tu navegador web.
Ve a la URL que aparece en tu terminal, generalmente:
http://127.0.0.1:8000/
Deberías ver la página de bienvenida de Django, que incluye el texto: "The install worked successfully! Congratulations!"
Conclusión
¡Felicidades! Has levantado tu primer proyecto Django y accedido a la página de bienvenida. Este es el primer paso para desarrollar aplicaciones más avanzadas con Django. A partir de aquí, puedes comenzar a agregar aplicaciones, modelos, vistas y más.