# CUC — Mapeo curricular · documento de trabajo

> Esta carpeta **ya no es la plantilla**: es la presentación real para la Corporación
> Universitaria de la Costa (CUC). Este archivo es el documento de trabajo de esa reunión, no
> el deck. La plantilla vive en `C:\Users\simsy\Downloads\plantilla-mapeo-curricular\`.

## Institución

- **Universidad**: Corporación Universitaria de la Costa (CUC)
- **Facultad**: Facultad de Ciencias Empresariales — nombre confirmado por Paula (el Excel no
  lo traía; los 5 programas del mapeo no comparten una única facultad "oficial" evidente en el
  archivo, así que si en la reunión se cuestiona el nombre, verificar con la CUC).
- **Programas mapeados (5)**: Administración de Empresas, Administración de Servicios de Salud,
  Contaduría Pública, Mercadeo y Publicidad, Negocios Internacionales — todos presenciales,
  Barranquilla, sin variante virtual.

## Fuente de verdad

- **Excel**: `C:\Users\simsy\Downloads\Corporación Universitaria de la Costa - CUC.xlsx`
  (copiado también a `mapeo-cuc.xlsx` en esta carpeta). Fecha de revisión/modificación:
  **17-sep-2026**.
- Hojas: `Resumen`, `Catálogo CompanyGame`, y una hoja por programa con columnas Semestre /
  Materia / Área temática / Simulador CompanyGame / Nivel CG / Grado de ajuste / Tipo de
  simulador a desarrollar / Observación.
- **Verificación**: recontamos las cifras desde las 5 hojas de programa (no solo desde
  `Resumen`, que en mapeos anteriores tenía errores). En este Excel **la hoja Resumen es
  consistente con el recuento por programa** — no se encontraron `#REF!` ni discrepancias.

## Cifras completas (incluidas las que el deck omite)

| Programa | Materias totales | Encaje perfecto | Encaje parcial | Encaje (perfecto+parcial) | No encaja | % con simulador | Simuladores distintos | Semestres con encaje |
|---|---|---|---|---|---|---|---|---|
| Administración de Empresas | 46 | 6 | 3 | 9 | 37 | 19,6 % | 9 | 1–8 |
| Adm. de Servicios de Salud | 46 | 3 | 2 | 5 | 41 | 10,9 % | 5 | 1–5 |
| Contaduría Pública | 48 | 2 | 2 | 4 | 44 | 8,3 % | 4 | 2–5 |
| Mercadeo y Publicidad | 46 | 4 | 4 | 8 | 38 | 17,4 % | 8 | 1–6 |
| Negocios Internacionales | 47 | 3 | 2 | 5 | 42 | 10,6 % | 5 | 1–7 |
| **TOTAL** | **233** | **18** | **13** | **31** | **202** | **13,3 %** | **15** (distintos en todo el mapeo) | 1–8 |

**Si preguntan por la cobertura o por el denominador en la reunión**, la respuesta honesta es:
31 de 233 asignaturas (13,3 %). El deck nunca muestra ni el total (233) ni el porcentaje —
solo dice «31 asignaturas con simulador» — por criterio editorial (ver `CLAUDE.md` de la
plantilla).

**Asignaturas sin encaje (202) — por qué, según las notas metodológicas del Excel:**
- El catálogo CompanyGame no tiene categoría de RR. HH., gestión pública/estatal, ni sector
  salud: todas las materias de talento humano, liderazgo, gestión pública y las asignaturas
  clínico-administrativas propias de Adm. de Servicios de Salud (sistemas de salud, salud
  pública, terminología médica, servicios asistenciales, SST, contratación en salud) se marcan
  "No encaja".
- Mercadeo y Publicidad y Negocios Internacionales son los programas de menor encaje directo:
  el primero por su componente de diseño/creatividad publicitaria (identidad de marca,
  escritura creativa, fotografía publicitaria), sin producto equivalente en el catálogo; el
  segundo por su alto contenido de comercio exterior, logística aduanera y geopolítica.
- Contaduría Pública y Administración de Empresas son los que mejor aprovechan la línea de
  Finanzas y Banca (ContaTrainer, Corbatul) y Negocios y Estrategia (T-Shirt, Business21,
  Business Global), respectivamente.

## Simuladores usados en el mapeo (15)

Advisor Jr., Business Global, Business21, Coffee Time, ContaTrainer, Corbatul, ESG Management,
ESG Project, FOCUS, Fitness Gym, Food Company, GlobalMarket, Inter Pyme, SalesManager, T-Shirt.

## Salvedades

- El Excel no trae grado de ajuste "sin definir": todas las 233 filas tienen un valor cerrado
  (perfecto / parcial / no encaja), sin casos ambiguos.
- No hubo que normalizar nombres de simulador contra el catálogo: los nombres de la hoja de
  cada programa coinciden literalmente con los del catálogo (`Catálogo CompanyGame`).
- **Los badges de nivel en las fichas siguen el nivel real de cada asignatura** (columna
  "Nivel CG" del Excel), no un color fijo por tipo de encaje: badge-green N1-2 · badge-teal
  N3-4 · badge-orange N5 · badge-purple N6-7. Ninguna asignatura del mapeo CUC quedó en N4-5,
  así que `badge-amber` no se usa en las fichas.

## Qué se eliminó respecto a la plantilla, y por qué

- **Se borró el slide de asignaturas transversales** (`slideTransversales`) y el acordeón del
  hallazgo en el slide 3. Ninguna asignatura con **encaje perfecto** se repite en los **5**
  programas a la vez (la candidata más cercana, Mercadeo y Creación de Valor / Coffee Time,
  aparece perfecta en 4 de 5 — falta en Contaduría Pública, que no tiene ninguna materia de
  mercadeo). El criterio de la plantilla es no forzarlo si no se cumple en los 5, así que el
  deck queda en **12 slides** en vez de 13.
- **El slide de Evidencia de aprendizaje se amplió**, no solo se recortó: la plantilla solo
  traía filas para 9 de los 15 simuladores usados en este mapeo. Se añadieron filas para
  Business21, Business Global, ESG Project, Food Company e Inter Pyme (redactadas a partir de
  su descripción en la hoja `Catálogo CompanyGame`, con el mismo estilo de las demás filas) para
  que la tabla cubra los 15 simuladores que sí aparecen en el mapeo de la CUC.
- El orden de la tabla de alcance (slide 4) y de las 5 fichas por programa es el mismo:
  Administración de Empresas, Mercadeo y Publicidad, Adm. de Servicios de Salud, Negocios
  Internacionales, Contaduría Pública — de más a menos asignaturas con encaje. Adm. de
  Servicios de Salud y Negocios Internacionales empatan en 5; se puso primero Adm. de Servicios
  de Salud sin que eso implique una jerarquía real entre ambos.

## ⚠️ Si este repositorio va a ser público

Este archivo expone la cobertura real (13,3 %) y el detalle de asignaturas sin encaje por
programa — información que el deck comercial nunca muestra. **No lo subas a un repositorio
público** sin revisar antes con el equipo si ese detalle puede salir de la casa.

## Contacto de la reunión

Sin datos de fecha/hora de la reunión ni de la persona de contacto en la CUC todavía —
completar aquí cuando se agende.
