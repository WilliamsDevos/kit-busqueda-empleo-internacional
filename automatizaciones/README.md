# Automatizaciones

Dos tareas que corren solas: una **busca** vacantes y te las deja listas para enviar, otra **revisa** el estado de lo que ya enviaste.

Lo que hacen que una lista de tareas manual no hace: siguen corriendo la semana que estás desanimado.

---

## Puesta en marcha, 10 minutos

**1. Llena [`CONFIG.md`](CONFIG.md).** Es lo único que se edita. Las dos tareas leen de ahí.

**2. Crea la tarea de búsqueda.** En tu asistente, programa una tarea recurrente con la frecuencia de `FRECUENCIA_BUSQUEDA` y pega como prompt el contenido de [`TAREA_busqueda.md`](TAREA_busqueda.md).

**3. Crea la tarea de seguimiento.** Igual, con `FRECUENCIA_SEGUIMIENTO` y [`TAREA_seguimiento.md`](TAREA_seguimiento.md).

**4. Córrelas a mano una vez.** La primera ejecución suele pedir permisos de navegador o correo. Mejor que eso pase contigo delante y no a las 8 de la mañana en una corrida automática que se queda trabada esperando.

> **Si tu asistente no programa tareas:** las plantillas funcionan igual pegadas a mano. Ponte un recordatorio en el calendario con la misma frecuencia. Pierdes la automatización, no el método.

---

## Los cuatro números que controlan todo

| Parámetro | Qué controla | Si empiezas |
|---|---|---|
| `VACANTES_POR_RONDA` | Cuántas trae cada búsqueda | 5 |
| `APLICACIONES_META_SEMANA` | Meta de envíos por semana | 10 |
| `FRECUENCIA_BUSQUEDA` | Cada cuánto busca | cada 2 días |
| `FRECUENCIA_SEGUIMIENTO` | Cada cuánto revisa estados | cada 2 días |

**Empieza bajo.** Diez semanas sostenidas a 10 por semana valen más que una semana de 30 y luego nada. Sube el número cuando lleves dos semanas cumpliendo la meta, no antes.

**Diario es casi siempre demasiado.** Genera ruido, y el ruido hace que dejes de leer el reporte — que es la forma más común en que esto se abandona.

---

## Por qué dejan las aplicaciones sin enviar

Las dos tareas rellenan todo y se detienen antes del Submit. A propósito.

No es una limitación técnica: es que **el que responde en la entrevista eres tú.** Si no leíste lo que se envió, la primera llamada te agarra explicando algo que no escribiste. Revisar y dar Submit toma un minuto por aplicación y es el minuto que hace que el resto sirva.

Tampoco crean cuentas, escriben contraseñas, marcan casillas de consentimiento ni graban tu voz.

---

## Qué esperar de verdad

**Primera semana:** poco. El asistente todavía no sabe cuáles son los portales de tu sector y va a traer resultados genéricos. Corrígelo y anota los portales buenos en `PORTALES_PROPIOS_DE_MI_SECTOR`.

**Tercera semana:** empiezan las respuestas de las primeras aplicaciones. La mayoría serán rechazos. Es normal y no significa que el sistema falle.

**Si a la cuarta semana enviaste mucho y no respondió nadie:** el problema no es el volumen, es el CV o el ajuste al puesto. La tarea de seguimiento te lo va a decir. Hazle caso — subir el volumen en ese punto solo multiplica el silencio.
