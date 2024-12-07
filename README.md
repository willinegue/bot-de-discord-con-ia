# Discord Image Classification Bot  

Un bot de Discord diseñado para clasificar imágenes en tiempo real utilizando un modelo de aprendizaje automático entrenado con [Teachable Machine](https://teachablemachine.withgoogle.com/).  

---

## Descripción  

Este proyecto permite a los usuarios cargar imágenes en Discord y recibir una respuesta instantánea del bot con la clasificación correspondiente. El modelo de clasificación ha sido entrenado usando **Teachable Machine** y se integra en el bot a través de **Keras** y **TensorFlow**.  

### Características principales:  
- Procesa imágenes cargadas por los usuarios en canales de Discord.  
- Utiliza modelos de clasificación personalizados creados con herramientas accesibles.  
- Responde con etiquetas predichas, confianza del modelo, y más.  
- Compatible con múltiples servidores y canales.  

---

## Tecnologías  

El proyecto está desarrollado utilizando las siguientes herramientas:  
- **[Discord.py](https://discordpy.readthedocs.io/)**: Biblioteca para la creación de bots en Discord.  
- **[Keras](https://keras.io/)**: Framework para implementar modelos de aprendizaje automático.  
- **TensorFlow**: Base del motor de aprendizaje profundo para el modelo de clasificación.  
- **Teachable Machine**: Plataforma accesible para entrenar modelos ML rápidamente.  

---

## Instalación  
Sigue estos pasos para configurar y ejecutar tu bot de Discord:

Requisitos Previos
Antes de comenzar, asegúrate de tener lo siguiente:

Python 3.8 o superior instalado en tu computadora.
Una cuenta de Discord y acceso al Discord Developer Portal.
El sistema operativo configurado para usar pip (el gestor de paquetes de Python).

Paso 1: Clonar el Repositorio

Abre una terminal o consola.
Ejecuta el siguiente comando para clonar el repositorio del bot:

git clone https://github.com/tu_usuario/discord-bot.git
Cambia al directorio del proyecto:

cd discord-bot

Paso 2: Configurar Dependencias
Asegúrate de que tienes un entorno virtual configurado (opcional, pero recomendado):

python -m venv venv
source venv/bin/activate   # En Linux/Mac
venv\Scripts\activate      # En Windows
Instala las dependencias necesarias con pip:

pip install -r requirements.txt

Paso 3: Configurar el Token del Bot
Ve al Discord Developer Portal e inicia sesión.
Crea una nueva aplicación y añade un bot a ella.
Copia el token del bot.
En la carpeta raíz del proyecto, crea un archivo llamado .env y añade tu token:
env
Copiar código
DISCORD_TOKEN=tu_token_aqui
Paso 4: Configurar el Modelo de Clasificación
Si deseas usar tu propio modelo, entrena uno en Teachable Machine.
Exporta el modelo como TensorFlow - Keras.
Reemplaza el archivo de modelo existente en la carpeta del proyecto (por ejemplo, model.h5).
Paso 5: Ejecutar el Bot
Una vez configurado todo, ejecuta el bot con el siguiente comando:

bash
Copiar código
python bot.py
Si todo está configurado correctamente, deberías ver un mensaje en la consola indicando que el bot está conectado.

Paso 6: Añadir el Bot a tu Servidor
Ve al Discord Developer Portal y selecciona tu aplicación.
En la pestaña OAuth2, selecciona el permiso "Bot" y otros permisos necesarios (como "Enviar mensajes").
Genera un enlace de invitación y úsalo para añadir el bot a tu servidor.
