# AranaBot
 Controlador Elcetronico de Velocidad para una arana robotica

-----------------------------------------------------------------------------------------
 Caracteristicas

 1| STM32F4 microcontrolador
 2| DRV8302 MOSFET driver 
 3| 5V 1A de salida para electronica externa
 4| Tension: 8V-60V (Seguro para baterias LiPo 3S a 12S)
 5| Corriente : 240A por unos segundos o 50A continuos
 6| FOC con y sin sensores, con autodeteccion de todos los parametros del motor desde FW 2.3
 7| Firmware basado en ChibiOS/RT 
 8| Corriente y tension medidas en todas las fases
 9| Braking regenerativo
 10| Soporte para motores DC
 11| Operacion con sensores o sin sensores
 12| Interfaces de control de los motores: Senal PPM (RC servo), analogo, UART, I2C, USB o bus CAN 
 13| Proteccion ajustable contra :

        -Tension de entrada baja
        -Tension de entrada alta
        -Corriente de motor alta
        -Corriente de entrada alta
        -Corriente de Braking alta
        -Cambios rapidos en los ciclos de trabajo (ramping)
        -RPM altos