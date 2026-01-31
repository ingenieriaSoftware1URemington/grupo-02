

# Grupo 02
- Angie Villada  
- Paula Henao  
- Laura Sepúlveda  

---

## Nombre del proyecto
**Zune Media Player (Microsoft Zune)**

---

## Lenguaje en que está hecho
**Lenguaje C**

Se utilizó C porque era un sistema embebido con recursos limitados y requería alto rendimiento.

---

## Tipo de proyecto
Sistema embebido / Software para dispositivo electrónico.  
Reproductor multimedia portátil (hardware + software).

---

## Descripción del fallo
El sistema presentaba un error en el cálculo de fechas, específicamente al manejar años bisiestos.  
El código entraba en un **bucle infinito** cuando el número de días era exactamente **366**.

---

## ¿Cómo se manifestaba el error?
- El **31 de diciembre de 2008**
- El dispositivo se congelaba completamente
- No respondía a botones ni reinicios
- La pantalla quedaba bloqueada
- El usuario no podía usar el equipo

---

## Consecuencia
La única “solución” temporal fue esperar a que cambiara el día.

