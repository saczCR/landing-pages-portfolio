# Landing Page — IA Heroes (Evento de IA Aplicada)

Página web de promoción para un evento en vivo sobre Inteligencia Artificial aplicada, con una sección adicional para un programa de formación más extenso (PRO X).

## Demo

Abre index.html en tu navegador, o publícalo con GitHub Pages (ver sección abajo).

## Tecnologías

- HTML5 semántico (incluye details/summary nativos para el FAQ)
- CSS3: variables (custom properties), Grid, Flexbox, animaciones con @keyframes, diseño responsive
- SVG inline: fondo decorativo de "circuito" dibujado directamente en SVG

## Características principales

- Ticker animado (banda de texto en movimiento continuo) construido solo con CSS (@keyframes + translateX).
- FAQ nativo usando las etiquetas semánticas details y summary de HTML5, sin necesidad de JavaScript.
- Timeline de 4 días en formato de tarjetas, con grid responsive (4 → 2 → 1 columnas según el ancho de pantalla).
- Fondo decorativo en SVG con patrón de cuadrícula y líneas tipo circuito.
- Accesibilidad: focus-visible personalizado y soporte para prefers-reduced-motion.

## Estructura

```
landing-ia-heroes/
├── index.html   # Página completa (HTML + CSS en un solo archivo)
└── README.md
```

## Cómo verlo en vivo (GitHub Pages)

1. Sube este repositorio a tu cuenta de GitHub.
2. Ve a Settings → Pages.
3. En "Branch", selecciona main y carpeta /root, guarda.
4. En un par de minutos, GitHub te da un link público (https://tuusuario.github.io/landing-ia-heroes/).
