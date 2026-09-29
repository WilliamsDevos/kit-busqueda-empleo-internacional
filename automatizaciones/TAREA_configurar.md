# Configuración — pégalo una sola vez

Este es el único paso manual. Copia todo lo que está debajo de la línea y pégalo en tu asistente. Te va a hacer unas preguntas cortas y, al terminar, deja las dos tareas automáticas funcionando.

**No tienes que editar ningún archivo.**

---

---

Vas a configurar mi sistema automático de búsqueda de empleo. Al terminar tendré dos tareas corriendo solas: una que busca vacantes y otra que revisa el estado de lo que ya envié.

## Cómo me preguntas

**Máximo 5 preguntas por bloque**, numeradas, en lenguaje sencillo. Espera mi respuesta antes de seguir.

**No me preguntes nada que puedas averiguar.** Si te doy mi CV o mi LinkedIn, léelos primero y da por contestado todo lo que ya esté ahí. Si no sé algo de mi propio sector —qué portales se usan, qué certificación piden— investígalo en internet y propónmelo, no me lo preguntes.

**Nunca me pidas un número en frío.** Propón uno con su razón y deja que lo confirme o lo cambie. "¿Cuántas vacantes por ronda?" no se responde bien; "te propongo 5, porque sostener diez semanas vale más que una de treinta — ¿te sirve?" sí.

**Si respondo "no sé", decide tú** y dime qué elegiste y por qué. No me devuelvas la pregunta.

## Qué necesitas averiguar

### Bloque 0 — Alcance (siempre lo primero)

**Antes de cualquier otra pregunta, aunque te dé el CV.** El CV no dice dónde quiero trabajar, y de esto depende todo lo demás: portales, formato del CV, salario, visas.

1. ¿Busco **local** (mi país), **internacional** o **ambos**?
2. ¿**Remoto**, **presencial** o **ambos**?

Según la combinación, haz la pregunta de seguimiento que toque:

- **Local + presencial** → ciudad y distancia máxima; si me mudaría dentro del país.
- **Local + remoto** → si solo empresas de mi país o también filiales de extranjeras que contraten remoto.
- **Internacional + remoto** → empleado o contratista, husos horarios que acepto, cómo prefiero cobrar.
- **Internacional + presencial** → reubicación permanente, rotacional (FIFO, offshore, cruceros) o estacional; si necesito patrocinio de visa.

> Si elijo "ambos", propón tú el reparto por porcentajes con su razón en una línea. Guarda las respuestas como `ALCANCE_GEOGRAFICO`, `MODALIDAD` y `DETALLE_DE_ALCANCE`.
>
> **El alcance decide qué se pregunta después.** Si busco solo local, no me preguntes por visas ni patrocinio. Si busco solo presencial, no me preguntes por micrófono ni cámara.

### Bloque 1 — Quién soy y qué busco
Profesión o área · años de experiencia · país de residencia y nacionalidad · idiomas con nivel real · puesto o puestos que busco.

> Si te subo el CV, no preguntes nada de esto. Léelo y pásame directo al bloque 2 con un resumen de una línea para que lo confirme.

### Bloque 2 — Mercados concretos
**El alcance ya lo definió el Bloque 0; no lo vuelvas a preguntar.** Aquí solo se afina dentro de él: qué mercados concretos (remoto, reubicación con visa, rotacional/FIFO, marítimo, estacional, o el mercado laboral local de mi ciudad) · países que me interesan y los que descarto · si necesito patrocinio de visa sí o sí (solo si el alcance es presencial en el extranjero).

> Propón tú el reparto por porcentajes según mi perfil y explícame en una línea por qué. No me hagas inventar la mezcla.

**Pregúntame también qué acepto como relleno.** Habrá semanas sin suficientes vacantes de mi modalidad principal, y es mejor saber ahora hasta dónde puedo abrir que dejarte adivinando. Plantéamelo así:

- ¿Acepto **presenciales en el extranjero** con reubicación?
- ¿Acepto **presenciales en mi propio país**? Si sí, ¿solo de empresas extranjeras o de cualquier empleador?
- ¿Cuántas de relleno por ronda como máximo?

Guarda la respuesta como `MODALIDADES_DE_RELLENO` y `TOPE_DE_RELLENO_POR_RONDA`. Si digo que no acepto ninguna, escribe "ninguna" — así en las rondas cortas te limitas a avisarme en vez de traer cosas que no quiero.

### Bloque 3 — Dinero
Qué gano hoy · mínimo que aceptaría · lo que voy a pedir.

> Investiga el rango real de mercado para mi puesto **antes** de sugerirme una cifra. Si mi mínimo está por encima de lo que paga el mercado, dímelo con el número en la mano, no con una opinión.
>
> Distingue: un puesto con alojamiento y comida incluidos no se compara directo con uno donde pago mi vida.

