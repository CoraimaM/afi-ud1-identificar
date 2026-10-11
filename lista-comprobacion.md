LISTA DE COMPROBACIÓN

## 1\. Al llegar a la escena

- Entender qué ha pasado. Preguntar qué incidente se ha producido, cuándo se detectó y qué se necesita averiguar. - Norma: NIST SP 800-86, ENFSI.
- Preguntar qué se ha hecho hasta ahora. Averiguar si alguien ha apagado equipos, borrado archivos, reiniciado sistemas o modificado configuraciones. - Norma: RFC 3227, ENFSI.
- Localizar todas las posibles fuentes de evidencia. Revisar ordenadores, servidores, móviles, dispositivos de red, USB, servicios en la nube, correo y registros externos. - Norma: NIST SP 800-86, RFC 3227.
- Anotar quién está presente y qué sabe cada persona. Registrar quién ha intervenido, qué ha observado y qué cambios ha realizado, sin confundir sus declaraciones con hechos ya comprobados. - Norma: RFC 3227,ENFSI.
- Comprobar los riesgos de la escena. Tener en cuenta la seguridad de las personas y el posible impacto sobre sistemas críticos. - Norma: ENFSI.

## 2\. Antes de tocar nada

- Documentar el estado inicial. Fotografiar los equipos, las pantallas, las conexiones y su ubicación. Anotar si están encendidos, apagados o bloqueados. - Norma: RFC 3227, ENFSI.
- Comprobar si hay registros fuera del equipo afectado. Preguntar si existen copias en servidores centrales, SIEM, proveedores de servicios o sistemas de monitorización. - _Norma:_ NIST SP 800-86.
- No apagar ni desconectar automáticamente los equipos. Podría perderse información de la memoria RAM, procesos o conexiones activas. Valorar antes las consecuencias. - Norma: RFC 3227, NIST SP 800-86.
- Comprobar si existen datos volátiles. Buscar posibles evidencias en memoria, procesos, conexiones de red, cachés y archivos temporales. - Norma: RFC 3227, NIST SP 800-86.
- Valorar el cifrado y las conexiones activas. Comprobar si hay volúmenes desbloqueados, sesiones abiertas o riesgo de bloqueo o borrado remoto. - Norma: NIST SP 800-86, ENFSI.
- Valorar si es necesario aislar el equipo de la red. Si existe riesgo de acceso remoto o borrado de datos, coordinar el aislamiento sin perder información volátil importante. - _Norma:_ RFC 3227, NIST SP 800-86.
- Preparar herramientas adecuadas y registrar las actuaciones. Anotar quién interviene, cuándo y qué herramientas utiliza, manteniendo la trazabilidad de las evidencias. - Norma: RFC 3227, ENFSI.

##

##

## 3\. Al decidir qué se adquiere

- Relacionar cada fuente con el incidente. Por ejemplo, consultar registros de autenticación si se investiga un acceso no autorizado, o registros de red si se busca conocer las comunicaciones realizadas. - Norma: NIST SP 800-86.
- Valorar tres aspectos: qué información puede desaparecer, qué utilidad tiene para la investigación y cuánto cuesta obtenerla. - Norma: NIST SP 800-86, ENFSI.
- Priorizar los datos más volátiles. Como regla general, recoger primero los datos más efímeros y después los más estables, adaptando el orden a las circunstancias. - Norma: RFC 3227.
- Decidir si hace falta una adquisición en vivo. Si procede, capturar memoria RAM, procesos y conexiones antes de que desaparezcan, teniendo en cuenta los cambios que puede provocar la intervención. - Norma: NIST SP 800-86, ENFSI.
- Comprobar la integridad de las copias. Calcular hashes de las imágenes forenses y verificar que se mantienen iguales durante el proceso de adquisición y análisis. _Norma:_ NIST SP 800-86, ENFSI.
- Adquirir los datos estables relevantes. Crear imágenes forenses de los discos y recoger registros, copias de seguridad y otras fuentes necesarias. - Norma: RFC 3227, NIST SP 800-86.
- Verificar y proteger las evidencias. Utilizar hashes cuando corresponda, conservar los originales, documentar la cadena de custodia y justificar cualquier fuente que no se haya podido recoger. - Norma: RFC 3227, ENFSI.