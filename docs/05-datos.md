# Fase 05 · Modelo de datos

> 🔤 **Códigos que verás:** **RN-01** = regla de negocio 1 (y así sucesivamente)

**🎭 Hoy eres** **Diseñador/a de datos**: decide qué información guarda el sistema y cómo se relaciona.  
**📦 Al terminar tendrás:** El modelo de datos **y tu base de datos creada y con datos de ejemplo** · **⏱** 1-2 sesiones

`DESCUBRIR 01·02·03·04 │ DISEÑAR [05]·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD 14·15 │ ENTREGAR 16·17·18`

**Partes de:** pantallas (04), historias (03) y reglas de negocio (02).

## 1. ¿Qué información aparece?
🧭 Recorre tus pantallas y anota cada dato que se ve, se escribe o se consulta.

> 💡 **Ejemplo ReservAula:** Semana del aula · nombre del aula, día, franja horaria y quién reservó.

| Pantalla / historia | Datos que aparecen |
|---|---|
| | |

## 2. Entidades, atributos y clave

> 💡 **Ejemplo ReservAula:** RESERVA · id, usuario_id, aula_id, franja_id, fecha, creada_en · Clave primaria: id

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

> 💡 **Ejemplo ReservAula:** RN-01 Sin dobles reservas · Base de datos · UNIQUE (aula_id, fecha, franja_id)

| Regla | Dónde la protejo | Cómo |
|---|---|---|
| RN-__ | ☐ Base de datos ☐ Servidor | |

## 5. Diagrama
🧭 Con dbdiagram.io, draw.io o MySQL Workbench. Guárdalo en `docs/img/05-modelo.png`.

> 💡 **Ejemplo ReservAula:** Cuatro cajas (USUARIO, AULA, FRANJA y RESERVA) unidas por líneas 1 : N hacia RESERVA.

![Modelo de datos](img/05-modelo.png)

## 6. Hazlo real

> 💡 **Ejemplo ReservAula:** «¿Qué franjas del aula 204 están ocupadas el jueves?» → `SELECT franja_id FROM reserva WHERE aula_id = 204 AND fecha = '2027-01-14';`

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
