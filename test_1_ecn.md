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

### Test 1: Uso de ECN para control de congestión

- Pruebas sobre tráfico multimedia en tiempo real bajo condiciones de congestión.
- Evaluación del impacto en latencia, pérdida de paquetes, jitter y retransmisiones.
- Objetivo: comprobar la validez de ECN en entornos xURLLC (ultra baja latencia y alta fiabilidad).

### RAW data

* Se adjunta los datos pruebas en la carpeta [results](results/)
  
## Main results

- ECN es la mejor opción para detección temprana, reducción de saturación y reducción de la latencia percibida total.
- ECN ofrece feedback explícito, frente a las técnicas actuales de codecs adaptativos y cálculos generados por análisis o estudio experimental del entorno (STUN, learning loop)
- ECN tiene muy poco despliegue en red, lo cual es un problema.

Ver conclusiones generales en:
* [Conclusiones principales](tests-results.md)