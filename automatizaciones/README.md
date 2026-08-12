# Automatizaciones

Dos tareas que corren solas: una **busca** vacantes y te las deja listas para enviar, otra **revisa** el estado de lo que ya enviaste.

Lo que hacen que una lista de tareas manual no hace: siguen corriendo la semana que estás desanimado.

---

## Puesta en marcha

**Un solo paso.** Copia [`TAREA_configurar.md`](TAREA_configurar.md) y pégalo en tu asistente.

Te va a hacer unas preguntas cortas —qué buscas, cuánto ganas hoy, cuánto tiempo tienes, si tienes micrófono— y con eso escribe tu configuración, crea tu archivo de registro y deja las dos tareas programadas. Después te muestra un resumen y ya está corriendo.

**Tú no editas ningún archivo.** Si algo cambia, se lo dices en una frase: *"sube la meta a 15 por semana"*, *"agrega Portugal a los descartes"*, *"ya tengo micrófono"*. Él actualiza la configuración y el cambio aplica desde la siguiente corrida.

---

## Qué hay en esta carpeta

| Archivo | Para qué |
|---|---|
| [`TAREA_configurar.md`](TAREA_configurar.md) | **Empieza aquí.** Te entrevista y deja todo montado |
| [`TAREA_busqueda.md`](TAREA_busqueda.md) | El prompt de la tarea que busca vacantes |
| [`TAREA_seguimiento.md`](TAREA_seguimiento.md) | El prompt de la tarea que revisa estados |

Las dos últimas las programa el asistente por ti. Están aquí sueltas por si quieres leerlas antes, o pegarlas a mano si tu herramienta no programa tareas.

`mi-configuracion.md` lo genera el asistente en el primer paso. No existe hasta entonces.

---

## Los cuatro números que controlan todo

El asistente te los propone ya calculados según las horas que tengas. Vale la pena saber qué significan:

| Parámetro | Qué controla | Arranque razonable |
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

**Primera semana:** poco. El asistente todavía está aprendiendo cuáles son los portales buenos de tu sector y va a traer resultados genéricos. Corrígelo — esa corrección es la que hace que la segunda semana sirva.

**Tercera semana:** empiezan las respuestas de las primeras aplicaciones. La mayoría serán rechazos. Es normal y no significa que el sistema falle.

**Si a la cuarta semana enviaste mucho y no respondió nadie:** el problema no es el volumen, es el CV o el ajuste al puesto. La tarea de seguimiento te lo va a decir. Hazle caso — subir el volumen en ese punto solo multiplica el silencio.
