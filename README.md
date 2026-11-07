# Examen final piloto – Informática aplicada a los negocios

**Instituto Alfa · Tecnicaturas en Higiene y Seguridad, Comercio Exterior, Marketing Digital, Seguros y Administración de Empresas**
**Duración: 80 minutos · Modalidad: presencial, en laboratorio**

---

## 1. Qué tenés que lograr

Construir, dentro de este repositorio, el **módulo de tu tecnicatura** del caso *Yerbatera Tres Fronteras*: una investigación, una planilla, un informe, una presentación y el registro de cómo usaste la IA.

**Se evalúa únicamente lo que quede en tu repositorio al terminar los 80 minutos.** Si algo no está en el repo (o el enlace no abre), no se evalúa.

## 2. Antes de empezar (1 minuto de lectura)

1. Leé el caso: [`caso/enunciado.md`](caso/enunciado.md)
2. Los datos del caso están en [`caso/datos_base.md`](caso/datos_base.md). Usalos tal cual.
3. Abrí **solo la consigna de tu tecnicatura** en la carpeta [`consignas/`](consignas/).

**Herramientas permitidas:** GitHub, Perplexity, NotebookLM (Gemini), Claude, Google Sheets, Google Docs, Gamma, Word y Excel.

**Reglas:**
- Todo dato que no venga de `datos_base.md` debe tener fuente citada (con enlace).
- Podés usar IA en cualquier etapa, pero tenés que **registrar tus prompts** en `05-ia/prompts.md` y explicar qué corregiste vos.
- Todos los enlaces (Google Sheets, Google Docs, Gamma) deben estar en modo **"cualquier persona con el enlace puede ver"**. Probalos en una pestaña de incógnito.

## 3. Cronograma sugerido

| Etapa | Minutos | Acumulado | Herramienta | Entregable en el repo |
|---|---|---|---|---|
| 0. Preparación | 5 | 0–5 | GitHub | `00-estudiante.md` completo |
| 1. Investigación | 15 | 5–20 | Perplexity | `01-investigacion/fuentes.md` |
| 2. Síntesis | 8 | 20–28 | NotebookLM | `01-investigacion/sintesis.md` |
| 3. Planilla | 17 | 28–45 | Google Sheets / Excel | `02-datos/planilla.xlsx` + `enlace-planilla.md` |
| 4. Informe | 15 | 45–60 | Google Docs / Word | `03-informe/informe.pdf` + `enlace-informe.md` |
| 5. Presentación | 12 | 60–72 | Gamma | `04-presentacion/enlace-gamma.md` |
| 6. Revisión con IA | 5 | 72–77 | Claude | `05-ia/prompts.md` completo |
| 7. Cierre | 3 | 77–80 | GitHub | README verificado y entrega |

## 4. Paso a paso

### Etapa 0 · Preparación (0–5 min)
1. Hacé clic en **Use this template → Create a new repository**. Nombre: `examen-informatica-APELLIDO`. Visibilidad: **Public**.
2. Completá `00-estudiante.md` (nombre, tecnicatura, cohorte).
3. **Commit 1:** `etapa 0: datos del estudiante`

### Etapa 1 · Investigación con Perplexity (5–20 min)
1. Con la consigna de tu tecnicatura, hacé al menos **3 búsquedas** distintas en Perplexity.
2. Por cada búsqueda, anotá en `01-investigacion/fuentes.md`: la pregunta, el dato obtenido y el enlace de la fuente.
3. **Commit 2:** `etapa 1: fuentes de investigación`

### Etapa 2 · Síntesis con NotebookLM (20–28 min)
1. Cargá en NotebookLM los enlaces de tus fuentes.
2. Pedí una síntesis orientada a la pregunta de tu módulo y copiá el resultado a `01-investigacion/sintesis.md`.
3. Marcá con **[VERIFICADO]** lo que contrastaste con la fuente original y **[REVISAR]** lo que no pudiste verificar.
4. **Commit 3:** `etapa 2: síntesis`

