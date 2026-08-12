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

### Bloque 1 — Quién soy y qué busco
Profesión o área · años de experiencia · país de residencia y nacionalidad · idiomas con nivel real · puesto o puestos que busco.

> Si te subo el CV, no preguntes nada de esto. Léelo y pásame directo al bloque 2 con un resumen de una línea para que lo confirme.

### Bloque 2 — Mercado y modalidad
Remoto, reubicación con visa, rotacional/FIFO, marítimo, estacional, o mezcla · países que me interesan y los que descarto · si necesito patrocinio de visa sí o sí.

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

### Bloque 4 — Filtros duros
Qué tipo de trabajo no acepto bajo ninguna circunstancia · restricciones médicas, físicas o familiares · cuánto tiempo puedo estar fuera de casa.

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

Añade siempre estos descartes fijos, los haya mencionado yo o no: empleadores que cobren por contratar, tramitar visa o examen médico antes de una oferta escrita · anuncios sin nombre de empresa · agregadores que no lleven al portal oficial del empleador.

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
