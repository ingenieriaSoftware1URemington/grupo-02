# grupo-02
Angie Villada, Paula Henao, Laura Sepulveda

Nombre del proyecto

Zune Media Player (Microsoft Zune)
Lenguaje en que está hecho
Lenguaje C
(Usado porque era un sistema embebido con recursos limitados y necesidad de alto rendimiento)

Tipo de proyecto
Sistema embebido / Software de dispositivo electrónico
Un reproductor multimedia portátil (hardware + software).

Descripción del fallo
¿Qué fallaba?
El sistema tenía un error en el cálculo de fechas, específicamente al manejar años bisiestos.
El código entraba en un bucle infinito cuando el número de días era exactamente 366.

¿Cómo se manifestaba el error?
•	El 31 de diciembre de 2008
•	El dispositivo se congelaba completamente
•	No respondía a botones ni reinicios
•	La pantalla quedaba bloqueada
•	El usuario no podía usar el equipo

La única “solución” fue esperar a que cambiara el día.
Resumen corto (por si lo necesitas)

Un pequeño error lógico en código escrito en C provocó un bucle infinito en el software del Zune, causando que miles de dispositivos se congelaran durante un día completo.
