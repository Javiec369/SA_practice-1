# Leer para el desarrollo de la práctica

> [!NOTE]
> Se presenta en la tabla de contenidos algunas instalaciones adicionales para el desarrollo de la práctica. Asimismo, se detalla en cada paso como realizar correctamente dichas instalaciones. 

## Tabla de contenidos

- [Videos acerca del ECG y EEG](#Videos)
- [Descarga OpenBCI GUI](#OpenBCI)
- [FTDI Drivers](#FTDIDrivers)
- [Arduino](#Arduino)
- [Entornos virtuales](#venv)
<hr />

## Videos acerca del ECG y EEG

Un electrocardiograma, abreviado como ECG, es un método de monitorización de la actividad, la velocidad y el ritmo cardíaco. Cuando el corazón está en funcionamiento, este se contrae y emite variaciones en la corriente eléctrica. En ese momento, el electrocardiograma registra esas variaciones en forma de curva. A través de la lectura del electrocardiograma, podemos conocer la capacidad del corazón para expulsar sangre, el ritmo y la velocidad del corazón. Un video explicativo de este estudio se muestra en el siguiente [enlace](https://www.youtube.com/watch?v=xIZQRjkwV9Q&t=424s).

El electroencefalograma, abreviado como EEG, registra la actividad bioeléctrica del cerebro mediante electrodos colocados en el cuero cabelludo, en raras ocasiones en la superficie de la corteza cerebral o en la masa encefálica. Esta actividad eléctrica se manifiesta en forma de ondas en el electroencefalograma. Un video explicativo de este estudio se muestra en el siguiente [enlace](https://www.youtube.com/watch?v=T7MKlPYiL48&t=19s).


## OpenBCI

Ésta es una interfaz gráfica de usuario (GUI) independiente para su sistema operativo. la cual permite conectarse al hardware OpenBCI de manera rápida para visualizar datos fisiológicos y transmitirlos a otras aplicaciones y herramientas. Para esto, se debe descargar la GUI desde el siguiente [enlace](https://openbci.com/downloads).


## FTDI Driver

Estos drivers permiten la comunicación entre la tarjeta de desarollo (Cyton en este caso) y el Dongle, que es dispositivo USB que recibe los datos de la Cyton. La descarga se realiza desde el siguiente [enlace](https://ftdichip.com/drivers/vcp-drivers/) y dependen del sistema operativo en uso.

## Arduino

Se debe instalar el software Arduino, el cual se descarga del sigueinte [enlace](https://www.arduino.cc/en/software). Además, se debe instalar la librería Firmata como se muestra a continuación:


 
<p align="center">
   <img src="https://github.com/Javiec369/SA-IE763Labs/assets/87388852/b7dfba93-d6fd-4e62-9feb-01cd2f657e06" width="470" height="370"/>
</p>


## VENV

Para la correcta ejecución de la práctica se requieren instaladas algunas librerías o paquetes de Python. A continuación, los pasos a seguir para realizar la creación de un entorno virtual que nos permite crear un espacio aislado para un proyecto, con su propio conjunto de dependencias, independientemente de las que se instalen en el sistema global. 

### Para Windows
1. Crear un directorio para la práctica. Añadir el número de la práctica al final del nombre.
   
    ```bash
    mkdir Lab_SA
    cd Lab_SA
    ```

2. Una vez dentro de ese directorio, dar click derecho y abrir una terminal o consola. Posteriormente ejecutar el comando:

    ```bash
    python -m venv venv
    ```

<p align="center">
   <img src="https://github.com/Javiec369/SA_practice-1/assets/87388852/e65a1d3b-22a1-4e62-b51a-acb7cabdcc91" width="470" height="370"/>
</p>


3. Activar el entorno virtual (desde la terminal) ejecutando:

    - En Windows:

        ```bash
        .\venv\Scripts\activate
        ```

    - En macOS y Linux:

        ```bash
        source venv/bin/activate
        ```

4. Descargar el archivo `requirements.txt` dentro de la carpeta [Lab_SA2](https://github.com/Javiec369/SA-IE763Labs/blob/main/Laboratorios%202024-2/Lab_SA2/requirements.txt).

5. Ejecutar el siguiente comando en la terminal para la instalación de las librerías.

    ```bash
    pip install -r requirements.txt
    ```

6. Verificar que las librerías han sido instaladas correctamente.

    ```bash
    pip list
    ```
    
<p align="center">    
<img src="https://github.com/Javiec369/SA_practice-1/assets/87388852/ec432bcb-ecbe-4fad-a5aa-40b8a4259b39" width="470" height="370"/>
</p>
