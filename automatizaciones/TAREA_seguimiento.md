# Tarea automática — Seguimiento de aplicaciones

Pégalo como prompt de una tarea programada con la frecuencia de `FRECUENCIA_SEGUIMIENTO`.

---

Lee `mi-configuracion.md` y el archivo indicado en `ARCHIVO_DE_REGISTRO` antes de hacer nada.

> Si `mi-configuracion.md` no existe, no improvises: dile al usuario que corra primero `TAREA_configurar.md` y detente ahí.

## Qué hacer

Revisa el estado de **todas** las aplicaciones que no estén cerradas.

Dónde mirar, en orden:

1. **El correo** — respuestas, rechazos, invitaciones a entrevista, confirmaciones. Mira también la carpeta de spam: los correos de portales ATS caen ahí con frecuencia.
2. **Los portales** donde aplicaste, si el estado se ve sin iniciar sesión
3. **LinkedIn → Applied jobs**, si aplicaste por ahí

**Solo lectura.** No respondas, no archives, no marques como leído.

## Qué hacer con lo que encuentres

**Respuesta positiva o invitación a entrevista** → arriba del reporte, con la fecha límite si la hay. Ofrece preparar: las 10 preguntas más probables del sector, respuestas usando su experiencia real, y las 3 preguntas que él debe hacer.

**Rechazo** → registrar y cerrar. Si van tres rechazos del mismo tipo de puesto, decirlo: es señal de que el CV o el perfil objetivo necesitan ajuste, no de que haya que aplicar más.

**Silencio de DIAS_HABILES_SEGUIMIENTO días hábiles** → redactar el correo de seguimiento, dejarlo listo, **no enviarlo**.

**Silencio de DIAS_PARA_DARLA_POR_MUERTA días** → marcar como cerrada sin respuesta y sacarla del conteo activo.

**Vacante que ya no existe** → cerrarla. Si cerró en menos de 48 horas desde que se publicó, anotarlo: es un dato sobre la velocidad que exige ese mercado.

## El correo de seguimiento

Cinco líneas, no más. Que aporte algo, no que solo pregunte.

```
Asunto: Following up — [Puesto] application ([fecha])

Hi [nombre, o "hiring team" si no lo hay],

I applied for [puesto] on [fecha] and wanted to check in on where
things stand.

[Una línea con algo nuevo: una certificación avanzada, un proyecto
terminado, disponibilidad que cambió. Si no hay nada nuevo, borra
esta línea antes que inventarla.]

I'm still very interested and available [disponibilidad].

Best,
[nombre]
```

**Un solo seguimiento por aplicación.** Un segundo no ayuda y molesta.

## El reporte

Si SOLO_NOVEDADES es "sí" y no hay novedades, escribe exactamente **"Sin novedades"** y nada más. No inventes actividad para justificar la corrida — es lo que hace que la gente deje de leer estos reportes.

```
SEGUIMIENTO — [fecha]

⚡ REQUIERE ACCIÓN HOY
- [solo si hay entrevistas o fechas límite]

NOVEDADES
- [Empresa]: [qué cambió]

SEGUIMIENTOS REDACTADOS (listos, sin enviar)
- [Empresa] — aplicada [fecha], van X días hábiles

CERRADAS
- [Empresa]: [rechazo / sin respuesta / vacante retirada]

ACTIVAS: N   ·   Esta semana: N de APLICACIONES_META_SEMANA

SIGUIENTE PASO: [una sola acción]
```

## Cada cuatro semanas, además

Un párrafo corto sobre lo que dicen los números, no sobre los números:

- **Aplicas mucho y no responde nadie** → el problema es el CV o el ajuste al puesto, no el volumen. Subir el volumen empeora las cosas.
- **Te responden pero no avanzas** → el problema está en la carta o en la primera entrevista.
- **Avanzas y caes al final** → suele ser una brecha real de credencial. Vale más invertir en cerrarla que seguir aplicando.

Dilo aunque no lo hayan preguntado. Es la parte del seguimiento que de verdad cambia resultados.
