# Conclusiones principales

Se incluyen a continuación los resultados y conclusiones principales del proyecto.

## Arquitectura

Los tests se realizaron en un laboratorio conjunto entre Gradiant y Quobis.

Para más información:

* [Laboratoy description](lab_description.md)

## Tests

Los test y sus resultados correspondientes son detallados en sus propias paǵinas

* [Test #1 - ECN analysis](test_1_ecn.md)
* [Test #2 - ptime modelation](test_2_ptime.md)
* [Test #3 - RTCP monitoring](test_3_rtcp.md)

## Principales resultados del proyecto

- Frente a la limitación física de latencia, la exclusividad de uso de canales, y la eficiencia en el control de cogestión son las claves para obtener comunicaciones de baja latencia fiables.
- La saturación es la principal cuasa de variabilidad en la latencia, generando un perjuicio explícito para comunicaciones críticas.
- ECN y el RFC8888 (extensión del RTCP) se muestran como las principales herramientas para garantizar dicha latencia garantizada estable.

**Más conclusiones de los tests**

- ECN es la mejor opción para detección temprana, reducción de saturación y reducción de la latencia percibida total.
- ECN ofrece feedback explícito, frente a las técnicas actuales de codecs adaptativos y cálculos generados por análisis o estudio experimental del entorno (STUN, learning loop)
- ECN tiene muy poco despliegue en red, lo cual es un problema.
- RTCP sigue siendo el principal indicador de medición para latencia, jitter y packet-loss.
- RTCP ofrece un protocolo sólido y efectivo para actuar en proceso de reducción de latencia, su extensión para uso de ECN provee un proceso independiente de la capa de señalización.
- ptime ofrece un trade-off entre latencia y calidad, pero su recorrido está limitado a lo que ya usa la comunidad a día de hoy.
- El recorrido efectivo de ptime es de 10-20ms ofreciendo el resto de valores resultados poco prácticos.

**Observaciones generales**

- Los códecs adaptativos "reducen" la latencia efectiva percibida. Su uso en conjunto con las técnicas previamente comentadas hace que las comunicaciones huma-to-human y human-to-machine tengan percepción satisfactoria de baja o nula latencia.
- Como líneas futuras, la aplicación de ML / IA con modelos dedicados sobre estos datos ofrecerá las mejores combinaciones de parametrización de todos los datos monitorizados.

# Información de contacto

https://quobis.com/es/proyectos-de-innovacion/6g-on-time/

- yudani.riobo@quobis.com
- santiago.troncoso@quobis.com