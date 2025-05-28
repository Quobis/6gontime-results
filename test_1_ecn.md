# Test #1 - RTCP monitoring

El objetivo de esta actividad es estudiar los mecanismos basados en ECN
(Explicit Congestion Notification) para entornos xURLLC de baja latencia y alta
fiabilidad. Típicamente, las redes TCP/IP señalan la congestión descartando
paquetes. Cuando ECN se negocia con éxito, un router compatible con ECN puede
establecer una marca en el encabezado IP en lugar de descartar un paquete para
indicar una congestión inminente. El receptor del paquete hace eco de la
indicación de congestión al remitente, que reduce su tasa de transmisión como si
detectara un paquete descartado.

Esta actividad analizará estas técnicas para valorar cómo optimizar el control
de tráfico en el establecimiento y curso de comunicaciones multimedia en tiempo
real en entornos 5G avanzado.
 
## Lab definition

![test1-lab-diagram](<img/6GONTIME-test_1_ecn.png>)

## Main results

TBC