### Bloque 4 — Mis filtros (los defino yo)

**Tú no decides qué es una vacante mala; lo decido yo.** Pregúntame **un ámbito a la vez**, máximo 5 preguntas por mensaje, y **siempre con una propuesta ya redactada y su razón** para que la confirme, cambie o rechace. **Nunca guardes un filtro que no confirmé.** Si respondo "no sé", elige la opción más conservadora, dime cuál y por qué, y márcala como provisional.

Los ámbitos, con la propuesta que me haces en cada uno:

1. **Tipo de trabajo.** ¿Qué tareas no acepto? (atención telefónica, ventas con cuota, cobranzas, atención directa al cliente, turnos nocturnos, trabajo físico). Si rechazo el teléfono, pregunta cuánto sí tolero: si acepto llamadas escaladas de otro nivel, la prueba es si yo **soy la cola** (SLAs, AHT, "queue", BPO), no si hay llamadas.
2. **Sectores.** ¿Descarto alguno aunque el puesto sea aceptable? ¿Prefiero alguno? Propuesta: ninguno por defecto. Un rechazo de sector corta también los puestos que aceptaría en otro sector, y debo saberlo.
3. **Credenciales.** Si una vacante pide algo que no tengo: ¿descarto, aplico declarando la brecha, o solo si la empresa lo patrocina? Propuesta: aplicar declarando la brecha si está en curso o la empresa la patrocina; descartar si es rígido.
4. **Antigüedad del anuncio.** Propuesta: 48 horas en remoto y presencial estándar; 2 semanas en marítimo y offshore.
5. **Salario no publicado.** Propuesta: en presencial local, descartar (compite contra lo que ya gano); en internacional, no descartar (se negocia).
6. **Puesto ideal frente a entrar.** Solo si el alcance incluye rotacional, offshore, marítimo o Golfo. Propuesta: cualquier puesto que abra la puerta, sujeto a los filtros 1 y 2; dime el costo (empiezo fuera de mi perfil).

Además, pregúntame: restricciones médicas, físicas o familiares · cuánto tiempo puedo estar fuera de casa.

**Protecciones que no se preguntan, pero se me explican aquí:** empleadores que cobren por contratar, tramitar visa o examen médico antes de una oferta escrita · anuncios sin nombre de empresa · contacto solo por WhatsApp sin dominio de empresa · agregadores que no lleven al portal oficial.

### Bloque 5 — Con qué cuento
CV actual y si tengo versiones por perfil · **¿micrófono y cámara usables?** · espacio silencioso para grabar · certificaciones que tengo y las que están en curso, con fecha · documentos que sé que me faltan.

> Lo del micrófono no es un detalle. Una proporción alta de vacantes remotas internacionales exige grabación de voz o video. Si digo que no tengo, avísamelo ahora y no cuando ya perdí una hora llenando un formulario.

### Bloque 6 — Ritmo
Cuántas horas por semana puedo dedicarle.

> De ahí deduces tú los cuatro números de volumen y me los propones ya calculados. **Empieza bajo:** 5 vacantes por ronda, meta de 10 por semana, búsqueda y seguimiento cada 2 días. Diario casi siempre es demasiado — genera ruido, y el ruido hace que deje de leer los reportes, que es como esto se abandona de verdad.

---

## Al terminar el bloque 6

**1. Investiga dónde se publica de verdad mi trabajo.** Esto lo haces tú, no me lo preguntes. Necesito dos listas:

- **`PORTALES_PROPIOS_DE_MI_SECTOR`** — los portales especializados de mi industria y los regionales del mercado que busco. Casi ningún sector vive en los portales generalistas, y los regionales suelen ser invisibles desde fuera de esa región. Verifica que cada uno tenga vacantes vivas de mi perfil ahora mismo; si está vacío, no lo listes.
- **`PAGINAS_DE_CARRERA_A_REVISAR`** — 3 a 5 empleadores concretos que contraten mi perfil, con el enlace directo a su sección de empleo. Muchos publican ahí antes que en ningún portal, y algunos solo ahí.

Si no encuentras nada específico para mi sector, dilo. No inventes nombres de portales.

**2. Escribe el archivo `mi-configuracion.md`** con exactamente esta estructura, sin campos vacíos y sin inventar nada que yo no haya confirmado:

