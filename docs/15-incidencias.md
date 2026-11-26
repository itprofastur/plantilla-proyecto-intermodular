# Fase 15 · Gestión de incidencias

> 🔤 **Códigos que verás:** **BUG-01** = error registrado 1 (y así sucesivamente)

**🎭 Hoy eres** **Desarrollador/a de mantenimiento**: decide qué se arregla, lo diagnostica con método y demuestra que está resuelto.  
**📦 Al terminar tendrás:** Los bugs importantes corregidos y comprobados, y el resto documentado · **⏱** 1-2 sesiones

`DESCUBRIR 01·02·03·04 │ DISEÑAR 05·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD 14·[15] │ ENTREGAR 16·17·18`

## El ciclo de una incidencia

```
Triaje → Reproducir → Diagnosticar → Corregir (rama fix/) → pull request → Re-test → Regresión → Cerrar (o reabrir)
```

## 1. Triaje: no todo se arregla ahora

> 💡 **Ejemplo ReservAula:** BUG-02 Cancelar reservas ajenas · Alta · Alta · Se corrige ya

| Bug | Severidad | Prioridad | Decisión |
|---|---|---|---|
| | | | ☐ Ahora ☐ Después del release ☐ No se arregla (motivo) |
| | | | ☐ Ahora ☐ Después del release ☐ No se arregla (motivo) |

## 2. Diagnosticar con método
🧭 No cambies cosas al azar hasta que «funcione». **Reproduce, plantea una hipótesis, compruébala** (logs, consola del navegador, consultas a la base de datos).

> 💡 **Ejemplo ReservAula:** BUG-01 · La fecha cambia de día · Miro la fecha guardada en la base de datos · Se guardaba con la hora y la zona horaria

| Bug | Hipótesis | Cómo la comprobé | Causa real |
|---|---|---|---|
| | | | |

## 3. Corregir con trazabilidad

> 💡 **Ejemplo ReservAula:** BUG-02 · Pull request #14 · Re-test correcto · Regresión correcta · Cerrado

- Rama `fix/BUG-03-...` · Commit `Corrige ... (fix #3)` · pull request enlazada al bug.
- **Corregido no es cerrado:** lo cierra quien lo comprueba (re-test). Si falla, se **reabre**.
- Pasa tu comprobación de regresión (fase 12): arreglar un bug no puede crear otro.

| Bug | Pull request | Re-test | Regresión | Estado |
|---|---|---|---|---|
| | | ☐ OK | ☐ OK | ☐ Cerrado ☐ Reabierto |

## 4. Problemas conocidos
🧭 Lo que no se corrige se documenta. Ocultarlo es peor que tenerlo. Esta lista irá al README.

> 💡 **Ejemplo ReservAula:** «En pantallas de menos de 320 px el calendario se corta. Solución temporal: girar el móvil.»

-

## ✅ Hecho cuando
- [ ] No queda ningún bug que bloquee el release.
- [ ] Cada corrección tiene pull request, re-test y comprobación de regresión.
- [ ] Los problemas que quedan están documentados.

## 🗣 Compruébalo
Cuenta **cómo encontraste la causa de un bug**: qué pensabas que era, cómo lo comprobaste y qué era en realidad.
