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
| [docs/notas-presentacion.tex](docs/notas-presentacion.tex) | Notas de la presentación, tabla I1–I16 y respuestas F1–F3 en LaTeX |
| [docs/notas-presentacion.pdf](docs/notas-presentacion.pdf) | Documento unificado compilado |
| [docs/referencias.bib](docs/referencias.bib) | Bibliografía en formato BibLaTeX |

## Cómo abrir el diagrama

Abrir `Diagrama AeroAndes_comunicacion MPZ.drawio` en https://app.diagrams.net o en draw.io Desktop (File → Open).

Para exportarlo de nuevo: File → Export as → PNG (Zoom 313 %, que equivale a unos 300 DPI) o File → Export as → PDF.

## Cómo compilar las notas

Usa pdfLaTeX y Biber para generar las referencias en formato IEEE. Desde la raíz del repositorio, ejecuta:

```bash
cd docs
pdflatex -halt-on-error notas-presentacion.tex
biber notas-presentacion
pdflatex -halt-on-error notas-presentacion.tex
pdflatex -halt-on-error notas-presentacion.tex
```

Se requiere TeX Live o MiKTeX con Biber, `babel` en español, `geometry`, `array`, `booktabs`, `longtable`, `csquotes`, `enumitem`, `biblatex`, `biblatex-ieee`, `xurl` e `hyperref`.

En Overleaf, sube `notas-presentacion.tex` y `referencias.bib` juntos y selecciona pdfLaTeX.
