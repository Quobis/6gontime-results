# Test #2 - ptime study

El objetivo de esta actividad es estudiar los mecanismos de modelado del ptime.
ptime es el periodo de paquetización en comunicaciones en tiempo real como VoIP,
que se utiliza tanto en comunicaciones SIP como WebRTC. Se establece en el
mensaje SDP (el mecanismo que usa SIP para negociar la configuración de los
medios) y define la longitud de cada paquete de media RTP  que se envía.

Esta actividad estudiará las técnicas de medida de ptime y cómo configurarlo
para poder analizar su influencia en la latencia de la transmisión de
comunicaciones multimedia.

## Lab definition

![test2-lab-diagram](<img/6GONTIME-test_2_ptime.png>)

### Test 2: Ajuste dinámico del ptime

- Estudio del impacto de la variabilidad de ptime en latencia y fiabilidad.
- Configuración mediante negociación SDP (SIP/WebRTC) usando Quobis Communication Platform.
- Objetivo: optimizar el ptime en función del contexto de red y el caso de uso xURLLC.

### RAW data

* Se adjunta los datos pruebas en la carpeta [results](results/)

## Main results

- ptime ofrece un trade-off entre latencia y calidad, pero su recorrido está limitado a lo que ya usa la comunidad a día de hoy.
- El recorrido efectivo de ptime es de 10-20ms ofreciendo el resto de valores resultados poco prácticos.

Ver conclusiones generales en:
* [Conclusiones principales](tests-results.md)