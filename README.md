# TripleTend Homeland Web Project

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![BEM](https://img.shields.io/badge/BEM-000?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyBmaWxsPSIjZmZmIiBoZWlnaHQ9IjE2IiB2aWV3Qm94PSIwIDAgMjQgMTYiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cmVjdCBmaWxsPSIjMDAwIiBoZWlnaHQ9IjE2IiB3aWR0aD0iMjQiIHJ4PSI0Ii8+PHBhdGggZD0iTTUgM2g0djEwSDV6bTggMGg0djEwSDl6Ii8+PC9zdmc+)

Proyecto profesional y responsivo, construido con HTML y CSS puro, siguiendo la metodología BEM Flat y replicando un diseño Figma con máxima fidelidad visual.

## 🚀 Características principales

- **Pixel-perfect:** Réplica exacta del diseño Figma, incluyendo tipografías, espaciados, imágenes y alineaciones.
- **Responsive:** Adaptado para desktop (1280px), tablet (768px) y móvil (320px), sin scroll horizontal.
- **BEM Flat:** Estructura de archivos y clases siguiendo BEM Flat, con bloques en `/blocks` y media queries separadas.
- **Tipografía Inter:** Usando Google Fonts y fallback local.
- **Imágenes centralizadas:** Todas en `/images`.
- **Código limpio:** Sin frameworks, sin estilos duplicados, sin !important.

## 📁 Estructura del proyecto

```
web_project_homeland/
├── blocks/                # Bloques BEM y media queries
├── images/                # Imágenes del proyecto
├── pages/
│   └── index.css          # Importa normalize, fuentes y bloques
├── vendor/
│   ├── fonts.css
│   ├── fonts/
│   └── normalize.css
├── favicon.ico
├── index.html
├── .editorconfig
├── .prettierignore
├── .gitignore
└── README.md
```

## 🖥️ Visualización y despliegue

1. Clona el repositorio: `git clone ...`
2. Abre `index.html` en tu navegador.
3. Visualiza la web en diferentes tamaños de pantalla (1280px, 768px, 320px).
4. [Opcional] Sube el proyecto a GitHub Pages para compartirlo online.

## ⚙️ Especificaciones técnicas

- **Breakpoints:**
  - Desktop: 1280px
  - Tablet: 768px
  - Mobile: 320px
- **Metodología:** BEM Flat, sin anidamiento excesivo, sin frameworks.
- **Accesibilidad:** Imágenes con `alt`, estructura semántica (`header`, `main`, `footer`, `section`).
- **Validación:** Sin errores W3C, sin scroll horizontal, sin !important.
- **Fidelidad visual:** Márgenes, paddings y fuentes según Figma.

## 📚 Tecnologías y técnicas

- HTML5, CSS3
- BEM Flat
- Media queries para responsividad
- Normalize.css
- Google Fonts (Inter)

## 🌐 Enlace a GitHub Pages

> [\[Pon aquí tu enlace de despliegue si lo tienes\]](https://sierra117sp.github.io/web_project_homeland)

---

### ¿Cómo modificar el diseño?

Edita los archivos en `/blocks` para cambiar estilos de bloques, o agrega nuevos siguiendo la convención BEM. Los breakpoints y media queries están en archivos separados para fácil mantenimiento.

---

Desarrollado por Jose Emmanuel Alvarado · 2025
