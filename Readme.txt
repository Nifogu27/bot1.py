# Proyecto: Bot de Discord

## Descripción
Este es un bot de Discord desarrollado utilizando la biblioteca `discord.py`. El bot tiene múltiples comandos que permiten a los usuarios interactuar y recibir memes, imágenes de animales y recomendaciones de películas.

## Requisitos
- Python 3.8 o superior
- Biblioteca `discord.py`
- Descargar otras bibliotecas en la terminal (Pip install "...") como: requests, os, time.
- Acceso a la API de Discord (un token de bot)

## Instalación
1. Clona el repositorio:
git clone <URL del repositorio>

css
Copiar código
2. Navega al directorio del proyecto:
cd <nombre del directorio>

markdown
Copiar código
3. Instala las dependencias necesarias:
pip install -r requirements.txt

markdown
Copiar código

## Estructura de Archivos
- `bot.py`: Archivo principal que contiene la lógica del bot.
- `settings.py`: Archivo que contiene la configuración, como el token del bot.
- `images/`: Carpeta que contiene imágenes y memes utilizados por el bot.
- `mem2.jpg`: Un meme específico.
- Subcarpetas para categorías de memes (e.g., `animales`, `deportes`, `tecnologia`).

## Comandos Disponibles
- **$hello**: Saluda al usuario.
- **$heh [n]**: Repite "he" [n] veces (por defecto 5).
- **$mem**: Envía un meme específico.
- **$mem1**: Envía un meme aleatorio de la carpeta de imágenes.
- **$animal**: Envía un meme de la categoría "animales".
- **$deporte**: Envía un meme de la categoría "deportes".
- **$tecnologia**: Envía un meme de la categoría "tecnología".
- **$duck**: Envía una imagen aleatoria de un pato.
- **$dog**: Envía una imagen aleatoria de un perro.
- **$fox**: Envía una imagen aleatoria de un zorro.
- **$add [num1] [num2]**: Suma dos números.
- **$joined [@usuario]**: Muestra cuándo se unió un usuario al servidor.
- **$choose [opcion1] [opcion2] ...**: Elige entre múltiples opciones.
- **$contaminacion**: Habla sobre la contaminación y da consejos.
- **$peliculas**: Recomienda películas y plataformas para verlas.
- **$ayuda**: Muestra la lista de comandos disponibles.

## Uso
Para iniciar el bot, ejecuta el siguiente comando en la terminal:
python bot.py

## Contribuciones