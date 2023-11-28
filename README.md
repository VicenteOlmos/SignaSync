# Modelo para Lenguaje de señas chileno
Modelo hecho para el ramo ELO328 PROCESAMIENTO DIGITAL DE IMAGENES de la carrera de Ingeniería Civil Telemática de la Universidad Técnica Federico Santa María.

Mediante el siguiente comando se instalan todos los paquetes necesarios:
````
pip install albumentations opencv-python-headless glob2 ultralytics roboflow matplotlib
````

Para la clasificacion de imagenes y obtentencion de dataset se utilizo roboflow.

El modelo de letras, el cual esta entrenado con YOLOv8, pudiendo reconocer todas las letras del abecedario.

El modelo de palabras esta entrenado Roboflow v2 classification, pudiendo reconocer 5 frases, las cuales son:
- ¿Cómo estás?
- Disculpa
- Hola
- Dónde
- Vives



## Integrantes
- Fernando Amthauer
- Vicente Olmos



