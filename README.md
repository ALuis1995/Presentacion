# Código fuente del evento de "Inteligencia Artificial para el reconocimiento facial en Python"
Se deja a continuacion el acceso al vídeo y resumen del evento se hará desde la propia web del [#campusFA](https://www.fundacionayesa.org/inteligencia-artificial-para-reconocimiento-facial-en-python/), de donde se ha tomadoreferencia para el desarrollo del proyecto 

## Cosas a tener en cuenta para ejecutar el proyecto
1. Se debe saber cómo crear entornos virtuales con Conda a partir de un fichero yml
2. OpenCV puede dar problemas a la hora de instalar desde el CMD de Anaconda. 

## Cómo replicar el proyecto
1. Desacargar el repositorio al ordenador 
2. Tener previamente instalado el software de Anaconda y ahí vendrá Jupyter.
3. Establecer Tensorflow como el backend de Keras con el siguiente comando. 
    ```set KERAS_BACKEND=tensorflow``` (para Windows)
   Para comprobar que todo está configurado correctamente:
        ```python -c "from keras import backend"```
4. Activar el entorno de desarrollo y hacer disponible este entorno virtual para ser ejecutado desde Jupyter. Se puede encontrar cómo hacerlo en [este enlace](https://help.pythonanywhere.com/pages/IPythonNotebookVirtualenvs/).
5. Seleccionar nuestro entorno virtual para que el kernel de Jupyter ejecute el código usando nuestras librerías.

## Autor:
**Luis García** - [ALuis1995](https://github.com/ALuis1995)
Udacity attribution as the original creators of this project in their full AI Nanodegree program.
Todo el código es libre de ser distribuido y modificado bajo la licencia Apache v2.0
