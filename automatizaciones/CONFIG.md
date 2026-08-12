# CONFIG — tus parámetros

Edita este archivo **una vez**. Las dos tareas automáticas leen de aquí.

Todo lo que está entre `<< >>` es para reemplazar. Si algo no aplica a tu caso, escribe `ninguno` en vez de borrarlo — las plantillas esperan encontrar la línea.

---

## Quién eres

```
PERFIL_OBJETIVO:        << ej. Soporte IT remoto / Soldador offshore / Enfermera >>
PERFILES_SECUNDARIOS:   << otros puestos que también aceptas, o "ninguno" >>
PAIS_DE_RESIDENCIA:     << >>
NACIONALIDAD:           << >>
IDIOMAS:                << ej. Español nativo, inglés avanzado >>
ANOS_DE_EXPERIENCIA:    << >>
```

---

## Cuánto y cada cuánto

Estos cuatro números controlan el volumen de todo el sistema.

```
VACANTES_POR_RONDA:        << ej. 10 >>   # cuántas vacantes traer en cada búsqueda
APLICACIONES_META_SEMANA:  << ej. 15 >>   # meta de envíos distintos por semana
FRECUENCIA_BUSQUEDA:       << ej. cada 2 días a las 8:30 >>
FRECUENCIA_SEGUIMIENTO:    << ej. cada 2 días a las 8:00 >>
DIAS_HABILES_SEGUIMIENTO:  << ej. 10 >>   # cuándo escribir tras aplicar sin respuesta
DIAS_PARA_DARLA_POR_MUERTA: << ej. 30 >>  # cuándo archivar una aplicación sin respuesta
```

> **Cómo elegir el volumen.** Si nunca has hecho esto, empieza en 5 por ronda y 10 por semana. Es preferible sostener 10 semanas seguidas que hacer 30 una semana y abandonar. Sube el número solo cuando lleves dos semanas cumpliendo.

---

## Dónde buscar

```
MERCADOS:
  - << mercado 1 >>: << % del total >>
  - << mercado 2 >>: << % del total >>
# Ejemplo: "remoto internacional: 50" / "rotacional y offshore: 50"

PAISES_QUE_ME_INTERESAN:  << o "cualquiera" >>
PAISES_QUE_DESCARTO:      << o "ninguno" >>
NECESITO_PATROCINIO_DE_VISA: << sí / no / solo para algunos mercados >>

PORTALES_PROPIOS_DE_MI_SECTOR:
  - << ej. Rigzone, allcruisejobs, Job Bank, un colegio profesional >>
# Muchos sectores no usan los portales grandes. Si no sabes cuáles son los tuyos,
# pídele al asistente que los investigue en la primera ronda y los escriba aquí.
```

---

## Filtros duros

Lo que se descarta sin discusión. Es la parte que más tiempo ahorra.

```
SALARIO_PISO:       << ej. USD 1400/mes — por debajo no se aplica >>
SALARIO_OBJETIVO:   << ej. USD 1800/mes — lo que se pide en los formularios >>
MI_SALARIO_ACTUAL:  << para calcular si una oferta realmente mejora tu vida >>

ANTIGUEDAD_MAXIMA_DEL_ANUNCIO: << ej. 48 horas >>
# Las vacantes remotas buenas cierran en menos de 24 h. Este filtro importa más
# de lo que parece.

NO_QUIERO_BAJO_NINGUNA_CIRCUNSTANCIA:
  - << ej. puestos 100% call center >>
  - << ej. turnos nocturnos fijos >>
  - << ej. trabajo que exija mudarme con familia >>

TAMPOCO:
  - Empleadores que cobren por contratar, tramitar visa o examen médico
  - Anuncios sin nombre de empresa
  - Agregadores que no lleven al portal oficial del empleador
```

---

## Con qué cuento

```
CV_POR_PERFIL:
  - << perfil >>: << nombre_del_archivo.pdf >>

TENGO_MICROFONO_USABLE:  << sí / no >>
TENGO_CAMARA_USABLE:     << sí / no >>
# Una proporción alta de vacantes remotas internacionales exige grabación de voz
# o video en inglés. Si respondes "no", el asistente te avisará antes de que
# pierdas tiempo llenando el formulario.

DOCUMENTOS_QUE_ME_FALTAN:
  - << ej. certificado de antecedentes vigente >>
```

---

## Cómo quiero recibir el reporte

```
IDIOMA_DEL_REPORTE:    << >>
SOLO_NOVEDADES:        << sí / no >>
# "sí" = no repetir lo que ya sabías. Recomendado: sin esto, dejas de leerlo
# a la tercera semana.

DONDE_GUARDAR:         << ej. carpeta Empleo / repositorio privado >>
ARCHIVO_DE_REGISTRO:   << ej. TRACKER_APLICACIONES.md >>
```
