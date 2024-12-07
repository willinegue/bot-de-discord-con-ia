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

1 ten python 3.11.9
2 ten una cuenta de discord

primero instales 
pipenv shell
pipenv install discord.py
pipenv install numpy
pipenv install keras
pipenv install requests
pipenv install tensorflow
pipenv install Pillow

y a lo ultimo pon tu token si no sabes ve a https://discord.com/developers/applications y hay va a estar
