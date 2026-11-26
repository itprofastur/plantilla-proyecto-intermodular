# Fase 02 · Requisitos

> 🔤 **Códigos que verás:** **RF-01** = requisito funcional 1 · **RNF-01** = requisito no funcional 1 · **RN-01** = regla de negocio 1 (y así sucesivamente)

**🎭 Hoy eres** **Analista funcional**: traduce lo que el cliente necesita a requisitos claros y comprobables.  
**📦 Al terminar tendrás:** Requisitos funcionales, no funcionales y reglas de negocio de tu producto mínimo viable · **⏱** 1-2 sesiones

`DESCUBRIR 01·[02]·03·04 │ DISEÑAR 05·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD 14·15 │ ENTREGAR 16·17·18`

**Partes de:** usuarios y producto mínimo viable de la [fase 01](01-producto.md).

## 1. Entrevista al cliente
🧭 Prepara 5-8 preguntas **antes** de hablar con el cliente (el profesor). Pregunta por: quién lo usa, qué hace paso a paso, qué pasa si algo sale mal, qué límites hay. Evita preguntas de sí o no.

> 💡 **Ejemplo ReservAula:** «¿Qué pasa hoy cuando dos profesores quieren la misma aula a la misma hora?»

| Pregunta | Respuesta del cliente |
|---|---|
| | |
| | |
| | |

## 2. Requisitos funcionales: qué debe HACER el sistema
🧭 Formato: *El sistema permitirá a* [actor] [acción]. Cada requisito funcional sale de una capacidad del producto mínimo viable.

> 💡 **Ejemplo ReservAula:** RF-03 · El sistema permitirá al profesorado reservar una franja libre de un aula · Capacidad: reservar.

*Ejemplo:* `RF-03 · El sistema permitirá al profesorado reservar un aula libre indicando fecha y franja.`

| ID | Requisito | Capacidad del producto mínimo |
|---|---|---|
| RF-01 | | |
| RF-02 | | |
| RF-03 | | |

## 3. Requisitos no funcionales: CÓMO de bien debe hacerlo
🧭 Solo los que importan en tu proyecto (3-5) y que se puedan **comprobar**. *Mal:* «que sea rápida». *Bien:* «el listado carga en menos de 2 s con 100 registros».

| ID | Requisito | Cómo lo comprobaré |
|---|---|---|
| RNF-01 | | |
| RNF-02 | | |

## 4. Reglas de negocio: las normas del mundo real
🧭 *Ejemplo:* `RN-01 · Un aula no puede tener dos reservas en la misma fecha y franja.`

| ID | Regla | Qué pasa si se incumple |
|---|---|---|
| RN-01 | | |
| RN-02 | | |

## 5. Dudas, contradicciones y cambios de alcance

> 💡 **Ejemplo ReservAula:** Duda: ¿un profesor puede reservar para otro? La pregunto al cliente y apunto aquí su respuesta.

-

🧭 Añade en [`TRAZABILIDAD.md`](TRAZABILIDAD.md) qué requisito funcional sale de cada capacidad del producto mínimo viable.

## ✅ Hecho cuando
- [ ] Cada requisito funcional sale de una capacidad del producto mínimo viable. No hay requisitos funcionales «huérfanos».
- [ ] Todos los requisitos no funcionales se pueden comprobar.
- [ ] He incluido reglas sobre lo que **no** se permite.
- [ ] El cliente ha respondido mis dudas o están anotadas.

## 🗣 Compruébalo
Deberías poder explicar **la diferencia entre un requisito funcional, uno no funcional y una regla de negocio** usando un ejemplo de tu propio proyecto.

---
**Revisión del cliente/profesor:** ☐ Validada · ☐ Validada con cambios · ☐ Replantear
Cambios pedidos:
