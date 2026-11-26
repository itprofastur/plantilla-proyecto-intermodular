# Fase 14 · Plan de pruebas

> 🔤 **Códigos que verás:** **CP-01** = caso de prueba 1 (y así sucesivamente)

**🎭 Hoy eres** **Tester**: no busca fallos al azar; diseña comprobaciones repetibles para saber la calidad real del producto.  
**📦 Al terminar tendrás:** Casos de prueba ejecutados en la URL, bugs registrados y un veredicto: ¿está listo? · **⏱** 1-2 sesiones

`DESCUBRIR 01·02·03·04 │ DISEÑAR 05·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD [14]·15 │ ENTREGAR 16·17·18`

> 🧭 Hoy cambias de chaqueta: **tu objetivo es encontrar lo que falla**, aunque lo hayas programado tú. Si es posible, prueba el proyecto de un compañero y que él pruebe el tuyo.

## 1. ¿Qué puede salir mal?

> 💡 **Ejemplo ReservAula:** Dos personas reservan la misma franja a la vez · Doble reserva · ☑ Lo pruebo

| Riesgo | Impacto si ocurre | ☐ Lo pruebo |
|---|---|---|
| *Dos personas reservan la misma franja* | *Alto: el problema que queríamos resolver* | ☐ |
| | | ☐ |
| | | ☐ |

## 2. Casos de prueba
🧭 Salen de los **criterios de aceptación**. Por cada historia: al menos un caso **positivo** (lo que debe funcionar) y uno **negativo** (lo que debe impedirse). No olvides los permisos (¿puedo hacer algo que no debería?) y el móvil.

> 💡 **Ejemplo ReservAula:** CP-02 · HU-02 · Reservar una franja ya ocupada · Aula 204, jueves, 3.ª hora · Mensaje «Esa franja ya está reservada»

| ID | Historia | Pasos | Datos | Resultado esperado | Obtenido | ✔/✘ |
|---|---|---|---|---|---|---|
| CP-01 | | | | | | |
| CP-02 | | | | | | |
| CP-03 | | | | | | |
| CP-04 | | | | | | |
| CP-05 | | | | | | |

## 3. Prueba exploratoria (20 min)
🧭 Con una misión concreta: «intenta romper la reserva usando fechas raras, dobles clics y el botón Atrás». Anota lo que encuentres.

## 4. Cada fallo, un bug reproducible
🧭 Usa la plantilla de bug del repositorio. Un bug es útil si **otra persona lo puede reproducir**.

> 💡 **Ejemplo ReservAula:** BUG-02 · CP-04 · Alta · Alta · Enlace a la incidencia en GitHub

**Severidad** = cuánto daño hace · **Prioridad** = cuándo hay que arreglarlo. No son lo mismo.

| Bug | Caso | Severidad | Prioridad | Enlace |
|---|---|---|---|---|
| | | | | |

## 5. Extra (opcional, suma nivel)

> 💡 **Ejemplo ReservAula:** Una prueba automática de la API con Postman, o revisar la accesibilidad con Lighthouse.

☐ He automatizado al menos un test (unitario o de API) y se ejecuta con un comando.

## 6. Veredicto

> 💡 **Ejemplo ReservAula:** «Apto para publicar: 18 de 20 casos correctos. Los 2 fallos son leves y están documentados.»

**¿Listo para el release?** ☐ Sí ☐ Sí, con problemas conocidos ☐ No: bloquean →

## ✅ Hecho cuando
- [ ] Cada historia del producto mínimo viable tiene casos positivos y negativos ejecutados en la URL.
- [ ] Cada fallo está registrado con pasos para reproducirlo.
- [ ] Hay un veredicto justificado.

## 🗣 Compruébalo
Explica **la diferencia entre severidad y prioridad** con un bug de tu proyecto.
