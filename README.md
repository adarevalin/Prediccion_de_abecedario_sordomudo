# Predicción del Abecedario Sordomudo mediante Imágenes

Este proyecto utiliza aprendizaje automático para crear un modelo capaz de reconocer el abecedario en lengua de señas utilizando imágenes de las manos. Incluye todo el código necesario para crear el dataset, entrenar el modelo y realizar predicciones en tiempo real.

## Contenido

- `Manos.py`: Script para la creación del dataset de imágenes.
- `Entrenamiento.py`: Script para entrenar la red neuronal.
- `Prediccion.py`: Script para ejecutar el modelo en tiempo real.

## Requisitos

Asegúrate de tener instaladas las siguientes dependencias antes de ejecutar el proyecto. Se recomienda usar un entorno virtual para gestionar las dependencias.

- Python 3.x
- OpenCV
- TensorFlow
- NumPy

## Instalación

1. Clona este repositorio:
    ```sh
    git clone https://github.com/tuusuario/abecedario-sordomudo.git
    ```
2. Navega al directorio del proyecto:
    ```sh
    cd abecedario-sordomudo
    ```
3. Crea un entorno virtual (opcional pero recomendado):
    ```sh
    python -m venv venv
    source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
    ```
4. Instala las dependencias:
    ```sh
    pip install -r requirements.txt
    ```

## Creación del Dataset

Para crear tu propio dataset de imágenes, ejecuta el script `Manos.py`. Este script capturará imágenes de tus manos haciendo diferentes señales del abecedario y las guardará en la carpeta especificada.

```sh
python Manos.py
