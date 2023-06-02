# :gun: WeaponDetectionYOLOv5
En este repositorio puede encontrarse tanto el código necesario para entrenar, aplicar y testear el modelo YOLOv5s para la detección de armas cortas y largas de fuego, como los datos utilizados, modelos entrenados y resultados obtenidos.

## :page_facing_up: Memoria del proyecto
La memoria explicativa del proyecto es **Memoria.pdf**

## :notebook: Google Colab Notebook 
En el cuaderno de Google Colab de nombre **WeaponDetectionYOLOv5** se encuentra el código utilizado para el entrenamiento, validación del modelo YOLOv5s para la detección de armas. Las instrucciones a seguir para ejecutarlo correctamente se incluyen a modo de celdas de texto en el propio cuaderno. Basta con ejecutar las mismas en el orden en el que aparecen. 
## :alembic: Experimentos

Para acceder a los experimentos: https://drive.google.com/drive/folders/15O3lpCT-JYyuhEc5WftPzr0vCELjLPSS?usp=drive_link  
En el link encontraremos una carpeta por cada experimento que contendrá los datasets usados y los resultados obtenidos.

### Datasets
En la carpeta **DATASETS** se incluyen los distintos datasets utilizados en el experimento descritos en la memoria. 
Incluyen las imágenes subdivididas en carpetas train, valid y test, o solo test en caso de que el dataset haya sido utilizado para comprobar el rendimiento del modelo entrenado ante unas condiciones determinadas. Contienen también un fichero de extensión Yaml donde se indica la ruta de las imágenes en carpetas del dataset. 

:warning: En algunos caso será necesario modificar la ruta en el fichero Yaml para que detecte las imágenes correctamente en Google Colab adaptandolo al directorio de Drive donde estén contenidas. En el cuaderno de Google Colab se explica con más detalle como modificarlo.


### Resultados 
En la carpeta **RESULTADOS** se encuentran los resultados obtenidos a la hora de detectar las armas para cada experimento así como los resultados de las métricas de evaluación.


### Modelos
Los modelos ya entrenados basados en YOLOv5s y YOLOv5m se incluyen en la carpeta **Modelos**. YOLOv5s es el utilizado en los experimentos.
Si no se quisiera reentrenar, puede usarse los modelos aquí contenidos.


