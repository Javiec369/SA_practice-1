# Creación de un entorno virtual

Para la correcta ejecución de la práctica se requieren instaladas algunas librerías o paquetes de Python. A continuación, los pasos a seguir para realizar la creación de un entorno virtual que nos permite crear un espacio aislado para un proyecto, con su propio conjunto de dependencias, independientemente de las que se instalen en el sistema global. 

1. Crear un directorio para la práctica. Añadir el número de la práctica al final del nombre.
   
    ```bash
    mkdir Lab_SA
    cd Lab_SA
    ```

2. Una vez dentro de ese directorio, dar click derecho y abrir una terminal o consola. Posteriormente ejecutar el comando:

    ```bash
    python -m venv venv
    ```

3. Activar el entorno virtual (desde la terminal) ejecutando:

    - En Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - En macOS y Linux:

        ```bash
        source venv/bin/activate
        ```

4. Descargar el archivo `requirements.txt` desde el [repositorio](https://github.com/Javiec369/SA_practice-1/tree/main/Lab1_2024-2) asignado a la práctica.

5. Guardar el archivo `.txt` en el directorio creado para la práctica y ejecutar el siguiente comando dentro del directorio para realizar la instalación de las librerías.

    ```bash
    pip install -r requirements.txt
    ```

6. Verificar que las librerías han sido instaladas correctamente utilizando el siguiente comando nuevamente en la terminal.

    ```bash
    pip list
    ```

## Visualización de ejemplo 

Creación del entorno virtual.

<img src="https://github.com/Javiec369/SA_practice-1/assets/87388852/e65a1d3b-22a1-4e62-b51a-acb7cabdcc91" width="500" height="450"/>

Instalación de los paquetes y/o librerías.

<img src="https://github.com/Javiec369/SA_practice-1/assets/87388852/ec432bcb-ecbe-4fad-a5aa-40b8a4259b39" width="500" height="450"/>