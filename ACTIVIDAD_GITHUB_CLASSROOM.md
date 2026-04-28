# Plantilla de Propuesta de Tarea: Práctica Temática Pequeña

## 1) Título

**Diseño de Práctica Temática Pequeña para GitHub Classroom**

> Ejemplos de enfoque temático (elige uno o propón uno similar):
> - Mini Toolkit en ARM64
> - Asistente de Estudio en Terminal
> - Reporteador de Información del Sistema
> - Organizador de Archivos
> - Juego de Aprendizaje en Línea de Comandos

---

## 2) Descripción General

En esta actividad, **el estudiante diseñará una propuesta de proyecto pequeño** y documentará su planeación antes de implementar código.

La propuesta debe elegir **un lenguaje principal**:
- ARM64 Assembly
- C
- Python
- Bash

> **Nota importante sobre ARM64 Assembly:** úsalo solo para programas **muy pequeños y puntuales** (por ejemplo: operaciones básicas, manejo simple de entrada/salida o utilerías mínimas de terminal).

### Enfoque de la actividad
La prioridad de esta práctica es:
1. Documentar claramente la idea.
2. Justificar su utilidad.
3. Definir una estructura limpia de repositorio.
4. Presentar un plan básico de pruebas.

El código es secundario en esta etapa; si se incluye, debe ser mínimo y coherente con la propuesta.

---

## 3) Entregables del Estudiante

El repositorio de entrega debe incluir, como mínimo:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`
- opcional: `src/`
- opcional: `scripts/`
- opcional: `tests/`

---

## 4) Estructura Recomendada del Repositorio

Usa esta estructura mínima como guía:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

> `<ext>` depende del lenguaje elegido (`s`, `c`, `py`, `sh`, etc.).

---

## 5) Contenido mínimo por archivo

### `README.md`
Debe incluir:
- Nombre del proyecto.
- Descripción breve (3 a 6 renglones).
- Lenguaje principal elegido y justificación corta.
- Alcance: qué sí hace y qué no hace el proyecto.
- Instrucciones rápidas para ejecutar (si existe prototipo).

### `docs/propuesta.md`
Debe incluir:
1. **Tema y problema** que se quiere atender.
2. **Objetivo general** (1 párrafo).
3. **Objetivos específicos** (3 a 5 puntos).
4. **Lenguaje elegido** y justificación técnica.
5. **Alcance pequeño** (MVP en versión mínima).
6. **Fuera de alcance** (lo que no se implementará).
7. **Riesgos y limitaciones** (tiempo, complejidad, aprendizaje).

### `docs/caso_de_uso.md`
Debe incluir:
- Perfil de usuario (quién lo usaría).
- Escenario principal de uso.
- Entradas esperadas.
- Salidas esperadas.
- Ejemplo de ejecución en terminal (texto simulado permitido).

### `docs/estructura_repositorio.md`
Debe incluir:
- Árbol del repositorio (actual o planeado).
- Propósito de cada carpeta/archivo principal.
- Convenciones de nombres (archivos, scripts, pruebas).

### `docs/plan_de_pruebas.md`
Debe incluir:
- Estrategia de prueba manual mínima.
- Casos de prueba funcionales básicos (al menos 5).
- Casos límite simples (al menos 2).
- Criterios de aceptación.

---

## 6) Reglas de alcance (obligatorias)

Para mantener el proyecto viable con herramientas gratuitas y límites de uso:

- Mantener el proyecto **pequeño y terminal-first**.
- Evitar frameworks grandes y dependencias complejas.
- No usar APIs pagadas.
- No usar bases de datos externas.
- No usar servicios de nube.
- No usar contenedores.
- Evitar integración con múltiples tecnologías al mismo tiempo.

---

## 7) Sugerencias de temas pequeños (referencia)

Elige uno o propón uno equivalente en complejidad:

1. **Organizador básico de archivos** por extensión.
2. **Generador de checklist de estudio** en texto plano.
3. **Reporteador de uso básico del sistema** (CPU/memoria/procesos simples).
4. **Conversor de formatos sencillos** (por ejemplo, minúsculas/mayúsculas, conteo de palabras).
5. **Mini juego de comandos** con preguntas de opción múltiple en terminal.

---

## 8) Rúbrica de evaluación sugerida (100 puntos)

1. **Claridad de la propuesta** (25 pts)
   - Problema bien definido.
   - Objetivos congruentes.

2. **Justificación técnica del lenguaje** (15 pts)
   - Elección coherente con alcance y dificultad.

3. **Diseño de repositorio y documentación** (25 pts)
   - Estructura ordenada.
   - Archivos completos y consistentes.

4. **Caso de uso y plan de pruebas** (20 pts)
   - Escenario realista.
   - Casos de prueba útiles y verificables.

5. **Viabilidad del MVP** (15 pts)
   - Proyecto acotado, alcanzable y medible.

---

## 9) Instrucciones de entrega para GitHub Classroom

1. Acepta la tarea en GitHub Classroom.
2. Completa primero la documentación en `docs/`.
3. Sube commits pequeños y con mensajes claros.
4. (Opcional) agrega prototipo mínimo en `src/` y script de ejecución.
5. Verifica que el repositorio incluya todos los entregables.
6. Entrega el enlace del repositorio según indique el docente.

---

## 10) Checklist final del estudiante

Antes de entregar, confirma:

- [ ] Elegí un lenguaje principal (ARM64 Assembly, C, Python o Bash).
- [ ] Mi propuesta es pequeña y viable.
- [ ] Completé `README.md` y todos los archivos en `docs/`.
- [ ] Incluí un caso de uso claro con entradas/salidas.
- [ ] Incluí plan de pruebas con casos funcionales y límites.
- [ ] Mi estructura de repositorio está documentada y ordenada.
- [ ] (Opcional) Mi prototipo mínimo corre sin dependencias complejas.
