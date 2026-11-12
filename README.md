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

## Entrega final

Los dos PDF para el LMS están en [entrega-final](entrega-final).

- [Diagrama de comunicación](entrega-final/MPZ_AeroAndes_GA-TL-01_Diagrama.pdf)
- [Documento técnico con tabla I1–I16 y respuestas F1–F3](entrega-final/MPZ_AeroAndes_GA-TL-01_Documento.pdf)

## Archivos fuente

| Archivo | Descripción |
|---|---|
| [entrega-final/aeroandes-mpz.drawio](entrega-final/aeroandes-mpz.drawio) | Diagrama editable de comunicación entre procesos |
| [diagrama/vista-anterior.png](diagrama/vista-anterior.png) | Vista previa anterior del diagrama |
| [entrega-final/MPZ_AeroAndes_GA-TL-01_Documento.tex](entrega-final/MPZ_AeroAndes_GA-TL-01_Documento.tex) | Diseño de comunicación, tabla I1–I16 y respuestas F1–F3 en LaTeX |
| [entrega-final/referencias.bib](entrega-final/referencias.bib) | Bibliografía en formato BibLaTeX |
| [docs/Detalles..pdf](docs/Detalles..pdf) | Rúbrica y enunciado del escenario |

## Cómo abrir el diagrama

Abre `entrega-final/aeroandes-mpz.drawio` en diagrams.net o en draw.io Desktop (File → Open).

Para exportarlo de nuevo, selecciona File → Export as → PDF.

## Cómo compilar las notas

Usa pdfLaTeX y Biber para generar las referencias en formato IEEE. Desde la raíz del repositorio, ejecuta:

```bash
cd entrega-final
pdflatex -halt-on-error MPZ_AeroAndes_GA-TL-01_Documento.tex
biber MPZ_AeroAndes_GA-TL-01_Documento
pdflatex -halt-on-error MPZ_AeroAndes_GA-TL-01_Documento.tex
pdflatex -halt-on-error MPZ_AeroAndes_GA-TL-01_Documento.tex
```

Se requiere TeX Live o MiKTeX con Biber, `babel` en español, `geometry`, `array`, `booktabs`, `longtable`, `csquotes`, `enumitem`, `biblatex`, `biblatex-ieee`, `xurl` e `hyperref`.

En Overleaf, sube `MPZ_AeroAndes_GA-TL-01_Documento.tex` y `referencias.bib` juntos y selecciona pdfLaTeX.
