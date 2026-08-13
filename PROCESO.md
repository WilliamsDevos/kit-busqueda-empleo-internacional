# Cómo se mejora este kit

Este kit no se escribió de una sentada. Sale de una búsqueda de empleo real que sigue en curso, y cada pieza se corrigió cuando algo falló en la práctica.

Este documento explica cómo entra un aprendizaje nuevo, para que el kit mejore sin convertirse en un archivo de anécdotas y sin filtrar los datos personales de nadie.

---

## La regla de las dos capas

**Capa privada** — el proceso real de una persona: sus aplicaciones, su CV, su salario, sus documentos. Vive en un repositorio privado o en una carpeta local. Nunca sale de ahí.

**Capa pública** — este kit. Solo contiene el **método**: lo que se aprendió, sin quién lo aprendió.

El aprendizaje viaja de la primera a la segunda. Nunca al revés, y nunca con datos pegados.

---

## Qué sí y qué no cruza

| Cruza al kit | Se queda en privado |
|---|---|
| "Las vacantes remotas buenas cierran en menos de 24 horas" | Qué vacante concreta se perdió y de qué empresa |
| "3 de cada 4 remotas piden grabación de voz" | Los formularios de las cuatro empresas |
| "Una pasantía mal catalogada se lee como hueco laboral" | El perfil de LinkedIn donde pasó |
| "Cierra mercados con números, no con opiniones" | El umbral salarial que cerró un país concreto para un perfil concreto |
| Umbrales, plazos y reglas verificables, **con su fuente** | Nombres, teléfonos, direcciones, salarios, fechas de nacimiento |

**Nada de esto entra nunca al kit público:** nombre completo, dirección, teléfonos, fecha de nacimiento, número de pasaporte, salario actual o pedido, correos personales, nombres de empleadores actuales o anteriores, capturas de formularios llenados.

Los ejemplos se anonimizan y se generalizan: *"la ruta de migrante altamente cualificado de un país europeo exige X al mes para menores de 30"* en vez del caso con nombre y apellido.

---

## Cuándo escribir un aprendizaje

**Escríbelo el día que falla algo**, no al final del mes. La razón exacta se pierde en una semana y queda solo el resumen, que es la parte inútil.

Tres señales de que algo merece entrar al kit:

1. **Costó una oportunidad.** Una vacante perdida, una aplicación a medias, una entrevista que no llegó.
2. **Nadie te lo había dicho.** Si lo descubriste tú y era invisible desde afuera, a otro le va a pasar igual.
3. **Se puede convertir en una acción.** "Sé rápido" no sirve. "Filtra por publicadas hace menos de 48 horas y aplica el mismo día" sí.

Si no cumple ninguna de las tres, es una anécdota. Las anécdotas engordan el documento y hacen que nadie lo lea.

---

## Dónde va cada cosa

| Tipo de aprendizaje | Archivo |
|---|---|
| Regla de comportamiento del asistente | `skill/SKILL.md` y `PROMPT_MAESTRO.md` — **los dos** |
| Error que le cuesta entrevistas a cualquiera | `GUIA_RAPIDA.md` |
| Campo, documento o columna que hacía falta | `plantillas/` |
| Cambio en cómo se mantiene el kit | Este archivo |

**`skill/SKILL.md` y `PROMPT_MAESTRO.md` dicen lo mismo con distinta voz.** El SKILL le habla al asistente en segunda persona; el prompt lo escribe la persona en primera. Si cambias uno y no el otro, quedan dos métodos distintos con el mismo nombre. Cámbialos juntos o no cambies ninguno.

---

## Cómo se escribe

- **Una regla, una razón.** Toda instrucción trae el porqué. Sin el porqué, la primera vez que estorbe se ignora.
- **Verbo antes que consejo.** "Confirma que ese canal publique el puesto" en vez de "ten cuidado con los canales".
- **Números cuando los haya**, con su fecha y su fuente. Precios y umbrales caducan; un dato sin fecha es un dato que va a mentir dentro de un año.
- **Nada de relleno.** Si una frase se puede borrar sin perder información, se borra.

---

## Antes de publicar

1. Buscar en todo el repo nombres propios, teléfonos, direcciones, correos y cifras de salario.
2. Verificar que ningún archivo enlazado desde el README falte.
3. Verificar que `SKILL.md` y `PROMPT_MAESTRO.md` sigan diciendo lo mismo.
4. Comprobar que cada dato con número tenga fecha o fuente.

---

## Si lo usas y algo no funciona

Abre un issue. Los errores reales son lo que hace bueno a este método — se escribió entero a partir de cosas que salieron mal.

Interesa especialmente saber: en qué país y sector lo usaste, qué paso se rompió, y qué hiciste en su lugar.
