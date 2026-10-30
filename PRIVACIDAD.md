# Privacidad — léelo antes de usar el kit

Este repositorio no contiene datos de nadie y no recoge nada. Pero **el kit sí genera archivos con tus datos personales**, y ahí está el riesgo real.

---

## El error que hay que evitar

Clonas el repo, corres la configuración dentro de la carpeta, y el asistente crea `mi-configuracion.md` con tu nombre, tu teléfono, tu dirección, tu salario actual y el que pides. Después haces `git add .` y `git push` sobre tu fork.

**Acabas de publicar tu salario y tu dirección en internet.**

Hay un `.gitignore` que cubre los nombres de archivo previsibles, pero no puede adivinar cómo llamaste a los tuyos.

## Cómo evitarlo

**Lo más seguro: no trabajes dentro del repo.** Copia el kit a otra carpeta y trabaja ahí.

```
mi-busqueda/          ← tus datos viven aquí, sin git
kit-.../              ← el repo, solo lectura
```

**Si prefieres tenerlo todo junto y versionado, que tu repositorio sea privado.** En GitHub: Settings → General → Danger Zone → Change visibility.

**Antes de cada push, mira qué estás subiendo.** `git status` y `git diff --cached` toman cinco segundos y evitan el problema entero.

---

## Qué contiene cada archivo que genera el kit

| Archivo | Qué guarda |
|---|---|
| `mi-configuracion.md` | Nombre, país, salario actual y objetivo, filtros personales |
| Tu archivo de registro | Empresas donde aplicaste, fechas, estados, notas |
| Tus CV | Todo: dirección, teléfonos, historial laboral completo |
| Cartas de presentación | Nombre, contacto, a veces cifras de salario |

El de registro parece inofensivo y no lo es: la lista de dónde estás aplicando, si la ve tu empleador actual, es exactamente la información que no querías que tuviera.

---

## Cuidado con tu empleador actual

Si sigues empleado, hay tres fugas comunes que no tienen nada que ver con git:

- **El marco #OpenToWork visible para todos** también lo ve tu empresa. La opción "solo reclutadores" existe.
- **Los portales de empleo suelen tener un ajuste de visibilidad del perfil.** "Público" significa indexable por Google. Si tu empleador busca tu nombre, te encuentra buscando trabajo.
- **Pedirle una carta laboral a tu jefe actual** le avisa de que estás buscando. Usa empleadores anteriores o el certificado educativo.

---

## El chat es una copia

Todo lo que pegas en tu asistente queda en el lado del proveedor: el histórico de la conversación y, según la herramienta, su retención. Un CV pegado completo lleva tu dirección y tu teléfono; la hoja de datos maestros lleva tu documento de identidad y tu fecha de nacimiento.

- **Pega lo mínimo que la tarea necesite.** Si la entrevista pide tres campos, no pegues el documento entero.
- **Contraseñas y códigos de verificación no van al chat.** Lo que el portal de empleo necesite que escribas, se escribe ahí mismo en el portal — no en la conversación.
- Si tu herramienta ofrece un modo sin histórico o privado, los pasos con más datos van ahí.

---

## Contribuir

Si abres un issue o un pull request, **no pegues tu configuración, tu CV ni capturas con tus datos.** Anonimiza antes: cambia nombres, teléfonos y cifras por ejemplos.

Los issues de este repositorio son públicos y quedan indexados.
