# 🎨 Guía de Estilos - Portfolio

## Colores Personalizados (Definidos en @theme)

### Colores disponibles:
```css
--color-primary: #135bec    → utilidades: bg-primary, text-primary, border-primary
--color-accent: #00f2ff     → utilidades: bg-accent, text-accent, border-accent
--color-bg-light: #f6f6f8   → utilidades: bg-bg-light
--color-bg-dark: #0a0d14    → utilidades: bg-bg-dark, border-bg-dark
```

### Fuente:
```css
--font-family-display → utilidad: font-display
```

## 📝 Cómo usar las utilidades

### Ejemplos de uso en componentes:

```astro
<!-- Fondo y texto con color primario -->
<div class="bg-primary text-white">

<!-- Hover con color primario -->
<a class="hover:text-primary">

<!-- Border con opacidad -->
<div class="border-primary/20">

<!-- Fondo con opacidad -->
<button class="bg-primary/90">

<!-- Color de acento -->
<div class="border-accent text-accent">

<!-- Fondos de tema -->
<body class="bg-bg-light dark:bg-bg-dark">

<!-- Fuente personalizada -->
<h1 class="font-display">
```

## 🔧 Ventajas de este enfoque:

1. **Cambio centralizado**: Modifica colores una sola vez en `global.css`
2. **Autocompletado**: Tu editor sugerirá `bg-primary`, `text-primary`, etc.
3. **Performance**: Clases estáticas generadas por Tailwind
4. **Limpieza**: Código más legible sin valores hexadecimales
5. **Escalable**: Fácil agregar nuevos colores

## 🎯 Cambiar colores del tema:

Para cambiar la paleta de colores, edita `src/styles/global.css`:

```css
@theme {
  --color-primary: #tu-nuevo-color;
  --color-accent: #tu-acento;
  /* etc... */
}
```

¡Y automáticamente se aplicará en todos los componentes! 🎉

## 📦 Clases personalizadas disponibles:

- `.glass-card` - Efecto glassmorphism
- `.lightsaber-line` - Línea con glow effect
- `.hyperspace-hover` - Efecto hover de transformación
