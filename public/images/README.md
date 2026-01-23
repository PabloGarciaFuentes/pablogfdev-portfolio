# Carpeta de Imágenes

Esta carpeta contiene las imágenes estáticas utilizadas en el portfolio.

## Estructura recomendada:

```
public/images/
├── profile.jpg          # Imagen de perfil para About section
├── hero-bg.jpg          # Imagen de fondo del Hero
├── projects/            # Imágenes de proyectos
│   ├── project-1.jpg
│   ├── project-2.jpg
│   └── project-3.jpg
└── icons/               # Iconos personalizados (opcional)
```

## Cómo usar las imágenes:

En los componentes Astro, referencia las imágenes desde la raíz:

```astro
<!-- Desde la carpeta public/ -->
<img src="/images/profile.jpg" alt="Profile" />

<!-- Para proyectos -->
<img src="/images/projects/project-1.jpg" alt="Project" />
```

## Imágenes requeridas:

### About Section:
- **profile.jpg** - Imagen de perfil (recomendado: 800x800px, formato: JPG/PNG/WebP)

### Projects Section:
- **project-1.jpg** - Screenshot proyecto 1 (recomendado: 1200x675px - ratio 16:9)
- **project-2.jpg** - Screenshot proyecto 2
- **project-3.jpg** - Screenshot proyecto 3

### Hero Section (opcional):
- **hero-bg.jpg** - Imagen de fondo personalizada (recomendado: 1920x1080px)

## Formatos recomendados:
- ✅ **WebP** - Mejor compresión (recomendado)
- ✅ **JPG** - Para fotografías
- ✅ **PNG** - Para imágenes con transparencia
- ✅ **SVG** - Para logos e iconos

## Optimización:
Asegúrate de optimizar las imágenes antes de subirlas:
- Usa herramientas como TinyPNG, Squoosh, o ImageOptim
- Mantén el tamaño de archivo razonable (<500KB por imagen)
