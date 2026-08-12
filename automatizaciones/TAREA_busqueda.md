# Tarea automática — Búsqueda de vacantes

Pégalo como prompt de una tarea programada con la frecuencia de `FRECUENCIA_BUSQUEDA`.

---

Lee `mi-configuracion.md` y el archivo indicado en `ARCHIVO_DE_REGISTRO` antes de hacer nada. Todo lo que sigue usa esos valores.

> Si `mi-configuracion.md` no existe, no improvises: dile al usuario que corra primero `TAREA_configurar.md` y detente ahí.

## Qué hacer

Busca **VACANTES_POR_RONDA** vacantes nuevas para PERFIL_OBJETIVO y PERFILES_SECUNDARIOS, repartidas según los porcentajes de MERCADOS.

**Busca en internet. No uses tu memoria.** Las vacantes expiran; una lista de tu memoria es una lista de vacantes muertas.

Prioriza en este orden:

1. Publicadas hace menos de ANTIGUEDAD_MAXIMA_DEL_ANUNCIO
2. Con pocos aplicantes
3. En PORTALES_PROPIOS_DE_MI_SECTOR antes que en los portales generalistas
4. Que no exijan un requisito que aparezca en DOCUMENTOS_QUE_ME_FALTAN

## Nunca hagas una ronda de un solo portal

Cada portal cubre un pedazo del mercado y ninguno los cubre todos. **LinkedIn en particular cubre bien el mercado remoto anglosajón y casi nada de lo rotacional, presencial internacional o de sectores especializados.**

Toca como mínimo, en cada ronda:

- **Dos portales sectoriales** de PORTALES_PROPIOS_DE_MI_SECTOR
- **Una página de carrera de un empleador** directamente. Identifica 3–5 empresas que contraten mi perfil y revisa su sección de empleo. Muchas publican ahí primero, y algunas *solo* ahí.
- **Un portal regional** del mercado que busco. Cada región tiene el suyo y suelen ser invisibles desde fuera.

**Si un agregador muestra una vacante, búscala en la web del empleador y aplica ahí.** El agregador sirve para descubrir; el portal oficial es donde la aplicación cuenta.

**Verifica el canal correcto dentro del portal.** Los empleadores grandes segmentan por región o marca, y no todos los canales publican todos los puestos. Aplicar por el canal equivocado pierde la aplicación entera.

## Descarta sin preguntar

- Todo lo de NO_QUIERO_BAJO_NINGUNA_CIRCUNSTANCIA
- Salario por debajo de SALARIO_PISO, o rango de mercado que no lo alcance
- Empleadores que cobren por contratar, tramitar visa o examen médico
- Anuncios sin nombre de empresa
- Agregadores que no lleven al portal oficial
- Lo que ya esté en tu archivo de registro

**No rellenes el cupo con vacantes malas.** Si solo encuentras 4 buenas, trae 4 y dilo. Una lista inflada hace perder más tiempo del que ahorra.

## Lee el anuncio COMPLETO antes de juzgarlo

**Nunca decidas con el resumen ni con el primer párrafo visible.** Casi todos los portales cortan la descripción con un "Read more", "Ver más", "Show full description" o un acordeón, y **el requisito que descalifica la vacante suele estar justo debajo del corte**.

Antes de evaluar: expande todo lo que esté colapsado, baja hasta el final, y confirma que estás viendo responsabilidades y requisitos completos. Si el portal no deja ver el texto entero, abre la vacante en la página oficial del empleador.

**Desconfía del texto promocional.** Un anuncio que dice *"you aren't just reading from a script"* o *"this isn't your typical support role"* está anticipándose a una objeción real. Juzga por la lista de responsabilidades, no por cómo se describe a sí mismo.

## Con cada vacante que pase el filtro

1. **Verifica que siga viva.** Abre el enlace. Si dio 404 o dice "closed", no la listes.
2. **Prepara la aplicación completa:** URL oficial, qué CV de CV_POR_PERFIL adjuntar, asunto y carta de máximo 250 palabras — primer párrafo con algo real de esa empresa, segundo con el resultado más fuerte y su número, tercero declarando de frente cualquier requisito que falte.
3. **Rellena el formulario hasta donde puedas** y déjalo listo para Submit. **Nunca envíes.**
4. Si pide grabación de voz o video, **avísalo arriba del todo** y escribe el guion.
5. Registra la fila en ARCHIVO_DE_REGISTRO con estado "lista para enviar".

## Lo que nunca haces

Crear cuentas · escribir contraseñas · marcar casillas de consentimiento · grabar audio o video · enviar sin aprobación · inventar un dato que no esté en `mi-configuracion.md`.

Cuando llegues a un campo que no puedas contestar con certeza, **anótalo en la lista de "necesito de ti"** en vez de adivinar.

## El reporte

Máximo una pantalla. Si SOLO_NOVEDADES es "sí", no repitas nada de rondas anteriores.

```
BÚSQUEDA — [fecha]

Encontradas: N   ·   Listas para enviar: N   ·   Descartadas: N

LISTAS PARA ENVIAR
1. [Empresa] — [Puesto] · [país/modalidad] · [salario o "no publicado"]
   Publicada hace: X   ·   Estado: falta [lo que falta] o "solo Submit"

NECESITO DE TI
- [una línea por cosa, solo lo que te bloquea]

DESCARTADAS: N por [razón agrupada]

VAS EN: N de APLICACIONES_META_SEMANA esta semana.

SIGUIENTE PASO: [una sola acción, la más importante]
```

Termina siempre con **una sola acción**. Una lista de veinte cosas paraliza.

## Si no llegas al número

**Primero agota `MODALIDADES_DE_RELLENO`.** Si están configuradas, complétalas hasta su tope y márcalas como relleno en el reporte. Nunca desplazan a una vacante de las modalidades principales: solo llenan el hueco que quedó.

**Si aun así te quedas corto, no inventes ni bajes el listón en silencio.** Di el número real y pregunta. Ejemplos de pregunta útil:

- *"Encontré 6 de 10. ¿Amplío a presenciales en tu ciudad? ¿Subo el tope de relleno esta ronda?"*
- *"Solo hay 3 dentro de tu piso salarial. ¿Bajo el piso esta semana o prefiero calidad sobre cantidad?"*
- *"Tu perfil objetivo casi no tiene vacantes esta semana. ¿Abro a [perfil adyacente]?"*

Pregunta con la alternativa concreta ya propuesta. Una pregunta abierta obliga al usuario a hacer el trabajo de pensar la opción.

## Si te quedas corto dos rondas seguidas

No subas el volumen: cambia el planteamiento. Dilo en el reporte y propón una de estas.

- El perfil objetivo es demasiado estrecho para el mercado
- Estás buscando en los portales equivocados para el sector
- El piso salarial está por encima de lo que paga el mercado para ese perfil
- Hace falta un puesto puente: menos ideal, alcanzable en 60 días
