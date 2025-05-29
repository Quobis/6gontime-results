# 6gontime-results

## Descripción

![6gontime-logo](img/6GONTIME-logo-proyecto.png)
![6gontime-patrocinios](img/6GONTIME-logos-patrocinio.png)

El presente repositorio recoge los resultados de las medidas, pruebas y datos
técnicos sobre el proyecto 6G ON TIME

### Título proyecto

6G ON TIME: Optimización de latencia en comunicaciones en tiempo real para 5G
avanzado

### Resumen ejecutivo

Los protocolos de comunicación en tiempo real SIP y WebRTC son la base de los
principales servicios de comunicaciones  over-the-top (OTT) y de las
herramientas de comunicaciones unificadas que ofrecen servicios multimedia en
tiempo real y colaborativos. Las redes 5G han generado nuevas oportunidades
gracias a sus capacidades de gran relevancia para el mundo de las comunicaciones
unificadas, ya que la transmisión de vídeo es bastante intensiva en el consumo
de recursos. Aún así, los mecanismos que implementan los sistemas de
comunicaciones unificadas actuales, no optimizan los recursos ofrecidos por las
redes 5G.

El objetivo de 6G ON TIME es explorar e identificar las mejores soluciones para
reducir la latencia en la transmisión de tráfico de comunicaciones en tiempo
real, basado en SIP y WebRTC, manteniendo la calidad de servicio y experiencia
del usuario. La reducción de latencias es importante en algunos servicios
críticos como es el caso de notificaciones automáticas de emergencias,
comunicaciones críticas, cirugías en remoto, control de drones, etc.

6G ON TIME propone trabajar en el ámbito de xURLLC (extreme ultra-reliable low
latency communications) de 6G, como extensión del URLLC de 5G. En particular se
evaluarán mecanismos como ECN (Explicit congestion communication), los
diferentes indicadores de calidad de servicios de RTCP (real-time control
protocol) y SRTCP (secured RTCP), los tiempos de paquetización ptime y los
codecs adaptativos (principalmente OPUS y/o SILK). El objetivo es aprovechar las
capacidades de adaptación de estos mecanismos para optimizar los tiempos de
transmisión y reducir la latencia de este tipo de comunicaciones, logrando un
mayor aprovechamiento de las capacidades de las redes de última generación.

## Navegación repositorio

* [Laboratoy description](lab_description.md)
* [Test #1 - ECN analysis](test_1_ecn.md)
* [Test #2 - ptime modelation](test_2_ptime.md)
* [Test #3 - RTCP monitoring](test_3_rtcp.md)

En cada documento se almacena una descripción del proceso de testeo y sus
conclusiones principales. En su carpeta correspondiente, se almacenan los datos
RAW.

# Copyright

@ Quobis Networks SLU. 2024. Todos los derechos reservados. La plataforma de
comunicaciones de Quobis y sus marcas relacionadas, son marcas comerciales de
Quobis. Todas las otras marcas registradas mencionadas son propiedad de sus
respectivos fabricantes. El contenido de este documento es confidencial.