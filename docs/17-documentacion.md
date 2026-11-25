# Fase 17 · Documentación

| 🎭 Hoy eres | ⏱ Tiempo | 📦 Al terminar tendrás |
|---|---|---|
| **Technical writer / desarrollador/a**: deja el producto listo para que otra persona lo use, lo instale y lo mantenga sin ti | 1-2 sesiones | Un README que funciona, la documentación técnica actualizada y una guía de usuario |

`DESCUBRIR 01·02·03·04 │ DISEÑAR 05·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD 14·15 │ ENTREGAR 16·[17]·18`

> 🧭 Buena noticia: llevas toda la vida del proyecto documentando en `docs/`. Hoy toca **actualizar, ordenar y comprobar** que la documentación funciona.

## 1. Dos públicos

| Público | Qué necesita | Dónde |
|---|---|---|
| Desarrollador/a que llega nuevo | Entender, instalar y arrancar el proyecto | `README.md` + `docs/` |
| Usuario final | Hacer sus tareas sin ayuda | `docs/guia-usuario.md` |

## 2. README
🧭 Usa la plantilla `README.md` del repositorio. Debe tener: qué es, URL y usuarios demo, capturas, tecnologías, **instalación paso a paso**, variables de entorno, estructura, estado y problemas conocidos.
- [ ] README completo.

## 3. Prueba de transferencia ⭐
🧭 Un compañero clona tu repositorio y lo arranca **solo con tu README**. Tú miras y no ayudas.

| Dónde se atascó | Qué he corregido en el README |
|---|---|
| | |

☐ Ha conseguido arrancarlo en ___ minutos.

## 4. Documentación técnica: lo que EXISTE, no lo que planeaste
- [ ] Diagrama de arquitectura actualizado (fase 06).
- [ ] Modelo de datos y `schema.sql` actualizados (fase 05).
- [ ] Endpoints de la API: tabla con método, ruta, para qué sirve y si pide login.

## 5. Guía de usuario
🧭 Explica **tareas, no botones**: «Cómo reservar un aula», no «el botón azul sirve para…». Pasos numerados y una captura por tarea.
- [ ] `docs/guia-usuario.md` con las 3-5 tareas principales, probada por alguien que no conoce la app.

## 6. Limpieza del repositorio
- [ ] Sin archivos basura, código comentado ni ramas muertas.
- [ ] `.gitignore` correcto. Sin `node_modules`, `vendor` ni `.env` subidos.

## ✅ Hecho cuando
- [ ] Otra persona ha arrancado el proyecto solo con el README.
- [ ] La documentación técnica coincide con el código actual.
- [ ] Un usuario puede hacer las tareas principales con la guía.

## 🗣 Compruébalo
Explica **qué falló en tu prueba de transferencia y qué cambiaste.** Si no falló nada, explica por qué crees que no.
