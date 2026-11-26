# Fase 12 · Sprint 2 · Desarrollo

**🎭 Hoy eres** **Desarrollador/a con un producto en marcha**: construyes lo nuevo sin romper lo que ya funciona.  
**📦 Al terminar tendrás:** Las historias del Sprint 2 online y todo lo anterior funcionando · **⏱** Todas las sesiones del sprint

`DESCUBRIR 01·02·03·04 │ DISEÑAR 05·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·[12]·13 │ CALIDAD 14·15 │ ENTREGAR 16·17·18`

> 🧭 Mismo ciclo que en la [fase 09](09-sprint1-desarrollo.md). Hay dos novedades: **proteger lo que ya funciona** y **revisar el código de verdad**.

## 1. Tu comprobación de regresión (créala el primer día)
🧭 Una regresión es algo que funcionaba y deja de funcionar por un cambio nuevo. Escribe 5-6 comprobaciones rápidas de lo más importante y **pásalas después de cada merge**.

| # | Comprobación | Resultado esperado |
|---|---|---|
| R1 | *Entrar con el usuario demo* | *Veo el panel principal* |
| R2 | | |
| R3 | | |
| R4 | | |
| R5 | | |

## 2. Revisión de código (en cada pull request)
🧭 Si trabajas en equipo, revisa la pull request de un compañero. Si trabajas solo, revisa tu propia pull request al día siguiente.

> 💡 **Ejemplo ReservAula:** «En la línea 40 la fecha se compara como texto; mejor como fecha.» Se corrige antes del merge.

- ¿Se entiende sin que el autor lo explique? ¿Los nombres dicen lo que hacen?
- ¿Hay código duplicado o comentado sin usar?
- ¿Los datos se validan **también en el servidor**?
- ¿Hay contraseñas o datos sensibles en el código?

## 3. Aplica la mejora de la retrospectiva

> 💡 **Ejemplo ReservAula:** Mejora: pull requests pequeñas. Este sprint: 9 pull requests, todas integradas el mismo día.

**Mejora:** · **¿Se está cumpliendo?** ☐ Sí ☐ A medias ☐ No

## Diario breve

> 💡 **Ejemplo ReservAula:** Sesión 2 · Pantalla de gestión de aulas · El login dejó de funcionar · Se revierte el cambio y se corrige.

| Sesión | Avance | Bloqueo / bug / regresión | Decisión |
|---|---|---|---|
| | | | |
| | | | |

## Cierre del sprint

> 💡 **Ejemplo ReservAula:** HU-07 Avisos por correo · Sin terminar · Pasa a «versión futura».

| Historia | Estado | Si no está en Done, ¿qué falta? |
|---|---|---|
| | ☐ Done ☐ No terminada | |

**¿Sprint Goal cumplido?** ☐ Sí ☐ En parte ☐ No · **¿Pasan las comprobaciones de regresión en la URL?** ☐ Sí ☐ No

## ✅ Hecho cuando
- [ ] Lo nuevo cumple la Definition of Done y funciona en la URL.
- [ ] Las comprobaciones de regresión pasan en la URL.
- [ ] Cada pull request ha tenido revisión.

## 🗣 Compruébalo
Explica **qué es una regresión** y enseña una pull request donde la revisión haya mejorado algo.
