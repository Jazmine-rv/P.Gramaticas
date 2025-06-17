# Lenguajes y Autómatas - Árboles de Derivación 

Este proyecto forma parte de la materia **Técnicas del Procesamiento del Habla**. Se implementa una gramática simple del español usando **Definite Clause Grammars (DCG)** en Prolog. Permite analizar oraciones compuestas por determinantes, sustantivos y verbos, teniendo en cuenta el **género** y **número** de las palabras.

---

##  Objetivo

Simular la estructura sintáctica de oraciones en español y generar árboles de análisis mediante reglas gramaticales en Prolog.

##  Palabras utilizadas

- **Sustantivos:** empleado, empleada, empleados, empleadas, sueldo, sueldos  
- **Determinantes:** el, la, los, las, un, una, unos, unas  
- **Verbos intransitivos:** trabaja, trabajan  
- **Verbos transitivos:** cobra, cobran  

##  Consultas realizadas

- phrase(o(_), [el, empleado, trabaja, un, sueldo]).
- phrase(o(_), [el, empleado, trabaja, una, empleada]).
- phrase(o(_), [el, empleada, trabaja]).
- phrase(o(_), [la, empleada, trabaja]).
- phrase(o(_), [los, empleada, sobran, sueldos]).
- phrase(o(_), [los, empleados, cobran, sueldos]).
- phrase(o(_), [los, empleados, cobran, los, sueldos]).
- phrase(o(a), [los, empleados, cobran, los, sueldos]).
- phrase(o(_), [los, empleados, trabajan, los, sueldos]).


---

## Archivos

- `README.md`: Este es un archivo descriptivo.
- `gramatica.pl`: Gramaticas programadas.

---

