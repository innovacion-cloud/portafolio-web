# Portafolio Web — Alejandro Guerrero (ZogetZ)

Sitio web personal de portafolio para Alejandro Guerrero, Coordinador de Innovación radicado en Japón.

## Descripción

Landing page de una sola página (SPA estática) que presenta el trabajo y perfil profesional del Coordinador de Innovación. Construida únicamente con HTML5 y CSS3 vanilla, sin dependencias ni frameworks externos.

## Secciones

| # | Sección | Contenido |
|---|---------|-----------|
| — | Hero | Nombre, tagline y llamadas a la acción |
| 01 | Sobre mí | Biografía, foto de perfil y áreas de especialización |
| 02 | Proyectos | Tres tarjetas de trabajo seleccionado |
| 03 | Contacto | Datos de contacto + formulario HTML nativo |

## Proyectos destacados

- **Nómada Coffee Co.** — Estrategia de innovación y posicionamiento para tostadora de especialidad
- **Revista Umbral** — Coordinación de proyecto editorial y dirección creativa para revista cultural bimestral
- **Raíz Skincare** — Desarrollo de concepto e innovación de producto para línea de cosméticos naturales

## Tecnologías

- HTML5 semántico
- CSS3 (Flexbox, Custom Properties, Media Queries, `clamp()`)
- Google Fonts: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) + [Inter](https://fonts.google.com/specimen/Inter)

## Características técnicas

- Diseño responsive (desktop → tablet → móvil)
- Navegación fija con `backdrop-filter: blur`
- Scroll suave nativo (`scroll-behavior: smooth`)
- Sin JavaScript — todo el comportamiento visual es CSS puro
- Paleta de color oscura con acento rojo `#E63946`

## Estructura de archivos

```
portafolio-web/
├── index.html    # Toda la estructura, estilos y contenido
└── README.md     # Este archivo
```

## Mejoras pendientes

1. **Menú hamburguesa en móvil** — los links del nav se ocultan en pantallas < 620px; implementar toggle con JS o con el truco CSS de `checkbox + label`
2. **Imágenes reales** — reemplazar los `<div>` placeholder por `<img>` con archivos WebP optimizados y `loading="lazy"`
3. **Formulario funcional** — conectar el `<form>` a un servicio externo como [Formspree](https://formspree.io) o Netlify Forms

## Contacto

- **Email:** hola@alejandroguerrero.mx
- **Ubicación:** Japón
- **Redes:** Behance · Instagram · LinkedIn
