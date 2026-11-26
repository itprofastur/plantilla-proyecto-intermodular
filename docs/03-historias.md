# Fase 03 · Historias de usuario

> 🔤 **Códigos que verás:** **RF-01** = requisito funcional 1 · **RN-01** = regla de negocio 1 · **HU-01** = historia de usuario 1 · **CA1** = criterio de aceptación 1 (y así sucesivamente)

**🎭 Hoy eres** **Product Owner**: representa al cliente ante el equipo y decide qué aporta más valor.  
**📦 Al terminar tendrás:** Las historias del producto mínimo viable con criterios de aceptación: la base de tu backlog · **⏱** 1-2 sesiones

`DESCUBRIR 01·02·[03]·04 │ DISEÑAR 05·06 │ PLANIFICAR 07·08 │ CONSTRUIR 09·10·11·12·13 │ CALIDAD 14·15 │ ENTREGAR 16·17·18`

**Partes de:** los requisitos funcionales y las reglas de negocio de la [fase 02](02-requisitos.md).

## 1. Escribe las historias
🧭 Formato: **Como** [usuario] **quiero** [acción] **para** [beneficio]. Una historia = algo que el usuario puede hacer y notar. Agrupa los requisitos funcionales que hablan de la misma necesidad.

## 2. Añade los criterios de aceptación
🧭 Formato: **Dado** [situación] **cuando** [acción] **entonces** [resultado observable]. Incluye **al menos un caso negativo** (qué pasa cuando algo no se permite). Son los que usarás para comprobar si la historia está terminada.

Copia este bloque para cada historia:

### HU-01 · [título corto]
**Como** … **quiero** … **para** …
**Viene de:** RF-__ · RN-__ · **Depende de:** HU-__ (o «ninguna»)

- [ ] **CA1** · Dado … cuando … entonces …
- [ ] **CA2** · Dado … cuando … entonces …
- [ ] **CA3 (caso negativo)** · Dado … cuando … entonces …

> 💡 **Ejemplo ReservAula**
>
> **HU-02 · Reservar una franja**
> **Como** profesor/a **quiero** reservar una franja libre de un aula **para** asegurarla para mi clase.
> **Viene de:** RF-03 · RN-01 · RN-02 · **Depende de:** HU-01
>
> - **CA1** · Dado una franja libre en una fecha futura, cuando confirmo la reserva, entonces la franja aparece ocupada a mi nombre y en «Mis reservas».
> - **CA2** · Dado una franja ya ocupada, cuando intento reservarla, entonces no se crea la reserva y veo «Esa franja ya está reservada».
> - **CA3** · Dado una fecha pasada, cuando abro el calendario, entonces no puedo seleccionarla.

## 3. Revisa el tamaño
🧭 Si una historia no cabe en una semana de trabajo o tiene más de 5-6 criterios, divídela. Pregúntate: «¿puedo entregar una parte útil antes?».

> 💡 **Ejemplo ReservAula:** «Gestionar reservas» era demasiado grande. La dividimos en HU-02 Reservar y HU-03 Cancelar.

## ✅ Hecho cuando
- [ ] Todos los requisitos funcionales están cubiertos por alguna historia (anótalo en [`TRAZABILIDAD.md`](TRAZABILIDAD.md)).
- [ ] Cada historia dice **para qué**, no solo qué.
- [ ] Cada criterio se puede comprobar con un sí o un no.
- [ ] Ninguna historia habla de tecnología («crear tabla», «hacer endpoint»).

## 🗣 Compruébalo
Elige una historia y explica **cómo sabrías, sin mirar el código, que está terminada.**

---
**Revisión del cliente/profesor:** ☐ Validada · ☐ Validada con cambios · ☐ Replantear
Cambios pedidos:
