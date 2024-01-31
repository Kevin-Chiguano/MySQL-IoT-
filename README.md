<a name="readme-top"></a>
# MySQL-IoT-
base de datos de un proyecto IoT para invernaderos
<br>
<div align="center" >
 <img src="https://qiu.itq.edu.ec/Principal/imgLogin/ITQ.png" alt="Logo" width="612" height="200">
</div>
 <h3 align="center">Proyecto IoT</h3>
 <h2>Integrantes
 </h2>
 <li>Joel Caza</li>
  <li>Mathias Cruz</li>
   <li>Kevin Chiguano</li>
<!-- PROJECT LOGO -->
<div align="center" >
   <img src="https://cdn-icons-png.flaticon.com/512/6228/6228463.png" alt="Logo" width="280" height="280">
</div>
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla De Contenidos</summary>
  <ol>
    <li>
      <a href="#introdducion">Introduccion</a>
    </li>
    <li>
      <a href="#escenario">Escenario</a>
    </li>
    <li><a href="#herramientas">Herramientas</a></li>
    <li><a href="#consultas">Consultas</a></li>
  </ol>
</details>
</div>


<!-- ABOUT THE PROJECT -->
## Introduccion <a name="introdducion"></a>

En un mundo donde la seguridad alimentaria y la eficiencia agrícola son prioridades globales, la tecnología de Internet de las Cosas (IoT) ha emergido como un catalizador fundamental para la transformación del sector agrícola. Los invernaderos, en particular, representan un espacio crucial donde la integración de dispositivos IoT puede revolucionar la forma en que se cultiva y se gestiona la producción de alimentos.

Este proyecto tiene como objetivo explorar y desarrollar un sistema de IoT para invernaderos, diseñado para optimizar el control ambiental, monitorear el crecimiento de las plantas y mejorar la eficiencia en el uso de recursos como agua y energía. Al emplear sensores inteligentes, actuadores y una plataforma de gestión de datos en la nube, se busca crear un entorno de cultivo inteligente y autónomo que permita a los agricultores supervisar y gestionar sus cultivos de manera remota y en tiempo real.


<p align="right">(<a href="#readme-top">Regresar al Inicio</a>)</p>

<!-- GETTING STARTED -->
## Escenario <a name="escenario"></a>
Somos una empresa de sensores para invernaderos, los sensores se 
encargarán de recoger la información relacionada con: temperatura, humedad, 
presión atmosférica, luminosidad.
<p align="right">(<a href="#readme-top">Regresar al Inicio</a>)</p>

## Herramientas <a name="herramientas"></a>
Para la realización de un proyecto IoT para un invernadero, es necesario contar con una variedad de herramientas y tecnologías que permitan la adquisición, procesamiento y gestión de datos, así como el control de dispositivos. A continuación, se detallan algunas de las herramientas esenciales:


  
  <li>Sensores y Actuadores:
            <ul>
                <li>Sensores de temperatura y humedad</li>
                <li>Sensores de luz</li>
                <li>Sensores de humedad del suelo</li>
                <li>Actuadores de riego</li>
                <li>Actuadores de ventilación</li>
            </ul>
        </li>
        <li>Plataforma de Gestión de Datos:
            <ul>
                <li>Base de Datos (MySQL, PostgreSQL, MongoDB)</li>
                <li>Servicios en la Nube (AWS IoT Core, Google Cloud IoT Core, Azure IoT Hub)</li>
            </ul>
        </li>
        <li>Software de Desarrollo:
            <ul>
                <li>Lenguajes de Programación (Python, JavaScript, C++)</li>
                <li>Frameworks de Desarrollo IoT (MQTT, CoAP, HTTP)</li>
            </ul>
        </li>
        <li>Interfaz de Usuario:
            <ul>
                <li>Aplicación Web o Móvil</li>
                <li>Frameworks de Desarrollo Web o Móvil (Flask, Django, React, Angular, Flutter)</li>
            </ul>
        </li>
        <li>Seguridad:
            <ul>
                <li>Protocolos de Seguridad IoT (TLS/SSL)</li>
                <li>Autenticación y Autorización</li>
            </ul>
        </li>
