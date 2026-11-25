# Fase 05 · Modelo de datos

> 🔤 **Códigos que verás:** **RN-01** = regla de negocio 1 (y así sucesivamente)

| 🎭 Hoy eres | ⏱ Tiempo | 📦 Al terminar tendrás |
|---|---|---|
| **Diseñador/a de datos**: decide qué información guarda el sistema y cómo se relaciona | 1-2 sesiones | El modelo de datos **y tu base de datos creada y con datos de ejemplo** |

`DESCUBRIR 01·02·03·04 │ DISEÑAR [05]·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD 14·15 │ ENTREGAR 16·17·18`

**Partes de:** pantallas (04), historias (03) y reglas de negocio (02).

## 1. ¿Qué información aparece?
🧭 Recorre tus pantallas y anota cada dato que se ve, se escribe o se consulta.

| Pantalla / historia | Datos que aparecen |
|---|---|
| | |

## 2. Entidades, atributos y clave

| Entidad | Atributos principales | Clave primaria |
|---|---|---|
| | | |
| | | |

## 3. Relaciones

| Relación | Cardinalidad | Se lee así… |
|---|---|---|
| USUARIO – RESERVA | 1 : N | Un usuario hace muchas reservas; una reserva es de un usuario |
| | | |

## 4. Restricciones: las reglas de negocio dentro de la base de datos
🧭 Revisa tus reglas de negocio de la fase 02. Algunas se pueden proteger en la base de datos (`NOT NULL`, `UNIQUE`, `FOREIGN KEY`, `CHECK`) y otras se validan en el servidor.

| Regla | Dónde la protejo | Cómo |
|---|---|---|
| RN-__ | ☐ Base de datos ☐ Servidor | |

## 5. Diagrama
🧭 Con dbdiagram.io, draw.io o MySQL Workbench. Guárdalo en `docs/img/05-modelo.png`.

![Modelo de datos](img/05-modelo.png)

## 6. Hazlo real
1. Escribe `database/schema.sql` (crea las tablas) y `database/seed.sql` (datos de ejemplo realistas).
2. Ejecútalos en tu MySQL/MariaDB desde cero.
3. Comprueba que tu modelo responde a tus pantallas con 3 consultas:

| Pregunta de una pantalla | Consulta SQL | ¿Funciona? |
|---|---|---|
| *¿Qué franjas del aula 204 están ocupadas esta semana?* | | ☐ |
| | | ☐ |
| | | ☐ |

## ✅ Hecho cuando
- [ ] Todo dato que aparece en las pantallas tiene sitio en el modelo.
- [ ] Las reglas de negocio importantes están protegidas (base de datos o servidor).
- [ ] `schema.sql` y `seed.sql` se ejecutan sin errores en una base vacía.
- [ ] Las 3 consultas devuelven lo esperado.

## 🗣 Compruébalo
Señala una restricción de tu `schema.sql` y explica **qué regla de negocio protege y qué pasaría sin ella.**

---
**Revisión del profesor:** ☐ Validada · ☐ Validada con cambios · ☐ Replantear
Cambios pedidos:
