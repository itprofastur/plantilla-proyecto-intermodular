# Fase 16 · Release a producción

| 🎭 Hoy eres | ⏱ Tiempo | 📦 Al terminar tendrás |
|---|---|---|
| **DevOps / Release manager**: publica una versión estable, comprueba que funciona y sabe volver atrás si falla | 1 sesión | La versión **v1.0.0** en producción, comprobada, y un plan para deshacerla si falla |

`DESCUBRIR 01·02·03·04 │ DISEÑAR 05·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD 14·15 │ ENTREGAR [16]·17·18`

> 🧭 Tu app está online desde la fase 06. Hoy no «subes» la app: **conviertes lo que tienes en una versión de producción**, identificada y fiable.

## 1. Configuración de producción
- [ ] Variables de entorno configuradas en la plataforma (no en el código). `.env.example` actualizado.
- [ ] Modo debug o desarrollo **desactivado**. Los errores no muestran detalles internos al usuario.
- [ ] Contraseñas por defecto cambiadas. Usuarios de demo creados (para el tribunal).
- [ ] Datos de demo realistas cargados.
- [ ] Copia de seguridad de la base de datos exportada antes de publicar.

## 2. Versión identificable
- [ ] `CHANGELOG.md` con lo que incluye esta versión.
- [ ] Etiqueta en Git: `git tag v1.0.0` y `git push --tags` (o una Release en GitHub).

| Versión | Commit | Fecha | URL |
|---|---|---|---|
| v1.0.0 | | | |

## 3. Smoke test en producción (después de publicar)
🧭 5-8 comprobaciones rápidas **en la URL real** de que lo esencial funciona.

| # | Comprobación | ✔/✘ |
|---|---|---|
| S1 | La URL abre con HTTPS y sin errores en la consola | |
| S2 | | |
| S3 | | |
| S4 | | |
| S5 | | |

## 4. Plan de vuelta atrás (rollback)
🧭 Si la nueva versión rompe algo, ¿cómo vuelves a la anterior **en minutos**?
**Mi plan:**
☐ Lo he probado al menos una vez.

## 5. Incidencias del despliegue y cómo se resolvieron
-

## ✅ Hecho cuando
- [ ] v1.0.0 etiquetada y desplegada; la URL abre por HTTPS.
- [ ] El smoke test pasa en producción.
- [ ] No hay secretos en el repositorio y el modo debug está desactivado.
- [ ] Sé volver a la versión anterior.

## 🗣 Compruébalo
Explica **la diferencia entre «funciona en mi ordenador» y «está listo para producción»**, con dos ejemplos de tu proyecto.
