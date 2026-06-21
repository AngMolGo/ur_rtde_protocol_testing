# ur_rtde_protocol_testing
Repositorio para aprender a utilizar el protocolo RTDE de Universal Robots.

El protocolo __Real-Time Data Exchange (RTDE)__ de Universal Robots es una interfaz de comunicación de alta velocidad (hasta 500 Hz) que permite el intercambio bidireccional de datos en tiempo real entre el controlador del robot y sistemas externos. Facilita el monitoreo preciso, la sincronización y el control de baja latencia en aplicaciones complejas.

Características y detalles principales:

- __Alta Velocidad y Baja Latencia__: Optimizado para un rendimiento rápido, alcanzando frecuencias de hasta 500 Hz en los cobots más modernos, ideal para sincronización precisa.
- __Comunicación Bidireccional__: Permite tanto recibir datos del estado del robot (posiciones, fuerzas, velocidades) como enviar comandos de control.
- __Compatibilidad__: Funciona en robots de la serie E y CB3 con software versión 3.4 o superior.
- Funcionalidades:
    - __Monitorización__: Captura de variables como posiciones articulares, corrientes, fuerzas, entradas/salidas y estados del robot.
    - __Control__: Envío de comandos para modificar la trayectoria o comportamiento del robot.

El protocolo se conecta al puerto 3004 del control box.