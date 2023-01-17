# 24-Camera-Web-Server-ESP32

# Introducción

"CameraWebServer" es un sketch de ejemplo de Arduino para la placa ESP32CAM, que permite utilizar la cámara integrada en la placa para tomar fotos y transmitirlas a través de un servidor web. Una vez que el sketch está cargado en la placa ESP32CAM, se puede acceder a la cámara a través de un navegador web en un dispositivo conectado a la misma red Wi-Fi que la placa.

# Material Necesario

- [Instalar y Configurar Arduino IDE](https://github.com/RaulToribio/23-Instalar-y-Configurar-Arduino-IDE)

# Material de Referencia

- [Configuración del IDE para ESP32-CAM](https://edu.codigoiot.com/course/view.php?id=850)

# Instrucciones

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(1).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(1).png)

Acceder al menú “Tools - “Board “Arduino Uno” - ESP32 Arduino”.

Seleccionar “AI Thinker ESP32-CAM”.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(2).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(2).png)

Acceder al menú “File - Examples - ESP32 - Camera”

Seleccionar “Camera Web Server”.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(3).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(3).png)

Camera Web Server - ESP32CAM.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(4).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(4).png)

Por defecto tiene seleccionado “CAMERA_MODEL_ESP_EYE”.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(5).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(5).png)

Seleccionar “CAMERA_MODEL_AI_THINKER”.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(6).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(6).png)

Modificar los datos de red del archivo.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(7).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(7).png)

SSID = Nombre de la Red.

Password = Contraseña.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(8).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(8).png)

Compilar el programa.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(9).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(9).png)

Se habrá completado el compilado.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(10).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(10).png)

Acceder al menú “Dispositivos - USB”.

Seleccionar FTDI.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(11).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(11).png)

Deberá aparecer un *check* en el FTDI.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(12).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(12).png)

Acceder al menú “Tools - Port”.

Seleccionar “/dev/ttyUSB0”.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(13).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(13).png)

Aparecerá una leyenda en el menú “Tools” que dirá Port:”/dev/ttyUSB0”

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(14).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(14).png)

Abrir el “Monitor Serie”.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(15).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(15).png)

Presionar el botón “Reset” en el ESP32CAM.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(17).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(17).png)

Cargar el programa.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(18).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(18).png)

Realizar el “Hard Resetting” con el botón “Reset” del ESP32CAM.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(19).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(19).png)

El microcontrolador se habrá conectado a la red.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(20).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(20).png)

Utilizar la dirección proporcionada por el monitor serial.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(21).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(21).png)

Podremos acceder desde cualquier dispositivo que se encuentre en nuestra red local.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(22).png](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Camera%20Web%20Server%20ESP32%20(22).png)

Clic en “Start Stream”.

# Evidencias

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Evidencia%20A.jpg](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Evidencia%20A.jpg)

Circuito para cargar el programa.

![https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Evidencia%20B.jpg](https://raw.githubusercontent.com/RaulToribio/24-Camera-Web-Server-ESP32/main/Im%C3%A1genes/Evidencia%20B.jpg)

Circuito para correr el programa.

# Créditos

> [José Raúl Toribio Gabriel](https://github.com/RaulToribio)
> 

> [Codigo IoT](https://github.com/codigo-iot)
>