### Etapa 3 · Planilla (28–45 min)
1. Armá la planilla que pide tu consigna en Google Sheets, con **fórmulas** (no valores escritos a mano) y **al menos un gráfico**.
2. Descargala como `.xlsx` y subila a `02-datos/` con el nombre `planilla.xlsx` (**Add file → Upload files**).
3. Pegá el enlace de la hoja de Google en `02-datos/enlace-planilla.md`.
4. **Commit 4:** `etapa 3: planilla del módulo`

### Etapa 4 · Informe (45–60 min)
1. Redactá el informe en Google Docs (1 a 2 páginas) siguiendo la estructura de `03-informe/enlace-informe.md`.
2. Insertá al menos **1 tabla y 1 gráfico** traídos de tu planilla.
3. Descargalo como PDF, subilo como `03-informe/informe.pdf` y pegá el enlace del Doc en `enlace-informe.md`.
4. **Commit 5:** `etapa 4: informe`

### Etapa 5 · Presentación en Gamma (60–72 min)
1. Generá la presentación a partir del texto de tu informe (6 láminas, estructura en `04-presentacion/enlace-gamma.md`).
2. Pegá el enlace público en `04-presentacion/enlace-gamma.md`.
3. **Commit 6:** `etapa 5: presentación`

### Etapa 6 · Revisión con Claude (72–77 min)
1. Pedile a Claude que revise tu informe: coherencia, errores y claridad.
2. Completá `05-ia/prompts.md` con **todos** los prompts que usaste durante el examen y qué decidiste aceptar o corregir.
3. **Commit 7:** `etapa 6: registro de uso de IA`

### Etapa 7 · Cierre (77–80 min)
1. Abrí cada enlace en incógnito y confirmá que funciona.
2. Verificá la lista de la sección 6.
3. **Commit final:** `entrega final` y entregá al docente la URL de tu repositorio, como se indique en el aula.

## 5. Estructura final esperada del repositorio

```
examen-informatica-APELLIDO/
├── README.md
├── 00-estudiante.md
├── caso/
│   ├── enunciado.md
│   └── datos_base.md
├── consignas/                (no se modifica)
├── 01-investigacion/
│   ├── fuentes.md
│   └── sintesis.md
├── 02-datos/
│   ├── planilla.xlsx
│   └── enlace-planilla.md
├── 03-informe/
│   ├── informe.pdf
│   └── enlace-informe.md
├── 04-presentacion/
│   └── enlace-gamma.md
└── 05-ia/
    └── prompts.md
```

## 6. Lista de verificación antes de entregar

- [ ] `00-estudiante.md` completo
- [ ] Mínimo 3 fuentes con enlace en `fuentes.md`
- [ ] `sintesis.md` con marcas [VERIFICADO] / [REVISAR]
- [ ] `planilla.xlsx` subida, con fórmulas y 1 gráfico
- [ ] `informe.pdf` subido, con 1 tabla y 1 gráfico
- [ ] Los 3 enlaces (Sheets, Docs, Gamma) abren en incógnito
- [ ] `prompts.md` con todos los prompts usados
- [ ] Mínimo **6 commits** hechos durante el examen, con mensajes descriptivos
- [ ] URL del repositorio entregada al docente

## 7. Cómo se evalúa

| Criterio | Puntos |
|---|---|
| Integración entre herramientas (la salida de una es insumo de la siguiente) | 25 |
| Uso de GitHub (estructura, commits, README) | 20 |
| Calidad del módulo (análisis y coherencia con tu carrera) | 20 |
| Planilla (fórmulas, orden, gráfico) | 15 |
| Informe y presentación (formato, claridad, fuentes) | 10 |
| Uso crítico de la IA (prompts registrados, verificación) | 10 |
| **Total** | **100** |
