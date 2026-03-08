# TopVentas Amazon.es — Guía de compras

Sitio web estático de afiliación con **los productos más vendidos en Amazon España**, optimizado para SEO y publicado con **GitHub Pages**.

## 🌐 Ver el sitio en vivo

👉 **https://skirep.github.io/saveweb/**

## 📋 Descripción

Esta web presenta los **10 gadgets y electrodomésticos más vendidos en Amazon España** en 2024, organizados por categoría:

- 🍳 **Cocina Inteligente** — Freidoras de aire, ollas multicocina
- 🏠 **Hogar Inteligente** — Altavoces Alexa, robots aspiradores, videoporteros
- 📱 **Tecnología** — Streaming sticks, lectores Kindle, tablets
- 🦷 **Salud y Bienestar** — Cepillos eléctricos inteligentes

### Características principales
- ✅ **SEO optimizado**: meta tags, Open Graph, Schema.org (WebPage + ItemList + Product)
- ✅ **Diseño responsive** para móvil, tablet y escritorio
- ✅ **Accesibilidad**: ARIA labels, skip links, focus visible
- ✅ **Rendimiento**: lazy loading de imágenes, CSS puro sin dependencias
- ✅ **Links de afiliado Amazon** con tag de asociado
- ✅ **FAQ estructurado** con `<details>` / `<summary>` (schema.org compatible)
- ✅ **sitemap.xml** y **robots.txt** para indexación

## 🔧 Configuración de GitHub Pages

1. Ve a **Settings → Pages** en el repositorio
2. Selecciona **Branch: main**, carpeta **/ (root)**
3. Guarda. El sitio estará disponible en unos minutos en `https://skirep.github.io/saveweb/`

## 🏷️ Código de afiliado Amazon

Todos los enlaces usan el tag `saveweb-21`. Para usar tu propio código de afiliado:

1. Regístrate en [Amazon Associates España](https://afiliados.amazon.es/)
2. Sustituye todas las ocurrencias de `saveweb-21` en `index.html` por tu tag personal

## 📁 Estructura del proyecto

```
saveweb/
├── index.html      # Página principal con todos los productos
├── css/
│   └── style.css   # Estilos responsive con diseño Amazon
├── robots.txt      # Directivas para motores de búsqueda
├── sitemap.xml     # Mapa del sitio para SEO
├── .nojekyll       # Deshabilita Jekyll para GitHub Pages
└── README.md       # Este archivo
```

## ⚖️ Aviso legal

Como Asociado de Amazon, obtenemos ingresos por las compras adscritas que cumplen los requisitos aplicables. Los precios son orientativos y pueden variar.
