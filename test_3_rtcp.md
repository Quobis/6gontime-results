# Test #3 - RTCP monitoring

El objetivo de esta actividad es analizar la información disponible vía RTCP
para poder evaluar la relación de dichos datos con la experiencia de usuario y
la latencia de las comunicaciones.
 
## Lab definition

![test3-lab-diagram](<img/6GONTIME-test_3_rtcp.png>)

### Test 3: Gestión de calidad vía RTCP

- Análisis de estadísticas RTCP en tiempo real (RTP).
- Evaluación de variables como: número de tramas, búferes, y configuración de códecs.
- Objetivo: entender cómo RTCP puede garantizar la QoS y minimizar latencia, ajustando dinámicamente el flujo.
6G ON TIME

### RAW data

* Se adjunta los datos pruebas en la carpeta [results](results/)

## Main results

- RTCP sigue siendo el principal indicador de medición para latencia, jitter y packet-loss.
- RTCP ofrece un protocolo sólido y efectivo para actuar en proceso de reducción de latencia, su extensión para uso de ECN provee un proceso independiente de la capa de señalización.

Ver conclusiones generales en:
* [Conclusiones principales](tests-results.md)