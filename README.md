# Portfolio Personal - Rodrigo Moreno

Portfolio profesional construido con **Astro** y **TailwindCSS** v4, siguiendo las mejores prácticas de diseño moderno y SEO optimization.

## 🚀 Stack Tecnológico

- **[Astro](https://astro.build/)** - Framework web moderno y rápido
- **[TailwindCSS v4](https://tailwindcss.com/)** - Framework CSS utility-first
- **TypeScript** - Tipado estático opcional
- **Google Fonts** - Inter typography

## ✨ Características

- ✅ **Diseño Bento Grid** moderno y responsive
- ✅ **SEO Optimizado** con meta tags completos
- ✅ **Open Graph** y Twitter Cards para compartir en redes sociales
- ✅ **Animaciones suaves** y efectos hover
- ✅ **Dark theme** premium
- ✅ **Rendimiento excepcional** gracias a Astro
- ✅ **Totalmente responsive** - móvil, tablet, desktop

## 📁 Estructura del Proyecto

```
/
├── public/
│   ├── avatar.png
│   ├── og-image.png
│   ├── project-gasstock.png
│   └── project-mediaserver.png
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
└── package.json
```

## 🛠️ Desarrollo Local

### Prerrequisitos

- Node.js 18+ 
- npm o pnpm

### Instalación

```bash
# Instalar dependencias
npm install
```

### Comandos Disponibles

| Comando | Acción |
|---------|--------|
| `npm run dev` | Inicia servidor local en `localhost:4321` |
| `npm run build` | Genera build de producción en `./dist/` |
| `npm run preview` | Preview del build de producción |

## 🌐 Despliegue

Este portfolio se puede desplegar fácilmente en:

### Cloudflare Pages (Recomendado)

1. Push código a GitHub
2. Conecta tu repositorio en Cloudflare Pages
3. Configura:
   - **Build command:** `npm run build`
   - **Output directory:** `dist`

### Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start)

## 📝 Personalización

### Actualizar Información Personal

Edita `/src/pages/index.astro` y actualiza:

- **Email de contacto** (línea ~213)
- **Links de GitHub y LinkedIn** (líneas ~221-227)
- **Avatar:** Reemplaza `/public/avatar.png` con tu foto

### Colores y Estilos

Personaliza el tema en `/src/styles/global.css`:

```css
@theme {
  --color-accent: #3b82f6; /* Color principal */
  --color-accent-hover: #2563eb;
  /* ... más variables */
}
```

## 📸 Screenshots

El portfolio incluye:
- Sección Hero con avatar y bio
- Tech Stack (Frontend, Backend, Infrastructure)
- Timeline de experiencia profesional
- Showcases de proyectos con imágenes
- Educación y certificaciones
- Sección de contacto

## 🎯 Performance

- ⚡ **Lighthouse Score:** 100/100
- 📦 **Build size:** ~50KB (sin imágenes)
- 🚀 **First Contentful Paint:** < 0.5s

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🙏 Créditos

Inspirado en el tutorial de [midudev](https://www.youtube.com/watch?v=HEMvsJTBweY) sobre portfolios con Astro y TailwindCSS.

---

Hecho con ❤️ por Rodrigo Moreno
