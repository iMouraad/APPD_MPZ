  # FORM-TL-01: Taller de modelado de comunicación entre procesos distribuidos

Universidad Técnica Estatal de Quevedo (UTEQ) · Carrera de Software

Aplicaciones Distribuidas · 7mo nivel · Paralelo B

Docente: Ing. Gleiston Cicerón Guerrero Ulloa

Equipo MPZ:

- Muñoz Vera Melanie Michelle
- Pozo Castillo Steven Fernando
- Zambrano Yong Angel Daniel

Escenario asignado: Escenario 1, sistema de reservas de vuelos AeroAndes Reservas

Semana 2 · Entrega: 11/11/2026

## Archivos de esta carpeta

| Archivo | Descripción |
|---|---|
| `Diagrama AeroAndes_comunicacion MPZ.drawio` | Diagrama editable de comunicación entre procesos (draw.io) |
| `Diagrama AeroAndes_comunicacion MPZ.pdf` | Exportación del diagrama en PDF |
| `Diagrama AeroAndes_comunicacion MPZ.png` | Exportación del diagrama en PNG a 300 DPI |
| `notas/notas.tex` | Notas de la presentación en LaTeX, con las preguntas recibidas y las respuestas |
| `notas/notas.pdf` | Notas compiladas |

## Cómo abrir el diagrama

Abrir `Diagrama AeroAndes_comunicacion MPZ.drawio` en https://app.diagrams.net o en draw.io Desktop (File → Open).

Para exportarlo de nuevo: File → Export as → PNG (Zoom 313 %, que equivale a unos 300 DPI) o File → Export as → PDF.

## Cómo compilar las notas

Compilador: `pdflatex`.

Archivo principal: `notas/notas.tex`

Desde la carpeta `notas`:

```bash
pdflatex notas.tex
pdflatex notas.tex
```

O en un solo paso:

```bash
latexmk -pdf notas.tex
```

Dependencias: TeX Live 2022 o superior (o MiKTeX en Windows) con los paquetes `babel` (`spanish`), `geometry`, `booktabs`, `longtable`, `xcolor`, `enumitem`, `hyperref` y `lmodern`.

En Overleaf: subir `notas.tex` y elegir Compiler: pdfLaTeX en Menu → Settings.
