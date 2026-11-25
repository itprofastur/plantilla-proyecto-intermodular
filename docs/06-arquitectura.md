# Fase 06 · Arquitectura y esqueleto online

> 🔤 **Códigos que verás:** **HU-01** = historia de usuario 1 (y así sucesivamente)

| 🎭 Hoy eres | ⏱ Tiempo | 📦 Al terminar tendrás |
|---|---|---|
| **Arquitecto/a de software + DevOps**: decide las piezas, las tecnologías y cómo llega la app a internet | 2 sesiones | Tu arquitectura **y un esqueleto de la app funcionando en una URL pública** |

`DESCUBRIR 01·02·03·04 │ DISEÑAR 05·[06] │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD 14·15 │ ENTREGAR 16·17·18`

**Partes de:** requisitos no funcionales (fase 02), pantallas (04) y modelo de datos (05).

## 1. Piezas y responsabilidades

| Componente | De qué se encarga | Tecnología |
|---|---|---|
| Cliente (navegador) | | |
| Servidor / API | | |
| Base de datos | | |
| Despliegue / hosting | | |

## 2. Decisiones técnicas (con motivo)
🧭 Una decisión sin motivo no se puede defender ante el tribunal. Usa tus requisitos no funcionales y lo que sabes hacer.

| Decisión | Por qué | Alternativa descartada y por qué |
|---|---|---|
| | | |
| | | |

## 3. Cómo se comunican: endpoints principales

| Método | Ruta | Para qué | Historia |
|---|---|---|---|
| GET | `/api/...` | | HU-__ |
| POST | `/api/...` | | HU-__ |

## 4. Diagrama
🧭 Cajas y flechas: navegador → API → base de datos, y dónde se despliega cada pieza. Guárdalo en `docs/img/06-arquitectura.png`.

![Arquitectura](img/06-arquitectura.png)

## 5. Esqueleto andante (walking skeleton) 🚀
🧭 Es lo más importante de la fase: **la versión más fina posible que atraviesa todas las piezas y está online**. Por ejemplo, una página que llama a `GET /api/...` y muestra datos reales de tu base de datos.

- [ ] Estructura de carpetas creada y subida a Git.
- [ ] El cliente llama a un endpoint y el endpoint lee de la base de datos.
- [ ] Publicado en internet. **URL:**
- [ ] `.env.example` con los nombres de las variables. **Ninguna contraseña real en el repositorio.**
- [ ] El README explica cómo arrancarlo en local (mínimo).

## ✅ Hecho cuando
- [ ] Cada componente tiene una responsabilidad clara.
- [ ] Cada tecnología elegida tiene un motivo.
- [ ] Hay una URL pública donde se ven datos de la base de datos.
- [ ] No he añadido piezas que el producto mínimo viable no necesita (microservicios, colas, etc.).

## 🗣 Compruébalo
Abre tu URL y explica **por dónde viaja la petición** desde que se carga la página hasta que aparecen los datos.

---
**Revisión del profesor:** ☐ Validada · ☐ Validada con cambios · ☐ Replantear
Cambios pedidos:
