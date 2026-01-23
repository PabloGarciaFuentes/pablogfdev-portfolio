# 🚀 PablogfDev - Portfolio - Fullstack Developer

Portfolio profesional desarrollado con Astro y Tailwind CSS 4, con un diseño futurista inspirado en el espacio y el mar.

![Astro](https://img.shields.io/badge/Astro-5.16-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-4.1-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

## ✨ Características

- 🎨 **Diseño Moderno** - Interfaz futurista con efectos glassmorphism y animaciones suaves
- 📱 **Responsive Design** - Mobile-first, optimizado para todos los dispositivos
- ⚡ **Alto Rendimiento** - Construido con Astro para máxima velocidad
- 🎭 **Tema Oscuro** - Diseño preparado para modo claro/oscuro
- 🌐 **Preparado para i18n** - Estructura lista para internacionalización ES/EN
- ♿ **Accesible** - Siguiendo las mejores prácticas de accesibilidad web
- 🎯 **SEO Optimizado** - Meta tags y estructura semántica

## 📂 Estructura del Proyecto

```
├── public/
│   └── images/          # Imágenes estáticas
│       ├── about/       # Foto de perfil
│       └── projects/    # Screenshots de proyectos
├── src/
│   ├── components/      # Componentes reutilizables
│   │   ├── Navigation.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Experience.astro
│   │   ├── TechStack.astro
│   │   ├── Projects.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro  # Layout principal
│   ├── pages/
│   │   └── index.astro   # Página principal
│   └── styles/
│       └── global.css    # Estilos globales + tema
├── STYLES_GUIDE.md       # Guía de estilos y colores
└── package.json
```

## 🎨 Secciones

- **Hero** - Presentación principal con animaciones
- **About Me** - Información personal y años de experiencia
- **Experience** - Timeline de experiencia profesional
- **Tech Stack** - Tecnologías y herramientas
- **Projects** - Proyectos destacados con imágenes
- **Contact** - Formulario de contacto

## 🛠️ Tecnologías

- **[Astro](https://astro.build/)** - Framework web moderno
- **[Tailwind CSS 4](https://tailwindcss.com/)** - Framework CSS utility-first
- **TypeScript** - Tipado estático
- **Space Grotesk** - Tipografía principal
- **Material Symbols** - Iconos

## 🚀 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/TU_USUARIO/pablogfdev-portfolio.git
cd pablogfdev-portfolio
```

2. Instala las dependencias:
```bash
npm install
```

3. Inicia el servidor de desarrollo:
```bash
npm run dev
```

4. Abre [http://localhost:4321](http://localhost:4321) en tu navegador

## 📝 Comandos Disponibles

| Comando                | Acción                                      |
| :--------------------- | :------------------------------------------ |
| `npm install`          | Instala las dependencias                    |
| `npm run dev`          | Inicia servidor local en `localhost:4321`   |
| `npm run build`        | Construye el sitio para producción en `./dist/` |
| `npm run preview`      | Vista previa de la build antes de desplegar |

## 🎨 Personalización

### Colores del Tema

Los colores están definidos en `src/styles/global.css`:

```css
@theme {
  --color-primary: #135bec;    /* Azul principal */
  --color-accent: #00f2ff;     /* Cyan de acento */
  --color-bg-light: #f6f6f8;   /* Fondo claro */
  --color-bg-dark: #0a0d14;    /* Fondo oscuro */
}
```

Usa las utilidades de Tailwind generadas automáticamente:
- `bg-primary`, `text-primary`, `border-primary`
- `bg-accent`, `text-accent`
- `bg-bg-dark`, etc.

Ver [STYLES_GUIDE.md](STYLES_GUIDE.md) para más detalles.

### Añadir Imágenes

Coloca tus imágenes en `public/images/`:
- `public/images/about/image.png` - Tu foto de perfil
- `public/images/projects/project-X.jpg` - Screenshots de proyectos

### Personalizar Contenido

Edita los componentes en `src/components/`:
- **Hero.astro** - Cambia nombre y descripción
- **About.astro** - Actualiza información personal
- **Experience.astro** - Añade tu experiencia laboral
- **Projects.astro** - Agrega tus proyectos
- **TechStack.astro** - Lista tus tecnologías

## 🚀 Deploy

### Vercel

```bash
npm run build
# Deploy desde la carpeta ./dist
```

### Netlify

```bash
npm run build
# Deploy desde la carpeta ./dist
```

### GitHub Pages

Consulta la [documentación de Astro](https://docs.astro.build/en/guides/deploy/github/) para configurar GitHub Actions.

## 🎯 Próximas Características

- [ ] Internacionalización (ES/EN)
- [ ] Toggle tema claro/oscuro
- [ ] Integración con CMS (opcional)
- [ ] Blog section
- [ ] Animaciones avanzadas con View Transitions

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 👤 Autor

**Pablo García**

- Portfolio: [tu-portfolio.com](https://tu-portfolio.com)
- GitHub: [@tu-usuario](https://github.com/tu-usuario)
- LinkedIn: [tu-perfil](https://linkedin.com/in/tu-perfil)

---

⭐ Si te gustó este proyecto, dale una estrella en GitHub!

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