<p align="right">(<a href="#readme-top">Regresar al Inicio</a>)</p>

 <div align="center" >
 <img src="BD tablas/images.jpg">
 </div>

<!-- USAGE EXAMPLES -->
## Consultas <a name="consultas"></a>
 1. Obtener todos los dispositivos junto con la cantidad de datos de sensores registrados
para cada uno.
 ```sh
   git clone 1
   ```
<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>

2. Encontrar la temperatura máxima registrada por cada dispositivo.
```sh
   git clone 2
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
3. Mostrar la cantidad total de datos de sensores registrados para cada tipo de sensor.
```sh
   git clone 3
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
4. Obtener la lista de dispositivos que no han enviado datos en las últimas 24 horas.
```sh
   git clone 4
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
5. Calcular el promedio de temperatura por hora para todos los dispositivos.
```sh
   git clone 5
   ```
<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>

6. Encontrar el dispositivo con la mayor cantidad de datos de sensores registrados.
```sh
   git clone 6
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
7. Mostrar los dispositivos cuya temperatura promedio sea superior a cierto umbral.
```sh
   git clone 7
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
8. Obtener la cantidad total de datos de sensores registrados para cada dispositivo en el
último mes.
```sh
   git clone 8
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>

9. Encontrar los dispositivos que tengan al menos dos tipos diferentes de sensores.
```sh
   git clone 9
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
10. Mostrar los dispositivos cuyo estado actual sea "activo" y que hayan enviado datos en
las últimas 12 horas.
```sh
   git clone 10
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
11. Calcular la suma total de datos de sensores para cada tipo de sensor en los últimos siete
días.
```sh
   git clone 11
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
12. Encontrar los dispositivos que han experimentado un aumento del 20% en la
temperatura en la última hora.
```sh
   git clone 12
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
13. Mostrar los dispositivos cuya humedad promedio sea inferior al 30% y que estén
actualmente inactivos.
```sh
   git clone 13
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
14. Obtener la cantidad de datos de sensores registrados para cada dispositivo, agrupados
por día.
```sh
   git clone 14
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
15. Calcular la temperatura promedio por cada hora del día para todos los dispositivos.
```sh
   git clone 15
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
16. Encontrar los dispositivos que tengan tanto sensores de temperatura como sensores de
humedad.
```sh
   git clone 16
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
17. Mostrar los dispositivos cuya temperatura máxima haya superado un cierto umbral en
los últimos siete días.
```sh
   git clone 17
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
18. Obtener la lista de dispositivos junto con la cantidad de datos de sensores registrados,
ordenados por fecha de registro.
```sh
   git clone 18
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
19. Calcular la diferencia de temperatura máxima y mínima registrada para cada dispositivo.
```sh
   git clone 19
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
20. Encontrar los dispositivos que han enviado datos constantemente durante las últimas 48
horas.
```sh
   git clone 20
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
21. Mostrar los dispositivos cuya humedad promedio sea superior al 60% y que estén
actualmente activos.
```sh
   git clone 21
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
22. Obtener la suma total de datos de sensores para cada dispositivo, excluyendo aquellos
cuyo estado sea "inactivo".
```sh
   git clone 22
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
23. Calcular la temperatura promedio por cada día de la semana para todos los dispositivos.
```sh
   git clone 23
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
24. Encontrar los dispositivos cuyo consumo total de energía supere cierto umbral.
```sh
   git clone 24
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 
25. Mostrar los dispositivos que hayan experimentado una variación de temperatura superior al 15% en la última hora.
```sh
   git clone 25
   ```

<div align="center" >
 <img src="BD tablas/images.jpg">
 </div>
 

<p align="right">(<a href="#readme-top">Regresar al Inicio</a>)</p>