```
ALCANCE_GEOGRAFICO:  (local | internacional | ambos, con % si es ambos)
MODALIDAD:           (remoto | presencial | ambos, con % si es ambos)
DETALLE_DE_ALCANCE:  (ciudad y radio si es local presencial · rotacional/reubicación/estacional si es internacional presencial · empleado o contratista si es remoto)

PERFIL_OBJETIVO:
PERFILES_SECUNDARIOS:
PAIS_DE_RESIDENCIA:
NACIONALIDAD:
IDIOMAS:
ANOS_DE_EXPERIENCIA:

VACANTES_POR_RONDA:
APLICACIONES_META_SEMANA:
FRECUENCIA_BUSQUEDA:
FRECUENCIA_SEGUIMIENTO:
DIAS_HABILES_SEGUIMIENTO:
DIAS_PARA_DARLA_POR_MUERTA:

MERCADOS:            (mercado: % del total)
MODALIDADES_DE_RELLENO:
TOPE_DE_RELLENO_POR_RONDA:
PAISES_QUE_ME_INTERESAN:
PAISES_QUE_DESCARTO:
NECESITO_PATROCINIO_DE_VISA:
PORTALES_PROPIOS_DE_MI_SECTOR:
PAGINAS_DE_CARRERA_A_REVISAR:

SALARIO_PISO:
SALARIO_OBJETIVO:
MI_SALARIO_ACTUAL:
ANTIGUEDAD_MAXIMA_DEL_ANUNCIO:
FILTRO_TIPO_DE_TRABAJO:            (tareas que NO acepto, con mis palabras y la fecha)
FILTRO_SECTORES_EXCLUIDOS:         (sectores que descarto aunque el puesto sea aceptable, o "ninguno")
FILTRO_SECTORES_PREFERIDOS:        (o "ninguno")
POLITICA_DE_CREDENCIALES:          (descartar | aplicar declarando la brecha | solo si la empresa patrocina)
POLITICA_SALARIO_NO_PUBLICADO:     (por modalidad: descartar | no descartar)
OBJETIVO_EN_MERCADOS_DE_ENTRADA:   (mi puesto | cualquier puesto que abra la puerta | no aplica)
NO_QUIERO_BAJO_NINGUNA_CIRCUNSTANCIA:

CV_POR_PERFIL:       (perfil: nombre_archivo.pdf)
TENGO_MICROFONO_USABLE:
TENGO_CAMARA_USABLE:
DOCUMENTOS_QUE_ME_FALTAN:

IDIOMA_DEL_REPORTE:
SOLO_NOVEDADES:
DONDE_GUARDAR:
ARCHIVO_DE_REGISTRO:
```

Añade siempre las protecciones fijas de seguridad, las haya mencionado yo o no: empleadores que cobren por contratar, tramitar visa o examen médico antes de una oferta escrita · anuncios sin nombre de empresa · contacto solo por WhatsApp sin dominio de empresa · agregadores que no lleven al portal oficial del empleador.

**Todo lo demás son filtros míos, y solo se escribe lo que yo confirmé.** Nada de "por defecto".

**Los campos que el alcance vuelve irrelevantes se escriben como "no aplica", no como vacíos.** Ejemplo: `NECESITO_PATROCINIO_DE_VISA: no aplica (búsqueda local)`.

**3. Crea el archivo de registro** copiando `plantillas/TRACKER_APLICACIONES.md` al nombre y lugar que quedaron en `ARCHIVO_DE_REGISTRO`.

**4. Programa las dos tareas automáticas.** Si tu herramienta puede crear tareas recurrentes, créalas tú:

- Una con la frecuencia de `FRECUENCIA_BUSQUEDA`, usando como prompt el contenido de `TAREA_busqueda.md`
- Otra con la frecuencia de `FRECUENCIA_SEGUIMIENTO`, usando `TAREA_seguimiento.md`

Si tu herramienta **no** programa tareas, dímelo claramente y explícame en dos líneas cómo pegarlas a mano con un recordatorio de calendario. Pierdo la automatización, no el método.

**5. Córrelas una vez delante de mí.** La primera ejecución suele pedir permisos de navegador o de correo. Mejor que eso pase ahora y no a las 8 de la mañana en una corrida que se queda trabada esperando una autorización que nadie va a dar.

**6. Muéstrame el resumen** y nada más:

```
CONFIGURACIÓN LISTA

Buscando:     [perfil] en [mercados con sus %]
Volumen:      [N] vacantes por ronda · meta [N] por semana
Ritmo:        busca [frecuencia] · revisa [frecuencia]
Salario:      piso [X] · pides [Y]
Descartas:    [lo que dije, en una línea]

⚠️ [solo si hay algo que me bloquea: sin micrófono, un documento
    caducado, un mínimo salarial por encima del mercado]

PRIMERA BÚSQUEDA: [cuándo corre]
```

---

## Para cambiar algo después

No hace falta repetir nada de esto. Basta con decírselo al asistente en una frase — *"sube la meta a 15 por semana"*, *"agrega Portugal a los países que descarto"*, *"ya tengo micrófono"* — y él actualiza `mi-configuracion.md`. Las dos tareas leen el archivo en cada corrida, así que el cambio aplica desde la siguiente.

**Vale la pena revisar la configuración cada mes.** Lo que más suele cambiar: el piso salarial, después de ver lo que paga el mercado de verdad; y los portales, cuando descubres cuáles sí traen vacantes de tu sector.
