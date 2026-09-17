# CompanyGame en la CUC — Mapeo curricular

Presentación que **Simuladores de Negocios Colombia** lleva a los directores de programa y
decanos de la **Facultad de Ciencias Empresariales** de la **Corporación Universitaria de la
Costa (CUC)**.

No presenta un simulador: muestra, pregrado por pregrado, **qué asignaturas del plan de
estudios pueden trabajarse hoy con un simulador CompanyGame**, con cuál y en qué semestre.

**Cifras de portada**: 31 asignaturas con simulador, 18 de aplicación directa, 15 simuladores
del catálogo, 5 pregrados (Administración de Empresas, Administración de Servicios de Salud,
Contaduría Pública, Mercadeo y Publicidad, Negocios Internacionales).

El detalle completo del análisis —incluidas las cifras que el deck no muestra— está en
`CLAUDE.md`.

## Estructura

```
cuc-mapeo-presentacion/
├── index.html            la presentación entera (HTML + CSS + JS, sin dependencias)
├── CLAUDE.md             documento de trabajo: cifras completas, salvedades, criterio editorial
├── mapeo-cuc.xlsx         Excel fuente del mapeo curricular
├── build-artifact.js     genera la versión publicable como Artifact de Claude
└── assets/
    ├── logo-sdn.png          logo blanco (portada y cierre)
    ├── logo-sdn-color.png    logo a color (referencia de marca)
    ├── cartelera.jpg         portafolio CompanyGame
    └── avatares.png          avatares de IA
```

## Contenido — 12 slides (≈ 23–25 minutos)

1. Portada y contexto
2. Cartelera de simuladores CompanyGame · **fijo**
3. Lo que ya se puede hacer hoy
4. Alcance por programa
5–9. **Ficha por programa** — una por pregrado (Adm. de Empresas, Mercadeo y Publicidad, Adm.
   de Servicios de Salud, Negocios Internacionales, Contaduría Pública)
10. Los tres modelos de uso docente (A / B / C) · **fijo**
11. Evidencia de aprendizaje y acreditación
12. Cierre y contacto · **fijo**

No hay slide de asignaturas transversales: ninguna asignatura con encaje perfecto se repite en
los 5 programas a la vez (detalle en `CLAUDE.md`).

Las **fichas por programa** son el eje de la reunión: cada una lista, con semestre y
simulador, las asignaturas del pregrado que entran de forma directa y las que entran como
apoyo al curso. Ocupan unos 10 de los ~24 minutos y sirven además como material para enviar
después.

## Cómo verla

Abre `index.html` en cualquier navegador. Navegación con flechas en pantalla, teclado
(← →, espacio) y swipe en móvil. Las capturas se amplían al hacer clic.

## Identidad visual

Paleta tomada por muestreo del logo de Simuladores de Negocios Colombia: cyan `#16AAE2`,
azul `#0E73B8` y los grises `#737170` / `#989998` / `#CECBCB`. **Es la identidad del
distribuidor y no cambia según la universidad.** El detalle está en `CLAUDE.md`.

## Tecnología

HTML5 + CSS3 + JavaScript vanilla, todo embebido en `index.html`. Sin frameworks.

---

Derivada del deck de la Universidad Santiago de Cali (agosto 2026), que sigue siendo el
ejemplo completo de referencia.

Simuladores de Negocios Colombia S.A.S. · Distribuidor autorizado CompanyGame
