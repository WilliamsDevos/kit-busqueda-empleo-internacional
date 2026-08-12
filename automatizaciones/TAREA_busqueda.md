# Tarea automática — Búsqueda de vacantes

Pégalo como prompt de una tarea programada con la frecuencia de `FRECUENCIA_BUSQUEDA`.

---

Lee `CONFIG.md` y `TRACKER_APLICACIONES.md` antes de hacer nada. Todo lo que sigue usa esos valores.

## Qué hacer

Busca **VACANTES_POR_RONDA** vacantes nuevas para PERFIL_OBJETIVO y PERFILES_SECUNDARIOS, repartidas según los porcentajes de MERCADOS.

**Busca en internet. No uses tu memoria.** Las vacantes expiran; una lista de tu memoria es una lista de vacantes muertas.

Prioriza en este orden:

1. Publicadas hace menos de ANTIGUEDAD_MAXIMA_DEL_ANUNCIO
2. Con pocos aplicantes
3. En PORTALES_PROPIOS_DE_MI_SECTOR antes que en los portales generalistas
4. Que no exijan un requisito que aparezca en DOCUMENTOS_QUE_ME_FALTAN

## Descarta sin preguntar

- Todo lo de NO_QUIERO_BAJO_NINGUNA_CIRCUNSTANCIA
- Salario por debajo de SALARIO_PISO, o rango de mercado que no lo alcance
- Empleadores que cobren por contratar, tramitar visa o examen médico
- Anuncios sin nombre de empresa
- Agregadores que no lleven al portal oficial
- Lo que ya esté en TRACKER_APLICACIONES.md

**No rellenes el cupo con vacantes malas.** Si solo encuentras 4 buenas, trae 4 y dilo. Una lista inflada hace perder más tiempo del que ahorra.

## Con cada vacante que pase el filtro

1. **Verifica que siga viva.** Abre el enlace. Si dio 404 o dice "closed", no la listes.
2. **Prepara la aplicación completa:** URL oficial, qué CV de CV_POR_PERFIL adjuntar, asunto y carta de máximo 250 palabras — primer párrafo con algo real de esa empresa, segundo con el resultado más fuerte y su número, tercero declarando de frente cualquier requisito que falte.
3. **Rellena el formulario hasta donde puedas** y déjalo listo para Submit. **Nunca envíes.**
4. Si pide grabación de voz o video, **avísalo arriba del todo** y escribe el guion.
5. Registra la fila en TRACKER_APLICACIONES.md con estado "lista para enviar".

## Lo que nunca haces

Crear cuentas · escribir contraseñas · marcar casillas de consentimiento · grabar audio o video · enviar sin aprobación · inventar un dato que no esté en CONFIG.md.

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

## Si te quedas corto dos rondas seguidas

No subas el volumen: cambia el planteamiento. Dilo en el reporte y propón una de estas.

- El perfil objetivo es demasiado estrecho para el mercado
- Estás buscando en los portales equivocados para el sector
- El piso salarial está por encima de lo que paga el mercado para ese perfil
- Hace falta un puesto puente: menos ideal, alcanzable en 60 días
