# ProyectoIoT2023
GDS0453 - Documentación proyecto IoT 

## Integrantes
- Brandon Jesús Soto Rangel
- Miguel Ángel Anastasio Nava
- José Manuel Sánchez Arredondo
- Victor Javier Otero

## Objetivo general
El objetivo general de este proyecto es poder implementar un sistema de riego de cannabis, por lo que se propondra es mantener estas
plantas regadas adecuadamente cada que necesiten agua.
### Objetivos específicos
- 1.- Planeación de prototipo.
- 2.- Diseñado del prototipo.
- 3.- Validación de prototipo.
- 4.- Test de prototipo.
- 5.- Realización de proyecto final.
- 6.- Test de proyecto.
- 7.- Liberación de proyecto.

## Tabla de Software utilizado
| Id | Software | Version | Tipo |
|----|----------|---------|------|
|1.1|Arduino IDE | 2-0.4 |Freeware|
|1.2|Visual Studio Code | 1.74.3 |Freeware|
|1.3|Mosquitto   | 5.0.3.1.1|Freeware|
|1.4|Node-Red   | 3.0.2 |Freeware|
|1.5|Node.js  | 18.13.0 |Freeware|


## Tabla con el hardware utilizado
| Id | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|-------------|--------|----------|-------------|
|2.1|  Esp32  | Es la denominación de una familia de chips SoC de bajo coste y consumo de energía, con tecnología Wi-Fi y Bluetooth de modo dual integrada.            |![image](https://user-images.githubusercontent.com/106613839/217649811-9335a9c7-5a4c-4813-8f17-e03488f52967.png)| 1         | $150            |
|2.2|  Cables          | Clabes por los cuales se harán conecciones entre sensores, actuadores y la esp32|![image](https://user-images.githubusercontent.com/106613839/217650692-88574d94-022c-44fe-a183-58dd5121c26a.png)| 30         |  $30           |
|2.3| Foco con socket  | Foco el cual será controlado para iluminar una zona.   |![image](https://user-images.githubusercontent.com/106613839/217650095-d221a148-1c63-45fc-8211-0f1e97fa8816.png)| 1    | $80            |
|2.4| Sensor de humedad  | Cuenta con dos microsensores calibrados en función de la humedad relativa del área o la zona. |![image](https://user-images.githubusercontent.com/107832766/219272302-4151c8bc-315a-4dc3-9610-5f902f33414e.png)| 2   |  $57           |
|2.5| Modulo Relay  | Es un dispositivo que funciona como un interruptor controlado por un circuito eléctrico. |![image](https://user-images.githubusercontent.com/106613839/217650285-e2eb47d3-dd0d-417d-8b56-bc9ed793780a.png)| 1 | $100  |
|2.6| Raspberry Pi  | Consiste en una placa base que soporta distintos componentes de un ordenador como un procesador ARM de hasta 1500 MHz, un chip gráfico y una memoria RAM de hasta 8 GB. Además, tiene otras muchas otras posibilidades. Gracias a sus puertos y entradas, permite conectar dispositivos periféricos. |![image](https://user-images.githubusercontent.com/106613839/217650399-cdfdb686-4b04-4740-9ed4-f50115d25a98.png)|  1        | $2750            |
|2.7| Buzzer  | Es un pequeño duspositivo capaz de convertir energía eléctrica en sonido. |![image](https://user-images.githubusercontent.com/106613839/217650467-74e67b77-a1b1-4a00-9268-57ff7921a149.png)|  1       | $20             |

## Epicas del proyecto (Minimo debe de haber una épica por integrante de equipo)
- Yo como usuario quiero detectar si mi planta de cannabis necesita ser regada.
- Yo como usuario quiero que mi dispositivo riegue la planta cada que lo necesite.
- Yo como usuario quiero que el dispositivo active un sonido de alarma para saber cuando regar la planta.
- Yo como usuario quiero que almacenar la información cada vez que se riega la planta.
- Yo como usuario quiero que el dispositivo sepa cuanta agua necesita la planta.

## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
|3.1 | Yo como usuario quiero detectar si mi planta de cannabis necesita ser regada. | Alta | 1 Mes  | Que el dispositivo se de cuenta cuando la tierra de la planta este seca. | Brandon y José Manuel |
| 3.2 | Yo como usuario quiero que mi dispositivo riegue la planta cada que lo necesite | Alta | 1 Mes | El dispositivo permitira el paso del agua hacía la planta. | Miguel Ángel |
| 3.3 | Yo como usuario quiero que el dispositivo active un sonido de alarma para saber cuando regar la planta. | Semi-Alta | 1 Mes | Cuando la tierra de la planta este seca ver si hace el sonido. | Victor |
| 3.4 | Yo como usuario quiero que almacenar la información cada vez que se riega la planta. | Semi-Alta | 2 Meses | Checar en el dispositivo el registro de las detecciones.  | José Manuel y Miguel Ángel|
| 3.5 | Yo como usuario quiero que el dispositivo sepa cuanta agua necesita la planta. | Semi-Alta | 2 Meses | A través de un dispositivo móvil | Brandon y Victor|

## Prototipo en dibujo
- Coloca la fotografia de tu prototipo dibujado a lapiz

![WhatsApp Image 2023-02-16 at 00 53 29](https://user-images.githubusercontent.com/107832766/219290535-70bf23d2-de48-4e55-9166-8594278d453b.jpeg)

